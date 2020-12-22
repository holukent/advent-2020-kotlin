## Advent of Code 2020 Solutions in Kotlin

[![license](https://img.shields.io/github/license/tginsberg/advent-2020-kotlin)]()

This repo is my personal attempt at solving the [Advent of Code 2020](http://adventofcode.com/2020) set of problems with the Kotlin programming language.

I am trying to solve these on the day they are posted with clear, idiomatic solutions. That means in some cases I will sacrifice performance for a more clear solution. While I will endeavour to have these done day-of I can't promise it because work and life can get in the way. Plus, some of these problems can get quite involved, so solving it clearly and writing up an explanation might take me longer than a day. We'll see how it goes! :)

Past years, also in Kotlin:
 * 2017 - [GitHub](https://github.com/tginsberg/advent-2017-kotlin/) and [Blog Posts](https://todd.ginsberg.com/post/advent-of-code/2017/)
 * 2018 - [GitHub](https://github.com/tginsberg/advent-2018-kotlin/) and [Blog Posts](https://todd.ginsberg.com/post/advent-of-code/2018/)
 * 2019 - [GitHub](https://github.com/tginsberg/advent-2019-kotlin/) and [Blog Posts](https://todd.ginsberg.com/post/advent-of-code/2019/)

#### Daily Solution Index for 2020
|   Day   | Title                                         |  Links                                       |
| --------|-----------------------------------------------|--------------------------------------------- |
|    1    |  Report Repair                                | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day1/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day01.kt) [\[AoC\]](http://adventofcode.com/2020/day/1) |
|    2    |  Password Philosophy                          | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day2/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day02.kt) [\[AoC\]](http://adventofcode.com/2020/day/2) |
|    3    |  Toboggan Trajectory                          | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day3/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day03.kt) [\[AoC\]](http://adventofcode.com/2020/day/3) |
|    4    |  Passport Processing                          | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day4/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day04.kt) [\[AoC\]](http://adventofcode.com/2020/day/4) |
|    5    |  Binary Boarding                              | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day5/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day05.kt) [\[AoC\]](http://adventofcode.com/2020/day/5) |
|    6    |  Custom Customs                               | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day6/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day06.kt) [\[AoC\]](http://adventofcode.com/2020/day/6) |
|    7    |  Handy Haversacks                             | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day7/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day07.kt) [\[AoC\]](http://adventofcode.com/2020/day/7) |
|    8    |  Handheld Halting                             | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day8/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day08.kt) [\[AoC\]](http://adventofcode.com/2020/day/8) |
|    9    |  Encoding Error                               | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day9/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day09.kt) [\[AoC\]](http://adventofcode.com/2020/day/9) |
|    10   |  Adapter Array                                | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day10/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day10.kt) [\[AoC\]](http://adventofcode.com/2020/day/10) |
|    11   |  Seating System                               | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day11/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day11.kt) [\[AoC\]](http://adventofcode.com/2020/day/11) |
|    12   |  Rain Risk                                    | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day12/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day12.kt) [\[AoC\]](http://adventofcode.com/2020/day/12) |
|    13   |  Shuttle Search                               | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day13/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day13.kt) [\[AoC\]](http://adventofcode.com/2020/day/13) |
|    14   |  Docking Data                                 | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day14/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day14.kt) [\[AoC\]](http://adventofcode.com/2020/day/14) |
|    15   |  Rambunctious Recitation                      | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day15/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day15.kt) [\[AoC\]](http://adventofcode.com/2020/day/15) |
|    16   |  Ticket Translation                           | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day16/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day16.kt) [\[AoC\]](http://adventofcode.com/2020/day/16) |
|    17   |  Conway Cubes                                 | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day17/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day17.kt) [\[AoC\]](http://adventofcode.com/2020/day/17) |
|    18   |  Operation Order                              | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day18/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day18.kt) [\[AoC\]](http://adventofcode.com/2020/day/18) |
|    19   |  Monster Messages                             | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day19/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day19.kt) [\[AoC\]](http://adventofcode.com/2020/day/19) |
|    20   |  Jurassic Jigsaw                              | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day20/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day20.kt) [\[AoC\]](http://adventofcode.com/2020/day/20) |
|    21   |  Allergen Assessment                          | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day21/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day21.kt) [\[AoC\]](http://adventofcode.com/2020/day/21) |
|    22   |  Crab Combat                                  | [\[Blog Post\]](https://todd.ginsberg.com/post/advent-of-code/2020/day22/) [\[Code\]](https://github.com/tginsberg/advent-2020-kotlin/blob/master/src/main/kotlin/com/ginsberg/advent2020/Day22.kt) [\[AoC\]](http://adventofcode.com/2020/day/22) |
     
    
Copyright &copy; 2020 by Todd Ginsberg.
