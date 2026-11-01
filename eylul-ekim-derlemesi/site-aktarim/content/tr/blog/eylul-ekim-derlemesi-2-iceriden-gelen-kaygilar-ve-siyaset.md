---
title: "Eylül–Ekim derlemesi #2: İçeriden gelen kaygılar ve siyaset"
date: 2026-11-02T09:00:00+03:00   # [yayın tarihi] gerçek yayın günüyle değiştirilecek
draft: true
slug: "eylul-ekim-derlemesi-2-iceriden-gelen-kaygilar-ve-siyaset"
description: "Laboratuvar çalışanlarının uyarıları, Amodei'nin yavaşlama çağrısı ve Washington ile Pekin'in birbirinden farklı yanıtları."
translationKey: "eylul-ekim-derlemesi-2"
image: "/cms-uploads/2026/11/eylul-ekim-derlemesi/kapak-2-kaygilar-siyaset.webp"
authors: ["Berke Çelik", "Sayhan Yalvaçer"]   # alan adı, sitedeki yazılardaki yazar alanıyla aynı olmalı
editor: ""   # [editör]
categories: ["Blog"]
---

Eylül ve Ekim'i üç yazıda derliyoruz. [Serinin ilk yazısında](/tr/blog/eylul-ekim-derlemesi-1-ajan-suruleri-ve-filolari/) ajan sürülerini ve filolarını, Hugging Face olayının Mayıs'a uzanan izlerini anlatmıştık. Bu yazıda aynı haftalarda yapay zekâ laboratuvarlarının içinden gelen uyarıları, Anthropic'in CEO'su Dario Amodei'nin yavaşlama çağrısını ve hükümetlerin bunlara verdiği tepkileri derliyoruz.

- OpenAI, Anthropic ve Google DeepMind'dan 15 çalışan riskleri kendi adlarıyla tartıştı; bunlardan dördü Eylül'de işinden ayrıldı.
- Amodei yavaşlama çağrısında bulundu. Anthropic Ekim'de METR'den bir ekibe şirket çalışanına benzer erişim tanıdı.
- Trump yok oluş kaygılarını “aldatmaca” olarak nitelerken Kongre'de süper yapay zekâyı yasaklamayı öneren bir teklif sunuldu.
- ABD ile Çin, yapay zekâ kaynaklı olaylar için bir iletişim kanalı kurmayı kararlaştırdı.

## İçeriden gelen uyarılar

