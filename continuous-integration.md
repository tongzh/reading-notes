# 持续集成：软件质量改进和风险降低之道

## 主旨
这本书讲的是关于持续集成的原则和实践。Martin Fowler关于CI的[热门文章](https://martinfowler.com/articles/continuousIntegration.html)发表于2006年，这本书作于2007年，虽然十年间CI的工具已经发生了不少变迁，但本书中提到的基本原则和实践仍然值得借鉴，而且书中提到的关于CI未来发展方向的论述也得到了验证。

## 什么是持续集成

Martin Fowler在其文章中将CI描述为：

> 一种软件开发实践，即团队的成员经常集成他们的工作，通常每个成员每天至少集成一次——这导致每天发生多次集成。每次集成都通过自动化的构建（包括测试）来验证，从而尽快地检测出集成错误。许多团队发现，这个过程会大大减少集成问题，让团队能够更快地开发出一致的软件。

这意味着持续集成其实是一系列实践的集合，例如：

* 所有开发者均先执行个人构建，在将代码提交到代码库中，以保证集成构建不会失败。
* 开发者每天至少向代码库提交一次代码。
* 集成构建每天会在一台独立的机器上执行多次。
* 每次构建必须100%通过测试。
* 构建必须有产物，如可部署的包等。
* 修复失败的构建是最高优先级的事情。
* 构建中包含代码复查，生成如代码质量报告或依赖分析报告等，作为改进的参考。

关于CI：

* CI实践中提倡自动化，因为集成本身就是一个需要多次重复的过程，自动化有利于降低出错的可能性。
* 使用CI的一个明显好处是能够得到快速反馈，这与重构、TDD等实践的理念是一致的，即进行小的变更，而CI为这些变更提供了一张安全网。
* 关于“**持续**”一词的解读，其实更应理解为“**经常**”集成。



##  
