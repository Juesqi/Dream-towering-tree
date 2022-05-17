
The first half of the 20th century saw the world's population almost double.
20世纪上半叶，世界人口几乎翻倍
Global trade and transit networks became interconnected like never before,
全球贸易和运输更加紧密
and the sophistication of our engineering and scientific endeavors reached new heights
工程和科学的复杂度也达到新高
And it was this explosion of complexity, bureaucracy, and ultimately data,
复杂度的增高导致数据量暴增

that drove an increasing need for automation and computation.
人们需要更多自动化 更强的计算能力

Soon those cabinet-sized electro-mechanical computers grew into room-sized behemoths
很快，柜子大小的计算机变成房间大小

One of the largest electro-mechanical computers built was the Harvard Mark I,
最大的机电计算机之一是 哈佛马克一号

completed in 1944 by IBM for the Allies during World War 2.
IBM 在 1944 完成建造，给二战同盟国建造的.

One of the earliest uses for this technology was running simulations for the Manhattan Project.
这台机器最早的用途之一 是给"曼哈顿计划"跑模拟

The brains of these huge electro-mechanical beasts were relays:
这台机器的大脑是"继电器"

electrically-controlled mechanical switches.
继电器是：用电控制的机械开关

Unfortunately, the mechanical arm inside of a relay *has mass*,
不幸的是，继电器内的机械臂 *有质量*

and therefore can't move instantly between opened and closed states.
因此无法快速开关

The Harvard Mark I could do 3 additions or subtractions per second;
哈佛马克一号，1 秒能做 3 次加法或减法运算


And more complex operations, like a trigonometric function, could take over a minute.
更复杂的操作 比如三角函数，可能要一分钟以上

In addition to slow switching speed, another limitation was wear and tear.
除了速度慢，另一个限制是齿轮磨损

Anything mechanical that moves will wear over time.
任何会动的机械都会随时间磨损

Some things break entirely, and other things start getting sticky, slow, and just plain unreliable.
有些部件会完全损坏，有些则是变黏，变慢，变得不可靠

And as the number of relays increases, the probability of a failure increases too.
并且随着继电器数量增加，故障概率也会增加

The Harvard Mark I had roughly 3500 relays.
哈佛马克一号 有大约 3500 个继电器

you'd have to replace, on average, one faulty relay every day!
也意味着平均每天得换一个故障继电器！
And that's not all engineers had to contend with.
而且还有更多其他问题要考虑
These huge, dark, and warm machines also attracted insects.
这些巨大，黑色，温暖的机器也会吸引昆虫
In September 1947, operators on the Harvard Mark II pulled a dead moth from a malfunctioning relay.
1947年9月，哈佛马克2型的操作员从故障继电器中，拔出一只死虫
Grace Hopper who we'll talk more about in a later episode noted,
Grace Hopper（这位我们以后还会提到）曾说
"From then on, when anything went wrong with a computer,
"从那时起，每当电脑出了问题，
we said it had bugs in it."
我们就说它出了 bug（虫子）"
And that's where we get the term computer bug.
这就是术语 "bug" 的来源
It was clear that a faster, more reliable alternative to electro-mechanical relays was needed
显然，如果想进一步提高计算能力
if computing was going to advance further,
我们需要更快更可靠的东西，来替代继电器
and fortunately that alternative already existed!
幸运的是，替代品已经存在了！
In 1904, English physicist John Ambrose Fleming
在 1904 年，英国物理学家 "约翰·安布罗斯·弗莱明"

developed a new electrical component called a thermionic valve
开发了一种新的电子组件，叫"热电子管"

- this was the first vacuum tube.
-这是世上第一个真空管

One of the electrodes could be heated, which would cause it to emit electrons
其中一个电极可以加热，从而发射电子
– a process called thermionic emission.
-这叫 "热电子发射"
The other electrode could then attract these electrons to create the flow of our electric faucet,
另一个电极会吸引电子，形成"电龙头"的电流
but only if it was positively charged
但只有带正电才行
- if it had a negative or neutral charge, the electrons would no longer be attracted across the vacuum
- 如果带负电荷或中性电荷，电子就没办法被吸引，越过真空区域
so no current would flow.
因此没有电流
An electronic component that permits the one-way flow of current is called a diode,
电流只能单向流动的电子部件叫 "二极管"
but what was really needed was a switch to help turn this flow on and off.
但我们需要的是，一个能开关电流的东西
Luckily, shortly after, in 1906, American inventor Lee de Forest
幸运的是，不久之后在 1906 年，美国发明家 "李·德富雷斯特"
added a third "control" electrode that sits between the two electrodes in Fleming's design.
他在"弗莱明"设计的两个电极之间，加入了第三个 "控制" 电极
By applying a positive charge to the control electrode, it would permit the flow of electrons as before.
向"控制"电极施加正电荷，它会允许电子流动
But if the control electrode was given a negative charge,
但如果施加负电荷
it would prevent the flow of electrons.
它会阻止电子流动