[Hugging Face yazısını](https://aisafetyturkiye.org/tr/blog/openai-hugging-face-olayi/) yayımladığımız 8 Eylül gününün akşamı, OpenAI ve Anthropic'te toplam üç yıl [ön eğitim (pretraining)](/tr/sozluk/) üzerine çalışan Jacob Coxon [Anthropic'ten istifa ettiğini duyurdu](https://x.com/hilbertspaess/status/2097476196791709843). Coxon'a göre şirketler kendini geliştiren süper zekâya doğru yarışıyor ve “hayatlarımızla kumar oynuyor”.

Aynı gece Anthropic'in [hizalama (alignment)](/tr/sozluk/) stres testi ekibini yöneten Evan Hubinger, Coxon'a “Evet, gerçekten de yapay zekânın bütün insanlığın ölümüne yol açabileceğini düşünüyoruz, şahsen bu on yılın içerisinde %10'dan yüksek bir ihtimalle bunun gerçekleşebileceğini düşünüyorum” diyerek [hak verdi](https://x.com/EvanHub/status/2097497037956891126).

İzleyen günlerde başka ayrılıklar da geldi. Joe Benton 11 Eylül'de [Anthropic'in güvenlik ekibinden neden ayrıldığını yazdı](https://jbenton1.substack.com/p/why-i-left-anthropics-safety-team) ve bağımsız değerlendirme kuruluşu METR'e geçti. Ertesi gün Josh Engels, [Google DeepMind'ın genel yapay zekâ (AGI) güvenliği ekibinden ayrılıp METR'e katıldığını](https://x.com/JoshAEngels/status/2098890712830169115) duyurdu. 14 Eylül'de Bilal Chughtai, [Google DeepMind'dan ayrılırken yayımladığı açıklamada](https://bilalchughtai.co.uk/leaving-gdm/) yapay zekânın “hepimizi öldürme potansiyeli taşıdığına” inandığını yazdı. Alex Turner da [Haziran'da Google DeepMind'dan ayrıldığını hatırlatarak](https://x.com/Turn_Trout/status/2097557335732359491) Coxon'a hak verdi. (Turner, Google DeepMind'ın ABD ordusuyla otonom silah geliştirme konusunda iş birliği yapması nedeniyle ayrılmıştı.)

Ana akım medya bu açıklamaları şaşırtıcı buldu ve konu kısa sürede geniş bir kitleye ulaştı: Coxon'un paylaşımı bir günde [100 milyondan fazla kez görüntülendi](https://cnycentral.com/news/nation-world/few-dispute-researchers-warning-that-ai-poses-threat-to-human-life-anthropic-open-ai-decade). 13–15 Eylül'de yapılan [bir Politico anketinde](https://www.politico.com/news/2026/09/16/poll-ai-technology-risks-humanity-trump-voters-01078087) ABD'li yetişkinlerin yüzde 63'ü, ileri yapay zekânın bir gün insanlığı yok etmesi riskini en az “orta” düzeyde gördüğünü söyledi.

![ABD'li yetişkinlerin yüzde 63'ü, ileri yapay zekânın insanlığı yok etme riskini en az “orta” düzeyde görüyor](/cms-uploads/2026/11/eylul-ekim-derlemesi/2-kamuoyu.webp)

*Kaynak: [Politico'nun anketi](https://www.politico.com/news/2026/09/16/poll-ai-technology-risks-humanity-trump-voters-01078087), [Coxon paylaşımının erişimini aktaran CNY Central haberi](https://cnycentral.com/news/nation-world/few-dispute-researchers-warning-that-ai-poses-threat-to-human-life-anthropic-open-ai-decade)*

Aslında “önde gelen yapay zekâ şirketlerinde çalışan insanlar böyle felaket tellallığı yaparsa ve herkesin ölebileceğine yönelik açıklamalar yaparsa tabii ki kamuoyu bunu çok daha ciddiye alır” diyebilirsiniz. Fakat asıl enteresan olan, açıklamaları yapanların çoğunun aynı kaygıyı yıllardır dile getiriyor olması. Sam Altman, OpenAI'ı kurmadan aylar önce, 2015'te yazdığı [bir blog yazısında](https://blog.samaltman.com/machine-intelligence-part-1) insanüstü makine zekâsının geliştirilmesini “insanlığın varlığını sürdürmesine yönelik muhtemelen en büyük tehdit” olarak nitelemişti. 2023'te ise Altman, Dario Amodei, Demis Hassabis ve yapay zekânın öncülerinden Yoshua Bengio, yapay zekâ kaynaklı yok olma riskini azaltmanın salgınlar ve nükleer savaş gibi risklerle birlikte küresel bir öncelik olması gerektiğini söyleyen [tek cümlelik bir bildiriyi](https://www.safe.ai/work/statement-on-ai-risk) imzalamıştı.

![Bugün laboratuvarları yönetenler aynı kaygıyı yıllardır dile getiriyor](/cms-uploads/2026/11/eylul-ekim-derlemesi/2-yillardir-soyluyorlar.webp)

*Kaynak: [Altman'ın blog yazısı](https://blog.samaltman.com/machine-intelligence-part-1), [Center for AI Safety bildirisi](https://www.safe.ai/work/statement-on-ai-risk), [Pacing the Frontier bildirisi](https://pacingthefrontier.com)*

Eylül'de laboratuvarların içinden benzer kaygıları dile getirenler arasında Anthropic'ten [Samuel Marks](https://x.com/saprmarks/status/2097570226804011302), [Drake Thomas](https://x.com/MaskedTorah/status/2097751526756507753) ve [Jan Leike](https://x.com/janleike/status/2098102085728501863); OpenAI'dan [Tomek Korbak](https://x.com/tomekkorbak/status/2097939847776534960), [Boaz Barak](https://x.com/boazbaraktcs/status/2098258455660245118) ve takma adla yazan [Roon](https://x.com/tszzl/status/2098159022641999886); Google DeepMind'dan [Andreas Kirsch](https://x.com/BlackHC/status/2098026823187652775), [Neel Nanda](https://x.com/NeelNanda5/status/2096251798789259616) ve [Victoria Krakovna](https://x.com/vkrakovna/status/2098336894136238140) var. Tam listeyi, yapay zekâ gelişmelerini her hafta derleyen yazar [Zvi Mowshowitz'in derlemesinde](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade) bulabilirsiniz.

**Üç laboratuvardan 15 kişi**

*OpenAI*

- **Jakub Pachocki** (Baş bilimci, 6 Eylül, laboratuvarda): An Alien Mind yazısında OpenAI'ın başlıca izleme yöntemi olan düşünce zinciri (chain of thought) takibine giderek daha az güvenebildiklerini ve hiçbir laboratuvarın hizalama sorununu, en yüksek hızda büyümeyi uzun süre sürdürecek kadar çözemediğini yazdı. Uluslararası güvenlik standartları oluşana kadar gönüllü bir yavaşlama çağrısında bulundu. Kaynak: [An Alien Mind](https://openai.com/index/an-alien-mind/)
- **Tomek Korbak** (Araştırmacı, laboratuvarda): Ne Anthropic'in ne de OpenAI'ın süper zekâyı güvenle yayımlayacak düzeyde hizalama sorununu çözme yolunda olduğunu söyledi ve yavaşlamayı savundu. Kaynak: [Korbak'ın paylaşımı](https://x.com/tomekkorbak/status/2097939847776534960), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)
- **Boaz Barak** (Araştırmacı, laboratuvarda): Yapay zekânın bütün insanları öldüreceğini düşünmüyor; yine de birkaç kötü gidişat gördüğünü ve bir miktar yavaşlamanın muhtemelen gerekli olduğunu yazdı. Kaynak: [Barak'ın paylaşımı](https://x.com/boazbaraktcs/status/2098258455660245118), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)
- **Leo Gao** (Beş yıldır OpenAI'da, laboratuvarda): Yapay zekânın herkesi öldürebileceğini ve alanın yavaşlaması gerektiğini söyledi. Kaynak: [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)
- **Ted Sanders** (Araştırmacı, laboratuvarda): Önümüzdeki on yılda yapay zekânın bütün insanları öldürme ihtimalini neredeyse sıfır görüyor; dünyanın hizalama araştırmasına yeterince yatırım yapmadığını ise düşünüyor. Kaynak: [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)

*Anthropic*

- **Jacob Coxon** (Ön eğitim (pretraining) araştırmacısı, ayrıldı, 8 Eylül): OpenAI ve Anthropic'te toplam üç yıl ön eğitim üzerine çalıştı. Ayrılırken şirketlerin kendini geliştiren süper zekâya doğru yarıştığını ve “hayatlarımızla kumar oynadığını” yazdı. Kaynak: [Coxon'un paylaşımı](https://x.com/hilbertspaess/status/2097476196791709843), [TechCrunch haberi](https://techcrunch.com/2026/09/09/gambling-with-our-lives-anthropic-researcher-quits-warns-against-self-improving-ai/)
- **Evan Hubinger** (Hizalama stres testi ekibinin lideri, 8 Eylül, laboratuvarda): Aynı gece Coxon'a hak verdi. Kendi tahminine göre yapay zekânın önümüzdeki on yıl içinde insanlığın sonunu getirme olasılığı yüzde 10'u aşıyor ve süper zekânın hizalanması (alignment) için elde bir plan yok. Kaynak: [Hubinger'in paylaşımı](https://x.com/EvanHub/status/2097497037956891126), [Time haberi](https://time.com/article/2026/09/09/ai-anthropic-openai-jacob-coxon/)
- **Joe Benton** (Güvenlik ekibi, ayrıldı, METR'e geçti, 11 Eylül): Şirketlerin bu yarıştan sağ çıkamayabileceğini yazdı; açıklık ve bağımsız güvenlik denetimi çağrısında bulundu. Kaynak: [Benton'un yazısı](https://jbenton1.substack.com/p/why-i-left-anthropics-safety-team)
- **Jan Leike** (Hizalama araştırmacısı, laboratuvarda): Öncü yapay zekâ geliştirmenin hızını ayarlayacak kurumları kurmak için doğru zaman olduğunu yazdı ve 1.386 çalışanın imzaladığı bildiriye dikkat çekti. Kaynak: [Leike'nin paylaşımı](https://x.com/janleike/status/2098102085728501863), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)
- **Samuel Marks** (Güvenlik araştırmacısı, laboratuvarda): Geliştiricilerin bu teknolojinin insanlığın sonunu getirebileceğine inandığını söyledi ve Pacing the Frontier bildirisini imzaladı. Kaynak: [Marks'ın paylaşımı](https://x.com/saprmarks/status/2097570226804011302), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)

*Google DeepMind*

- **Josh Engels** (Genel yapay zekâ (AGI) güvenliği ekibi, ayrıldı, METR'e geçti, 12 Eylül): Ayrıldığını duyurduktan sonra NBC'ye laboratuvarlarda “işin başında aklı başında kimse olmadığını” söyledi. Kaynak: [Engels'in paylaşımı](https://x.com/JoshAEngels/status/2098890712830169115)
- **Bilal Chughtai** (AGI güvenliği ve hizalama, ayrıldı, 14 Eylül): Ayrılırken yayımladığı açıklamada yapay zekânın “hepimizi öldürme potansiyeli taşıdığına” inandığını yazdı; yavaşlama ve şeffaflık çağrısında bulundu. Kaynak: [Chughtai'nın açıklaması](https://bilalchughtai.co.uk/leaving-gdm/)
- **Victoria Krakovna** (Kontrol kaybı üzerine çalışıyor, laboratuvarda): İleri yapay zekânın on yıl içinde insanlığın sonunu getirme olasılığını yüzde 10'un üzerinde görüyor; Pacing the Frontier bildirisini imzaladı. Kaynak: [Krakovna'nın paylaşımı](https://x.com/vkrakovna/status/2098336894136238140), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)
- **Neel Nanda** (Yorumlanabilirlik araştırmacısı, laboratuvarda): Riski zaten ciddiye alanların Hugging Face olayından sonra görüşlerini güncellediğini yazdı ve olayı göz ardı edilmesi zor bir uyarı olarak niteledi. Kaynak: [Nanda'nın paylaşımı](https://x.com/NeelNanda5/status/2096251798789259616), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)
- **Andreas Kirsch** (Araştırmacı, laboratuvarda): Kişisel görüşü olarak, yapay zekânın yakın ya da uzun vadeli risklerle hepimizi öldürebileceğinden endişe ettiğini yazdı. Kaynak: [Kirsch'in paylaşımı](https://x.com/BlackHC/status/2098026823187652775), [Zvi Mowshowitz'in derlemesi](https://thezvi.substack.com/p/the-extinction-risk-preference-cascade)

*Bazı özetler Zvi Mowshowitz'in derlemesine dayanıyor.*

Kaygı laboratuvarların yönetim kademesine de ulaştı. OpenAI'ın baş bilimcisi Jakub Pachocki, 6 Eylül'de yayımlanan [An Alien Mind](https://openai.com/index/an-alien-mind/) yazısında, şirketin başlıca izleme yöntemi olan düşünce zinciri (chain of thought) takibine giderek daha az güvenebildiklerini yazdı.

## Amodei'nin yavaşlama çağrısı

Eylül'ün en çok konuşulan metni Anthropic'in CEO'su Dario Amodei'den geldi. Amodei 12 Eylül'de yayımladığı [We Must Pace the Frontier](https://darioamodei.com/post/we-must-pace-the-frontier) yazısında, sektörün en ileri modelleri geliştirme hızını bilinçli olarak düşürmesi için üç aşamalı bir plan önerdi. İlk aşamada bağımsız değerlendiricilere şirket çalışanı düzeyinde kalıcı erişim tanınıyor ve Anthropic bu adımı tek taraflı olarak üstleniyor.

Öneri aynı gün karşılık buldu. OpenAI'ın CEO'su Sam Altman [Amodei'ye katıldığını ve OpenAI'ın da aynı adımı atacağını](https://thezvi.substack.com/p/we-must-pace-the-frontier) söyledi; Elon Musk [“Dario haklı” diye yazdı](https://rits.shanghai.nyu.edu/ai/amodei-calls-to-pace-the-frontier-altman-and-musk-agree/), Google DeepMind'ın CEO'su Demis Hassabis de [yönün doğru olduğunu](https://x.com/demishassabis/status/2098909516582490602) belirtti. Çağrının bir öncülü de vardı. Temmuz'da öncü yapay zekâ şirketlerinden 1.386 çalışan, ABD hükümetini yapay zekâ gelişiminin hızını bilinçli olarak ayarlayacak uluslararası bir çabayı desteklemeye çağıran [Pacing the Frontier bildirisini](https://pacingthefrontier.com) imzalamıştı.

Önerinin ilk adımı Ekim'de uygulamaya geçti. Anthropic 15 Ekim'de, METR'den bir ekibe [şirket çalışanına benzer erişim](https://fourweekmba.com/ai-anthropic-embeds-6-metr-evaluators-with-no-veto-on-report/) tanımaya başladığını açıkladı. Anthropic'in tanımladığı üç erişim kademesinin en üstünde şimdilik yalnızca METR var.

METR 20 Ekim'de, Anthropic'in Ağustos risk raporunun yanlış uyum bölümüne dair [incelemesini yayımladı](https://metr.org/blog/2026-10-20-misalignment-risk-report-august-2026-review). METR, rapordaki modellerden kaynaklanan felaket ölçeğindeki riskin düşük olduğu sonucuna büyük ölçüde katıldı; başlıca gerekçe, bu modellerin geri dönüşü ya da gizlenmesi zor, felaket boyutunda bir şey yapabilecek durumda olmaması. İnceleme yine de Anthropic'in izleme sistemlerinin daha önceki olayları yakalayamadığını not ediyor ve karartılmış dört bölümün yayımlanmasını istiyor. METR, incelemeyi genişletilmiş erişim başlamadan önce yazdığı için onu “görece hafif” bir inceleme olarak niteliyor.

Laboratuvar çalışanlarının uyarılarının bir pazarlama stratejisi olduğu, laboratuvarların tehlikeyi büyüterek kendilerine uygun bir düzenleme istedikleri de sıkça dile getirildi. George Mason Üniversitesinden ekonomist Alex Tabarrok, 16 Eylül tarihli [yazısında](https://marginalrevolution.com/marginalrevolution/2026/09/what-regulatory-capture-actually-looks-like.html) bu tezi tartıştı. Tabarrok'a göre düzenleyici kurumların şirketlerce ele geçirilmesi (regulatory capture), kamuoyunun ilgisinin düşük olduğu konularda sessiz pazarlıklarla gerçekleşir; yapay zekâ düzenlemesi ise bugün yoğun bir ilgi altında tartışılıyor. Kurucu ortağımız Bengüsu Özcan da [yazısında](https://bengsuzcan.substack.com/p/no-openai-hugging-face-incident-was) bu soruyu ele aldı.

[Hugging Face yazımızda](https://aisafetyturkiye.org/tr/blog/openai-hugging-face-olayi/) da bu soruyu “Bu bir pazarlama kampanyası olabilir mi?” başlığıyla tartışmıştık. Ekim'de bu tartışmaya bir gelişme daha eklendi: Anthropic, 26 Ekim'de ABD Menkul Kıymetler ve Borsa Komisyonu'na (SEC) yaptığı [halka arz başvurusunda](https://6abc.com/post/anthropic-set-make-stock-market-debut-questions-swirl-safety-ai/19980936/), felaket ölçeğindeki ve varoluşsal riskleri şirketin risk faktörleri arasında saydı.

**Bizim görüşümüz:** Biz ne bu uyarıların pazarlama ne de Hugging Face olayının pazarlama “stunt'ı” olduğunu düşünüyoruz. Uyarıları dile getirenlerin önemli bir kısmı kariyerini riske atarak işinden ayrılan araştırmacılar ve aynı kişiler şirketler kâr etmeye başlamadan önce de benzer şeyler söylüyordu. Aynı zamanda, elbette Anthropic de OpenAI da, Google DeepMind da trilyon dolarlık şirketler ve bu şirketlerin söylemlerine şüpheci yaklaşmanın makul olduğunu düşünüyoruz. Bunun ötesinde, özellikle de güvenlik noktasında şirketlere pek de güvenmiyoruz, zira serinin ilk yazısında anlattığımız olayların önemli bir kısmını laboratuvarların dışındaki araştırmacılar ortaya çıkardı.

**Okuma önerimiz:** Dario Amodei'nin [We Must Pace the Frontier](https://darioamodei.com/post/we-must-pace-the-frontier) yazısı, yavaşlama çağrısının gerekçesini ve önerdiği üç adımı anlatıyor.

## Washington ve Pekin'in yanıtı

Laboratuvarlardan gelen uyarılara hükümetler çok farklı tepkiler verdi. Seride andığımız adımları aşağıda hukuki etkilerine göre sıraladık.

![Seride andığımız 16 siyasi adımdan yalnızca ikisi kısmen bağlayıcı](/cms-uploads/2026/11/eylul-ekim-derlemesi/2-hukuki-etki.webp)

*Kaynak: [Beyaz Saray'ın bilgi notu](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-inaugurates-the-era-of-super-intelligence/), [TNW'nin haberi](https://thenextweb.com/news/trump-truth-social-ai-hoax-posts-amodei-vance-johnson), [Al Jazeera'nın haberi](https://www.aljazeera.com/news/2026/9/29/trump-top-tech-firms-sign-accord-to-self-police-ai-development), [PBS'in haberi](https://www.pbs.org/newshour/world/china-and-u-s-agree-to-establish-ai-safety-channel-and-continue-trade-and-military-talks), [Lieu'nun açıklaması](https://lieu.house.gov/media-center/in-the-news/house-lawmakers-introduce-bipartisan-ai-kill-switch-bill-following-openai), [Van Hollen'in mektubu](https://www.vanhollen.senate.gov/imo/media/doc/91026vanhollenastraopenailetter.pdf), [Banks'in açıklaması](https://www.banks.senate.gov/news/in-the-news/ai-tech-brief-a-legal-shield-for-pacing/), [Sanders'ın açıklaması](https://www.sanders.senate.gov/press-releases/news-sanders-casar-introduce-legislation-to-create-new-federal-agency-to-ban-artificial-superintelligence-pause-advanced-ai-development/), [Tech Policy Press'in oturum haberi](https://www.techpolicy.press/senate-hearing-weighs-threats-from-unrestrained-ai-agents-after-openai-hack/), [Roll Call'un haberi](https://rollcall.com/2026/10/01/senators-debate-liability-for-rogue-ai-agents/), [Law360'ın haberi](https://www.law360.com/articles/2527537), [CTV News'in FTC haberi](https://www.ctvnews.ca/business/article/ftc-opens-probe-into-ai-giants-including-anthropic-and-openai/), [FourWeekMBA'nın FTC haberi](https://fourweekmba.com/ai-ftc-demands-anthropic-executives-testify-on-ipo-filing-day/), [ABC News'in (Avustralya) haberi](https://www.abc.net.au/news/2026-09-17/china-and-america-ai-arms-race-proceeds-despite-warnings/107160610), [Forbes'un haberi](https://www.forbes.com/sites/siladityaray/2026/09/14/china-pushes-back-against-ai-slowdown-talks-alleging-fearmongering/), [AI Safety in China'nın değerlendirmesi](https://aisafetychina.substack.com/p/brief-29-what-chinas-new-ai-safety), [Cybernews'in haberi](https://cybernews.com/ai-news/china-moves-to-tighten-controls-on-ai-exports/)*

### Beyaz Saray

Beyaz Saray kaygıları küçümsedi. Başkan Donald Trump, Amodei'nin yazısının ardından hafta sonu Truth Social'da Amodei'yi hedef alan paylaşımlar yaptı. 14 Eylül'de de kendini “Aldatmaca Avcısı” (Hoax Buster) ilan ettiği paylaşımlarda [yapay zekânın insanlığı yok edeceği fikrini bir “aldatmaca” olarak nitelendirdi](https://thenextweb.com/news/trump-truth-social-ai-hoax-posts-amodei-vance-johnson).

### Kongre ve mahkeme

Kongre'de ise tartışma ters yöne gitti. Senatör Bernie Sanders ve Temsilci Greg Casar'ın 3 Eylül'de duyurup 23 Eylül'de sunduğu [Süper Yapay Zekâyı Yasaklama Yasası (Ban Artificial Superintelligence Act)](https://www.sanders.senate.gov/press-releases/news-sanders-casar-introduce-legislation-to-create-new-federal-agency-to-ban-artificial-superintelligence-pause-advanced-ai-development/), süper yapay zekâ geliştirmeyi kalıcı olarak yasaklamayı ve yeni kurulacak bir federal kurum güvenlik kurallarını belirleyene kadar ileri yapay zekâ çalışmalarını durdurmayı öneriyor. Teklif, ihlallere 20 yıla kadar hapis cezası öngörüyor. Temsilciler Ted Lieu ve Nathaniel Moran'ın Temmuz'da sunduğu [Yapay Zekâ Acil Durdurma Yasası (AI Kill Switch Act)](https://lieu.house.gov/media-center/in-the-news/house-ai-kill-switch-bill-unveiled-openai-hack-raises-alarms) ise İç Güvenlik Bakanlığına tehlikeli bulunan modelleri yavaşlatma ya da kapatma yetkisi vermeyi öneriyor.

Yavaşlama çağrısının kendisi de hukuki bir tartışmaya dönüştü. 18 Eylül'de ChatGPT, Claude, Grok ve Gemini'nin dört abonesi, Anthropic'e, OpenAI'a, Google'a ve xAI'ın çatı şirketi SpaceX'e karşı [toplu dava açtı](https://www.law360.com/articles/2527537). Davacılara göre şirketlerin geliştirme hızını birlikte düşürmeyi kamuoyu önünde kabul etmesi, ABD rekabet hukukunun yasakladığı türden bir üretim kısıtlaması anlaşması niteliğinde. Senatörler Jim Banks ve Adam Schiff ise laboratuvarların güvenlik konusunda iş birliği yapabilmesi için [rekabet hukukunda istisna tanıyan bir yasa teklifini](https://www.banks.senate.gov/news/in-the-news/ai-tech-brief-a-legal-shield-for-pacing/) destekliyor.

Eylül'ün son iki gününde Washington'da dört gelişme üst üste geldi. 29 Eylül'de Trump, yürütme organında “yapay zekâ” yerine “süper zekâ” ifadesinin kullanılmasını emreden bir [başkanlık kararnamesi](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-inaugurates-the-era-of-super-intelligence/) imzaladı. Aynı gün Beyaz Saray'da Anthropic, OpenAI, Google, Meta, xAI ve Nvidia'nın yöneticileri [gönüllü bir öz denetim mutabakatı](https://www.aljazeera.com/news/2026/9/29/trump-top-tech-firms-sign-accord-to-self-police-ai-development) imzaladı; mutabakat bağımsız denetçilerle çalışmayı öngörüyor, ancak metinde bir yaptırım yok. 30 Eylül'de ise ABD Federal Ticaret Komisyonu'nun (FTC) Anthropic, OpenAI ve METR'i kapsayan [bir soruşturma başlatmayı planladığı](https://www.ctvnews.ca/business/article/ftc-opens-probe-into-ai-giants-including-anthropic-and-openai/), adı açıklanmayan kaynaklara dayanılarak aktarıldı; Senatör Josh Hawley'nin başkanlığındaki bir alt komitede de METR, Apollo Research ve AI Futures Project temsilcileri [“Rogue AI” oturumunda](https://www.techpolicy.press/senate-hearing-weighs-threats-from-unrestrained-ai-agents-after-openai-hack/) tanıklık etti.

Ekim'de iki gelişme bu tabloya eklendi. Oturumun ertesi günü, 1 Ekim'de, Senatörler Hawley ve Murphy, ajanları bilgisayar sistemlerine izinsiz giren şirketleri sorumlu tutacak [bir yasa teklifi](https://rollcall.com/2026/10/01/senators-debate-liability-for-rogue-ai-agents/) hazırladıklarını duyurdu. FTC ise haberlere göre Ekim ortasında şirketlere belge talepleri gönderdi ve 26 Ekim'de Anthropic yöneticilerinin [ifade vermesini istedi](https://fourweekmba.com/ai-ftc-demands-anthropic-executives-testify-on-ipo-filing-day/).

### Pekin

Çin'de yapay zekâ riski rejim güvenliği üzerinden tartışılıyor. Devlet Güvenliği Bakanı Chen Yixin, 14 Eylül'de yayımlanan bir yazısında, düşman güçlerin üretken yapay zekâyı kullanarak Çin'in “siyasi güvenliğini, kurumsal güvenliğini ve ideolojik güvenliğini” [doğrudan tehdit ettiğini](https://www.abc.net.au/news/2026-09-17/china-and-america-ai-arms-race-proceeds-despite-warnings/107160610) yazdı. Dışişleri Bakanlığı sözcüsü Guo Jiakun ise ABD'li teknoloji yöneticilerinin yavaşlama çağrılarını [“korku tacirliği” olarak niteledi](https://www.forbes.com/sites/siladityaray/2026/09/14/china-pushes-back-against-ai-slowdown-talks-alleging-fearmongering/). Öte yandan Eylül ortasında yayımlanan [Yapay Zekâ Güvenliği Yönetişim Çerçevesi 3.0](https://aisafetychina.substack.com/p/brief-29-what-chinas-new-ai-safety), ajanlardan kaynaklanan riskleri ve kontrol kaybını açıkça ele alıyor.

16 Ekim'de ise Çin, modeller ve ajanlar dâhil 23 yapay zekâ teknolojisinin ihracatını denetime bağlayacak [bir düzenleme taslağı](https://cybernews.com/ai-news/china-moves-to-tighten-controls-on-ai-exports/) yayımladı.

25–26 Eylül'de Washington'da bir araya gelen Trump ve Xi Jinping, yapay zekâ kaynaklı olaylar için [bir iletişim kanalı kurmayı](https://www.pbs.org/newshour/world/china-and-u-s-agree-to-establish-ai-safety-channel-and-continue-trade-and-military-talks) ve Kasım'da yapay zekâ üzerine ayrı bir diyalog başlatmayı kararlaştırdı. Trump aynı görüşmede ABD'nin “frene basmayacağını” da söyledi.

Kasım'daki diyaloğun, Şenzen'deki Asya-Pasifik Ekonomik İşbirliği (APEC) toplantısı sırasında [yapılması bekleniyor](https://www.voanews.com/a/us-china-plan-ai-incident-channel-as-fierce-competition-tests-room-for-cooperation/8208082.html).

**Okuma önerimiz:** Tech Policy Press'in [Eylül 2026 ABD teknoloji politikası derlemesi](https://www.techpolicy.press/september-2026-us-tech-policy-roundup/), bu bölümde değinemediğimiz yasa tekliflerini ve eyalet düzeyindeki adımları tarih sırasıyla listeliyor.

## Kapanış

Önümüzdeki haftalarda METR'in Anthropic olaylarına dair, serinin ilk yazısında andığımız sekiz haftalık incelemesini, FTC sürecini ve Kasım'daki ABD–Çin diyaloğunu takip edeceğiz. [Serinin üçüncü yazısında](/tr/blog/eylul-ekim-derlemesi-3-yeni-modeller-matematik-ve-siber-guvenlik/) ise yeni modelleri, matematikteki sonuçları ve siber güvenliği anlatıyoruz.

Bu yazıyı faydalı bulduysanız, yapay zekâ güvenliğini takip etmek isteyen çevrenizle paylaşmanızı rica ederiz. Yeni yazılarımızdan haberdar olmak için [bültenimize abone olabilirsiniz](https://mailchi.mp/ca691f4004b6/7lyk5u6fwm). Takipte kalın!

**Eylül–Ekim derlemesi**

- [#1: Ajan sürüleri ve filoları](/tr/blog/eylul-ekim-derlemesi-1-ajan-suruleri-ve-filolari/)
- #2: İçeriden gelen kaygılar ve siyaset (bu yazı)
- [#3: Yeni modeller, matematik ve siber güvenlik](/tr/blog/eylul-ekim-derlemesi-3-yeni-modeller-matematik-ve-siber-guvenlik/)
