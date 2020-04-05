## 模型设计阶段性报告
协同过滤，从字面上理解，包括协同和过滤两个操作。所谓协同就是利用群体的行为来做决策(推荐)，生物上有协同进化的说法，通过协同的作用，让群体逐步进化到更佳的状态。对于推荐系统来说，通过用户的持续协同作用，最终给用户的推荐会越来越准。而过滤，就是从可行的决策(推荐)方案(标的物)中将用户喜欢的方案(标的物)找(过滤)出来。

具体来说，协同过滤的思路是通过群体的行为来找到某种相似性(用户之间的相似性或者标的物之间的相似性)，通过该相似性来为用户做决策和推荐。

现实生活中有很多协同过滤的案例及思想体现，除了前面提到的生物的进化是一种”协同过滤“作用外，我认为人类喜欢追求相亲中的“门当户对”，其实也是一种协同过滤思想的反射，门当户对实际上是建立了相亲男女的一种“相似度”(家庭背景、出身、生活习惯、为人处世、消费观、甚至价值观可能会相似)，给自己找一个门当户对的伴侣就是一种“过滤”，当双方”门当户对“时，各方面的习惯及价值观会更相似，未来幸福的概率也会更大。如果整个社会具备这样的传统和风气，以及在真实”案例“中”门当户对“的夫妻确实会更和谐，通过”协同进化“作用，大家会越来越认同这种方式。我个人也觉得”门当户对“是有一定道理的。

协同过滤利用了两个非常朴素的自然哲学思想：“群体的智慧”和“相似的物体具备相似的性质”，群体的智慧从数学上讲应该满足一定的统计学规律，是一种朝向平衡稳定态发展的动态过程，越相似的物体化学及物理组成越一致，当然表现的外在特性会更相似。虽然这两个思想很简单，也很容易理解，但是正因为思想很朴素，价值反而非常大。所以协同过滤算法原理很简单，但是效果很不错，而且也非常容易实现。
### model_0
结合使用文本卷积、GRU（Gate Recurrent Unit）循环神经网络构建模型。


### model_1
结合使用文本卷积、lstm循环神经网络构建模型。

### model_2
### model_3
### model_4