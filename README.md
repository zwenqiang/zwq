# zwq
通用头布局（不依赖xml）自定义  多种类型头布局 通过TitleMode设置使用方式:
@TitleModeInject(mode = CommentTitleBar.TitleMode.IMG_EDIT_IMG)
public class MainActivity extends BaseActivity {do something...}
状态栏根据头布局的颜色变色 （仅支持4.4以上） 可以设置头布局 颜色，图片 状态栏随之变色，可以添加多个左侧 或 右侧按钮
