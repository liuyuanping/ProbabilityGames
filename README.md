## Welcome to ProbabilityGames

You can use the [ProbabilityGames](https://liuyuanping.github.io/ProbabilityGames/ProbabilityGames.html) to do your own reseach.

If you have any problem, please contact me at any time.


### The Usage

Oops, please wait a minute.

![some-thoughts](assets/img/post-2022-06-12-some-thoughts.jpg "运行结果参考")


### Post List
<div id="home">
    <ul class="posts">
        {% for post in site.posts %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.*title* }}</a></li>
        {% endfor %}
    </ul>
</div>


### Story Time

这里是第一届NPC抛金币模拟大赛，感谢您的到来。此次大赛共有1000名NPC参赛。开赛前，我们每个NPC都会拿到100枚金币的游戏道具。游戏内容就是抛金币，金币有正反两面，得到正反面的概率各50%。每个NPC最多抛2500次，抛到正面奖励10枚金币，抛到反面则惩罚10枚金币。如果抛到的反面过多，金币都被惩罚完了，则此NPC不能再继续游戏了，获得loss称号；如果抛到的正面过多，金币总数达到1000枚（初始金币的10倍），则此NPC也不能继续游戏了，获得win称号；如果抛完了2500次，还没有获得loss或者win称号，则此NPC将获得pending称号。就在我们讲解大赛规则的时候，我们已经看到有多名NPC获得了loss称号。实在是可惜啊。希望他们再接再厉，争取在下一届大赛中取得一个更好的成绩。好，那边已经有一名NPC拿到了1000枚的金币，获得第一个win称号，恭喜恭喜。我们的第一届抛金币大赛，各位参赛选手都是劲头十足啊。两千五百次也已经很快结束了。裁判们正在统计结果，让我们稍事休息进入到最后的颁奖环节。广告之后马上回来，不要走开哦。

好，此次大赛的结果已经在我的手上了。他们分别是：38/1000的选手获得了win称号，让我们恭喜他们；第二个要揭晓的是，839/1000的选手获得了loss称号，也恭喜他们；最后是123/1000的选手获得了pending称号，祝贺他们。祝贺各位参赛选手取得的优异成绩，希望他们在以后的比赛中都能赛出水平，赛出风格。我们的第一届NPC抛金币模拟大赛也到此结束了。感谢您的光临，祝您晚安。让我们一起期待下一届抛金币大赛早日到来吧。谢谢。谢谢大家。谢谢。


### Some Thoughts

【戒赌神器：随机游走模拟器】
【形象、具体、直观地展示赌徒的命运】
【即使是最公平的赌局，没有人出老千，输赢概率一半一半，赌徒也会输光】

1. 为什么说久赌必输？因为赢的时候没有尽头；输的时候到零就没了，输光了。
2. 又有说十赌九输，为什么还有人能赢？因为“赢钱一刻谁都有”，他赢了之后就不赌了，及时收手了，激流勇退了，所以就赢了。其他人赢了之后还想赢更多，不收手，最后都输光了。
3. 如何提高赢钱的概率？降低期望。十块钱变成一千块的概率大概是百分之一（十除以一千）；十块钱变成一万块的概率大概是千分之一（十除以一万）；十块钱变成十块零一毛的概率大概是百分之九十九（十除以十又十分之一，也说“赢钱一刻谁都有”），但即使是百分之九十九，还是有大概百分之一的风险输光这十块。降低期望，不要想着赢那么多，自然胜率就提高了。只是胜率提高了能赢到的钱也变少了。胜率越高，能赢到的钱也越少。最难的就是胜率再高也有输光的风险，无法避免。
4. 如果一定要赌，做好全部输光的准备。
5. 如果身边有个稀里糊涂就赢了座金山的人（很多都是稀里糊涂的），可以的话，劝他别赌了。苦海无边，回头是岸。放下屠刀，立地成佛。当然，他/她大概率不会听。如果听了，也许能把金山守住。
6. 最后，如果有的赌局是一定要参加的。那就只能通过降低每一局的赌注用以延缓输光出局的时间。降低到一定程度，也可以不用输光。

【年轻人要敢赌敢拼，输了大不了从头再来；赢了就是一座金山。】
【粗粗记一笔先。还有很多地方可以展开，在想要不要做一个系列。毕竟，程序都写了。】

