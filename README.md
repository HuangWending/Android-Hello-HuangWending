# Android-Hello-HuangWending
Kotlin和XML开发的一个Hello,HuangWending安卓(Android)程序
LinearLayout：这是一个布局容器，用于垂直排列其中的子视图。
xmlns:android：这个属性指定了XML文件中使用的命名空间为Android命名空间。
xmlns:tools：这个属性指定了XML文件中使用的命名空间为工具命名空间。
android:layout_width和android:layout_height：这些属性定义了布局容器的宽度和高度，使用match_parent表示填充父容器。
android:gravity：这个属性定义了子视图在布局容器中的对齐方式，这里设置为居中对齐。
android:orientation：这个属性定义了子视图的排列方向，这里设置为垂直排列。
tools:context：这个属性指定了与布局文件相关联的活动的上下文，这里设置为.MainActivity。
TextView：这是一个文本视图，用于显示文本内容。
android:id：这个属性指定了视图的唯一标识符，这里设置为@+id/helloTextView。
android:text：这个属性定义了显示在文本视图中的文本内容，这里设置为"Hello, HuangWending!"。
android:textSize：这个属性定义了文本的大小，这里设置为24sp。
创建一个名为MainActivity.kt的Kotlin文件。在该文件中，处理与用户界面交互的逻辑。
package：这个语句指定了文件所属的包名，这里设置为com.example.hellohuangwending。
import：这个语句用于导入所需的类或函数。在这里，我们导入了android.os.Bundle和androidx.appcompat.app.AppCompatActivity。
class MainActivity : AppCompatActivity()：这个语句定义了一个名为MainActivity的类，该类继承自AppCompatActivity类。
override fun onCreate(savedInstanceState: Bundle?)：这个语句定义了一个名为onCreate的函数，该函数在活动创建时被调用。
super.onCreate(savedInstanceState)：这个语句调用了父类的onCreate函数，确保执行父类的初始化逻辑。
setContentView(R.layout.activity_main)：这个语句设置活动的内容视图为activity_main.xml布局文件。
这样，就完成了一个"Hello, HuangWending"应用程序的创建。当应用程序启动时，它将显示一个包含"Hello, HuangWending"文本的界面。
