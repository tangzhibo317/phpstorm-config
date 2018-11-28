# phpstorm-config
phpstorm的配置以及ideavimrc配置
Jetbrains 的很多产品还是非常好用的，IntelliJ IDEA, PyCharm, Clion 等等都非常受欢迎。 因为我比较喜欢 vim， 因此在使用这些 IDE 时都会装上 vim 的插件：ideavim. 不过因为我对 vim 的默认配置更改了很多，定制了很多快捷键等等，在使用默认配置下的 ideavim 时还是有些不太顺手，因此针对 ideavim 定制一些 vim 的配置便十分有必要了。

.ideavimrc 配置文件
其实很简单，修改 ideavim 的配置文件 .ideavimrc 即可。默认情况下该文件并不存在，需要自行创建。

在类 unix 系统中将 .ideavimrc 放置在用户根目录
~/.ideavimrc  

在 windows 系统中将 .ideavimrc 文件放置在如下目录
C:\Users\你的用户名\.ideavimrc

Windows系统中无法创建以 . 开头的文件，可以在记事本中通过另存为的方式创建，编码为 UTF-8，配置完 .ideavimrc 需要重启 idea 才会生效，关于 ideavim 和  idea 按键的冲突，可以在 Other Settings/Vim Emulation 中进行设置，我把所有的都设置抢IDE的，看个人爱好。

创建配置文件 .ideavimrc 后，接下来就是写入配置信息了。要注意，ideavim 只是 IDE 的插件，并没有实现原生 vim 的所有功能，有些 vim 的功能在 ideavim 中并不存在。比如定义一下方法，加载个插件，比如 <Leader> 设置无效。

剩下的文件里都有了
