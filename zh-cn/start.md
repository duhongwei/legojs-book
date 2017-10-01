# 开始

把hotloadjs看作js模块管理器更为合适。Hotloadjs把精力放在依赖处理和热加载上，不负责具体加载文件。因为具体项目的环境都不一样，开发者的习惯也不一样，实现通用的自动加载文件很复杂，也很难令所有人满意。相反的，如果对具体项目具体实现加载文件的功能会很简单。

Hotloadjs 只用于浏览器环境，参照了ADM规范，详见 [规范](specs.md)

hotloadjs 支持ie6+ 和现在浏览器

Hotloadjs 规定:模块分为两个状态，waiting和ready。

hotloadjs的理念第一是简单，每二是简单，第三还是简单。hotloadjs注重开发过程的舒适度，在浏览器中查看的所有代码都可以立即定位到具体文件，文件所有修改都是无需编译就能立即同步到浏览器。相对于目前大环境，hotloadjs走了一条不寻常的道路。hotloadjs尽量采用直接的，浏览器原生可以理解的方式进行。

hotloadjs是一个前端解决方案，目前发布了js热加载这部分，这部分可以独立使用。代码只有一个js,相较于代码，更多的是设计思想。代码有形，思想无形，设计思想可以更好的应对实际情况。

如果有什么问题可以在[holoadjs issue](https://github.com/duhongwei/hotloadjs/issues) 上提出。如果觉得有用，慷慨您的鼓励，我会更快的发布legojs的资源管理等其它内容。

接下来，我们将会做更深入地探讨。无规矩不成方圆，首先从[规范](specs.md)说起