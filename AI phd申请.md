https://web.thuhole.com/##324735 【精品】
【长文慎入】开个洞来详细的讲讲美国AI方向PhD的申请。

本来我早就想写这么一个来造福有意向出国读研的学弟学妹，但是要么我太忙没时间，要么有时间但因为喜欢冲塔被树洞小管家禁言。正巧前两天看见那个答疑洞吸引了很多关注，而且我最近就差nips写作了，正好借此机会练习一下文笔写点东西。请注意，本文由于追求完备，力争覆盖申请的每一个细节，所以可能会很长，毕竟我想写这个的目的就是看不惯中介靠信息差卖高价，我就是来砸他们的饭碗的，所以自然要事无巨细地全写出来。这样即便大家要报世毕盟，也只需要报半价的那个套餐就好了。不过我其实有很多地方十分主观，比如涉及评价学校的部分，所以不认同的人可能觉得我在夹带私货。如果你不认同本人的部分观点，就请当做我的一家之言，仅做参考就完了。
当然，这个洞是专门给AI方向的PhD申请开的，主要针对的群体是ai/ml/cv/nlp/dm/robotics方向的申请者。cs其他方向比如system也可以参考，甚至不是cs的申请者读完可能也会觉得有所收获，所以各位敬请各取所需。我在最后也会讲讲关于mscs的申请。
所以为什么要去美国读AI的PhD呢？这似乎在当下有点政治不正确，显得清华好像留美预备学校一样。按理说，看csranking上清华北大反超cmu登顶世界第一不过是时间问题，为什么要跑到“注定失败”的美国去再上演一出49年入国军呢？很多人有从各个面向给出了很多不同的解答。我只根据纯粹的research原因给大家一个我的想法。其实，清华cs和北美top校最大的差距就是工作偏follow-up。不服气的小伙伴可以先想一想，ai顶会国内没少产出，但dl时代真正有high impact的可能只有当年kaiming he在msra的那一系列工作，而kaiming现在也已经在FAIR了。换言之，国外的顶级cs phd program更喜欢学生能够去开坑，而清华的phd更倾向去填坑。
什么样的工作算开坑呢？一个类型是定义新的问题，比如fei-fei组的工作。很多人诟病飞飞标了个数据集，或者搞了个新的benchmark就不管了，但在她看来刷benchmark是工业界的事，学术界本来就应该告诉大家我们应该往哪里move on，无论是定义新问题，还是标新的数据集，都是在告诉大家整个community下一步的前进方向。而不单纯是今天我有一个task，有一个benchmark，还有一个SOTA的模型，我在上面加加减减然后提几个点，讲一个故事就是一篇论文。值得关心的不是在ImageNet上有提了几个点，而是我们究竟离AI还有多远这样一个big picture。所以很多做object detection或者segmentation的同学不妨想想，为什么要从bounding box和pixel-wise两个角度来做understanding。另一类开坑的工作，是创造性的提出一套前所未有的解决问题的范式。很多人用lstm做nlp的时候，google第一个说attention is all u need,cv都是cnn的时候也是google告诉大家transformer可以代替cnn。很多人现在做点云，但是第一个提出可以直接用deep model on point cloud的是guibas组。类似的还有首先用deep model结合SDF表达3D物体的DeepSDF（UW+FB），以及去年大火的nerf（Berkeley+google)第一个把deep model引进到rendering中取得了很好的结果。总之，说穿了就两个问题，我可以怎么创造新的问题来继续提升deep learning？deep learning可以用来提升哪些现有的问题？很多时候回答这两个问题需要的是对于潮流发展有敏锐的sense，我认为这才是中美AI学界差距最大的地方。song han能拿到mit的教职是因为在stanford开了model compression的大坑，jun-yan zhu和tianqi chen拿到cmu的offer也是因为分别在Berkeley和UW开了image2image以及tvm的大坑。我觉得清华要摆脱留美预备学校的帽子，需要先清华能让美国人做我们定义的问题。

好像扯得有点远，不过我觉得先让大家厘清为何要去美国读AI PhD是一件很重要的事情。下面我把申请中的各要素分门别类地和大家详细讲一讲。

GPA：我首先就要讲gpa。很多人说gpa对phd不重要，也有很多人说gpa重要，到底重不重要呢？It depends。如果你本科毕业发了10篇顶会一作，gpa可有可无，如果没有paper，gpa可能就是你的救命稻草。申请的结果是各个方面加权的结果，但不同人的加权系数是不一样的。与高考关注有没有短板不同，美国学校更关注的是你的长板，一般来说你出彩的那一部分越出彩作用越大，加权越高。所以3.95gpa很可能让缺少过硬科研经历的你进入Princeton这种分控学校。但很多gpa没这么高的同学也不必过于担心，你也可以通过多发paper来弥补。虽然gpa永远越高越好，但gpa过了3.7以后边际效益就很低了，3.7和3.8的差距远远小于一篇一作paper的差距。从来没有什么不到3.8上不了top phd的说法，唯一的硬线只有3.0，到不了3.0是真的会第一轮被刷的。所以啊，如果你都大三了，别天天计较怎么能让gpa的百分位高一点这种事了，赶快去加入实验室做科研吧。如果你刚大一的话，赶快让自己的gpa高一点，这样你其他方面的压力会小不少。

托福/GRE： 很多人为了英语考试没完没了给ets或者新东方送钱，真的是没必要。其实cs研究生的申请根本没必要什么托福110，许多学校的线一般是100，有些学校或项目会明确写出来要求托福100以上，如果想保险一点可以考到105以上，再往上也没啥用了。至于单项唯一要紧的是口语，至少要上20，像cornell这种藤校，明确写了会卡22的线。一般低于22的话，你的交流水平会被质疑，教授肯定要通过面试确认一下你是不是不会说英文。但不会因为22就不录取你，而是要你入学后去上英语课，毕竟读phd要做TA。至于GRE，这东西320+3.5以上绝对够了，现在无论phd还是ms都越来越淡化GRE的重要性了，毕竟背一堆生僻词汇以后也用不上。

研究经历&Publication： 重中之重。AI方向没有一作paper基本与top phd绝缘，即便3.95的gpa最好很可能也就是Pton了。可能偏理论的机器学习方向还好一些，但应用方向比如cv/nlp没有paper基本四大第一轮就被筛掉了。所以建议有志于top phd的赶快搞paper，但是tier2的学校很多没有paper也是有可能的，这就要看你的推荐信（主要是暑研导师的评价）以及gpa了。但paper与paper是不同的，一般paper看的是几作、什么会议以及是否已经中稿。基本来说，一作顶会是能逆天改命的，本科毕业生一篇中了的一作顶会基本能把你送进前15的学校。二作对本科来说也有点用，三作及以后作用寥寥，但在简历上写上去总比什么也没有好看，所以即便蹭三作也请大家蹭一蹭。至于会议类别，基本北美top phd只看顶会，cv就是cvpr/iccv/eccv，国内喜欢投什么aaai/mm，这对于top phd作用比较小，但tier2的学校会看，申请ms也是大有裨益，基本一篇aaai一作能报送进入cmu类似miis或者mscv这类项目，所以看大家的目标院校，如果不是非四大不读，可能差一点的会议也可以投投。至于我上面说北美学校比较喜欢开坑的工作，会不会对文章质量也有要求呢？其实这是对phd毕业生的期待，junior researcher的paper基本只能证明你走了一整套流程， 教授看的也是这个，因为可以不用从头培养。所以啊，即便灌水顶会，也请多灌一点，你大四申请的时候中了三篇icml/nips/iclr一作，要是没有四大offer，我可以跟你姓。顶会水文的确多，但也不是是个人拍拍脑瓜就能中的。当然如果能像zhuang liu那样发一篇best paper就能横扫了，但这不是必要条件。至于文章本身，topic也比较重要，建议大家看看自己感兴趣的老师在做啥，然后follow他们的工作，会大大提高被录取的概率。但并不是说你不能申请其他方向的老师，因为你本科做得可能和你phd做得完全不同，老师看的是潜力，所以申请的时候不要因为和自己方向不match就不申请了，只要你觉得你愿意做，你就大胆去申请就是了，反正申请就是轮盘赌，一看风水二看命，然后才看你的背景条件。paper另一个重要的点是中没中。不管是不是水文侥幸中的，只要中了就是大大有用。当然很多人暑研的工作大概率申请的时候没结果，但也要在cv和ps里列出来，然后标上in submission，虽然不如accept，但也是有用的！然后建议在投的要么挂arxiv，要么加一个google drive的link，然后要在教授的letter中体现出来。至于in progress的列了也没用，因为没完成的paper等于没有。