So by manipulating the control wire, one could open or close the circuit.
因此通过控制线路，可以断开或闭合电路

It's pretty much the same thing as a relay
和继电器的功能一样

- but importantly, vacuum tubes have no moving parts.
- 但重要的是，真空管内没有会动的组件
This meant there was less wear,
这意味着更少的磨损
and more importantly, they could switch thousands of times per second.
更重要的是，每秒可以开闭数千次
These triode vacuum tubes would become the basis of radio, long distance telephone,
因此这些"三极真空管"成为了无线电，长途电话

and many other electronic devices for nearly a half century.
以及其他电子设备的基础，持续了接近半个世纪

I should note here that vacuum tubes weren't perfect
我应该提到，真空管不是完美的
- they're kind of fragile, and can burn out like light bulbs,
-它们有点脆弱，并且像灯泡一样会烧坏
they were a big improvement over mechanical relays.
但比起机械继电器是一次巨大进步

Also, initially vacuum tubes were expensive.
起初，真空管非常昂贵
But by the 1940s,
但到了 1940 年代
their cost and reliability had improved to the point where they became feasible for use in computers….
它的成本和可靠性得到改进，可以用在计算机里

This marked the shift from electro-mechanical computing to electronic computing.
这标志着计算机 从机电转向电子
The first large-scale use of vacuum tubes for computing was the Colossus MK 1,
第一个大规模使用真空管的计算机是 "巨人1号"
designed by engineer Tommy Flowers and completed in December of 1943.
由工程师 Tommy Flowers 设计，完工于1943年12月
The Colossus was installed at Bletchley Park, in the UK,
巨人1号 在英国的"布莱切利园", 用于破解纳粹通信
and helped to decrypt Nazi communications.
巨人1号 在英国的"布莱切利园", 用于破解纳粹通信
the first version of Colossus contained 1,600 vacuum tubes,
巨人1号有 1600 个真空管

Colossus is regarded as the first programmable, electronic computer.
巨人 被认为是第一个可编程的电子计算机

Programming was done by plugging hundreds of wires into plugboards,
编程的方法是把几百根电线插入插板

sort of like old school telephone switchboards,
有点像老电话交换机

in order to set up the computer to perform the right operations.
这是为了让计算机执行正确操作

So while "programmable", it still had to be configured to perform a specific computation.
虽然"可编程" ，但还是要配置它

Enter the The Electronic Numerical Integrator and Calculator - or ENIAC -
电子数值积分计算机 "ENIAC"

completed a few years later in 1946 at the University of Pennsylvania.
几年后在 1946 年，在"宾夕法尼亚大学"完成建造

Designed by John Mauchly and J. Presper Eckert,
设计者是 John Mauchly 和 J. Presper Eckert

this was the world's first truly general purpose, programmable, electronic computer.
这是世上第一个真正的通用，可编程，电子计算机
ENIAC could perform 5000 ten-digit additions or subtractions per second,
ENIAC 每秒可执行 5000 次十位数加减法
many, many times faster than any machine that came before it.
比前辈快了很多倍
It was operational for ten years,
它运作了十年
and is estimated to have done more arithmetic than the entire human race up to that point.
据估计，它完成的运算，比全人类加起来还多


By the 1950's, even vacuum-tube-based computing was reaching its limits.
到 1950 年代，真空管计算机都达到了极限

The US Air Force's AN/FSQ-7 computer, which was completed in 1955,
美国空军的 AN/FSQ-7 计算机于 1955 年完成

was part of the "SAGE" air defense computer system,
是 "SAGE" 防空计算机系统的一部分

To reduce cost and size, as well as improve reliability and speed,
为了降低成本和大小，同时提高可靠性和速度

