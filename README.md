## Spreadsheet to calculate sizing of Aerospike

1. [What is it?](#what-is-it)
2. [How to use?](#how-to-use)
    1. [Input parameters are balanced](#input-parameters-are-balanced)
    2. [Input parameters are slightly unbalanced](#input-parameters-are-slightly-unbalanced)
    3. [Input parameters are unbalanced](#input-parameters-are-unbalanced)
3. [License](#license)

### What is it?
This is a spreadsheet that helps to estimate a number of servers and their configuration while sizing [Aerospike](http://www.aerospike.com) according to the [official documentation](http://www.aerospike.com/docs/operations/plan/capacity/).

### How to use?

Just start playing with *INPUT* paratemers and look at how the number of required servers, their configuration as well as different kinds of overhead change.

#### Input parameters are balanced


Input parameters are considered to be *balanced* if the number of required servers is the same for both RAM as well as SSD.

#### Input parameters are slightly unbalanced

Input parameters are considered to be *slightly unbalanced* if the difference between the number of required servers for RAM and SSD is one.

#### Input parameters are unbalanced

Input parameters are considered to be *unbalanced* if the difference between the number of reuired servers for RAM and SSD is more than one.

### License

The spreadsheet is distributed under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).