暑研： 对于申请phd来说，北美推荐信很重要，当然ms也一样。唯一的拿到北美letter的机会就是暑研。所以无论申请ms或者phd的，都请暑假去美国实验室搬砖吧，即便你对科研没兴趣。而要申请phd的人，去academia要比industry强，即便你的offer来自google brain。至于暑研选校的问题，我诚挚地建议不要无脑四大，虽然我觉得我说了很多人也不会听。道理很简单，暑研的目的是拿推荐信，暑研不会给你发文凭，即便ugvr这种官方项目也不会给你发斯坦福的文凭。你要确保的是哪里能拿强推。众所周知，四大ai的phd return极度难拿，一年去了好几个可能就一个能拿return，如果你没gpa很高，或者已经有一作顶会了，我建议不要去陪太子读书当分母了。要不到时候你那些去了top10的同学纷纷把坑位占了，你回头才发现top10都没你位子了。不过如果你海专精算后发现自己是四大的有力竞争者，建议直接去四大暑研，因为本校的推荐信总是更好用。很多人可能怀疑letter质量是否会和学校专排挂钩，我可以这么讲，这个相关性有，但比你做的怎么样要低得多。你去ucsd拿top1%的强推照样可以把你送进四大。当然如果目标就是ms，请直接去目标学校，因为ms的坑位多很多，不会有别人占了你的概率就急剧降低这种事。所以啊，准确定位自己是申请暑研前应该做的第一件事！也是申请成功的先决条件。确定了自己的水平然后就是确定去哪个老师。建议参考各校官网率、csranking以及过往学长去向，然后广撒网。可能发十封有一封回复的，这其实很正常。一般老师如果愿意会约你面试，这基本大半只脚就迈进去了。因为暑研门槛不高，所以不要紧张！和老师随便聊聊你过去的一些科研经历或者参与的srt，可以很naive，但老师只是想看看你有没有入门而已。至于办理签证买机票我就不赘述了。
然后我要讲讲怎么做一个成功的暑研。基本有两点，第一个有产出，第二个给老师留下印象。有产出自然是有paper了，对于老师写推荐信来说，paper提交了中没中其实差距不大，但有没有交这评价注定是两个档次，特别是ai领域。然后留下印象这事可能比较tricky，我的建议是多交流，多开口！！老师认知学生最主要方式就是交流，一个是paper reading，另一个是关于project的personal meeting。纵然你满腹经纶，但如果你徐庶进曹营，一言不发，你这个letter也不会很强，因为老师没东西写。可能有人觉得我没啥可说的啊，项目进度很快就说完了。这就需要你展现吹nb的天赋了，你大可以和教授讨论各种high-level的东西，美国人喜欢学生对high-level的东西有思考，而不是只关注技术细节。至于high-level是什么东东？请看各文章的intro部分。交流的质量只要从你的表达能力以及思维是不是清楚来判定。如果你觉得自己英语不好，或者专业术语不太熟悉，建议找华人教授，这样可以中文交流，甚至可以微信交流。总之多交流就对了！当然你也不能做一个光说不做的人，你要干活，要可靠，如果你答应了要做一个实验，下一次请展示出结果，而不是说我忘了，否则大大扣分！然后要关注细节，无论是和导师的日常交流还是面试，很多时候对细节的追问会体现你到底懂不懂自己的project。最后的最后，要主动！！如果老师不找你，你就找他；如果你对project有什么想法，你就大大方方地说出来，哪怕你想做一个不同的也无所谓。展现出你的热情以及对于新知的渴望来！哪怕一个task从没接触过也不要怕，你要展现出你在清华锻炼的自学能力以及学习热情来，因为fast adaptation是很重要的能力。暑假结束后，也不要不理老师了。要继续保持联络，直到project得到论文产出，善始还要善终。

推荐信：最重要的没有之一！！！！好的推荐信能让你逆天改命，坏的则能让你前功尽弃。所以怎么做才能得到好的letter，我已经在上一段讲了。我这一段说说怎么判定是不是positive的letter，该向谁要letter，以及如果自己写letter该怎么弄。有些限制推荐信数量的，我觉得都是坑。填推荐信其实特别快。我问过我所有老板，他们都说没数量限制。而且负责人的老板在你申请前，比如11月底，会主动抽时间和你商量一下你的申请，该怎么选校，该怎么写文书，一般老板越关心你的申请，越愿意和你聊你的申请，你拿到强推的可能性越高。至于该管谁要，尽量找你的科研老板，上课教师基本没啥用，即便是交换期间的美国授课老师也是不如国内老板的。美国有个词形容这一类推荐信，叫做DWIC，也就是do well in class，毫无信息量，因为上课的人太多了，即便你做了十分好的project，也没用。ms也一样。所以尽量找你的academic advisor，因为他们和你接触的最多。要知道，推荐信的强度和推荐人对你的熟悉程度直接挂钩，你认识越长这信说服力越强。但是很多时候国内老师不知道怎么写美国学校的lor，所以这就牵扯另一个问题，我们自己怎么写。首先是信的内容，主要就是要有具体的例子，不要泛泛，要从这几个例子得出被推荐人的品质，比如highly motivated，quick learner，clarity of thought, independent, hard-working, own initiative and self-driven，反正推荐信看的就是成为good researcher的潜力，一定要把相关的特质反映出来，但是不要凭空突然冒出一个形容词来，那样会很生硬。然后老美很夸张的，就不要太谦虚，就直接说recommende with no reservation。如果你觉得自己nb的很，大可以加上“这是我xxx年来见过的最nb的本科生，你不录取他我会和拼命的！”。除了信的本体，还要填一个调查问卷，渴望了解的quality列的很清楚。有些人不了解情况，觉得20%就不错，简直大错特错，那简直快和黑推差不多了。如果综合评价没有全在5%，也就是outstanding，基本上top phd就和你say goodbye了。哪怕是申请ms，也请厚着脸皮给自己勾选top 10%及以前的选项。有志于top phd的同学，请直接选前两项， top 5% or top 1%。
哦对了，补充一点，建议尽量去美国暑研拿美国推荐信。因为美国人很自大，即便是欧洲的推荐信很多分量也不重，他只看美国的letter，但欧洲、新加坡、香港的学校是认美国推荐信的。

CV：cv很重要，因为是最直观了解你的窗口。即便没有上传cv的窗口，也请在补充材料里面上传。cv不要太长，就2页。第一部分是教育背景，gpa啥的，如果排名好看就把排名加上去。第二部分是publication list，即便in submission的也加进去，当然你需要在letter里面有所呼应。然后把自己的名字标黑，按照作者顺序依次排列。后面可以加一个paper网页的超链接。不要没有paper，自己瞎编，这是诚信问题，后果十分严重。第三部分是你的project部分，著作等身的同学可以不写，但没paper的还是写一下吧。然后接下来的section你可以列一下你得到的各种award或者scholarship。最后一个section，写一下你掌握的技能，比如计算机涉及的各种tools，例如pytorch，还有你的语言能力，比如托福、GRE分数。

