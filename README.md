# aw01

请参考课件内给的示例（[sa-spring/cashregister](https://github.com/sa-spring/cashregister) ），用Spring container的三种configuration中的任意一种，将[AsciiPanel](https://github.com/trystan/AsciiPanel)改造为一个构件系统，要求可以创建`AsciiPanel`和不同的`AsciiFont`构件，并将其进行组装并运行。

例如，可将`CP437_9x16`的`AsciiFont`组装进`AsciiPanel`，

![](https://www.plantuml.com/plantuml/png/SoWkIImgAStDuOfsB4xEp0n8p4lDYLNGrRLJW0YuvUULw3e7c1YRnrjM69h5SZcavgK0rGC0)

或将`CP437_8x8`的`AsciiFont`组装进`AsciiPanel`。

![](https://www.plantuml.com/plantuml/png/SoWkIImgAStDuOfsB4xEp0n8p4lDYLNGrRLJW0YuvUULw3e7c1YRnrjKMCHoEQJcfG2L0m00)

要求Maven工程项目代码，参考示例（[sa-spring/cashregister](https://github.com/sa-spring/cashregister) ），实现至少两个不同的构件系统configration，且包含可直接运行的main函数。

