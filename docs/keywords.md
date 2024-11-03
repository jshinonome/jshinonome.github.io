---
title: Keywords
nav_order: 7
---

<!-- prettier-ignore-start -->

# Keywords
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<!-- prettier-ignore-end -->

---

## Unary Keywords

| keyword   | description                                 |
| --------- | ------------------------------------------- |
| abs       | absolute value                              |
| all       | true if all truthy values                   |
| any       | true if any truthy values                   |
| acos      | the inverse cosine                          |
| acosh     | the inverse hyperbolic cosine               |
| asin      | the inverse sine                            |
| asinh     | the inverse hyperbolic sine                 |
| atan      | the inverse tangent                         |
| atanh     | the inverse hyperbolic tangent              |
| asc       | sort in ascending order                     |
| bfill     | backward fill nulls                         |
| cbrt      | cube root                                   |
| ceil      | rounds up to the nearest integer            |
| cos       | cosine                                      |
| cosh      | hyperbolic cosine                           |
| cot       | cotangent                                   |
| count     | count                                       |
| ccount    | cumulative count                            |
| cmax      | cumulative max                              |
| cmin      | cumulative min                              |
| cproduct  | cumulative product                          |
| csum      | cumulative sum                              |
| desc      | sort in descending order                    |
| diff      | difference between shifted items            |
| exp       | exponential                                 |
| first     | first scalar of list                        |
| flatten   | flatten a list or string                    |
| floor     | rounds down to the nearest integer value    |
| fill      | forward fill nulls                          |
| hash      | `nyi`                                       |
| interp    | interpolate                                 |
| kurtosis  | fill null values using linear interpolation |
| last      | last scalar of list                         |
| ln        | the natural logarithm                       |
| log10     | the 10 logarithm                            |
| log1p     | the natural logarithm plus one              |
| lowercase | lowercase                                   |
| trims     | trim start of strings                       |
| max       | max of a list                               |
| mean      | mean of a list                              |
| median    | median of a list                            |
| min       | min of a list                               |
| neg       | negate                                      |
| next      | shift to next value                         |
| mode      | the most occurring value(s)                 |
| not       | negate a boolean value                      |
| null      | if values are null                          |
| pc        | percent change                              |
| prev      | shift to previous value                     |
| product   | product                                     |
| rank      | assign ranks to values                      |
| reverse   | reverse a list                              |
| trime     | trim end of strings                         |
| shuffle   | shuffle a list                              |
| sign      | the element-wise indication of the sign     |
| sin       | sine                                        |
| sinh      | hyperbolic sine                             |
| skew      | the sample skewness of a list               |
| sqrt      | square root                                 |
| std0      | standard deviation with ddof=0              |
| std1      | standard deviation with ddof=1              |
| string    | `removed`                                   |
| trim      | trim start and end of strings               |
| sum       | sum of a list                               |
| tan       | tangent                                     |
| tanh      | hyperbolic tangent                          |
| unique    | unique values of a list                     |
| uc        | unique count                                |
| uppercase | uppercase                                   |
| var0      | variance with ddof=0                        |
| var1      | variance with ddof=1                        |
| cols      | column names of a dataframe                 |
| describe  | summary statistics for a dataframe          |
| enlist    | as scalar of a list                         |
| eval      | evaluate a string or a list                 |
| exit      | exit with a return code                     |
| filter    | cast booleans to indices                    |
| flag      | check flag of a list                        |
| get       | `removed`                                   |
| getenv    | get environment value                       |
| exists    | if a path exists                            |
| hdel      | remove a path                               |
| hsym      | `removed`                                   |
| key       | keys of a dictionary                        |
| schema    | schema of a dataframe                       |
| seed      | set a random seed                           |
| show      | print a value to stdout                     |
| system    | execute a string system command             |
| tables    | `nyi`                                       |
| range     | generate a continue list                    |
| transpose | transpose a dataframe                       |
| type      | data type name                              |
| utc       | `nyi`                                       |

## Binary Keywords

| keyword       | description                                      |
| ------------- | ------------------------------------------------ |
| between       | if between given lower and upper bounds          |
| bottom        | the n smallest elements                          |
| corr0         | the pearson's correlation with ddof=0            |
| corr1         | the pearson's correlation with ddof=1            |
| cov0          | the covariance with ddof=0                       |
| cov1          | the covariance with ddof=1                       |
| cross         | cartesian product                                |
| differ        | set difference                                   |
| ewmmean       | exponentially-weighted moving average            |
| ewmstd        | exponentially-weighted moving standard deviation |
| ewmvar        | exponentially-weighted moving variance           |
| in            | if presents in other list                        |
| intersect     | set intersection                                 |
| like          | if matches regular expression                    |
| log           | logarithm to a given base                        |
| matches       | count regular expression matches                 |
| mod           | modulus                                          |
| join          | join strings                                     |
| rollingmax    | moving max                                       |
| rollingmean   | moving mean                                      |
| rollingmedian | moving median                                    |
| rollingmin    | moving min                                       |
| rollingskew   | moving skewness                                  |
| rollingstd0   | moving standard deviation(ddof=0)                |
| rollingstd1   | moving standard deviation(ddof=1)                |
| rollingsum    | moving sum                                       |
| rollingvar0   | moving variance(ddof=0)                          |
| rollingvar1   | moving variance(ddof=1)                          |
| pow           | exponentiation                                   |
| quantile      | quantile                                         |
| reshape       | reshape                                          |
| rotate        | rotate elements/records                          |
| round         | round float values                               |
| shift         | shift elements                                   |
| split         | split strings                                    |
| ss            | search for leftmost suitable sorted indices      |
| ssr           | search for rightmost suitable sorted indices     |
| top           | the n largest elements                           |
| union         | set union                                        |
| wmean         | weighted mean                                    |
| wsum          | weighted sum                                     |
| extend        | extend dataframe vertically without reallocation |
| hstack        | extend dataframe horizontally                    |
| parallel      | parallel each                                    |
| set           | `nyi`                                            |
| setenv        | `nyi`                                            |
| vstack        | extend dataframe vertically with reallocation    |
| xasc          | sort dataframe ascending                         |
| xbar          | group values                                     |
| xdesc         | sort dataframe descending                        |
| xreorder      | reorder dataframe columns                        |
| xrename       | rename dataframe columns                         |
| timeit        | time execution                                   |
| console       | config console output                            |

