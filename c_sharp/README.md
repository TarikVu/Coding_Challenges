# Coding Challenges in C#
These coding challenges are not mine.  Their respective sources are listed below. 

## Table of Contents
1. [XUnit Testing](#tests)
1. [Original Sources](#orig)
1. [References](#ref)

## <a name="tests"></a> XUnit Testing
Testing done for these coding challenges are conducted using XUnit.
These tests are a combination of my own tests as well as tests supplied by the original challenge.
See **ItemGroups** under c_sharp.csproj for packages installd via NuGet.

## <a name="orig"></a> Original Sources

- [Binary Tree - Max Depth (Easy)](https://leetcode.com/problems/maximum-depth-of-binary-tree/description/)

- [Icecream Parlor (Intermediate)](https://www.hackerrank.com/challenges/icecream-parlor/problem?isFullScreen=true)

- [Plus One (Easy)](https://leetcode.com/problems/plus-one/)

- [Roman to Integer (Easy)](https://leetcode.com/problems/roman-to-integer/description/) 

- [Two Sum (Easy)](https://leetcode.com/problems/two-sum/) 

- [Valid Parenthesis (Easy)](https://leetcode.com/problems/valid-parentheses/description/)



## <a name="refs"></a> References 

[Using XUnit Testing in VS Code](https://www.youtube.com/watch?v=HQmbAdjuB88)

[Commands & filtering for Xunit testing](https://learn.microsoft.com/en-us/dotnet/core/testing/selective-unit-tests?pivots=xunit)
- dotnet test : Run all Xunit Tests
- dotnet test --filter _filter_ : Run Unit tests given a filter. **Tests are filtered by their respective challenge**

[Creating the Xunit testing library](https://www.youtube.com/watch?v=04nzwCE_nw0)
- [Documentation link](https://code.visualstudio.com/docs/csharp/testing)
- dotnet new xunit -o _library name_
- dotnet add _location of your test csproj file_ reference _location of the csproj file for project to be tested_

[NuGet Package Manager retreival error fix](https://stackoverflow.com/questions/58108809/versioning-information-could-not-be-retrieved-from-the-nuget-package-repository)