PS： 个人陈述其实没那么重要，至少肯定不如cv重要，虽然很多人鼓吹说我依靠与众不同的文书逆袭了。但洗洗睡吧，这事儿落不到你头上，你还是老老实实写一篇正常的八股ps比较靠谱。开头不要说什么自己小时候怎么样怎么样，搞得和二十四史帝王传记开篇一样天有异象。你是申请phd，不是申请当皇帝。没人care你小时候如何如何天纵奇才，或者是怎么开始搞计算机的。你就直接说，我对计算机感兴趣，对ai感兴趣，因为ai可以改变世界，改变人类，blablabla。然后你就需要把你列在cv里的代表性项目，用一个high-level的topic串联起来，来表达你曾经探索过什么方向。举个例子，比如我现在既做过few-shot，又搞过efficient ml，我就可以说我长期以来都对于如何在resource constraint的情况下提升deep learning model感兴趣。然后分别叙述这两个project。叙述project请简短叙述project是什么方向，然后highlight你做了啥，然后解释给了你哪些high-level的思考。陈述完个人过往经历之后，还要展望未来，说说你未来想干什么，这个部分可以针对不同学校定制，往该校相关方向关心的问题上面去靠。然后要写一段你愿意和学校的谁合作什么项目，一般一所学校列三个老师，不要太多，要不大家会觉得你海王。也不要太少，要不正好这老师不招生你就惨了。最后加一段结尾表达对该校衷心的热爱与对录取的期待。不要让ps超过两页。

选方向：
我大致谈谈AI的几大方向以及顶会，我把他分成了六大方向。
传统AI：现在做的人很少了，一般包括search、planning，其实bayes那些我觉得也可以算进来。顶会自然是aaai、ijcai，虽然这俩在cv领域不咋样。此外UAI也不错。
计算机视觉（cv)：顶会自然是cvpr、iccv、eccv。很多人说cv不行了，但是国外申请的人还是多的一笔。有一些小会议，比如WACV、BMVC或者3dv，感觉3dv其实还不错，就是topic比较窄，只局限在3d vision。BMVC因为牛津的人力捧，所以感觉比wacv强一点。
自然语言处理（nlp）：可能比cv申请更卷的方向，因为美本喜欢做，而且因为short、finding这些，paper数量大家都很多。请见acl、emnlp、naacl，而且一般以长文为主。short要弱一些，finding就更弱了。至于其他的像coling这种会其实都差一档。
机器学习（ml）：因为理论，所以自动筛掉了很多竞争者。也因为这样，相比其他方向，ICML/NIPS/ICLR的论文数量是最能体现四大优势的。其他几项csranking就是个笑话。当然AISTATS和COLT也很好，但更理论。其实AAAI的ml paper比cv paper质量高一些。
数据挖掘（DM）：这个领域基本是走日薄西山了，KDD已经不比10年前了，sigir更衰，我觉得已经混到cikm、icdm差不多的水平了。www会议还不错。而且这个领域的老师很多也在和nlp或者hci交叉，会投很多CHI或者acl这种会议。
机器人（Robotics）：Robotics感觉相当杂，基本cs、ee、me的人都在做，而且侧重点从偏perception到偏control的，这中间的差异可谓相当之大。一般传统上的三大顶会是ICRA/IROS/RSS，其中rss最好，iros相对最容易。近年还有做robot learning的人搞得CORL，北美反正是认这个会，可能国内因为ccf还没啥人投吧。
（5-14 16:02:37 916关注 128回复）

[洞主] 选校：
然后我要开始得罪人了，开始点评各个学校的AI综合实力。当然大家选校基本是靠排名，常见的排名包括USNEWS的cs专排以及csranking网站排名。前者是peer review的结果，比较靠谱，但有滞后性。后者是辣鸡，不要相信那个排名，大家看看老师有谁就好了，而且名单还不一定齐全。不过排名很多时候差个两三名但实力其实差不多，所以我把他们分了个档来排，同档的有些微差距但并不十分大。以下这个排名只反映AI综合实力，一不代表cs总体实力或者其他方向的实力，典型就是UIUC、UMich，他们system很好，但AI就一般。二不代表分项的实力，例如nlp和dm领域的排名就与之有很大出入。至于大家选校，还可以看看faculty跳槽的去向，毕竟faculty判断谁靠谱那是真的靠谱。
Tier 1：
四大yyds。不过CMU方差比较大，里面是真有些比较菜的老师的存在的。相对来说，斯坦福的cs基本坑货比较少，而且各个方向都十分强。MIT和Berkeley没有做data mining的，nlp的也很少，但Berkeley的cv和mit的robotics都逆天强。四大的共同特点就是ml都巨强，是直接拉出第五一档的强，而且人也特别多。
Tier1.5:
UW&Cornell: 两所基本在AI所有方向都很强的学校，但是加总起来从规模到质量都比四大稍差一点点的学校。UW主要是得益于西雅图的地理位置，msft和amazon钱给的多，而且像fb和google这些硅谷公司已经把西雅图变成了最大的分部，近十年来不知道从CMU挖了多少学术新星；cornell虽然在偏僻的伊萨卡，但是他在同处纽约州的纽约市建了康泰克校区，尽管坐公交要5个多小时吧。罗斯福岛地理位置很好，紧挨着google的office。虽然校园很小，但环境真的美如画。基本上，在工业界学术界联手搞事情的今天，地理位置的作用还是很大的。
Princeton：普林整体实力其实不如上面两所，主要是因为规模太小。不过要是你碰巧是普林的强势方向，也就是偏重理论的方向，特别是ml，普林真的是很好的选择，但越应用就相对越差一些。不过普林这种基本一个方向坑位很少，可选的老师很少，录取的人也很少，很可能你找不到你感兴趣的方向。
Caltech：更极端的例子，普林是你可能找不到对应的老师，caltech是除了极个别方向，比如rl啥的，你都找不到对应的导师。不过一旦有，还都是很好的！而且地处帕萨迪那，周围就是全美最好的中餐。
tier1和tier1.5的学校基本都不是rolling-based，就发一轮offer，然后没有拿到的发reject，因为他们有足够的信心会有达到预期数量的学生会take offer。当然一般也没有wl，因为他们第一轮发的数量就多于预期录取的数量了。mit是个例外，可能会有一些wl，但很难转正，因为锯掉mit的太少了。
Tier2：
UIUC：我把UIUC放这里真不是故意黑他。可能有人说uiuc不是有韩家伟这种超级华人ip，但很遗憾，dm community的影响力已经日薄西山了，而其他领域uiuc也不错但我觉得基本就是tier2的水平。我认为主要还是地理位置的原因。uiuc很多funding来时军方，像他们的nlp方向的paper的tease都r经常是战场背景……
UT-Austin：其实我甚至想把他放在tier2的第一个，但我怕uiuc的同学打我，而且UT的规模也不大。不过各个方向ut都还是做得不错的！而且陈平老师都住的地方，生活一定不那么困难！
UCSD：我觉得ucsd综合来看真的是很好的选择。各方向基本都有老师而且实力都还不错，像cv老师是又多又强。而且地处拉霍亚，冬天穿条短裤走路去沙滩的感觉不要太好。
Gatech：其实前两年我认为gt是最强的，奈何现在song le/hongyuan zha纷纷出走，其他一些老师沉迷industry不怎么在学校。但gt的底子还是很厚的，像cv/robotics都是十分的强。只是ml现在有点人去楼空。而且google也会在亚特兰大建新的分部，相信gt以后会更好。
UCLA: UCLA的ml这几年是真的不错。其他方向像nlp、dm这几年也都作出了一些不错的hiring。唯一就是cv方向现在朱松纯回国之后没什么人，可能也是以后要招人的方向。
UMICH: umich的sys很强，特别是arch方向，但ai真的一般。他最近做的几个hiring我也都认为一般，大家可以自己查csranking，人挺多，但个体实力我就不予置评了。当然像honglak这种没列出来，但他基本只招韩国人。
COLUMBIA: 哥大AI挺强的，基本上各个方向都有老师，就是许多老教师现在不是很活跃。每个方向的新老师也不是很多，基本上就一个。
PENN: PENN的robotics和nlp都很强，像grasp基本涵盖了robotics所有的方向了。而且今年penn cs也在积极招新的faculty。
HARVARD: 也是只有ml这种偏理论的方向，应用方向要么缺门，要么相对弱势。当然，哈佛的econ+cs、tcs还有ml都是不错的。加上哈佛的牌子，能去还是很不错的。
Tier3：
top30其他学校。其实像umd这种，实力也够tier2。所以我的分类准则是根据四大选手会选哪些做保底。就即便上了斯坦福的学生也会申请许多tier2的学校，但他们大概率不会申请tier3的学校了。不过tier3的学校也有很多很好的老师。BTW，我认为清华的ai实力在tier3，当然这没有考虑毕业出路等其他因素。

