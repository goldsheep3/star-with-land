---
title: GK-23a 实体卡预览页面
---

*ver. Aplha-0306*

<!--more-->

<style>
    @font-face {font-family: "MiSans";src: "MiSans-Semibold.ttf";}
    div        {font-family: "MiSans" ;}
    img        {display: block;margin: 0 auto;}
	a          {color:black;}
    .character {float: left;width: 72px;height: 95px;margin: 4px;background: #E9E5DC;text-align: center;border-radius: 5px;}
    .topic     {width: 720px;background: #DEB76C;color: #FEFEFE;border-radius: 8px;font-size: 1.5em;padding: 6px;border-radius: 5px;margin: 10px auto;text-align: center;}
    .thumbnail {float: left;width: 72px;height: 100px;margin: 3px;background-image: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);;text-align: center;border-radius: 8px;font-size: 0.9em}
    
    #pyro      {background: #E2311D;}
    #cryo      {background: #98C8E8;}
    #anemo     {background: #33CCB3;}
    #electro   {background: #D376F0;}
    #hydro     {background: #1C72FD;}
    #dendro    {background: #7BB42D;}
    #geo       {background: #CFA726;}
    #fivestar  {background: linear-gradient(0deg,#de9552 0%,#9a6d43 100%);border-radius: 5px;}
    #fourstar  {background: linear-gradient(0deg,#917ab1 0%,#6c6192 100%);border-radius: 5px;}
</style>

<table style="width: 760px;margin: 10px auto;">
    <tr>
        <td>
            <div class="topic" id="pyro"><b>火元素角色</b></div>
            <div>
                <a href="../../images/gk/character/diluc.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/diluc.webp"  weight=72 height=72>迪卢克</span></a>
                <a href="../../images/gk/character/klee.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/klee.webp"  weight=72 height=72>可莉</span></a>
                <a href="../../images/gk/character/hu_tao.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/hu_tao.webp"  weight=72 height=72>胡桃</span></a>
                <a href="../../images/gk/character/yoimiya.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/yoimiya.webp"  weight=72 height=72>宵宫</span></a>
                <a href="../../images/gk/character/dehya.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/dehya.webp"  weight=72 height=72>迪希雅</span></a>
                <a href="../../images/gk/character/amber.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/amber.webp"  weight=72 height=72>安柏</span></a>
                <a href="../../images/gk/character/bennett.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/bennett.webp"  weight=72 height=72>班尼特</span></a>
                <a href="../../images/gk/character/xiangling.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/xiangling.webp"  weight=72 height=72>香菱</span></a>
                <a href="../../images/gk/character/xinyan.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/xinyan.webp"  weight=72 height=72>辛焱</span></a>
                <a href="../../images/gk/character/yanfei.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/yanfei.webp"  weight=72 height=72>烟绯</span></a>
                <a href="../../images/gk/character/thoma.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/thoma.webp"  weight=72 height=72>托马</span></a>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="topic" id="hydro"><b>水元素角色</b></div>
            <div>
                <a href="../../images/gk/character/mona.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/mona.webp"  weight=72 height=72>莫娜</span></a>
                <a href="../../images/gk/character/tartaglia.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/tartaglia.webp"  weight=72 height=72>达达利亚</span></a>
                <a href="../../images/gk/character/sangonomiya_kokomi.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/sangonomiya_kokomi.webp"  weight=72 height=72>心海</span></a>
                <a href="../../images/gk/character/kamisato_ayato.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/kamisato_ayato.webp"  weight=72 height=72>神里绫人</span></a>
                <a href="../../images/gk/character/yelan.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/yelan.webp"  weight=72 height=72>夜兰</span></a>
                <a href="../../images/gk/character/nilou.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/nilou.webp"  weight=72 height=72>妮露</span></a>
                <a href="../../images/gk/character/barbara.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/barbara.webp"  weight=72 height=72>芭芭拉</span></a>
                <a href="../../images/gk/character/xingqiu.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/xingqiu.webp"  weight=72 height=72>行秋</span></a>
                <a href="../../images/gk/character/candace.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/candace.webp"  weight=72 height=72>坎蒂丝</span></a>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="topic" id="anemo"><b>风元素角色</b></div>
            <div>
                <a href="../../images/gk/character/jean.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/jean.webp"  weight=72 height=72>琴</span></a>
                <a href="../../images/gk/character/venti.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/venti.webp"  weight=72 height=72>温迪</span></a>
                <a href="../../images/gk/character/xiao.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/xiao.webp"  weight=72 height=72>魈</span></a>
                <a href="../../images/gk/character/kaedehara_kazuha.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/kaedehara_kazuha.webp"  weight=72 height=72>枫原万叶</span></a>
                <a href="../../images/gk/character/wanderer.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/wanderer.webp"  weight=72 height=72>流浪者</span></a>
                <a href="../../images/gk/character/sucrose.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/sucrose.webp"  weight=72 height=72>砂糖</span></a>
                <a href="../../images/gk/character/sayu.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/sayu.webp"  weight=72 height=72>早柚</span></a>
                <a href="../../images/gk/character/shikanoin_heizou.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/shikanoin_heizou.webp"  weight=72 height=72>平藏</span></a>
                <a href="../../images/gk/character/faruzan.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/faruzan.webp"  weight=72 height=72>珐露珊</span></a>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="topic" id="electro"><b>雷元素角色</b></div>
            <div>
                <a href="../../images/gk/character/keqing.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/keqing.webp"  weight=72 height=72>刻晴</span></a>
                <a href="../../images/gk/character/raiden_shogun.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/raiden_shogun.webp"  weight=72 height=72>雷电将军</span></a>
                <a href="../../images/gk/character/yae_miko.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/yae_miko.webp"  weight=72 height=72>八重神子</span></a>
                <a href="../../images/gk/character/cyno.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/cyno.webp"  weight=72 height=72>赛诺</span></a>
                <a href="../../images/gk/character/beidou.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/beidou.webp"  weight=72 height=72>北斗</span></a>
                <a href="../../images/gk/character/razor.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/razor.webp"  weight=72 height=72>雷泽</span></a>
                <a href="../../images/gk/character/lisa.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/lisa.webp"  weight=72 height=72>丽莎</span></a>
                <a href="../../images/gk/character/fischl.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/fischl.webp"  weight=72 height=72>菲谢尔</span></a>
                <a href="../../images/gk/character/kujou_sara.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/kujou_sara.webp"  weight=72 height=72>九条裟罗</span></a>
                <a href="../../images/gk/character/kuki_shinobu.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/kuki_shinobu.webp"  weight=72 height=72>久岐忍</span></a>
                <a href="../../images/gk/character/dori.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/dori.webp"  weight=72 height=72>多莉</span></a>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="topic" id="dendro"><b>草元素角色</b></div>
            <div>    
                <a href="../../images/gk/character/tighnari.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/tighnari.webp"  weight=72 height=72>提纳里</span></a>
                <a href="../../images/gk/character/nahida.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/nahida.webp"  weight=72 height=72>纳西妲</span></a>
                <a href="../../images/gk/character/alhaitham.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/alhaitham.webp"  weight=72 height=72>艾尔海森</span></a>
                <a href="../../images/gk/character/collei.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/collei.webp"  weight=72 height=72>柯莱</span></a>
                <a href="../../images/gk/character/yaoyao.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/yaoyao.webp"  weight=72 height=72>瑶瑶</span></a>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="topic" id="cryo"><b>冰元素角色</b></div>
            <div>
                <a href="../../images/gk/character/qiqi.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/qiqi.webp"  weight=72 height=72>七七</span></a>
                <a href="../../images/gk/character/ganyu.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/ganyu.webp"  weight=72 height=72>甘雨</span></a>
                <a href="../../images/gk/character/eula.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/eula.webp"  weight=72 height=72>优菈</span></a>
                <a href="../../images/gk/character/kamisato_ayaka.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/kamisato_ayaka.webp"  weight=72 height=72>神里绫华</span></a>
                <a href="../../images/gk/character/shenhe.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/shenhe.webp"  weight=72 height=72>申鹤</span></a>
                <a href="../../images/gk/character/chongyun.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/chongyun.webp"  weight=72 height=72>重云</span></a>
                <a href="../../images/gk/character/kaeya.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/kaeya.webp"  weight=72 height=72>凯亚</span></a>
                <a href="../../images/gk/character/diona.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/diona.webp"  weight=72 height=72>迪奥娜</span></a>
                <a href="../../images/gk/character/rosaria.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/rosaria.webp"  weight=72 height=72>罗莎莉亚</span></a>
                <a href="../../images/gk/character/layla.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/layla.webp"  weight=72 height=72>莱依拉</span></a>
                <!--<a href="../../images/gk/character/layla.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/mika.webp"  weight=72 height=72>米卡</span></a>-->
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="topic" id="geo"><b>岩元素角色</b></div>
            <div>
                <a href="../../images/gk/character/zhongli.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/zhongli.webp"  weight=72 height=72>钟离</span></a>
                <a href="../../images/gk/character/albedo.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/albedo.webp"  weight=72 height=72>阿贝多</span></a>
                <a href="../../images/gk/character/arataki_itto.webp"><span class="thumbnail"><img id="fivestar" src="../../images/gk/icons/character/arataki_itto.webp"  weight=72 height=72>荒泷一斗</span></a>
                <a href="../../images/gk/character/ningguang.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/ningguang.webp"  weight=72 height=72>凝光</span></a>
                <a href="../../images/gk/character/noelle.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/noelle.webp"  weight=72 height=72>诺艾尔</span></a>
                <a href="../../images/gk/character/gorou.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/gorou.webp"  weight=72 height=72>五郎</span></a>
                <a href="../../images/gk/character/yun_jin.webp"><span class="thumbnail"><img id="fourstar" src="../../images/gk/icons/character/yun_jin.webp"  weight=72 height=72>云堇</span></a>
            </div>
        </td>
    </tr>
</table>


{% folding yellow::查看GK-23a卡牌更新日志 %}

- Alpha-0306
  网页版正式发布。更新所有目前可玩角色（米卡尚未可获取，暂时不可玩）。

{% endfolding %}
