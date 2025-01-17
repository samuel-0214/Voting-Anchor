# Solana Voting dApp
A decentralized voting application built on Solana using Anchor framework.

## Features
Create polls with customizable descriptions and time periods
Add multiple candidates to each poll
Vote for candidates in active polls
Track vote counts for each candidate
PDA-based account structure for secure and efficient data management

## Program Structure
The program consists of three main components:

### Poll Creation (initialize_poll)
Create new polls with unique IDs
Set poll description and duration
Track number of candidates

### Candidate Registration (initialize_candidate)
Add candidates to existing polls
Initialize vote counter for each candidate
Update poll's candidate count

### Voting Mechanism (vote)
Cast votes for candidates
Update vote counts securely
PDA-based account validation
