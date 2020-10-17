[![Actions Status](https://github.com/JohnCampionJr/MiniScaffoldCSharp/workflows/.NET%20Core%20Coverage%20(Ubuntu)/badge.svg)](https://github.com/JohnCampionJr/MiniScaffoldCSharp/actions)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/f2cec74cb05346b88e9bb54488198c54)](https://www.codacy.com/gh/JohnCampionJr/MiniScaffoldCSharp/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=JohnCampionJr/MiniScaffoldCSharp&amp;utm_campaign=Badge_Grade)
[![codecov](https://codecov.io/gh/JohnCampionJr/MiniScaffoldCSharp/branch/main/graph/badge.svg?token=OIGAKLPE23)](undefined)

# MiniScaffoldCSharp
This a mini scaffold setup, ready to use to build .NET Core projects.  I put this together for my own use,
both to use and to learn concepts.  It will also save time in future projects.

Inspired by [MiniScaffold](https://github.com/TheAngryByrd/MiniScaffold)

## Features
- .NET Core 3.1
- xUnit Testing / Shouldly Assertions
- Code Coverage with Coverlet and reporting to codecov
- Git ignore / attributes
- Editor Config
- GitHub Actions - testing, coverage, publishing, multi-os testing
- [Pull Reqest Labeler](https://github.com/marketplace/actions/pr-labeler)
- [Release Drafter](https://github.com/marketplace/actions/release-drafter)

## To-Do

- [ ] Build a VS Template 

## Recommended Settings
**GitHub** 
Enable Dependabot updates

**WIP** - _GitHub Integration_ - Enable on GH  
Recommended to block PRs for WIP items

**Codacy** - _GitHub Integration_ - Configure on codacy.com    
Extra comments in PR are major visual distractions and make conversation harder.  
 
- PR Status: Enabled
- PR Comments: Disabled
- PR Summary: Disabled

**Codecov** - _GitHub Integration_ - Configure on codecov.io
For private repositories, setup your CODECOV_TOKEN in Secrets

### References 
[CodeCoverage.runsettings](https://docs.microsoft.com/en-us/visualstudio/test/customizing-code-coverage-analysis?view=vs-2019)
[Solution Structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)

### Thanks

[MongoFramework](https://github.com/TurnerSoftware/MongoFramework) - Learned much about good workflows, and @turnerj's version code ans build script were much appreciated
[Dotnetlayout](https://gist.github.com/davidfowl/ed7564297c61fe9ab814) - @davidfowl's structure was very helpful