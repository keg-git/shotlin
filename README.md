# Shotlin
- this project will start out as a Sporting Clay score card written in Kotlin
- may branch out to other shooting sports after


## Sporting Clays
### Data Structures
    - User
        - username
        - range records
            - need to figure out how to store these
            - probably best to store them as cards
    - Range
        - name
        - location
        - course
            - name
            - stations (16? usually)
                - has 2 launchers with descriptions of what kind of shot is being performed
                - previously report or true pair
                - revision date
    - cards
        - these will keep the scores
        - should these be separate from the Range data structure? probably different just bare bones with a reference to range and course
        - range
        - course
        - stations
            - date
            - hits and misses
            - record hits and misses as 0s and 1s in an integer on each station (long or reg not sure yet)
            - record pair data in a string or character array using X / \ O as markers for pairs when taken