选老师：
其实老师比学校重要。老师主要是要看让你做什么，你做的topic直接影响你未来的出路。建议提前查看组里的同学都在做什么，以及他们毕业后的去向。基本这就是你未来的模板。然后还要关注和这个老师合作的舒适度，如果是个push或者放羊的主，你就要掂量掂量自己的个性了，毕竟五年快乐过下来比你做出多大成绩要重要。我见过很多北美phd读的很快乐的，也见过很多痛苦到quit的，主要的区别就是选了个什么样的老板。所以怎么能够掌握自己的方向都有哪些活跃的faculty，又怎么能够判断他们工作solid与否或者是否是rising star呢？除了csranking和官网，我还有一个建议是好好利用twitter。基本年轻的老师都会在上面推销自己的工作。而且有一些营销号，像AK，会转推好的arxiv new submission，比看arxiv daily高效多了，也比微信公众号那些花钱pr的paper质量好多了。

套磁：
我觉得其实对多数人没啥用，多数都是模板回复，毕竟多数人没到非你不可的地步。但我还是建议大家就像表白一样，宁可被拒也不要错过。就给自己选的professor of interest发一封邮件，说说自己对他的paper是多么的感兴趣。可能全是模板回复或者石沉大海，说欢迎申请或者你录取了我们详谈，但没准就有一个愿意和你面试呢。而且有些paper在投的同学，也可以通过email来和professor或者负责admission的staff来update你paper的情况。

面试：
基本所有学校都要有面试，第一轮基本在一月份，一般拿到面试就离offer很近了。多数学校的面试就是聊聊你cv上的paper，你想做的方向以及瞎扯淡。最重要的是放松，不要紧张，就正常的和老师交流，把你paper的细节清晰地说出来，从motivation到method再到取得的结果。然后要对面试老师近期的paper有所了解，建议仔细阅读他的homepage以及google scholar。我相信大家经过和暑研老师的meeting肯定对这个驾轻就熟了。

等结果：
一般会在一月底二月初开始出结果，tier2的学校到三月份也会接着发，毕竟要等第一轮录取的学生是否接前面学校的offer。大家也可以利用这个时间和学校更新自己cv上在投paper的情况，个别老师也会在三月份再安排面试。总之，耐心等待吧，这个过程很煎熬的。

非cs院系的ai：
其实除了cs系，ee/me这些院系也有做ai的，比如stanford的ee、Berkeley的me和mit的aeroastro。只不过他们光谱比较窄。ee基本偏signal processing，me基本只有robotics，这样到时候找工作的时候也会受限。比如me做robotics也基本都是去自动驾驶公司，相比之下cs做robotics的选择会宽的多。教职的话就更不用说了，cs做ai的可以找ee的教职，但ee做ai的找cs教职难度层级大大提高。所以即便差一层级的学校，建议大家还是优选cs，如果你想做ai的话。

ms的情况我写不动了，过两天我再开一个洞写一写。
所以总结一下timeline就是：认真刷gpa->srt或者联系老师去搬砖->考托福和GRE->联系暑研->拿到重要的海外推荐信->整理ps&cv->在申请网站上填申请->套磁->面试->等offer->决定去哪里->办签证买机票。

祝大家好运！欢迎大家在楼下提问。

