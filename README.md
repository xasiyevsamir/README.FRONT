 #                                          __(FRONT-GIRIS)__

 1.__(index.html)__ Bu    __html)__ fayilidir .Html ne ucundur sualina cavab olaraq yaradilan sehvenin nece gorunmesini ve basliqi nece olmasini ve s. html ile hell olunur.Html fayili yaradarken isdifade olunur burada __Index)__ fayilin adidir ve __html)__ ise fayilin tipini gosderir. Biz Html fayili yaradarken muxdelif adlar vere bilerik mes: __MAIN.html ve ya samir.html)__ .Lakin html fayili yaratmaq ucun __(.html)__ yazmaliyiq.Her bir html) fayili html --> teqleri ile baslayir ve bitir.Umumi baxanda html ozu teqlerden ibaretdir. Html ozude 2 teqlerden ibaretdir. bunlar asagidakilardir.HTML-de 4  etab var. Bunlar head ve body hissesidir ve head, body hisselerde teqlerden isdifade olunur ve teqlere de atributlar vere bilerik.Atribut dedikde eni uzunlugu rengi ve s. nezerde tutulur.
----------------------------------------------------------------------------------------------------------------------------------------
 0                                                __(head)__
 * __(<head> /head>)__ head teqi sehvenin basligini yazmaq ucundur.head teqinin icersinde sorc axdaris yazila biler yeni acar sozler head teqinde yazilir. head teqinin daxilinde de teqler yazilir. mes: basliqi adlandirmaq ucun ve s.onlar asagidakilardir.

 1. __(<title>Kontakhome </title>)__ burada  biz sehvenin baslifini Kontakt-home qoyduq.Umumi yazilis  
  __(<head><title>Kontakhome </title> </head>)__ beledir.

 2. link rel="icon" href="" >>>> bu teqde head icerisinde yazilir lakin bu acilan anda baglanan teqlerdendir.Burada rel(icon)--relin icon oldugunu ve href("")-ise iconun adresini bildirir.
 ---------------------------------------------------------------------------------------------------------------------------------------
  0                                                __(body)__
 * body --> body teqi ise sehveni govdesidir yeni sehvenin basliqlarindan basqa diger bir cox seyler body teqinde yazilir. Mes: burada bis salam sozunu yazdiq.body teqininde icersinde de bir cox teqler var meselen bunlar asagidakilardir.

1. P --> Paraqraf teqidir.Bir paraqraf butov bir setri tutur ve buna gorede yanasi gelmirler.
2. span --> span ise butov bir setri tutmur ve yanasi gelir. 
3. h1>/h1>, h2>/h2>, h3>/h3>, h4>/h4>, h5>/h5>, h6>h6> -->  bu teqlerle ise basliqlari vere bilerik burada en boyuk teq h1 ve en kiciyi ise h6 dir.
4.  __div)__-->bir nece qrupun birlesmesi--> divde bir nece qrupun birlesmesini bir div kimi gosdere bilerik.
5. __img src="" alt="sekilin adi fln" width=(seklin eni demekdir)"50% ve ya 50px" height=(seklin hundurluyu demekdir)"80" title="Kontak-Home)__ -->bu img ile sekil yukleye bilerik burada src sekilin saxlandigi yer alt ise sekil haqqinda nese yaza bilerik. img olcusunu iki yolla vere bilerik birincisi tutdugu yerin 50% kimi ikinci ise pikseller ile.Olcunu vermek ucun bu (__width="")__ ifadeden isdifade edilir. Dediyimiz kimi ikcur olcu vere bilerik. Faizle verdikde __(width="50%")__ bele pikselle verdikde ise __(width="50px")__ kimi ifade edilir.Biz burada seklin hundurluyunu de artira bilerik lakin seklin effektliyi ite biler. Qeyd: eger biz seklin eni ve hundurluyunu artirib azaldanda % ve px yazmasaq defult olaraq px(piksel qebul edir).Burada __(title="Kontak-Home)__ atribut var bu ise seklin uzerine getdikde kontak-home sozunu cixardir. __(title)__ atributu qulobaldir ve butun teqlerde isdifade ede bilerik.
6. __u)__ bu teq daxil etdiyimiz sozun altindan xet cekir.
7. __i)__ bu teq ise yazdigimiz sozu italiq formada yeni eyri formada yazir.
----------------------------------------------------------------------------------------------------------------------------------------
0                                                      __(KECIDLER)__
    __Qeyd:)__ Kecidler iki cur olur seyfe daxili ve seyfe xarici . Seyfe daxili kecidler hal-hazirda oldugun seyfenin her hansi bir noqtesine gedise deyilir Mes: 100 setrlik melumatin 20 setrine gedis. Seyfe daxili kecidler ise basqa seyfelere yonlendirmekdi meselen kilik etdikde isdagrama ,watsaba, ve eyni seyfenin daxilinde basqa bir seyfeye kecid adlanir. 
    __(Qeyd:)__ Kecit etmek ucun __(a teqinden isdifade olunur ve (anchor lovber sozunden gotrulmusdur))__ .Ve Acilib baglanan teqdir.