## Test Keywords

| keyword | description     | example      |
| ------- | --------------- | ------------ |
| assert  | assert if true  | `assert 1=1` |
| equal   | assert if equal | `1 equal 1`  |
| fail    | `nyi`           |              |

## IO Keywords

| keyword    | description                       | usage                                                               |
| ---------- | --------------------------------- | ------------------------------------------------------------------- |
| hopen      | open a handle to other process    |                                                                     |
| hclose     | close a handle to other process   |                                                                     |
| ikdb       | `nyi`                             |                                                                     |
| rbin       | `nyi`                             |                                                                     |
| rcsv       | read csv                          | `rcsv[filepath;hasHeader;sep;ignoreErrors;dataTypeDict]`            |
| rdatabase  | `nyi`                             |                                                                     |
| rexcel     | `nyi`                             |                                                                     |
| rjson      | read json                         | `rjson[filepath;dataTypeDict]`                                      |
| rparquet   | read parquet                      | `rparquet[filepath;rows;rechunk;columns]`                           |
| rtxt       | read text                         | `rtxt[filepath]`                                                    |
| wbin       | `nyi`                             |                                                                     |
| wcsv       | write csv                         | `wcsv[filepath;dataframe;sep]`                                      |
| wdatabase  | `nyi`                             |                                                                     |
| wexcel     | `nyi`                             |                                                                     |
| wjson      | write json                        | `wjson[filepath;dataframe]`                                         |
| wparquet   | write parquet                     | `wparquet[filepath;dataframe;compressionLevel]`                     |
| wtxt       | write text                        | `wtxt[filepath;string;appendToFile]`                                |
| wpartition | write partition                   | `wpartition[dbPath;partition;table_name;dataframe;columns;rechunk]` |
| load       | load parquet partitioned database | `load dbPath`                                                       |

## Matrix Keywords

| keyword | description         |
| ------- | ------------------- |
| inv     | inverse of a matrix |

## SQL Other Keywords

| keyword         | description                              | usage                            |
| --------------- | ---------------------------------------- | -------------------------------- |
| clip            | set values outside to the boundary value | `clip[num;lower;upper]`          |
| concat          | concatenate strings                      | `concat[delimiter;str;str]`      |
| replace         | replace matched regular expression       | `replace[str;regex;replacement]` |
| rolling         | `nyi`                                    |                                  |
| rollingquantile | mquantile                                | `mquantile[quantile;size;num]`   |

## SQL Keywords

| keyword | description            |
| ------- | ---------------------- |
| select  | select columns         |
| update  | update columns/records |
| delete  | delete columns/records |
| by      | by columns             |
| from    | from dataframe         |
| where   | where clause           |
| aby     | aggregate by columns   |

## SQL Join Keywords

| keyword | description                                                                     |
| ------- | ------------------------------------------------------------------------------- |
| aj      | as of join                                                                      |
| cj      | cross join, returns the Cartesian product of rows from both tables              |
| ij      | inner join                                                                      |
| lj      | left join                                                                       |
| fj      | full join, returns all rows when there is a match in either left or right table |
| pj      | `nyi`                                                                           |
| uj      | `nyi`                                                                           |
| wj      | `nyi`                                                                           |
| anti    | filter rows that have a match in the right table                                |
| semi    | filter rows that not have a match in the right table.                           |

## Dataframe Keywords

| keyword | description         | usage                                                             |
| ------- | ------------------- | ----------------------------------------------------------------- |
| unpivot | unpivot a dataframe | `unpivot[dataframe;indexColumns;valueColumns]`                    |
| pivot   | pivot a dataframe   | `pivot[dataframe;indexColumns;extractColumns;valueColumns;aggFn]` |

aggFn can be

- first
- last
- max
- mean
- median
- min
- count
- sum

```
t: ([]date:100?2024.11.03+range 3;sym:100?`a`b`c;qty:100?10);

p: pivot[t; `date; `sym; `qty; `sum];

unpivot[p; `date; `a`b`c]
```
