# 2.3 语法和语言的Chomsky层次结构

图Fig 2.3和2.5中的语法都很容易理解，而事实上一些简单的短语结构语法可以生成复杂的集合。然而，对于任何一组给定的语法通常都很难说是简单的。（虽然语法有无限的集合，但是在这我们还是说“一个给定集合的语法”。通过一个集合的语法，我们来解释任何做了同样工作的语法，并且不是过于复杂的。）理论上说如果一个集合最终可以生成（例如，通过一个程序），那么它就可以通过一个短语结构语法来生成，不过理论上没有表明这样做很容易，或者说语法是容易理解的。在这一节中要说明Manhattan龟的路劲尽量写出其语法，这些路劲中龟总是不能从起始点向西爬行的。（问题2.3）。

不考虑短语结构语法带来的智力问题，他们也表现出了基本和实际的问题。我们可以看出对这些集合没有普适的解析算法，而所有已知的特殊算法，要么效率很低要么就是很复杂；见3.4.2节。

也就是在尽可能的保持它们的生成力的情况下，约束短语结构语法超出控制的情况，这样就有了语法的Chomsky层次结构。这种层次结构分为了四种类型的语法，编号为0到3；引入第5种类型，也就是被称为类型4的类型，是有意义的。0型语法是（无限制的）短语结构语法，我们已经看到了它的例子。其他类型源于越来越被限制的语法规则中被允许的形式。每一种限制条件都带来深远的影响；最终语法逐渐变得更易于理解和掌握，但也逐渐不那么强大。幸运的是，这些不那么强大的语法依旧十分有用，甚至实际上比0型更有用。

我们现在先按顺序来看看前三个类型，然后接着在看看琐碎但有用的第四个类型。

生成0型语言的完全不同的方法，见示例Geffert[395]。