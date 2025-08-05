
# Predicting MLB Hall of Fame Inductions
**INFO 523 - Final Project**  
**Team Fastball** – Austin Cortopassi, David Pelley, Nathan Harville  
**College of Information Science, University of Arizona**

---

## Codebooks for Datasets

### Codebook for `People.csv`

- **playerID**: Unique identifier for the player  
- **playerID**: object

- **birthYear**: Year of birth  
- **birthYear**: object

- **birthMonth**: Month of birth  
- **birthMonth**: object

- **birthDay**: Day of birth  
- **birthDay**: object

- **nameFirst**: First name of the player  
- **nameFirst**: object

- **nameLast**: Last name of the player  
- **nameLast**: object

- **bats**: Batting hand (R, L, or B)  
- **bats**: object

- **throws**: Throwing hand (R or L)  
- **throws**: object

- **debut**: Date of MLB debut  
- **debut**: object

- **finalGame**: Date of final MLB game  
- **finalGame**: object

- **height**: Player height in inches  
- **height**: object

- **weight**: Player weight in pounds  
- **weight**: object

- **pos**: Primary position  
- **pos**: object

### Codebook for `Batting.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Season year  
- **yearID**: object

- **teamID**: Team identifier  
- **teamID**: object

- **G**: Games played  
- **G**: object

- **AB**: At-bats  
- **AB**: object

- **R**: Runs scored  
- **R**: object

- **H**: Hits  
- **H**: object

- **2B**: Doubles  
- **2B**: object

- **3B**: Triples  
- **3B**: object

- **HR**: Home runs  
- **HR**: object

- **RBI**: Runs batted in  
- **RBI**: object

- **SB**: Stolen bases  
- **SB**: object

- **BB**: Walks  
- **BB**: object

- **SO**: Strikeouts  
- **SO**: object

- **BA**: Batting average  
- **BA**: object

### Codebook for `Pitching.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Season year  
- **yearID**: object

- **teamID**: Team identifier  
- **teamID**: object

- **W**: Wins  
- **W**: object

- **L**: Losses  
- **L**: object

- **ERA**: Earned run average  
- **ERA**: object

- **G**: Games pitched  
- **G**: object

- **GS**: Games started  
- **GS**: object

- **SV**: Saves  
- **SV**: object

- **IPouts**: Outs pitched  
- **IPouts**: object

- **H**: Hits allowed  
- **H**: object

- **ER**: Earned runs  
- **ER**: object

- **HR**: Home runs allowed  
- **HR**: object

- **BB**: Walks allowed  
- **BB**: object

- **SO**: Strikeouts  
- **SO**: object

### Codebook for `Fielding.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Season year  
- **yearID**: object

- **teamID**: Team identifier  
- **teamID**: object

- **POS**: Fielding position  
- **POS**: object

- **G**: Games played  
- **G**: object

- **GS**: Games started  
- **GS**: object

- **PO**: Putouts  
- **PO**: object

- **A**: Assists  
- **A**: object

- **E**: Errors  
- **E**: object

- **DP**: Double plays  
- **DP**: object

### Codebook for `Teams.csv`

- **teamID**: Team identifier  
- **teamID**: object

- **yearID**: Season year  
- **yearID**: object

- **lgID**: League ID  
- **lgID**: object

- **G**: Games played  
- **G**: object

- **W**: Wins  
- **W**: object

- **L**: Losses  
- **L**: object

- **Rank**: Final standing  
- **Rank**: object

- **R**: Runs scored  
- **R**: object

- **RA**: Runs allowed  
- **RA**: object

- **HR**: Home runs  
- **HR**: object

- **ERA**: Earned run average  
- **ERA**: object

### Codebook for `BattingPost.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Season year  
- **yearID**: object

- **round**: Postseason round  
- **round**: object

- **teamID**: Team identifier  
- **teamID**: object

- **G**: Games played  
- **G**: object

- **AB**: At-bats  
- **AB**: object

- **R**: Runs scored  
- **R**: object

- **H**: Hits  
- **H**: object

- **2B**: Doubles  
- **2B**: object

- **3B**: Triples  
- **3B**: object

- **HR**: Home runs  
- **HR**: object

- **RBI**: Runs batted in  
- **RBI**: object

- **SB**: Stolen bases  
- **SB**: object

- **BB**: Walks  
- **BB**: object

- **SO**: Strikeouts  
- **SO**: object

### Codebook for `PitchingPost.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Season year  
- **yearID**: object

- **round**: Postseason round  
- **round**: object

- **teamID**: Team identifier  
- **teamID**: object

- **W**: Wins  
- **W**: object

- **L**: Losses  
- **L**: object

- **ERA**: Earned run average  
- **ERA**: object

- **G**: Games pitched  
- **G**: object

- **GS**: Games started  
- **GS**: object

- **SV**: Saves  
- **SV**: object

- **IPouts**: Outs pitched  
- **IPouts**: object

- **H**: Hits allowed  
- **H**: object

- **ER**: Earned runs  
- **ER**: object

- **HR**: Home runs allowed  
- **HR**: object

- **BB**: Walks allowed  
- **BB**: object

- **SO**: Strikeouts  
- **SO**: object

### Codebook for `FieldingPost.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Season year  
- **yearID**: object

- **round**: Postseason round  
- **round**: object

- **teamID**: Team identifier  
- **teamID**: object

- **POS**: Position played  
- **POS**: object

- **G**: Games played  
- **G**: object

- **GS**: Games started  
- **GS**: object

- **PO**: Putouts  
- **PO**: object

- **A**: Assists  
- **A**: object

- **E**: Errors  
- **E**: object

- **DP**: Double plays  
- **DP**: object

### Codebook for `HallOfFame.csv`

- **playerID**: Player identifier  
- **playerID**: object

- **yearID**: Year of voting  
- **yearID**: object

- **votedBy**: Voting body  
- **votedBy**: object

- **ballots**: Total number of ballots  
- **ballots**: object

- **votes**: Votes received  
- **votes**: object

- **inducted**: Induction result (Y/N)  
- **inducted**: object

- **category**: Role of candidate (player, manager, etc.)  
- **category**: object
