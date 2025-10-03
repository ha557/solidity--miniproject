# Simple Voting DApp

This contract allows users to vote for candidates.  
It uses a mapping to store vote counts for each candidate.

## Features
- Add candidates at deployment
- Anyone can vote once per candidate
- Get total votes per candidate

## How to Deploy
1. Open Remix IDE.
2. Create file `Voting.sol`.
3. Paste code and compile.
4. Deploy → input candidate names (e.g., ["Alice","Bob","Charlie"]).
5. Call `vote("Alice")`.
6. Call `getVotes("Alice")` → returns number of votes.

## Example Usage
- Deploy with ["Alice","Bob"].
- Call `vote("Bob")`.
- `getVotes("Bob")` → 1.
