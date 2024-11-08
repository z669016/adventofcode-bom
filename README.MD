# Advent Of Code Bill of Materials
Initial version created in 2022 as prep for this year's [AoC](https://adventofcode.com/). Next to the fact
that I'd like to refresh my problem-solving skills, I'd also like to learn a bit more on Maven. Also, because
GitHub's [dependabot](https://github.com/dependabot) regulars comes with warning on library upgrades I should
do. Hopefully this helps a bit addressing that issue as well. So, yes, I'm trying to kill two birds in one 
stone.

I took the dependency list from my AoC 2021 project and turned that into a BOM file. 

## Version 1.1
Added ```com.github.dpaukov.combinatoricslib3``` which is a great library to generate combinations or 
permutations from a list of elements. I introduced this library for AoC 2016, and apparently forgot about it, as I 
also implemented a Permutator (by copying some code from the Internet, sorry I cannot remember the source);

## Version 1.1.1
Updated the AOC library to 1.4.18 (Josephus problem for AoC 2016 day 19)

## Version 1.2.0
Added com.google.guava to add missing streaming methods like ```Streams.zip``` to enable more functional
programming based solutions for the puzzles.
Upgraded several libraries to the latest versions, incl jackson to solve a security vulnerability.

## Version 1.2.1
Bumped AoC library (added transform to Point and Point3D)

## Version 1.2.2
Bumped AoC library (added Size class from AoC 2018)

## Version 1.2.3
Bumped AoC library (added Factors.gcm() and Factors.lcm())

## Version 1.2.4
Bumped algorithms library (added TSP.longestPath)

## Version 1.3.0
Bumped aoc library to 1.5.0 with some classes removed (already available elsewhere)

## Version 1.3.1
Bumped aoc library to 1.5.1

## Version 1.3.1
Bumped aoc library to 1.5.2

## Version 1.5.0
Bumped many libraries ;-)

## Version 1.5.1
Bumped many libraries ;-)