[洞主] 因为上限1万字，所以我拆开发了。
[Alice] 看到陈平我实在绷不住了
[洞主] Re Alice: 嘿嘿😜
[Bob] 请教洞主，外系跨专业选手申CS master，推荐信是最好找谁写呢？因为没有科研经历，最多有一个实习可以用公司邮箱写，其余好像也只能找上课教师了
[Carol] Re : 谢谢dz！
[洞主] Re Bob: 找实习的出一封，其他的上课老师出。实习对于ms申请还是有用的，特别是大厂实习，当然美国企业更好了。我到时候会再开个洞讲ms的申请
[Bob] Re 洞主: 太好了，谢谢洞主！
[Dave] 呜呜呜dz真的太棒了 想知道传统工科跨专业申ai方向ms怎么准备比较好呢
[Eve] 感谢dz，顺便求问如果没有暑研是不是基本告别PhD了
[洞主] Re Dave: 其实除了cmu的ms，其他mscs方向分的没那么细。从提升自身的角度来说，就是做ai的research拿海外推荐信。从选项目的角度来说，选契合的specialization，而general的mscs没那么care这个，也可以申请其他专业的ms，比如ee的。
[Francis] 谢谢dz
[Grace] 请问绩点很拉垮（～3.5）但是有一作顶会，申请system方向的tier 2学校有什么把握嘛？有哪些学校不那么卡绩点呀
[洞主] Re Eve: emmm我觉得没美国推荐信的话，tier1和tier1.5可能性就不大了。tier2看你有没有两片以上的一作吧。当然tier3开始的学校还是有希望的。不过即便没有美国学术推，也请有其他的学术推，工业界sde实习的推荐信对phd申请作用很有限。
[Hans] Re 洞主: 推荐信对ms来说也是必要的吗？
[洞主] Re Grace: system的分档可能稍有出入。但我认为system有顶会一作还是很有竞争力的！我认为有一封strong letter申请tier2里的那些公立大u还是机会不小的
[洞主] Re Hans: 是的。推荐信，特别是美国推荐信无论是对ms还是phd都是很大的加成。不过每个学校口味不同啦，有些学校没有也可，有些学校非有不可。我之后会在ms申请洞里聊聊这个。大体说来，可能哥大mscs没有海外推还可以，uiuc有没有他本校的letter难度会差的很大，像cmu scs的很多ms项目现在甚至必须要paper
[Grace] Re 洞主: 谢谢🙏 那一般私立学校，常春藤这些都卡绩点吗？
[洞主] Re 洞主: 藤校绩点和出身看得更重，不过可能是录取名额少给我的错觉XD
[洞主] Re 洞主: 而且藤校的sys普遍不好…还不像ai
[Isabella] 火钳刘明
[Jason] 这么长，必火留名
[Kate] Re : liuming
[Louis] 想加dz联系方式，太专业了ww
[洞主] 开了个qq小号：2⃣️四壹肆7五2七9⃣️4。欢迎大家私信咨询
[Margaret] 感谢分享！
[Louis] 我竟然是dz好友
[洞主] Re Louis: 哈哈哈哈我觉得我大概知道你是谁了。我那会个号总共就没几个好友
[Nathan] 谢谢dz！Orz
[Olivia] Re 洞主: 谢谢洞主，大三暑研中特别迷茫，现在也算有方向了
[Paul] Re : 你说usnews靠谱，又说清华在tier3，但是清华在usnews的cs排名里是世界第4的。。。
[洞主] Re Paul: 我显然说的不是usnews的世界专业排名，明显是usnews的美国国内cs专业排名。凡是四大不是前四的排名都是辣鸡。
link：https://www.usnews.com/best-graduate-schools/top-science-schools/computer-science-rankings
[Paul] Re : “你大四申请的时候中了三篇icml/nips/iclr一作，要是没有四大offer，我可以跟你姓”
至少我知道不少一堆这些顶会、但是申请结果并不好的例子。强推荐信才是最重头。
[洞主] Re Paul: 哦哪个大四的申请时候三片已经中了的icml/nips/iclr一作申请不好了？不要拿延毕和gap的例子出来，
[Paul] Re 洞主: https://www.usnews.com/education/best-global-universities/computer-science
这也是usnews的，清华在第四，为什么世界范围的就不可信呢？
[洞主] Re Paul: 因为评价方式不一样，美国国内排名是usnews给各学校发问卷大家peer review出来的，但世界排名不是这么排的。这就好比usnews的美国综排很靠谱，但他的世界大学总排名就不那么可靠了。同理还有他的全球engineering school排名
[Bob] 看其他洞里说最好看cs ranking？
[洞主] Re Paul: 说看csranking的一般还处于入了门但不是很懂的状态，也就是半懂不懂。csranking有几个问题，一是paper数量排名就很扯，paper水平完全不一样怎么能相同权重计算数量，像cvpr水文一大把，全部计算之下难免鱼龙混杂、泥沙俱下。而且top school更渴望做有impact的工作而不是短平快地堆数量。有个榜单是专门计算best paper的，可能还更有说服力，如果数oral数量可能也是有说服力的。第二个，会议水平不同，aaai和icml相同权重算paper数量，简直太扯。第三个，不同方向产量不同，system和ai比数量永远比不过。第四个，csranking对faculty多的学校友好，所以像普林不知到哪里去了，caltech更惨。第五个，csranking作者经常会手动去掉那些他认为走了的或者去工业界的人，但是在industry挂职的有一部分还在学校积极带学生。而且他经常有些去掉了有些没去掉，像文中的song-chun zhu他就去掉了，但le song就还在。所以那个排名你看看就好
[Queen] Re 洞主: csranking里即使是算每个faculty的平均产出，清华在ai领域也超过四大了。
不过我认同你说的目前清华缺乏开创性工作的说法，但不意味着在你读博五年期间就不会有吧，总之我感觉清华cs还是越来越好的，五年后水平跃升至tier1也未可知。
[Richard] Re Queen: 只算icml、kdd、nips，csranking上清华能排第五，四大在前四，faculty数量都差不多，但是把kdd去掉清华就掉到13名了
csranking上面没有统计iclr
[洞主] Re Queen: 简单计数本来就没什么意义，ccpr与cvpr的差距大了去了，清华有哪一个ai主流会议的best paper吗？icml/iclr/nips/cvpr/iccv/eccv/acl/emnlp。你再去看看四大的数量。科研可不讲什么三个臭皮匠胜过一个一个诸葛亮，或者三篇水文顶一篇oral。至于你说五年之内一下大翻身，突然就开创性工作井喷了，这现实吗？清华cs越来越好不假，但五年内成为tier1的可能性和中芯五年内突破7nm芯片制程的可能性差不多。根本原因是faculty不会突变。清华ai faculty能在北美top20拿到教职的寥寥无几，我想来想去也就朱军是一个，其他的都够呛。即便茶园新招的几个，你让他们在北美找教职，他们也很难找到。同做cv的，不说jun-yan，就是xiaolong wang就比他们有竞争力的多，google、fb两个fellowship，efros的postdoc，也就是ucsd。而且还有non-local这样的工作。你没有那样的领袖人才，拿什么去凭空冲击tier1？
[洞主] Re Richard: kdd的google scholar metric已经和ml三大会拉开差距了，没记错的话都不如aaai。没人cite的area是不会长久繁荣的
[Susan] 好顶赞
[Queen] Re 洞主: 你说得太短视了。phd期间做出有高impact的工作是非常看运气的，清华年轻faculty并不差，虽然现在impact可能与顶校ap比不够，但并不意味着他们没有能力、以后不能做出好工作。举个例子，ai拿图灵奖的那三位也不在你说的那些顶校里吧？
五年的尺度是很大的，大到五年后可能已经没人做ai了；至少和五年前的对比清华是突飞猛进的，我对清华保有信心。
[Thomas] 求问洞主觉得mila处于哪种水平？
[Uma] 感谢dz这么认真的分享（体感本科清华的dl挺多的，但回来的少且回来做出成绩的也少
[Vivian] Re 洞主: 这有点过分了吧……贵系是没几个老师能在北美拿到教职，但这主要是学校(中国博）因素吧。jun zhu 当年有 cmu 的教职 offer，这可比 cmu phd 拿到难10倍吧。茶园那几个拿你列的 tier 2 里靠后的几所教职问题不大(你这个 t2 有点太广了)。xiaolong wang 基本是年轻一代 cv 的最强水平了，他去 ucsd 的原因很简单(虽然 ucsd 也很好了），就是老板坑。Abhnaiv 现在主要在 industry，不太管学生，而且这人很偏袒印度老乡，每年总结吹他印度老乡表现最好，最后也没强推 xiaolong
[Xander] Re 洞主: 美国的学术界就是九品中正制，拿教职成果是一方面，种族、性别、出身、推荐等等都占很大比重。拿不到美国顶校教职不代表水平就不足，拿到了也不代表就一定很厉害。清华cs博能拿美国顶校教职的基本都几篇best paper傍身，这难度、能力、运气比美国博强太多了。
[Vivian] Re Queen: 确实，按照 dz 这个 metric，dl 顶校应该是多大牛津
[Louis] Re Xander: 清华cs博能拿到顶校教职？
[Xander] Re Louis: 能，虽然很少。比如Xi Chen(columbia) 、Fei Wang(cornell) 、还有vivian提到的朱军(cmu)等
[Xander] Re Xander: 清华cs青年老师水平其实真不弱，部分中年的老师也是很厉害的，虽然可能没有很大的title和国际名声。
[Vivian] Re Xander: 贵系年轻老师虽然都是土博，但是学术水平真的超强了……在贵系都不是很火的youyou lu，在file system这个方向也是世界上年轻一代top1的水平
[Xander] Re Vivian: 是的，还有叉院的一些老师学术水平也非常强
[Yasmine] 感谢dz
[洞主] Re Queen: 你说有没有可能性某个人灵光乍现，做出个了不起work，我觉得是有的，但你说的可是五年成为tier1水准，那可不是什么一个人灵光乍现，那是需要各方向都有一堆人灵光乍现。虽然很多时候预测未来永远不说没有，但这个概率小到可怜。
[洞主] Re Thomas: mila和uoft我没加进来的原因在加拿大，不考虑在加拿大我愿意给划到tier1.5，考虑在加拿大可能我会认为是tier2？毕竟去industry加拿大机会还是少一些。
[洞主] Re Vivian: oxford的cv可以排tier1-tier1.5。uoft我觉得是tier1.5-tier2
[洞主] Re Xander: 你说做cv那几个吗？我觉得他们还真拿不到t2后几个。yi li、huazhe、zhao hang、gao yang，你说说他们几个能拿到哪个？bolei 当年也只拿到cu Boulder，我觉得他们的竞争力还不如bolei。除了nlp的zhilin可能能拿到
[洞主] Re Xander: 清华博能拿到美国phd是难度更大更nb没有错啊，但有几个呢？ai就朱军一个吧。你不能拿凤毛麟角来说事吧，清华博士的数量那么多
[洞主] Re Xander: 这里面就做ai的只有朱军，清华做ai的老师数量那么多都是朱军水平？
[洞主] Re Vivian: 怎么全在往别的方向扯，你大可以说说ai方向哪个年轻人是top1。
[Zach] 洞主说了好多实在话，内容详尽又有深度，我申请季时看了许多类似的中英文长文，写得这么好又切合清华学生现况的独此一家，支持一个。
[Olivia] Re : 洞主觉得USC的CS怎么样呢？
[Vivian] Re 洞主: dz 好凶，ssfd。雷系黄高算是 top 1 有力竞争者吧？再说了，你列的这些 tier 2的学校就都有 top 1？那 dz 大可说说觉得 UMich、Harvard 哪些 AI 方向哪些年轻人可以是 top 1？或者干脆说说你排的 T2 里后四个哪个年轻老师有 densenet 这种 work？我觉得黑大清 PhD 不好找教职、很多中老年以及搞行政的老师很坑爹都没问题，但是黑清华 AI 这个方向的学术水平黑到连哈佛都不如实在太过了。
[洞主] Re Olivia: graphics很好，robotics、nlp也不错。但总体来说我觉得tier3。
[洞主] Re Vivian: huanggao怎么就是top1了？？？那liu zhuang是phd top1？也没有吧？毕竟也没看liuzhuang拿任何的fellowship啊？
而且densenet也是在Killian手下做出来的，huang gao最近的paper离best award还差好远呢吧？一来这文章产出时候在cornell不在清华，二来产出作者回了清华之后这两年不再能发出来这个水平的paper。所以能用densenet作为清华ai的水平？就好像能用faster rcnn或者resnet作为中科大cs的水平吗？shaoqing那时候名义还是联培phd呢。如果huanggao能够在清华依然像在cornell那样产出高质量paper，那可能可以算top1。
至于umich，我认为honglak和朱军差不多，比黄高强。哈佛可能ai实力也是tier3，很可能是不如umd的，我之所以把哈佛放tier2，umd放tier3也说的很清楚了，因为申请的时候很多做ml去四大的会申请哈佛，而不会申请umd。我虽然也认为umd实力更好，但我选哈佛。你说哈佛ai实力不如清华，我也是赞成的。
[Queen] Re 洞主: 我的意思是说phd期间做出好工作需要灵光乍现、需要运气，然后才好找顶校教职，但基本能力具备后，没有这个运气的并不意味着以后不会有，有这个运气的也不意味着以后还有。比如你列举的song han，假如他“灵光乍不现”就没有发模型压缩的那篇工作（或者有人先于他发了），他还能找到mit教职吗？我看不能吧。当然入顶校有顶级phd形成正向循环，基本不用担心未来缺乏“运气”了。
我的意思就是，清华的这些年轻老师获得“运气”的基本能力并没有问题，虽然现下还没有这个运气（当然有的比如yi wu也有不错的代表作了），但是未来完全可期。
[洞主] Re Queen: 我并不认为韩松那就是运气，我觉得那是insight，总是比人家快一步想到，怎么能用运气就涵盖了呢？resnet那么简单，是不是也是运气呢？
而且对个人是运气，很多人就不能用运气说事儿了。难道清华风水有问题，才导致过去所有phd的运气都不好？而且我拿北美教职说事儿只是针对海外phd回清华任教的这一群人，毕竟茶园最近招了一批四大phd。我并没有以此为标准拿土博和他们比，土博我就是在比工作的质量。
至于有没有能力，我见过很多考不上清华的也说自己能力很强呢。但科研评价是看你做出什么成果，没有任何一个奖是因为我们认为你实力强颁给你的吧
[Grace] 请问Uchicago怎么样呢？
[洞主] https://jeffhuang.com/best_paper_awards/
wozhao
我终于找到了best paper数量的排名，虽然这个ranking也很扯。一个是有些方向best paper发的太多，说的就是你，hci。另一个是best paper很多时候选的也很迷，一个会议上最好的工作往往不是best paper，而是test of time，但那个要十年后才知道。但这个排名依然某种程度上反映了不同机构高质量research的产出情况。虽然不用纠结具体先后顺序，但可以看看大趋势，有个基本的认知就ok了
[洞主] Re Grace: uchi连cs系都没吧。。。妥妥的tier3啊……虽然像junchen jiang还不错。不知道你算不算ttic，ttic的nlp/cv也都还可以
[Thomas] Re 洞主: 加国industry这方面确实也是个考虑因素🥲
[Angry Alice] dz dm方向怎么选校呢？好多学校都无
[洞主] Re Angry Alice: 纯正dm啊，一般就斯坦福、cmu、uw、cornell、uiuc、gatech、ucla、ucsd、columbia、usc这些。一般来说这些学校的ml许多都比较human-centered，所以dm还是挺多的。然后建议研究jiawei徒子徒孙都在哪里。还有其他大佬比如刘欢、phillip yu、xiong hui这些大佬，还有pei jian这样在加拿大的。
然后根据自己的方向做交叉。数学比较好交叉ml混申，做的都是text-based的dm建议申请些nlp老师。如果偏计算社会学，可以考虑hci。比如许多学校ischool都有ds和hci交叉的老师，典型的Berkeley还有uw。
[洞主] Re Zach: zach说得好😉
[Angry Alice] Re 洞主: 很有帮助，谢谢dz

[Xander] Re 洞主: 像茶园的yi wu、zhilin yang、yang yuan这些人拿tier2教职应该是没有问题的
[洞主] Re Xander: 我觉得yang yuan做的方向找tier2很吃亏，我觉得他未必强于rong ge。yi wu我觉得tier2还是可以的。
[Angry Bob] 感谢dz
[Angry Carol] 个人很赞同dz说的，清华做AI几乎没有high imapct的工作，gao huang的dense net严格来讲也不一定称得上high impact，国内high impact几乎只有kaiming的resnet
[洞主] Re Angry Carol: 还有faster-rcnn
[Angry Carol] 另外清华AI的青年中坚lzy lms hg ljw这些老师个人认为实际水平和能力跟欧美国家以及新加坡hk等地的青年俊杰比还是有差距的。加之国内环境追求短平快，不认为五年后清华可以做出high impact工作，类似于不认为五年后可以7nm芯片
[Angry Carol] Re 洞主: faster rcnn和resnet还不在一个档次
[洞主] Re Angry Carol: 我觉得算得上high impact了。只不过resnet更general，但faster-rcnn基本是一代two-stage detector的baseline了，完全是和yolo这些一档次的work，绝对是high impact的工作。
[洞主] Re Angry Carol: 这几个大水车吧，有些还要靠学生自己。我觉得指望茶园新招的那些还靠谱一些
[Angry Carol] Re 洞主: 这个档次没问题，但是resnet已经是可以媲美good fellow提出GAN、max welling提出VAE这个级别的重大突破了
[Angry Carol] Re 洞主: faster rcnn跟junyan zhu的cyclegan应该也差不多档次了
[洞主] Re Angry Carol: 我觉得resnet是和alexnet一个level的，影响力可能超越gan，但gan的创新性是划时代的，只不过做判别模型的应用比生成模型广。faster-rcnn到不了这个fundamental的级别，但是他奠定了detection这一个主流领域的的主流方向，而且也作为下游领域最普遍使用的detector。单论模型对模型，从impact上我认为可能比cyclegan要强。但cycle consistency的这个idea更有意思也启发了更多其他的方法
[Angry Dave] 催更一点MS申请qwq
[洞主] Re Angry Dave: 稍安勿躁，dz周末在玩耍中，争取周一前完稿
[Angry Carol] Re 洞主: 主要cycle consistency后来成为了无监督学习的经典范式之一，因此我认为impact不弱于faster rcnn。无监督是AI的核心问题之一
[洞主] Re Angry Carol: 怎么说，我觉得cyclegan模型本身impact是比不过faster-rcnn的。cycle consistency当然是他的带火的，但这个东西之前在nlp就有类似的思想了。所以我认同cycle consistency和faster-rcnn一个level，但cyclegan不是
[Angry Carol] Re 洞主: 刚列举的几位感觉都在国内读的博士，没有师从顶级大牛深造的经历。而且一般拿到终身教职尤其是正高后就会参与各种领导工作，拿企业兼职，不会一直深入钻研积淀。不少实验室好像要靠学生厉害带着发论文。这种环境背景下感觉出faster rcnn都难，更何况resnet这种重大基础性突破
[Xander] Re Angry Carol: 也不能这么说吧，resnet不也是学生(kaiming等人)做出来的，国外一些甩手掌柜型导师的学生也有好工作。记得之前openai的dalle，算一个突破了吧，清华唐杰组也在做类似的、只是慢了一步。
[洞主] Re Angry Carol: 所见略同
[Angry Carol] Re Xander: kaiming是jian sun带出来的
[Xander] Re Angry Carol: 那你觉得kaiming的一系列工作都是由导师带出来的吗？明显更多是kaiming自己作为学生做出来的。只要基本环境（氛围）到位了，做出什么来取决于学生自己，但统计意义上就会涌现出很多好工作。这个基本环境，清华和最一流的当然还有差距，但是进步是很明显的。
[洞主] Re Xander: kaiming11年就lead researcher了，明显不能学生吧。而且不就一个kaiming吗，人家能做出来也是因为当时msra还人才济济，有孙剑，那是马毅应该也在。而且相对来说msra的职称体系比国内教职简单得多。前两天wenhu chen还抱怨根本看不懂国内职称体系以及各种帽子的区别。链接在这，https://www.zhihu.com/question/344449272/answer/1880118576。清华能有当年kaiming在的那个msra的环境吗？何况kaiming现在也跑fair去了。你不能拿kaiming做清华水平的代表，虽然他是清华本科；也不能做msra其他人水平代表，因为msra现在明显不复当年；更不能当作普通清华学生的范本吧，全世界有几个人敢拍着胸脯说有kaiming的条件也能做出那种工作？
[Angry Carol] Re Xander: 早期肯定受益于jian sun这么强的老师用心培养，才打好了做研究的基础，帮助他找到了自己擅长的地方，并指导他第一篇就拿到best paper。可是清华又有多少博士有这种机会？
[Angry Eve] Re 洞主: dz牛逼
[Angry Francis] Re 洞主: dz牛逼

[Angry Grace] 打扰洞主 想问一下文科跨专业学生想在两年内申请cs phd如何安排呢？ 能否推荐一下具体的学习路径 感谢
[洞主] Re Angry Grace: 首先你要选择一个对文科友好的方向，典型就是hci或者computational social science这种。然后你要去cs系做科研，拿到cs系的推荐信，作为文科生，你最大的希望是拿到return offer。适当修一些数据结构、数据科学这种cs课，操作系统或者计算机网络虽然是cs系基础课，但其实你不用修。当然你可以申请一些ischool的hci项目，比如Berkeley、uw、umich、cornell。像cmu在scs这个school下面有hci这个department。mit的media lab偏向文理设计大交叉，但bar很高，像uw还有hcde也是类似ischool的存在
[Angry Grace] Re 洞主: 十分感谢您的时间与解答~ 很有帮助~目前自己大二 对CS方向很感兴趣~希望您生活愉快
[Angry Hans] 想请教一下dz对于现阶段美国读书的安全性问题怎么看呢？不（仅）是枪击抢劫呀什么的这些治安事件，更多是现在的政治环境下有可能遇到一些预料之外的操作？因为自己有几个相关的data point所以有些虚，想听听dz的看法。
[Angry Isabella] Re Angry Hans: 还有疫情因素
[洞主] Re Angry Hans: 我觉得看你的专业了，以及你对老板从darpa这种军方拿了多少钱。像ai里面robotics可能会比较敏感，但像ml这种偏理论的和军事应用关联不大的可能就会好得多。
[Angry Jason] 想问一下IR是属于DM方向吗？cz是小白不太懂这些专业术语，这么看的话，我直接一脚踏入了夕阳产业吗……可是我感觉推荐在工业届成果遍地开花啊。另外，我大二才开始做科研，现在基本还在读论文，复现别人的model的阶段，大三发出顶会一作的可能性微乎甚微，这样看，我是不是还得乖乖直博呀。
[洞主] Re Angry Jason: ir？我觉得比dm更夕阳，国外做ir投sigir的少之又少。而且ir基本和recommender system是个镜像领域，基本就是来回抄。至于工业界，他本来和学术界的性质就不一样啊，许多工业界用的风生水起的东西很早就没人研究了吧。就比如搜索引擎，00年之前很多人研究，现在早没人做了，但不妨碍search engine还是Google最挣钱的事业线吧。学术界本来很多时候就是会更超前，更原型化，更偏向制造prototype。尤其美国学术界更是如此，国内学界很多时候的责任是要突破卡脖子，所以很多学术机构会像小公司那样干工程。
至于paper嘛，都是有个过程的，大二发不出来很正常，最好找个学长带你，走一遍发论文的流程。你走过整个做实验、写论文、投稿、rebuttal整个流程之后才能真正学会怎么做论文，各种关键必须亲身经历才能领悟。
当然我也不是说你要转行，不做ir了，就是单纯说可能你到时候需要申请点dm或者nlp的老师。虽然sigir含金量不如其他许多ai会议，但能中比啥也没有强一百倍。只不过现在还投sigir的好学校可能也就uiuc了吧？
[Angry Jason] Re 洞主: 哎呀，现在转NLP的话感觉大三是不太可能发论文了（笑哭）。如果我在IR领域做出成果，将来申偏NLP方向的话会很难吗？还是应该现在转NLP，看看大三能不能发出paper？
[洞主] Re 洞主: 我觉得现在别转nlp了，可以在ir做的偏nlp一点，或者偏dm也还可以。然后申请的时候就挑韩家伟的徒子徒孙申请，就是什么uiuc啦、ucla啦、gatech啦、usc啦。基本mit和伯克利我觉得和你就say goodbye了。不过斯坦福还是有戏的，因为我觉得斯坦福对方向match的程度要求没那么高，毕竟进去之后rotation，他更喜欢你表现的潜力，即便sigir也是可以的。cmu嘛，可能lti有点戏吧，但可选择的老师可能很少。。。不过做ir要是发了ml顶会，像nips/iclr还是管用的。
[Angry Jason] Re 洞主: 嗯嗯，谢谢洞主指导！
[Angry Kate] Re 洞主: 催更dz MS申请洞~
[Angry Louis] 铜球master申请洞~
[Angry Margaret] 想请教一下dz，清华的老板写推荐信的话，效力大概有多大呢？
[洞主] Re Angry Louis: 正在写。。。
[洞主] Re Angry Margaret: 清华老板啊，作用一般…不过也得看你老板和美国圈子的connection具体如何
[洞主] Re Angry Margaret: 可能对华人教授，特别是有清华背景的比较有用，但对其他人可能就作用寥寥了
[Angry Nathan] cy
[Angry Olivia] dz觉得jian pei怎么样？老师是大牛但那个学校有点差
[Angry Olivia] 另外如果从未来大厂想找工作的角度，AI做什么方向好呢？
[Angry Paul] Re Angry Olivia: 加拿大的工作机会和薪资都比不上美国，jian pei本人是大佬
[Angry Paul] Re Angry Olivia: 如果在美国找工作，我实话说所有的方向都好找工作…
[Angry Olivia] Re Angry Paul: 那在国内呢
[Angry Paul] Re Angry Olivia: 国内可能做推荐系统、数据挖掘或者nlp这些能直接对接业务的更吃香吧。robotics感觉工作很受限
[Angry Queen] 请问三封推荐信一般都从哪里来呢？cz国内老板一封，（如果有）暑研老板一封，那么第三封从哪里来呢？
[Angry Richard] Re Angry Queen: 任课老师

https://web.thuhole.com/##482406
#324735
再来打个补丁，关于30名-50名的phd。实话说，很多清华同学看不上这个档次，但如果能接受未来在美国工作，这个level的phd也没啥不好，即便去不了google brain或者fair，去个其他的research部门还是没那么难的。而且回国去个中游985基本也不是很难。对于保研中拿不到名额的同学其实这是一条不错的道路。

可能有人会问，我保研都保不上，还能申请到北美top50 phd？实话说有几个诀窍，能极大增进你拿offer的概率。那就是尽可能找偏僻大公校的华人导师。偏僻的地方美国人不爱去（美国人匹兹堡就不爱去了），大公校对gpa的执念相对低一些，华人导师看中清华身份，即便分低也会觉得能上清华就是可造之才，只不过被暂时埋没了。所以只要选导师科学一点，申请个30-50名的ai phd并没有那么难。也不需要你要有什么paper的，可能就一段随便的科研经历。至于gpa，3.2、3.3也并非不够用。

我给大家列几个学校，毕竟的确这些学校你们平时都没听说过。
u minnesota
ohio state
u north Carolina（nlp就别想了，但除了nlp我也不记得还有谁…）
penn state
uc Irvine
u Virginia
rutgers
uc-davis
stony brook
uc- Boulder（科罗拉多！！）
arizona state
Virginia tech
tamu
utah
boston university
neu
upitts
wustl
michigan state
uc-santa cruz

当然可能有些人觉得去了这里又不甘心，那我再教大家一招，叫做投资潜力股。有些老师和你们一样不甘心这些学校，特别是刚毕业的年轻ap。所以他们会拼命工作，第一个tenure五年到期之后就会跳槽到top30的学校。所以建议大家重点关注一下这些ap，这样就可以和老板一起进步，实现曲线救国，学历完成重大升级。


（9-17 3:28:55 195关注 55回复）

[Alice] phd入学和毕业可以不是同一个学校吗
[洞主] Re Alice: 多了去了
[洞主] Re Alice: 见过好多从这个档次跳到top20的phd
[洞主] Re Alice: 但是要注意的是，如果老板跳槽的时候如果你已经博四博五了可能就不带你去新学校了。所以要挑那些tenure已经开始了一段时间了，马上一两年内就要开始重新找工作准备跳槽的那种
[洞主] 或许bu和neu也没那么容易…这俩排名我认为被低估了，尤其neu，我觉得neu是有top30的水平的，结果被usnews排了个49…今年david bau从mit phd毕业放弃了cmu的offer去了neu。
[Bob] 确实 洞主真的方方面面都是行家啊
[Carol] Re 洞主: 我感觉UNC被你低估了啊，北卡的CV也挺厉害的吧
[洞主] Re Carol: 有可能，的确被我低估了
[Dave] hhh ucb!
[Eve] 什么德州农机啊也可以试一试
[洞主] Re Eve: 就tamu啊
[Eve] Re 洞主: 哦哦没看见，gatech性价比也不错
[洞主] Re Eve: ？？？gt那是前十的学校，不是三五十名可以bideq
[Eve] Re 洞主: ？？？gatech怎么能排到前十大哥
[洞主] Re Eve: gatech显然前十好吧
[Eve] Re 洞主: 不是caltech啊
[洞主] Re Eve: caltech应该是排不了前十的
[Eve] Re 洞主: 我觉得caltech前十，gatech也就三十
[洞主] Re Eve: 您做过科研吗？？？
[Eve] Re 洞主: 做过，我还申请过，caltech和galtech都试过
[洞主] Re Eve: 两个offer我会选Caltech，如果有合适的导师的话。但caltech的问题是规模太小，大概率无match的人选，毕竟连独立的cs系都没有，只有个cms。综合考虑gt绝对强于caltech
[洞主] Re Eve: gt的hci ubicomp robotics都是全美排很前的，你告诉我排30名？？？
[Dave] Re 洞主: Eve可能不是cs的？
[洞主] Re Dave: 反正eve对cs应该是完全不了解
[Eve] Re Dave: 我是cs啊。可能当初申请的太容易有错觉吧
[洞主] Re Eve: 敢问您是以3.5以下gpa拿的offer？
[Dave] （我作为贵系平均水平，被里面的两所拒过，也没那么容易吧
[洞主] Re Dave: 哦申请嘛中一所就OK了，而且也得考虑你做的方向，我只是提供个list给大家去试一试
[Francis] 这样的话需要提前找目标导师陶瓷吗？还是录取后再选老师？不太懂美国PhD是怎么分配学生导师的。
[洞主] Re Francis: 越往后的学校fellowship越少，就要靠老师的ra，一般是更需要陶瓷的
[Grace] 强啊
[Hans] 又来了，估计dz和前段时间搞什么ai排名、phd申请夹带私货的那个是同一个人吧？这么喜欢在萌新之中找存在感的吗？
哦看了下引用的洞，真是同一个人啊，猜对了。。。
[洞主] Re Hans: 夹带的私货就是清华是tier3吗？那的确是我的观点，难道还不能说吗？
[Isabella] 杨振宁在stony brook有个研究所
[Jason] Re Isabella: 物理数学和cs是不一样的
[Isabella] TAMU应该就是texas A&M吧，也挺不错的，至少在德州有影响力
[洞主] Re Isabella: 这个不能拿stonybrook的物理来参考他的cs吧😅
[洞主] Re Isabella: tamu就还不错啊，但门槛就没那么高，还很多人看到农机就直接拉黑了
[Kate] cz是＃481515 dz，正在讨论30-50 phd申请难度的问题，我认为是完全不用paper的，dz信息非常有用，感谢了！
[Isabella] Re 洞主: 确实不能用物理来参考cs的情况，只是觉得不少tier2学校也有大山头
[Isabella] Re 洞主: 清华以前也有录取到caltech的cms的同学，都是GPA大佬+UGVR推荐信（或者等价暑研），而且本科专业特别杂，有力学的机械的电子的。。。 
[Louis] Re Isabella: 我大电子也成了杂专业😂
[洞主] Re Isabella: caltech难度主要在没有match的老师
[Margaret] 说实话，现在run到北美已经错过Big Tech的红利期了，美股市值/GDP 200%，百年历史大顶，而湾区码农的高收入基本来自于所在公司的股票暴力上涨，微软的市值已经接近英国GDP了，意味着未来10年工资基本不会再涨，而北美的房价正以每年30%的速度前所未有地飞速上涨中，湾区200w usd的房子勉强能看，生活成本属实不低。
[Margaret] 北京城区人均gdp都4w美元了，run到北美中西部村里属实是有待商榷。
[Nathan] 但这种怎么确定导师是否nice呢
[Francis] Re Margaret: 那西雅图呢
[Margaret] Re Francis: 西雅图挺好，加州税太高了，差不多得有50%
[Olivia] 看来ucsb能进30啊
[洞主] Re Margaret: fresh grad加州税也就40%
[洞主] Re Olivia: ucsb只是系很小，影响了他的csranking排名，论申请难度绝对是前30的
[Paul] 补充一下非CS的经验，我基本是复制了楼主的操作，去某Top30以外的学校找了做的不错的年轻华人AP。我大概是大三升大四八月份开始跟那个老师做了一段时间科研，当时纠结保不保研纠结了好久，所以开始找暑研已经八月份了。

实话实说我科研真的很菜，不是夸张，我暑研做的内容都比不上平时上课的大作业，但我导师somehow就感觉我是个可造之材对我很好。经历了一番是否学历降级的思想斗争还是去了这个学校，没读master也没直接工作。
[Paul] Re Paul: 现在体验挺好的，学校氛围好一点也不卷，可能因为学校一般吧，周围的朋友也都心态比较平和不焦虑。导师年轻，所以基本手把手带我科研。未来的话无论工作还是学术都有出路。当然如果你天天想着，我清本同学怎么去了MIT，我来了这么个野鸡大学，就活得很痛苦。专注于自己的学习科研会很充实快乐。
[Isabella] Re Paul: 清本的同学很少能去MIT级别的学校吧，大多数其实也就是在top30左右的PhD，不过也有先读master当跳板的，cz家里没太多资金，可能就直接PhD了
[Isabella] Re 洞主: ucsb的system挺强的