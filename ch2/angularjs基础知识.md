1. Angular表达式与JavaScript表达式的区别
	1. Angular中所有表达式的值都来源于$scope对象，由该对象以添加属性的方式统一进行设置，
	并不像在传统的JavaScript中，可以由全局的window对象来调用表达式。
	2. Angular中表达式的容错能力很强，可以允许值出现null和undefined情况，
	而不会像在传统JavaScript中那样抛出异常代码。
	3. 由于Angular中表达式的值的来源固定，因此，在表达式中，不允许出现各类判断和循环语句，
	这一点也与传统的JavaScript区别较大，在使用时需要注意。
	4. Angular中表达式的值可以是使用管道符“|”进行格式化显示的数值，
	这也是不同于传统的JavaScript中表达式的一个很明显的特征
 	