a radical new electronic switch would be needed.
我们需要一种新的电子开关

In 1947, Bell Laboratory scientists John Bardeen, Walter Brattain, and William Shockley
1947 年，贝尔实验室科学家 \N John Bardeen，Walter Brattain，William Shockley

invented the transistor,
发明了晶体管

and with it, a whole new era of computing was born!
一个全新的计算机时代诞生了！

The physics behind transistors is pretty complex, relying on quantum mechanics,
晶体管的物理学相当复杂，牵扯到量子力学

so we're going to stick to the basics.
所以我们只讲基础

A transistor is just like a relay or vacuum tube
晶体管 就像之前提过的"继电器"或"真空管"

- it's a switch that can be opened or closed by applying electrical power via a control wire.
-它是一个开关，可以用控制线路来控制开或关

Typically, transistors have two electrodes separated by a material that sometimes can conduct electricity,
晶体管有两个电极，\N 电极之间有一种材料隔开它们，这种材料有时候导电

and other times resist it
有时候不导电

- a semiconductor.
- 这叫"半导体"

In this case, the control wire attaches to a "gate" electrode.
控制线连到一个 "门" 电极

By changing the electrical charge of the gate,
通过改变 "门" 的电荷

the conductivity of the semiconducting material can be manipulated,
我们可以控制半导体材料的导电性

allowing current to flow or be stopped
来允许或不允许 电流流动

- like the water faucet analogy we discussed earlier.
- 就像之前的水龙头比喻

Even the very first transistor at Bell Labs showed tremendous promise
贝尔实验室的第一个晶体管就展示了巨大的潜力

- it could switch between on and off states 10,000 times per second.
每秒可以开关 10,000 次

Further, unlike vacuum tubes made of glass and with carefully suspended, fragile components,
而且，比起玻璃制成，小心易碎的真空管

transistors were solid material known as a solid state component.
晶体管是固态的

Almost immediately, transistors could be made smaller than the smallest possible relays or vacuum tubes.
晶体管可以远远小于继电器或真空管

This led to dramatically smaller and cheaper computers, like the IBM 608, released in 1957
导致更小更便宜的计算机，比如1957年发布的IBM 608

– the first fully transistor-powered, commercially-available computer.
- 第一个完全用晶体管，而且消费者也可以买到的计算机

It contained 3000 transistors and could perform 4,500 additions,
它有 3000 个晶体管，每秒执行 4500 次加法

or roughly 80 multiplications or divisions, every second.
每秒能执行 80 次左右的乘除法

IBM soon transitioned all of its computing products to transistors,
IBM 很快把所有产品都转向了晶体管

bringing transistor-based computers into offices, and eventually, homes.
把晶体管计算机带入办公室，最终引入家庭

Today, computers use transistors that are smaller than 50 nanometers in size
如今，计算机里的晶体管小于 50 纳米

- for reference, a sheet of paper is roughly 100,000 nanometers thick.
- 而一张纸的厚度大概是 10 万纳米

And they're not only incredibly small, they're super fast
晶体管不仅小，还超级快

- they can switch states millions of times per second, and can run for decades.
- 每秒可以切换上百万次，并且能工作几十年

A lot of this transistor and semiconductor development happened
很多晶体管和半导体的开发在"圣克拉拉谷"

in the Santa Clara Valley, between San Francisco and San Jose, California.
这个地方在加州，位于"旧金山"和"圣荷西"之间

As the most common material used to create semiconductors is silicon,
而生产半导体最常见的材料是 "硅"

this region soon became known as Silicon Valley.
所以这个地区被称为 "硅谷"

Even William Shockley moved there, founding Shockley Semiconductor,
甚至 William Shockley 都搬了过去，创立了"肖克利半导体"

whose employees later founded Fairchild Semiconductors,
里面的员工后来成立了"仙童半导体"

whose employees later founded Intel - the world's largest computer chip maker today.
这里面的员工后来创立了英特尔 - 当今世界上最大的计算机芯片制造商

Ok, so we've gone from relays to vacuum tubes to transistors.
好了，我们从"继电器"到"真空管"到"晶体管"

We can turn electricity on and off really, really, really fast.
我们可以让电路开闭得非常非常快

But how do we get from transistors to actually computing something,
但我们是如何用晶体管做计算的？

That's what tangbo going to cover over 
这将是唐波接下来准备要讲的