1. __<a href="#">kecid et</a>)__ burada a teqini yazmisiq yeni xarici kecid __href)__ bos olduqda reslef edir yeni seyfeni yeniliyir # 
yazdiqda seyfe daxilinda dayanir ve her hansi sayitin linkini yazdiqda ise klik ederken hemin sehveye kecid edir.Burada __target)__ atributu var ki biz a teqine klik etdikde ozunde ve ya yeni sehvede acir target defult olaraq self-dir yeni target="_self" bele yazdiqda yeni sehveni ozunde acir. target ozunun acar sozleri var meselen target="_blank" etsek yeni sehvede acacaq . # varsa bu seyfe daxili kecitdir. __a)__ teqi ile telefon ve ya mail de yonlendirmek olar bu zaman ise asagidakilari yazmaq lazimdir.
2. __a href="tel:+994516687023">Zeng et</a)__ bu cur yazilisdan isdifade etmek olar. Burada __tel:)__ acar sozdur.
3.  __a href="mailto:samirakh@code.edu.az">gmail ile elaqe saxla</a>)__ bu cur yazilisdan isdifade etmek olar. Burada __mailto:)__ acar sozdur.
4. __a href="../Sekil/download.png" download> neyise yuklemek ucun dowload </a>)__ bu kodla ise nelerise yukluye bilerik.
________________________________________________________________________________________________________________________________________
0                                                      __(Listler)__
1. Listler iki cur olur. Sirali ve sirasiz.Sirasiz listler ucun ferq etmir birinci ile axrincinin yerini deyissek.Lakin sirali lislerde ise tam eksidir onlarda birinci gelen birinci axrinci gelen ise axrinci olmalidir ve sirali reqemler a-z ve ya A-Z siralanir ve rum reqemleri ilede siralana biler.
2. __ul> </ul>)__ bu sirasiz listleri yazmaq ucundur ve icersinde li-lerden isdifade edilir ve eger li-lerinde ul-lari olarsa li-lerin icersinde yazilir. __ul type="disc", type="cricle", type="Square" ,type="none")__ tayplarri var ve burada (disc ici dilu dayre) , (cricle ise ici bos cevredir) , (Square ise ici dolu kvadiratdir), (none ise hec bir cevre ve ya kvadirat gorunmesin.)

3. __ol type="1" start="12"> </ol>)__  bu ise sirali listler ucundur ve bunlarinda terkibinde li-ler olmalidir ve eger li-lerinde ol-lari olarsa li-lerin icersinde yazilir. __ol)__ listininde taypi var A-Z,a-z,reqem kimi ve rum reqemi kimi.Burada start neceden baslasin demekdir.
4. __li></li>)__ bu ise hem sirali hemde sirasiz lislerin yazilmasinda esas amillerden biridir yeni lisleri temin edr .
________________________________________________________________________________________________________________________________________
0                                                     __(Bezi acar simvollar)__

1. ./ --> Hal-hazirda oldugumuz qovlugu bildirir.
2.    ../ --> Bir qovluq cole cixmaq ucun isdifade edilir.
3. br-- break sozunun qisalisidi qirmaq yeni metni ,text qirir.