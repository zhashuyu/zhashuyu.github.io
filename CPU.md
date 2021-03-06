目前，主要的CPU架构有四种：ARM、X86、MIPS、Power。


其中ARM/MIPS/Power均是基于精简指令集机器处理器的架构；X86则是基于复杂指令集的架构，Atom是x86或者是x86指令集的精简版。

    精简指令集，是计算机中央处理器的一种设计模式，也被称为RISC(Reduced Instruction Set Computing的缩写)。特点是所有指令的格式都是一致的，所有指令的指令周期也是相同的，并且采用流水线技术。
    复杂指令集，英文名是CISC（Complex Instruction Set Computer的缩写）。它是英特尔生产的x86系列（也就是IA-32架构）CPU及其兼容CPU，如AMD、VIA的。即使是现在新起的X86-64（也被称为AMD64）都是属于CISC的范畴。


ARM、X86、MIPS和Power简介


### ARM

ARM架构过去称作进阶精简指令集机器（Advanced RISC Machine，更早称作：Acorn RISC Machine），是一个32位精简指令集（RISC）处理器架构，其广泛地使用在许多嵌入式系统设计。由于节能的特点，ARM处理器非常适用于移动通讯领域，符合其主要设计目标为低耗电的特性。

### x86

xx86或80x86是Intel首先开发制造的一种微处理器体系结构的泛称。x86架构是重要地可变指令长度的CISC（复杂指令集电脑，Complex Instruction Set Computer）。

### MIPS

MIPS，是一种采取精简指令集（RISC）的处理器架构，1981年出现，由MIPS科技公司开发并授权，广泛被使用在许多电子产品、网络设备、个人娱乐装置与商业装置上。最早的MIPS架构是32位，最新的版本已经变成64位。不过MIPS目前已经不是市场主流。

### Power

POWER是1991年，Apple、IBM、Motorola组成的AIM联盟所发展出的微处理器架构。PowerPC是整个AIM平台的一部分，并且是到目前为止唯一的一部分。Power架构目前也不是市场主流了，发展前景并不被看好。


## 国产处理器

目前，在移动芯片领域，ARM架构的芯片占据了90%以上的市场份额，在服务器CPU市场上，英特尔X86处理器占据超过90%市场份额。MIPS和Power虽然已经不是主流，却也有不少厂家在使用。

首先来看ARM处理器，ARM架构是公开授权的。ARM自身并不生产芯片，只转让芯片设计许可。ARM的授权分为3种，分别是架构授权、内核授权和使用授权。

    架构授权：是指企业购买了架构级的ARM处理器设计和制造许可。企业获得架构授权之后，可以从整个架构和指令集方面入手，对ARM架构进行大幅度改造，甚至可以对ARM指令集进行扩展或缩减，以便达到更高性能、更低功耗或更低成本等不同目的。
    内核授权：内核授权则是指用户可以将其所购买的ARM核心应用到其自行设计的芯片中。但用户不得对其购买的ARM核心本身进行修改。
    使用授权：拥有使用授权的用户只能购买已经封装好的ARM处理器核心，而如果想要实现更多功能和特性，则只能通过增加封装之外的DSP核心的形式来实现。

### 移动芯片领域：华为、展讯、小米

华为

华为在2013年购买了ARM的架构授权，也就是说华为可以对ARM原有架构进行改造和对指令集进行扩展或者缩减。从2013年到现在，海思麒麟处理器已经从910更新到980，并且一直在升级。

有消息称麒麟980处理器将在8月31日与华为Mate 20新机同时发布。麒麟980拥有8 核心，4个A77大核，4个A55小核心，采用台积电7nm制成工艺。来自极果曝光的华为Mate 20跑分显示，麒麟980处理器跑分超过了35W分，超过骁龙845处理器5W左右。

展讯

展讯处理器也有部分采用ARM架构，展讯通信是中国领先的 2G、3G 和 4G 无线通信终端的核心芯片供应商之一，成立于2001年，于2013年12月23日被紫光集团收购，2016年与锐迪科整合成为紫光展锐。

展讯的处理器芯片主要面向中低端，其中一款SC9832集成四核ARM Cortex-A7处理器，该方案已经被中国移动、酷派、360、Micromax、Condor等众多国内外智能手机品牌采用。

小米

