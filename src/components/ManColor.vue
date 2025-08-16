<template>
  <div>
    <audio id="voiceOfClick1">
      <source src="../assets/audio/click3.wav" type="audio/mpeg" />
    </audio>
    <el-container>
      <el-header id="header">
        点击
        <small>色块</small>
        <sub>复制</sub> 颜色码
      </el-header>
      <el-main class="main-body">
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#5c2223">暗玉紫</button>
            <button @click="onHandleClick" style="background:#eea2a4">牡丹粉红</button>
            <button @click="onHandleClick" style="background:#5a191b">栗紫</button>
            <button @click="onHandleClick" style="background:#f07c82">牡丹粉红</button>
            <button @click="onHandleClick" style="background:#5a1216">葡萄酱紫</button>
            <button @click="onHandleClick" style="background:#ed5a65">艳红</button>
            <button @click="onHandleClick" style="background:#c04851">玉红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ee3f4d">茶花红</button>
            <button @click="onHandleClick" style="background:#c02c38">高粱红</button>
            <button @click="onHandleClick" style="background:#a7535a">满江红</button>
            <button @click="onHandleClick" style="background:#e3b4b8">鼠鼻红</button>
            <button @click="onHandleClick" style="background:#f0a1a8">合欢红</button>
            <button @click="onHandleClick" style="background:#f1939c">春梅红</button>
            <button @click="onHandleClick" style="background:#a61b29">苋菜红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#894e54">烟红</button>
            <button @click="onHandleClick" style="background:#c45a65">莓红</button>
            <button @click="onHandleClick" style="background:#d11a2d">鹅冠红</button>
            <button @click="onHandleClick" style="background:#c21f30">枫叶红</button>
            <button @click="onHandleClick" style="background:#de1c31">唐菖蒲红</button>
            <button @click="onHandleClick" style="background:#7c1823">枣红</button>
            <button @click="onHandleClick" style="background:#541e24">猪肝紫</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#4c1f24">葡萄紫</button>
            <button @click="onHandleClick" style="background:#82202b">暗紫苑红</button>
            <button @click="onHandleClick" style="background:#82111f">殷红</button>
            <button @click="onHandleClick" style="background:#ef475d">草茉莉红</button>
            <button @click="onHandleClick" style="background:#4d1018">酱紫</button>
            <button @click="onHandleClick" style="background:#ed556a">山茶红</button>
            <button @click="onHandleClick" style="background:#7a7374">锌灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f03752">海棠红</button>
            <button @click="onHandleClick" style="background:#e6d2d5">蓟粉红</button>
            <button @click="onHandleClick" style="background:#f0c9cf">石蕊红</button>
            <button @click="onHandleClick" style="background:#ee2746">淡曙红</button>
            <button @click="onHandleClick" style="background:#2b1216">李紫</button>
            <button @click="onHandleClick" style="background:#ee4863">石竹红</button>
            <button @click="onHandleClick" style="background:#e77c8e">淡茜红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#500a16">金鱼紫</button>
            <button @click="onHandleClick" style="background:#c27c88">山黎豆红</button>
            <button @click="onHandleClick" style="background:#73575c">鼠背灰</button>
            <button @click="onHandleClick" style="background:#ee4866">淡蕊香红</button>
            <button @click="onHandleClick" style="background:#621624">甘蔗紫</button>
            <button @click="onHandleClick" style="background:#ce5777">月季红</button>
            <button @click="onHandleClick" style="background:#cc163a">尖晶玉红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f1c4cd">水红</button>
            <button @click="onHandleClick" style="background:#eeb8c3">姜红</button>
            <button @click="onHandleClick" style="background:#856d72">芦灰</button>
            <button @click="onHandleClick" style="background:#2d0c13">茄皮紫</button>
            <button @click="onHandleClick" style="background:#36282b">苍蝇灰</button>
            <button @click="onHandleClick" style="background:#bf3553">锦葵红</button>
            <button @click="onHandleClick" style="background:#ec9bad">粉团花红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ec8aa4">报春红</button>
            <button @click="onHandleClick" style="background:#ec7696">淡绛红</button>
            <button @click="onHandleClick" style="background:#ea7293">凤仙花红</button>
            <button @click="onHandleClick" style="background:#ef82a0">霞光红</button>
            <button @click="onHandleClick" style="background:#ec2c64">喜蛋红</button>
            <button @click="onHandleClick" style="background:#eb507e">夹竹桃红</button>
            <button @click="onHandleClick" style="background:#eb3c70">松叶牡丹红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ea517f">莲瓣红</button>
            <button @click="onHandleClick" style="background:#de7897">白芨红</button>
            <button @click="onHandleClick" style="background:#b598a1">隐红灰</button>
            <button @click="onHandleClick" style="background:#ef82a0">榲桲红</button>
            <button @click="onHandleClick" style="background:#c5708b">酢酱草红</button>
            <button @click="onHandleClick" style="background:#33141e">火鹅紫</button>
            <button @click="onHandleClick" style="background:#621d34">鹞冠紫</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ef3473">品红</button>
            <button @click="onHandleClick" style="background:#382129">磨石紫</button>
            <button @click="onHandleClick" style="background:#310f1b">墨紫</button>
            <button @click="onHandleClick" style="background:#381924">檀紫</button>
            <button @click="onHandleClick" style="background:#e16c96">初荷红</button>
            <button @click="onHandleClick" style="background:#951c48">菜头紫</button>
            <button @click="onHandleClick" style="background:#62102e">葡萄酒红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#e0c8d1">淡青紫</button>
            <button @click="onHandleClick" style="background:#d13c74">菠根红</button>
            <button @click="onHandleClick" style="background:#4b1e2f">海象紫</button>
            <button @click="onHandleClick" style="background:#ec4e8a">兔眼红</button>
            <button @click="onHandleClick" style="background:#de3f7c">嫩菱红</button>
            <button @click="onHandleClick" style="background:#a8456b">洋葱紫</button>
            <button @click="onHandleClick" style="background:#ce5e8a">吊钟花红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#461629">绀紫</button>
            <button @click="onHandleClick" style="background:#ee2c79">紫荆红</button>
            <button @click="onHandleClick" style="background:#ef498b">扁豆花红</button>
            <button @click="onHandleClick" style="background:#ede3e7">马鞭草紫</button>
            <button @click="onHandleClick" style="background:#ec2d7a">藏花红</button>
            <button @click="onHandleClick" style="background:#482936">斑鸠灰</button>
            <button @click="onHandleClick" style="background:#440e25">古铜紫</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#d2568c">丹紫红</button>
            <button @click="onHandleClick" style="background:#e9d7df">丁香淡紫</button>
            <button @click="onHandleClick" style="background:#d2357d">玫瑰红</button>
            <button @click="onHandleClick" style="background:#36292f">古鼎灰</button>
            <button @click="onHandleClick" style="background:#d276a3">菱锰红</button>
            <button @click="onHandleClick" style="background:#c06f98">樱草紫</button>
            <button @click="onHandleClick" style="background:#cc5595">龙须红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#c35691">电气石红</button>
            <button @click="onHandleClick" style="background:#ba2f7b">玫瑰紫</button>
            <button @click="onHandleClick" style="background:#9b1e64">苋菜紫</button>
            <button @click="onHandleClick" style="background:#5d3f51">紫灰</button>
            <button @click="onHandleClick" style="background:#4e2a40">龙睛鱼紫</button>
            <button @click="onHandleClick" style="background:#bc84a8">青蛤壳紫</button>
            <button @click="onHandleClick" style="background:#c08eaf">萝兰紫</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#411c35">荸荠紫</button>
            <button @click="onHandleClick" style="background:#ad6598">豆蔻紫</button>
            <button @click="onHandleClick" style="background:#a35c8f">扁豆紫</button>
            <button @click="onHandleClick" style="background:#681752">牵牛紫</button>
            <button @click="onHandleClick" style="background:#894276">芓紫</button>
            <button @click="onHandleClick" style="background:#7e2065">葛巾紫</button>
            <button @click="onHandleClick" style="background:#8b2671">青莲</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#983680">芥花紫</button>
            <button @click="onHandleClick" style="background:#c8adc4">凤信紫</button>
            <button @click="onHandleClick" style="background:#1c0d1a">深牵牛紫</button>
            <button @click="onHandleClick" style="background:#7e1671">魏紫</button>
            <button @click="onHandleClick" style="background:#1e131d">乌梅紫</button>
            <button @click="onHandleClick" style="background:#813c85">桔梗紫</button>
            <button @click="onHandleClick" style="background:#d1c2d3">淡牵牛紫</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#3e3841">剑锋紫</button>
            <button @click="onHandleClick" style="background:#815c94">蕈紫</button>
            <button @click="onHandleClick" style="background:#806d9e">槿紫</button>
            <button @click="onHandleClick" style="background:#e2e1e4">芡食白</button>
            <button @click="onHandleClick" style="background:#322f3b">龙葵紫</button>
            <button @click="onHandleClick" style="background:#8076a3">藤萝紫</button>
            <button @click="onHandleClick" style="background:#35333c">沙鱼灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#22202e">暗龙胆紫</button>
            <button @click="onHandleClick" style="background:#131124">暗蓝紫</button>
            <button @click="onHandleClick" style="background:#302f4b">野葡萄紫</button>
            <button @click="onHandleClick" style="background:#525288">野菊紫</button>
            <button @click="onHandleClick" style="background:#2f2f35">水牛灰</button>
            <button @click="onHandleClick" style="background:#ccccd6">远山紫</button>
            <button @click="onHandleClick" style="background:#74759b">螺甸紫</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#1f2040">晶石紫</button>
            <button @click="onHandleClick" style="background:#2e317c">满天星紫</button>
            <button @click="onHandleClick" style="background:#a7a8bd">淡蓝紫</button>
            <button @click="onHandleClick" style="background:#61649f">山梗紫</button>
            <button @click="onHandleClick" style="background:#2d2e36">牛角灰</button>
            <button @click="onHandleClick" style="background:#5e616d">鱼尾灰</button>
            <button @click="onHandleClick" style="background:#47484c">瓦罐灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#0f1423">钢蓝</button>
            <button @click="onHandleClick" style="background:#00008b">李青</button>
            <button @click="onHandleClick" style="background:#475164">鲸鱼灰</button>
            <button @click="onHandleClick" style="background:#2b333e">青灰</button>
            <button @click="onHandleClick" style="background:#1c2938">鸽蓝</button>
            <button @click="onHandleClick" style="background:#101f30">暗蓝</button>
            <button @click="onHandleClick" style="background:#142334">钢青</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#15559a">海涛蓝</button>
            <button @click="onHandleClick" style="background:#0f59a4">飞燕草蓝</button>
            <button @click="onHandleClick" style="background:#1661ab">靛青</button>
            <button @click="onHandleClick" style="background:#3170a7">安安蓝</button>
            <button @click="onHandleClick" style="background:#346c9c">海军蓝</button>
            <button @click="onHandleClick" style="background:#2775b6">景泰蓝</button>
            <button @click="onHandleClick" style="background:#2b73af">品蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#1772b4">群青</button>
            <button @click="onHandleClick" style="background:#baccd9">云水蓝</button>
            <button @click="onHandleClick" style="background:#619ac3">羽扇豆蓝</button>
            <button @click="onHandleClick" style="background:#495c69">战舰灰</button>
            <button @click="onHandleClick" style="background:#8fb2c9">晴山蓝</button>
            <button @click="onHandleClick" style="background:#5698c3">睛蓝</button>
            <button @click="onHandleClick" style="background:#11659a">搪磁蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#2983bb">潮蓝</button>
            <button @click="onHandleClick" style="background:#1677b3">天蓝</button>
            <button @click="onHandleClick" style="background:#c4cbcf">大理石灰</button>
            <button @click="onHandleClick" style="background:#1177b0">牵牛花蓝</button>
            <button @click="onHandleClick" style="background:#2486b9">宝石蓝</button>
            <button @click="onHandleClick" style="background:#5e7987">淡蓝灰</button>
            <button @click="onHandleClick" style="background:#74787a">嫩灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#2474b5">尼罗蓝</button>
            <button @click="onHandleClick" style="background:#4e7ca1">蝶翅蓝</button>
            <button @click="onHandleClick" style="background:#2376b7">花青</button>
            <button @click="onHandleClick" style="background:#144a74">鷃蓝</button>
            <button @click="onHandleClick" style="background:#93b5cf">星蓝</button>
            <button @click="onHandleClick" style="background:#2177b8">虹蓝</button>
            <button @click="onHandleClick" style="background:#126bae">柏林蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#cdd1d3">银鱼白</button>
            <button @click="onHandleClick" style="background:#1781b5">釉蓝</button>
            <button @click="onHandleClick" style="background:#66a9c9">涧石蓝</button>
            <button @click="onHandleClick" style="background:#d0dfe6">远天蓝</button>
            <button @click="onHandleClick" style="background:#2f90b9">云山蓝</button>
            <button @click="onHandleClick" style="background:#8abcd1">秋波蓝</button>
            <button @click="onHandleClick" style="background:#c3d7df">井天蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#158bb8">鸢尾蓝</button>
            <button @click="onHandleClick" style="background:#d8e3e7">云峰白</button>
            <button @click="onHandleClick" style="background:#b2bbbe">星灰</button>
            <button @click="onHandleClick" style="background:#1a94bc">钴蓝</button>
            <button @click="onHandleClick" style="background:#5cb3cc">碧青</button>
            <button @click="onHandleClick" style="background:#134857">苍蓝</button>
            <button @click="onHandleClick" style="background:#132c33">深灰蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#21373d">灰蓝</button>
            <button @click="onHandleClick" style="background:#b0d5df">湖水蓝</button>
            <button @click="onHandleClick" style="background:#22a2c3">海青</button>
            <button @click="onHandleClick" style="background:#474b4c">黄昏灰</button>
            <button @click="onHandleClick" style="background:#63bbd0">霁青</button>
            <button @click="onHandleClick" style="background:#126e82">玉鈫蓝</button>
            <button @click="onHandleClick" style="background:#0f95b0">胆矾蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#1491a8">樫鸟蓝</button>
            <button @click="onHandleClick" style="background:#c7d2d4">鸥蓝</button>
            <button @click="onHandleClick" style="background:#1e9eb3">翠蓝</button>
            <button @click="onHandleClick" style="background:#3b818c">蜻蜓蓝</button>
            <button @click="onHandleClick" style="background:#0eb0c9">孔雀蓝</button>
            <button @click="onHandleClick" style="background:#29b7cb">蔚蓝</button>
            <button @click="onHandleClick" style="background:#51c4d3">瀑布蓝</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#7cabb1">闪蓝</button>
            <button @click="onHandleClick" style="background:#10aec2">甸子蓝</button>
            <button @click="onHandleClick" style="background:#648e93">晚波蓝</button>
            <button @click="onHandleClick" style="background:#93d5dc">清水蓝</button>
            <button @click="onHandleClick" style="background:#617172">夏云灰</button>
            <button @click="onHandleClick" style="background:#c6e6e8">海天蓝</button>
            <button @click="onHandleClick" style="background:#869d9d">虾壳青</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#57c3c2">石绿</button>
            <button @click="onHandleClick" style="background:#c4d7d6">穹灰</button>
            <button @click="onHandleClick" style="background:#12aa9c">美蝶绿</button>
            <button @click="onHandleClick" style="background:#737c7b">垩灰</button>
            <button @click="onHandleClick" style="background:#12a182">蓝绿</button>
            <button @click="onHandleClick" style="background:#1ba784">竹绿</button>
            <button @click="onHandleClick" style="background:#428675">亚丁绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#c0c4c3">月影白</button>
            <button @click="onHandleClick" style="background:#248067">海王绿</button>
            <button @click="onHandleClick" style="background:#1a3b32">深海绿</button>
            <button @click="onHandleClick" style="background:#314a43">绿灰</button>
            <button @click="onHandleClick" style="background:#2c9678">青矾绿</button>
            <button @click="onHandleClick" style="background:#223e36">苍绿</button>
            <button @click="onHandleClick" style="background:#497568">飞泉绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#141e1b">莽丛绿</button>
            <button @click="onHandleClick" style="background:#69a794">梧枝绿</button>
            <button @click="onHandleClick" style="background:#2bae85">铜绿</button>
            <button @click="onHandleClick" style="background:#9abeaf">草原远绿</button>
            <button @click="onHandleClick" style="background:#45b787">蛙绿</button>
            <button @click="onHandleClick" style="background:#92b3a5">浪花绿</button>
            <button @click="onHandleClick" style="background:#1f2623">苷蓝绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#83cbac">粉绿</button>
            <button @click="onHandleClick" style="background:#70887d">淡绿灰</button>
            <button @click="onHandleClick" style="background:#55bb8a">麦苗绿</button>
            <button @click="onHandleClick" style="background:#20a162">翠绿</button>
            <button @click="onHandleClick" style="background:#40a070">葱绿</button>
            <button @click="onHandleClick" style="background:#1a6840">荷叶绿</button>
            <button @click="onHandleClick" style="background:#61ac85">淡绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#68b88e">田园绿</button>
            <button @click="onHandleClick" style="background:#a4cab6">玉簪绿</button>
            <button @click="onHandleClick" style="background:#3c9566">蟾绿</button>
            <button @click="onHandleClick" style="background:#5dbe8a">蔻梢绿</button>
            <button @click="onHandleClick" style="background:#207f4c">薄荷绿</button>
            <button @click="onHandleClick" style="background:#eef7f2">月白</button>
            <button @click="onHandleClick" style="background:#579572">蛋白石绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#b9dec9">竹篁绿</button>
            <button @click="onHandleClick" style="background:#229453">孔雀绿</button>
            <button @click="onHandleClick" style="background:#20894d">宫殿绿</button>
            <button @click="onHandleClick" style="background:#15231b">云杉绿</button>
            <button @click="onHandleClick" style="background:#66c18c">毛绿</button>
            <button @click="onHandleClick" style="background:#a4aca7">冰山蓝</button>
            <button @click="onHandleClick" style="background:#8a988e">明灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#9eccab">明绿</button>
            <button @click="onHandleClick" style="background:#83a78d">松霜绿</button>
            <button @click="onHandleClick" style="background:#485b4d">白屈菜绿</button>
            <button @click="onHandleClick" style="background:#5d655f">狼烟灰</button>
            <button @click="onHandleClick" style="background:#6e8b74">瓦松绿</button>
            <button @click="onHandleClick" style="background:#2b312c">槲寄生绿</button>
            <button @click="onHandleClick" style="background:#c6dfc8">淡翠绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#41b349">玉髓绿</button>
            <button @click="onHandleClick" style="background:#43b244">鲜绿</button>
            <button @click="onHandleClick" style="background:#253d24">油绿</button>
            <button @click="onHandleClick" style="background:#41ae3c">宝石绿</button>
            <button @click="onHandleClick" style="background:#add5a2">嘉陵水绿</button>
            <button @click="onHandleClick" style="background:#5e665b">田螺绿</button>
            <button @click="onHandleClick" style="background:#8cc269">水绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#5bae23">鹦鹉绿</button>
            <button @click="onHandleClick" style="background:#dfecd5">艾背绿</button>
            <button @click="onHandleClick" style="background:#cad3c3">艾绿</button>
            <button @click="onHandleClick" style="background:#9fa39a">镍灰</button>
            <button @click="onHandleClick" style="background:#b2cf87">橄榄石绿</button>
            <button @click="onHandleClick" style="background:#96c24e">芽绿</button>
            <button @click="onHandleClick" style="background:#f0f5e5">嫩菊绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#b7d07a">芦苇绿</button>
            <button @click="onHandleClick" style="background:#d0deaa">姚黄</button>
            <button @click="onHandleClick" style="background:#373834">蒽油绿</button>
            <button @click="onHandleClick" style="background:#bacf65">苹果绿</button>
            <button @click="onHandleClick" style="background:#e2e7bf">海沬绿</button>
            <button @click="onHandleClick" style="background:#bec936">橄榄黄绿</button>
            <button @click="onHandleClick" style="background:#d2d97a">槐花黄绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#e2d849">蝶黄</button>
            <button @click="onHandleClick" style="background:#fffef8">象牙白</button>
            <button @click="onHandleClick" style="background:#5e5314">橄榄绿</button>
            <button @click="onHandleClick" style="background:#fffef9">雪白</button>
            <button @click="onHandleClick" style="background:#ad9e5f">淡灰绿</button>
            <button @click="onHandleClick" style="background:#fed71a">佛手黄</button>
            <button @click="onHandleClick" style="background:#f9f4dc">乳白</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#e4bf11">香蕉黄</button>
            <button @click="onHandleClick" style="background:#d2b116">新禾绿</button>
            <button @click="onHandleClick" style="background:#fbda41">油菜花黄</button>
            <button @click="onHandleClick" style="background:#eed045">秋葵黄</button>
            <button @click="onHandleClick" style="background:#f1ca17">柚黄</button>
            <button @click="onHandleClick" style="background:#d2b42c">草黄</button>
            <button @click="onHandleClick" style="background:#f2ce2b">硫华黄</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#e2c027">姜黄</button>
            <button @click="onHandleClick" style="background:#645822">潭水绿</button>
            <button @click="onHandleClick" style="background:#fcd217">金瓜黄</button>
            <button @click="onHandleClick" style="background:#f8df70">麦秆黄</button>
            <button @click="onHandleClick" style="background:#dfc243">蒿黄</button>
            <button @click="onHandleClick" style="background:#f8df72">茉莉黄</button>
            <button @click="onHandleClick" style="background:#ffd111">藤黄</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ddc871">芒果黄</button>
            <button @click="onHandleClick" style="background:#fffefa">海参灰</button>
            <button @click="onHandleClick" style="background:#867018">碧螺春绿</button>
            <button @click="onHandleClick" style="background:#887322">苔绿</button>
            <button @click="onHandleClick" style="background:#fcd337">柠檬黄</button>
            <button @click="onHandleClick" style="background:#8e804b">草灰绿</button>
            <button @click="onHandleClick" style="background:#fecc11">向日葵黄</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#fccb16">素馨黄</button>
            <button @click="onHandleClick" style="background:#ffc90c">乳鸭黄</button>
            <button @click="onHandleClick" style="background:#b7ae8f">月灰</button>
            <button @click="onHandleClick" style="background:#f8d86a">葵扇黄</button>
            <button @click="onHandleClick" style="background:#fbcd31">大豆黄</button>
            <button @click="onHandleClick" style="background:#fcc307">金盏黄</button>
            <button @click="onHandleClick" style="background:#e9ddb6">菊蕾白</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#fcc515">黄连黄</button>
            <button @click="onHandleClick" style="background:#f7e8aa">杏仁黄</button>
            <button @click="onHandleClick" style="background:#e8b004">谷黄</button>
            <button @click="onHandleClick" style="background:#f9c116">木瓜黄</button>
            <button @click="onHandleClick" style="background:#f9d770">淡茧黄</button>
            <button @click="onHandleClick" style="background:#fbc82f">雅梨黄</button>
            <button @click="onHandleClick" style="background:#f1f0ed">银白</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#5b4913">棕榈绿</button>
            <button @click="onHandleClick" style="background:#f6c430">鹦鹉冠黄</button>
            <button @click="onHandleClick" style="background:#b78d12">枯绿</button>
            <button @click="onHandleClick" style="background:#f9bd10">浅烙黄</button>
            <button @click="onHandleClick" style="background:#f9d367">淡密黄</button>
            <button @click="onHandleClick" style="background:#d9a40e">芥黄</button>
            <button @click="onHandleClick" style="background:#ebb10d">栀子黄</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#584717">暗海水绿</button>
            <button @click="onHandleClick" style="background:#f7de98">篾黄</button>
            <button @click="onHandleClick" style="background:#f9f1db">蚌肉白</button>
            <button @click="onHandleClick" style="background:#f4ce69">炒米黄</button>
            <button @click="onHandleClick" style="background:#feba07">琥珀黄</button>
            <button @click="onHandleClick" style="background:#8a6913">灰绿</button>
            <button @click="onHandleClick" style="background:#876818">粽叶绿</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#b6a476">尘灰</button>
            <button @click="onHandleClick" style="background:#fcb70a">鼬黄</button>
            <button @click="onHandleClick" style="background:#f0d695">象牙黄</button>
            <button @click="onHandleClick" style="background:#87723e">鲛青</button>
            <button @click="onHandleClick" style="background:#f8e8c1">豆汁黄</button>
            <button @click="onHandleClick" style="background:#d6a01d">土黄</button>
            <button @click="onHandleClick" style="background:#f7da94">香水玫瑰黄</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#eaad1a">虎皮黄</button>
            <button @click="onHandleClick" style="background:#fbb612">鸡蛋黄</button>
            <button @click="onHandleClick" style="background:#b5aa90">银鼠灰</button>
            <button @click="onHandleClick" style="background:#f7f4ed">鱼肚白</button>
            <button @click="onHandleClick" style="background:#f8bc31">初熟杏黄</button>
            <button @click="onHandleClick" style="background:#b78b26">山鸡黄</button>
            <button @click="onHandleClick" style="background:#e5d3aa">莲子白</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#695e45">蟹壳灰</button>
            <button @click="onHandleClick" style="background:#e5b751">沙石黄</button>
            <button @click="onHandleClick" style="background:#f3bf4c">甘草黄</button>
            <button @click="onHandleClick" style="background:#685e48">燕羽灰</button>
            <button @click="onHandleClick" style="background:#fbb929">鹅掌黄</button>
            <button @click="onHandleClick" style="background:#f9d27d">麦芽糖黄</button>
            <button @click="onHandleClick" style="background:#e2c17c">浅驼色</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#b4a992">百灵鸟灰</button>
            <button @click="onHandleClick" style="background:#f6dead">酪黄</button>
            <button @click="onHandleClick" style="background:#f2e6ce">荔肉白</button>
            <button @click="onHandleClick" style="background:#f8e0b0">淡肉色</button>
            <button @click="onHandleClick" style="background:#393733">河豚灰</button>
            <button @click="onHandleClick" style="background:#835e1d">蜴蜊绿</button>
            <button @click="onHandleClick" style="background:#f8f4ed">汉白玉</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#fca104">橙皮黄</button>
            <button @click="onHandleClick" style="background:#815f25">莱阳梨黄</button>
            <button @click="onHandleClick" style="background:#fca106">枇杷黄</button>
            <button @click="onHandleClick" style="background:#ffa60f">金叶黄</button>
            <button @click="onHandleClick" style="background:#806332">苍黄</button>
            <button @click="onHandleClick" style="background:#fbf2e3">粉白</button>
            <button @click="onHandleClick" style="background:#fba414">淡橘橙</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#e4dfd7">珍珠灰</button>
            <button @click="onHandleClick" style="background:#826b48">龟背黄</button>
            <button @click="onHandleClick" style="background:#dad4cb">浅灰</button>
            <button @click="onHandleClick" style="background:#bbb5ac">铅灰</button>
            <button @click="onHandleClick" style="background:#bbb5ac">中灰</button>
            <button @click="onHandleClick" style="background:#ff9900">雄黄</button>
            <button @click="onHandleClick" style="background:#fbb957">蜜黄</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#dc9123">风帆黄</button>
            <button @click="onHandleClick" style="background:#c09351">桂皮淡棕</button>
            <button @click="onHandleClick" style="background:#f4a83a">金莺黄</button>
            <button @click="onHandleClick" style="background:#f7c173">肉色</button>
            <button @click="onHandleClick" style="background:#e7a23f">凋叶棕</button>
            <button @click="onHandleClick" style="background:#533c1b">古铜绿</button>
            <button @click="onHandleClick" style="background:#f9e8d0">落英淡粉</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#de9e44">软木黄</button>
            <button @click="onHandleClick" style="background:#f9cb8b">瓜瓤粉</button>
            <button @click="onHandleClick" style="background:#f9a633">榴萼黄</button>
            <button @click="onHandleClick" style="background:#daa45a">玳瑁黄</button>
            <button @click="onHandleClick" style="background:#553b18">焦茶绿</button>
            <button @click="onHandleClick" style="background:#513c20">蟹壳绿</button>
            <button @click="onHandleClick" style="background:#986524">山鸡褐</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#97846c">猴毛灰</button>
            <button @click="onHandleClick" style="background:#e3bd8d">鹿角棕</button>
            <button @click="onHandleClick" style="background:#4d4030">淡松烟</button>
            <button @click="onHandleClick" style="background:#fb8b05">万寿菊黄</button>
            <button @click="onHandleClick" style="background:#f8c387">蛋壳黄</button>
            <button @click="onHandleClick" style="background:#f28e16">杏黄</button>
            <button @click="onHandleClick" style="background:#503e2a">橄榄灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#4a4035">鹤灰</button>
            <button @click="onHandleClick" style="background:#cfccc9">玛瑙灰</button>
            <button @click="onHandleClick" style="background:#c1b2a3">淡银灰</button>
            <button @click="onHandleClick" style="background:#867e76">瓦灰</button>
            <button @click="onHandleClick" style="background:#847c74">夜灰</button>
            <button @click="onHandleClick" style="background:#fc8c23">北瓜黄</button>
            <button @click="onHandleClick" style="background:#fbecde">荷花白</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#4f4032">松鼠灰</button>
            <button @click="onHandleClick" style="background:#fbeee2">淡米粉</button>
            <button @click="onHandleClick" style="background:#81776e">深灰</button>
            <button @click="onHandleClick" style="background:#9a8878">海鸥灰</button>
            <button @click="onHandleClick" style="background:#5d3d21">茶褐</button>
            <button @click="onHandleClick" style="background:#66462a">驼色</button>
            <button @click="onHandleClick" style="background:#918072">银灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#d99156">鹿皮褐</button>
            <button @click="onHandleClick" style="background:#c1651a">槟榔综</button>
            <button @click="onHandleClick" style="background:#d4c4b7">晓灰</button>
            <button @click="onHandleClick" style="background:#be7e4a">淡赭</button>
            <button @click="onHandleClick" style="background:#5c3719">古铜褐</button>
            <button @click="onHandleClick" style="background:#de7622">麂棕</button>
            <button @click="onHandleClick" style="background:#db8540">醉瓜肉</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#80766e">雁灰</button>
            <button @click="onHandleClick" style="background:#f09c5a">鲑鱼红</button>
            <button @click="onHandleClick" style="background:#f97d1c">橘橙</button>
            <button @click="onHandleClick" style="background:#f26b1f">金黄</button>
            <button @click="onHandleClick" style="background:#f8b37f">玫瑰粉</button>
            <button @click="onHandleClick" style="background:#fa7e23">美人焦橙</button>
            <button @click="onHandleClick" style="background:#f9e9cd">米色</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#b7a091">蛛网灰</button>
            <button @click="onHandleClick" style="background:#945833">淡咖啡</button>
            <button @click="onHandleClick" style="background:#f0945d">海螺橙</button>
            <button @click="onHandleClick" style="background:#964d22">岩石棕</button>
            <button @click="onHandleClick" style="background:#954416">芒果棕</button>
            <button @click="onHandleClick" style="background:#e16723">陶瓷红</button>
            <button @click="onHandleClick" style="background:#fc7930">菠萝红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#cf7543">余烬红</button>
            <button @click="onHandleClick" style="background:#f86b1d">金莲花橙</button>
            <button @click="onHandleClick" style="background:#cd6227">火砖红</button>
            <button @click="onHandleClick" style="background:#f6dcce">初桃粉红</button>
            <button @click="onHandleClick" style="background:#d85916">铁棕</button>
            <button @click="onHandleClick" style="background:#f7cfba">介壳淡粉红</button>
            <button @click="onHandleClick" style="background:#f27635">蟹壳红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#e46828">金驼</button>
            <button @click="onHandleClick" style="background:#fc6315">燕颔红</button>
            <button @click="onHandleClick" style="background:#b7511d">淡可可棕</button>
            <button @click="onHandleClick" style="background:#ea8958">晨曦红</button>
            <button @click="onHandleClick" style="background:#e8b49a">玉粉红</button>
            <button @click="onHandleClick" style="background:#fb9968">野蔷薇红</button>
            <button @click="onHandleClick" style="background:#edc3ae">藕荷</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#363433">长石灰</button>
            <button @click="onHandleClick" style="background:#8b614d">中红灰</button>
            <button @click="onHandleClick" style="background:#aa6a4c">火泥棕</button>
            <button @click="onHandleClick" style="background:#a6522c">绀红</button>
            <button @click="onHandleClick" style="background:#fa5d19">莓酱红</button>
            <button @click="onHandleClick" style="background:#71361d">丁香棕</button>
            <button @click="onHandleClick" style="background:#b89485">淡玫瑰灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f68c60">瓜瓤红</button>
            <button @click="onHandleClick" style="background:#f6ad8f">淡藏花红</button>
            <button @click="onHandleClick" style="background:#732e12">筍皮棕</button>
            <button @click="onHandleClick" style="background:#f7cdbc">润红</button>
            <button @click="onHandleClick" style="background:#ef632b">龙睛鱼红</button>
            <button @click="onHandleClick" style="background:#8c4b31">淡土黄</button>
            <button @click="onHandleClick" style="background:#64483d">珠母灰</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f9723d">芙蓉红</button>
            <button @click="onHandleClick" style="background:#cf4813">落霞红</button>
            <button @click="onHandleClick" style="background:#ee8055">法螺红</button>
            <button @click="onHandleClick" style="background:#f8ebe6">草珠红</button>
            <button @click="onHandleClick" style="background:#753117">咖啡</button>
            <button @click="onHandleClick" style="background:#603d30">中灰驼</button>
            <button @click="onHandleClick" style="background:#883a1e">椰壳棕</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#b14b28">蟹蝥红</button>
            <button @click="onHandleClick" style="background:#873d24">淡豆沙</button>
            <button @click="onHandleClick" style="background:#f6cec1">淡桃红</button>
            <button @click="onHandleClick" style="background:#5b423a">淡铁灰</button>
            <button @click="onHandleClick" style="background:#624941">石板灰</button>
            <button @click="onHandleClick" style="background:#673424">淡栗棕</button>
            <button @click="onHandleClick" style="background:#f43e06">银朱</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ef6f48">草莓红</button>
            <button @click="onHandleClick" style="background:#f4c7ba">洋水仙红</button>
            <button @click="onHandleClick" style="background:#ed5126">淡桃红</button>
            <button @click="onHandleClick" style="background:#5b423a">朱红</button>
            <button @click="onHandleClick" style="background:#f34718">榴花红</button>
            <button @click="onHandleClick" style="background:#652b1c">可可棕</button>
            <button @click="onHandleClick" style="background:#eea08c">淡罂粟红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f04b22">大红</button>
            <button @click="onHandleClick" style="background:#692a1b">柞叶棕</button>
            <button @click="onHandleClick" style="background:#f1441d">蜻蜓红</button>
            <button @click="onHandleClick" style="background:#773d31">橡树棕</button>
            <button @click="onHandleClick" style="background:#eeaa9c">颊红</button>
            <button @click="onHandleClick" style="background:#f0ada0">桃红</button>
            <button @click="onHandleClick" style="background:#863020">火岩棕</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f2e7e5">淡藤萝紫</button>
            <button @click="onHandleClick" style="background:#862617">赭石</button>
            <button @click="onHandleClick" style="background:#f5391c">铁水红</button>
            <button @click="onHandleClick" style="background:#f03f24">胭脂红</button>
            <button @click="onHandleClick" style="background:#f33b1f">极光红</button>
            <button @click="onHandleClick" style="background:#f23e23">红汞红</button>
            <button @click="onHandleClick" style="background:#f13c22">萝卜红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f05a46">曲红</button>
            <button @click="onHandleClick" style="background:#f17666">谷鞘红</button>
            <button @click="onHandleClick" style="background:#f15642">苹果红</button>
            <button @click="onHandleClick" style="background:#f25a47">桂红</button>
            <button @click="onHandleClick" style="background:#f2b9b2">粉红</button>
            <button @click="onHandleClick" style="background:#592620">暗驼棕</button>
            <button @click="onHandleClick" style="background:#de2a18">夕阳红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#ed3321">樱桃红</button>
            <button @click="onHandleClick" style="background:#f04a3a">珊瑚红</button>
            <button @click="onHandleClick" style="background:#482522">火山棕</button>
            <button @click="onHandleClick" style="background:#5c1e19">栗棕</button>
            <button @click="onHandleClick" style="background:#d42517">鹤顶红</button>
            <button @click="onHandleClick" style="background:#f19790">舌红</button>
            <button @click="onHandleClick" style="background:#ab372f">鹅血石红</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#5a1f1b">酱棕</button>
            <button @click="onHandleClick" style="background:#ed3b2f">鱼鳃红</button>
            <button @click="onHandleClick" style="background:#bdaead">芦穗灰</button>
            <button @click="onHandleClick" style="background:#eb261a">丽春红</button>
            <button @click="onHandleClick" style="background:#ac1f18">覆盆子红</button>
            <button @click="onHandleClick" style="background:#483332">海报灰</button>
            <button @click="onHandleClick" style="background:#481e1c">豆沙</button>
          </div>
          <div class="main-body-line">
            <button @click="onHandleClick" style="background:#f1908c">榴子红</button>
            <button @click="onHandleClick" style="background:#ec2b24">秋海棠红</button>
            <button @click="onHandleClick" style="background:#efafad">无花果红</button>
            <button @click="onHandleClick" style="background:#f2cac9">淡绯</button>
            <button @click="onHandleClick" style="background:#4b2e2b">玫瑰灰</button>
            <button @click="onHandleClick" style="background:#ed4845">淡菽红</button>
            <button @click="onHandleClick" style="background:#ed3333">枸枢红</button>
          </div>
      </el-main>
      <el-footer>
        <input value="111" id="copy-for-inp" v-model="input" placeholder="颜色码" />
      </el-footer>
      <div></div>
    </el-container>
    <div id="colorMarsk1">
      <!-- <el-button @click="show2 = !show2">Click Me</el-button> -->
      <!-- <transition id="el-zoom-in-center" name="el-zoom-in-center">
        <div v-if="show2" class="transition-box">复制成功</div>
      </transition>-->
      <p id="colorMarsk1-p">{{ colorCode }}</p>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      input: "",
      show2: false,
      colorCode: "",
      i: document.getElementById("copy-for-inp"),
      copyStrMsg: {
        CopFnc_: t => {
          this.i.focus(function() {
            document.activeElement.blur();
          });
          i.value = t;
          i.select();
          document.execCommand("copy");
          return;
        },
      }
    };
  },
  mounted() {
    // this.copyStrMsg.CopFnc_();
    this.capture();

    // let input = document.getElementById("copy-for-inp");
    // input.focus(function() {
    //   document.activeElement.blur();
    // });
  },
  methods: {
    onHandleClick($e) {
      this.copyInp($e.target.style.background)
    },
    copyInp(text) {
  let input = document.getElementById("copy-for-inp");
  input.focus(function() {
    document.activeElement.blur();
  });
  input.value = text;
  input.select();
  document.execCommand("copy");
},
    capture() {
      //嵌套
      function copyInp(text) {
        let input = document.getElementById("copy-for-inp");
        input.focus(function() {
          document.activeElement.blur();
        });
        input.value = text;
        input.select();
        document.execCommand("copy");
      }
      //todo：
      let button = document.getElementsByTagName("button");
      for (let index = 0; index < button.length; index ++) {
        //手机触摸事件
        button[index].addEventListener("touchstart", () => {
          // alert('yes')
          let copyStr = button[index].getAttribute("style").slice(12, -1);
          document.getElementById("colorMarsk1-p").style.background = copyStr;
          document.body.style.background = copyStr;
        });
        //鼠标经过事件
        button[index].addEventListener("mouseover", function() {
          let copyStr = button[index].getAttribute("style").slice(12, -1);
          document.body.style.background = copyStr;
        });
        //鼠标按下事件
        button[index].addEventListener("click mouseover", function() {
          // button[index].setAttribute('@click','show2 = !show2')
          let colorMarsk1 = document.getElementById("colorMarsk1");
          colorMarsk1.style.opacity = "1";
          colorMarsk1.style.visibility = "unset";
          setTimeout(function() {
            colorMarsk1.style.opacity = "0";
            colorMarsk1.style.visibility = "hidden";
          }, 1500);

          let copyStr = button[index].getAttribute("style").slice(12, -1);
          document.getElementById("colorMarsk1-p").style.background = copyStr;
          document.body.style.background = copyStr;
          this.colorCode = copyStr;
          copyInp(copyStr)
          // this.copyStrMsg.CopFnc_(copyStr);
          let click1v_ = document.getElementById("voiceOfClick1");
          click1v_.play();
        });
      }
      console.log(button.length);
    },
    openMe32() {
      this.$message("复制成功");
    }
  }
};
</script>
<style>
* {
  padding: 0;
  margin: 0;
  /* filter: saturate(10%); */
}
html {
  background: #5d3131;
  transition: 0.5s;
}
body {
  transition: 0.8s;
}
#colorMarsk1 {
  /* display: flex; */
  opacity: 0;
  visibility: hidden;
  justify-content: center;
  align-items: center;
  font-size: 30px;
  /* font-weight: 1000; */
  /* color: white; */
  position: fixed;
  background: rgba(255, 255, 255, 0.3);
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 100;
  transition: 0.5s;
}
@keyframes identifier {
}
#colorMarsk1-p {
  line-height: 150px;
  width: 100%;
  /* background: #f1908c; */
  color: white;
}
#padding-main {
  padding: 0;
}
#header {
  margin-top: 5%;
  color: white;
  font-size: 30px;
}
.main-body {
  display: flex;
  flex-direction: column;
}
.main-body-line {
  display: flex;
}
button {
  flex: 1;
  border: 0;
  outline: none;
  height: 120px;
  color: white;
  font-size: 17px;
  text-shadow: 3px 3px 3px 2px rgba(0, 0, 0, 0.2);
  cursor: pointer;
  transition: 0.5s ease-in-out;
}
button:hover {
  transform: scale(1.5);
  z-index: 10;
  /* filter: blur(3px); */
}
#copy-for-inp {
  position: fixed;
  top: 10%;
  border: 0;
  background: rgba(0, 0, 0, 0);
  outline: none;
  font-size: 20px;
  font-weight: 600;
  letter-spacing: 5px;
  color: white;
  opacity: 0;
}
#el-zoom-in-center {
  position: fixed;
  top: 0;
  /* left: 50%; */
}
.transition-box {
  margin-bottom: 10px;
  width: 100%;
  height: 100px;
  /* border-radius: 4px; */
  background-color: #409eff;
  text-align: center;
  color: #fff;
  padding: 40px 20px;
  box-sizing: border-box;
  margin-right: 20px;
  z-index: 100;
  /* display: flex; */
  justify-content: center;
  align-items: center;
  font-size: 30px;
  position: fixed;
  /* background: rgba(255, 255, 255, 0); */
  top: 40%;
  left: 0;
  /* width: 100%; */
}
</style>
