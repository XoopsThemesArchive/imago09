/*####################################################
	布景名称：IMAGO09 BLOG风格版
	发布站点：http://www.imagocn.net/theme/
	站点名称：IMAGO:THEMES 
	制作者：MACLINKS
	发布日期：2005.01.07
	联系方式: maclinks@imagocn.net
	说明：如果您修改了我们的样式风格，请保留该处信息
	      以示对我们的支持！
	声明：该布景仅限用于个人及公益网站，商业站点请与
	      我们联系商业授权事宜。
  ###################################################*/


  --------------------------------------------------------
  关于IMAGO:THEMES
  --------------------------------------------------------
  IMAGO:THEMES就是建立在XOOPS上的专业THEME（布景）制作站点。
  您只需将您的要求告诉我们，我们将跟据您的站点性质，如：游
  戏、IT、网络、电子商务等，为您的XOOPS站点量身打造个性化的
  的布景主题。同时，在IMAGO:THEMES您不时可以下载到众多本站
  独创的可用于个人站点上的FREE THEME。

  --------------------------------------------------------
  关于本布景
  --------------------------------------------------------
  本布景在发布之前已经在IE及FIREFOX下测试(还未在MAC上进行测
  试，您如果有条件，可以告知我们style.css或styleNN.css 哪个
  更适合于MAC，默认使用的是idstyle.css样式)

  在IE的测试中没有发现什么问题。
  在FIREFOX中存在如下问题：
  1.无法自动适应显示或不显示左右区块(目前暂时无法解决这个问
    题)，如果您更看重使用FIREFOX的用户，我们建议您在每一个模
    组中都显示左区块，而不显示右区块，同时您需要在
    idstyleNN.css中将
	#blockCenter{
	padding-left:10px;
	padding-right:10px;
	margin-left:175px;
	margin-right:175px;
	}
     修改为：
	#blockCenter{
	padding-left:10px;
	padding-right:10px;
	margin-left:175px;
	}
  
  如果您在使用过程中发现什么问题，请与我们联系，我们将及时进
  行修正。

  --------------------------------------------------------
  关于文件夹结构
  --------------------------------------------------------
  IMAGO09
  |- style.css				// IE浏览器样式
  |- styleNN.css			// Mozilla浏览器
  |- styleMAC.css			// MAC 类浏览器
  |- theme.html				// 主模板文件
  |- README.txt				// 关于布景的说明文件
  +[DIR] PNG_FILES			// 图片源文件目录
  +[DIR] images				// 图片目录
  +[DIR] jscript			// JS代码目录
  +[DIR] styles				// CSS样式目录
     |- mycontent.css			// 自定内容样式
     |- main.css			// 默认CSS CLASS
     |- idstyleNN.css			// FIREFOX浏览器样式
     |- idstyle.css			// IE浏览器样式
     |- font.css			// 全局字体大小
     |- color.css			// 全局颜色样式
  +[DIR] blocks				// 区块模板目录
     |- theme_block_centerc.html	// 中中区块模板	
     |- theme_block_centerl.html	// 中左区块模板
     |- theme_block_centerr.html	// 中右区块模板
     |- theme_block_left.html		// 左区块模板
     |- theme_block_right.html		// 右区块模板
     |- theme_navmenu.html		// 自定菜单模板
  +[DIR] templates	// 模板文件目录
  
  注：虽然上述文件有的文件夹是空的，您可以删除它，但是我们
      建议您保留它，因为以后IMAGO的布景将按此结构进行创建。
      您升级布景时，只需将相应的文件放入相应的目录及可。