2017年2月，小米公布了史上研发周期最长的一款产品，自主芯片澎湃S1，引起业界一片喧嚣。因为作为手机厂商，自主研发处理器芯片，当时世界上也只有苹果和华为两家。

据当时报道，这款SoC的CPU部分为四核1.4G主频的Cortex A53和四核2.2G主频的Cortex A53，与海思麒麟650（4核2.0GHz A53+4核1.7GHz A53）、高通骁龙616（4核1.7GHz A53+4核1.2GHz A53）、高通骁龙625（8核2.0Ghz A53）属于同一个档次。

搭载澎湃S1的手机是小米5C，当时的消息是说，小米的C系列后续机型都会搭载自家的松果处理器，然而澎湃S2却迟迟未见发布，据内部消息透露，以小米高性价比的利润，根本就无法承担澎湃S2的研发费用，以后不会有澎湃S2，小米6C也不会再出现。

### 服务器芯片领域：阿里、华芯通、飞腾

阿里

2016年12月，ARM与阿里在数据中心业务展开合作，阿里巴巴宣布将在自身数据中心的服务器上大量采用ARM设计的低功耗CPU，逐步替换Intel产品。

消息称，阿里巴巴自主运营着支撑巨大电商业务的数据中心，同时还在中美等国提供名为“阿里云”的云服务。伴随需求增加，阿里巴巴将在各地增设数据中心。同时，因设备类耗电量正在迅速增大，该公司将逐步把英特尔CPU改为ARM产品，以提高用电效率。

华芯通

华芯通半导体由贵州省政府与美国高通于2016年创立。2018年5月27日，华芯通半导体正式发布其ARM架构服务器芯片品牌-昇龙（StarDragon）。

昇龙处理器是华芯通第一代服务器芯片产品，它是兼容ARMv8架构的48核处理器芯片，采用目前国际上先进的10纳米工艺，在性能上媲美国际市场中高端服务器主流芯片产品水平。

飞腾
2014年10月，飞腾第一款兼容ARM指令集的CPU——FT-1500A面世，成为国产CPU的代表之作。随后，飞腾又在2016年推出了FT-2000（代号为“火星”），并在2017年流片了优化升级的FT-2000+芯片，后者是飞腾目前最顶尖也是性价比最高的芯片产品，其实测性能达到了2014年Intel志强E5主流服务器芯片的水平。

然而日前，有报道称国内国内自主芯片领军厂商飞腾存在芯片造假，引起行业人士的关注。8月3日，天津飞腾就此事召开新闻发布会回应称，天津飞腾的CPU产品基于ARM技术架构研发，但包括CPU计算模块(内核)在内的代码部分均为公司历时多年自主研发完成。

面对芯片造假传闻，飞腾公司总经理谷虹回应道，“我们从未向ARM购买包括Cortex A57在内的任何CPU产品，更不可能将没有购买过的产品打上所谓标签推向市场。”

### 再看MIPS处理器，国内有龙芯、北京君正就是采用的MIPS架构。

龙芯

龙芯是中国科学院计算所主导研发的通用CPU，主要产品有龙芯1号、龙芯2号和龙芯3号。龙芯1号的频率为266MHz，最早在2002年开始使用。龙芯2号的频率最高为1GHz。龙芯3A是首款国产商用4核处理器，其工作频率为900MHz～1GHz。龙芯3A的峰值计算能力达到16GFLOPS。龙芯3B是首款国产商用8核处理器，主频达到1GHz，支持向量运算加速，峰值计算能力达到128GFLOPS，具有很高的性能功耗比。

目前，龙芯1号处理器已经随北斗卫星上天，并且已经有十多颗北斗卫星使用了龙芯1E和龙芯1F作为主控芯片。1号芯片的抗辐照能力可以与现在使用的国外芯片一较高下，价格和性能都要优于国外芯片。

龙芯2号芯片2K1000处理器在国产高性能芯片中的价格是最低的，和同性能TI芯片的开发板价格接近。2K1000处理器已经在石油、轨道交通、电力等领域有了应用，性能与国外芯片相当。

