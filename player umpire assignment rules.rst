player umpire assignment rules:


- player needs to be available to umpire ( has the skill to do so )
- player needs to be available on game date ( is not away on given date)
- player needs to be available at game time  (is not playing a game at the same time)
- player needs to be available to umpire game by grade major
- player needs to be available to umpire game by grade minor

- set umpire capability score: 

    - the higher the umpire's own team grade is above the game grade major:

        - umpire team grade major is 2 above team grade major = 1.0
        - umpire team grade major is 3 above team grade major = 2.0
        - etc

    - the higher the umpires own team grade minor is above the game grade minor:
        - umpire is at or below team grade minor = 0.0
        - umpire is 1 above team grade minor = 0.1
        - umpire is 2 above team grade minor = 0.2
        - etc
    
    - personal skill bonus: If umpire A is better then umpire B but in a lower minor grade how is that reflected?
        - score in a range of 0 to +10 where:
        - 0 umpire can only umpire in default age group defined for umpire age group
        - +1 umpire can umpire default age group +1 year above
        - +2 umpire can umpire default age group and up to 2 years above 
        - etc

fill umpire roster bottom up in terms of grades and number of games umpired already:

- start with games at lowest grade i.e. 10s
- build umpire list based games major / minor grade for each game in grade
- clamp umpires of a score range to avoid top level umpire doing base level game
- from the lowest minor grade in this grade i.e. E assign umpire:
        - with the lowest score
        - with the lowest number of games umpired