龙芯3A处理器采用的是RISC架构，兼容MIPS指令,原生四核设计，内含两条HT PHY超传输总线，采用65nm（纳米）工艺，主频1GHz，晶体管数目4.25亿个， 单颗龙芯3A的最大功耗为15W，一台刀片服务器功耗也仅为110W（两颗龙芯3A处理器,16GB内存,1块250GB硬盘,两块1000Mbps网卡等），理论峰值为16Gflops，每颗CPU单瓦特能效比1.06Gflops/W，是目前X86 CPU的2倍以上，达到了世界先进水平。


北京君正

成立于2005年，致力于在中国研制自主创新CPU技术和产品，目前已发展成为一家国内外领先的嵌入式CPU芯片及解决方案提供商。

有人认为，北京君正在人工智能CPU上很出色。北京君正既可以自己开发一套人工智能指令集，也可以单独开发一个人工智能加速单元。而且这些都可以直接嵌入cpu的底层，也就是cpu的人工智能指令集，和北京君正早期开发的simd同理。这和寒武纪只是外围的指令集，而非cpu指令集，其中的差距是很大的。也就是说北京君正的AI cpu 从速度和功耗肯定比寒武纪要好。

有人认为，北京君正基于MIPS架构的芯片，在同等工艺上，功耗比ARM有优势，但兼容性很差。在移动操作系统已经被安卓和ios彻底统一的现在，尤其是安卓，90%以上的安卓设备都是ARM的。但是ARM指令集和MIPS并不兼容，所以市面上大部分为ARM优化的程序不能在君正的MIPS处理器上直接运行。君正要想在市场上生存，必须要把ARM纳入视野。

### 在Power处理器上，中晟宏芯于2014年获得了Power 8架构的授权，然而目前Power架构目前已经不是主流市场。

中晟宏芯

该公司从2013年末成立以来也是问题重重，不间断的进行股权更换，甚至在2016年闹出欠薪风波，总体来说，在国产芯片的发展上，基本没有看到显眼的成绩。

申威处理器

在国产处理器发展过程中，江南所的申威处理器也很值得一提，申威处理器使用的是Alpha指令，主要用于超算处理器中，国内最强的超算神威·太湖之光就使用了申威的处理器。

文中第一部分并未提到Alpha架构，Alpha也不是主流架构。资料显示，Alpha架构于1992年2月25日，在东京召开的一次会议上面被正式推介。Alpha处理器最早由DEC公司设计制造，在Compaq（康柏）公司收购DEC之后，Alpha处理器继续得到发展，并且应用于许多高档的Compaq服务器上。

### 最后重点介绍X86处理器，事实上真正做到高性能且通用的处理器只有X86。

上海兆芯

上海兆芯的X86处理器在VIA X86处理器上改进，VIA是可授权X86的三家公司之一，另外两家分别是英特尔和AMD。目前可授权X86的企业有英特尔、AMD、VIA。

上海兆芯最新的KX-5000架构做到了8核架构，性能与英特尔的Core i3-6100处理器接近，进步也是非常明显。

海光（Hygon）

2018年7月，中国国产Dhyana X86处理器开始启动生产，引起业界高度关注，这预示着国产处理器芯片又进一步。

北京时间7月9日，由海光（Hygon）负责制造的中国国产Dhyana（禅定）x86处理器开始启动生产。早在2016年AMD与中国海光集团达成的合作协议，AMD将高性能X86架构授权给中国公司，授权费是2.93亿美元，而Dhyana处理器就是双方合作的产物，主要针对服务器市场。

此次授权对于国内芯片产业发展，收益是有的，不过也存在很多问题。从收益层面来看，海光生产出了X86 CPU，该款处理器性能还相当高。但是如果要站在是否掌握X86 CPU关键技术层面来看，还是有一定差距。

因为产品从设计到成品需要经历很多环节，而很多环节中方并没有参与。当时AMD与天津海光达成协议，设立合资公司开发X86芯片的时候，同时与海光成立了两个公司，一个叫做成都海光微电子（HMC），一个叫做和成都海光集成电路设计有限公司（Hygon）。其中 AMD持有HMC 51％股份和Hygon 30％的股份。

其中，HMC享有IP所有权，然后授权给Hygon进行芯片的设计，而Hygon设计出芯片之后再交由HMC进行生产。HMC找代工厂生产之后，再交由Hygon来销售，也就是说这中间很多环节中方根本没参与。


https://blog.csdn.net/juS3Ve/article/details/81611596链接
