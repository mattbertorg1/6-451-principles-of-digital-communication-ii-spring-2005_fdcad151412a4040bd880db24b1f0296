---
about_this_resource_text: '<p><strong>Topics covered: </strong>Reed-Solomon Codes</p><p><strong>Instructor:
  </strong>Prof. David Forney</p>'
course_id: 6-451-principles-of-digital-communication-ii-spring-2005
embedded_media:
- id: 12.jpg
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-12-reed-solomon-codes/12.jpg
  title: 12.jpg
  type: null
  uid: 089ae22a325d1e7b9086e83f7505768c
- id: Video-YouTube-Stream
  media_location: OJafRrE21WE
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Video-YouTube-Stream
  type: Video
  uid: 4b5b34596b76251beaf9f5e459706428
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/OJafRrE21WE/default.jpg
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 30d0b9ed2ccd4fd26e50b6ff964bc8d9
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597857
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Video-iTunes U-MP4
  type: Video
  uid: fef7aa298fc43d5fcfd9772ef49e2676
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.451S05/12ocw-6.451_4-261-14mar2005-220k.mp4
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Video-Internet Archive-MP4
  type: Video
  uid: 86171a6f0ac165b686d8636c1ba0bd88
- id: Thumbnail-OCW-JPG
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 9dbbb05447e5aac8375c23004d2e9720
- id: 3Play-3PlayYouTubeid-MP4
  media_location: OJafRrE21WE
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2fe4962168c08b84becf829e6d43191e
- id: OJafRrE21WE.srt
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-12-reed-solomon-codes/OJafRrE21WE.srt
  title: 3play caption file
  type: null
  uid: 7e56a5ed159efe05e691082151b7e078
- id: OJafRrE21WE.pdf
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-12-reed-solomon-codes/OJafRrE21WE.pdf
  title: 3play pdf file
  type: null
  uid: f196f2fd02f6a3056c95238470e40473
- id: Caption-3Play YouTube id-SRT
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3c10ebfdf77a1b55b8994afd8352352b
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e809be35f6c976eaf8e0103a99ec2ec0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 857fbbd55d7f2502094ddd148d37e09a
inline_embed_id: 53990755lecture12:reed-solomoncodes20911906
layout: video
order_index: null
parent_uid: 73f9a1c91575f1a3abda44e7358df3a2
related_resources_text: <p>Reed-Solomon Codes (<a title="Open in a new window." target="_blank"
  href="./resolveuid/01060b08ba74792ee8d85eb82b9efdb4">PDF</a>)</p>
short_url: lecture-12-reed-solomon-codes
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-12-reed-solomon-codes
template_type: Tabbed
title: 'Lecture 12: Reed-Solomon Codes'
transcript: <p><span m='0'>PROFESSOR:</span> <span m='40'>All right,</span> <span
  m='530'>I thought</span> <span m='740'>he would</span> <span m='840'>be.</span>
  <span m='1196'>It's</span> <span m='1910'>always</span> <span m='2230'>a</span>
  <span m='2360'>hazard</span> <span m='2860'>putting</span> <span m='3140'>up somebody</span>
  <span m='3455'>who you</span> <span m='3770'>know is</span> <span m='4200'>going
  to</span> <span m='4330'>lecture</span> <span m='4650'>better</span> <span m='4830'>than</span>
  <span m='5020'>you</span> <span m='5230'>do.</span> <span m='7200'>But</span> <span
  m='7640'>I</span> <span m='7660'>hope</span> <span m='7940'>that</span> <span m='8160'>was</span>
  <span m='8480'>a</span> <span m='8970'>good</span> <span m='9230'>change</span>
  <span m='9550'>of</span> <span m='9630'>pace.</span> <span m='10080'>And,</span>
  <span m='10770'>of</span> <span m='10820'>course,</span> <span m='11070'>he</span>
  <span m='11190'>knows</span> <span m='11630'>more</span> <span m='11910'>about</span>
  <span m='12250'>the</span> <span m='12550'>subject</span> <span m='12950'>of</span>
  <span m='13070'>Reed-Solomon</span> <span m='13710'>decoding</span> <span m='14080'>than</span>
  <span m='14450'>I</span> <span m='14630'>or</span> <span m='15185'>more than</span>
  <span m='15510'>practically</span> <span m='15660'>anyone</span> <span m='16090'>else</span>
  <span m='16550'>does,</span> <span m='16825'>so --</span> <span m='18860'>did</span>
  <span m='19030'>he</span> <span m='19170'>have</span> <span m='19260'>much</span>
  <span m='19490'>time</span> <span m='19720'>to</span> <span m='19780'>talk</span>
  <span m='20040'>about</span> <span m='20440'>decoding</span> <span m='21020'>or</span>
  <span m='21130'>was</span> <span m='21270'>the</span> <span m='21470'>most --</span>
  <span m='21670'>yeah.</span> <span m='22730'>Talked</span> <span m='22990'>about</span>
  <span m='23190'>the</span> <span m='23270'>decoding</span> <span m='23740'>algorithms,</span>
  <span m='24910'>Sudan-type</span> <span m='25190'>decoding</span> <span m='25650'>algorithms.</span>
  <span m='26762'>Yeah?</span> <span m='28180'>OK.</span> <span m='29070'>Good.</span>
  <span m='29850'>Well,</span> <span m='30040'>in fact,</span> <span m='30440'>he
  covered</span> <span m='30750'>so</span> <span m='30930'>much</span> <span m='31535'>that</span>
  <span m='31880'>I</span> <span m='32080'>don't</span> <span m='32250'>have</span>
  <span m='32390'>much</span> <span m='32650'>left</span> <span m='33150'>to</span>
  <span m='33425'>do</span> <span m='33700'>today.</span> </p><p><span m='37110'>I</span>
  <span m='38160'>remind</span> <span m='38610'>you,</span> <span m='39880'>Ashish</span>
  <span m='40260'>put</span> <span m='40430'>out</span> <span m='40590'>an</span>
  <span m='40700'>email.</span> <span m='41280'>There's</span> <span m='41530'>a</span>
  <span m='41740'>review</span> <span m='42090'>session</span> <span m='42500'>tomorrow</span>
  <span m='42900'>for</span> <span m='43080'>the</span> <span m='43190'>midterm</span>
  <span m='44710'>from</span> <span m='44960'>5</span> <span m='45310'>to</span> <span
  m='45410'>7</span> <span m='45930'>in</span> <span m='46220'>a</span> <span m='46300'>different</span>
  <span m='46640'>room,</span> <span m='47120'>36-112.</span> <span m='49760'>The</span>
  <span m='50080'>midterm</span> <span m='50800'>is</span> <span m='51060'>Wednesday</span>
  <span m='51580'>in</span> <span m='51740'>this</span> <span m='51980'>room.</span>
  <span m='52460'>It</span> <span m='52960'>starts</span> <span m='53340'>at</span>
  <span m='53450'>9:05</span> <span m='55220'>to</span> <span m='55320'>give</span>
  <span m='55480'>you</span> <span m='55650'>a</span> <span m='55680'>little</span>
  <span m='55790'>bit</span> <span m='55950'>more</span> <span m='56180'>time</span>
  <span m='56480'>to</span> <span m='56560'>work</span> <span m='56840'>on</span>
  <span m='56980'>it.</span> <span m='58400'>It's</span> <span m='58740'>closed</span>
  <span m='59180'>book</span> <span m='60970'>except</span> <span m='61480'>that</span>
  <span m='61760'>you're</span> <span m='61980'>allowed</span> <span m='62310'>to</span>
  <span m='62450'>make</span> <span m='62720'>up</span> <span m='62880'>three</span>
  <span m='64519'>normal</span> <span m='64810'>size</span> <span m='65150'>sheets</span>
  <span m='65630'>of</span> <span m='66330'>notes.</span> <span m='67280'>You</span>
  <span m='67400'>can</span> <span m='67510'>write</span> <span m='67740'>as</span>
  <span m='67810'>small</span> <span m='68180'>as</span> <span m='68270'>you</span>
  <span m='68440'>like.</span> <span m='70830'>This</span> <span m='71880'>experience</span>
  <span m='72440'>has</span> <span m='72550'>shown</span> <span m='72920'>this</span>
  <span m='73090'>is</span> <span m='73220'>the</span> <span m='73310'>very</span>
  <span m='74140'>best</span> <span m='74450'>way</span> <span m='74740'>of</span>
  <span m='74920'>getting</span> <span m='75190'>you</span> <span m='75350'>to</span>
  <span m='76420'>consolidate</span> <span m='77180'>what</span> <span m='77370'>you've</span>
  <span m='77570'>learned</span> <span m='77870'>up</span> <span m='78020'>to</span>
  <span m='78140'>this</span> <span m='78380'>point,</span> <span m='78670'>is</span>
  <span m='78810'>writing</span> <span m='79010'>your</span> <span m='79780'>own</span>
  <span m='80060'>three-page</span> <span m='81110'>precis</span> <span m='81400'>of</span>
  <span m='81620'>the</span> <span m='81920'>course</span> <span m='82260'>to date.</span>
  <span m='83090'>So,</span> <span m='83790'>yes?</span> </p><p><span m='84115'>AUDIENCE:</span>
  <span m='84440'>[INAUDIBLE]?</span> </p><p><span m='86352'>PROFESSOR:</span> <span
  m='86830'>What</span> <span m='87000'>is</span> <span m='87120'>the rule,</span>
  <span m='87200'>both --</span> <span m='87680'>what?</span> </p><p><span m='88596'>AUDIENCE:</span>
  <span m='89054'>Both</span> <span m='89512'>sides.</span> </p><p><span m='89970'>PROFESSOR:</span>
  <span m='90180'>Both</span> <span m='90570'>sides.</span> <span m='90950'>All</span>
  <span m='91200'>right.</span> <span m='92070'>Six</span> <span m='92440'>sheets.</span>
  <span m='93746'>If</span> <span m='94090'>you</span> <span m='94520'>can't</span>
  <span m='94750'>write</span> <span m='94980'>down</span> <span m='95190'>the</span>
  <span m='95250'>whole</span> <span m='95460'>course</span> <span m='95820'>in</span>
  <span m='95890'>six</span> <span m='96230'>sheets,</span> <span m='96640'>then,</span>
  <span m='99460'>well,</span> <span m='99610'>you</span> <span m='99770'>haven't</span>
  <span m='99930'>been</span> <span m='100040'>paying</span> <span m='100250'>attention.</span>
  <span m='104200'>OK.</span> <span m='106030'>And</span> <span m='106440'>you</span>
  <span m='106560'>can</span> <span m='106690'>bring</span> <span m='107000'>calculators,</span>
  <span m='107980'>but</span> <span m='108490'>we</span> <span m='108700'>don't</span>
  <span m='108880'>expect</span> <span m='109310'>they'll</span> <span m='109450'>be</span>
  <span m='109570'>useful.</span> <span m='111110'>Please</span> <span m='111440'>erase</span>
  <span m='111980'>any</span> <span m='112140'>erasable</span> <span m='112590'>will</span>
  <span m='112770'>memories</span> <span m='113090'>if you</span> <span m='113590'>do</span>
  <span m='113700'>bring</span> <span m='113940'>calculators.</span> <span m='115320'>These</span>
  <span m='115590'>are</span> <span m='115720'>things</span> <span m='116030'>we</span>
  <span m='116160'>tell</span> <span m='116400'>undergraduates.</span> <span m='117190'>I</span>
  <span m='117270'>guess</span> <span m='117930'>they</span> <span m='118280'>hardly</span>
  <span m='118430'>seem</span> <span m='118780'>necessary</span> <span m='119390'>in
  a</span> <span m='119500'>graduate</span> <span m='120000'>course.</span> <span
  m='122070'>Any</span> <span m='122240'>other</span> <span m='122400'>questions</span>
  <span m='123000'>about</span> <span m='123350'>the</span> <span m='123430'>logistics</span>
  <span m='124070'>of</span> <span m='124140'>the</span> <span m='124220'>midterm?</span>
  </p><p><span m='125500'>AUDIENCE:</span> <span m='126420'>What</span> <span m='127190'>is</span>
  <span m='127530'>the</span> <span m='128110'>material</span> <span m='128548'>going
  to be</span> <span m='128986'>for</span> <span m='129424'>the</span> <span m='129862'>midterm?</span>
  </p><p><span m='130738'>PROFESSOR:</span> <span m='131180'>Everything</span> <span
  m='131460'>that's</span> <span m='131600'>been</span> <span m='131750'>covered</span>
  <span m='132870'>up</span> <span m='133040'>to</span> <span m='133180'>today.</span>
  <span m='134820'>I won't</span> <span m='135120'>hold</span> <span m='135350'>you</span>
  <span m='135460'>responsible</span> <span m='136040'>for</span> <span m='136160'>anything</span>
  <span m='136390'>I've</span> <span m='136440'>talked</span> <span m='136720'>about</span>
  <span m='136890'>today.</span> <span m='137760'>So</span> <span m='137980'>it's</span>
  <span m='138100'>basically</span> <span m='138470'>chapters</span> <span m='138940'>one</span>
  <span m='139130'>through</span> <span m='139370'>eight.</span> <span m='144650'>I</span>
  <span m='144790'>really</span> <span m='145110'>will</span> <span m='145290'>only</span>
  <span m='146270'>hold</span> <span m='146480'>you</span> <span m='146560'>responsible</span>
  <span m='147160'>for</span> <span m='147270'>what</span> <span m='147380'>we</span>
  <span m='147510'>covered</span> <span m='147810'>in</span> <span m='147900'>class,</span>
  <span m='148940'>which</span> <span m='149560'>chapters</span> <span m='150000'>one,</span>
  <span m='150240'>two,</span> <span m='150450'>and</span> <span m='150620'>three</span>
  <span m='150790'>were</span> <span m='150940'>so</span> <span m='151390'>brief,</span>
  <span m='153420'>you</span> <span m='153590'>can't</span> <span m='153860'>say</span>
  <span m='153980'>we</span> <span m='154110'>really</span> <span m='154350'>covered</span>
  <span m='154660'>them.</span> <span m='155760'>So</span> <span m='156050'>really,</span>
  <span m='156300'>chapters</span> <span m='156720'>four</span> <span m='156960'>through</span>
  <span m='157210'>eight.</span> <span m='162633'>Any</span> <span m='163130'>other</span>
  <span m='163270'>questions?</span> <span m='165560'>All</span> <span m='165640'>right.</span>
  <span m='166040'>You'll</span> <span m='166270'>have</span> <span m='166730'>more</span>
  <span m='166890'>chance</span> <span m='167160'>as</span> <span m='167430'>we</span>
  <span m='167540'>go</span> <span m='167810'>along.</span> </p><p><span m='172170'>So</span>
  <span m='173380'>as</span> <span m='173550'>I</span> <span m='173630'>say,</span>
  <span m='175540'>Ralf</span> <span m='176040'>really</span> <span m='177540'>covered</span>
  <span m='177950'>the</span> <span m='178070'>main</span> <span m='178350'>things</span>
  <span m='178810'>about</span> <span m='179210'>Reed-Solomon</span> <span m='180000'>codes,</span>
  <span m='182020'>which</span> <span m='182330'>are</span> <span m='182470'>the</span>
  <span m='182620'>crowning</span> <span m='184270'>achievement</span> <span m='185030'>of</span>
  <span m='185240'>algebraic</span> <span m='185860'>coding</span> <span m='186210'>theory.</span>
  <span m='187480'>They</span> <span m='188010'>have</span> <span m='188170'>a</span>
  <span m='188330'>lot</span> <span m='188660'>of</span> <span m='189970'>favorable</span>
  <span m='190650'>attributes.</span> <span m='192180'>They are</span> <span m='193560'>optimum,</span>
  <span m='196160'>from</span> <span m='196610'>an</span> <span m='196720'>n,</span>
  <span m='197020'>k,</span> <span m='197360'>d</span> <span m='197690'>point</span>
  <span m='198050'>of</span> <span m='198140'>view,</span> <span m='199360'>in</span>
  <span m='200030'>the</span> <span m='200280'>sense</span> <span m='200570'>that
  they're</span> <span m='203020'>maximum</span> <span m='203450'>distance</span>
  <span m='204220'>separable.</span> <span m='206500'>The</span> <span m='207000'>parameters</span>
  <span m='207490'>are</span> <span m='207570'>as</span> <span m='207700'>good</span>
  <span m='207850'>as</span> <span m='208020'>they</span> <span m='208160'>possibly</span>
  <span m='208690'>could</span> <span m='208870'>be</span> <span m='209060'>by</span>
  <span m='209140'>this</span> <span m='209520'>very</span> <span m='209740'>basic</span>
  <span m='210680'>Singleton</span> <span m='211330'>bound.</span> <span m='213360'>They</span>
  <span m='213750'>have</span> <span m='215070'>efficient</span> <span m='215660'>algebraic</span>
  <span m='216430'>decoding</span> <span m='216970'>algorithms.</span> <span m='222130'>And</span>
  <span m='223090'>traditionally,</span> <span m='224980'>this</span> <span m='225270'>has</span>
  <span m='225930'>meant</span> <span m='226780'>hard</span> <span m='227060'>decision</span>
  <span m='227640'>bounded</span> <span m='228170'>distance</span> <span m='229040'>decoding</span>
  <span m='229630'>algorithms</span> <span m='230230'>like</span> <span m='230430'>the</span>
  <span m='230530'>Welch-Berlekamp</span> <span m='232030'>algorithm</span> <span
  m='232530'>or</span> <span m='232610'>the</span> <span m='232690'>Berlekamp-Massey</span>
  <span m='233280'>match</span> <span m='233750'>algorithm,</span> <span m='235220'>which</span>
  <span m='236440'>take</span> <span m='236970'>hard</span> <span m='237170'>decisions</span>
  <span m='237710'>in,</span> <span m='237980'>put</span> <span m='239230'>hard</span>
  <span m='239390'>decisions</span> <span m='240060'>on</span> <span m='241170'>symbols</span>
  <span m='241750'>out.</span> </p><p><span m='243360'>But</span> <span m='243690'>as</span>
  <span m='244050'>Ralf</span> <span m='244460'>suggested</span> <span m='245080'>to</span>
  <span m='245190'>you,</span> <span m='245390'>now</span> <span m='245710'>there</span>
  <span m='246120'>are</span> <span m='246600'>algorithms</span> <span m='247160'>that</span>
  <span m='247210'>can</span> <span m='247380'>use</span> <span m='248040'>soft</span>
  <span m='248360'>decisions</span> <span m='248900'>in,</span> <span m='249740'>produce</span>
  <span m='250140'>a</span> <span m='250310'>list,</span> <span m='251310'>at</span>
  <span m='251430'>least,</span> <span m='251800'>coming</span> <span m='252140'>out,</span>
  <span m='253160'>some</span> <span m='253460'>indication</span> <span m='253765'>of</span>
  <span m='254070'>the</span> <span m='254160'>reliability</span> <span m='254980'>of</span>
  <span m='255100'>each</span> <span m='255880'>element</span> <span m='256209'>of</span>
  <span m='256279'>the</span> <span m='256360'>list.</span> <span m='257980'>So</span>
  <span m='259110'>they've</span> <span m='259279'>been</span> <span m='259440'>softened</span>
  <span m='259959'>up.</span> <span m='263080'>Nonetheless,</span> <span m='263770'>what</span>
  <span m='263970'>are</span> <span m='266410'>the</span> <span m='266610'>negatives</span>
  <span m='267890'>is,</span> <span m='268710'>basically,</span> <span m='269095'>that</span>
  <span m='269480'>they</span> <span m='270370'>work</span> <span m='270730'>on</span>
  <span m='271410'>bytes,</span> <span m='272920'>or</span> <span m='273030'>symbols,</span>
  <span m='276000'>not</span> <span m='276320'>bits.</span> <span m='280130'>So</span>
  <span m='280550'>if</span> <span m='280650'>we</span> <span m='280750'>have</span>
  <span m='280980'>a</span> <span m='281040'>basically</span> <span m='281700'>binary</span>
  <span m='282290'>channel,</span> <span m='283150'>as</span> <span m='283310'>we</span>
  <span m='283870'>very</span> <span m='284080'>frequently</span> <span m='284610'>do,</span>
  <span m='286580'>then</span> <span m='289220'>they</span> <span m='289560'>need</span>
  <span m='289790'>something</span> <span m='290160'>else</span> <span m='290510'>to</span>
  <span m='290610'>make</span> <span m='290820'>them</span> <span m='290970'>adapted</span>
  <span m='291530'>to</span> <span m='291720'>the</span> <span m='291820'>binary</span>
  <span m='292220'>channel,</span> <span m='293600'>or</span> <span m='293950'>even</span>
  <span m='294140'>on</span> <span m='294280'>the</span> <span m='294440'>additive</span>
  <span m='294640'>white</span> <span m='294920'>Gaussian</span> <span m='295290'>noise</span>
  <span m='295730'>channel.</span> </p><p><span m='296060'>I</span> <span m='296150'>don't</span>
  <span m='296415'>think</span> <span m='296680'>we've gone</span> <span m='297610'>through</span>
  <span m='297820'>the</span> <span m='297920'>calculation.</span> <span m='298740'>You</span>
  <span m='298910'>could</span> <span m='299060'>think</span> <span m='299390'>of</span>
  <span m='301590'>sending</span> <span m='303740'>q</span> <span m='304040'>or</span>
  <span m='304315'>e</span> <span m='304590'>symbols</span> <span m='305140'>over</span>
  <span m='305450'>the</span> <span m='306970'>additive</span> <span m='307100'>white</span>
  <span m='307150'>Gaussian</span> <span m='307480'>noise</span> <span m='307730'>channel,</span>
  <span m='308080'>but</span> <span m='308510'>what</span> <span m='308780'>would</span>
  <span m='308920'>you need?</span> <span m='309240'>You</span> <span m='309420'>would</span>
  <span m='309490'>need</span> <span m='309870'>a</span> <span m='310410'>q or e</span>
  <span m='310930'>signal</span> <span m='311330'>set.</span> <span m='312490'>Now,</span>
  <span m='312810'>if</span> <span m='312890'>you</span> <span m='313040'>pick</span>
  <span m='313290'>that</span> <span m='313630'>to</span> <span m='313750'>be</span>
  <span m='314090'>a</span> <span m='314260'>q</span> <span m='315350'>simplex</span>
  <span m='315950'>signals</span> <span m='316390'>set</span> <span m='316720'>or
  a</span> <span m='317430'>orthogonal</span> <span m='317980'>or</span> <span m='318360'>biorthogonal</span>
  <span m='318860'>signal</span> <span m='319210'>set,</span> <span m='319530'>then</span>
  <span m='319670'>that</span> <span m='319860'>might</span> <span m='320040'>work</span>
  <span m='320460'>because</span> <span m='321020'>the</span> <span m='321120'>distance</span>
  <span m='321570'>structure</span> <span m='322110'>of</span> <span m='322190'>such</span>
  <span m='322440'>a</span> <span m='322490'>signal</span> <span m='322820'>set</span>
  <span m='323530'>is</span> <span m='323740'>like</span> <span m='324110'>the</span>
  <span m='324350'>Hamming</span> <span m='324750'>distance</span> <span m='325190'>structure</span>
  <span m='325790'>in</span> <span m='326700'>GF of q.</span> <span m='329650'>In</span>
  <span m='329720'>other</span> <span m='329840'>words,</span> <span m='330170'>it's</span>
  <span m='330700'>approximately</span> <span m='331230'>equally</span> <span m='331550'>likely</span>
  <span m='331960'>to</span> <span m='332100'>make</span> <span m='332840'>an</span>
  <span m='332980'>error</span> <span m='333400'>to</span> <span m='335590'>any</span>
  <span m='335850'>other</span> <span m='336060'>symbol.</span> <span m='336330'>The</span>
  <span m='337050'>symbols</span> <span m='337570'>are</span> <span m='337640'>more</span>
  <span m='337880'>or</span> <span m='337920'>less</span> <span m='338250'>equally</span>
  <span m='338640'>spread</span> <span m='338920'>apart</span> <span m='339760'>in</span>
  <span m='339910'>Euclidean</span> <span m='340390'>space.</span> <span m='340890'>Just
  as</span> <span m='342240'>when</span> <span m='342490'>we</span> <span m='342630'>count</span>
  <span m='342930'>distance</span> <span m='343980'>in</span> <span m='344110'>Hamming</span>
  <span m='344400'>space,</span> <span m='345450'>we</span> <span m='345830'>give</span>
  <span m='346020'>the</span> <span m='346130'>same</span> <span m='346470'>weight</span>
  <span m='347030'>to</span> <span m='347450'>each</span> <span m='347730'>possible</span>
  <span m='348210'>kind</span> <span m='348390'>of</span> <span m='348580'>error</span>
  <span m='348980'>or</span> <span m='349190'>each</span> <span m='349410'>possible</span>
  <span m='349880'>kind</span> <span m='350110'>of</span> <span m='350350'>symbol</span>
  <span m='350670'>difference.</span> </p><p><span m='351610'>So</span> <span m='353880'>if</span>
  <span m='354040'>you</span> <span m='354150'>did</span> <span m='354370'>that,</span>
  <span m='354780'>then</span> <span m='356340'>Reed-Solomon</span> <span m='356820'>codes</span>
  <span m='357330'>might</span> <span m='357550'>work</span> <span m='357850'>well.</span>
  <span m='358240'>That's</span> <span m='359400'>one</span> <span m='359700'>form</span>
  <span m='360070'>of</span> <span m='360200'>a</span> <span m='360280'>concatenated</span>
  <span m='360860'>scheme,</span> <span m='361370'>which</span> <span m='361600'>I</span>
  <span m='361670'>will</span> <span m='361830'>talk</span> <span m='362120'>about</span>
  <span m='362940'>in</span> <span m='363180'>just</span> <span m='363470'>a</span>
  <span m='363520'>second.</span> <span m='364290'>But</span> <span m='364660'>if</span>
  <span m='364930'>you</span> <span m='365110'>tried</span> <span m='365390'>to</span>
  <span m='365490'>apply</span> <span m='365810'>Reed-Solomon</span> <span m='366460'>codes</span>
  <span m='367350'>to</span> <span m='367700'>a</span> <span m='367840'>binary</span>
  <span m='368350'>input</span> <span m='368840'>additive</span> <span m='369150'>white</span>
  <span m='369260'>Gaussian</span> <span m='370010'>noise</span> <span m='370350'>channel,</span>
  <span m='370635'>just</span> <span m='370920'>translate</span> <span m='371266'>the,</span>
  <span m='372450'>say,</span> <span m='372670'>8-bit</span> <span m='373200'>bytes</span>
  <span m='373680'>into</span> <span m='374040'>bits</span> <span m='375080'>and</span>
  <span m='375260'>send</span> <span m='375480'>them</span> <span m='375590'>one</span>
  <span m='375810'>bit</span> <span m='376030'>at</span> <span m='376150'>a</span>
  <span m='376280'>time,</span> <span m='377700'>then</span> <span m='378100'>the</span>
  <span m='378380'>distance</span> <span m='378780'>structures</span> <span m='380410'>don't</span>
  <span m='380680'>correspond</span> <span m='381230'>at</span> <span m='381300'>all</span>
  <span m='381550'>well.</span> <span m='381840'>It's</span> <span m='382010'>much</span>
  <span m='382250'>more</span> <span m='382440'>likely</span> <span m='382830'>to</span>
  <span m='382910'>make</span> <span m='383130'>a</span> <span m='383190'>single</span>
  <span m='383550'>bit</span> <span m='383750'>error</span> <span m='384520'>than</span>
  <span m='385310'>an</span> <span m='385580'>error that</span> <span m='385660'>involves</span>
  <span m='386350'>all</span> <span m='386690'>eight</span> <span m='386910'>bits</span>
  <span m='387220'>or</span> <span m='387340'>something.</span> <span m='388270'>And</span>
  <span m='390720'>for</span> <span m='390840'>that</span> <span m='391560'>fundamental</span>
  <span m='392090'>reason,</span> <span m='393050'>you'll</span> <span m='393240'>find</span>
  <span m='393570'>that</span> <span m='393700'>performance</span> <span m='394530'>is</span>
  <span m='395650'>not</span> <span m='395890'>so</span> <span m='396060'>great.</span>
  </p><p><span m='396500'>And</span> <span m='397240'>certainly,</span> <span m='398510'>this</span>
  <span m='398750'>is</span> <span m='398950'>not</span> <span m='399230'>the</span>
  <span m='399320'>way</span> <span m='399600'>to</span> <span m='399870'>get</span>
  <span m='400140'>to</span> <span m='400260'>capacity</span> <span m='400940'>all</span>
  <span m='401120'>by</span> <span m='401330'>itself</span> <span m='401890'>unless</span>
  <span m='402190'>it's</span> <span m='402360'>married</span> <span m='402750'>with</span>
  <span m='402890'>something</span> <span m='403290'>else.</span> <span m='405370'>So</span>
  <span m='406540'>that's</span> <span m='406750'>something</span> <span m='407100'>we</span>
  <span m='407210'>always</span> <span m='407470'>have</span> <span m='407650'>to</span>
  <span m='407780'>deal</span> <span m='408010'>with in</span> <span m='408260'>another</span>
  <span m='408590'>applications,</span> <span m='409410'>as</span> <span m='409610'>I</span>
  <span m='409680'>will</span> <span m='410320'>talk</span> <span m='410600'>about</span>
  <span m='410890'>in a</span> <span m='410980'>minute.</span> <span m='411300'>We</span>
  <span m='411690'>naturally</span> <span m='412180'>do</span> <span m='412360'>want</span>
  <span m='412530'>to</span> <span m='412700'>correct</span> <span m='413560'>bytes,</span>
  <span m='414470'>or</span> <span m='414950'>symbols,</span> <span m='415610'>or</span>
  <span m='415710'>blocks.</span> <span m='417210'>There</span> <span m='417570'>are</span>
  <span m='417610'>many</span> <span m='417920'>bits.</span> <span m='419950'>And</span>
  <span m='420090'>then</span> <span m='420230'>Reed-Solomon</span> <span m='420820'>codes</span>
  <span m='421230'>are</span> <span m='422300'>just</span> <span m='422610'>exactly</span>
  <span m='423090'>what</span> <span m='423230'>we</span> <span m='423350'>want.</span>
  <span m='423770'>They're</span> <span m='424820'>optimal</span> <span m='425115'>in</span>
  <span m='425410'>any</span> <span m='425620'>such</span> <span m='425930'>situation.</span>
  </p><p><span m='427570'>And</span> <span m='428180'>so</span> <span m='428430'>what
  did I</span> <span m='428690'>just</span> <span m='428970'>say?</span> <span m='429280'>They're</span>
  <span m='430710'>not</span> <span m='431070'>the</span> <span m='431170'>way</span>
  <span m='431400'>to</span> <span m='431480'>get</span> <span m='431750'>to</span>
  <span m='431830'>capacity,</span> <span m='435850'>although</span> <span m='436230'>they</span>
  <span m='436470'>are</span> <span m='436520'>sometimes</span> <span m='437160'>part</span>
  <span m='437415'>of</span> <span m='437670'>schemes</span> <span m='438260'>for</span>
  <span m='439170'>getting</span> <span m='439480'>to</span> <span m='439640'>capacity.</span>
  <span m='441930'>And</span> <span m='442180'>since</span> <span m='442540'>getting</span>
  <span m='442790'>to</span> <span m='442910'>capacity</span> <span m='443640'>in
  the</span> <span m='443740'>additive</span> <span m='443910'>white</span> <span
  m='444340'>Gaussian</span> <span m='444930'>noise</span> <span m='445270'>channel</span>
  <span m='445530'>is</span> <span m='445790'>the</span> <span m='445910'>theme</span>
  <span m='446230'>of</span> <span m='446400'>this</span> <span m='446640'>course,</span>
  <span m='447600'>then</span> <span m='449150'>they</span> <span m='449520'>play</span>
  <span m='449780'>only</span> <span m='450130'>a</span> <span m='451120'>peripheral</span>
  <span m='451540'>role</span> <span m='452720'>in</span> <span m='452860'>that</span>
  <span m='453130'>theme.</span> <span m='453440'>Nonetheless,</span> <span m='454040'>they're</span>
  <span m='455040'>great codes.</span> <span m='455750'>They're</span> <span m='456730'>in</span>
  <span m='456890'>wide</span> <span m='457210'>use.</span> <span m='457580'>They're</span>
  <span m='457690'>part</span> <span m='457970'>of</span> <span m='458070'>every</span>
  <span m='458420'>semiconductor</span> <span m='459070'>manufacturer's</span> <span
  m='459960'>core</span> <span m='460280'>library.</span> <span m='461400'>You</span>
  <span m='461610'>can</span> <span m='461770'>buy</span> <span m='462550'>(255,223)</span>
  <span m='466990'>distance</span> <span m='467490'>33,</span> <span m='469200'>16</span>
  <span m='469830'>error</span> <span m='470110'>correcting</span> <span m='471220'>Reed-Solomon</span>
  <span m='472090'>decoder</span> <span m='473900'>in</span> <span m='474210'>part</span>
  <span m='474520'>of</span> <span m='474640'>any</span> <span m='474970'>chip</span>
  <span m='475240'>package</span> <span m='475900'>and</span> <span m='476050'>it'll</span>
  <span m='476250'>go</span> <span m='476600'>at</span> <span m='477440'>gigabits</span>
  <span m='477980'>nowadays.</span> <span m='480260'>So</span> <span m='482230'>it's</span>
  <span m='482690'>kind</span> <span m='482840'>of</span> <span m='482990'>the</span>
  <span m='483130'>all-purpose</span> <span m='483930'>error</span> <span m='484160'>correcting</span>
  <span m='484640'>code,</span> <span m='485980'>with</span> <span m='486260'>the</span>
  <span m='486540'>caveat</span> <span m='487170'>that</span> <span m='487320'>you</span>
  <span m='487510'>need</span> <span m='487800'>to</span> <span m='488650'>somehow</span>
  <span m='489050'>get</span> <span m='489230'>what</span> <span m='489380'>you</span>
  <span m='489540'>correct</span> <span m='490300'>to</span> <span m='490400'>be</span>
  <span m='490560'>bytes</span> <span m='491040'>rather</span> <span m='491300'>than</span>
  <span m='491470'>bits,</span> <span m='494060'>OK?</span> </p><p><span m='495320'>So</span>
  <span m='497910'>today</span> <span m='498280'>I</span> <span m='498350'>thought</span>
  <span m='498700'>I'd</span> <span m='499770'>cover</span> <span m='500400'>the</span>
  <span m='500620'>last</span> <span m='500840'>two</span> <span m='501030'>topics</span>
  <span m='501770'>in</span> <span m='502710'>chapter</span> <span m='503200'>eight</span>
  <span m='503680'>and</span> <span m='503970'>maybe,</span> <span m='504910'>to the</span>
  <span m='505040'>extent</span> <span m='505560'>that</span> <span m='505750'>time</span>
  <span m='507490'>permits,</span> <span m='509680'>go</span> <span m='509810'>back</span>
  <span m='510270'>to</span> <span m='512400'>chapter</span> <span m='513409'>seven.</span>
  <span m='515106'>But</span> <span m='515600'>we'll</span> <span m='516280'>see</span>
  <span m='516570'>how</span> <span m='516760'>we</span> <span m='516880'>feel</span>
  <span m='517210'>about</span> <span m='517490'>that.</span> <span m='519530'>Applications</span>
  <span m='520030'>of</span> <span m='520530'>Reed-Solomon</span> <span m='521429'>codes.</span>
  <span m='525470'>OK,</span> <span m='528380'>basically,</span> <span m='529040'>you</span>
  <span m='529180'>can</span> <span m='529330'>apply</span> <span m='529730'>them</span>
  <span m='530030'>wherever</span> <span m='530590'>you</span> <span m='530770'>want</span>
  <span m='530930'>to</span> <span m='531100'>correct</span> <span m='531840'>blocks,</span>
  <span m='532950'>rather</span> <span m='533300'>than</span> <span m='534600'>bits</span>
  <span m='534970'>or</span> <span m='535130'>packets</span> <span m='535830'>or</span>
  <span m='537280'>n-tuples</span> <span m='538290'>or</span> <span m='538690'>what</span>
  <span m='538880'>have</span> <span m='539100'>you.</span> <span m='540990'>So</span>
  <span m='541270'>one</span> <span m='541510'>obvious</span> <span m='542030'>application</span>
  <span m='543770'>is,</span> <span m='544940'>when</span> <span m='545420'>you</span>
  <span m='545610'>send</span> <span m='545980'>packets</span> <span m='546570'>through</span>
  <span m='546860'>the</span> <span m='547190'>internet,</span> <span m='558810'>if</span>
  <span m='559050'>you</span> <span m='560320'>use</span> <span m='560700'>Reed-Solomon</span>
  <span m='561400'>codes</span> <span m='561820'>across</span> <span m='562410'>the</span>
  <span m='562510'>packet,</span> <span m='565010'>then</span> <span m='566660'>you</span>
  <span m='566910'>can</span> <span m='568270'>correct</span> <span m='569370'>errors</span>
  <span m='569920'>that</span> <span m='570040'>occur</span> <span m='570490'>in</span>
  <span m='570820'>individual</span> <span m='571850'>packets.</span> </p><p><span
  m='573020'>This</span> <span m='573470'>is</span> <span m='573610'>not</span> <span
  m='573830'>the way</span> <span m='574060'>the</span> <span m='574180'>internet</span>
  <span m='574580'>usually</span> <span m='574950'>works.</span> <span m='575950'>The</span>
  <span m='576190'>internet</span> <span m='576360'>usually</span> <span m='576680'>works</span>
  <span m='577090'>by</span> <span m='578100'>having</span> <span m='578410'>an</span>
  <span m='578900'>error</span> <span m='579550'>detection</span> <span m='580900'>code</span>
  <span m='581330'>within</span> <span m='581640'>each</span> <span m='581860'>packet,</span>
  <span m='582290'>a</span> <span m='582760'>cyclic</span> <span m='583240'>redundancy</span>
  <span m='584260'>check (CRC).</span> <span m='585930'>You</span> <span m='586500'>hash</span>
  <span m='586950'>bits,</span> <span m='587650'>whatever.</span> <span m='589020'>You</span>
  <span m='589570'>provide</span> <span m='590070'>some</span> <span m='590210'>redundant</span>
  <span m='590740'>bits</span> <span m='591130'>within</span> <span m='591500'>each</span>
  <span m='592510'>packet</span> <span m='593160'>if --</span> <span m='594170'>when</span>
  <span m='594370'>you</span> <span m='594500'>receive</span> <span m='594930'>the</span>
  <span m='595020'>packet,</span> <span m='595460'>you</span> <span m='595590'>check</span>
  <span m='596450'>to</span> <span m='596590'>see</span> <span m='596840'>whether</span>
  <span m='597120'>the</span> <span m='597200'>parity</span> <span m='597610'>check</span>
  <span m='597960'>checks.</span> <span m='599130'>If</span> <span m='599440'>there</span>
  <span m='600800'>are</span> <span m='601930'>parity</span> <span m='602260'>check</span>
  <span m='602690'>bits,</span> <span m='603710'>then</span> <span m='604430'>a</span>
  <span m='604550'>very</span> <span m='604850'>good</span> <span m='605050'>rule</span>
  <span m='605290'>of</span> <span m='605400'>thumb</span> <span m='605770'>is</span>
  <span m='606200'>that</span> <span m='607080'>the</span> <span m='607180'>probability</span>
  <span m='607820'>of</span> <span m='608280'>not</span> <span m='608560'>detecting</span>
  <span m='609180'>an</span> <span m='609260'>error</span> <span m='609970'>for</span>
  <span m='610210'>almost</span> <span m='610630'>any</span> <span m='610940'>type</span>
  <span m='611280'>of</span> <span m='611390'>error</span> <span m='611660'>pattern</span>
  <span m='612070'>is</span> <span m='612230'>going</span> <span m='612350'>to</span>
  <span m='612470'>be</span> <span m='612590'>of</span> <span m='612700'>the</span>
  <span m='612820'>order</span> <span m='613030'>of</span> <span m='613110'>2</span>
  <span m='613280'>to</span> <span m='613330'>the</span> <span m='613410'>minus</span>
  <span m='613800'>r.</span> <span m='614750'>That's</span> <span m='615280'>exactly</span>
  <span m='615740'>what</span> <span m='615860'>it</span> <span m='615920'>would</span>
  <span m='616070'>be</span> <span m='616230'>if</span> <span m='616330'>you</span>
  <span m='616420'>had</span> <span m='616500'>a</span> <span m='616590'>completely</span>
  <span m='616970'>random</span> <span m='617390'>stream</span> <span m='617740'>of</span>
  <span m='617880'>bits.</span> <span m='618940'>Random</span> <span m='619230'>stream</span>
  <span m='619540'>of</span> <span m='619620'>bits</span> <span m='620400'>with</span>
  <span m='620660'>r</span> <span m='621040'>redundant</span> <span m='621510'>bits</span>
  <span m='621790'>in</span> <span m='621890'>a</span> <span m='621940'>block,</span>
  <span m='622830'>the</span> <span m='622940'>probability</span> <span m='623630'>that</span>
  <span m='624260'>all</span> <span m='624580'>the</span> <span m='624780'>check</span>
  <span m='625050'>bits</span> <span m='625300'>are</span> <span m='625350'>random,</span>
  <span m='625890'>the</span> <span m='625990'>probability</span> <span m='626530'>that</span>
  <span m='626620'>they're</span> <span m='626780'>all</span> <span m='626980'>equal</span>
  <span m='627210'>to</span> <span m='627260'>0,</span> <span m='628060'>is</span>
  <span m='628230'>2</span> <span m='628440'>to the</span> <span m='628510'>minus</span>
  <span m='628890'>r.</span> <span m='629940'>All</span> <span m='630030'>right?</span>
  </p><p><span m='630340'>But</span> <span m='630640'>it</span> <span m='630800'>turns</span>
  <span m='631110'>out</span> <span m='631270'>that's</span> <span m='632240'>very</span>
  <span m='632510'>good</span> <span m='632680'>approximation</span> <span m='633640'>for</span>
  <span m='634420'>just</span> <span m='634670'>about</span> <span m='634850'>any</span>
  <span m='635120'>error</span> <span m='635420'>mechanism.</span> <span m='635990'>So</span>
  <span m='636180'>you</span> <span m='636330'>pick</span> <span m='636570'>r</span>
  <span m='636820'>large</span> <span m='637150'>enough.</span> <span m='638870'>It's</span>
  <span m='639090'>often</span> <span m='639410'>been</span> <span m='639650'>picked</span>
  <span m='639930'>to</span> <span m='640010'>be</span> <span m='640170'>something</span>
  <span m='640540'>like</span> <span m='640810'>r</span> <span m='641080'>equals</span>
  <span m='641440'>32.</span> <span m='643110'>What</span> <span m='643460'>kind</span>
  <span m='643710'>of</span> <span m='644460'>failure</span> <span m='644950'>to</span>
  <span m='645190'>detect</span> <span m='645800'>does</span> <span m='645990'>that</span>
  <span m='646190'>give?</span> <span m='647320'>2</span> <span m='647530'>to the</span>
  <span m='647610'>minus</span> <span m='647950'>32,</span> <span m='648630'>which</span>
  <span m='648900'>is</span> <span m='649420'>what,</span> <span m='649690'>about</span>
  <span m='649950'>2</span> <span m='650120'>the</span> <span m='650190'>minus</span>
  <span m='650550'>9th,</span> <span m='650850'>2</span> <span m='651220'>to the minus</span>
  <span m='651590'>10th --</span> <span m='652320'>10</span> <span m='652590'>to</span>
  <span m='652650'>the</span> <span m='652730'>minus</span> <span m='653060'>9th,</span>
  <span m='653310'>10</span> <span m='653580'>to the</span> <span m='653670'>minus</span>
  <span m='654000'>10th.</span> <span m='656190'>Is</span> <span m='656350'>that</span>
  <span m='656490'>low</span> <span m='656730'>enough?</span> <span m='658010'>It
  was</span> <span m='658160'>certainly --</span> <span m='659100'>when</span> <span
  m='659300'>I</span> <span m='659380'>started</span> <span m='659790'>in</span> <span
  m='659830'>this</span> <span m='660030'>business,</span> <span m='660440'>that</span>
  <span m='660510'>was</span> <span m='660790'>considered</span> <span m='661390'>just</span>
  <span m='661660'>incredibly</span> <span m='662140'>low,</span> <span m='662400'>but</span>
  <span m='662590'>now that</span> <span m='662830'>we're</span> <span m='663010'>sending</span>
  <span m='664590'>mega</span> <span m='664930'>packets</span> <span m='665390'>per</span>
  <span m='665580'>second,</span> <span m='666020'>it</span> <span m='666110'>doesn't</span>
  <span m='666380'>seem</span> <span m='666610'>quite</span> <span m='666880'>so low</span>
  <span m='667310'>anymore.</span> <span m='668220'>And</span> <span m='668450'>so</span>
  <span m='668660'>32</span> <span m='669340'>is</span> <span m='670450'>a</span>
  <span m='670560'>little</span> <span m='670790'>bit on the</span> <span m='671150'>sloppy</span>
  <span m='671630'>side.</span> <span m='672640'>There</span> <span m='673000'>are</span>
  <span m='673230'>going</span> <span m='673330'>to</span> <span m='673430'>be</span>
  <span m='673540'>undetected</span> <span m='674110'>errors</span> <span m='674530'>that</span>
  <span m='674620'>get</span> <span m='674870'>through</span> <span m='675150'>if</span>
  <span m='675270'>you're</span> <span m='675420'>spending</span> <span m='676390'>10</span>
  <span m='676600'>to</span> <span m='676660'>the</span> <span m='676750'>9th,</span>
  <span m='677100'>10</span> <span m='677300'>to</span> <span m='677370'>the</span>
  <span m='677490'>10th</span> <span m='679080'>packets.</span> <span m='679710'>But</span>
  <span m='682490'>32</span> <span m='683180'>or,</span> <span m='684490'>nowadays,</span>
  <span m='684950'>64</span> <span m='685640'>would</span> <span m='685780'>be</span>
  <span m='685910'>a</span> <span m='685960'>better</span> <span m='686230'>number.</span>
  <span m='686900'>Just</span> <span m='687100'>like</span> <span m='687360'>cryptography,</span>
  <span m='688100'>the</span> <span m='688230'>number</span> <span m='688660'>of bits</span>
  <span m='689220'>has to</span> <span m='689430'>go up</span> <span m='689960'>as</span>
  <span m='690390'>technology</span> <span m='691030'>goes</span> <span m='691370'>up.</span>
  <span m='692020'>But</span> <span m='692130'>32</span> <span m='692970'>is</span>
  <span m='693200'>often</span> <span m='693480'>used.</span> </p><p><span m='694400'>OK,</span>
  <span m='694790'>but</span> <span m='694970'>here's</span> <span m='695280'>an</span>
  <span m='695550'>alternative</span> <span m='696220'>scheme.</span> <span m='697700'>Suppose</span>
  <span m='698360'>you</span> <span m='698600'>coded</span> <span m='700170'>across</span>
  <span m='700680'>packets.</span> <span m='701220'>So</span> <span m='701470'>here</span>
  <span m='701730'>is</span> <span m='701960'>a,</span> <span m='702460'>say,</span>
  <span m='702840'>a</span> <span m='703220'>1,000-bit</span> <span m='705750'>packet.</span>
  <span m='708720'>And</span> <span m='709980'>here's</span> <span m='710310'>packet</span>
  <span m='710770'>one,</span> <span m='711980'>here's</span> <span m='712360'>packet</span>
  <span m='712620'>two,</span> <span m='714500'>here's</span> <span m='714830'>packet</span>
  <span m='715270'>three,</span> <span m='716770'>and</span> <span m='717030'>so</span>
  <span m='717280'>forth</span> <span m='718415'>up</span> <span m='718810'>to</span>
  <span m='722280'>packet</span> <span m='723410'>k,</span> <span m='724140'>where</span>
  <span m='724550'>we're</span> <span m='724680'>going</span> <span m='724770'>to</span>
  <span m='724810'>use</span> <span m='727170'>n,</span> <span m='727500'>k,</span>
  <span m='727900'>d</span> <span m='729590'>equals</span> <span m='730090'>n</span>
  <span m='730330'>minus</span> <span m='730790'>k</span> <span m='731050'>plus</span>
  <span m='731480'>1,</span> <span m='732910'>RS</span> <span m='733460'>code</span>
  <span m='735330'>over,</span> <span m='735690'>it</span> <span m='736050'>doesn't</span>
  <span m='736370'>matter,</span> <span m='738020'>GF</span> <span m='738460'>of</span>
  <span m='738720'>let's</span> <span m='738980'>say</span> <span m='739270'>256,</span>
  <span m='740930'>just</span> <span m='741120'>for</span> <span m='741240'>definite</span>
  <span m='741720'>[INAUDIBLE].</span> <span m='742740'>Here</span> <span m='742900'>I'm</span>
  <span m='742990'>using</span> <span m='743300'>older</span> <span m='743640'>notation.</span>
  <span m='745270'>This is</span> <span m='745380'>the</span> <span m='745480'>same</span>
  <span m='745890'>as</span> <span m='746320'>F-256.</span> <span m='748140'>Or</span>
  <span m='748370'>we</span> <span m='748480'>sometimes</span> <span m='748990'>write</span>
  <span m='749250'>that</span> <span m='749470'>as</span> <span m='749890'>F 2</span>
  <span m='750130'>to the 8th.</span> </p><p><span m='752960'>OK,</span> <span m='754650'>how</span>
  <span m='754800'>are</span> <span m='754970'>we</span> <span m='755100'>going</span>
  <span m='755230'>to</span> <span m='755360'>do</span> <span m='755560'>packet</span>
  <span m='755930'>error</span> <span m='756210'>correction?</span> <span m='756640'>We're</span>
  <span m='756730'>going</span> <span m='756820'>to</span> <span m='756900'>code</span>
  <span m='757700'>crosswise</span> <span m='758730'>in</span> <span m='758920'>columns,</span>
  <span m='760970'>all</span> <span m='761090'>right?</span> <span m='761420'>So</span>
  <span m='763990'>these</span> <span m='764250'>would</span> <span m='764390'>be</span>
  <span m='764620'>k.</span> <span m='766860'>Let's</span> <span m='767170'>make</span>
  <span m='767430'>this</span> <span m='767700'>eight-wide.</span> <span m='768540'>Just</span>
  <span m='768790'>pick</span> <span m='769020'>off</span> <span m='769380'>a bite</span>
  <span m='769640'>at a</span> <span m='769910'>time</span> <span m='770290'>here.</span>
  <span m='770630'>So</span> <span m='770840'>each</span> <span m='771040'>of</span>
  <span m='771090'>these</span> <span m='771350'>can</span> <span m='771590'>be</span>
  <span m='772110'>considered</span> <span m='772570'>to</span> <span m='772620'>be</span>
  <span m='772760'>a</span> <span m='772840'>symbol</span> <span m='773290'>in</span>
  <span m='773440'>GF of</span> <span m='774330'>256.</span> <span m='776500'>And</span>
  <span m='776630'>then</span> <span m='776810'>we'll</span> <span m='777030'>code</span>
  <span m='778080'>n</span> <span m='778270'>minus</span> <span m='778680'>k</span>
  <span m='780430'>parity</span> <span m='780690'>check</span> <span m='781060'>packets</span>
  <span m='781780'>down</span> <span m='782150'>here.</span> <span m='784370'>So</span>
  <span m='784610'>these</span> <span m='784970'>are</span> <span m='786510'>redundant</span>
  <span m='787700'>check</span> <span m='787990'>packets.</span> <span m='790200'>Encoded</span>
  <span m='794590'>bytes</span> <span m='795410'>at</span> <span m='795530'>this</span>
  <span m='795740'>point.</span> <span m='796030'>They're</span> <span m='796150'>not</span>
  <span m='796390'>packets</span> <span m='796840'>yet.</span> <span m='797220'>But</span>
  <span m='797660'>if</span> <span m='797770'>we</span> <span m='797870'>do</span>
  <span m='798100'>that</span> <span m='798850'>column-wise</span> <span m='799760'>across</span>
  <span m='801280'>here,</span> <span m='802640'>we</span> <span m='803240'>can</span>
  <span m='804270'>fill</span> <span m='804730'>in</span> <span m='806390'>n</span>
  <span m='806610'>minus</span> <span m='807090'>k</span> <span m='809080'>check</span>
  <span m='809400'>packets</span> <span m='816380'>and</span> <span m='820270'>you</span>
  <span m='820440'>can see</span> <span m='820780'>the</span> <span m='821130'>block</span>
  <span m='821490'>length</span> <span m='821800'>is</span> <span m='822160'>quite</span>
  <span m='822460'>huge</span> <span m='823050'>here.</span> <span m='824310'>So</span>
  <span m='824550'>you</span> <span m='824690'>might</span> <span m='824900'>have</span>
  <span m='825080'>a</span> <span m='825350'>delay</span> <span m='825780'>or</span>
  <span m='825950'>latency</span> <span m='826500'>problem</span> <span m='828000'>in</span>
  <span m='828320'>executing</span> <span m='828840'>this</span> <span m='829090'>scheme.</span>
  <span m='829340'>Basically,</span> <span m='829980'>you would</span> <span m='830150'>have</span>
  <span m='830320'>to</span> <span m='830500'>send</span> <span m='831350'>this</span>
  <span m='831530'>whole</span> <span m='831840'>thing</span> <span m='833090'>before</span>
  <span m='834530'>you</span> <span m='834700'>could</span> <span m='834890'>do</span>
  <span m='835120'>error</span> <span m='835410'>correction</span> <span m='836050'>and</span>
  <span m='836490'>then</span> <span m='836810'>error correct</span> <span m='837030'>the</span>
  <span m='837130'>whole</span> <span m='837350'>thing.</span> </p><p><span m='838040'>But
  how</span> <span m='838140'>does</span> <span m='838430'>error</span> <span m='838690'>correction</span>
  <span m='839190'>work?</span> <span m='840450'>You</span> <span m='840620'>send</span>
  <span m='840930'>this.</span> <span m='841230'>Perhaps</span> <span m='842480'>some</span>
  <span m='842730'>of</span> <span m='842790'>the</span> <span m='842870'>packets</span>
  <span m='843520'>are</span> <span m='843950'>erased</span> <span m='844730'>or</span>
  <span m='844990'>even</span> <span m='845240'>received</span> <span m='845740'>incorrectly.</span>
  <span m='847230'>You</span> <span m='847440'>would then</span> <span m='847690'>use</span>
  <span m='847990'>some</span> <span m='849030'>error</span> <span m='849310'>correction</span>
  <span m='849970'>or</span> <span m='850300'>erasure and</span> <span m='850760'>error</span>
  <span m='851010'>correction</span> <span m='851520'>scheme,</span> <span m='853000'>which</span>
  <span m='853350'>Ralf</span> <span m='853640'>talked</span> <span m='854060'>about,</span>
  <span m='854540'>for</span> <span m='854880'>correcting</span> <span m='856890'>the</span>
  <span m='857110'>Reed-Solomon</span> <span m='857790'>code.</span> <span m='858610'>And</span>
  <span m='858880'>you</span> <span m='859040'>could</span> <span m='859320'>correct</span>
  <span m='860970'>up</span> <span m='861180'>to</span> <span m='863410'>d</span>
  <span m='863650'>over</span> <span m='863890'>2</span> <span m='865240'>errors,</span>
  <span m='865850'>or</span> <span m='866640'>up to</span> <span m='866780'>d</span>
  <span m='867470'>minus</span> <span m='867820'>1</span> <span m='868180'>erasures,</span>
  <span m='870810'>OK?</span> </p><p><span m='871640'>So</span> <span m='871890'>this</span>
  <span m='872390'>would</span> <span m='872550'>be</span> <span m='872670'>a</span>
  <span m='872720'>very</span> <span m='872980'>powerful</span> <span m='874870'>packet</span>
  <span m='875290'>error</span> <span m='875560'>correction</span> <span m='876020'>scheme.</span>
  <span m='876470'>What</span> <span m='876650'>are</span> <span m='876750'>its</span>
  <span m='876950'>costs?</span> <span m='877500'>It's</span> <span m='877690'>costs</span>
  <span m='878160'>are</span> <span m='878850'>quite</span> <span m='879090'>a</span>
  <span m='879130'>bit</span> <span m='879290'>of</span> <span m='879400'>redundancy.</span>
  <span m='880590'>It</span> <span m='880950'>doesn't</span> <span m='881250'>fit</span>
  <span m='881460'>the</span> <span m='881570'>internet</span> <span m='881940'>architecture</span>
  <span m='882690'>very</span> <span m='882950'>well.</span> <span m='885270'>This</span>
  <span m='885420'>is</span> <span m='885520'>basically</span> <span m='885870'>a</span>
  <span m='885930'>point-to-point</span> <span m='886840'>scheme.</span> <span m='888420'>So</span>
  <span m='888740'>when</span> <span m='888910'>you're</span> <span m='889070'>sending</span>
  <span m='889550'>from</span> <span m='889900'>a</span> <span m='890100'>to</span>
  <span m='890200'>b,</span> <span m='890540'>you'd</span> <span m='890740'>have</span>
  <span m='890940'>to</span> <span m='891050'>send</span> <span m='891400'>b</span>
  <span m='891720'>an</span> <span m='891780'>additional</span> <span m='892840'>n</span>
  <span m='893070'>minus</span> <span m='893440'>k</span> <span m='893720'>streams.</span>
  <span m='895390'>And</span> <span m='895700'>if</span> <span m='895810'>you're</span>
  <span m='896010'>sending</span> <span m='896360'>the</span> <span m='896450'>same</span>
  <span m='897060'>webpage,</span> <span m='897800'>as</span> <span m='897890'>you</span>
  <span m='898030'>often</span> <span m='898180'>do,</span> <span m='898270'>to</span>
  <span m='898660'>multiple</span> <span m='899070'>people,</span> <span m='900230'>you'd</span>
  <span m='900420'>have</span> <span m='900670'>to</span> <span m='900950'>send</span>
  <span m='901250'>this</span> <span m='902340'>to</span> <span m='902490'>everybody.</span>
  <span m='903290'>And</span> <span m='905380'>it</span> <span m='905590'>also</span>
  <span m='905880'>doesn't</span> <span m='906130'>have</span> <span m='906250'>any</span>
  <span m='906400'>feedback</span> <span m='906700'>in</span> <span m='907000'>it.</span>
  </p><p><span m='907380'>The</span> <span m='907550'>great</span> <span m='907840'>thing</span>
  <span m='908010'>about</span> <span m='908250'>ARQ</span> <span m='909590'>is</span>
  <span m='909890'>that you</span> <span m='910100'>only</span> <span m='910370'>have</span>
  <span m='910550'>to</span> <span m='910650'>send</span> <span m='910870'>the</span>
  <span m='910960'>information</span> <span m='911500'>that's</span> <span m='911670'>necessary.</span>
  <span m='912720'>You only</span> <span m='913050'>have</span> <span m='913310'>to</span>
  <span m='914120'>restore</span> <span m='914700'>the</span> <span m='914880'>packets</span>
  <span m='915510'>that</span> <span m='915650'>are</span> <span m='915800'>actually</span>
  <span m='916210'>lost.</span> <span m='917185'>You</span> <span m='917550'>send
  them</span> <span m='917770'>again.</span> <span m='920370'>Whereas</span> <span
  m='920690'>here,</span> <span m='921020'>you're</span> <span m='921200'>just</span>
  <span m='921460'>kind</span> <span m='921730'>of,</span> <span m='922090'>a</span>
  <span m='922250'>priori,</span> <span m='922830'>deciding</span> <span m='923370'>that</span>
  <span m='923520'>you're</span> <span m='923670'>going</span> <span m='923820'>to</span>
  <span m='924320'>send</span> <span m='924700'>a</span> <span m='924780'>great</span>
  <span m='925090'>deal</span> <span m='925310'>of</span> <span m='925510'>redundant</span>
  <span m='925830'>information</span> <span m='926450'>down</span> <span m='926720'>here</span>
  <span m='926990'>to</span> <span m='927090'>cover</span> <span m='927410'>some</span>
  <span m='927640'>kind</span> <span m='927880'>of</span> <span m='928440'>worst</span>
  <span m='928830'>case,</span> <span m='929290'>whatever</span> <span m='930240'>you</span>
  <span m='930380'>think</span> <span m='930820'>the</span> <span m='931050'>worst-case</span>
  <span m='931710'>number</span> <span m='931970'>of</span> <span m='932030'>packets</span>
  <span m='932510'>would</span> <span m='932750'>be.</span> <span m='933320'>If</span>
  <span m='933420'>there</span> <span m='933540'>are</span> <span m='933580'>more</span>
  <span m='933820'>that</span> <span m='934080'>worst-case</span> <span m='934600'>number
  or</span> <span m='934870'>packets,</span> <span m='935430'>then</span> <span m='936080'>you</span>
  <span m='936210'>could</span> <span m='936360'>retransmit</span> <span m='937010'>again,</span>
  <span m='937410'>but</span> <span m='937540'>you're</span> <span m='937880'>retransmitting</span>
  <span m='938480'>this</span> <span m='938650'>huge</span> <span m='938960'>block,</span>
  <span m='939810'>all</span> <span m='940270'>right?</span> </p><p><span m='940730'>So</span>
  <span m='941490'>for</span> <span m='941620'>that</span> <span m='941820'>reason,</span>
  <span m='942160'>this</span> <span m='942390'>is</span> <span m='943160'>not</span>
  <span m='943380'>actually</span> <span m='943810'>used,</span> <span m='944710'>as</span>
  <span m='944880'>far</span> <span m='945100'>as</span> <span m='945230'>I'm</span>
  <span m='945400'>aware,</span> <span m='945700'>in</span> <span m='945780'>the</span>
  <span m='945870'>internet.</span> <span m='946840'>ARQ,</span> <span m='947940'>wherever</span>
  <span m='948090'>you</span> <span m='948210'>have</span> <span m='948380'>a</span>
  <span m='948550'>feedback</span> <span m='949120'>path,</span> <span m='949400'>you</span>
  <span m='949530'>should</span> <span m='949750'>use</span> <span m='950030'>it.</span>
  <span m='952460'>That's</span> <span m='952710'>a</span> <span m='952760'>general</span>
  <span m='953130'>moral.</span> <span m='955280'>So</span> <span m='956000'>ARQ</span>
  <span m='956490'>is</span> <span m='956630'>a</span> <span m='956720'>wonderful</span>
  <span m='957160'>scheme</span> <span m='957660'>that</span> <span m='957890'>is,</span>
  <span m='958940'>on an</span> <span m='959150'>erasure</span> <span m='959540'>channel,</span>
  <span m='959970'>that's</span> <span m='960310'>a</span> <span m='960790'>capacity-approaching</span>
  <span m='961890'>scheme.</span> <span m='963810'>Just on</span> <span m='964250'>a</span>
  <span m='964310'>bitwise</span> <span m='964900'>basis,</span> <span m='965320'>if</span>
  <span m='965480'>you</span> <span m='965640'>have a</span> <span m='965710'>binary</span>
  <span m='966090'>erasure</span> <span m='966490'>channel</span> <span m='966880'>with</span>
  <span m='967470'>erasure</span> <span m='967860'>probability</span> <span m='968440'>p,</span>
  <span m='969430'>and</span> <span m='971150'>then</span> <span m='971310'>the</span>
  <span m='971410'>capacity</span> <span m='971700'>of</span> <span m='971990'>the</span>
  <span m='972120'>channel</span> <span m='972460'>is</span> <span m='972550'>1</span>
  <span m='972780'>minus</span> <span m='973180'>p,</span> <span m='974220'>and</span>
  <span m='974540'>you</span> <span m='974700'>can</span> <span m='974850'>reach</span>
  <span m='975140'>that</span> <span m='975370'>capacity</span> <span m='976050'>if</span>
  <span m='976190'>you</span> <span m='976280'>simply</span> <span m='977090'>retransmit</span>
  <span m='977800'>each</span> <span m='978010'>bit</span> <span m='978200'>that</span>
  <span m='978310'>was</span> <span m='978460'>erased.</span> <span m='978970'>As</span>
  <span m='979200'>it's</span> <span m='979380'>erased --</span> <span m='980530'>it's</span>
  <span m='980650'>erased,</span> <span m='980940'>you</span> <span m='981070'>send</span>
  <span m='981320'>it</span> <span m='981420'>again.</span> </p><p><span m='982300'>And</span>
  <span m='982510'>a</span> <span m='982610'>quick</span> <span m='982830'>calculation</span>
  <span m='983500'>shows</span> <span m='983900'>you that</span> <span m='984200'>the</span>
  <span m='984380'>average</span> <span m='984770'>number of</span> <span m='985100'>retransmissions</span>
  <span m='985990'>is</span> <span m='986150'>p.</span> <span m='986960'>And</span>
  <span m='987150'>so</span> <span m='988090'>the</span> <span m='988260'>average</span>
  <span m='988580'>reduction</span> <span m='989200'>from</span> <span m='989900'>1</span>
  <span m='990280'>bit</span> <span m='990500'>per</span> <span m='990660'>second</span>
  <span m='991100'>is --</span> <span m='991660'>1</span> <span m='991920'>bit</span>
  <span m='992140'>per</span> <span m='992390'>transmission</span> <span m='993100'>is</span>
  <span m='993860'>p</span> <span m='994000'>bits</span> <span m='994280'>per</span>
  <span m='994380'>transmission,</span> <span m='995020'>you</span> <span m='995140'>can</span>
  <span m='995260'>achieve</span> <span m='995600'>1</span> <span m='995800'>minus</span>
  <span m='996170'>p</span> <span m='996920'>with</span> <span m='997060'>no</span>
  <span m='997220'>coding</span> <span m='997540'>at</span> <span m='997630'>all,</span>
  <span m='998010'>just by</span> <span m='998240'>retransmission.</span> <span m='999890'>So</span>
  <span m='1000150'>it's</span> <span m='1000340'>perfectly</span> <span m='1000780'>matched</span>
  <span m='1001160'>to the</span> <span m='1001260'>erasure</span> <span m='1001600'>channel.</span>
  <span m='1001990'>And</span> <span m='1002080'>the</span> <span m='1002850'>internet,</span>
  <span m='1003830'>especially</span> <span m='1004350'>with</span> <span m='1005480'>parity</span>
  <span m='1005850'>checks,</span> <span m='1006530'>CRC,</span> <span m='1007250'>within</span>
  <span m='1007600'>blocks,</span> <span m='1010410'>long</span> <span m='1010670'>enough</span>
  <span m='1010860'>CRC</span> <span m='1012050'>is</span> <span m='1012270'>basically</span>
  <span m='1012910'>a</span> <span m='1012980'>packet</span> <span m='1013420'>erasure</span>
  <span m='1014010'>channel.</span> <span m='1016250'>You</span> <span m='1017140'>really,</span>
  <span m='1018140'>in</span> <span m='1018270'>practice,</span> <span m='1018780'>hardly</span>
  <span m='1019120'>ever</span> <span m='1019310'>make</span> <span m='1019630'>a</span>
  <span m='1020150'>undetected --</span> <span m='1021500'>let a</span> <span m='1022820'>packet</span>
  <span m='1023150'>with</span> <span m='1023310'>errors</span> <span m='1023700'>come</span>
  <span m='1023880'>through.</span> <span m='1025920'>OK?</span> <span m='1027530'>Any</span>
  <span m='1027680'>questions</span> <span m='1028109'>about</span> <span m='1028339'>this?</span>
  </p><p><span m='1028750'>AUDIENCE:</span> <span m='1029712'>[INAUDIBLE].</span>
  </p><p><span m='1032519'>PROFESSOR:</span> <span m='1033319'>The</span> <span m='1033720'>TCP/IP</span>
  <span m='1035109'>protocol</span> <span m='1035760'>just</span> <span m='1036510'>has</span>
  <span m='1036790'>a</span> <span m='1037069'>32-bit</span> <span m='1037710'>CRC,</span>
  <span m='1038430'>I think,</span> <span m='1038950'>and</span> <span m='1040109'>if</span>
  <span m='1040329'>it</span> <span m='1040460'>fails</span> <span m='1040740'>to</span>
  <span m='1040869'>check,</span> <span m='1041240'>you</span> <span m='1041410'>ask</span>
  <span m='1041680'>for</span> <span m='1041760'>that</span> <span m='1042000'>packet</span>
  <span m='1042310'>again</span> <span m='1042800'>by</span> <span m='1042950'>packet</span>
  <span m='1043349'>number.</span> <span m='1048930'>OK?</span> <span m='1050090'>So</span>
  <span m='1051220'>Reed-Solomon</span> <span m='1051390'>codes,</span> <span m='1052190'>of</span>
  <span m='1052290'>course,</span> <span m='1052680'>are</span> <span m='1052870'>optimal</span>
  <span m='1053570'>if</span> <span m='1053800'>that's</span> <span m='1054040'>what</span>
  <span m='1054170'>you</span> <span m='1054310'>want</span> <span m='1054440'>to</span>
  <span m='1054570'>do.</span> <span m='1055040'>You</span> <span m='1055220'>couldn't</span>
  <span m='1056000'>possibly</span> <span m='1056520'>have</span> <span m='1056750'>a</span>
  <span m='1056810'>better</span> <span m='1057120'>code</span> <span m='1057590'>for</span>
  <span m='1058000'>coding</span> <span m='1058340'>across</span> <span m='1058790'>packets.</span>
  <span m='1059890'>But</span> <span m='1060110'>it's</span> <span m='1060300'>cumbersome</span>
  <span m='1061220'>in the</span> <span m='1061580'>packet</span> <span m='1062140'>environment.</span>
  <span m='1065860'>OK.</span> </p><p><span m='1069880'>Let's</span> <span m='1070270'>talk</span>
  <span m='1070610'>about</span> <span m='1071020'>concatenated</span> <span m='1071950'>codes.</span>
  <span m='1074060'>I guess</span> <span m='1074310'>I'll do it at</span> <span m='1074620'>the
  same</span> <span m='1074970'>place.</span> <span m='1092370'>This</span> <span
  m='1092630'>is</span> <span m='1095100'>something --</span> <span m='1095800'>I</span>
  <span m='1095950'>did in</span> <span m='1096220'>my</span> <span m='1096390'>thesis</span>
  <span m='1097070'>and</span> <span m='1099600'>last</span> <span m='1099910'>week</span>
  <span m='1100220'>I</span> <span m='1100330'>was</span> <span m='1100640'>at a</span>
  <span m='1103550'>tribute</span> <span m='1104110'>to</span> <span m='1104530'>Andy
  Viterbi,</span> <span m='1105420'>who</span> <span m='1106240'>invented</span> <span
  m='1106690'>the</span> <span m='1106900'>Viterbi</span> <span m='1107230'>algorithm,</span>
  <span m='1107680'>among</span> <span m='1107960'>other</span> <span m='1108160'>things.</span>
  <span m='1109310'>Of</span> <span m='1109350'>course,</span> <span m='1110070'>everybody</span>
  <span m='1110820'>knows</span> <span m='1111330'>that</span> <span m='1111460'>the</span>
  <span m='1111600'>Viterbi</span> <span m='1111950'>algorithm,</span> <span m='1112850'>when</span>
  <span m='1113070'>Andy</span> <span m='1113360'>invented</span> <span m='1113790'>it,</span>
  <span m='1115010'>he</span> <span m='1115070'>had</span> <span m='1115230'>no</span>
  <span m='1115380'>idea</span> <span m='1115730'>it was</span> <span m='1115880'>actually</span>
  <span m='1116190'>going</span> <span m='1116300'>to</span> <span m='1116340'>be</span>
  <span m='1116410'>a</span> <span m='1116460'>practical</span> <span m='1116950'>algorithm.</span>
  <span m='1117960'>It's</span> <span m='1118220'>become</span> <span m='1118400'>one</span>
  <span m='1118540'>of</span> <span m='1118600'>the</span> <span m='1118700'>super</span>
  <span m='1119050'>practical</span> <span m='1119520'>algorithms.</span> <span m='1120060'>He</span>
  <span m='1120190'>was</span> <span m='1120330'>just</span> <span m='1120920'>trying</span>
  <span m='1121080'>to</span> <span m='1121230'>prove</span> <span m='1121580'>a</span>
  <span m='1121640'>certain</span> <span m='1121940'>result,</span> <span m='1122570'>exponential</span>
  <span m='1123200'>error</span> <span m='1123420'>bounds</span> <span m='1123830'>for</span>
  <span m='1123950'>convolutional</span> <span m='1124550'>codes.</span> <span m='1125600'>And</span>
  <span m='1125910'>he</span> <span m='1126030'>thought</span> <span m='1126350'>the</span>
  <span m='1126430'>proof</span> <span m='1126780'>was</span> <span m='1126950'>easier</span>
  <span m='1127290'>to</span> <span m='1127380'>understand</span> <span m='1128030'>if</span>
  <span m='1128120'>you</span> <span m='1128300'>introduce</span> <span m='1128810'>this</span>
  <span m='1129560'>algorithm,</span> <span m='1132150'>which</span> <span m='1132840'>he</span>
  <span m='1133120'>describes</span> <span m='1133730'>perfectly.</span> <span m='1134240'>It</span>
  <span m='1134370'>is</span> <span m='1134560'>the</span> <span m='1134760'>Viterbi</span>
  <span m='1135120'>algorithm.</span> <span m='1135590'>But</span> <span m='1138550'>really,</span>
  <span m='1138820'>just</span> <span m='1139050'>a proof</span> <span m='1139410'>technique.</span>
  <span m='1140150'>Didn't</span> <span m='1140360'>even</span> <span m='1141090'>realize</span>
  <span m='1141580'>it</span> <span m='1141670'>was</span> <span m='1141830'>an</span>
  <span m='1141920'>optimum</span> <span m='1142360'>decoder.</span> </p><p><span
  m='1145140'>And</span> <span m='1145370'>then</span> <span m='1145630'>somebody,</span>
  <span m='1146180'>not</span> <span m='1146420'>him,</span> <span m='1146680'>not</span>
  <span m='1146980'>me,</span> <span m='1148080'>but</span> <span m='1148360'>in</span>
  <span m='1148520'>his</span> <span m='1148780'>company,</span> <span m='1149200'>fortunately,</span>
  <span m='1150280'>realized</span> <span m='1150800'>that</span> <span m='1150940'>gee,</span>
  <span m='1151380'>this</span> <span m='1151720'>could</span> <span m='1151840'>be</span>
  <span m='1151950'>very</span> <span m='1152200'>practical.</span> <span m='1153330'>And</span>
  <span m='1153600'>that</span> <span m='1153810'>became a</span> <span m='1154360'>workhorse</span>
  <span m='1155040'>decoding</span> <span m='1155520'>algorithm.</span> <span m='1156620'>Very</span>
  <span m='1156890'>similarly,</span> <span m='1157550'>concatenated</span> <span
  m='1158210'>codes</span> <span m='1158800'>are</span> <span m='1159180'>something</span>
  <span m='1159540'>that</span> <span m='1159680'>I</span> <span m='1161530'>did</span>
  <span m='1161700'>in</span> <span m='1161800'>my</span> <span m='1161940'>thesis</span>
  <span m='1162520'>in</span> <span m='1162660'>1965.</span> <span m='1164450'>And</span>
  <span m='1165660'>I</span> <span m='1165870'>was</span> <span m='1166650'>looking,</span>
  <span m='1167010'>basically,</span> <span m='1167510'>for a</span> <span m='1167710'>theoretical</span>
  <span m='1168360'>result.</span> <span m='1168880'>How could</span> <span m='1169280'>you</span>
  <span m='1169930'>approach</span> <span m='1170430'>capacity</span> <span m='1173960'>with</span>
  <span m='1174230'>an</span> <span m='1174340'>exponentially</span> <span m='1175060'>decreasing</span>
  <span m='1175810'>error</span> <span m='1176090'>probability</span> <span m='1176750'>near</span>
  <span m='1177060'>capacity</span> <span m='1178810'>but</span> <span m='1178980'>with</span>
  <span m='1179160'>only</span> <span m='1179380'>polynomial</span> <span m='1180120'>increasing</span>
  <span m='1180620'>complexity?</span> <span m='1182010'>And</span> <span m='1184090'>I</span>
  <span m='1185920'>looked</span> <span m='1186180'>into</span> <span m='1186360'>this</span>
  <span m='1186580'>very</span> <span m='1187050'>simple</span> <span m='1187500'>idea</span>
  <span m='1187870'>of</span> <span m='1188070'>basically</span> <span m='1188610'>taking</span>
  <span m='1188980'>two</span> <span m='1189200'>codes</span> <span m='1189690'>and</span>
  <span m='1189800'>using</span> <span m='1190140'>one</span> <span m='1190920'>to</span>
  <span m='1191090'>correct</span> <span m='1191520'>the</span> <span m='1191670'>errors</span>
  <span m='1192040'>of</span> <span m='1192120'>the</span> <span m='1192300'>other.</span>
  <span m='1192630'>And</span> <span m='1192760'>I</span> <span m='1192820'>found</span>
  <span m='1193160'>that</span> <span m='1193300'>you</span> <span m='1193450'>could</span>
  <span m='1193590'>do</span> <span m='1193750'>that.</span> </p><p><span m='1194590'>And</span>
  <span m='1195590'>I'd</span> <span m='1196540'>also</span> <span m='1197010'>never</span>
  <span m='1197270'>realized</span> <span m='1198405'>that</span> <span m='1198840'>this</span>
  <span m='1199310'>might</span> <span m='1199500'>actually</span> <span m='1199830'>be</span>
  <span m='1200020'>practical.</span> <span m='1200580'>I</span> <span m='1200670'>remember</span>
  <span m='1201590'>going</span> <span m='1201830'>around</span> <span m='1202260'>giving</span>
  <span m='1202830'>talks</span> <span m='1203370'>when</span> <span m='1203520'>I</span>
  <span m='1203650'>was</span> <span m='1203780'>interviewing</span> <span m='1204280'>afterwards</span>
  <span m='1204870'>that</span> <span m='1205500'>I</span> <span m='1205610'>was</span>
  <span m='1205780'>looking</span> <span m='1206040'>for an</span> <span m='1206220'>industrial</span>
  <span m='1207000'>position.</span> <span m='1207580'>I</span> <span m='1207630'>went</span>
  <span m='1207830'>down</span> <span m='1208020'>to</span> <span m='1208080'>places</span>
  <span m='1208520'>like</span> <span m='1208710'>Bell</span> <span m='1208920'>Labs,</span>
  <span m='1209570'>IBM</span> <span m='1210040'>labs,</span> <span m='1210295'>and</span>
  <span m='1211450'>did</span> <span m='1211730'>seminars</span> <span m='1213030'>talking</span>
  <span m='1213280'>about</span> <span m='1213570'>codes</span> <span m='1214080'>that</span>
  <span m='1214180'>were</span> <span m='1215390'>thousands</span> <span m='1215950'>of</span>
  <span m='1216040'>symbols</span> <span m='1216520'>long</span> <span m='1217020'>and</span>
  <span m='1217300'>everybody</span> <span m='1217690'>rolled</span> <span m='1218030'>their</span>
  <span m='1218260'>eyes</span> <span m='1218630'>and</span> <span m='1218700'>said,</span>
  <span m='1218820'>boy,</span> <span m='1218880'>this</span> <span m='1219290'>guy
  is</span> <span m='1219630'>not</span> <span m='1219850'>very</span> <span m='1220030'>practical.</span>
  <span m='1222320'>And</span> <span m='1222740'>to</span> <span m='1222850'>my</span>
  <span m='1223080'>surprise</span> <span m='1223810'>and</span> <span m='1224070'>everyone</span>
  <span m='1224330'>else's</span> <span m='1224540'>surprise,</span> <span m='1225620'>this</span>
  <span m='1226530'>became</span> <span m='1227880'>and</span> <span m='1228120'>still</span>
  <span m='1228480'>is</span> <span m='1229930'>a</span> <span m='1230030'>very</span>
  <span m='1230340'>practical</span> <span m='1231560'>way</span> <span m='1232420'>of</span>
  <span m='1232680'>getting</span> <span m='1232990'>high-performance</span> <span
  m='1233900'>codes.</span> <span m='1234460'>This,</span> <span m='1234820'>in</span>
  <span m='1235230'>conjunction --</span> <span m='1236610'>well,</span> <span m='1237020'>I'll</span>
  <span m='1237600'>get</span> <span m='1237760'>into</span> <span m='1238110'>it,</span>
  <span m='1238310'>but</span> <span m='1238630'>this</span> <span m='1238850'>was,</span>
  <span m='1240020'>again,</span> <span m='1240430'>a</span> <span m='1240460'>workhorse</span>
  <span m='1241450'>coding</span> <span m='1241800'>technique</span> <span m='1244420'>and</span>
  <span m='1245270'>still</span> <span m='1245670'>is</span> <span m='1245830'>in</span>
  <span m='1245930'>wide</span> <span m='1246270'>use.</span> <span m='1247730'>In</span>
  <span m='1247950'>fact,</span> <span m='1249042'>as</span> <span m='1249380'>you
  will</span> <span m='1249660'>see,</span> <span m='1250050'>this</span> <span m='1251550'>contains</span>
  <span m='1251960'>some</span> <span m='1252220'>of</span> <span m='1252280'>the</span>
  <span m='1252440'>ideas</span> <span m='1253060'>that</span> <span m='1254210'>go</span>
  <span m='1254430'>into</span> <span m='1255350'>modern</span> <span m='1255930'>capacity-approaching</span>
  <span m='1257010'>codes.</span> </p><p><span m='1258650'>But</span> <span m='1258850'>the</span>
  <span m='1259000'>idea</span> <span m='1259340'>is</span> <span m='1259460'>very</span>
  <span m='1259690'>simple.</span> <span m='1261100'>You</span> <span m='1261280'>can</span>
  <span m='1264110'>do</span> <span m='1264290'>it</span> <span m='1264450'>two</span>
  <span m='1264650'>ways,</span> <span m='1265842'>or</span> <span m='1267230'>probably</span>
  <span m='1267650'>many more</span> <span m='1267850'>than</span> <span m='1268080'>two.</span>
  <span m='1270730'>Suppose</span> <span m='1271210'>we</span> <span m='1271360'>have</span>
  <span m='1271670'>a</span> <span m='1272580'>basically</span> <span m='1273200'>binary</span>
  <span m='1273760'>channel.</span> <span m='1277910'>I'll</span> <span m='1278070'>just</span>
  <span m='1278660'>say</span> <span m='1278910'>a</span> <span m='1279030'>core</span>
  <span m='1279660'>physical</span> <span m='1280170'>channel</span> <span m='1280660'>there.</span>
  <span m='1281340'>The</span> <span m='1281620'>channel</span> <span m='1282070'>is</span>
  <span m='1282220'>what</span> <span m='1282460'>you</span> <span m='1282640'>can't</span>
  <span m='1283660'>affect</span> <span m='1284210'>as</span> <span m='1284430'>an</span>
  <span m='1284510'>engineer.</span> <span m='1285200'>So</span> <span m='1286320'>let's</span>
  <span m='1286530'>say</span> <span m='1286710'>we</span> <span m='1286820'>have</span>
  <span m='1286930'>a</span> <span m='1286980'>binary</span> <span m='1287470'>symmetric</span>
  <span m='1287840'>channel</span> <span m='1288320'>or</span> <span m='1288540'>a</span>
  <span m='1288580'>binary</span> <span m='1289030'>input</span> <span m='1289370'>additive</span>
  <span m='1289710'>white</span> <span m='1289880'>Gaussian</span> <span m='1290460'>noise</span>
  <span m='1290790'>channel</span> <span m='1292162'>or</span> <span m='1292530'>whatever</span>
  <span m='1292670'>you</span> <span m='1292850'>like.</span> <span m='1293310'>And</span>
  <span m='1293580'>then</span> <span m='1293760'>we</span> <span m='1293930'>could</span>
  <span m='1294610'>put</span> <span m='1294840'>on</span> <span m='1295060'>it</span>
  <span m='1295370'>an</span> <span m='1297850'>encoder</span> <span m='1300446'>and</span>
  <span m='1300850'>decoder</span> <span m='1306440'>for</span> <span m='1307570'>an</span>
  <span m='1307860'>n,</span> <span m='1308140'>k,</span> <span m='1308460'>d</span>
  <span m='1310790'>binary</span> <span m='1311210'>linear</span> <span m='1311670'>block</span>
  <span m='1312060'>code.</span> <span m='1316080'>OK?</span> </p><p><span m='1318740'>Now,</span>
  <span m='1320370'>from</span> <span m='1320540'>the</span> <span m='1320650'>input</span>
  <span m='1321120'>and</span> <span m='1321280'>the</span> <span m='1321400'>output,</span>
  <span m='1322030'>what</span> <span m='1322230'>is</span> <span m='1322420'>this</span>
  <span m='1323150'>channel</span> <span m='1323490'>going</span> <span m='1323590'>to</span>
  <span m='1323680'>look</span> <span m='1323920'>like?</span> <span m='1327720'>At</span>
  <span m='1327910'>the</span> <span m='1328010'>input,</span> <span m='1328500'>we're</span>
  <span m='1328660'>putting --</span> <span m='1329220'>basically,</span> <span m='1330260'>per</span>
  <span m='1330460'>block,</span> <span m='1330900'>we</span> <span m='1331030'>put</span>
  <span m='1331400'>k</span> <span m='1331520'>bits</span> <span m='1331800'>in.</span>
  <span m='1332780'>They're</span> <span m='1332940'>encoded</span> <span m='1333400'>into</span>
  <span m='1333700'>n</span> <span m='1333950'>bits.</span> <span m='1335390'>They're
  sent</span> <span m='1335660'>over</span> <span m='1335850'>the</span> <span m='1335990'>channel,</span>
  <span m='1337860'>received</span> <span m='1339440'>some</span> <span m='1339900'>n-tuple</span>
  <span m='1341110'>of</span> <span m='1341500'>noisy</span> <span m='1341860'>received</span>
  <span m='1342280'>symbols.</span> <span m='1343250'>The</span> <span m='1343430'>decoder</span>
  <span m='1344440'>tries</span> <span m='1344760'>to</span> <span m='1344850'>find</span>
  <span m='1345150'>the</span> <span m='1345230'>best</span> <span m='1345530'>code</span>
  <span m='1345790'>word.</span> <span m='1346480'>The</span> <span m='1346770'>code</span>
  <span m='1347030'>word</span> <span m='1347280'>is</span> <span m='1347430'>identified</span>
  <span m='1348070'>by</span> <span m='1348210'>k</span> <span m='1348490'>bits.</span>
  <span m='1352170'>Most of</span> <span m='1352520'>the</span> <span m='1352650'>time</span>
  <span m='1353400'>there'll</span> <span m='1353920'>be</span> <span m='1354070'>no</span>
  <span m='1354260'>error</span> <span m='1354680'>and</span> <span m='1354770'>these
  --</span> <span m='1356370'>let's</span> <span m='1356600'>call</span> <span m='1356890'>this</span>
  <span m='1358870'>u</span> <span m='1359500'>in</span> <span m='1359930'>and</span>
  <span m='1360350'>u hat</span> <span m='1361050'>out.</span> <span m='1361520'>u</span>
  <span m='1361750'>hat</span> <span m='1362010'>is</span> <span m='1362180'>going</span>
  <span m='1362290'>to</span> <span m='1362400'>equal</span> <span m='1362990'>u.</span>
  </p><p><span m='1365240'>But,</span> <span m='1365560'>of</span> <span m='1365730'>course,</span>
  <span m='1366820'>let's</span> <span m='1367320'>imagine</span> <span m='1367770'>this
  is</span> <span m='1367850'>a</span> <span m='1368150'>relatively</span> <span m='1368450'>short</span>
  <span m='1368870'>code.</span> <span m='1369790'>Let's</span> <span m='1370020'>imagine</span>
  <span m='1370500'>this</span> <span m='1370760'>is</span> <span m='1371040'>a</span>
  <span m='1371230'>maximum</span> <span m='1371750'>likelihood</span> <span m='1372290'>decoder</span>
  <span m='1373230'>or</span> <span m='1373380'>minimum</span> <span m='1373710'>distance</span>
  <span m='1374220'>decoder</span> <span m='1374780'>in</span> <span m='1374860'>the</span>
  <span m='1374950'>appropriate</span> <span m='1375500'>space.</span> <span m='1377800'>Then</span>
  <span m='1379490'>the</span> <span m='1379610'>complexity</span> <span m='1380280'>is</span>
  <span m='1380500'>going</span> <span m='1380600'>to</span> <span m='1380690'>be</span>
  <span m='1380950'>of the</span> <span m='1381070'>order</span> <span m='1381400'>of</span>
  <span m='1381500'>2</span> <span m='1381690'>to</span> <span m='1381780'>the</span>
  <span m='1381940'>k.</span> <span m='1383890'>And</span> <span m='1384180'>so</span>
  <span m='1384330'>you</span> <span m='1384480'>can't</span> <span m='1384730'>let</span>
  <span m='1384970'>k</span> <span m='1385200'>get</span> <span m='1385450'>very</span>
  <span m='1385680'>big.</span> <span m='1387080'>We'll</span> <span m='1387600'>find</span>
  <span m='1388000'>somewhat</span> <span m='1388300'>better</span> <span m='1388530'>ways</span>
  <span m='1388870'>to</span> <span m='1388960'>do</span> <span m='1389180'>maximum</span>
  <span m='1389600'>likelihood</span> <span m='1390010'>decoding.</span> <span m='1390900'>But</span>
  <span m='1391260'>if</span> <span m='1391310'>you're</span> <span m='1391430'>really</span>
  <span m='1391630'>trying</span> <span m='1391760'>to</span> <span m='1391890'>do</span>
  <span m='1392040'>optimum</span> <span m='1392420'>decoding,</span> <span m='1392950'>the</span>
  <span m='1393050'>complexity</span> <span m='1393570'>is</span> <span m='1393720'>going</span>
  <span m='1393830'>to</span> <span m='1393870'>go</span> <span m='1393980'>up</span>
  <span m='1394140'>exponentially</span> <span m='1394890'>at</span> <span m='1395030'>this</span>
  <span m='1395170'>stage</span> <span m='1396080'>with</span> <span m='1396670'>the</span>
  <span m='1396770'>number</span> <span m='1397030'>of</span> <span m='1397100'>information</span>
  <span m='1397710'>bits</span> <span m='1398000'>k.</span> <span m='1398350'>So</span>
  <span m='1398590'>this</span> <span m='1398830'>is</span> <span m='1399000'>not</span>
  <span m='1399710'>the</span> <span m='1399820'>scheme</span> <span m='1400150'>that</span>
  <span m='1400280'>we're</span> <span m='1400410'>looking</span> <span m='1400750'>for</span>
  <span m='1401060'>that</span> <span m='1401230'>has</span> <span m='1401440'>only</span>
  <span m='1401670'>polynomial</span> <span m='1402370'>complexity.</span> <span m='1403940'>We</span>
  <span m='1404200'>know</span> <span m='1404520'>that</span> <span m='1404860'>we</span>
  <span m='1405170'>can</span> <span m='1405480'>choose</span> <span m='1405840'>codes</span>
  <span m='1406190'>like</span> <span m='1406420'>this</span> <span m='1406730'>that</span>
  <span m='1406800'>with</span> <span m='1407140'>optimum</span> <span m='1407360'>decoding</span>
  <span m='1408750'>get</span> <span m='1408980'>to</span> <span m='1409080'>capacity.</span>
  <span m='1409700'>That's</span> <span m='1409870'>Shannon's</span> <span m='1410740'>theorem.</span>
  <span m='1412350'>But</span> <span m='1412740'>we</span> <span m='1412860'>don't</span>
  <span m='1413010'>know</span> <span m='1413570'>how</span> <span m='1413690'>to</span>
  <span m='1413790'>decode</span> <span m='1414200'>them</span> <span m='1414360'>with</span>
  <span m='1415260'>reasonable</span> <span m='1416040'>complexity.</span> </p><p><span
  m='1417950'>But,</span> <span m='1418340'>all</span> <span m='1418430'>right,</span>
  <span m='1418620'>here's</span> <span m='1418850'>a</span> <span m='1418920'>start.</span>
  <span m='1419320'>We</span> <span m='1419470'>could</span> <span m='1419590'>use</span>
  <span m='1420710'>a</span> <span m='1420790'>relatively</span> <span m='1421630'>modest</span>
  <span m='1422160'>length</span> <span m='1422500'>code</span> <span m='1422890'>that</span>
  <span m='1423040'>we</span> <span m='1423590'>can</span> <span m='1423910'>feasibly</span>
  <span m='1424490'>decode.</span> <span m='1425480'>And</span> <span m='1425620'>this</span>
  <span m='1425790'>is</span> <span m='1425920'>what</span> <span m='1426090'>we</span>
  <span m='1426230'>get.</span> <span m='1428470'>OK.</span> <span m='1429740'>So</span>
  <span m='1430010'>we</span> <span m='1430120'>have</span> <span m='1430430'>blocks</span>
  <span m='1430890'>going</span> <span m='1431230'>in.</span> <span m='1432240'>Block</span>
  <span m='1432730'>from</span> <span m='1433070'>an</span> <span m='1433460'>alphabet</span>
  <span m='1434030'>of</span> <span m='1434080'>size</span> <span m='1434510'>2</span>
  <span m='1434690'>to</span> <span m='1434760'>the</span> <span m='1434890'>k.</span>
  <span m='1435920'>Blocks</span> <span m='1436260'>coming</span> <span m='1436550'>out,</span>
  <span m='1436940'>alphabet</span> <span m='1437420'>size</span> <span m='1437740'>2</span>
  <span m='1437990'>to the</span> <span m='1438110'>k.</span> <span m='1438550'>Occasionally,</span>
  <span m='1439060'>we</span> <span m='1439180'>make</span> <span m='1439440'>errors.</span>
  <span m='1441710'>What's</span> <span m='1441950'>a</span> <span m='1442010'>good</span>
  <span m='1442180'>idea</span> <span m='1442640'>to</span> <span m='1442820'>then</span>
  <span m='1443090'>do?</span> <span m='1446150'>This</span> <span m='1446360'>is</span>
  <span m='1446480'>not</span> <span m='1446670'>very</span> <span m='1446890'>hard.</span>
  <span m='1447770'>This is</span> <span m='1447920'>why</span> <span m='1448090'>you</span>
  <span m='1448200'>should</span> <span m='1448380'>have</span> <span m='1448510'>been
  in</span> <span m='1448680'>this</span> <span m='1448850'>field</span> <span m='1449160'>in</span>
  <span m='1449240'>the</span> <span m='1449310'>'60s</span> <span m='1449870'>rather</span>
  <span m='1450160'>than</span> <span m='1451180'>the</span> <span m='1451340'>year</span>
  <span m='1452020'>2005.</span> <span m='1452870'>There</span> <span m='1453010'>were</span>
  <span m='1453060'>lots</span> <span m='1453400'>of</span> <span m='1453490'>good</span>
  <span m='1454090'>ideas</span> <span m='1454660'>just</span> <span m='1455170'>laying</span>
  <span m='1455570'>around</span> <span m='1455900'>waiting</span> <span m='1456230'>to</span>
  <span m='1456300'>be</span> <span m='1456440'>picked</span> <span m='1456790'>up.</span>
  <span m='1458530'>Class?</span> <span m='1459020'>Anyone</span> <span m='1459380'>have</span>
  <span m='1459490'>a</span> <span m='1459590'>suggestion</span> <span m='1460250'>for</span>
  <span m='1460460'>how</span> <span m='1460600'>to</span> <span m='1460670'>make</span>
  <span m='1460980'>further</span> <span m='1461310'>improvement</span> <span m='1461780'>in</span>
  <span m='1461890'>this</span> <span m='1461990'>system?</span> </p><p><span m='1462480'>AUDIENCE:</span>
  <span m='1462902'>[INAUDIBLE].</span> </p><p><span m='1464168'>PROFESSOR:</span>
  <span m='1464590'>Add</span> <span m='1464800'>another</span> <span m='1465100'>code.</span>
  <span m='1465590'>What</span> <span m='1465810'>should</span> <span m='1466140'>it
  be?</span> <span m='1468690'>Let's</span> <span m='1469470'>put</span> <span m='1469770'>an</span>
  <span m='1469860'>encoder</span> <span m='1470390'>here</span> <span m='1474110'>for</span>
  <span m='1474420'>what?</span> </p><p><span m='1478734'>AUDIENCE:</span> <span m='1479222'>[INAUDIBLE].</span>
  </p><p><span m='1481662'>PROFESSOR:</span> <span m='1482638'>Everyone</span> <span
  m='1483126'>is</span> <span m='1483630'>extremely</span> <span m='1484300'>wide</span>
  <span m='1484590'>awake.</span> <span m='1485190'>An</span> <span m='1485510'>n,</span>
  <span m='1485810'>k,</span> <span m='1486290'>d</span> <span m='1487540'>Reed-Solomon</span>
  <span m='1488390'>code</span> <span m='1489570'>over</span> <span m='1489850'>what</span>
  <span m='1490070'>field?</span> <span m='1495670'>In</span> <span m='1495830'>principle,</span>
  <span m='1496690'>it should</span> <span m='1496920'>be</span> <span m='1497150'>over</span>
  <span m='1498480'>F2</span> <span m='1498670'>to</span> <span m='1499110'>the</span>
  <span m='1499260'>k.</span> <span m='1500965'>Now,</span> <span m='1501420'>of</span>
  <span m='1501460'>course,</span> <span m='1501830'>if</span> <span m='1502120'>k</span>
  <span m='1502360'>is</span> <span m='1502520'>64</span> <span m='1502920'>or</span>
  <span m='1503310'>something</span> <span m='1503700'>here,</span> <span m='1503930'>you</span>
  <span m='1504070'>might</span> <span m='1504270'>not</span> <span m='1504450'>even</span>
  <span m='1504650'>go</span> <span m='1504810'>all</span> <span m='1504930'>the</span>
  <span m='1505050'>way</span> <span m='1505410'>to</span> <span m='1506180'>field
  of</span> <span m='1506820'>2 to the</span> <span m='1506890'>64</span> <span m='1507230'>elements.</span>
  <span m='1507900'>You</span> <span m='1507990'>might</span> <span m='1508200'>divide</span>
  <span m='1508500'>it</span> <span m='1508600'>up</span> <span m='1508740'>again</span>
  <span m='1509040'>as</span> <span m='1509170'>we</span> <span m='1509280'>did</span>
  <span m='1509450'>in</span> <span m='1509540'>the</span> <span m='1509620'>packet</span>
  <span m='1510600'>error</span> <span m='1510880'>correction.</span> <span m='1511380'>But</span>
  <span m='1513320'>basically,</span> <span m='1513970'>the way</span> <span m='1514520'>this</span>
  <span m='1514780'>goes</span> <span m='1515110'>is</span> <span m='1515210'>you</span>
  <span m='1515330'>try</span> <span m='1515560'>to</span> <span m='1516170'>keep</span>
  <span m='1516430'>this</span> <span m='1516690'>as</span> <span m='1516790'>small</span>
  <span m='1517180'>as</span> <span m='1517310'>possible</span> <span m='1517890'>so
  that</span> <span m='1518280'>this</span> <span m='1519080'>can</span> <span m='1519190'>still</span>
  <span m='1519450'>work.</span> </p><p><span m='1519770'>There's</span> <span m='1519920'>a</span>
  <span m='1519980'>tradeoff</span> <span m='1520490'>between</span> <span m='1520850'>the</span>
  <span m='1521540'>complexity</span> <span m='1526360'>of</span> <span m='1526570'>the</span>
  <span m='1526680'>two</span> <span m='1526930'>codes</span> <span m='1527570'>and</span>
  <span m='1527680'>therefore,</span> <span m='1528090'>the</span> <span m='1528230'>rates.</span>
  <span m='1529672'>The</span> <span m='1530070'>decoder --</span> <span m='1533390'>here</span>
  <span m='1533790'>we</span> <span m='1534080'>have</span> <span m='1534360'>an</span>
  <span m='1534840'>algebraic</span> <span m='1536620'>Reed-Solomon</span> <span m='1537360'>decoder,</span>
  <span m='1542740'>which,</span> <span m='1544160'>in</span> <span m='1544270'>the</span>
  <span m='1544340'>simplest</span> <span m='1545750'>case,</span> <span m='1546200'>could</span>
  <span m='1546360'>just</span> <span m='1547550'>do</span> <span m='1547820'>error</span>
  <span m='1548080'>correction.</span> <span m='1548660'>Just</span> <span m='1548900'>take</span>
  <span m='1549130'>these</span> <span m='1549360'>k</span> <span m='1549560'>bits</span>
  <span m='1549960'>as</span> <span m='1550120'>a</span> <span m='1550590'>hard</span>
  <span m='1550880'>decision</span> <span m='1551440'>on</span> <span m='1551640'>u</span>
  <span m='1551880'>hat</span> <span m='1552780'>and</span> <span m='1553020'>try</span>
  <span m='1553190'>to</span> <span m='1553300'>correct</span> <span m='1553690'>any</span>
  <span m='1553880'>errors</span> <span m='1554310'>that</span> <span m='1554410'>occurred</span>
  <span m='1554840'>in</span> <span m='1554990'>this</span> <span m='1555970'>inner</span>
  <span m='1556900'>loop</span> <span m='1557310'>here,</span> <span m='1557580'>which</span>
  <span m='1558450'>we</span> <span m='1558550'>might</span> <span m='1558790'>think</span>
  <span m='1559000'>of</span> <span m='1559110'>this</span> <span m='1559450'>as</span>
  <span m='1559680'>being</span> <span m='1560570'>a</span> <span m='1560700'>2</span>
  <span m='1560980'>to the</span> <span m='1561100'>kre</span> <span m='1561580'>channel.</span>
  <span m='1562110'>So</span> <span m='1562420'>this</span> <span m='1562610'>whole</span>
  <span m='1562850'>thing</span> <span m='1563080'>together</span> <span m='1564270'>is</span>
  <span m='1564580'>a</span> <span m='1565030'>2 to the</span> <span m='1565440'>kre</span>
  <span m='1566230'>super</span> <span m='1566620'>channel.</span> <span m='1569500'>Sorry</span>
  <span m='1569810'>if</span> <span m='1569950'>you</span> <span m='1570070'>can't</span>
  <span m='1570360'>read</span> <span m='1570600'>that,</span> <span m='1571465'>but</span>
  <span m='1571760'>you</span> <span m='1571960'>heard</span> <span m='1572170'>me</span>
  <span m='1572300'>say</span> <span m='1572560'>it.</span> </p><p><span m='1575020'>So</span>
  <span m='1575380'>here's</span> <span m='1575680'>a</span> <span m='1575750'>channel</span>
  <span m='1576290'>that</span> <span m='1577030'>takes</span> <span m='1577330'>in</span>
  <span m='1578170'>2 to the</span> <span m='1578490'>kre</span> <span m='1578890'>symbols,</span>
  <span m='1579470'>puts</span> <span m='1579740'>out</span> <span m='1579990'>2 to</span>
  <span m='1580120'>the</span> <span m='1580300'>kre</span> <span m='1580700'>symbols</span>
  <span m='1581290'>and</span> <span m='1583580'>sometimes</span> <span m='1584050'>makes</span>
  <span m='1584280'>errors</span> <span m='1585900'>according</span> <span m='1586320'>to</span>
  <span m='1586430'>whatever</span> <span m='1586710'>the</span> <span m='1586810'>error</span>
  <span m='1587020'>probability</span> <span m='1587340'>you</span> <span m='1587660'>can</span>
  <span m='1587770'>achieve</span> <span m='1588160'>here is.</span> <span m='1591560'>Or</span>
  <span m='1593650'>some</span> <span m='1593930'>of</span> <span m='1594180'>the</span>
  <span m='1594400'>discussion</span> <span m='1595030'>back</span> <span m='1595340'>when</span>
  <span m='1595440'>we</span> <span m='1595560'>were talking</span> <span m='1595760'>about</span>
  <span m='1595930'>hard</span> <span m='1596210'>decision</span> <span m='1596480'>with</span>
  <span m='1596750'>binary</span> <span m='1597870'>suggested</span> <span m='1598205'>that</span>
  <span m='1598540'>it</span> <span m='1598640'>would</span> <span m='1598820'>be</span>
  <span m='1599170'>better</span> <span m='1599620'>to</span> <span m='1599760'>pass</span>
  <span m='1600150'>along</span> <span m='1600540'>more</span> <span m='1601050'>reliability</span>
  <span m='1601820'>information</span> <span m='1602510'>here</span> <span m='1603980'>along</span>
  <span m='1604380'>with</span> <span m='1604690'>just</span> <span m='1604970'>the</span>
  <span m='1605090'>hard</span> <span m='1605350'>decision.</span> <span m='1609980'>And</span>
  <span m='1610680'>the</span> <span m='1610850'>very</span> <span m='1611110'>simplest</span>
  <span m='1611630'>kind</span> <span m='1611830'>of</span> <span m='1611910'>reliability</span>
  <span m='1612480'>information</span> <span m='1613210'>is</span> <span m='1614340'>if</span>
  <span m='1614600'>this</span> <span m='1614870'>guy</span> <span m='1615070'>really</span>
  <span m='1615380'>isn't</span> <span m='1615630'>sure,</span> <span m='1618190'>if</span>
  <span m='1618470'>either</span> <span m='1618780'>the</span> <span m='1618880'>noise</span>
  <span m='1619190'>is</span> <span m='1619310'>too</span> <span m='1619490'>large</span>
  <span m='1619950'>so</span> <span m='1620030'>he</span> <span m='1620140'>can't</span>
  <span m='1620340'>make</span> <span m='1620540'>any</span> <span m='1620720'>decision</span>
  <span m='1621740'>or</span> <span m='1622940'>if</span> <span m='1623210'>the</span>
  <span m='1623330'>noise</span> <span m='1623690'>leaves</span> <span m='1623920'>him</span>
  <span m='1624000'>exactly</span> <span m='1624780'>halfway</span> <span m='1625300'>between</span>
  <span m='1625690'>two</span> <span m='1625870'>code</span> <span m='1626140'>words</span>
  <span m='1626530'>so</span> <span m='1626750'>it's</span> <span m='1626920'>a</span>
  <span m='1626980'>completely</span> <span m='1627370'>ambiguous</span> <span m='1627950'>decision,</span>
  <span m='1629050'>or</span> <span m='1629210'>whatever</span> <span m='1629590'>criteria</span>
  <span m='1630160'>you</span> <span m='1630380'>have,</span> <span m='1631290'>this</span>
  <span m='1631540'>might</span> <span m='1631780'>make</span> <span m='1631990'>erasures.</span>
  </p><p><span m='1633600'>And</span> <span m='1633980'>I'm</span> <span m='1634060'>sure</span>
  <span m='1634510'>Ralf</span> <span m='1634830'>told</span> <span m='1635120'>you</span>
  <span m='1635260'>how</span> <span m='1635380'>to</span> <span m='1635500'>do</span>
  <span m='1635900'>error</span> <span m='1636190'>and</span> <span m='1636270'>erasure</span>
  <span m='1636730'>correction</span> <span m='1637280'>with</span> <span m='1637510'>Reed-Solomon</span>
  <span m='1638190'>codes.</span> <span m='1640870'>Or</span> <span m='1641050'>this</span>
  <span m='1641290'>could</span> <span m='1641470'>be</span> <span m='1641630'>more</span>
  <span m='1642100'>likely</span> <span m='1642520'>that</span> <span m='1642670'>information</span>
  <span m='1643590'>just --</span> <span m='1645320'>how</span> <span m='1645510'>likely</span>
  <span m='1646610'>was</span> <span m='1646900'>the</span> <span m='1647000'>code</span>
  <span m='1647260'>word</span> <span m='1647630'>you</span> <span m='1647740'>actually</span>
  <span m='1648100'>saw?</span> <span m='1648490'>And</span> <span m='1648570'>there</span>
  <span m='1648700'>are</span> <span m='1648740'>various</span> <span m='1649530'>ways</span>
  <span m='1649970'>of</span> <span m='1650080'>devising</span> <span m='1650720'>an</span>
  <span m='1650870'>approximate</span> <span m='1652080'>likelihood</span> <span m='1652630'>metric.</span>
  <span m='1653900'>You</span> <span m='1654020'>just</span> <span m='1654240'>do</span>
  <span m='1654620'>what</span> <span m='1654800'>makes</span> <span m='1655100'>sense</span>
  <span m='1655980'>that</span> <span m='1656120'>indicates</span> <span m='1656650'>that</span>
  <span m='1656750'>some</span> <span m='1657030'>words,</span> <span m='1657470'>you're</span>
  <span m='1657670'>absolutely</span> <span m='1658090'>sure</span> <span m='1658510'>of</span>
  <span m='1658780'>in</span> <span m='1658980'>this</span> <span m='1659170'>decoding.</span>
  <span m='1660130'>And</span> <span m='1660310'>other</span> <span m='1660480'>words,</span>
  <span m='1663490'>you</span> <span m='1663600'>don't</span> <span m='1663770'>know
  --</span> <span m='1664890'>if</span> <span m='1665170'>you</span> <span m='1665410'>have</span>
  <span m='1666050'>one</span> <span m='1666240'>or</span> <span m='1666280'>more</span>
  <span m='1666520'>good</span> <span m='1666690'>candidates</span> <span m='1667370'>or</span>
  <span m='1667450'>you</span> <span m='1667660'>have no</span> <span m='1667840'>good</span>
  <span m='1668050'>candidates.</span> <span m='1670620'>So</span> <span m='1671290'>based</span>
  <span m='1671620'>on</span> <span m='1671740'>this</span> <span m='1671860'>reliability</span>
  <span m='1672520'>information,</span> <span m='1673190'>you</span> <span m='1673340'>can</span>
  <span m='1673490'>actually</span> <span m='1674880'>incorporate</span> <span m='1675670'>that.</span>
  <span m='1675990'>Did</span> <span m='1676280'>Ralf</span> <span m='1676590'>talk</span>
  <span m='1676880'>about</span> <span m='1677120'>reliability-based</span> <span
  m='1678120'>decoding?</span> <span m='1678580'>Soft</span> <span m='1678940'>decoding</span>
  <span m='1679370'>algorithms</span> <span m='1679970'>for</span> <span m='1680240'>Reed-Solomon</span>
  <span m='1680700'>codes?</span> <span m='1682030'>No?</span> <span m='1682710'>OK,</span>
  <span m='1683220'>well,</span> <span m='1683450'>that's</span> <span m='1683490'>a
  shame</span> <span m='1683910'>because</span> <span m='1684180'>he</span> <span
  m='1684360'>and</span> <span m='1685010'>Alex</span> <span m='1685370'>Vardy</span>
  <span m='1685800'>are</span> <span m='1685950'>the</span> <span m='1686200'>inventors</span>
  <span m='1686720'>of</span> <span m='1688600'>a</span> <span m='1688620'>very</span>
  <span m='1688870'>good</span> <span m='1689090'>class</span> <span m='1689930'>that's</span>
  <span m='1690250'>recently</span> <span m='1690740'>been</span> <span m='1691120'>improved.</span>
  </p><p><span m='1691760'>So</span> <span m='1692960'>one</span> <span m='1693210'>of</span>
  <span m='1693370'>the</span> <span m='1695400'>knocks</span> <span m='1695930'>on</span>
  <span m='1696430'>Reed-Solomon</span> <span m='1697150'>codes</span> <span m='1698330'>is</span>
  <span m='1698800'>that,</span> <span m='1699640'>at</span> <span m='1700060'>one</span>
  <span m='1700360'>point,</span> <span m='1700560'>you</span> <span m='1700710'>might</span>
  <span m='1700880'>have</span> <span m='1700990'>said</span> <span m='1701260'>a</span>
  <span m='1701370'>minus</span> <span m='1704820'>can</span> <span m='1704930'>only</span>
  <span m='1705150'>work</span> <span m='1705520'>with</span> <span m='1705670'>hard</span>
  <span m='1706010'>decisions.</span> <span m='1709000'>And</span> <span m='1709530'>then,</span>
  <span m='1709800'>fairly</span> <span m='1710140'>early,</span> <span m='1710540'>it
  was</span> <span m='1710750'>figured</span> <span m='1711070'>out</span> <span m='1711280'>how</span>
  <span m='1711410'>to</span> <span m='1711540'>correct</span> <span m='1711930'>to</span>
  <span m='1712060'>erasures.</span> <span m='1713970'>But</span> <span m='1714270'>just</span>
  <span m='1714610'>in</span> <span m='1714690'>the</span> <span m='1714940'>last</span>
  <span m='1715180'>10</span> <span m='1715430'>years,</span> <span m='1717380'>we</span>
  <span m='1717500'>now</span> <span m='1717750'>have --</span> <span m='1719320'>this
  is</span> <span m='1719560'>no</span> <span m='1719710'>longer</span> <span m='1720030'>true.</span>
  <span m='1720420'>We</span> <span m='1720600'>can</span> <span m='1721150'>have</span>
  <span m='1721430'>soft,</span> <span m='1722950'>meaning</span> <span m='1723320'>reliability-labeled</span>
  <span m='1725350'>inputs.</span> <span m='1735740'>And</span> <span m='1737420'>this
  is a</span> <span m='1737650'>plus.</span> <span m='1738890'>That</span> <span m='1739100'>means</span>
  <span m='1739410'>we</span> <span m='1739560'>can</span> <span m='1739700'>do</span>
  <span m='1740560'>soft --</span> <span m='1741260'>and</span> <span m='1741440'>we</span>
  <span m='1741550'>have</span> <span m='1741960'>corresponding</span> <span m='1742680'>algorithms</span>
  <span m='1743430'>that can</span> <span m='1743730'>do</span> <span m='1744650'>soft</span>
  <span m='1745140'>Reed-Solomon</span> <span m='1745760'>decoding.</span> <span m='1747080'>They</span>
  <span m='1747260'>are,</span> <span m='1747670'>of</span> <span m='1748110'>course,</span>
  <span m='1748440'>more</span> <span m='1748640'>complicated</span> <span m='1749440'>than</span>
  <span m='1749570'>just</span> <span m='1749770'>straightforward</span> <span m='1750700'>error</span>
  <span m='1751020'>correction</span> <span m='1751520'>with</span> <span m='1751670'>hard</span>
  <span m='1751930'>decisions.</span> <span m='1753720'>But</span> <span m='1755380'>there's</span>
  <span m='1755980'>still</span> <span m='1756270'>polynomial</span> <span m='1756880'>complexity.</span>
  <span m='1757660'>They're</span> <span m='1760030'>maybe</span> <span m='1760410'>an
  order</span> <span m='1760830'>of</span> <span m='1761750'>slightly</span> <span
  m='1762370'>higher</span> <span m='1763480'>degree</span> <span m='1764070'>of</span>
  <span m='1764190'>n,</span> <span m='1765660'>but</span> <span m='1765990'>still</span>
  <span m='1766510'>polynomial</span> <span m='1766855'>in</span> <span m='1767200'>the</span>
  <span m='1767250'>block</span> <span m='1767600'>length</span> <span m='1767990'>or</span>
  <span m='1768130'>in</span> <span m='1768460'>k</span> <span m='1768710'>or</span>
  <span m='1768860'>d</span> <span m='1769130'>or</span> <span m='1769200'>whatever</span>
  <span m='1769480'>you're</span> <span m='1769640'>taking.</span> <span m='1771780'>And</span>
  <span m='1772220'>so</span> <span m='1772440'>we</span> <span m='1772550'>now</span>
  <span m='1772760'>have</span> <span m='1773030'>some</span> <span m='1773270'>such</span>
  <span m='1773550'>algorithms</span> <span m='1774200'>that</span> <span m='1774330'>do</span>
  <span m='1774500'>make</span> <span m='1775160'>substantial</span> <span m='1775860'>gains.</span>
  </p><p><span m='1777240'>And,</span> <span m='1778380'>of</span> <span m='1778600'>course,</span>
  <span m='1779820'>if</span> <span m='1780260'>he</span> <span m='1780420'>didn't</span>
  <span m='1780590'>tell</span> <span m='1780720'>you</span> <span m='1780810'>about</span>
  <span m='1781030'>them,</span> <span m='1781120'>I'm not</span> <span m='1781350'>going
  to</span> <span m='1781610'>tell</span> <span m='1781760'>you</span> <span m='1781930'>about
  them.</span> <span m='1783720'>It's</span> <span m='1784360'>a</span> <span m='1784400'>rather</span>
  <span m='1784730'>specialized</span> <span m='1785330'>subject.</span> <span m='1785890'>But</span>
  <span m='1786090'>it's</span> <span m='1786310'>something</span> <span m='1786660'>that's</span>
  <span m='1786840'>really</span> <span m='1787080'>happened</span> <span m='1787490'>the</span>
  <span m='1787680'>last</span> <span m='1787870'>10</span> <span m='1788110'>years.</span>
  <span m='1790650'>And</span> <span m='1790970'>they've</span> <span m='1791490'>constantly</span>
  <span m='1791750'>been</span> <span m='1791930'>improved.</span> <span m='1792500'>The</span>
  <span m='1792570'>first</span> <span m='1792940'>ones,</span> <span m='1793840'>like</span>
  <span m='1794020'>one</span> <span m='1794180'>I</span> <span m='1794300'>came</span>
  <span m='1794570'>up</span> <span m='1794770'>with</span> <span m='1794980'>called</span>
  <span m='1795260'>generalized</span> <span m='1795530'>minimum</span> <span m='1795980'>distance</span>
  <span m='1796410'>decoding,</span> <span m='1798740'>made</span> <span m='1799010'>a</span>
  <span m='1799060'>modest</span> <span m='1799560'>improvement.</span> <span m='1800950'>In</span>
  <span m='1801070'>dB</span> <span m='1801270'>terms,</span> <span m='1801680'>1</span>
  <span m='1801910'>dB,</span> <span m='1803120'>where</span> <span m='1803480'>there's</span>
  <span m='1803830'>3</span> <span m='1804070'>dB</span> <span m='1804470'>to</span>
  <span m='1804600'>be</span> <span m='1804760'>got.</span> <span m='1805810'>Now</span>
  <span m='1806090'>they're</span> <span m='1806310'>up</span> <span m='1806470'>to</span>
  <span m='1806620'>2,</span> <span m='1806950'>2 1/2</span> <span m='1807280'>out</span>
  <span m='1807580'>of</span> <span m='1807760'>the</span> <span m='1807930'>3</span>
  <span m='1808170'>dB</span> <span m='1809410'>with</span> <span m='1809780'>these</span>
  <span m='1810040'>new</span> <span m='1810360'>soft</span> <span m='1810850'>Reed-Solomon</span>
  <span m='1811450'>decoding</span> <span m='1812010'>algorithms.</span> </p><p><span
  m='1814160'>So</span> <span m='1814480'>anyway,</span> <span m='1814820'>if</span>
  <span m='1814950'>you</span> <span m='1815080'>pass</span> <span m='1815470'>some</span>
  <span m='1815610'>reliability</span> <span m='1816330'>information</span> <span
  m='1817000'>here,</span> <span m='1817560'>then</span> <span m='1818070'>you</span>
  <span m='1818210'>can</span> <span m='1818350'>improve</span> <span m='1818770'>the</span>
  <span m='1818890'>performance</span> <span m='1819510'>of</span> <span m='1819620'>this</span>
  <span m='1819870'>decoder.</span> <span m='1820775'>This</span> <span m='1821140'>decoder</span>
  <span m='1821720'>knows</span> <span m='1823600'>which</span> <span m='1823780'>symbols</span>
  <span m='1824390'>are</span> <span m='1825450'>reliable</span> <span m='1826310'>and</span>
  <span m='1827500'>it</span> <span m='1827640'>won't</span> <span m='1827970'>change</span>
  <span m='1828460'>in</span> <span m='1828570'>the</span> <span m='1828680'>decoding</span>
  <span m='1829280'>in</span> <span m='1829390'>which</span> <span m='1829680'>are</span>
  <span m='1830680'>unreliable</span> <span m='1831480'>or</span> <span m='1831610'>completely</span>
  <span m='1832040'>erased.</span> <span m='1832550'>Where</span> <span m='1832710'>there's</span>
  <span m='1832860'>no</span> <span m='1832990'>information</span> <span m='1833560'>about</span>
  <span m='1833920'>them,</span> <span m='1834150'>that actually</span> <span m='1834470'>helps</span>
  <span m='1834810'>you</span> <span m='1835420'>in</span> <span m='1835550'>the</span>
  <span m='1835650'>decoding.</span> <span m='1836940'>If</span> <span m='1837090'>you</span>
  <span m='1837250'>knew</span> <span m='1837520'>that</span> <span m='1838000'>you</span>
  <span m='1838300'>had</span> <span m='1840000'>s</span> <span m='1840280'>erasures</span>
  <span m='1840980'>rather</span> <span m='1841330'>than</span> <span m='1841530'>s</span>
  <span m='1841840'>errors,</span> <span m='1843670'>this</span> <span m='1843840'>helps</span>
  <span m='1844100'>you</span> <span m='1844240'>quite</span> <span m='1844450'>a</span>
  <span m='1844540'>lot.</span> <span m='1845620'>We</span> <span m='1845890'>can</span>
  <span m='1846050'>decode</span> <span m='1846480'>twice</span> <span m='1846800'>as</span>
  <span m='1846940'>many</span> <span m='1847350'>erasures</span> <span m='1847710'>as</span>
  <span m='1847840'>we</span> <span m='1847990'>can</span> <span m='1848300'>decode</span>
  <span m='1848460'>errors.</span> <span m='1849680'>And</span> <span m='1849850'>similarly,</span>
  <span m='1850540'>soft</span> <span m='1850970'>information</span> <span m='1851580'>in</span>
  <span m='1851660'>between</span> <span m='1852940'>can</span> <span m='1853060'>improve</span>
  <span m='1853450'>the</span> <span m='1853550'>capabilities</span> <span m='1854250'>of</span>
  <span m='1854340'>your</span> <span m='1854500'>decoder.</span> </p><p><span m='1856310'>All</span>
  <span m='1856440'>right.</span> <span m='1856730'>So</span> <span m='1860530'>that's</span>
  <span m='1860910'>the</span> <span m='1861010'>set</span> <span m='1861320'>up.</span>
  <span m='1861620'>You</span> <span m='1861790'>can</span> <span m='1861960'>see</span>
  <span m='1862920'>why it</span> <span m='1863020'>makes</span> <span m='1863260'>a</span>
  <span m='1863310'>certain</span> <span m='1863610'>amount</span> <span m='1863870'>of</span>
  <span m='1863940'>sense.</span> <span m='1867190'>From</span> <span m='1867370'>a</span>
  <span m='1867440'>complexity</span> <span m='1868070'>point</span> <span m='1868330'>of</span>
  <span m='1868690'>view,</span> <span m='1868940'>what</span> <span m='1869150'>it</span>
  <span m='1869280'>does --</span> <span m='1870360'>here,</span> <span m='1870560'>we're</span>
  <span m='1870650'>going</span> <span m='1870760'>to</span> <span m='1870830'>do</span>
  <span m='1871270'>maximum</span> <span m='1871680'>likelihood</span> <span m='1872150'>decoding,</span>
  <span m='1872680'>complexity</span> <span m='1873410'>order</span> <span m='1873750'>of</span>
  <span m='1873980'>2</span> <span m='1874170'>to</span> <span m='1874260'>the</span>
  <span m='1874410'>k.</span> <span m='1874760'>But</span> <span m='1875110'>we're</span>
  <span m='1875300'>not</span> <span m='1875460'>going</span> <span m='1875570'>to</span>
  <span m='1875810'>let</span> <span m='1876030'>k</span> <span m='1876240'>get</span>
  <span m='1876440'>very</span> <span m='1876710'>large,</span> <span m='1877650'>so</span>
  <span m='1877860'>this</span> <span m='1878050'>is</span> <span m='1878190'>feasible.</span>
  <span m='1878690'>Then</span> <span m='1878800'>we're</span> <span m='1878940'>going</span>
  <span m='1879060'>to</span> <span m='1879270'>let</span> <span m='1879560'>the</span>
  <span m='1879670'>code</span> <span m='1880010'>get</span> <span m='1880210'>very</span>
  <span m='1880430'>long,</span> <span m='1880890'>as</span> <span m='1881040'>we</span>
  <span m='1881160'>know</span> <span m='1881330'>we</span> <span m='1881440'>have</span>
  <span m='1881620'>to</span> <span m='1881790'>do</span> <span m='1882230'>from</span>
  <span m='1882670'>Shannon's</span> <span m='1882870'>Theorem,</span> <span m='1883480'>using</span>
  <span m='1884800'>this</span> <span m='1885010'>outer</span> <span m='1885340'>code.</span>
  <span m='1886020'>But</span> <span m='1887620'>now</span> <span m='1887870'>we</span>
  <span m='1888000'>know</span> <span m='1888210'>we</span> <span m='1888350'>have</span>
  <span m='1888510'>polynomial</span> <span m='1889180'>complexity</span> <span m='1889840'>Reed-Solomon</span>
  <span m='1890530'>decoding</span> <span m='1891010'>algorithms,</span> <span m='1892430'>even</span>
  <span m='1892780'>for</span> <span m='1892900'>the</span> <span m='1893020'>soft</span>
  <span m='1893340'>decision</span> <span m='1893810'>case.</span> </p><p><span m='1894600'>So</span>
  <span m='1896740'>if</span> <span m='1896880'>we</span> <span m='1897040'>balance</span>
  <span m='1897600'>the</span> <span m='1897720'>complexity</span> <span m='1898460'>here,</span>
  <span m='1899420'>basically</span> <span m='1900300'>let</span> <span m='1902330'>this</span>
  <span m='1902610'>length</span> <span m='1902970'>be</span> <span m='1903200'>exponential</span>
  <span m='1903910'>and</span> <span m='1904010'>this</span> <span m='1904260'>length,</span>
  <span m='1905160'>as</span> <span m='1905370'>it</span> <span m='1905470'>is --</span>
  <span m='1905820'>it's</span> <span m='1906140'>of the</span> <span m='1906280'>order</span>
  <span m='1906630'>of</span> <span m='1907910'>2</span> <span m='1908290'>to</span>
  <span m='1908530'>the</span> <span m='1908650'>k</span> <span m='1908970'>itself
  --</span> <span m='1910190'>then</span> <span m='1910600'>we</span> <span m='1910760'>can</span>
  <span m='1910850'>get</span> <span m='1911050'>polynomial</span> <span m='1911640'>complexity</span>
  <span m='1912300'>overall,</span> <span m='1913415'>all</span> <span m='1913900'>right?</span>
  <span m='1915100'>The</span> <span m='1915240'>overall</span> <span m='1915640'>complexity</span>
  <span m='1916330'>is</span> <span m='1916540'>going</span> <span m='1916670'>to</span>
  <span m='1916800'>be</span> <span m='1916920'>of</span> <span m='1917030'>the</span>
  <span m='1917140'>order</span> <span m='1917790'>of</span> <span m='1917920'>a</span>
  <span m='1917980'>small</span> <span m='1918390'>power</span> <span m='1918820'>of</span>
  <span m='1918930'>2 to</span> <span m='1919180'>the</span> <span m='1919310'>k.</span>
  <span m='1921250'>The</span> <span m='1921450'>overall</span> <span m='1921870'>block</span>
  <span m='1922220'>length</span> <span m='1922520'>is</span> <span m='1922780'>going</span>
  <span m='1922930'>to</span> <span m='1923080'>be</span> <span m='1923220'>of</span>
  <span m='1923330'>the</span> <span m='1923500'>order --</span> <span m='1924140'>is</span>
  <span m='1924330'>going</span> <span m='1924430'>to</span> <span m='1924480'>be</span>
  <span m='1924570'>linear</span> <span m='1925850'>in</span> <span m='1926150'>2
  to</span> <span m='1926370'>the</span> <span m='1926480'>k.</span> <span m='1927430'>And</span>
  <span m='1927920'>therefore,</span> <span m='1928370'>you're</span> <span m='1928500'>going</span>
  <span m='1928610'>to</span> <span m='1928710'>get</span> <span m='1929300'>polynomial</span>
  <span m='1929850'>decoding</span> <span m='1930300'>complexity.</span> </p><p><span
  m='1931620'>The</span> <span m='1931770'>other</span> <span m='1931910'>question</span>
  <span m='1932300'>is</span> <span m='1932430'>performance.</span> <span m='1934510'>And</span>
  <span m='1935670'>you</span> <span m='1935820'>can</span> <span m='1935980'>show</span>
  <span m='1937290'>that</span> <span m='1937750'>if</span> <span m='1937970'>you
  --</span> <span m='1939770'>well,</span> <span m='1940030'>even</span> <span m='1940180'>if</span>
  <span m='1940260'>you</span> <span m='1940360'>don't</span> <span m='1941130'>use</span>
  <span m='1941420'>reliability</span> <span m='1942010'>information,</span> <span
  m='1943570'>you</span> <span m='1943730'>can</span> <span m='1943930'>get</span>
  <span m='1944190'>all</span> <span m='1944480'>the</span> <span m='1944550'>way</span>
  <span m='1945285'>to</span> <span m='1945540'>the</span> <span m='1945730'>capacity</span>
  <span m='1946400'>of</span> <span m='1946470'>this</span> <span m='1946750'>underlying</span>
  <span m='1947360'>channel</span> <span m='1947770'>here</span> <span m='1950070'>with</span>
  <span m='1950360'>exponentially-decreasing</span> <span m='1951620'>error</span>
  <span m='1951860'>rate</span> <span m='1952160'>for</span> <span m='1952320'>any</span>
  <span m='1952500'>rate</span> <span m='1952810'>below</span> <span m='1953050'>that</span>
  <span m='1953300'>capacity.</span> <span m='1955080'>Not</span> <span m='1955530'>as</span>
  <span m='1955790'>good</span> <span m='1956330'>an</span> <span m='1956480'>exponent</span>
  <span m='1957220'>as</span> <span m='1957640'>if</span> <span m='1957750'>you</span>
  <span m='1957920'>just</span> <span m='1958770'>used</span> <span m='1959450'>random</span>
  <span m='1959800'>codes</span> <span m='1960350'>per</span> <span m='1960530'>Shannon</span>
  <span m='1961130'>and</span> <span m='1961440'>coded</span> <span m='1961730'>for</span>
  <span m='1961840'>the</span> <span m='1962020'>channel,</span> <span m='1963800'>but</span>
  <span m='1963910'>nonetheless,</span> <span m='1964440'>you</span> <span m='1964740'>basically</span>
  <span m='1965160'>get</span> <span m='1965340'>what</span> <span m='1965490'>you</span>
  <span m='1965630'>want.</span> <span m='1966030'>So</span> <span m='1967910'>using</span>
  <span m='1969010'>two</span> <span m='1969550'>smaller,</span> <span m='1970040'>simpler</span>
  <span m='1970470'>codes</span> <span m='1970930'>to</span> <span m='1971050'>create</span>
  <span m='1971390'>one</span> <span m='1971630'>long</span> <span m='1971960'>code</span>
  <span m='1973310'>turned</span> <span m='1973580'>out</span> <span m='1973720'>to</span>
  <span m='1973790'>be</span> <span m='1973910'>a</span> <span m='1973950'>good</span>
  <span m='1974200'>idea.</span> </p><p><span m='1975790'>First</span> <span m='1976240'>of</span>
  <span m='1976310'>all,</span> <span m='1976560'>for</span> <span m='1976690'>proving</span>
  <span m='1977120'>this</span> <span m='1977330'>theoretical</span> <span m='1977860'>result,</span>
  <span m='1978430'>you could</span> <span m='1978520'>get</span> <span m='1978710'>exponentially-decreasing</span>
  <span m='1979910'>error</span> <span m='1980100'>rate</span> <span m='1980440'>for</span>
  <span m='1981070'>polynomial</span> <span m='1981740'>increasing</span> <span m='1982250'>decoding</span>
  <span m='1982910'>complexity.</span> <span m='1984190'>And</span> <span m='1984710'>within</span>
  <span m='1985030'>about</span> <span m='1985340'>10</span> <span m='1985540'>years,</span>
  <span m='1986330'>this</span> <span m='1986510'>is</span> <span m='1986630'>what</span>
  <span m='1986830'>people</span> <span m='1987170'>actually</span> <span m='1987570'>did.</span>
  <span m='1990510'>And,</span> <span m='1992270'>in</span> <span m='1992420'>fact,</span>
  <span m='1992950'>what</span> <span m='1993220'>people</span> <span m='1993580'>actually</span>
  <span m='1994040'>did --</span> <span m='1994370'>I've</span> <span m='1994510'>got</span>
  <span m='1994680'>a</span> <span m='1994720'>block</span> <span m='1995090'>code</span>
  <span m='1995410'>here,</span> <span m='1997700'>but</span> <span m='1997890'>what</span>
  <span m='1998090'>people</span> <span m='1998430'>actually</span> <span m='1998830'>did</span>
  <span m='1999390'>was</span> <span m='1999750'>they</span> <span m='1999880'>used</span>
  <span m='2000360'>a</span> <span m='2001010'>short</span> <span m='2001380'>constraint</span>
  <span m='2001880'>length</span> <span m='2002220'>convolutional</span> <span m='2002970'>code</span>
  <span m='2003300'>here,</span> <span m='2004200'>which</span> <span m='2004720'>we'll</span>
  <span m='2004830'>be</span> <span m='2004990'>talking</span> <span m='2005380'>about</span>
  <span m='2006300'>after</span> <span m='2007000'>the</span> <span m='2007090'>break.</span>
  </p><p><span m='2008450'>Convolutional</span> <span m='2009180'>codes</span> <span
  m='2009650'>tend</span> <span m='2009940'>to</span> <span m='2010030'>have</span>
  <span m='2010250'>a</span> <span m='2010320'>better</span> <span m='2010680'>performance</span>
  <span m='2011260'>complexity</span> <span m='2011890'>tradeoff,</span> <span m='2012840'>particularly</span>
  <span m='2013420'>in</span> <span m='2013540'>soft</span> <span m='2013880'>decision</span>
  <span m='2014860'>situations</span> <span m='2015840'>than</span> <span m='2016100'>block</span>
  <span m='2016410'>codes</span> <span m='2016810'>do.</span> <span m='2017060'>So</span>
  <span m='2019490'>in</span> <span m='2019610'>a</span> <span m='2019660'>practical</span>
  <span m='2020100'>system,</span> <span m='2020620'>it's</span> <span m='2020910'>almost</span>
  <span m='2021290'>always</span> <span m='2021560'>better</span> <span m='2021790'>to</span>
  <span m='2021840'>use</span> <span m='2022020'>a</span> <span m='2022270'>convolutional</span>
  <span m='2022680'>code</span> <span m='2022930'>than</span> <span m='2023010'>a</span>
  <span m='2023080'>block</span> <span m='2023450'>code.</span> <span m='2024110'>We'll</span>
  <span m='2024290'>discuss</span> <span m='2024750'>the</span> <span m='2025030'>reasons</span>
  <span m='2025310'>why.</span> </p><p><span m='2026710'>So</span> <span m='2026910'>this</span>
  <span m='2027220'>convolutional</span> <span m='2027960'>code</span> <span m='2028260'>here,</span>
  <span m='2028560'>there</span> <span m='2028780'>is</span> <span m='2028940'>a</span>
  <span m='2029640'>maximum</span> <span m='2030270'>likelihood</span> <span m='2030830'>sequence</span>
  <span m='2031460'>detector</span> <span m='2032060'>for</span> <span m='2032230'>the</span>
  <span m='2032350'>convolutional</span> <span m='2033230'>code</span> <span m='2033550'>down
  here,</span> <span m='2033850'>which</span> <span m='2034130'>is</span> <span m='2034350'>the</span>
  <span m='2034560'>Viterbi</span> <span m='2034940'>algorithm,</span> <span m='2035410'>which</span>
  <span m='2035710'>you've</span> <span m='2036250'>probably</span> <span m='2036560'>all</span>
  <span m='2036770'>heard</span> <span m='2036950'>about.</span> <span m='2038550'>And</span>
  <span m='2038760'>this</span> <span m='2038900'>is</span> <span m='2039040'>very</span>
  <span m='2039320'>practical</span> <span m='2039910'>as</span> <span m='2040050'>long</span>
  <span m='2040340'>as</span> <span m='2040530'>the</span> <span m='2040770'>constraint</span>
  <span m='2041350'>length,</span> <span m='2042390'>k,</span> <span m='2042620'>now</span>
  <span m='2043180'>becomes</span> <span m='2043940'>the</span> <span m='2044040'>constraint</span>
  <span m='2044510'>length,</span> <span m='2044780'>nu,</span> <span m='2045230'>of
  the</span> <span m='2045360'>code</span> <span m='2045710'>doesn't</span> <span
  m='2045990'>get</span> <span m='2046210'>too</span> <span m='2046360'>large.</span>
  <span m='2047600'>So</span> <span m='2048190'>for</span> <span m='2048370'>about</span>
  <span m='2049820'>20</span> <span m='2050159'>years,</span> <span m='2051550'>the</span>
  <span m='2051719'>standard</span> <span m='2052239'>for</span> <span m='2052389'>space</span>
  <span m='2052820'>communication</span> <span m='2053570'>was</span> <span m='2053889'>this</span>
  <span m='2054139'>was</span> <span m='2054400'>a</span> <span m='2055750'>(255,
  223, 33)</span> <span m='2059530'>Reed-Solomon</span> <span m='2060330'>code</span>
  <span m='2061400'>over</span> <span m='2063110'>F-256.</span> <span m='2067270'>This</span>
  <span m='2067889'>is</span> <span m='2068480'>a</span> <span m='2069040'>constraint</span>
  <span m='2069679'>length</span> <span m='2070480'>6,</span> <span m='2071989'>rate</span>
  <span m='2072310'>1/2</span> <span m='2074989'>convolutional</span> <span m='2075429'>code.</span>
  <span m='2079100'>This</span> <span m='2079389'>is</span> <span m='2079659'>a</span>
  <span m='2079870'>64-state</span> <span m='2082900'>Viterbi</span> <span m='2083460'>algorithm.</span>
  </p><p><span m='2085270'>So</span> <span m='2086560'>what's</span> <span m='2086870'>the
  --</span> <span m='2088380'>again,</span> <span m='2088500'>if we</span> <span m='2088790'>have</span>
  <span m='2089050'>a</span> <span m='2089260'>look</span> <span m='2089530'>at</span>
  <span m='2089639'>the</span> <span m='2089820'>error</span> <span m='2090190'>channel,</span>
  <span m='2091679'>here</span> <span m='2091969'>is</span> <span m='2092159'>a</span>
  <span m='2092320'>stream</span> <span m='2092810'>of</span> <span m='2092980'>bits</span>
  <span m='2093290'>coming</span> <span m='2093570'>along.</span> <span m='2094790'>After</span>
  <span m='2095300'>encoding</span> <span m='2095840'>and</span> <span m='2095960'>decoding,</span>
  <span m='2096299'>what</span> <span m='2096639'>we</span> <span m='2096830'>typically</span>
  <span m='2097360'>see</span> <span m='2098690'>is</span> <span m='2098960'>bursts</span>
  <span m='2099363'>of errors,</span> <span m='2101830'>all</span> <span m='2101910'>right?</span>
  <span m='2102260'>So</span> <span m='2102450'>you</span> <span m='2102550'>get</span>
  <span m='2102920'>a</span> <span m='2103380'>burst</span> <span m='2103850'>that</span>
  <span m='2103990'>starts --</span> <span m='2104640'>in</span> <span m='2104750'>convolutional</span>
  <span m='2105030'>codes,</span> <span m='2105750'>it</span> <span m='2106090'>can
  start at</span> <span m='2106470'>a random</span> <span m='2106890'>time,</span>
  <span m='2107720'>end at</span> <span m='2108040'>a</span> <span m='2108080'>random</span>
  <span m='2108530'>time.</span> <span m='2109355'>You</span> <span m='2109720'>might</span>
  <span m='2110010'>get</span> <span m='2110160'>another</span> <span m='2111140'>discrete</span>
  <span m='2111720'>error</span> <span m='2112110'>event</span> <span m='2113590'>over</span>
  <span m='2113870'>here.</span> <span m='2114730'>In</span> <span m='2115040'>other</span>
  <span m='2115120'>words,</span> <span m='2115470'>most</span> <span m='2115710'>of</span>
  <span m='2115940'>the</span> <span m='2116050'>time,</span> <span m='2116410'>the</span>
  <span m='2116520'>decoder</span> <span m='2117120'>is</span> <span m='2117600'>decoding</span>
  <span m='2118070'>properly.</span> <span m='2119430'>What</span> <span m='2119730'>you're</span>
  <span m='2120000'>receiving</span> <span m='2120600'>is</span> <span m='2120740'>what</span>
  <span m='2120920'>you</span> <span m='2121030'>transmitted</span> <span m='2121790'>in</span>
  <span m='2122170'>a</span> <span m='2122220'>streamwise</span> <span m='2123110'>fashion.</span>
  <span m='2124150'>The</span> <span m='2124550'>bits</span> <span m='2124860'>just</span>
  <span m='2125140'>are</span> <span m='2125280'>transmitted</span> <span m='2125880'>forever.</span>
  <span m='2127510'>But</span> <span m='2127610'>every</span> <span m='2127790'>so</span>
  <span m='2128000'>often,</span> <span m='2128450'>the</span> <span m='2128920'>decoder</span>
  <span m='2129330'>gets</span> <span m='2129570'>off</span> <span m='2129770'>on</span>
  <span m='2129850'>the</span> <span m='2129920'>wrong</span> <span m='2130250'>track,</span>
  <span m='2131360'>puts</span> <span m='2131610'>out</span> <span m='2131760'>errors</span>
  <span m='2132120'>for</span> <span m='2132240'>a while,</span> <span m='2132680'>then</span>
  <span m='2132840'>gets</span> <span m='2133000'>resynchronized,</span> <span m='2136310'>and</span>
  <span m='2136590'>decodes</span> <span m='2137010'>correctly</span> <span m='2137430'>again.</span>
  <span m='2137680'>Is</span> <span m='2137800'>my</span> <span m='2137940'>picture</span>
  <span m='2138440'>clear?</span> <span m='2140140'>I'm</span> <span m='2140540'>using</span>
  <span m='2140860'>words,</span> <span m='2141250'>mainly,</span> <span m='2141560'>to</span>
  <span m='2141680'>tell</span> <span m='2141840'>you</span> <span m='2141980'>what</span>
  <span m='2142120'>it</span> <span m='2142200'>represents.</span> <span m='2144970'>OK.</span>
  </p><p><span m='2147290'>So</span> <span m='2147500'>now,</span> <span m='2147760'>basically,</span>
  <span m='2148380'>what</span> <span m='2148570'>you</span> <span m='2148730'>want</span>
  <span m='2148950'>to</span> <span m='2149000'>do</span> <span m='2149450'>is,</span>
  <span m='2151480'>just</span> <span m='2151770'>as</span> <span m='2151900'>we</span>
  <span m='2152010'>did</span> <span m='2152230'>in</span> <span m='2152310'>the</span>
  <span m='2152400'>packet</span> <span m='2152850'>communication</span> <span m='2153640'>case,</span>
  <span m='2155400'>you</span> <span m='2155530'>want</span> <span m='2155650'>to</span>
  <span m='2155760'>send</span> <span m='2156940'>multiple</span> <span m='2157460'>parallel</span>
  <span m='2157980'>streams,</span> <span m='2159700'>up</span> <span m='2159870'>to</span>
  <span m='2160040'>256</span> <span m='2161250'>of</span> <span m='2161330'>them,</span>
  <span m='2163620'>such</span> <span m='2164070'>that</span> <span m='2165540'>in</span>
  <span m='2165940'>this</span> <span m='2166080'>stream,</span> <span m='2166580'>you're</span>
  <span m='2166700'>going</span> <span m='2166780'>to</span> <span m='2166850'>get</span>
  <span m='2167090'>independent</span> <span m='2168890'>error</span> <span m='2169180'>blocks.</span>
  <span m='2169870'>And</span> <span m='2170010'>this</span> <span m='2170240'>one,</span>
  <span m='2170480'>you're</span> <span m='2170650'>going</span> <span m='2170780'>to</span>
  <span m='2170840'>get</span> <span m='2172130'>errors</span> <span m='2172710'>occurring</span>
  <span m='2173160'>somewhere</span> <span m='2173620'>else.</span> <span m='2173900'>They're</span>
  <span m='2174020'>going</span> <span m='2174120'>to</span> <span m='2174200'>have</span>
  <span m='2174280'>a</span> <span m='2174370'>typical</span> <span m='2174890'>length.</span>
  <span m='2176550'>You</span> <span m='2176760'>can</span> <span m='2177970'>very</span>
  <span m='2178160'>well</span> <span m='2178410'>estimate</span> <span m='2180060'>what</span>
  <span m='2180290'>the</span> <span m='2180380'>typical</span> <span m='2180850'>length</span>
  <span m='2181180'>of</span> <span m='2181290'>error</span> <span m='2181600'>events</span>
  <span m='2181650'>is,</span> <span m='2182440'>but</span> <span m='2182680'>they</span>
  <span m='2182830'>occur</span> <span m='2183160'>randomly.</span> <span m='2184390'>And</span>
  <span m='2184510'>now</span> <span m='2184750'>you use</span> <span m='2185190'>the</span>
  <span m='2185280'>Reed-Solomon</span> <span m='2186020'>code,</span> <span m='2186570'>coding</span>
  <span m='2187010'>across</span> <span m='2187510'>this,</span> <span m='2190510'>and</span>
  <span m='2192270'>that</span> <span m='2192470'>will</span> <span m='2194480'>basically</span>
  <span m='2194880'>give</span> <span m='2195060'>you</span> <span m='2195200'>this</span>
  <span m='2195430'>picture</span> <span m='2195830'>over</span> <span m='2196040'>here.</span>
  </p><p><span m='2199100'>How</span> <span m='2199540'>would</span> <span m='2199910'>I</span>
  <span m='2199990'>get</span> <span m='2200330'>this?</span> <span m='2202670'>One</span>
  <span m='2203000'>way</span> <span m='2203360'>is</span> <span m='2203810'>by</span>
  <span m='2204000'>using</span> <span m='2204500'>a</span> <span m='2204630'>block</span>
  <span m='2205120'>interleaver,</span> <span m='2214020'>which</span> <span m='2214390'>is</span>
  <span m='2214570'>described</span> <span m='2215100'>in</span> <span m='2215200'>the</span>
  <span m='2215300'>notes.</span> <span m='2216285'>A</span> <span m='2216540'>block</span>
  <span m='2216795'>interleaver,</span> <span m='2217460'>you</span> <span m='2217610'>basically</span>
  <span m='2218210'>take</span> <span m='2219140'>a</span> <span m='2219250'>long</span>
  <span m='2219760'>block</span> <span m='2221040'>from</span> <span m='2221200'>the</span>
  <span m='2221300'>convolutional</span> <span m='2221980'>code</span> <span m='2222380'>and</span>
  <span m='2223140'>you</span> <span m='2223270'>just</span> <span m='2224110'>encode</span>
  <span m='2224690'>and</span> <span m='2225470'>transmit</span> <span m='2225960'>along</span>
  <span m='2226300'>here</span> <span m='2226600'>and</span> <span m='2226660'>ultimately</span>
  <span m='2227060'>decode.</span> <span m='2228350'>And</span> <span m='2228470'>after</span>
  <span m='2228920'>a</span> <span m='2228970'>very</span> <span m='2229210'>long</span>
  <span m='2229530'>time,</span> <span m='2229860'>you</span> <span m='2229970'>come</span>
  <span m='2230170'>back</span> <span m='2230530'>and</span> <span m='2230640'>start</span>
  <span m='2231350'>transmitting</span> <span m='2231950'>the</span> <span m='2232050'>second</span>
  <span m='2232420'>row</span> <span m='2232720'>just</span> <span m='2233010'>as</span>
  <span m='2233110'>part</span> <span m='2233350'>of</span> <span m='2233420'>the</span>
  <span m='2233490'>same</span> <span m='2233840'>stream.</span> <span m='2235140'>And</span>
  <span m='2235470'>then</span> <span m='2235780'>the</span> <span m='2236190'>third</span>
  <span m='2236490'>row</span> <span m='2238070'>and</span> <span m='2238290'>so</span>
  <span m='2238520'>forth.</span> <span m='2239760'>And</span> <span m='2240100'>if</span>
  <span m='2241310'>the</span> <span m='2241530'>block</span> <span m='2242000'>length</span>
  <span m='2242500'>n,</span> <span m='2244180'>here,</span> <span m='2244480'>is</span>
  <span m='2244650'>long</span> <span m='2245020'>enough,</span> <span m='2246260'>the</span>
  <span m='2246630'>errors</span> <span m='2246790'>in</span> <span m='2246880'>different</span>
  <span m='2247170'>rows</span> <span m='2247570'>will</span> <span m='2247730'>be</span>
  <span m='2247910'>effectively</span> <span m='2248490'>independent,</span> <span
  m='2250078'>all right?</span> </p><p><span m='2251560'>So</span> <span m='2251900'>again,</span>
  <span m='2252220'>you</span> <span m='2252380'>wind</span> <span m='2252680'>up</span>
  <span m='2252910'>with</span> <span m='2253530'>very</span> <span m='2253740'>long</span>
  <span m='2253980'>blocks</span> <span m='2254470'>in</span> <span m='2254580'>this</span>
  <span m='2254850'>scheme,</span> <span m='2257040'>but</span> <span m='2257610'>analytically,</span>
  <span m='2257940'>it</span> <span m='2258270'>works.</span> <span m='2259365'>And</span>
  <span m='2259760'>in</span> <span m='2259960'>practice,</span> <span m='2260510'>this</span>
  <span m='2260760'>is</span> <span m='2262480'>roughly</span> <span m='2262950'>what's</span>
  <span m='2263310'>done,</span> <span m='2263650'>except</span> <span m='2265106'>there
  is</span> <span m='2265550'>such</span> <span m='2265850'>a</span> <span m='2265920'>thing</span>
  <span m='2266190'>as</span> <span m='2266360'>a</span> <span m='2266710'>convolutional</span>
  <span m='2267540'>interleaver,</span> <span m='2267740'>which</span> <span m='2269140'>again,</span>
  <span m='2270420'>operates</span> <span m='2270930'>streamwise</span> <span m='2271820'>and</span>
  <span m='2272430'>actually</span> <span m='2272790'>performs</span> <span m='2273290'>better</span>
  <span m='2273560'>in</span> <span m='2273630'>practice.</span> <span m='2275571'>But</span>
  <span m='2276000'>I won't</span> <span m='2276520'>take</span> <span m='2276720'>the</span>
  <span m='2276810'>time</span> <span m='2277060'>to</span> <span m='2277110'>go</span>
  <span m='2277310'>into</span> <span m='2277430'>this</span> <span m='2277730'>because</span>
  <span m='2277870'>we're</span> <span m='2278050'>not</span> <span m='2278300'>going</span>
  <span m='2278420'>to</span> <span m='2278480'>really</span> <span m='2278905'>be
  getting</span> <span m='2279330'>into</span> <span m='2279760'>things</span> <span
  m='2280040'>like</span> <span m='2280250'>interleavers.</span> <span m='2281470'>Do</span>
  <span m='2281670'>you</span> <span m='2281730'>see</span> <span m='2281890'>how</span>
  <span m='2282000'>this</span> <span m='2282170'>works?</span> <span m='2283780'>OK.</span>
  <span m='2285060'>So</span> <span m='2286632'>it</span> <span m='2287100'>works</span>
  <span m='2287360'>well</span> <span m='2287630'>theoretically.</span> <span m='2288300'>It</span>
  <span m='2288390'>gives</span> <span m='2288600'>us the</span> <span m='2288830'>theoretical</span>
  <span m='2289410'>result</span> <span m='2289780'>we</span> <span m='2289920'>want.</span>
  <span m='2290380'>Works</span> <span m='2290680'>well</span> <span m='2291780'>in</span>
  <span m='2291960'>practice.</span> </p><p><span m='2295570'>As I</span> <span m='2295680'>say,</span>
  <span m='2295900'>this</span> <span m='2296120'>was</span> <span m='2296290'>the</span>
  <span m='2296380'>standard</span> <span m='2296890'>for</span> <span m='2297040'>space</span>
  <span m='2297420'>communications</span> <span m='2299330'>during</span> <span m='2299570'>the</span>
  <span m='2299660'>'70s</span> <span m='2300420'>and</span> <span m='2300715'>the</span>
  <span m='2301010'>'80s.</span> <span m='2303710'>Around</span> <span m='2303960'>the</span>
  <span m='2304080'>end</span> <span m='2304250'>of</span> <span m='2304290'>the</span>
  <span m='2304450'>'80s,</span> <span m='2304880'>they</span> <span m='2305100'>upgraded</span>
  <span m='2305690'>this.</span> <span m='2307600'>First</span> <span m='2308000'>of</span>
  <span m='2308070'>all,</span> <span m='2308320'>they</span> <span m='2308430'>replaced</span>
  <span m='2309000'>this</span> <span m='2309360'>by</span> <span m='2309740'>a</span>
  <span m='2311140'>nu</span> <span m='2311540'>equals</span> <span m='2313380'>14,</span>
  <span m='2315350'>rate</span> <span m='2315860'>1/6,</span> <span m='2317120'>lower</span>
  <span m='2317490'>rate</span> <span m='2317810'>convolutional</span> <span m='2318490'>code,</span>
  <span m='2319350'>so</span> <span m='2319630'>this</span> <span m='2319920'>now</span>
  <span m='2320110'>becomes</span> <span m='2320730'>a</span> <span m='2321560'>2</span>
  <span m='2321780'>to</span> <span m='2321870'>the</span> <span m='2321990'>1fourth</span>
  <span m='2322690'>state</span> <span m='2324500'>Viterbi</span> <span m='2325040'>decoder.</span>
  <span m='2326075'>They</span> <span m='2326490'>built</span> <span m='2326770'>this</span>
  <span m='2326960'>huge</span> <span m='2327300'>rack at</span> <span m='2327810'>JPL</span>
  <span m='2328650'>that had</span> <span m='2330580'>8,192</span> <span m='2332340'>parallel</span>
  <span m='2333110'>decoding</span> <span m='2333640'>units,</span> <span m='2334080'>add-compare-select</span>
  <span m='2335220'>units</span> <span m='2335660'>in</span> <span m='2335770'>the</span>
  <span m='2335880'>Viterbi</span> <span m='2336290'>algorithm,</span> <span m='2337270'>to</span>
  <span m='2337620'>decode</span> <span m='2338090'>this</span> <span m='2338320'>thing.</span>
  <span m='2338560'>But,</span> <span m='2338690'>of</span> <span m='2338770'>course,</span>
  <span m='2339150'>they</span> <span m='2339280'>only</span> <span m='2339460'>need</span>
  <span m='2339740'>to</span> <span m='2339840'>do</span> <span m='2340000'>that</span>
  <span m='2340220'>in</span> <span m='2340320'>one</span> <span m='2340570'>place,</span>
  <span m='2341030'>in</span> <span m='2341150'>the</span> <span m='2341240'>space</span>
  <span m='2341580'>program.</span> <span m='2342130'>Everything</span> <span m='2342470'>comes</span>
  <span m='2342770'>back</span> <span m='2343080'>to</span> <span m='2343190'>JPL.</span>
  <span m='2344560'>So</span> <span m='2344860'>they</span> <span m='2345450'>built</span>
  <span m='2345660'>this</span> <span m='2345910'>BVD,</span> <span m='2346590'>Big</span>
  <span m='2346950'>Viterbi</span> <span m='2347300'>decoder.</span> <span m='2350210'>And</span>
  <span m='2352740'>first,</span> <span m='2353230'>they used</span> <span m='2353510'>it</span>
  <span m='2353580'>with</span> <span m='2353700'>this</span> <span m='2353950'>code</span>
  <span m='2354360'>and</span> <span m='2354460'>then</span> <span m='2354590'>they</span>
  <span m='2354730'>souped</span> <span m='2355130'>up</span> <span m='2355270'>the</span>
  <span m='2355600'>Reed-Solomon</span> <span m='2356130'>code.</span> <span m='2357110'>And</span>
  <span m='2358340'>by</span> <span m='2359040'>about</span> <span m='2359500'>1990,</span>
  <span m='2359930'>1991,</span> <span m='2361850'>they</span> <span m='2362010'>got</span>
  <span m='2362260'>this</span> <span m='2362480'>thing</span> <span m='2362780'>operating</span>
  <span m='2363490'>up</span> <span m='2363810'>within</span> <span m='2364090'>about</span>
  <span m='2364440'>2</span> <span m='2364610'>dB</span> <span m='2365500'>of</span>
  <span m='2365620'>the</span> <span m='2365740'>Shannon</span> <span m='2366180'>limit,</span>
  <span m='2367170'>OK?</span> <span m='2367980'>Which</span> <span m='2368240'>was</span>
  <span m='2368470'>considered</span> <span m='2369100'>a</span> <span m='2369410'>heroic</span>
  <span m='2369830'>feat</span> <span m='2370250'>at</span> <span m='2370460'>the</span>
  <span m='2370580'>time,</span> <span m='2371420'>or</span> <span m='2371560'>even</span>
  <span m='2371890'>now.</span> </p><p><span m='2372200'>So</span> <span m='2372810'>that</span>
  <span m='2373010'>kind</span> <span m='2373180'>of</span> <span m='2373260'>tells</span>
  <span m='2373580'>you,</span> <span m='2373820'>in</span> <span m='2374940'>the</span>
  <span m='2375050'>terms</span> <span m='2375400'>we've</span> <span m='2375570'>been</span>
  <span m='2375700'>using</span> <span m='2376010'>in</span> <span m='2376090'>this</span>
  <span m='2376300'>course,</span> <span m='2377970'>just</span> <span m='2378290'>what</span>
  <span m='2378480'>you</span> <span m='2378600'>can</span> <span m='2378790'>get</span>
  <span m='2379110'>out</span> <span m='2379320'>of</span> <span m='2379400'>this</span>
  <span m='2379620'>kind</span> <span m='2379840'>of</span> <span m='2379950'>approach.</span>
  <span m='2384310'>At</span> <span m='2384400'>that</span> <span m='2384650'>point,</span>
  <span m='2385040'>that</span> <span m='2385210'>was</span> <span m='2385390'>considered</span>
  <span m='2387670'>coding</span> <span m='2387980'>is</span> <span m='2388160'>dead.</span>
  <span m='2388520'>There's</span> <span m='2388710'>really</span> <span m='2388950'>nothing</span>
  <span m='2389250'>more</span> <span m='2389440'>to</span> <span m='2389530'>do.</span>
  <span m='2389770'>We're</span> <span m='2390140'>within</span> <span m='2390410'>about</span>
  <span m='2391250'>2</span> <span m='2391410'>dB</span> <span m='2391710'>of</span>
  <span m='2391860'>the</span> <span m='2392000'>Shannon</span> <span m='2392430'>limit</span>
  <span m='2392530'>and</span> <span m='2392770'>it's</span> <span m='2393000'>inconceivable</span>
  <span m='2393820'>that</span> <span m='2393920'>we</span> <span m='2394080'>could</span>
  <span m='2394230'>actually</span> <span m='2394560'>get</span> <span m='2394820'>any</span>
  <span m='2394910'>closer</span> <span m='2395320'>than that.</span> <span m='2396850'>Second</span>
  <span m='2397190'>half</span> <span m='2397470'>of the</span> <span m='2397590'>course</span>
  <span m='2398000'>will,</span> <span m='2398210'>of course,</span> <span m='2399120'>tell</span>
  <span m='2399310'>us</span> <span m='2399490'>how</span> <span m='2399600'>we can</span>
  <span m='2399730'>get</span> <span m='2399990'>within</span> <span m='2400470'>0.0045</span>
  <span m='2401650'>dB</span> <span m='2402000'>of</span> <span m='2402080'>the</span>
  <span m='2402200'>Shannon</span> <span m='2402610'>limit.</span> <span m='2403290'>But</span>
  <span m='2404450'>that</span> <span m='2404720'>was</span> <span m='2404860'>the</span>
  <span m='2404950'>state</span> <span m='2405260'>of</span> <span m='2405300'>the</span>
  <span m='2405450'>art</span> <span m='2405690'>as of</span> <span m='2405950'>about</span>
  <span m='2406250'>1990,</span> <span m='2407060'>15</span> <span m='2407520'>years</span>
  <span m='2407810'>ago.</span> <span m='2411460'>Questions?</span> <span m='2412310'>Comments?</span>
  <span m='2414670'>OK.</span> </p><p><span m='2418850'>All</span> <span m='2419020'>right.</span>
  <span m='2419220'>I'll</span> <span m='2419350'>just</span> <span m='2419560'>mention</span>
  <span m='2420300'>a</span> <span m='2420400'>third</span> <span m='2422310'>application</span>
  <span m='2423400'>is</span> <span m='2424530'>burst</span> <span m='2424990'>error</span>
  <span m='2425260'>correction,</span> <span m='2427970'>which</span> <span m='2428270'>really,</span>
  <span m='2428510'>we've</span> <span m='2428750'>already</span> <span m='2428990'>been</span>
  <span m='2429170'>talking</span> <span m='2429610'>about.</span> <span m='2435480'>Suppose
  --</span> <span m='2437970'>let's</span> <span m='2438390'>let</span> <span m='2438570'>this</span>
  <span m='2438800'>be</span> <span m='2438980'>a</span> <span m='2439060'>naked</span>
  <span m='2439480'>channel</span> <span m='2439910'>now.</span> <span m='2440270'>Suppose</span>
  <span m='2440650'>you're</span> <span m='2441370'>transmitting</span> <span m='2442000'>with</span>
  <span m='2442420'>an</span> <span m='2442870'>interleave</span> <span m='2443110'>scheme
  like</span> <span m='2443390'>this.</span> <span m='2444210'>And</span> <span m='2444380'>now,</span>
  <span m='2444630'>in</span> <span m='2444710'>the</span> <span m='2444800'>same</span>
  <span m='2445160'>way --</span> <span m='2446880'>it's</span> <span m='2447200'>a</span>
  <span m='2447270'>radio</span> <span m='2447680'>channel</span> <span m='2448090'>or</span>
  <span m='2448160'>something</span> <span m='2448590'>and every</span> <span m='2448830'>so</span>
  <span m='2449000'>often,</span> <span m='2449250'>you have</span> <span m='2449410'>an</span>
  <span m='2449530'>outage</span> <span m='2451240'>just</span> <span m='2451560'>due</span>
  <span m='2451710'>to</span> <span m='2451860'>fading,</span> <span m='2452590'>or
  a</span> <span m='2453040'>thunderstorm,</span> <span m='2453800'>or</span> <span
  m='2453960'>somebody</span> <span m='2454300'>turns</span> <span m='2454610'>on</span>
  <span m='2454750'>his</span> <span m='2454840'>vacuum</span> <span m='2455250'>cleaner,</span>
  <span m='2455980'>or</span> <span m='2456440'>whatever.</span> <span m='2458010'>Every</span>
  <span m='2458210'>so</span> <span m='2458420'>often,</span> <span m='2459210'>as</span>
  <span m='2459390'>you</span> <span m='2459510'>transmit,</span> <span m='2460060'>you're</span>
  <span m='2460200'>going</span> <span m='2460270'>to</span> <span m='2460330'>get</span>
  <span m='2460570'>bursts.</span> <span m='2461000'>You</span> <span m='2461080'>don't</span>
  <span m='2461280'>have</span> <span m='2461520'>independent,</span> <span m='2462330'>identically-distributed</span>
  <span m='2463580'>errors.</span> <span m='2464350'>The</span> <span m='2464550'>character</span>
  <span m='2464810'>of</span> <span m='2465070'>the</span> <span m='2465190'>channel</span>
  <span m='2465590'>is</span> <span m='2465680'>such</span> <span m='2466010'>that</span>
  <span m='2466230'>you</span> <span m='2466350'>see</span> <span m='2466580'>bursts</span>
  <span m='2466990'>of</span> <span m='2467090'>errors,</span> <span m='2468110'>which</span>
  <span m='2468340'>is</span> <span m='2468650'>precisely</span> <span m='2469170'>what</span>
  <span m='2469300'>you</span> <span m='2469420'>do</span> <span m='2469630'>in</span>
  <span m='2469700'>this</span> <span m='2469800'>super</span> <span m='2470210'>channel</span>
  <span m='2470590'>here.</span> <span m='2471670'>Every</span> <span m='2471850'>so</span>
  <span m='2472050'>often,</span> <span m='2472380'>you</span> <span m='2472510'>see</span>
  <span m='2474500'>a</span> <span m='2474930'>bunch</span> <span m='2475190'>of</span>
  <span m='2475270'>errors</span> <span m='2475700'>if</span> <span m='2475850'>you</span>
  <span m='2476120'>have</span> <span m='2476380'>the</span> <span m='2476690'>original</span>
  <span m='2477610'>transmitted</span> <span m='2478160'>scheme</span> <span m='2478530'>to</span>
  <span m='2478670'>compare it to.</span> </p><p><span m='2480470'>All</span> <span
  m='2480600'>right.</span> <span m='2481120'>In</span> <span m='2481260'>exactly</span>
  <span m='2481810'>the</span> <span m='2481890'>same</span> <span m='2482220'>way,</span>
  <span m='2482560'>you</span> <span m='2482730'>can</span> <span m='2483340'>code
  --</span> <span m='2484290'>with</span> <span m='2484660'>something</span> <span
  m='2485030'>like</span> <span m='2485220'>this</span> <span m='2485420'>block</span>
  <span m='2485770'>interleaver,</span> <span m='2486270'>you</span> <span m='2486420'>can</span>
  <span m='2486740'>code</span> <span m='2487470'>across</span> <span m='2488050'>channels</span>
  <span m='2488960'>and</span> <span m='2489140'>correct</span> <span m='2489590'>the</span>
  <span m='2489680'>bursts</span> <span m='2491760'>with</span> <span m='2491950'>Reed-Solomon</span>
  <span m='2492630'>codes.</span> <span m='2493850'>And</span> <span m='2494170'>here,</span>
  <span m='2494530'>it's</span> <span m='2494860'>quite</span> <span m='2495100'>easy</span>
  <span m='2495440'>to</span> <span m='2495520'>show</span> <span m='2495960'>that,</span>
  <span m='2496120'>because</span> <span m='2497100'>Reed-Solomon</span> <span m='2497660'>codes</span>
  <span m='2498030'>have</span> <span m='2498170'>optimal</span> <span m='2498560'>parameters</span>
  <span m='2499400'>n,</span> <span m='2499640'>k,</span> <span m='2499910'>d,</span>
  <span m='2500630'>that</span> <span m='2500780'>Reed-Solomon</span> <span m='2501420'>codes</span>
  <span m='2502330'>do</span> <span m='2502710'>the</span> <span m='2502820'>best</span>
  <span m='2503220'>possible</span> <span m='2503680'>job</span> <span m='2504030'>of</span>
  <span m='2504140'>correcting</span> <span m='2505260'>burst</span> <span m='2505580'>errors</span>
  <span m='2506510'>that</span> <span m='2506660'>you</span> <span m='2506810'>possibly</span>
  <span m='2507360'>could</span> <span m='2507560'>do,</span> <span m='2507830'>given</span>
  <span m='2508180'>some</span> <span m='2508940'>specification</span> <span m='2509810'>for</span>
  <span m='2510000'>how</span> <span m='2510160'>long</span> <span m='2510800'>the</span>
  <span m='2511070'>bursts</span> <span m='2511940'>could</span> <span m='2512090'>possibly</span>
  <span m='2512580'>be</span> <span m='2514090'>and</span> <span m='2516820'>the</span>
  <span m='2517010'>minimum</span> <span m='2517540'>guard</span> <span m='2517940'>space</span>
  <span m='2518500'>between</span> <span m='2518920'>bursts.</span> <span m='2520820'>This
  is</span> <span m='2521290'>classical</span> <span m='2521820'>stuff.</span> <span
  m='2523410'>Reed-Solomon</span> <span m='2524090'>codes</span> <span m='2524500'>are</span>
  <span m='2524620'>optimum</span> <span m='2525590'>burst</span> <span m='2525890'>correctors</span>
  <span m='2526530'>if</span> <span m='2526690'>you</span> <span m='2526820'>describe</span>
  <span m='2527350'>the</span> <span m='2527450'>burst</span> <span m='2527780'>channel</span>
  <span m='2528170'>by</span> <span m='2529500'>max</span> <span m='2530530'>burst</span>
  <span m='2530860'>length</span> <span m='2531250'>in</span> <span m='2531330'>a</span>
  <span m='2531410'>minimum</span> <span m='2531750'>guard</span> <span m='2532060'>space.</span>
  <span m='2534029'>Is</span> <span m='2534502'>that</span> <span m='2535450'>too</span>
  <span m='2535600'>brief?</span> <span m='2535980'>Probably</span> <span m='2536330'>is.</span>
  <span m='2537040'>Give</span> <span m='2537200'>you</span> <span m='2537290'>some</span>
  <span m='2537530'>impression</span> <span m='2538630'>of what</span> <span m='2538890'>we're</span>
  <span m='2539000'>talking</span> <span m='2539380'>about.</span> </p><p><span m='2539700'>So</span>
  <span m='2540470'>Reed-Solomon</span> <span m='2541130'>codes</span> <span m='2541415'>are</span>
  <span m='2541700'>optimum</span> <span m='2542200'>for burst</span> <span m='2542690'>error</span>
  <span m='2542920'>correction,</span> <span m='2543940'>which,</span> <span m='2545470'>most</span>
  <span m='2545770'>real</span> <span m='2546020'>channels</span> <span m='2547586'>are</span>
  <span m='2548010'>bursty.</span> <span m='2549750'>The</span> <span m='2550160'>only</span>
  <span m='2550870'>non-bursty</span> <span m='2551570'>channel</span> <span m='2552020'>that</span>
  <span m='2552060'>we</span> <span m='2552190'>really</span> <span m='2552460'>have</span>
  <span m='2552850'>is</span> <span m='2553080'>the</span> <span m='2553500'>additive</span>
  <span m='2553770'>white</span> <span m='2554090'>Gaussian</span> <span m='2554240'>noise</span>
  <span m='2554570'>channel,</span> <span m='2554950'>ultimately.</span> <span m='2556300'>That</span>
  <span m='2556570'>is</span> <span m='2556800'>the</span> <span m='2556930'>channel</span>
  <span m='2557260'>in</span> <span m='2557400'>space</span> <span m='2557770'>communications,</span>
  <span m='2558550'>which</span> <span m='2558750'>is</span> <span m='2558880'>why</span>
  <span m='2559100'>you</span> <span m='2559320'>can</span> <span m='2560240'>apply</span>
  <span m='2561700'>a</span> <span m='2561800'>nice,</span> <span m='2563410'>textbook-type</span>
  <span m='2564350'>code</span> <span m='2564640'>like</span> <span m='2564920'>this</span>
  <span m='2565280'>to</span> <span m='2565410'>the</span> <span m='2565540'>space</span>
  <span m='2565910'>channel.</span> <span m='2566810'>For</span> <span m='2566960'>any</span>
  <span m='2567120'>other</span> <span m='2567310'>channel,</span> <span m='2568100'>typically,</span>
  <span m='2568570'>you</span> <span m='2568680'>have</span> <span m='2568900'>to</span>
  <span m='2569010'>use</span> <span m='2569250'>some</span> <span m='2569490'>kind</span>
  <span m='2569740'>of</span> <span m='2569830'>interleaving</span> <span m='2570820'>to</span>
  <span m='2570920'>break</span> <span m='2571210'>up</span> <span m='2571380'>the</span>
  <span m='2571470'>bursts</span> <span m='2571965'>so</span> <span m='2572460'>that</span>
  <span m='2572600'>you</span> <span m='2572820'>can --</span> <span m='2574340'>this</span>
  <span m='2574820'>simply</span> <span m='2575170'>is</span> <span m='2576150'>no</span>
  <span m='2576420'>information</span> <span m='2577150'>over</span> <span m='2577380'>a</span>
  <span m='2577450'>long</span> <span m='2577750'>time.</span> <span m='2578120'>If</span>
  <span m='2578230'>you</span> <span m='2578340'>tried</span> <span m='2578700'>to</span>
  <span m='2579210'>encode</span> <span m='2579740'>crossways</span> <span m='2580480'>on</span>
  <span m='2580600'>this,</span> <span m='2580890'>you'd</span> <span m='2581060'>have</span>
  <span m='2581310'>to</span> <span m='2582780'>have</span> <span m='2582920'>a</span>
  <span m='2583060'>code</span> <span m='2583340'>that's</span> <span m='2583620'>long</span>
  <span m='2583960'>enough</span> <span m='2584240'>to</span> <span m='2584420'>see</span>
  <span m='2585150'>the</span> <span m='2585310'>average</span> <span m='2585700'>burst's</span>
  <span m='2586050'>behavior.</span> <span m='2587890'>We'd</span> <span m='2588060'>make</span>
  <span m='2588370'>the</span> <span m='2589370'>burst</span> <span m='2590790'>have</span>
  <span m='2590910'>an</span> <span m='2591470'>ergodic</span> <span m='2591870'>model.</span>
  <span m='2593370'>The</span> <span m='2593480'>way</span> <span m='2593600'>to</span>
  <span m='2593720'>do</span> <span m='2593890'>that</span> <span m='2594090'>in</span>
  <span m='2594190'>practice</span> <span m='2594770'>is</span> <span m='2594920'>to</span>
  <span m='2595040'>code</span> <span m='2595290'>across</span> <span m='2595750'>it</span>
  <span m='2595920'>so</span> <span m='2596030'>you</span> <span m='2596160'>get</span>
  <span m='2596780'>independent</span> <span m='2597540'>snippets</span> <span m='2598690'>of</span>
  <span m='2599180'>widely</span> <span m='2599700'>separated</span> <span m='2600350'>bursts</span>
  <span m='2600710'>which</span> <span m='2601180'>can</span> <span m='2601430'>be</span>
  <span m='2601660'>assumed to</span> <span m='2601890'>be</span> <span m='2602170'>independent.</span>
  <span m='2603156'>Yeah.</span> </p><p><span m='2603650'>AUDIENCE:</span> <span m='2604113'>[INAUDIBLE]?</span>
  </p><p><span m='2608890'>PROFESSOR:</span> <span m='2609360'>No</span> <span m='2609460'>different,</span>
  <span m='2609750'>really.</span> </p><p><span m='2610080'>AUDIENCE:</span> <span
  m='2610551'>[INAUDIBLE].</span> </p><p><span m='2613377'>PROFESSOR:</span> <span
  m='2614130'>Yeah,</span> <span m='2614590'>in</span> <span m='2614780'>space</span>
  <span m='2615200'>channel --</span> <span m='2615640'>all right.</span> <span m='2616010'>Here,</span>
  <span m='2616270'>I'm</span> <span m='2616360'>talking</span> <span m='2616760'>about</span>
  <span m='2617020'>power limit.</span> <span m='2617830'>That's</span> <span m='2618060'>a</span>
  <span m='2618110'>good</span> <span m='2618290'>question.</span> <span m='2620300'>But</span>
  <span m='2620720'>if</span> <span m='2620930'>you</span> <span m='2621060'>think</span>
  <span m='2621640'>about</span> <span m='2621920'>the</span> <span m='2621990'>band-limited</span>
  <span m='2622650'>regime,</span> <span m='2624540'>let's</span> <span m='2624770'>suppose
  --</span> <span m='2625640'>so</span> <span m='2625890'>this</span> <span m='2626100'>would</span>
  <span m='2626240'>be</span> <span m='2626450'>some</span> <span m='2627460'>[? MRE
  ?]</span> <span m='2627870'>channel.</span> <span m='2628320'>You</span> <span m='2628470'>would</span>
  <span m='2628600'>use</span> <span m='2630150'>some</span> <span m='2630510'>multilevel</span>
  <span m='2631510'>signaling</span> <span m='2631940'>scheme</span> <span m='2632520'>like</span>
  <span m='2632810'>QAM</span> <span m='2633440'>with</span> <span m='2633570'>a</span>
  <span m='2633700'>large</span> <span m='2634530'>signal</span> <span m='2634940'>set</span>
  <span m='2635790'>or</span> <span m='2635950'>QPSK</span> <span m='2636480'>or</span>
  <span m='2636610'>something</span> <span m='2636920'>like</span> <span m='2637140'>that</span>
  <span m='2637780'>to</span> <span m='2638300'>get</span> <span m='2638470'>a</span>
  <span m='2638530'>basic</span> <span m='2639030'>transmission</span> <span m='2640450'>with</span>
  <span m='2640600'>a</span> <span m='2640750'>discrete</span> <span m='2641530'>signal</span>
  <span m='2641730'>set</span> <span m='2642500'>that</span> <span m='2642710'>doesn't</span>
  <span m='2643040'>lose</span> <span m='2643360'>too</span> <span m='2643520'>much</span>
  <span m='2644400'>over</span> <span m='2645150'>sending</span> <span m='2645460'>Gaussian</span>
  <span m='2647030'>over</span> <span m='2647250'>the</span> <span m='2647430'>channel.</span>
  <span m='2648730'>Again,</span> <span m='2650040'>this</span> <span m='2650230'>will</span>
  <span m='2650300'>be</span> <span m='2650430'>later</span> <span m='2650700'>in</span>
  <span m='2650800'>the</span> <span m='2650890'>course.</span> <span m='2651440'>We'll</span>
  <span m='2651570'>talk</span> <span m='2651830'>about</span> <span m='2652010'>this</span>
  <span m='2652240'>in</span> <span m='2652350'>detail.</span> </p><p><span m='2653480'>Other</span>
  <span m='2653790'>than</span> <span m='2653980'>that --</span> <span m='2655770'>well,</span>
  <span m='2656270'>all</span> <span m='2656400'>right,</span> <span m='2656620'>so</span>
  <span m='2656740'>now</span> <span m='2656930'>this</span> <span m='2657130'>is</span>
  <span m='2657270'>an</span> <span m='2657390'>MRE</span> <span m='2657730'>channel.</span>
  <span m='2658940'>If</span> <span m='2659360'>M</span> <span m='2659730'>is</span>
  <span m='2659940'>large</span> <span m='2660310'>enough,</span> <span m='2660760'>then</span>
  <span m='2660940'>you</span> <span m='2661090'>could</span> <span m='2661240'>apply</span>
  <span m='2661620'>Reed-Solomon</span> <span m='2662280'>codes</span> <span m='2662660'>right</span>
  <span m='2662910'>here.</span> <span m='2663410'>But</span> <span m='2663990'>typically,</span>
  <span m='2664430'>it's</span> <span m='2664650'>not.</span> <span m='2664950'>M</span>
  <span m='2665200'>is</span> <span m='2665380'>like</span> <span m='2665730'>16</span>
  <span m='2666300'>or</span> <span m='2666420'>64.</span> <span m='2668590'>And</span>
  <span m='2668880'>so</span> <span m='2669340'>Reed-Solomon</span> <span m='2670300'>codes</span>
  <span m='2670560'>would</span> <span m='2670690'>still</span> <span m='2670980'>be</span>
  <span m='2671340'>too</span> <span m='2671490'>short.</span> <span m='2672940'>You</span>
  <span m='2673080'>would</span> <span m='2673170'>not</span> <span m='2673400'>be</span>
  <span m='2673530'>able</span> <span m='2673640'>to</span> <span m='2673680'>get</span>
  <span m='2673840'>long</span> <span m='2674110'>enough</span> <span m='2674370'>codes</span>
  <span m='2674870'>over</span> <span m='2675110'>such</span> <span m='2675380'>a</span>
  <span m='2675440'>channel.</span> <span m='2676280'>So</span> <span m='2676535'>a</span>
  <span m='2676790'>similar</span> <span m='2678250'>kind</span> <span m='2678490'>of</span>
  <span m='2678600'>thing</span> <span m='2679660'>can</span> <span m='2679790'>be</span>
  <span m='2679920'>done.</span> <span m='2680210'>And</span> <span m='2680330'>the</span>
  <span m='2681120'>history</span> <span m='2681550'>of</span> <span m='2681680'>bandwidth-limited</span>
  <span m='2682670'>coding</span> <span m='2683250'>pretty</span> <span m='2683470'>much</span>
  <span m='2683680'>parallels</span> <span m='2684210'>that</span> <span m='2684310'>of</span>
  <span m='2685090'>power-limited</span> <span m='2685710'>coding.</span> </p><p><span
  m='2687530'>What</span> <span m='2687730'>corresponds</span> <span m='2688550'>to</span>
  <span m='2689680'>block</span> <span m='2689970'>codes</span> <span m='2690410'>here</span>
  <span m='2690880'>is</span> <span m='2691480'>lattice</span> <span m='2691930'>codes</span>
  <span m='2692740'>for</span> <span m='2692850'>this</span> <span m='2693130'>channel.</span>
  <span m='2693820'>What</span> <span m='2694080'>corresponds</span> <span m='2694700'>to</span>
  <span m='2694840'>convolutional</span> <span m='2695440'>codes</span> <span m='2695910'>is</span>
  <span m='2696180'>trellis-coded</span> <span m='2696850'>modulation.</span> <span
  m='2699510'>And</span> <span m='2701150'>again,</span> <span m='2701510'>once</span>
  <span m='2701880'>you</span> <span m='2702470'>handle</span> <span m='2702930'>the</span>
  <span m='2703030'>basic</span> <span m='2703630'>physical</span> <span m='2704120'>channel</span>
  <span m='2705010'>with</span> <span m='2705180'>these</span> <span m='2705420'>codes</span>
  <span m='2705880'>that are</span> <span m='2706050'>well</span> <span m='2706330'>matched</span>
  <span m='2706710'>to</span> <span m='2706780'>that</span> <span m='2707000'>channel</span>
  <span m='2707410'>but</span> <span m='2708160'>whose</span> <span m='2708450'>complexity</span>
  <span m='2709070'>increases</span> <span m='2709720'>too</span> <span m='2709890'>rapidly</span>
  <span m='2710390'>if</span> <span m='2710500'>you</span> <span m='2710630'>make</span>
  <span m='2710850'>them</span> <span m='2710980'>long</span> <span m='2711420'>because</span>
  <span m='2712270'>of</span> <span m='2713070'>exponential</span> <span m='2713740'>decoding,</span>
  <span m='2714730'>then</span> <span m='2714960'>you</span> <span m='2715080'>can</span>
  <span m='2715220'>always</span> <span m='2715510'>clean</span> <span m='2715840'>up</span>
  <span m='2716580'>whatever</span> <span m='2716910'>errors</span> <span m='2717240'>you</span>
  <span m='2717400'>make.</span> </p><p><span m='2718430'>You</span> <span m='2718520'>can</span>
  <span m='2718660'>think</span> <span m='2718860'>of</span> <span m='2719100'>this</span>
  <span m='2719340'>as</span> <span m='2719500'>a</span> <span m='2719660'>cleanup</span>
  <span m='2720130'>function</span> <span m='2720510'>out here.</span> <span m='2722030'>Typically,</span>
  <span m='2722440'>the</span> <span m='2722560'>rates</span> <span m='2722950'>out</span>
  <span m='2723100'>here</span> <span m='2723290'>are</span> <span m='2723310'>very</span>
  <span m='2723580'>high.</span> <span m='2724290'>You</span> <span m='2724480'>don't</span>
  <span m='2724670'>need</span> <span m='2724970'>much</span> <span m='2725220'>redundancy.</span>
  <span m='2726120'>It</span> <span m='2726330'>doesn't</span> <span m='2726600'>cost</span>
  <span m='2726950'>too</span> <span m='2727070'>much</span> <span m='2727360'>in</span>
  <span m='2727520'>overall</span> <span m='2728040'>rate.</span> <span m='2730550'>But</span>
  <span m='2731230'>even</span> <span m='2731570'>with</span> <span m='2731770'>very</span>
  <span m='2732020'>high</span> <span m='2732230'>rates,</span> <span m='2732620'>like</span>
  <span m='2732760'>223</span> <span m='2733480'>over</span> <span m='2733700'>255,</span>
  <span m='2735570'>you</span> <span m='2735790'>can</span> <span m='2735950'>do</span>
  <span m='2736340'>a</span> <span m='2736730'>rather</span> <span m='2737030'>large</span>
  <span m='2737400'>amount</span> <span m='2737670'>of error</span> <span m='2737930'>correction.</span>
  <span m='2738225'>You can</span> <span m='2738520'>correct</span> <span m='2739010'>up</span>
  <span m='2739200'>to</span> <span m='2739500'>16</span> <span m='2739950'>errors</span>
  <span m='2740850'>or</span> <span m='2740970'>32</span> <span m='2741430'>erasures</span>
  <span m='2742020'>with</span> <span m='2742260'>us</span> <span m='2742640'>channel.</span>
  <span m='2742980'>So</span> <span m='2743750'>this</span> <span m='2743960'>is</span>
  <span m='2744070'>a</span> <span m='2744150'>cleanup</span> <span m='2744620'>function.</span>
  </p><p><span m='2745720'>You</span> <span m='2746080'>basically</span> <span m='2746480'>work</span>
  <span m='2746840'>very</span> <span m='2747140'>hard</span> <span m='2747390'>in</span>
  <span m='2747490'>here,</span> <span m='2747810'>get</span> <span m='2748040'>the</span>
  <span m='2748130'>best</span> <span m='2749060'>error</span> <span m='2749310'>probability</span>
  <span m='2750060'>you</span> <span m='2750360'>can,</span> <span m='2750660'>which
  --</span> <span m='2751430'>it</span> <span m='2751550'>doesn't</span> <span m='2751770'>have</span>
  <span m='2751950'>to</span> <span m='2752030'>be</span> <span m='2752180'>too</span>
  <span m='2752360'>low.</span> <span m='2752740'>10</span> <span m='2752970'>to</span>
  <span m='2753020'>the</span> <span m='2753080'>minus</span> <span m='2753440'>2,</span>
  <span m='2753920'>10</span> <span m='2754000'>to the</span> <span m='2754250'>minus</span>
  <span m='2754420'>3.</span> <span m='2755340'>And</span> <span m='2755540'>then</span>
  <span m='2755700'>you use</span> <span m='2756090'>this</span> <span m='2756340'>to</span>
  <span m='2756470'>clean</span> <span m='2756740'>it</span> <span m='2756850'>up</span>
  <span m='2757060'>and</span> <span m='2757140'>that</span> <span m='2757330'>drives</span>
  <span m='2757680'>the</span> <span m='2757900'>error</span> <span m='2757960'>probability</span>
  <span m='2758410'>down</span> <span m='2758680'>to</span> <span m='2758900'>10 to
  the</span> <span m='2759010'>minus</span> <span m='2759300'>12</span> <span m='2760040'>or</span>
  <span m='2760260'>10 to the minus 15</span> <span m='2760820'>or</span> <span m='2761420'>whatever</span>
  <span m='2761790'>you</span> <span m='2761810'>really</span> <span m='2762020'>want.</span>
  <span m='2765910'>But</span> <span m='2766920'>the</span> <span m='2767160'>principles</span>
  <span m='2767880'>are</span> <span m='2767980'>the</span> <span m='2768100'>same</span>
  <span m='2768500'>in</span> <span m='2769040'>power limit</span> <span m='2769335'>and</span>
  <span m='2769630'>band limit.</span> <span m='2770660'>But</span> <span m='2771020'>nice</span>
  <span m='2771330'>question.</span> <span m='2773730'>Any</span> <span m='2773860'>other</span>
  <span m='2774000'>questions?</span> <span m='2778700'>OK.</span> </p><p><span m='2779250'>So</span>
  <span m='2781260'>as</span> <span m='2781440'>a</span> <span m='2781620'>result,</span>
  <span m='2782870'>Reed-Solomon</span> <span m='2783500'>codes</span> <span m='2783950'>are</span>
  <span m='2784180'>the</span> <span m='2785400'>general</span> <span m='2785780'>purpose</span>
  <span m='2786290'>code</span> <span m='2788770'>that</span> <span m='2788920'>has</span>
  <span m='2789150'>emerged</span> <span m='2789660'>from</span> <span m='2789830'>algebraic</span>
  <span m='2790560'>coding</span> <span m='2790860'>theory.</span> <span m='2792310'>A</span>
  <span m='2792340'>good</span> <span m='2792570'>example</span> <span m='2793060'>of</span>
  <span m='2793160'>burst</span> <span m='2793540'>error</span> <span m='2793790'>correction</span>
  <span m='2794430'>is,</span> <span m='2796510'>you</span> <span m='2796710'>know</span>
  <span m='2796860'>on</span> <span m='2797080'>your</span> <span m='2797460'>CDs,</span>
  <span m='2798420'>there</span> <span m='2798940'>is</span> <span m='2799080'>an</span>
  <span m='2799150'>error</span> <span m='2799370'>correction</span> <span m='2800180'>scheme</span>
  <span m='2800550'>incorporated</span> <span m='2801260'>such</span> <span m='2801560'>that
  if</span> <span m='2801740'>you</span> <span m='2801860'>scratch</span> <span m='2802390'>the</span>
  <span m='2802510'>CD,</span> <span m='2802840'>it</span> <span m='2803090'>still</span>
  <span m='2803340'>works.</span> <span m='2805610'>How</span> <span m='2805670'>does</span>
  <span m='2805800'>that</span> <span m='2805930'>work?</span> <span m='2806240'>It</span>
  <span m='2806360'>could</span> <span m='2806500'>only</span> <span m='2807230'>be</span>
  <span m='2807420'>because</span> <span m='2807780'>there's</span> <span m='2807930'>some</span>
  <span m='2808140'>error</span> <span m='2808380'>correction</span> <span m='2808670'>in</span>
  <span m='2808960'>there.</span> </p><p><span m='2809150'>What,</span> <span m='2809880'>actually,</span>
  <span m='2810360'>is</span> <span m='2810640'>the</span> <span m='2810780'>error</span>
  <span m='2811040'>correction</span> <span m='2811510'>scheme?</span> <span m='2813810'>I'm</span>
  <span m='2813970'>not</span> <span m='2814160'>sure</span> <span m='2814410'>I</span>
  <span m='2814470'>know</span> <span m='2814660'>what</span> <span m='2814820'>the</span>
  <span m='2814900'>latest</span> <span m='2815310'>and</span> <span m='2815390'>greatest</span>
  <span m='2815880'>is,</span> <span m='2816150'>but</span> <span m='2818000'>generally,</span>
  <span m='2818620'>the</span> <span m='2819000'>error</span> <span m='2819240'>correction</span>
  <span m='2819640'>schemes</span> <span m='2820210'>for</span> <span m='2821310'>magnetic</span>
  <span m='2822150'>memory</span> <span m='2822560'>recording</span> <span m='2824530'>like</span>
  <span m='2824980'>that</span> <span m='2825160'>have</span> <span m='2825340'>used</span>
  <span m='2825700'>Reed-Solomon</span> <span m='2826340'>codes --</span> <span m='2828160'>have</span>
  <span m='2828380'>used</span> <span m='2828590'>two</span> <span m='2829090'>Reed-Solomon</span>
  <span m='2829740'>codes</span> <span m='2830170'>in</span> <span m='2830580'>interleave</span>
  <span m='2831040'>fashion</span> <span m='2831510'>like</span> <span m='2831710'>this.</span>
  <span m='2831960'>So</span> <span m='2832180'>the</span> <span m='2832870'>across</span>
  <span m='2833230'>code</span> <span m='2833480'>is</span> <span m='2833590'>Reed-Solomon.</span>
  <span m='2834290'>The</span> <span m='2834400'>down</span> <span m='2834710'>code</span>
  <span m='2835110'>is</span> <span m='2835340'>Reed-Solomon.</span> </p><p><span
  m='2836220'>As</span> <span m='2836430'>a</span> <span m='2836490'>result,</span>
  <span m='2836990'>if</span> <span m='2837120'>you</span> <span m='2837260'>make</span>
  <span m='2837640'>a</span> <span m='2838020'>scratch</span> <span m='2838740'>through</span>
  <span m='2838910'>the disc,</span> <span m='2840620'>you</span> <span m='2840820'>will</span>
  <span m='2842520'>cut</span> <span m='2844210'>all of</span> <span m='2844530'>these</span>
  <span m='2844840'>codes,</span> <span m='2845440'>but</span> <span m='2846350'>you
  will</span> <span m='2846630'>cut</span> <span m='2846880'>each</span> <span m='2847190'>one</span>
  <span m='2848810'>in a</span> <span m='2848980'>small</span> <span m='2849290'>enough</span>
  <span m='2849500'>place</span> <span m='2849860'>so that</span> <span m='2850120'>you</span>
  <span m='2850230'>can</span> <span m='2850350'>correct</span> <span m='2850750'>it.</span>
  <span m='2852300'>So</span> <span m='2852500'>you</span> <span m='2852600'>can</span>
  <span m='2852710'>think</span> <span m='2852930'>of</span> <span m='2852980'>this</span>
  <span m='2853200'>as a</span> <span m='2853320'>actually</span> <span m='2853660'>a</span>
  <span m='2853710'>physical</span> <span m='2854260'>laying</span> <span m='2854620'>down</span>
  <span m='2855315'>of</span> <span m='2855570'>Reed-Solomon</span> <span m='2856350'>codes</span>
  <span m='2857220'>on the</span> <span m='2857620'>two-dimensional</span> <span m='2858250'>surface</span>
  <span m='2858740'>of</span> <span m='2858820'>the</span> <span m='2858910'>disc</span>
  <span m='2860420'>in</span> <span m='2860620'>such</span> <span m='2860920'>a</span>
  <span m='2860980'>way</span> <span m='2861220'>that --</span> <span m='2861710'>well,</span>
  <span m='2862930'>even</span> <span m='2863170'>if</span> <span m='2863280'>your</span>
  <span m='2863390'>scratch</span> <span m='2863930'>came</span> <span m='2864160'>right</span>
  <span m='2864400'>across</span> <span m='2864890'>one</span> <span m='2865090'>whole</span>
  <span m='2865350'>channel</span> <span m='2865700'>here,</span> <span m='2865930'>then,</span>
  <span m='2866040'>of</span> <span m='2866520'>course,</span> <span m='2866820'>this</span>
  <span m='2867080'>decoder</span> <span m='2867550'>would</span> <span m='2867720'>be</span>
  <span m='2868160'>dead.</span> <span m='2868780'>But</span> <span m='2869030'>you</span>
  <span m='2869150'>still</span> <span m='2869480'>have</span> <span m='2869690'>somebody</span>
  <span m='2870630'>decoding</span> <span m='2871160'>in</span> <span m='2871250'>this</span>
  <span m='2871950'>direction</span> <span m='2872480'>to</span> <span m='2872590'>pick</span>
  <span m='2872790'>up</span> <span m='2873000'>the</span> <span m='2873150'>errors.</span>
  <span m='2874740'>And</span> <span m='2874920'>so</span> <span m='2875060'>that's</span>
  <span m='2875310'>why</span> <span m='2875560'>you</span> <span m='2875760'>can</span>
  <span m='2876220'>completely</span> <span m='2876650'>abuse</span> <span m='2877140'>these</span>
  <span m='2877420'>discs</span> <span m='2878000'>and</span> <span m='2879290'>they</span>
  <span m='2879590'>still</span> <span m='2879880'>work.</span> </p><p><span m='2881160'>And</span>
  <span m='2881240'>when</span> <span m='2881350'>you</span> <span m='2881430'>think</span>
  <span m='2881660'>about</span> <span m='2881820'>what's</span> <span m='2882010'>actually</span>
  <span m='2882330'>going</span> <span m='2882620'>on,</span> <span m='2882750'>think</span>
  <span m='2882940'>of</span> <span m='2883030'>the</span> <span m='2883120'>transfer</span>
  <span m='2883700'>rates</span> <span m='2885250'>from</span> <span m='2885850'>a</span>
  <span m='2886570'>CD</span> <span m='2887920'>to</span> <span m='2888020'>your</span>
  <span m='2888210'>computer.</span> <span m='2890120'>It's</span> <span m='2890880'>up</span>
  <span m='2891100'>in</span> <span m='2891250'>the</span> <span m='2891330'>hundreds</span>
  <span m='2891870'>of</span> <span m='2892010'>millions</span> <span m='2892460'>of</span>
  <span m='2893440'>bits</span> <span m='2893700'>per</span> <span m='2893850'>second.</span>
  <span m='2895160'>Maybe</span> <span m='2895370'>its</span> <span m='2895560'>gigabits</span>
  <span m='2896080'>by</span> <span m='2896250'>now.</span> <span m='2896950'>Perhaps</span>
  <span m='2897420'>it</span> <span m='2897630'>is.</span> <span m='2898380'>And</span>
  <span m='2898840'>you've</span> <span m='2899000'>got</span> <span m='2899210'>this</span>
  <span m='2899400'>Reed-Solomon --</span> <span m='2900130'>these</span> <span m='2900340'>are</span>
  <span m='2900420'>non-trivial</span> <span m='2901110'>Reed-Solomon</span> <span
  m='2902120'>decoders.</span> <span m='2902700'>These</span> <span m='2902920'>are</span>
  <span m='2903010'>like</span> <span m='2903830'>this</span> <span m='2904290'>16</span>
  <span m='2904810'>error</span> <span m='2905070'>correcting</span> <span m='2905720'>decoder</span>
  <span m='2906030'>out</span> <span m='2906190'>here.</span> <span m='2907020'>And</span>
  <span m='2907470'>so</span> <span m='2907720'>these</span> <span m='2907840'>are</span>
  <span m='2909090'>working</span> <span m='2909470'>away</span> <span m='2909810'>at</span>
  <span m='2909960'>that</span> <span m='2910180'>data</span> <span m='2910390'>rate,</span>
  <span m='2910680'>capable</span> <span m='2911180'>of</span> <span m='2911420'>doing</span>
  <span m='2911680'>decoding.</span> <span m='2911945'>And</span> <span m='2912210'>they're</span>
  <span m='2912420'>cheap</span> <span m='2912690'>enough</span> <span m='2913690'>so</span>
  <span m='2914090'>that</span> <span m='2914370'>they're</span> <span m='2914660'>just
  buried</span> <span m='2915100'>in</span> <span m='2915620'>part</span> <span m='2915890'>of</span>
  <span m='2916690'>one</span> <span m='2916880'>of</span> <span m='2916920'>the</span>
  <span m='2917000'>integrated</span> <span m='2917440'>circuits</span> <span m='2918860'>in</span>
  <span m='2918990'>your</span> <span m='2919120'>disc</span> <span m='2919400'>player</span>
  <span m='2919720'>circuitry.</span> </p><p><span m='2921520'>So</span> <span m='2922640'>that'd</span>
  <span m='2923250'>give</span> <span m='2923410'>you</span> <span m='2923550'>a</span>
  <span m='2923590'>physical</span> <span m='2924090'>sense</span> <span m='2924530'>for</span>
  <span m='2924660'>just</span> <span m='2926200'>how</span> <span m='2926410'>much</span>
  <span m='2926880'>error</span> <span m='2927150'>correction</span> <span m='2927560'>power</span>
  <span m='2928470'>and</span> <span m='2928600'>speed</span> <span m='2929300'>you</span>
  <span m='2929450'>can</span> <span m='2929610'>get</span> <span m='2929800'>out</span>
  <span m='2929970'>of</span> <span m='2930050'>this</span> <span m='2930260'>class</span>
  <span m='2931920'>of</span> <span m='2932090'>code</span> <span m='2932700'>decoder,</span>
  <span m='2935990'>OK?</span> <span m='2937050'>So</span> <span m='2938020'>wherever</span>
  <span m='2938270'>you</span> <span m='2938400'>want</span> <span m='2938590'>an</span>
  <span m='2938680'>extremely</span> <span m='2939320'>powerful</span> <span m='2939860'>code</span>
  <span m='2940860'>and</span> <span m='2941110'>you're</span> <span m='2941250'>a</span>
  <span m='2941290'>little</span> <span m='2941450'>bit</span> <span m='2941610'>less</span>
  <span m='2942050'>concerned</span> <span m='2942680'>with</span> <span m='2943080'>getting</span>
  <span m='2943330'>to</span> <span m='2943470'>capacity,</span> <span m='2944920'>Reed-Solomon</span>
  <span m='2945450'>code is</span> <span m='2945930'>the way</span> <span m='2946210'>to
  go.</span> <span m='2947045'>It's</span> <span m='2947530'>absolutely</span> <span
  m='2947970'>part</span> <span m='2948240'>of</span> <span m='2948370'>your</span>
  <span m='2948510'>toolbox,</span> <span m='2952390'>OK?</span> </p><p><span m='2957520'>The</span>
  <span m='2957800'>last</span> <span m='2958240'>topic</span> <span m='2958770'>in</span>
  <span m='2963400'>chapter</span> <span m='2964050'>eight</span> <span m='2964360'>is</span>
  <span m='2964670'>BCH</span> <span m='2965530'>codes,</span> <span m='2968740'>which</span>
  <span m='2969070'>are</span> <span m='2970350'>binary</span> <span m='2971120'>codes.</span>
  <span m='2973310'>So</span> <span m='2973640'>they're</span> <span m='2973780'>binary</span>
  <span m='2974540'>linear</span> <span m='2974970'>block</span> <span m='2975345'>codes</span>
  <span m='2978200'>of</span> <span m='2978700'>the</span> <span m='2978930'>class</span>
  <span m='2979360'>we've</span> <span m='2979570'>been</span> <span m='2979760'>discussing,</span>
  <span m='2980870'>comparable</span> <span m='2981400'>with</span> <span m='2981580'>Reed-Muller</span>
  <span m='2982210'>codes.</span> <span m='2984640'>Reed-Muller</span> <span m='2985130'>codes</span>
  <span m='2985660'>were</span> <span m='2986320'>discovered</span> <span m='2986920'>in</span>
  <span m='2987450'>1954</span> <span m='2988630'>in</span> <span m='2988790'>two</span>
  <span m='2988960'>separate</span> <span m='2989370'>papers</span> <span m='2989920'>by</span>
  <span m='2990070'>Reed</span> <span m='2990480'>and by</span> <span m='2990640'>Muller</span>
  <span m='2993340'>in</span> <span m='2993500'>two</span> <span m='2993670'>separate</span>
  <span m='2994080'>points</span> <span m='2994390'>of</span> <span m='2994460'>view.</span>
  <span m='2994790'>And</span> <span m='2995800'>there are a</span> <span m='2996120'>million</span>
  <span m='2996480'>points</span> <span m='2996760'>of view</span> <span m='2996860'>you</span>
  <span m='2997200'>can</span> <span m='2997330'>have</span> <span m='2997500'>for</span>
  <span m='2997760'>Reed-Muller</span> <span m='2998060'>codes.</span> <span m='2998470'>We've</span>
  <span m='2998820'>used</span> <span m='2999150'>yet</span> <span m='2999310'>a</span>
  <span m='2999430'>third</span> <span m='2999730'>one.</span> </p><p><span m='3002590'>BCH</span>
  <span m='3003630'>stands</span> <span m='3004190'>for</span> <span m='3004950'>Bose</span>
  <span m='3005580'>and</span> <span m='3005840'>Chaudhury</span> <span m='3007180'>and</span>
  <span m='3007490'>Hocquenghem.</span> <span m='3009880'>Bose</span> <span m='3010165'>and</span>
  <span m='3010450'>Chaudhury</span> <span m='3010960'>were</span> <span m='3011140'>both</span>
  <span m='3011410'>professors</span> <span m='3012020'>in</span> <span m='3012060'>the</span>
  <span m='3012150'>US.</span> <span m='3013290'>They</span> <span m='3013690'>wrote</span>
  <span m='3013960'>a</span> <span m='3014120'>paper</span> <span m='3014530'>about</span>
  <span m='3015490'>1960</span> <span m='3016450'>introducing</span> <span m='3017680'>Reed-Solomon</span>
  <span m='3018310'>codes,</span> <span m='3018720'>which,</span> <span m='3018920'>by</span>
  <span m='3019060'>the</span> <span m='3019210'>way,</span> <span m='3020450'>and</span>
  <span m='3020700'>introducing</span> <span m='3022290'>BC</span> <span m='3022640'>codes
  --</span> <span m='3023040'>Bose-Chaudhury</span> <span m='3023880'>codes --</span>
  <span m='3025240'>Reed-Solomon's</span> <span m='3026070'>paper</span> <span m='3026420'>was</span>
  <span m='3026630'>in</span> <span m='3026890'>1960</span> <span m='3027640'>also.</span>
  <span m='3028040'>These</span> <span m='3028270'>were</span> <span m='3028390'>completely</span>
  <span m='3028780'>independent</span> <span m='3029320'>of</span> <span m='3029400'>each</span>
  <span m='3029640'>other.</span> <span m='3031260'>And</span> <span m='3031530'>then</span>
  <span m='3031870'>this</span> <span m='3031990'>fellow</span> <span m='3032370'>named</span>
  <span m='3032900'>Hocquenghem</span> <span m='3034520'>in</span> <span m='3034860'>France,</span>
  <span m='3035380'>whose</span> <span m='3035660'>name</span> <span m='3036310'>I</span>
  <span m='3036470'>can't</span> <span m='3036860'>and</span> <span m='3037090'>few</span>
  <span m='3037280'>people</span> <span m='3037700'>can</span> <span m='3037870'>pronounce,</span>
  <span m='3040720'>turned</span> <span m='3040960'>out</span> <span m='3041100'>he</span>
  <span m='3041230'>had</span> <span m='3041360'>actually</span> <span m='3041710'>invented</span>
  <span m='3042030'>these</span> <span m='3042270'>codes</span> <span m='3042740'>in</span>
  <span m='3043220'>1959</span> <span m='3044930'>in</span> <span m='3045050'>a</span>
  <span m='3045110'>paper</span> <span m='3045460'>that</span> <span m='3045770'>unfortunately</span>
  <span m='3046035'>was</span> <span m='3046300'>in</span> <span m='3046430'>French,</span>
  <span m='3046900'>so</span> <span m='3047460'>few</span> <span m='3047680'>people</span>
  <span m='3047980'>read</span> <span m='3048200'>it.</span> </p><p><span m='3049750'>But</span>
  <span m='3049940'>anyway,</span> <span m='3050380'>in honor</span> <span m='3050750'>of</span>
  <span m='3050900'>all</span> <span m='3051130'>three</span> <span m='3051330'>of</span>
  <span m='3051380'>these</span> <span m='3051580'>people,</span> <span m='3051910'>these</span>
  <span m='3052120'>are</span> <span m='3052190'>called</span> <span m='3052500'>BCH</span>
  <span m='3053170'>codes.</span> <span m='3054340'>These</span> <span m='3054740'>fit</span>
  <span m='3055120'>right</span> <span m='3055600'>into</span> <span m='3056010'>the</span>
  <span m='3056140'>main</span> <span m='3056490'>theme</span> <span m='3056840'>of</span>
  <span m='3056970'>algebraic</span> <span m='3057750'>coding</span> <span m='3058070'>theory</span>
  <span m='3058400'>at</span> <span m='3058510'>that</span> <span m='3058750'>time.</span>
  <span m='3059080'>Maybe</span> <span m='3059400'>stimulated</span> <span m='3059820'>it</span>
  <span m='3060240'>because</span> <span m='3060520'>these</span> <span m='3061240'>turned
  out to</span> <span m='3061610'>be</span> <span m='3061730'>cyclic</span> <span
  m='3062190'>codes,</span> <span m='3062445'>or</span> <span m='3062700'>at</span>
  <span m='3062900'>least</span> <span m='3063100'>as</span> <span m='3063310'>they</span>
  <span m='3063440'>were</span> <span m='3064120'>originally</span> <span m='3064610'>introduced.</span>
  <span m='3065920'>And</span> <span m='3069040'>so</span> <span m='3070260'>when</span>
  <span m='3070550'>I</span> <span m='3070650'>was</span> <span m='3070870'>in</span>
  <span m='3070930'>school,</span> <span m='3071350'>which</span> <span m='3071580'>was</span>
  <span m='3071810'>in</span> <span m='3073250'>the</span> <span m='3073450'>early</span>
  <span m='3073670'>'60s,</span> <span m='3075130'>these</span> <span m='3075640'>were</span>
  <span m='3075870'>considered</span> <span m='3076930'>the</span> <span m='3077060'>greatest</span>
  <span m='3077480'>thing</span> <span m='3077700'>going.</span> <span m='3078590'>People</span>
  <span m='3078670'>were interested</span> <span m='3078965'>in</span> <span m='3079260'>binary</span>
  <span m='3079730'>codes,</span> <span m='3081240'>algebraic</span> <span m='3081830'>codes</span>
  <span m='3083500'>because</span> <span m='3083750'>they</span> <span m='3083900'>are</span>
  <span m='3086420'>slightly</span> <span m='3086820'>better</span> <span m='3087340'>than</span>
  <span m='3087480'>Reed-Muller</span> <span m='3087970'>codes.</span> </p><p><span
  m='3089570'>Now,</span> <span m='3089760'>I</span> <span m='3089850'>would</span>
  <span m='3090000'>say,</span> <span m='3090200'>there's</span> <span m='3090400'>sort</span>
  <span m='3090560'>of</span> <span m='3090650'>been a</span> <span m='3090830'>swing</span>
  <span m='3091180'>back.</span> <span m='3091980'>Shu Lin</span> <span m='3092490'>gave</span>
  <span m='3092800'>a</span> <span m='3092910'>paper</span> <span m='3093260'>about</span>
  <span m='3094130'>10</span> <span m='3094340'>years</span> <span m='3094630'>ago</span>
  <span m='3094910'>that</span> <span m='3095100'>said</span> <span m='3095780'>Reed-Muller</span>
  <span m='3096240'>codes</span> <span m='3096590'>are</span> <span m='3096740'>not</span>
  <span m='3097000'>so</span> <span m='3097160'>bad.</span> <span m='3098140'>In</span>
  <span m='3098350'>fact,</span> <span m='3098710'>in</span> <span m='3098820'>terms</span>
  <span m='3099210'>of</span> <span m='3099350'>performance</span> <span m='3099990'>versus</span>
  <span m='3100410'>complexity</span> <span m='3101140'>for</span> <span m='3101330'>certain</span>
  <span m='3101630'>kinds</span> <span m='3101970'>of</span> <span m='3102050'>decoding</span>
  <span m='3102570'>schemes,</span> <span m='3102950'>trellis-based</span> <span m='3103690'>decoding,</span>
  <span m='3104630'>Reed-Muller</span> <span m='3105080'>codes</span> <span m='3105410'>are</span>
  <span m='3105560'>better</span> <span m='3106010'>than</span> <span m='3106130'>BCH</span>
  <span m='3106810'>codes.</span> <span m='3108000'>So</span> <span m='3108300'>from</span>
  <span m='3108440'>a</span> <span m='3108590'>more</span> <span m='3108810'>modern</span>
  <span m='3109230'>prospective,</span> <span m='3109880'>we're</span> <span m='3110000'>more</span>
  <span m='3110280'>interested</span> <span m='3110610'>in Reed-Muller</span> <span
  m='3111150'>than</span> <span m='3111270'>we</span> <span m='3111430'>are</span>
  <span m='3111600'>in</span> <span m='3111620'>BCH.</span> <span m='3113520'>Nonetheless,</span>
  <span m='3116010'>you'll</span> <span m='3116200'>hear</span> <span m='3116390'>about</span>
  <span m='3116620'>these</span> <span m='3116850'>a</span> <span m='3116910'>lot</span>
  <span m='3117160'>if</span> <span m='3117260'>you</span> <span m='3117380'>read</span>
  <span m='3117550'>the</span> <span m='3117790'>literature</span> <span m='3118360'>and</span>
  <span m='3118460'>so</span> <span m='3118600'>you</span> <span m='3118750'>ought</span>
  <span m='3118910'>to</span> <span m='3119030'>know</span> <span m='3119150'>what</span>
  <span m='3119290'>they</span> <span m='3119460'>are.</span> </p><p><span m='3121780'>OK.</span>
  <span m='3122560'>Conceptually,</span> <span m='3123230'>what</span> <span m='3123410'>are</span>
  <span m='3123570'>they?</span> <span m='3125890'>Since</span> <span m='3126350'>we</span>
  <span m='3126500'>already</span> <span m='3126850'>know</span> <span m='3127240'>about</span>
  <span m='3127540'>Reed-Solomon</span> <span m='3128280'>codes,</span> <span m='3130470'>the</span>
  <span m='3130740'>way</span> <span m='3131440'>that</span> <span m='3131600'>I'm</span>
  <span m='3131750'>going</span> <span m='3131920'>to</span> <span m='3132000'>characterize</span>
  <span m='3132860'>BCH</span> <span m='3133540'>codes</span> <span m='3134460'>is</span>
  <span m='3134820'>as</span> <span m='3135060'>subfield</span> <span m='3135760'>subcodes</span>
  <span m='3136560'>of</span> <span m='3136700'>the</span> <span m='3136800'>Reed-Solomon</span>
  <span m='3137490'>codes.</span> <span m='3139480'>Now,</span> <span m='3139640'>if</span>
  <span m='3139740'>we</span> <span m='3139830'>have</span> <span m='3139950'>a</span>
  <span m='3140730'>Reed-Solomon</span> <span m='3141430'>code</span> <span m='3141830'>over</span>
  <span m='3142860'>F2</span> <span m='3144650'>to the</span> <span m='3144950'>8</span>
  <span m='3145320'>or</span> <span m='3145440'>something,</span> <span m='3147320'>the</span>
  <span m='3147470'>field</span> <span m='3147890'>with</span> <span m='3148090'>256</span>
  <span m='3149160'>elements,</span> <span m='3149680'>or</span> <span m='3149830'>any</span>
  <span m='3151100'>power</span> <span m='3151440'>of</span> <span m='3151540'>2,</span>
  <span m='3152800'>contains</span> <span m='3153410'>a</span> <span m='3153490'>subfield</span>
  <span m='3154200'>which</span> <span m='3154400'>is</span> <span m='3154500'>just</span>
  <span m='3154730'>0</span> <span m='3154930'>and</span> <span m='3155060'>1,</span>
  <span m='3156370'>all</span> <span m='3156440'>right?</span> <span m='3157240'>All</span>
  <span m='3158140'>fields</span> <span m='3158510'>contains</span> <span m='3159010'>0</span>
  <span m='3159120'>and</span> <span m='3159260'>1.</span> <span m='3160760'>If</span>
  <span m='3160920'>the</span> <span m='3161000'>field</span> <span m='3161280'>has</span>
  <span m='3161480'>characteristic</span> <span m='3162230'>2,</span> <span m='3162520'>then</span>
  <span m='3162810'>0 and</span> <span m='3163200'>1</span> <span m='3163500'>all</span>
  <span m='3163710'>by</span> <span m='3163860'>themselves</span> <span m='3164440'>are</span>
  <span m='3164580'>the</span> <span m='3164710'>prime</span> <span m='3165390'>subfield.</span>
  <span m='3167730'>So</span> <span m='3168580'>it's</span> <span m='3168820'>possible</span>
  <span m='3169490'>that there</span> <span m='3169780'>are</span> <span m='3169850'>certain</span>
  <span m='3170240'>words</span> <span m='3171220'>in</span> <span m='3171390'>the</span>
  <span m='3171490'>Reed-Muller</span> <span m='3172090'>code --</span> <span m='3172580'>sorry,</span>
  <span m='3173020'>in the</span> <span m='3173430'>Reed-Solomon</span> <span m='3174130'>code</span>
  <span m='3175220'>that</span> <span m='3175420'>are</span> <span m='3175660'>completely</span>
  <span m='3176630'>made</span> <span m='3176860'>up</span> <span m='3176990'>of</span>
  <span m='3177100'>0's</span> <span m='3177500'>and</span> <span m='3177570'>1's.</span>
  </p><p><span m='3178760'>For</span> <span m='3178870'>instance,</span> <span m='3179160'>the</span>
  <span m='3179290'>all-0</span> <span m='3179800'>word</span> <span m='3180080'>is</span>
  <span m='3180200'>certainly</span> <span m='3180550'>in</span> <span m='3180660'>the</span>
  <span m='3180740'>Reed-Solomon</span> <span m='3181380'>code,</span> <span m='3181820'>so</span>
  <span m='3182780'>we</span> <span m='3182910'>have,</span> <span m='3183090'>at</span>
  <span m='3183170'>least,</span> <span m='3183440'>that</span> <span m='3183660'>one</span>
  <span m='3183860'>that's</span> <span m='3184060'>made</span> <span m='3184260'>up</span>
  <span m='3184380'>of</span> <span m='3184520'>all</span> <span m='3184720'>zeros.</span>
  <span m='3185890'>Almost</span> <span m='3186290'>always,</span> <span m='3186720'>we</span>
  <span m='3186880'>find</span> <span m='3187180'>that</span> <span m='3187360'>the</span>
  <span m='3187520'>all-1</span> <span m='3188020'>word</span> <span m='3188520'>is</span>
  <span m='3188990'>a</span> <span m='3189310'>code</span> <span m='3189580'>word.</span>
  <span m='3190440'>So</span> <span m='3192060'>we</span> <span m='3192550'>have a</span>
  <span m='3192700'>code</span> <span m='3193010'>with all</span> <span m='3193220'>0's</span>
  <span m='3193710'>and all</span> <span m='3193960'>1's.</span> <span m='3194350'>And
  there</span> <span m='3194500'>might</span> <span m='3194680'>be</span> <span m='3194780'>more</span>
  <span m='3195050'>of</span> <span m='3195120'>them.</span> <span m='3196140'>And</span>
  <span m='3196510'>that's</span> <span m='3197630'>actually</span> <span m='3198560'>very</span>
  <span m='3198810'>straightforward,</span> <span m='3199470'>to</span> <span m='3199540'>find</span>
  <span m='3199790'>out</span> <span m='3199920'>how</span> <span m='3200090'>many</span>
  <span m='3202590'>completely</span> <span m='3203050'>binary</span> <span m='3203520'>words</span>
  <span m='3204000'>there</span> <span m='3204230'>are</span> <span m='3204530'>in</span>
  <span m='3204710'>a</span> <span m='3205290'>Reed-Solomon</span> <span m='3205950'>code.</span>
  </p><p><span m='3210080'>So</span> <span m='3211570'>it's</span> <span m='3211820'>the</span>
  <span m='3214290'>binary</span> <span m='3216720'>subfield.</span> <span m='3221950'>We</span>
  <span m='3222140'>have</span> <span m='3222330'>F2</span> <span m='3223240'>is</span>
  <span m='3223550'>a</span> <span m='3223610'>subfield</span> <span m='3224870'>of</span>
  <span m='3225670'>F2</span> <span m='3226760'>to the</span> <span m='3226980'>M</span>
  <span m='3227840'>for</span> <span m='3228030'>all</span> <span m='3228290'>M.</span>
  <span m='3231340'>OK,</span> <span m='3232750'>so</span> <span m='3234560'>a</span>
  <span m='3235080'>subfield</span> <span m='3238570'>subcode,</span> <span m='3241740'>if</span>
  <span m='3241900'>we</span> <span m='3242320'>have</span> <span m='3243075'>an</span>
  <span m='3243410'>n, k, d</span> <span m='3246090'>equals</span> <span m='3246660'>n</span>
  <span m='3246920'>minus</span> <span m='3247360'>k</span> <span m='3247650'>plus</span>
  <span m='3248090'>1</span> <span m='3249230'>Reed-Solomon</span> <span m='3250100'>code,</span>
  <span m='3252650'>then</span> <span m='3255870'>the</span> <span m='3256060'>set</span>
  <span m='3256360'>of</span> <span m='3256470'>all</span> <span m='3258150'>BCH</span>
  <span m='3258960'>code</span> <span m='3263670'>is</span> <span m='3263950'>the</span>
  <span m='3264250'>set</span> <span m='3265022'>of</span> <span m='3265410'>all</span>
  <span m='3267010'>binary</span> <span m='3267660'>code</span> <span m='3267960'>words,</span>
  <span m='3269950'>code</span> <span m='3270190'>words</span> <span m='3271160'>that</span>
  <span m='3271650'>just</span> <span m='3271990'>use</span> <span m='3272310'>the</span>
  <span m='3272390'>0</span> <span m='3272780'>and</span> <span m='3272850'>1</span>
  <span m='3273130'>of</span> <span m='3273250'>the</span> <span m='3273380'>code</span>
  <span m='3273660'>alphabet.</span> <span m='3279160'>Call this</span> <span m='3279520'>c</span>
  <span m='3281060'>in</span> <span m='3281350'>C.</span> <span m='3281860'>So</span>
  <span m='3283200'>we</span> <span m='3283240'>call</span> <span m='3283540'>this</span>
  <span m='3283650'>C</span> <span m='3284050'>prime.</span> </p><p><span m='3288780'>OK,</span>
  <span m='3290130'>so</span> <span m='3290410'>what</span> <span m='3290540'>are</span>
  <span m='3290650'>its</span> <span m='3290830'>parameters</span> <span m='3291440'>going
  to</span> <span m='3291680'>be?</span> <span m='3292350'>Its</span> <span m='3292540'>length</span>
  <span m='3292990'>is</span> <span m='3293830'>still</span> <span m='3294150'>going</span>
  <span m='3294250'>to</span> <span m='3294360'>be</span> <span m='3294470'>n,</span>
  <span m='3295040'>right?</span> <span m='3296600'>All</span> <span m='3297240'>the</span>
  <span m='3298260'>code</span> <span m='3298490'>words</span> <span m='3298740'>here
  are</span> <span m='3299040'>n-tuples,</span> <span m='3299610'>so these</span>
  <span m='3300110'>have got</span> <span m='3300320'>to</span> <span m='3300360'>be</span>
  <span m='3300530'>n-tuples.</span> <span m='3302940'>We</span> <span m='3303100'>don't</span>
  <span m='3303270'>know</span> <span m='3303450'>its</span> <span m='3303640'>dimension.</span>
  <span m='3304230'>Let's</span> <span m='3304580'>just</span> <span m='3304810'>call
  it</span> <span m='3305140'>k</span> <span m='3305380'>prime.</span> <span m='3306110'>That's</span>
  <span m='3306680'>how</span> <span m='3306950'>many</span> <span m='3307230'>such</span>
  <span m='3307650'>code</span> <span m='3308100'>words</span> <span m='3308430'>are</span>
  <span m='3308600'>there?</span> <span m='3308820'>We're</span> <span m='3308920'>going</span>
  <span m='3309060'>to</span> <span m='3309230'>have to do</span> <span m='3309410'>some</span>
  <span m='3310960'>combinatorics</span> <span m='3314190'>to</span> <span m='3314610'>find</span>
  <span m='3314880'>that</span> <span m='3315100'>out.</span> <span m='3317230'>And</span>
  <span m='3317370'>what's</span> <span m='3317600'>the</span> <span m='3317690'>minimum</span>
  <span m='3317960'>distance</span> <span m='3318400'>going</span> <span m='3318590'>to</span>
  <span m='3318780'>be?</span> <span m='3320600'>Anybody?</span> </p><p><span m='3324791'>AUDIENCE:</span>
  <span m='3325264'>[INAUDIBLE].</span> </p><p><span m='3327629'>PROFESSOR:</span>
  <span m='3328110'>In</span> <span m='3328250'>general,</span> <span m='3330080'>well,</span>
  <span m='3330500'>it's</span> <span m='3331090'>certainly</span> <span m='3331790'>not</span>
  <span m='3332080'>going</span> <span m='3332190'>to</span> <span m='3332230'>be</span>
  <span m='3332360'>less</span> <span m='3332790'>than</span> <span m='3336020'>because,</span>
  <span m='3336670'>by</span> <span m='3336850'>definition</span> <span m='3337560'>of
  the</span> <span m='3337640'>minimum</span> <span m='3338090'>distance,</span> <span
  m='3338640'>the</span> <span m='3338720'>minimum</span> <span m='3339080'>Hamming</span>
  <span m='3339460'>distance</span> <span m='3339900'>between</span> <span m='3340210'>any</span>
  <span m='3340800'>two</span> <span m='3341010'>code</span> <span m='3341270'>words</span>
  <span m='3341660'>in</span> <span m='3341820'>this</span> <span m='3341980'>code</span>
  <span m='3343180'>is</span> <span m='3343430'>d,</span> <span m='3344070'>so</span>
  <span m='3344510'>we're</span> <span m='3344690'>just</span> <span m='3344890'>looking</span>
  <span m='3345100'>at</span> <span m='3345160'>a</span> <span m='3345210'>subset</span>
  <span m='3345730'>of</span> <span m='3345810'>the</span> <span m='3345910'>code</span>
  <span m='3346130'>words</span> <span m='3346480'>in</span> <span m='3346590'>this</span>
  <span m='3346990'>code.</span> <span m='3347990'>And</span> <span m='3348590'>the
  minimum</span> <span m='3348990'>squared</span> <span m='3349360'>distance</span>
  <span m='3349790'>has</span> <span m='3350080'>to</span> <span m='3350190'>be</span>
  <span m='3351210'>at</span> <span m='3351320'>least</span> <span m='3351630'>d.</span>
  <span m='3354780'>There's</span> <span m='3354970'>an</span> <span m='3355020'>example</span>
  <span m='3355670'>given</span> <span m='3355980'>in</span> <span m='3356100'>the</span>
  <span m='3356220'>notes.</span> <span m='3356730'>If</span> <span m='3356900'>we</span>
  <span m='3357020'>let</span> <span m='3358240'>c</span> <span m='3358430'>be</span>
  <span m='3359090'>the</span> <span m='3359340'>4,</span> <span m='3360480'>3 --</span>
  <span m='3362420'>I think</span> <span m='3362620'>it's the</span> <span m='3362885'>4,</span>
  <span m='3363570'>2,</span> <span m='3364020'>3,</span> <span m='3365460'>over</span>
  <span m='3366670'>F4,</span> <span m='3369050'>then</span> <span m='3369390'>C</span>
  <span m='3369740'>prime</span> <span m='3370410'>turns</span> <span m='3370800'>out</span>
  <span m='3371010'>to</span> <span m='3371110'>be</span> <span m='3371290'>the</span>
  <span m='3371400'>4,</span> <span m='3372320'>1,</span> <span m='3373360'>4</span>
  <span m='3373850'>code</span> <span m='3374940'>over</span> <span m='3375210'>F2.</span>
  </p><p><span m='3379390'>In</span> <span m='3379550'>other</span> <span m='3379720'>words,</span>
  <span m='3380060'>the</span> <span m='3380230'>only</span> <span m='3380600'>two</span>
  <span m='3380930'>code</span> <span m='3381190'>words</span> <span m='3381580'>in</span>
  <span m='3381780'>this</span> <span m='3381980'>code</span> <span m='3382320'>that
  are</span> <span m='3382520'>all</span> <span m='3382710'>binary</span> <span m='3383190'>are
  the</span> <span m='3383480'>all-0</span> <span m='3384100'>and</span> <span m='3384420'>all-1</span>
  <span m='3385140'>sequences.</span> <span m='3386900'>All</span> <span m='3386980'>right?</span>
  <span m='3387310'>So</span> <span m='3387460'>we</span> <span m='3387590'>actually</span>
  <span m='3388070'>get</span> <span m='3388390'>a</span> <span m='3388540'>minimum</span>
  <span m='3388720'>distance</span> <span m='3389240'>of</span> <span m='3389450'>4.</span>
  <span m='3390720'>It</span> <span m='3390840'>has</span> <span m='3391070'>to</span>
  <span m='3391140'>be</span> <span m='3391290'>at</span> <span m='3391360'>least</span>
  <span m='3391670'>3</span> <span m='3391930'>in</span> <span m='3392050'>this</span>
  <span m='3392250'>particular</span> <span m='3392670'>case,</span> <span m='3393200'>so</span>
  <span m='3393470'>here's</span> <span m='3393770'>an</span> <span m='3393830'>example</span>
  <span m='3394310'>where</span> <span m='3394480'>it</span> <span m='3394550'>could</span>
  <span m='3394710'>be</span> <span m='3394840'>greater</span> <span m='3395880'>than</span>
  <span m='3396030'>3.</span> <span m='3398170'>Or</span> <span m='3398360'>if</span>
  <span m='3398540'>there</span> <span m='3398700'>are</span> <span m='3398770'>cases</span>
  <span m='3399350'>where</span> <span m='3399590'>the</span> <span m='3399730'>subcode</span>
  <span m='3400280'>just</span> <span m='3400500'>consists</span> <span m='3400950'>of
  the</span> <span m='3401270'>all-0</span> <span m='3401600'>word,</span> <span m='3403100'>then
  that,</span> <span m='3403570'>by</span> <span m='3403760'>convention,</span> <span
  m='3404300'>has</span> <span m='3404540'>an</span> <span m='3404630'>infinite</span>
  <span m='3405080'>minimum</span> <span m='3405350'>distance.</span> <span m='3407330'>So</span>
  <span m='3407760'>distance</span> <span m='3408180'>could</span> <span m='3408350'>be</span>
  <span m='3408460'>greater,</span> <span m='3408860'>but</span> <span m='3409000'>it</span>
  <span m='3409140'>never</span> <span m='3409430'>can</span> <span m='3409570'>be</span>
  <span m='3409720'>less</span> <span m='3410730'>than</span> <span m='3411270'>what</span>
  <span m='3411470'>you</span> <span m='3411570'>started</span> <span m='3411980'>with.</span>
  </p><p><span m='3412980'>On</span> <span m='3413340'>the</span> <span m='3413500'>other</span>
  <span m='3413710'>hand,</span> <span m='3414270'>the</span> <span m='3414660'>dimension</span>
  <span m='3415840'>is</span> <span m='3416030'>clearly</span> <span m='3416350'>going</span>
  <span m='3416520'>to</span> <span m='3416580'>go</span> <span m='3416750'>down.</span>
  <span m='3418100'>If</span> <span m='3418320'>it</span> <span m='3418370'>were</span>
  <span m='3418590'>still</span> <span m='3419160'>equal</span> <span m='3419550'>to</span>
  <span m='3419630'>what</span> <span m='3419820'>it</span> <span m='3419900'>was,</span>
  <span m='3420450'>then</span> <span m='3420610'>we'd</span> <span m='3420770'>have</span>
  <span m='3420930'>a</span> <span m='3420980'>binary</span> <span m='3421490'>MDS</span>
  <span m='3422560'>code</span> <span m='3422910'>and we</span> <span m='3423080'>know</span>
  <span m='3423610'>we</span> <span m='3423760'>don't</span> <span m='3423930'>get</span>
  <span m='3424190'>binary</span> <span m='3424680'>MDS</span> <span m='3424860'>codes.</span>
  <span m='3426860'>So</span> <span m='3427340'>in</span> <span m='3427540'>general,</span>
  <span m='3427970'>k</span> <span m='3428200'>prime</span> <span m='3429170'>decreases</span>
  <span m='3429800'>quite</span> <span m='3430060'>a</span> <span m='3430100'>bit.</span>
  <span m='3431230'>In</span> <span m='3431390'>this</span> <span m='3431580'>case,</span>
  <span m='3431880'>it</span> <span m='3431970'>just</span> <span m='3432190'>decreases</span>
  <span m='3432790'>by</span> <span m='3432950'>1.</span> <span m='3434640'>And</span>
  <span m='3434820'>we</span> <span m='3434950'>have</span> <span m='3435140'>to</span>
  <span m='3435250'>find</span> <span m='3435620'>out</span> <span m='3436400'>how</span>
  <span m='3436550'>it</span> <span m='3436680'>decreases.</span> </p><p><span m='3442510'>OK.</span>
  <span m='3442920'>I'm</span> <span m='3443040'>a</span> <span m='3443100'>little</span>
  <span m='3446930'>uncertain</span> <span m='3448980'>as</span> <span m='3449420'>to</span>
  <span m='3450660'>how</span> <span m='3450720'>much</span> <span m='3450940'>of
  the</span> <span m='3451090'>derivation --</span> <span m='3453060'>so</span> <span
  m='3453600'>we</span> <span m='3453880'>need</span> <span m='3454050'>to</span>
  <span m='3454220'>find --</span> </p><p><span m='3457676'>AUDIENCE:</span> <span
  m='3458147'>Is that</span> <span m='3458618'>[INAUDIBLE] at all points of the field,
  is it?</span> </p><p><span m='3468627'>PROFESSOR:</span> <span m='3469650'>No.</span>
  <span m='3471320'>One</span> <span m='3471610'>of</span> <span m='3471700'>the</span>
  <span m='3472800'>characterizations</span> <span m='3473730'>you</span> <span m='3473840'>have</span>
  <span m='3473960'>of</span> <span m='3474080'>Reed-Solomon</span> <span m='3474830'>codes,</span>
  <span m='3476150'>I</span> <span m='3476270'>assume,</span> <span m='3477250'>was</span>
  <span m='3477480'>that</span> <span m='3477590'>they're</span> <span m='3477830'>the</span>
  <span m='3477930'>set</span> <span m='3478270'>of</span> <span m='3478460'>all</span>
  <span m='3480390'>polynomials</span> <span m='3481020'>of</span> <span m='3481140'>length</span>
  <span m='3481470'>n</span> <span m='3482560'>that</span> <span m='3483360'>evaluate</span>
  <span m='3484280'>to</span> <span m='3485130'>0</span> <span m='3485590'>at</span>
  <span m='3485700'>some</span> <span m='3486040'>consecutive</span> <span m='3486750'>set</span>
  <span m='3487060'>of</span> <span m='3487190'>n</span> <span m='3487350'>minus</span>
  <span m='3487790'>k</span> <span m='3490240'>powers</span> <span m='3490670'>of</span>
  <span m='3490760'>alpha.</span> <span m='3492310'>Did</span> <span m='3492470'>you</span>
  <span m='3492590'>see</span> <span m='3492870'>anything</span> <span m='3493180'>like</span>
  <span m='3493400'>that?</span> </p><p><span m='3493690'>AUDIENCE:</span> <span m='3494087'>Yes.</span>
  </p><p><span m='3494881'>PROFESSOR:</span> <span m='3495280'>All</span> <span m='3495370'>right.</span>
  <span m='3496030'>In</span> <span m='3496230'>other words,</span> <span m='3496440'>they're
  --</span> <span m='3498950'>let</span> <span m='3499040'>me</span> <span m='3499120'>write</span>
  <span m='3499340'>that</span> <span m='3499540'>down</span> <span m='3499940'>because</span>
  <span m='3503100'>RS</span> <span m='3503690'>code</span> <span m='3505670'>is</span>
  <span m='3506040'>the</span> <span m='3506150'>set</span> <span m='3506610'>of</span>
  <span m='3506730'>all</span> <span m='3513450'>multiples</span> <span m='3518660'>f
  of x,</span> <span m='3520420'>g of x,</span> <span m='3524690'>of</span> <span
  m='3525150'>degree</span> <span m='3525620'>less</span> <span m='3525990'>than</span>
  <span m='3526090'>n</span> <span m='3530770'>where</span> <span m='3532380'>of</span>
  <span m='3535570'>g of x</span> <span m='3537430'>equals</span> <span m='3537845'>the</span>
  <span m='3538260'>product</span> <span m='3539530'>of</span> <span m='3540110'>x</span>
  <span m='3540510'>minus</span> <span m='3541830'>alpha</span> <span m='3542390'>to</span>
  <span m='3542530'>the</span> <span m='3542720'>i</span> <span m='3543210'>for</span>
  <span m='3544150'>i</span> <span m='3544560'>equals</span> <span m='3545120'>0</span>
  <span m='3545530'>to</span> <span m='3546260'>n</span> <span m='3546410'>minus</span>
  <span m='3546790'>k</span> <span m='3546970'>minus</span> <span m='3547390'>one</span>
  <span m='3547640'>or</span> <span m='3547740'>something</span> <span m='3548070'>like</span>
  <span m='3548270'>that.</span> <span m='3550140'>This</span> <span m='3550730'>is
  called</span> <span m='3550930'>a</span> <span m='3551050'>generator</span> <span
  m='3551640'>polynomial</span> <span m='3553240'>and --</span> <span m='3553870'>so</span>
  <span m='3554200'>what</span> <span m='3554400'>does</span> <span m='3554490'>this</span>
  <span m='3554670'>mean?</span> <span m='3554940'>In other</span> <span m='3555200'>language,</span>
  <span m='3556790'>all</span> <span m='3557070'>polynomials</span> <span m='3557760'>of</span>
  <span m='3557830'>degree</span> <span m='3558150'>less</span> <span m='3558480'>than</span>
  <span m='3558630'>n</span> <span m='3559910'>that</span> <span m='3560140'>have</span>
  <span m='3560340'>roots</span> <span m='3561290'>at</span> <span m='3561820'>1</span>
  <span m='3562320'>alpha,</span> <span m='3562820'>alpha</span> <span m='3563220'>squared,</span>
  <span m='3564320'>or</span> <span m='3564470'>so</span> <span m='3564680'>forth.</span>
  <span m='3566030'>It's</span> <span m='3566500'>better</span> <span m='3566890'>to</span>
  <span m='3567010'>make</span> <span m='3567260'>this</span> <span m='3567640'>i</span>
  <span m='3567870'>equals</span> <span m='3568240'>1</span> <span m='3568600'>to</span>
  <span m='3568690'>n</span> <span m='3568900'>minus</span> <span m='3569350'>k.</span>
  <span m='3570330'>You</span> <span m='3570480'>can also</span> <span m='3571110'>make
  it</span> <span m='3571390'>minus</span> <span m='3571900'>i.</span> <span m='3573170'>There
  are</span> <span m='3573300'>lots</span> <span m='3573630'>of</span> <span m='3574080'>details</span>
  <span m='3574440'>in</span> <span m='3574800'>here.</span> <span m='3576090'>But</span>
  <span m='3576570'>I'll</span> <span m='3576810'>just</span> <span m='3577220'>ask</span>
  <span m='3577540'>you</span> <span m='3577660'>broadly</span> <span m='3578130'>to</span>
  <span m='3578210'>recall</span> <span m='3578700'>that</span> <span m='3578950'>characterization.</span>
  <span m='3580570'>This</span> <span m='3580800'>is</span> <span m='3580990'>a --</span>
  </p><p><span m='3581270'>AUDIENCE:</span> <span m='3581729'>I</span> <span m='3582188'>have</span>
  <span m='3582647'>another</span> <span m='3583106'>question.</span> <span m='3584024'>[INAUDIBLE]</span>
  <span m='3584483'>are not</span> <span m='3584942'>linear?</span> </p><p><span m='3586319'>PROFESSOR:</span>
  <span m='3586780'>OK,</span> <span m='3587520'>let's</span> <span m='3588010'>ask
  that.</span> <span m='3590880'>So</span> <span m='3591250'>we've</span> <span m='3591470'>got</span>
  <span m='3592460'>a</span> <span m='3592550'>set</span> <span m='3592950'>of</span>
  <span m='3593140'>binary</span> <span m='3593520'>n-tuples,</span> <span m='3597110'>OK,</span>
  <span m='3598340'>defined</span> <span m='3599280'>as</span> <span m='3599490'>the</span>
  <span m='3599610'>subset.</span> <span m='3601160'>So</span> <span m='3601350'>what</span>
  <span m='3601500'>do we</span> <span m='3601620'>need</span> <span m='3601840'>to
  do to</span> <span m='3602280'>see</span> <span m='3602510'>whether</span> <span
  m='3602720'>it's</span> <span m='3602870'>linear</span> <span m='3603300'>or</span>
  <span m='3603340'>not?</span> </p><p><span m='3603560'>AUDIENCE:</span> <span m='3604514'>[INAUDIBLE].</span>
  </p><p><span m='3606422'>PROFESSOR:</span> <span m='3606900'>We just</span> <span
  m='3607220'>check</span> <span m='3607480'>the</span> <span m='3607550'>group</span>
  <span m='3607820'>property.</span> <span m='3608320'>Is it</span> <span m='3608640'>closed</span>
  <span m='3609100'>under</span> <span m='3609320'>addition?</span> <span m='3611710'>Suppose</span>
  <span m='3612100'>we</span> <span m='3612240'>take</span> <span m='3612520'>two</span>
  <span m='3612670'>of</span> <span m='3612780'>these</span> <span m='3613050'>code</span>
  <span m='3613280'>words</span> <span m='3613650'>we</span> <span m='3613840'>add</span>
  <span m='3614000'>them</span> <span m='3614150'>together,</span> <span m='3615980'>component-wise,</span>
  <span m='3616970'>vector</span> <span m='3617280'>form.</span> <span m='3620360'>Seems</span>
  <span m='3620720'>to</span> <span m='3620820'>me</span> <span m='3621390'>we</span>
  <span m='3621540'>get</span> <span m='3623020'>A,</span> <span m='3624710'>that</span>
  <span m='3624930'>gives</span> <span m='3625160'>us</span> <span m='3625310'>another</span>
  <span m='3625640'>code</span> <span m='3625870'>word in the</span> <span m='3626170'>Reed-Solomon</span>
  <span m='3626870'>code</span> <span m='3627190'>because</span> <span m='3627510'>it's</span>
  <span m='3627720'>closed</span> <span m='3628140'>under</span> <span m='3628420'>addition,</span>
  <span m='3629500'>and</span> <span m='3629700'>B,</span> <span m='3630710'>by</span>
  <span m='3630980'>the</span> <span m='3631340'>addition</span> <span m='3631680'>rules,</span>
  <span m='3632610'>it's</span> <span m='3633120'>going</span> <span m='3633240'>to</span>
  <span m='3633360'>be</span> <span m='3633460'>another</span> <span m='3633690'>binary</span>
  <span m='3634070'>code</span> <span m='3634300'>word,</span> <span m='3635650'>all</span>
  <span m='3635780'>right?</span> <span m='3637950'>So</span> <span m='3638350'>it's</span>
  <span m='3638520'>another</span> <span m='3638810'>binary</span> <span m='3639200'>code</span>
  <span m='3639450'>word in</span> <span m='3639570'>the</span> <span m='3639740'>RS</span>
  <span m='3640140'>code,</span> <span m='3640450'>therefore,</span> <span m='3640820'>it's</span>
  <span m='3641050'>in C</span> <span m='3641280'>prime.</span> <span m='3642230'>So</span>
  <span m='3642630'>that's</span> <span m='3643400'>proof</span> <span m='3643790'>that,</span>
  <span m='3643950'>in</span> <span m='3644080'>fact,</span> <span m='3644420'>this</span>
  <span m='3644630'>code</span> <span m='3644840'>is</span> <span m='3645010'>linear.</span>
  </p><p><span m='3645670'>AUDIENCE:</span> <span m='3646170'>What</span> <span m='3646610'>about</span>
  <span m='3647050'>[INAUDIBLE]?</span> </p><p><span m='3649250'>PROFESSOR:</span>
  <span m='3649690'>That's</span> <span m='3649950'>trivial.</span> <span m='3650620'>For</span>
  <span m='3650690'>a</span> <span m='3650770'>binary</span> <span m='3651230'>code,</span>
  <span m='3651800'>we</span> <span m='3652020'>only</span> <span m='3652180'>have</span>
  <span m='3652310'>to</span> <span m='3652650'>consider</span> <span m='3653020'>two</span>
  <span m='3653190'>scalars,</span> <span m='3653670'>0</span> <span m='3654040'>and</span>
  <span m='3654110'>1.</span> </p><p><span m='3654610'>AUDIENCE:</span> <span m='3655057'>[INAUDIBLE]?</span>
  </p><p><span m='3658186'>PROFESSOR:</span> <span m='3658640'>But now</span> <span
  m='3658960'>I'm</span> <span m='3659220'>asking</span> <span m='3659590'>whether</span>
  <span m='3659890'>this</span> <span m='3660160'>binary</span> <span m='3660620'>code</span>
  <span m='3660920'>is</span> <span m='3661080'>linear.</span> <span m='3664060'>There's
  the</span> <span m='3664270'>code</span> <span m='3664640'>over</span> <span m='3664910'>F2.</span>
  <span m='3668418'>Yes?</span> <span m='3668901'>You had a --</span> </p><p><span
  m='3669867'>AUDIENCE:</span> <span m='3670350'>Same</span> <span m='3670840'>question.</span>
  <span m='3671450'>The</span> <span m='3671680'>base</span> <span m='3672070'>field</span>
  <span m='3672390'>is</span> <span m='3672950'>F2</span> <span m='3673390'>to the
  x,</span> <span m='3673670'>so if you</span> <span m='3673950'>add 1</span> <span
  m='3674320'>and 1 there,</span> <span m='3676260'>it</span> <span m='3676380'>wouldn't</span>
  <span m='3676780'>be</span> <span m='3676930'>just</span> <span m='3677150'>0.</span>
  <span m='3677740'>But</span> <span m='3678390'>I</span> <span m='3678440'>guess</span>
  <span m='3678760'>if you</span> <span m='3679210'>restrict</span> <span m='3679550'>the</span>
  <span m='3679845'>field to</span> <span m='3680140'>F2,</span> <span m='3681406'>you
  have</span> <span m='3681894'>to check</span> <span m='3682382'>everything</span>
  <span m='3682870'>again,</span> <span m='3683360'>don't you?</span> </p><p><span
  m='3683745'>PROFESSOR:</span> <span m='3684130'>No,</span> <span m='3685510'>because</span>
  <span m='3686040'>we</span> <span m='3686170'>said</span> <span m='3686420'>F2</span>
  <span m='3686830'>is</span> <span m='3686980'>the</span> <span m='3687060'>subfield</span>
  <span m='3687850'>of</span> <span m='3689280'>F2</span> <span m='3689450'>to</span>
  <span m='3689710'>the</span> <span m='3689870'>M.</span> <span m='3690910'>And</span>
  <span m='3691230'>what</span> <span m='3691400'>we</span> <span m='3691560'>actually</span>
  <span m='3691860'>showed</span> <span m='3692900'>was</span> <span m='3693120'>that</span>
  <span m='3693770'>if</span> <span m='3693910'>you</span> <span m='3694030'>just</span>
  <span m='3694230'>stay</span> <span m='3694480'>in</span> <span m='3694610'>the</span>
  <span m='3694690'>prime</span> <span m='3695020'>field,</span> <span m='3695320'>the</span>
  <span m='3695620'>integers</span> <span m='3696190'>of</span> <span m='3696270'>the</span>
  <span m='3696340'>field,</span> <span m='3697330'>then</span> <span m='3699520'>you</span>
  <span m='3699680'>get</span> <span m='3699850'>exactly</span> <span m='3700250'>the</span>
  <span m='3700310'>same</span> <span m='3700580'>addition and</span> <span m='3701000'>multiplication</span>
  <span m='3701660'>rules</span> <span m='3702470'>as</span> <span m='3702660'>you</span>
  <span m='3702810'>do</span> <span m='3704440'>in</span> <span m='3704590'>the</span>
  <span m='3704680'>prime</span> <span m='3704970'>field.</span> <span m='3706400'>So</span>
  <span m='3706870'>in</span> <span m='3707120'>fact,</span> <span m='3707630'>in</span>
  <span m='3707760'>a</span> <span m='3707820'>field</span> <span m='3708140'>of</span>
  <span m='3708230'>characteristic</span> <span m='3708960'>2,</span> <span m='3710060'>we</span>
  <span m='3710280'>always</span> <span m='3710570'>have</span> <span m='3711130'>0</span>
  <span m='3711530'>plus</span> <span m='3711840'>1</span> <span m='3712120'>is</span>
  <span m='3712300'>1,</span> <span m='3712750'>0</span> <span m='3713080'>plus</span>
  <span m='3713780'>1</span> <span m='3714010'>plus</span> <span m='3714230'>0</span>
  <span m='3714540'>is</span> <span m='3714650'>1,</span> <span m='3714970'>1</span>
  <span m='3715240'>plus</span> <span m='3715480'>1</span> <span m='3715690'>is</span>
  <span m='3715810'>0.</span> <span m='3717710'>That</span> <span m='3717910'>last</span>
  <span m='3718110'>one is</span> <span m='3718350'>the only</span> <span m='3718520'>one</span>
  <span m='3718670'>you</span> <span m='3718780'>really</span> <span m='3719010'>have
  to</span> <span m='3719240'>check.</span> <span m='3721600'>So</span> <span m='3722690'>that</span>
  <span m='3723230'>accounts</span> <span m='3723680'>for</span> <span m='3723780'>the</span>
  <span m='3723860'>definition</span> <span m='3724155'>of</span> <span m='3724450'>characteristic,</span>
  <span m='3725840'>and</span> <span m='3726080'>that's</span> <span m='3726540'>the</span>
  <span m='3726650'>reason</span> <span m='3727190'>we</span> <span m='3727390'>can</span>
  <span m='3727560'>always</span> <span m='3727790'>use</span> <span m='3728100'>just</span>
  <span m='3728360'>plus</span> <span m='3728600'>signs,</span> <span m='3729750'>because</span>
  <span m='3730320'>subtraction</span> <span m='3730940'>is</span> <span m='3731090'>the</span>
  <span m='3731170'>same</span> <span m='3731460'>as</span> <span m='3731580'>addition.</span>
  </p><p><span m='3731890'>AUDIENCE:</span> <span m='3732200'>[INAUDIBLE]?</span>
  </p><p><span m='3736128'>PROFESSOR:</span> <span m='3736620'>Yeah.</span> <span
  m='3737810'>We</span> <span m='3737960'>showed --</span> <span m='3741480'>well,</span>
  <span m='3743230'>very</span> <span m='3743550'>simple</span> <span m='3743970'>proof.</span>
  <span m='3748290'>The</span> <span m='3748430'>order</span> <span m='3748650'>of
  a</span> <span m='3748700'>subgroup</span> <span m='3749230'>has</span> <span m='3749480'>to</span>
  <span m='3749590'>define</span> <span m='3750570'>the</span> <span m='3750700'>order</span>
  <span m='3750900'>of</span> <span m='3750940'>the</span> <span m='3751020'>group</span>
  <span m='3751290'>it's</span> <span m='3751460'>in.</span> <span m='3752420'>The</span>
  <span m='3752530'>additive</span> <span m='3752810'>group</span> <span m='3753180'>of</span>
  <span m='3753260'>the</span> <span m='3753350'>prime</span> <span m='3753680'>field</span>
  <span m='3754080'>has</span> <span m='3754510'>order</span> <span m='3755150'>2
  to</span> <span m='3755390'>the</span> <span m='3755570'>M,</span> <span m='3756320'>so</span>
  <span m='3756540'>it</span> <span m='3756720'>has to be</span> <span m='3756900'>some</span>
  <span m='3757160'>divisor</span> <span m='3757600'>of</span> <span m='3757730'>2
  to the</span> <span m='3758130'>M,</span> <span m='3758300'>which</span> <span m='3758480'>is</span>
  <span m='3758590'>a</span> <span m='3758650'>prime.</span> <span m='3763740'>I</span>
  <span m='3763880'>think</span> <span m='3764180'>we</span> <span m='3764370'>proved</span>
  <span m='3764740'>that</span> <span m='3764920'>another</span> <span m='3765280'>way,</span>
  <span m='3765460'>but</span> <span m='3765660'>that's</span> <span m='3765930'>a</span>
  <span m='3766030'>very</span> <span m='3766230'>simple</span> <span m='3766690'>proof.</span>
  <span m='3769330'>OK,</span> <span m='3769890'>great</span> <span m='3770230'>questions,</span>
  <span m='3770770'>because</span> <span m='3770990'>it</span> <span m='3771080'>shows</span>
  <span m='3772820'>you're</span> <span m='3772980'>thinking</span> <span m='3773400'>about</span>
  <span m='3774350'>how</span> <span m='3774630'>this</span> <span m='3774820'>relates</span>
  <span m='3775270'>to</span> <span m='3775370'>what</span> <span m='3775520'>you</span>
  <span m='3775630'>learned</span> <span m='3775870'>back</span> <span m='3776170'>in</span>
  <span m='3776250'>chapter</span> <span m='3776710'>seven.</span> <span m='3777210'>But</span>
  <span m='3777570'>at</span> <span m='3777750'>this</span> <span m='3777970'>point</span>
  <span m='3778350'>you've</span> <span m='3778690'>kind</span> <span m='3778970'>of</span>
  <span m='3779470'>got a little</span> <span m='3779800'>vague</span> <span m='3780160'>about</span>
  <span m='3780420'>chapter</span> <span m='3780830'>seven,</span> <span m='3781220'>what's</span>
  <span m='3781490'>really</span> <span m='3781720'>in</span> <span m='3781870'>there.</span>
  <span m='3782810'>By</span> <span m='3783480'>Wednesday,</span> <span m='3784060'>you're</span>
  <span m='3784280'>really</span> <span m='3784500'>going</span> <span m='3784690'>to
  know</span> <span m='3784820'>chapter</span> <span m='3785180'>seven</span> <span
  m='3785490'>well.</span> <span m='3785900'>Let me</span> <span m='3786170'>tell
  you.</span> <span m='3791240'>OK.</span> <span m='3792640'>Good.</span> <span m='3794370'>Thank</span>
  <span m='3794620'>you</span> <span m='3794720'>for</span> <span m='3794850'>the</span>
  <span m='3794950'>help.</span> <span m='3796290'>Because</span> <span m='3796890'>these</span>
  <span m='3797150'>are</span> <span m='3797240'>all</span> <span m='3797440'>things</span>
  <span m='3797730'>that</span> <span m='3797860'>I</span> <span m='3797940'>should</span>
  <span m='3798130'>have</span> <span m='3798250'>just</span> <span m='3798400'>said</span>
  <span m='3798680'>up</span> <span m='3798850'>here,</span> <span m='3799435'>but</span>
  <span m='3799760'>they</span> <span m='3799910'>come</span> <span m='3800110'>out
  much</span> <span m='3800330'>better,</span> <span m='3800620'>actually,</span>
  <span m='3801000'>if</span> <span m='3801160'>they</span> <span m='3801290'>come</span>
  <span m='3801490'>out</span> <span m='3801640'>in</span> <span m='3801710'>response</span>
  <span m='3802220'>to</span> <span m='3802330'>questions.</span> <span m='3806190'>OK.</span>
  </p><p><span m='3809650'>So</span> <span m='3812280'>here's</span> <span m='3812620'>one</span>
  <span m='3812930'>characterization</span> <span m='3814020'>of</span> <span m='3815900'>a</span>
  <span m='3815920'>Reed-Solomon</span> <span m='3816460'>code</span> <span m='3816800'>which</span>
  <span m='3816990'>apparently</span> <span m='3817460'>you</span> <span m='3817560'>did</span>
  <span m='3817820'>see.</span> <span m='3818290'>It's</span> <span m='3818890'>the</span>
  <span m='3819000'>set</span> <span m='3819240'>of</span> <span m='3819320'>all</span>
  <span m='3819520'>multiples</span> <span m='3820040'>of</span> <span m='3820120'>some</span>
  <span m='3820360'>generator</span> <span m='3820820'>polynomial.</span> <span m='3821430'>The</span>
  <span m='3821530'>generator</span> <span m='3822010'>polynomial</span> <span m='3823160'>is</span>
  <span m='3823380'>described</span> <span m='3824040'>as</span> <span m='3824240'>this</span>
  <span m='3824410'>polynomial</span> <span m='3825200'>of</span> <span m='3825600'>degree</span>
  <span m='3826600'>n</span> <span m='3826810'>minus</span> <span m='3827190'>k</span>
  <span m='3829820'>whose</span> <span m='3830690'>roots</span> <span m='3831160'>are</span>
  <span m='3831470'>precisely</span> <span m='3832630'>alpha</span> <span m='3832960'>up</span>
  <span m='3833290'>through</span> <span m='3833620'>alpha</span> <span m='3833990'>to</span>
  <span m='3834100'>the</span> <span m='3834240'>n</span> <span m='3834380'>minus</span>
  <span m='3834730'>k.</span> <span m='3835300'>You</span> <span m='3835410'>did</span>
  <span m='3835590'>say</span> <span m='3835790'>that?</span> <span m='3836890'>OK.</span>
  <span m='3840960'>So</span> <span m='3846240'>similarly,</span> <span m='3846705'>the</span>
  <span m='3847170'>BCH</span> <span m='3848430'>code --</span> <span m='3850460'>I'm</span>
  <span m='3850690'>just</span> <span m='3850920'>going</span> <span m='3851000'>to</span>
  <span m='3851080'>assert</span> <span m='3851580'>this</span> <span m='3851980'>just</span>
  <span m='3852210'>to</span> <span m='3852300'>show</span> <span m='3852510'>you</span>
  <span m='3852700'>how</span> <span m='3852840'>it</span> <span m='3853010'>goes.</span>
  <span m='3854030'>It's</span> <span m='3854250'>the</span> <span m='3854350'>set</span>
  <span m='3854970'>of</span> <span m='3855140'>all</span> <span m='3856470'>multiples</span>
  <span m='3861400'>of</span> <span m='3863700'>g</span> <span m='3864070'>prime</span>
  <span m='3864630'>of</span> <span m='3864890'>x,</span> <span m='3866390'>which</span>
  <span m='3866730'>is</span> <span m='3867120'>the</span> <span m='3867550'>minimal</span>
  <span m='3869100'>degree</span> <span m='3874780'>binary</span> <span m='3875440'>polynomial</span>
  <span m='3887590'>with</span> <span m='3889530'>the</span> <span m='3890010'>same</span>
  <span m='3890330'>roots.</span> <span m='3895810'>Now,</span> <span m='3896030'>how</span>
  <span m='3896300'>can</span> <span m='3896500'>a</span> <span m='3896700'>binary</span>
  <span m='3897260'>polynomial --</span> <span m='3901940'>alpha</span> <span m='3902540'>to</span>
  <span m='3902790'>the</span> <span m='3903080'>n</span> <span m='3903530'>minus</span>
  <span m='3903960'>k.</span> </p><p><span m='3906158'>How can</span> <span m='3906650'>a</span>
  <span m='3906830'>binary</span> <span m='3907380'>polynomial</span> <span m='3908020'>have</span>
  <span m='3908240'>non-binary</span> <span m='3908980'>roots?</span> <span m='3912720'>Well,</span>
  <span m='3913185'>it</span> <span m='3913650'>clearly</span> <span m='3914030'>can.</span>
  <span m='3915290'>Let's</span> <span m='3915680'>consider</span> <span m='3917210'>g</span>
  <span m='3917500'>of</span> <span m='3917740'>prime</span> <span m='3918045'>of</span>
  <span m='3918350'>x.</span> <span m='3921260'>It's</span> <span m='3921510'>an</span>
  <span m='3921570'>element</span> <span m='3923290'>of</span> <span m='3925200'>F2</span>
  <span m='3926690'>to the</span> <span m='3927080'>x,</span> <span m='3927370'>the</span>
  <span m='3927450'>set</span> <span m='3927720'>of</span> <span m='3927830'>all</span>
  <span m='3928360'>polynomials</span> <span m='3929030'>over</span> <span m='3929500'>F2,</span>
  <span m='3930250'>which</span> <span m='3930760'>is</span> <span m='3930890'>a</span>
  <span m='3930960'>subset</span> <span m='3932440'>of</span> <span m='3932640'>the</span>
  <span m='3932770'>set</span> <span m='3933180'>of</span> <span m='3933380'>all</span>
  <span m='3936950'>polynomials</span> <span m='3937550'>over</span> <span m='3937720'>2</span>
  <span m='3937910'>to</span> <span m='3937970'>the</span> <span m='3938110'>M</span>
  <span m='3938380'>for</span> <span m='3938480'>the</span> <span m='3938590'>same</span>
  <span m='3938880'>reason.</span> <span m='3939390'>F2</span> <span m='3939860'>is</span>
  <span m='3940040'>the</span> <span m='3940110'>subfield</span> <span m='3940770'>of</span>
  <span m='3941950'>F2</span> <span m='3942200'>to the</span> <span m='3942350'>M,</span>
  <span m='3942580'>so</span> <span m='3942810'>some</span> <span m='3943280'>of</span>
  <span m='3943480'>the</span> <span m='3943600'>polynomials</span> <span m='3944640'>over</span>
  <span m='3944980'>F2</span> <span m='3945130'>to</span> <span m='3945390'>the M</span>
  <span m='3945810'>have</span> <span m='3946000'>purely</span> <span m='3946800'>binary</span>
  <span m='3947250'>coefficients,</span> <span m='3948230'>all right?</span> <span
  m='3949040'>So</span> <span m='3949750'>that's</span> <span m='3950060'>the</span>
  <span m='3950160'>sense --</span> <span m='3951950'>that's</span> <span m='3952120'>how</span>
  <span m='3952230'>we</span> <span m='3952360'>can</span> <span m='3952550'>get</span>
  <span m='3952880'>between</span> <span m='3953820'>these</span> <span m='3954090'>two</span>
  <span m='3954290'>things.</span> </p><p><span m='3965260'>So</span> <span m='3965630'>some</span>
  <span m='3965940'>binary</span> <span m='3966370'>polynomials</span> <span m='3968840'>have</span>
  <span m='3969060'>roots</span> <span m='3969490'>in</span> <span m='3970210'>GF</span>
  <span m='3970680'>of 2</span> <span m='3970980'>the</span> <span m='3971170'>M</span>
  <span m='3972660'>let</span> <span m='3972890'>me</span> <span m='3973030'>give</span>
  <span m='3973210'>you</span> <span m='3973570'>an</span> <span m='3973690'>example.</span>
  <span m='3976890'>Let's</span> <span m='3977240'>consider</span> <span m='3978390'>x</span>
  <span m='3978680'>squared</span> <span m='3979240'>plus</span> <span m='3979570'>x</span>
  <span m='3980260'>plus</span> <span m='3980610'>1</span> <span m='3983190'>as</span>
  <span m='3983860'>a</span> <span m='3984060'>polynomial</span> <span m='3987380'>in</span>
  <span m='3989390'>F4</span> <span m='3989860'>of</span> <span m='3989990'>x,</span>
  <span m='3993870'>which</span> <span m='3994090'>is</span> <span m='3994160'>certainly</span>
  <span m='3994590'>is.</span> <span m='3997320'>It's</span> <span m='3997780'>a</span>
  <span m='3997830'>polynomial</span> <span m='3998460'>of degree</span> <span m='3998730'>2</span>
  <span m='3999220'>and</span> <span m='3999680'>F4</span> <span m='4000060'>of</span>
  <span m='4000150'>x.</span> <span m='4002740'>What</span> <span m='4003010'>are</span>
  <span m='4003410'>its</span> <span m='4003820'>roots</span> <span m='4004370'>in</span>
  <span m='4004780'>F4</span> <span m='4005350'>of</span> <span m='4005460'>x?</span>
  <span m='4005740'>Does it</span> <span m='4006040'>have</span> <span m='4006230'>any</span>
  <span m='4006370'>roots</span> <span m='4006830'>in</span> <span m='4007290'>F4
  of x?</span> <span m='4008890'>Does it</span> <span m='4009150'>have</span> <span
  m='4009300'>any</span> <span m='4009450'>roots</span> <span m='4009900'>in</span>
  <span m='4010310'>F2 --</span> <span m='4011890'>sorry,</span> <span m='4014280'>I'm</span>
  <span m='4014470'>asking</span> <span m='4014820'>whether</span> <span m='4014950'>it
  has</span> <span m='4015200'>any</span> <span m='4015300'>roots</span> <span m='4015780'>in
  F4.</span> <span m='4016270'>Now</span> <span m='4016550'>I</span> <span m='4016740'>step</span>
  <span m='4017060'>back</span> <span m='4017370'>and</span> <span m='4017440'>ask</span>
  <span m='4017740'>if</span> <span m='4017900'>it</span> <span m='4018060'>has</span>
  <span m='4018220'>any</span> <span m='4018310'>roots</span> <span m='4018660'>in</span>
  <span m='4018740'>F2.</span> <span m='4020230'>So</span> <span m='4020450'>how</span>
  <span m='4020650'>do</span> <span m='4020720'>we</span> <span m='4020840'>do</span>
  <span m='4021050'>that?</span> <span m='4021320'>We</span> <span m='4021430'>just</span>
  <span m='4021690'>ask</span> <span m='4022100'>if</span> <span m='4023162'>F of</span>
  <span m='4023530'>x</span> <span m='4023850'>is</span> <span m='4024130'>0</span>
  <span m='4024650'>for</span> <span m='4026440'>x</span> <span m='4026720'>equals</span>
  <span m='4027070'>0.</span> <span m='4028150'>We</span> <span m='4028440'>get</span>
  <span m='4028570'>1.</span> <span m='4029080'>So</span> <span m='4029380'>it's</span>
  <span m='4029550'>not</span> <span m='4029670'>a</span> <span m='4029800'>root</span>
  <span m='4030495'>of</span> <span m='4030790'>0.</span> <span m='4032680'>Substitute</span>
  <span m='4033170'>1,</span> <span m='4033550'>we</span> <span m='4033650'>get</span>
  <span m='4033770'>1</span> <span m='4034030'>plus</span> <span m='4034260'>1</span>
  <span m='4034470'>plus</span> <span m='4034740'>1.</span> <span m='4035610'>1</span>
  <span m='4035910'>is</span> <span m='4036080'>not</span> <span m='4036210'>a</span>
  <span m='4036340'>root</span> <span m='4036630'>F</span> <span m='4037040'>of</span>
  <span m='4037220'>x.</span> </p><p><span m='4039340'>All</span> <span m='4039490'>right.</span>
  <span m='4040000'>Well,</span> <span m='4040260'>we</span> <span m='4040350'>have</span>
  <span m='4040500'>two</span> <span m='4040660'>more</span> <span m='4040900'>candidates.</span>
  <span m='4041620'>How about</span> <span m='4041970'>alpha?</span> <span m='4043416'>For</span>
  <span m='4043900'>alpha,</span> <span m='4045440'>we</span> <span m='4045560'>get</span>
  <span m='4045800'>F</span> <span m='4046090'>of</span> <span m='4046950'>alpha</span>
  <span m='4047640'>equals</span> <span m='4048530'>alpha</span> <span m='4048590'>squared</span>
  <span m='4049150'>plus</span> <span m='4049490'>alpha</span> <span m='4050420'>plus</span>
  <span m='4050780'>1.</span> <span m='4052700'>And</span> <span m='4052820'>if</span>
  <span m='4052930'>you</span> <span m='4053060'>remember</span> <span m='4053400'>the</span>
  <span m='4053540'>addition</span> <span m='4053970'>table</span> <span m='4054870'>of</span>
  <span m='4054990'>F4,</span> <span m='4057160'>however</span> <span m='4057580'>it's</span>
  <span m='4057750'>constructed,</span> <span m='4058600'>this</span> <span m='4058830'>equals</span>
  <span m='4059170'>0,</span> <span m='4061810'>OK?</span> <span m='4070850'>0,</span>
  <span m='4071265'>1,</span> <span m='4071680'>alpha,</span> <span m='4072150'>alpha,</span>
  <span m='4072530'>squared.</span> <span m='4072925'>0,</span> <span m='4073320'>1</span>
  <span m='4073840'>alpha,</span> <span m='4074233'>alpha</span> <span m='4075020'>squared.</span>
  <span m='4075370'>0,</span> <span m='4076910'>1,</span> <span m='4077175'>alpha,</span>
  <span m='4077440'>alpha,</span> <span m='4078440'>squared.</span> <span m='4079040'>This</span>
  <span m='4079320'>is</span> <span m='4079600'>plus.</span> <span m='4080706'>1,</span>
  <span m='4081560'>alpha,</span> <span m='4081880'>alpha,</span> <span m='4082530'>squared.</span>
  <span m='4083190'>0,</span> <span m='4084480'>1</span> <span m='4084770'>plus</span>
  <span m='4084960'>alpha</span> <span m='4085370'>is</span> <span m='4085690'>alpha</span>
  <span m='4086030'>squared.</span> <span m='4086850'>1</span> <span m='4087060'>plus</span>
  <span m='4087570'>alpha</span> <span m='4087630'>squared</span> <span m='4088010'>is</span>
  <span m='4088170'>alpha.</span> <span m='4089090'>Any</span> <span m='4089300'>of</span>
  <span m='4089360'>these</span> <span m='4089640'>is</span> <span m='4089770'>telling</span>
  <span m='4090080'>you</span> <span m='4090410'>the</span> <span m='4090510'>same</span>
  <span m='4090800'>thing.</span> <span m='4092130'>0,</span> <span m='4092430'>1,</span>
  <span m='4093200'>0,</span> <span m='4093300'>1</span> <span m='4093860'>alpha,</span>
  <span m='4094347'>squared</span> <span m='4094834'>alpha.</span> </p><p><span m='4095810'>So</span>
  <span m='4096109'>we</span> <span m='4096210'>conclude</span> <span m='4096520'>from</span>
  <span m='4096830'>that</span> <span m='4097050'>that</span> <span m='4097270'>1</span>
  <span m='4097569'>plus</span> <span m='4098149'>1</span> <span m='4098529'>plus</span>
  <span m='4098939'>alpha,</span> <span m='4099439'>which</span> <span m='4099660'>is</span>
  <span m='4099819'>alpha</span> <span m='4100140'>squared,</span> <span m='4100830'>plus</span>
  <span m='4101140'>alpha</span> <span m='4101439'>squared</span> <span m='4101810'>is</span>
  <span m='4101930'>0.</span> <span m='4107609'>So</span> <span m='4108100'>alpha</span>
  <span m='4108710'>is,</span> <span m='4109029'>in</span> <span m='4109160'>fact,</span>
  <span m='4109500'>a</span> <span m='4109590'>root</span> <span m='4109939'>of</span>
  <span m='4110050'>this.</span> <span m='4112020'>And</span> <span m='4113910'>what</span>
  <span m='4114130'>about</span> <span m='4114470'>F</span> <span m='4114710'>of</span>
  <span m='4114859'>alpha</span> <span m='4115220'>squared?</span> <span m='4116859'>Alpha</span>
  <span m='4117160'>squared</span> <span m='4118370'>squared</span> <span m='4119080'>is</span>
  <span m='4119210'>alpha</span> <span m='4119580'>fourth,</span> <span m='4120170'>but</span>
  <span m='4120819'>we</span> <span m='4120939'>can</span> <span m='4121100'>reduce</span>
  <span m='4121520'>that</span> <span m='4121790'>mod</span> <span m='4122170'>3 --</span>
  <span m='4124229'>the</span> <span m='4124380'>exponent</span> <span m='4124910'>mod</span>
  <span m='4125100'>3.</span> <span m='4125520'>So</span> <span m='4125700'>this</span>
  <span m='4125859'>is</span> <span m='4126029'>alpha</span> <span m='4126779'>plus</span>
  <span m='4127180'>alpha</span> <span m='4127540'>squared</span> <span m='4128960'>plus</span>
  <span m='4129290'>1</span> <span m='4129574'>and</span> <span m='4129859'>that</span>
  <span m='4130149'>is</span> <span m='4130350'>equal</span> <span m='4130630'>to</span>
  <span m='4130680'>0.</span> <span m='4131050'>So</span> <span m='4131410'>alpha</span>
  <span m='4131790'>and</span> <span m='4131890'>alpha</span> <span m='4132260'>squared</span>
  <span m='4133200'>are</span> <span m='4133359'>roots</span> <span m='4135760'>of</span>
  <span m='4135960'>this</span> <span m='4136170'>polynomial.</span> </p><p><span
  m='4145910'>There's</span> <span m='4146160'>a</span> <span m='4146229'>lovely</span>
  <span m='4147990'>fact</span> <span m='4151700'>proved</span> <span m='4152240'>in</span>
  <span m='4152350'>the</span> <span m='4152470'>notes,</span> <span m='4155140'>which</span>
  <span m='4155490'>is</span> <span m='4155779'>that</span> <span m='4168859'>every</span>
  <span m='4171180'>element</span> <span m='4175460'>of --</span> <span m='4177800'>facts.</span>
  <span m='4178479'>Every</span> <span m='4178850'>element</span> <span m='4179649'>of</span>
  <span m='4180590'>F2</span> <span m='4181189'>to</span> <span m='4181560'>the</span>
  <span m='4181790'>M</span> <span m='4186380'>is</span> <span m='4187029'>a</span>
  <span m='4188350'>root</span> <span m='4189390'>of</span> <span m='4191109'>x 2</span>
  <span m='4192660'>to</span> <span m='4192970'>the</span> <span m='4193310'>M</span>
  <span m='4193729'>plus</span> <span m='4194340'>x.</span> </p><p><span m='4201330'>OK,</span>
  <span m='4201700'>did</span> <span m='4201860'>you</span> <span m='4201980'>see</span>
  <span m='4202160'>something</span> <span m='4202460'>like</span> <span m='4202650'>this</span>
  <span m='4202890'>last</span> <span m='4203190'>time?</span> <span m='4203490'>I</span>
  <span m='4203550'>see</span> <span m='4203750'>some</span> <span m='4203930'>shaking</span>
  <span m='4204600'>of</span> <span m='4204770'>heads.</span> <span m='4210010'>OK.</span>
  <span m='4213210'>And</span> <span m='4215630'>how</span> <span m='4215780'>many</span>
  <span m='4215930'>roots</span> <span m='4216230'>could</span> <span m='4216370'>there</span>
  <span m='4216490'>possibly</span> <span m='4216970'>be</span> <span m='4217230'>of</span>
  <span m='4217340'>x</span> <span m='4217560'>2 to</span> <span m='4217760'>the</span>
  <span m='4217890'>M</span> <span m='4218100'>plus</span> <span m='4218400'>x</span>
  <span m='4218740'>by</span> <span m='4218870'>the</span> <span m='4218990'>fundamental</span>
  <span m='4219480'>theorem</span> <span m='4219740'>of</span> <span m='4219880'>algebra?</span>
  </p><p><span m='4220195'>AUDIENCE:</span> <span m='4220510'>2 to the</span> <span
  m='4220887'>M.</span> </p><p><span m='4221264'>PROFESSOR:</span> <span m='4221641'>2</span>
  <span m='4222020'>to</span> <span m='4222220'>the</span> <span m='4222410'>M.</span>
  <span m='4224040'>So</span> <span m='4224920'>that</span> <span m='4225090'>means</span>
  <span m='4225560'>that</span> <span m='4227550'>x</span> <span m='4227930'>2</span>
  <span m='4228280'>to</span> <span m='4228520'>the</span> <span m='4228650'>M</span>
  <span m='4228840'>plus</span> <span m='4229200'>x --</span> <span m='4231010'>and</span>
  <span m='4231190'>for</span> <span m='4231330'>every</span> <span m='4231560'>root,</span>
  <span m='4231900'>it's</span> <span m='4232090'>got</span> <span m='4232240'>to</span>
  <span m='4232280'>have</span> <span m='4232420'>a</span> <span m='4232480'>factor</span>
  <span m='4237820'>of</span> <span m='4237990'>the</span> <span m='4238100'>form</span>
  <span m='4238630'>x</span> <span m='4239570'>minus,</span> <span m='4240120'>or</span>
  <span m='4240250'>in</span> <span m='4240340'>this</span> <span m='4240560'>case,</span>
  <span m='4240870'>plus</span> <span m='4242070'>beta.</span> <span m='4243770'>So</span>
  <span m='4244160'>this</span> <span m='4244430'>must</span> <span m='4244730'>have</span>
  <span m='4244910'>a</span> <span m='4244990'>complete</span> <span m='4245510'>factorization</span>
  <span m='4246540'>of</span> <span m='4246590'>the</span> <span m='4246680'>following</span>
  <span m='4247140'>form.</span> <span m='4253750'>x</span> <span m='4254010'>2 to</span>
  <span m='4254220'>the</span> <span m='4254370'>M</span> <span m='4254560'>plus</span>
  <span m='4254900'>x</span> <span m='4255210'>is</span> <span m='4255310'>simply</span>
  <span m='4255650'>the</span> <span m='4255760'>product</span> <span m='4256280'>of</span>
  <span m='4256440'>x</span> <span m='4258000'>minus</span> <span m='4258370'>beta.</span>
  <span m='4262370'>All</span> <span m='4262480'>right.</span> <span m='4266680'>In</span>
  <span m='4266870'>fact,</span> <span m='4267230'>you</span> <span m='4267380'>can</span>
  <span m='4267520'>see</span> <span m='4267940'>that</span> <span m='4268330'>0</span>
  <span m='4268840'>a</span> <span m='4268900'>root,</span> <span m='4269830'>obviously.</span>
  <span m='4271190'>1</span> <span m='4271490'>is</span> <span m='4271650'>a</span>
  <span m='4271730'>root,</span> <span m='4273560'>obviously.</span> <span m='4275150'>And</span>
  <span m='4278910'>we've</span> <span m='4279080'>checked</span> <span m='4279450'>up</span>
  <span m='4279640'>here.</span> <span m='4280730'>Let's</span> <span m='4280980'>see,</span>
  <span m='4281170'>what</span> <span m='4281340'>are</span> <span m='4281380'>we</span>
  <span m='4281530'>interested</span> <span m='4281950'>in?</span> <span m='4282350'>Here's</span>
  <span m='4282660'>another</span> <span m='4282920'>example.</span> <span m='4284070'>x</span>
  <span m='4284400'>to</span> <span m='4284460'>the</span> <span m='4284560'>fourth</span>
  <span m='4285030'>plus</span> <span m='4285410'>1,</span> <span m='4287580'>f</span>
  <span m='4287860'>of --</span> <span m='4288770'>if we have</span> <span m='4288910'>g</span>
  <span m='4289160'>of</span> <span m='4289310'>x</span> <span m='4289870'>equals</span>
  <span m='4290370'>x to the</span> <span m='4290640'>four --</span> <span m='4290970'>sorry
  --</span> <span m='4291380'>plus</span> <span m='4291740'>x,</span> <span m='4292800'>then</span>
  <span m='4293270'>g</span> <span m='4293740'>of</span> <span m='4294870'>alpha</span>
  <span m='4295560'>is</span> <span m='4296700'>alpha</span> <span m='4297070'>to</span>
  <span m='4297120'>the</span> <span m='4297200'>fourth</span> <span m='4297680'>plus</span>
  <span m='4298080'>alpha.</span> <span m='4298620'>But</span> <span m='4298800'>alpha</span>
  <span m='4299120'>to</span> <span m='4299180'>the</span> <span m='4299280'>fourth</span>
  <span m='4299720'>is</span> <span m='4300810'>equal to</span> <span m='4301190'>alpha,</span>
  <span m='4301660'>so</span> <span m='4301840'>that's</span> <span m='4302170'>0.</span>
  <span m='4303220'>g</span> <span m='4303600'>to</span> <span m='4303730'>the</span>
  <span m='4303900'>alpha</span> <span m='4304270'>squared</span> <span m='4305560'>equals</span>
  <span m='4306720'>alpha</span> <span m='4307180'>to</span> <span m='4307270'>the</span>
  <span m='4307450'>8th</span> <span m='4308340'>plus</span> <span m='4308850'>alpha</span>
  <span m='4309200'>squared.</span> <span m='4310400'>Alpha</span> <span m='4310700'>to</span>
  <span m='4310750'>the</span> <span m='4310920'>8th</span> <span m='4311260'>is</span>
  <span m='4311670'>alpha to</span> <span m='4311800'>the</span> <span m='4311880'>fifth</span>
  <span m='4312330'>is</span> <span m='4312500'>alpha</span> <span m='4312800'>squared,</span>
  <span m='4313430'>so that</span> <span m='4313710'>equals</span> <span m='4313990'>0.</span>
  <span m='4315140'>So,</span> <span m='4315360'>in</span> <span m='4315480'>fact,</span>
  <span m='4315810'>that's</span> <span m='4316090'>true</span> <span m='4318360'>for</span>
  <span m='4318450'>that</span> <span m='4318720'>case.</span> </p><p><span m='4324720'>Every</span>
  <span m='4329310'>irreducible</span> <span m='4334260'>polynomial</span> <span m='4338280'>g</span>
  <span m='4338620'>of</span> <span m='4338780'>x</span> <span m='4339420'>and</span>
  <span m='4340050'>F2</span> <span m='4340940'>of</span> <span m='4341330'>x</span>
  <span m='4344730'>whose</span> <span m='4356820'>degree</span> <span m='4358450'>g</span>
  <span m='4358750'>of</span> <span m='4358960'>x</span> <span m='4359570'>divides</span>
  <span m='4364238'>2</span> <span m='4364710'>to</span> <span m='4364990'>the</span>
  <span m='4365150'>M --</span> <span m='4374440'>is that</span> <span m='4374530'>right?</span>
  <span m='4376350'>This may</span> <span m='4376640'>be</span> <span m='4377770'>2
  to</span> <span m='4377920'>the</span> <span m='4378300'>M</span> <span m='4380860'>minus
  --</span> <span m='4385230'>I think</span> <span m='4385440'>it's</span> <span m='4385590'>whose</span>
  <span m='4385710'>degree</span> <span m='4385940'>divides</span> <span m='4386490'>M
  --</span> <span m='4391290'>is</span> <span m='4391790'>a</span> <span m='4394600'>factor</span>
  <span m='4397302'>of</span> <span m='4397780'>x</span> <span m='4398140'>to</span>
  <span m='4398270'>the</span> <span m='4398430'>2M</span> <span m='4399810'>plus</span>
  <span m='4400270'>x</span> <span m='4401470'>in</span> <span m='4403020'>F2</span>
  <span m='4403120'>to the x.</span> <span m='4409910'>OK.</span> <span m='4412580'>So</span>
  <span m='4413020'>let's</span> <span m='4415120'>give</span> <span m='4415240'>you</span>
  <span m='4415330'>an</span> <span m='4415440'>example</span> <span m='4415980'>again.</span>
  <span m='4417930'>Example</span> <span m='4418980'>M</span> <span m='4419270'>equals</span>
  <span m='4419900'>2.</span> <span m='4421220'>This</span> <span m='4421490'>means,</span>
  <span m='4422050'>what</span> <span m='4422230'>are</span> <span m='4422330'>the</span>
  <span m='4422510'>irreducible</span> <span m='4423230'>polynomials</span> <span
  m='4424000'>whose</span> <span m='4424170'>degrees</span> <span m='4424670'>divide</span>
  <span m='4424930'>2?</span> <span m='4428300'>The</span> <span m='4429090'>prime</span>
  <span m='4429450'>polynomials</span> <span m='4433950'>of</span> <span m='4434360'>degree</span>
  <span m='4434770'>1</span> <span m='4435840'>certainly</span> <span m='4436230'>divides</span>
  <span m='4436820'>to</span> <span m='4439320'>our</span> <span m='4440750'>x</span>
  <span m='4441200'>and</span> <span m='4441320'>x</span> <span m='4441550'>plus</span>
  <span m='4441840'>1.</span> <span m='4443890'>Do</span> <span m='4443960'>they</span>
  <span m='4444170'>divide</span> <span m='4444680'>x</span> <span m='4445000'>to</span>
  <span m='4445050'>the</span> <span m='4445160'>fourth</span> <span m='4445700'>plus</span>
  <span m='4446020'>1?</span> <span m='4448240'>Yeah,</span> <span m='4448510'>they</span>
  <span m='4448780'>do.</span> </p><p><span m='4453390'>How</span> <span m='4453460'>many</span>
  <span m='4454420'>prime</span> <span m='4454780'>polynomials</span> <span m='4455500'>are</span>
  <span m='4455650'>there of</span> <span m='4455890'>degree</span> <span m='4456390'>2?</span>
  <span m='4457910'>There's</span> <span m='4458210'>only</span> <span m='4458440'>one,</span>
  <span m='4459090'>x</span> <span m='4459300'>squared</span> <span m='4459630'>plus</span>
  <span m='4459950'>x</span> <span m='4460200'>plus</span> <span m='4460580'>1.</span>
  <span m='4463080'>And</span> <span m='4466380'>if</span> <span m='4466560'>you</span>
  <span m='4467010'>divide it</span> <span m='4467500'>out</span> <span m='4467920'>into</span>
  <span m='4468240'>x</span> <span m='4468480'>to the</span> <span m='4468570'>fourth</span>
  <span m='4468900'>plus</span> <span m='4469210'>1,</span> <span m='4469510'>it</span>
  <span m='4469720'>goes</span> <span m='4470420'>evenly.</span> <span m='4473380'>It</span>
  <span m='4473550'>turns</span> <span m='4473940'>out</span> <span m='4474230'>that</span>
  <span m='4476200'>what</span> <span m='4476460'>this</span> <span m='4476730'>implies</span>
  <span m='4479810'>is</span> <span m='4480280'>that</span> <span m='4482330'>this</span>
  <span m='4482500'>is</span> <span m='4482610'>actually</span> <span m='4482970'>an
  if or</span> <span m='4483470'>only</span> <span m='4483840'>if.</span> <span m='4485410'>A</span>
  <span m='4485530'>polynomial</span> <span m='4486290'>g</span> <span m='4486530'>of</span>
  <span m='4486670'>x</span> <span m='4487950'>divides</span> <span m='4488810'>x</span>
  <span m='4489130'>to</span> <span m='4489220'>2</span> <span m='4489330'>to</span>
  <span m='4489580'>the</span> <span m='4489700'>M</span> <span m='4489950'>plus</span>
  <span m='4490260'>x</span> <span m='4490650'>if</span> <span m='4490880'>and</span>
  <span m='4490990'>only</span> <span m='4491400'>if</span> <span m='4492780'>g</span>
  <span m='4493080'>of</span> <span m='4493220'>x</span> <span m='4493530'>has</span>
  <span m='4494160'>a</span> <span m='4494300'>degree</span> <span m='4494730'>which</span>
  <span m='4494990'>divides</span> <span m='4495470'>M</span> <span m='4495830'>and</span>
  <span m='4495980'>g</span> <span m='4496170'>of</span> <span m='4496290'>x</span>
  <span m='4496560'>is</span> <span m='4496940'>irreducible.</span> <span m='4499020'>So</span>
  <span m='4499310'>this</span> <span m='4499730'>implies</span> <span m='4500470'>that</span>
  <span m='4502060'>x</span> <span m='4502660'>to</span> <span m='4502980'>the</span>
  <span m='4503210'>M</span> <span m='4503770'>plus</span> <span m='4504390'>x</span>
  <span m='4505590'>factors</span> <span m='4508130'>in</span> <span m='4509830'>F2</span>
  <span m='4509860'>of</span> <span m='4510720'>x</span> <span m='4512120'>into</span>
  <span m='4513686'>the</span> <span m='4514040'>product</span> <span m='4516630'>of</span>
  <span m='4517720'>all</span> <span m='4518380'>irreducible</span> <span m='4521620'>polynomials</span>
  <span m='4524490'>whose</span> <span m='4525010'>degrees</span> <span m='4526710'>divide</span>
  <span m='4527140'>M.</span> <span m='4529150'>And</span> <span m='4529430'>I</span>
  <span m='4529570'>think</span> <span m='4529840'>you</span> <span m='4529950'>did</span>
  <span m='4530150'>a</span> <span m='4530220'>homework</span> <span m='4530570'>problem</span>
  <span m='4532780'>that</span> <span m='4532990'>used</span> <span m='4533330'>this,</span>
  <span m='4533640'>even</span> <span m='4533870'>though</span> <span m='4534030'>it</span>
  <span m='4534080'>was</span> <span m='4534270'>never</span> <span m='4534500'>proved</span>
  <span m='4534980'>in</span> <span m='4535050'>class.</span> <span m='4536710'>So
  you</span> <span m='4537010'>at</span> <span m='4537120'>least</span> <span m='4537450'>read</span>
  <span m='4537660'>about</span> <span m='4537960'>it.</span> </p><p><span m='4541400'>Again,</span>
  <span m='4541850'>for</span> <span m='4541970'>this</span> <span m='4542210'>example,</span>
  <span m='4543780'>that</span> <span m='4543990'>should</span> <span m='4544270'>mean</span>
  <span m='4544700'>that</span> <span m='4544890'>x</span> <span m='4545270'>to</span>
  <span m='4545350'>the</span> <span m='4545430'>fourth</span> <span m='4545950'>plus</span>
  <span m='4546350'>1</span> <span m='4546890'>equals</span> <span m='4547600'>x</span>
  <span m='4548600'>times</span> <span m='4548970'>x</span> <span m='4549250'>plus</span>
  <span m='4549550'>1</span> <span m='4551060'>times</span> <span m='4551660'>x</span>
  <span m='4551880'>squared</span> <span m='4552260'>plus</span> <span m='4552600'>x</span>
  <span m='4552900'>plus</span> <span m='4553230'>1.</span> <span m='4554450'>Is</span>
  <span m='4554540'>that</span> <span m='4554730'>true?</span> <span m='4558510'>Pretty</span>
  <span m='4558730'>easy</span> <span m='4558950'>to</span> <span m='4559030'>see
  that it</span> <span m='4559500'>is.</span> <span m='4560320'>x</span> <span m='4560570'>plus</span>
  <span m='4560850'>1</span> <span m='4561170'>times</span> <span m='4561440'>x</span>
  <span m='4561570'>squared</span> <span m='4561860'>plus</span> <span m='4562090'>x</span>
  <span m='4562290'>plus</span> <span m='4562530'>1</span> <span m='4562760'>is</span>
  <span m='4562870'>just</span> <span m='4563130'>x</span> <span m='4563410'>cubed</span>
  <span m='4563750'>plus</span> <span m='4564040'>1.</span> <span m='4565440'>Multiply</span>
  <span m='4565810'>by</span> <span m='4565980'>x --</span> <span m='4566470'>I'm</span>
  <span m='4566610'>sorry,</span> <span m='4566900'>this</span> <span m='4567110'>x</span>
  <span m='4567430'>fourth</span> <span m='4567790'>plus</span> <span m='4568050'>x.</span>
  <span m='4568420'>How many</span> <span m='4568780'>times</span> <span m='4569120'>have
  I</span> <span m='4569410'>done</span> <span m='4569650'>this?</span> <span m='4570970'>Should</span>
  <span m='4571160'>be</span> <span m='4571340'>x</span> <span m='4571610'>to the</span>
  <span m='4571690'>fourth</span> <span m='4572050'>plus</span> <span m='4572370'>x.</span>
  <span m='4574642'>Yes.</span> <span m='4577390'>OK,</span> <span m='4577700'>it's</span>
  <span m='4577870'>kind</span> <span m='4578030'>of</span> <span m='4578090'>miracle</span>
  <span m='4578630'>when</span> <span m='4578780'>you</span> <span m='4578880'>first</span>
  <span m='4579190'>see</span> <span m='4579420'>it.</span> <span m='4579610'>This</span>
  <span m='4579800'>works</span> <span m='4580070'>over</span> <span m='4580290'>any</span>
  <span m='4580480'>field</span> <span m='4580940'>for</span> <span m='4582960'>any</span>
  <span m='4583160'>PNM</span> <span m='4583780'>again,</span> <span m='4586020'>lest</span>
  <span m='4586570'>you</span> <span m='4586740'>get</span> <span m='4586950'>this</span>
  <span m='4587160'>kind</span> <span m='4587300'>of</span> <span m='4587430'>factorization.</span>
  </p><p><span m='4590740'>OK,</span> <span m='4591130'>but</span> <span m='4591310'>now,</span>
  <span m='4591620'>comparing</span> <span m='4592100'>this</span> <span m='4592500'>to</span>
  <span m='4592660'>this,</span> <span m='4594400'>what</span> <span m='4594640'>does</span>
  <span m='4594770'>that</span> <span m='4594970'>mean?</span> <span m='4596210'>That</span>
  <span m='4596390'>means</span> <span m='4600500'>this</span> <span m='4600740'>is</span>
  <span m='4600890'>one</span> <span m='4601190'>factorization.</span> <span m='4602290'>This</span>
  <span m='4602510'>is</span> <span m='4602760'>in --</span> <span m='4605520'>we</span>
  <span m='4605800'>can</span> <span m='4605920'>do a</span> <span m='4606090'>complete</span>
  <span m='4606610'>factorization</span> <span m='4607760'>in</span> <span m='4608050'>F2</span>
  <span m='4608350'>to</span> <span m='4608680'>the</span> <span m='4608860'>M</span>
  <span m='4609200'>of x.</span> <span m='4610400'>We</span> <span m='4610600'>can</span>
  <span m='4610730'>only</span> <span m='4611100'>do</span> <span m='4612560'>complete</span>
  <span m='4613010'>in the</span> <span m='4613100'>sense</span> <span m='4613490'>that</span>
  <span m='4613590'>we</span> <span m='4613690'>reduce</span> <span m='4614050'>it</span>
  <span m='4614710'>to</span> <span m='4614950'>a</span> <span m='4615470'>product</span>
  <span m='4615960'>of</span> <span m='4616080'>degree</span> <span m='4616470'>1</span>
  <span m='4616950'>polynomials.</span> <span m='4618350'>In</span> <span m='4618730'>F2</span>
  <span m='4620330'>of</span> <span m='4620450'>x,</span> <span m='4620790'>we</span>
  <span m='4620920'>can't</span> <span m='4621290'>do</span> <span m='4621430'>a</span>
  <span m='4621510'>complete</span> <span m='4621910'>factorization.</span> <span
  m='4622790'>This</span> <span m='4623000'>is</span> <span m='4623100'>similar</span>
  <span m='4623560'>to,</span> <span m='4624330'>over</span> <span m='4624500'>the</span>
  <span m='4624600'>complex</span> <span m='4625200'>field</span> <span m='4625530'>you</span>
  <span m='4625700'>can</span> <span m='4625870'>always</span> <span m='4626600'>completely</span>
  <span m='4627200'>factor</span> <span m='4627680'>a</span> <span m='4627740'>polynomial</span>
  <span m='4630440'>into</span> <span m='4631200'>one-dimensional</span> <span m='4632250'>polynomials</span>
  <span m='4632870'>of</span> <span m='4632990'>this</span> <span m='4633220'>form,</span>
  <span m='4633500'>where</span> <span m='4633730'>beta</span> <span m='4634550'>is</span>
  <span m='4634690'>the</span> <span m='4634770'>set</span> <span m='4635020'>of</span>
  <span m='4635120'>roots</span> <span m='4635460'>of</span> <span m='4635540'>the</span>
  <span m='4635610'>polynomial.</span> <span m='4636900'>Whereas</span> <span m='4637250'>over</span>
  <span m='4637410'>the</span> <span m='4637510'>real</span> <span m='4637790'>field,</span>
  <span m='4639740'>you</span> <span m='4639840'>might</span> <span m='4640030'>have</span>
  <span m='4640250'>to</span> <span m='4640380'>have</span> <span m='4640620'>some</span>
  <span m='4641910'>degree</span> <span m='4642330'>2</span> <span m='4643130'>polynomials</span>
  <span m='4643830'>in</span> <span m='4643970'>there.</span> </p><p><span m='4644370'>This</span>
  <span m='4644580'>is</span> <span m='4644750'>exactly</span> <span m='4645310'>analogous.</span>
  <span m='4646340'>You</span> <span m='4646450'>can't</span> <span m='4646790'>get</span>
  <span m='4648260'>complete</span> <span m='4648660'>factorization</span> <span m='4649570'>over</span>
  <span m='4650470'>this</span> <span m='4650690'>subfield.</span> <span m='4653450'>But</span>
  <span m='4653980'>what</span> <span m='4654210'>does</span> <span m='4654330'>it</span>
  <span m='4654430'>mean?</span> <span m='4654700'>Here</span> <span m='4654870'>we</span>
  <span m='4654940'>have</span> <span m='4655090'>a polynomial</span> <span m='4655380'>of</span>
  <span m='4655670'>degree</span> <span m='4656020'>4,</span> <span m='4656460'>has</span>
  <span m='4656710'>4</span> <span m='4657050'>roots.</span> <span m='4657890'>We</span>
  <span m='4658030'>factor</span> <span m='4658490'>like</span> <span m='4658780'>this.</span>
  <span m='4659640'>So</span> <span m='4660340'>each</span> <span m='4660600'>of</span>
  <span m='4660750'>these</span> <span m='4660900'>factors</span> <span m='4661480'>must</span>
  <span m='4662000'>contain</span> <span m='4662490'>a</span> <span m='4662560'>number</span>
  <span m='4662850'>of</span> <span m='4662910'>roots</span> <span m='4663380'>equal</span>
  <span m='4663730'>to</span> <span m='4663900'>its</span> <span m='4664090'>degree.</span>
  <span m='4665670'>So</span> <span m='4665900'>what</span> <span m='4666040'>are</span>
  <span m='4666170'>the</span> <span m='4666300'>roots?</span> <span m='4667280'>This</span>
  <span m='4667500'>is</span> <span m='4667640'>the</span> <span m='4667740'>polynomial</span>
  <span m='4668450'>that</span> <span m='4668740'>has</span> <span m='4669560'>root</span>
  <span m='4669870'>0.</span> <span m='4671170'>This</span> <span m='4671380'>is</span>
  <span m='4671490'>the</span> <span m='4671580'>polynomial</span> <span m='4671855'>that</span>
  <span m='4672130'>has</span> <span m='4672400'>root</span> <span m='4672600'>1.</span>
  <span m='4673710'>As</span> <span m='4674030'>we</span> <span m='4674150'>just</span>
  <span m='4674330'>showed,</span> <span m='4674780'>this</span> <span m='4674960'>is
  the</span> <span m='4675210'>polynomial</span> <span m='4675760'>that has</span>
  <span m='4676190'>the</span> <span m='4676310'>roots</span> <span m='4676710'>alpha</span>
  <span m='4677160'>and alpha</span> <span m='4677550'>squared,</span> <span m='4678632'>OK?</span>
  <span m='4681650'>So</span> <span m='4681840'>it's</span> <span m='4681980'>always</span>
  <span m='4682230'>going</span> <span m='4682330'>to</span> <span m='4682400'>turn</span>
  <span m='4682620'>out</span> <span m='4682820'>that</span> <span m='4683020'>way.</span>
  </p><p><span m='4685290'>So</span> <span m='4685570'>you</span> <span m='4685780'>can</span>
  <span m='4686100'>group</span> <span m='4688650'>the</span> <span m='4688760'>field</span>
  <span m='4689120'>elements</span> <span m='4690530'>into</span> <span m='4691080'>subsets</span>
  <span m='4693920'>where</span> <span m='4694430'>each</span> <span m='4694640'>subset</span>
  <span m='4696650'>is</span> <span m='4696890'>the</span> <span m='4696970'>set</span>
  <span m='4697280'>of</span> <span m='4697410'>roots</span> <span m='4697830'>of</span>
  <span m='4697990'>some</span> <span m='4698340'>irreducible</span> <span m='4699090'>binary</span>
  <span m='4699580'>polynomial</span> <span m='4701130'>of</span> <span m='4701620'>some</span>
  <span m='4701890'>degree</span> <span m='4702310'>that</span> <span m='4702450'>divides</span>
  <span m='4702950'>M,</span> <span m='4704480'>OK?</span> <span m='4705480'>These</span>
  <span m='4705660'>are</span> <span m='4705730'>called</span> <span m='4705980'>cyclotomic</span>
  <span m='4707410'>subsets.</span> <span m='4709390'>Whence</span> <span m='4709850'>the</span>
  <span m='4710190'>name of</span> <span m='4710430'>Elwyn</span> <span m='4710755'>Berlekamp's</span>
  <span m='4711080'>company,</span> <span m='4711570'>Cyclotomics.</span> <span m='4715630'>All</span>
  <span m='4715750'>right.</span> <span m='4716090'>So</span> <span m='4717620'>this</span>
  <span m='4717990'>is</span> <span m='4718140'>where,</span> <span m='4719040'>I</span>
  <span m='4719240'>think,</span> <span m='4719560'>the</span> <span m='4719670'>theory</span>
  <span m='4720040'>gets</span> <span m='4720370'>just</span> <span m='4720610'>absolutely</span>
  <span m='4721100'>lovely</span> <span m='4721580'>and</span> <span m='4721740'>unexpected,</span>
  <span m='4722490'>at</span> <span m='4722740'>least</span> <span m='4723400'>when</span>
  <span m='4723560'>you</span> <span m='4723680'>start</span> <span m='4724050'>in.</span>
  <span m='4724350'>And</span> <span m='4724920'>people</span> <span m='4725240'>who
  have</span> <span m='4725360'>a</span> <span m='4725430'>taste</span> <span m='4725740'>for</span>
  <span m='4725840'>these</span> <span m='4726080'>things,</span> <span m='4726410'>I</span>
  <span m='4726480'>encourage</span> <span m='4726950'>you</span> <span m='4727510'>to</span>
  <span m='4727610'>read</span> <span m='4727860'>a</span> <span m='4727910'>real</span>
  <span m='4728170'>book</span> <span m='4728460'>on</span> <span m='4728580'>the</span>
  <span m='4728690'>subject.</span> <span m='4730120'>Berlekamp's</span> <span m='4730625'>is</span>
  <span m='4730890'>one</span> <span m='4731710'>of the</span> <span m='4732170'>most</span>
  <span m='4732490'>elegant.</span> <span m='4733340'>But</span> <span m='4733500'>there</span>
  <span m='4733620'>are</span> <span m='4733670'>lots --</span> <span m='4734280'>because</span>
  <span m='4734670'>it's</span> <span m='4734840'>an</span> <span m='4735270'>elegant</span>
  <span m='4735660'>subject,</span> <span m='4736090'>there</span> <span m='4736220'>are</span>
  <span m='4736260'>lots</span> <span m='4736550'>of</span> <span m='4736660'>elegant</span>
  <span m='4737070'>treatments</span> <span m='4737540'>of it.</span> <span m='4739560'>All</span>
  <span m='4739710'>right.</span> </p><p><span m='4741590'>So</span> <span m='4742320'>remember</span>
  <span m='4742640'>what</span> <span m='4742780'>we were</span> <span m='4742940'>trying</span>
  <span m='4743220'>to</span> <span m='4743300'>do</span> <span m='4743520'>in</span>
  <span m='4743590'>the</span> <span m='4743810'>first</span> <span m='4744020'>place.</span>
  <span m='4744480'>We</span> <span m='4744580'>were</span> <span m='4744710'>trying</span>
  <span m='4744960'>to</span> <span m='4749340'>find</span> <span m='4749900'>the</span>
  <span m='4749990'>dimension</span> <span m='4750560'>of</span> <span m='4750690'>BCH</span>
  <span m='4751440'>codes.</span> <span m='4753510'>So</span> <span m='4753780'>where</span>
  <span m='4754170'>are</span> <span m='4754190'>we</span> <span m='4754350'>now?</span>
  <span m='4755120'>We've</span> <span m='4755280'>defined</span> <span m='4756000'>a</span>
  <span m='4756150'>BCH</span> <span m='4758630'>code</span> <span m='4760380'>as</span>
  <span m='4760990'>the</span> <span m='4761300'>set</span> <span m='4763350'>of</span>
  <span m='4763780'>all</span> <span m='4765410'>binary</span> <span m='4765960'>polynomials</span>
  <span m='4771830'>with</span> <span m='4772450'>roots</span> <span m='4774960'>alpha</span>
  <span m='4776760'>up</span> <span m='4777210'>to</span> <span m='4777450'>alpha</span>
  <span m='4777830'>to</span> <span m='4778110'>the</span> <span m='4778280'>n</span>
  <span m='4778460'>minus</span> <span m='4778900'>k</span> <span m='4779270'>where</span>
  <span m='4779500'>n and</span> <span m='4779820'>k</span> <span m='4780060'>are</span>
  <span m='4780180'>the</span> <span m='4780280'>parameters</span> <span m='4780940'>of</span>
  <span m='4781060'>the</span> <span m='4781140'>parent</span> <span m='4783760'>Reed-Solomon</span>
  <span m='4784420'>code.</span> <span m='4784760'>And</span> <span m='4785100'>alpha</span>
  <span m='4785550'>is</span> <span m='4785850'>in</span> <span m='4785980'>the</span>
  <span m='4786070'>parent</span> <span m='4786770'>field.</span> <span m='4787618'>So</span>
  <span m='4788494'>alpha</span> <span m='4788932'>in</span> <span m='4790250'>F2</span>
  <span m='4790585'>to the</span> <span m='4790920'>M.</span> </p><p><span m='4795490'>OK.</span>
  <span m='4795920'>One</span> <span m='4796330'>final</span> <span m='4796830'>fact,</span>
  <span m='4797310'>I</span> <span m='4797370'>guess,</span> <span m='4797650'>we</span>
  <span m='4797770'>need</span> <span m='4798000'>to</span> <span m='4798130'>know</span>
  <span m='4798360'>here.</span> <span m='4801415'>All</span> <span m='4801840'>right,</span>
  <span m='4802280'>if</span> <span m='4803800'>alpha</span> <span m='4804560'>is</span>
  <span m='4804850'>a</span> <span m='4804910'>root --</span> <span m='4805290'>now</span>
  <span m='4805420'>I'm</span> <span m='4805540'>talking</span> <span m='4805850'>about</span>
  <span m='4806080'>any</span> <span m='4806320'>field --</span> <span m='4808540'>then</span>
  <span m='4810020'>alpha</span> <span m='4810350'>squared</span> <span m='4810800'>is</span>
  <span m='4810920'>a</span> <span m='4811000'>root</span> <span m='4811850'>of</span>
  <span m='4812050'>a</span> <span m='4812120'>binary</span> <span m='4812770'>polynomial.</span>
  <span m='4818480'>And</span> <span m='4818780'>again,</span> <span m='4819100'>this</span>
  <span m='4819310'>is</span> <span m='4819510'>due</span> <span m='4819750'>to</span>
  <span m='4820050'>a</span> <span m='4820120'>very</span> <span m='4820760'>lovely</span>
  <span m='4821200'>fact,</span> <span m='4821730'>which</span> <span m='4821980'>is</span>
  <span m='4822160'>that</span> <span m='4822320'>squaring</span> <span m='4822950'>is</span>
  <span m='4823140'>linear</span> <span m='4824770'>in</span> <span m='4825910'>fields</span>
  <span m='4826310'>of</span> <span m='4826390'>characteristic</span> <span m='4827100'>2.</span>
  <span m='4829090'>Why</span> <span m='4829370'>is</span> <span m='4829480'>squaring</span>
  <span m='4829910'>linear.</span> <span m='4831045'>A little</span> <span m='4831410'>side</span>
  <span m='4831920'>calculation.</span> <span m='4833530'>a</span> <span m='4833700'>plus</span>
  <span m='4834090'>b</span> <span m='4834290'>squared</span> <span m='4835010'>equals</span>
  <span m='4835540'>a</span> <span m='4835730'>squared</span> <span m='4836260'>plus</span>
  <span m='4836560'>2ab</span> <span m='4837880'>plus</span> <span m='4838200'>b</span>
  <span m='4838410'>squared</span> <span m='4839070'>but</span> <span m='4839570'>characteristic</span>
  <span m='4840270'>2.</span> <span m='4841340'>We</span> <span m='4841480'>can</span>
  <span m='4841610'>wipe</span> <span m='4841870'>that</span> <span m='4842090'>out.</span>
  <span m='4843450'>So</span> <span m='4844200'>in</span> <span m='4844410'>general,</span>
  <span m='4848060'>f</span> <span m='4849910'>of</span> <span m='4850110'>x</span>
  <span m='4851450'>quantity</span> <span m='4851920'>squared</span> <span m='4852700'>is</span>
  <span m='4853460'>f</span> <span m='4853530'>of x</span> <span m='4853980'>squared.</span>
  <span m='4858120'>And</span> <span m='4858360'>that's</span> <span m='4858640'>why,</span>
  <span m='4858950'>if</span> <span m='4860410'>f</span> <span m='4860620'>of</span>
  <span m='4860750'>x</span> <span m='4861060'>evaluates</span> <span m='4861680'>to</span>
  <span m='4861810'>0,</span> <span m='4862600'>then</span> <span m='4863010'>f</span>
  <span m='4863180'>of</span> <span m='4863310'>x</span> <span m='4863520'>squared</span>
  <span m='4863900'>must</span> <span m='4864120'>evaluate</span> <span m='4864650'>to</span>
  <span m='4864780'>0</span> <span m='4868320'>since</span> <span m='4868630'>0</span>
  <span m='4868880'>squared</span> <span m='4869310'>is</span> <span m='4869450'>always</span>
  <span m='4869740'>equal</span> <span m='4869980'>to</span> <span m='4870020'>0.</span>
  </p><p><span m='4871910'>All</span> <span m='4872060'>right.</span> <span m='4872360'>So</span>
  <span m='4873720'>alpha</span> <span m='4874050'>is</span> <span m='4874160'>a</span>
  <span m='4874220'>root</span> <span m='4874490'>if</span> <span m='4874730'>and</span>
  <span m='4874810'>only</span> <span m='4875110'>if</span> <span m='4875610'>alpha</span>
  <span m='4875930'>squared</span> <span m='4876330'>is</span> <span m='4876470'>a</span>
  <span m='4876540'>root.</span> <span m='4877330'>Is</span> <span m='4877460'>that</span>
  <span m='4877610'>true</span> <span m='4877890'>here?</span> <span m='4878380'>Yes.</span>
  <span m='4878900'>Alpha</span> <span m='4879265'>alpha</span> <span m='4879630'>squared.</span>
  <span m='4880460'>Well,</span> <span m='4880690'>is it</span> <span m='4881040'>also</span>
  <span m='4881370'>true</span> <span m='4881660'>if</span> <span m='4881780'>we</span>
  <span m='4881890'>squared</span> <span m='4882280'>alpha</span> <span m='4882580'>squared?</span>
  <span m='4883080'>What</span> <span m='4883220'>is</span> <span m='4883340'>the</span>
  <span m='4883420'>square</span> <span m='4883750'>of</span> <span m='4883830'>alpha</span>
  <span m='4884110'>squared?</span> <span m='4885430'>It's back to</span> <span m='4885800'>alpha,</span>
  <span m='4887320'>all</span> <span m='4887410'>right?</span> <span m='4887800'>So</span>
  <span m='4888760'>these</span> <span m='4888990'>sets</span> <span m='4891560'>now</span>
  <span m='4891820'>turn</span> <span m='4892120'>out</span> <span m='4892350'>to</span>
  <span m='4892440'>be</span> <span m='4894290'>cyclotomic</span> <span m='4895760'>cosets,</span>
  <span m='4896520'>they're</span> <span m='4896720'>called,</span> <span m='4897440'>which</span>
  <span m='4897740'>is</span> <span m='4898400'>the</span> <span m='4898500'>set</span>
  <span m='4898780'>of</span> <span m='4898870'>all</span> <span m='4899130'>elements</span>
  <span m='4900040'>and</span> <span m='4900250'>their</span> <span m='4900400'>squares.</span>
  <span m='4901740'>We</span> <span m='4901950'>get</span> <span m='4902200'>alpha,</span>
  <span m='4902860'>alpha</span> <span m='4903150'>squared,</span> <span m='4903730'>alpha</span>
  <span m='4904040'>fourth,</span> <span m='4904630'>alpha</span> <span m='4905040'>eighth.</span>
  <span m='4906360'>And</span> <span m='4906500'>then,</span> <span m='4906660'>at</span>
  <span m='4906790'>some</span> <span m='4907020'>point,</span> <span m='4907350'>it</span>
  <span m='4907570'>cycles.</span> <span m='4908170'>Why?</span> <span m='4909420'>Because</span>
  <span m='4909760'>what</span> <span m='4909930'>does</span> <span m='4910060'>alpha</span>
  <span m='4910410'>to</span> <span m='4910490'>the</span> <span m='4910630'>2M</span>
  <span m='4911170'>equal?</span> </p><p><span m='4911620'>AUDIENCE:</span> <span
  m='4912086'>[INAUDIBLE].</span> </p><p><span m='4912552'>PROFESSOR:</span> <span
  m='4914416'>No.</span> <span m='4915820'>Alpha.</span> <span m='4916710'>Right.</span>
  <span m='4917120'>Alpha to the</span> <span m='4917680'>2M</span> <span m='4917960'>minus</span>
  <span m='4918290'>1</span> <span m='4918470'>is</span> <span m='4918610'>1,</span>
  <span m='4918950'>so</span> <span m='4919370'>alpha</span> <span m='4919640'>to
  the</span> <span m='4919890'>2M</span> <span m='4920360'>is</span> <span m='4920610'>alpha.</span>
  <span m='4921350'>So</span> <span m='4921550'>it</span> <span m='4921640'>comes</span>
  <span m='4921880'>back</span> <span m='4922180'>to</span> <span m='4922280'>alpha</span>
  <span m='4922640'>again</span> <span m='4924550'>because</span> <span m='4924940'>of</span>
  <span m='4925070'>that.</span> <span m='4925680'>So</span> <span m='4925900'>we</span>
  <span m='4926020'>get</span> <span m='4926270'>a</span> <span m='4926430'>finite</span>
  <span m='4926980'>number</span> <span m='4927310'>of</span> <span m='4927380'>roots</span>
  <span m='4927840'>which,</span> <span m='4928120'>of</span> <span m='4928340'>course,</span>
  <span m='4928560'>are</span> <span m='4928670'>equal</span> <span m='4928990'>to</span>
  <span m='4929170'>the</span> <span m='4929230'>degree</span> <span m='4929660'>here.</span>
  <span m='4930810'>In</span> <span m='4931010'>some</span> <span m='4931270'>cases,</span>
  <span m='4931770'>it's</span> <span m='4932000'>fewer.</span> <span m='4933306'>It's</span>
  <span m='4933690'>whatever</span> <span m='4934230'>the</span> <span m='4934340'>degree</span>
  <span m='4934680'>is.</span> <span m='4934830'>It's</span> <span m='4935590'>d,</span>
  <span m='4935980'>which</span> <span m='4936250'>divides</span> <span m='4936790'>M.</span>
  </p><p><span m='4943980'>So</span> <span m='4944220'>from</span> <span m='4944410'>this,</span>
  <span m='4944900'>we</span> <span m='4945040'>simply</span> <span m='4945380'>start
  --</span> <span m='4947360'>suppose</span> <span m='4947720'>we</span> <span m='4947820'>want</span>
  <span m='4948030'>alpha</span> <span m='4948480'>to</span> <span m='4948620'>be</span>
  <span m='4948790'>a root.</span> <span m='4950930'>Let's</span> <span m='4951190'>start</span>
  <span m='4952390'>with</span> <span m='4952570'>high</span> <span m='4952800'>rate</span>
  <span m='4953730'>codes.</span> <span m='4956180'>I</span> <span m='4956660'>think</span>
  <span m='4958300'>here</span> <span m='4958570'>in</span> <span m='4958640'>the</span>
  <span m='4958780'>example,</span> <span m='4960400'>in</span> <span m='4960640'>the</span>
  <span m='4960810'>text,</span> <span m='4961420'>I used</span> <span m='4961940'>F16.</span>
  <span m='4964140'>F16</span> <span m='4965750'>is</span> <span m='4966030'>going</span>
  <span m='4966230'>to</span> <span m='4966320'>have --</span> <span m='4967860'>the</span>
  <span m='4967960'>elements</span> <span m='4968340'>of</span> <span m='4968390'>F16</span>
  <span m='4969330'>are</span> <span m='4969510'>going</span> <span m='4969670'>to</span>
  <span m='4969860'>be</span> <span m='4971130'>the</span> <span m='4972010'>roots</span>
  <span m='4973380'>of</span> <span m='4973760'>all</span> <span m='4974030'>the</span>
  <span m='4974110'>degree</span> <span m='4974480'>1,</span> <span m='4975310'>2,</span>
  <span m='4976080'>and</span> <span m='4976310'>4</span> <span m='4976810'>polynomials</span>
  <span m='4977600'>because</span> <span m='4977960'>M</span> <span m='4978140'>is</span>
  <span m='4978320'>4</span> <span m='4978670'>and</span> <span m='4978790'>these</span>
  <span m='4978910'>are</span> <span m='4979830'>the</span> <span m='4979960'>degrees</span>
  <span m='4980280'>that</span> <span m='4980540'>divide</span> <span m='4980970'>4.</span>
  <span m='4981320'>So</span> <span m='4981520'>again,</span> <span m='4981810'>we</span>
  <span m='4982000'>get</span> <span m='4982250'>x</span> <span m='4983390'>and</span>
  <span m='4983590'>x</span> <span m='4983850'>plus</span> <span m='4984170'>1,</span>
  <span m='4986030'>which</span> <span m='4986330'>have</span> <span m='4986590'>roots</span>
  <span m='4988620'>0</span> <span m='4989400'>and</span> <span m='4989550'>1.</span>
  <span m='4991300'>We</span> <span m='4991450'>get</span> <span m='4991870'>x</span>
  <span m='4992160'>squared</span> <span m='4992680'>plus</span> <span m='4993080'>x</span>
  <span m='4993480'>plus</span> <span m='4993900'>1.</span> </p><p><span m='4995720'>What</span>
  <span m='4995900'>are</span> <span m='4995950'>the</span> <span m='4996070'>roots</span>
  <span m='4996780'>of</span> <span m='4996960'>x</span> <span m='4997150'>squared</span>
  <span m='4997420'>plus</span> <span m='4997700'>x</span> <span m='4997920'>plus</span>
  <span m='4998190'>1</span> <span m='4998470'>and</span> <span m='4998620'>F16?</span>
  <span m='4999870'>There</span> <span m='5000060'>are</span> <span m='5000150'>only</span>
  <span m='5000380'>going</span> <span m='5000490'>to</span> <span m='5000590'>be</span>
  <span m='5000700'>two</span> <span m='5000940'>of</span> <span m='5001040'>them</span>
  <span m='5002040'>and</span> <span m='5002160'>they've</span> <span m='5002320'>got</span>
  <span m='5002480'>to</span> <span m='5002520'>have</span> <span m='5002650'>the</span>
  <span m='5002740'>property</span> <span m='5003990'>that</span> <span m='5005905'>if</span>
  <span m='5006370'>we</span> <span m='5006500'>start</span> <span m='5006840'>with</span>
  <span m='5008070'>the</span> <span m='5008260'>first</span> <span m='5008660'>one,</span>
  <span m='5008770'>let's</span> <span m='5008970'>call</span> <span m='5009190'>it</span>
  <span m='5009350'>beta</span> <span m='5010290'>and</span> <span m='5010490'>beta</span>
  <span m='5010770'>squared.</span> <span m='5012300'>Beta</span> <span m='5012600'>fourth</span>
  <span m='5013050'>has</span> <span m='5013210'>got</span> <span m='5013360'>to</span>
  <span m='5013500'>equal</span> <span m='5013930'>beta</span> <span m='5014290'>because</span>
  <span m='5014520'>we</span> <span m='5014640'>only</span> <span m='5014850'>have</span>
  <span m='5015080'>two</span> <span m='5015290'>of</span> <span m='5015380'>them.</span>
  <span m='5016960'>That</span> <span m='5017320'>more</span> <span m='5017600'>or</span>
  <span m='5017650'>less</span> <span m='5017960'>forces</span> <span m='5019520'>beta</span>
  <span m='5020020'>to</span> <span m='5020200'>be</span> <span m='5021290'>alpha</span>
  <span m='5021560'>to</span> <span m='5021610'>the</span> <span m='5021730'>fifth</span>
  <span m='5022770'>or</span> <span m='5023040'>alpha to the</span> <span m='5023480'>tenth.</span>
  <span m='5025410'>Let's</span> <span m='5025890'>see</span> <span m='5026110'>if</span>
  <span m='5026310'>that</span> <span m='5026500'>works.</span> <span m='5028300'>We
  get</span> <span m='5028600'>alpha</span> <span m='5028710'>to the</span> <span
  m='5028850'>fifth,</span> <span m='5030200'>alpha</span> <span m='5030270'>to the</span>
  <span m='5030450'>tenth.</span> <span m='5031680'>Square</span> <span m='5032110'>that,</span>
  <span m='5032440'>we</span> <span m='5032560'>get</span> <span m='5032720'>alpha</span>
  <span m='5032900'>to</span> <span m='5033000'>the</span> <span m='5033130'>20th.</span>
  <span m='5034400'>But</span> <span m='5034780'>we</span> <span m='5035240'>now</span>
  <span m='5035480'>take</span> <span m='5035750'>the</span> <span m='5035870'>exponents</span>
  <span m='5036340'>mod</span> <span m='5036700'>15</span> <span m='5037330'>and</span>
  <span m='5037450'>we</span> <span m='5037580'>get</span> <span m='5037770'>5</span>
  <span m='5038090'>again,</span> <span m='5039030'>all right?</span> <span m='5040440'>So</span>
  <span m='5041870'>those</span> <span m='5042150'>are</span> <span m='5042180'>the</span>
  <span m='5042330'>two</span> <span m='5042610'>roots</span> <span m='5043760'>of</span>
  <span m='5043910'>x</span> <span m='5044070'>squared</span> <span m='5044350'>plus</span>
  <span m='5044610'>x</span> <span m='5044820'>plus</span> <span m='5045080'>1</span>
  <span m='5045410'>in</span> <span m='5045620'>F16.</span> <span m='5049220'>Obviously,</span>
  <span m='5049720'>I'm</span> <span m='5050050'>not --</span> <span m='5050920'>I</span>
  <span m='5051000'>guess</span> <span m='5051560'>that</span> <span m='5051740'>was</span>
  <span m='5052040'>a</span> <span m='5052100'>legitimate</span> <span m='5052660'>proof,</span>
  <span m='5053070'>but</span> <span m='5053270'>it</span> <span m='5053340'>was</span>
  <span m='5053520'>certainly</span> <span m='5054040'>quick.</span> </p><p><span
  m='5055810'>OK,</span> <span m='5056320'>there</span> <span m='5056710'>are</span>
  <span m='5056760'>three</span> <span m='5057140'>polynomials</span> <span m='5057860'>of</span>
  <span m='5057960'>degree</span> <span m='5058310'>4.</span> <span m='5058690'>By</span>
  <span m='5058920'>the</span> <span m='5059030'>way,</span> <span m='5060370'>I</span>
  <span m='5060510'>think</span> <span m='5060750'>you</span> <span m='5060870'>can</span>
  <span m='5061010'>imagine</span> <span m='5061570'>how,</span> <span m='5062320'>given</span>
  <span m='5062610'>this</span> <span m='5062850'>result,</span> <span m='5063790'>we</span>
  <span m='5063970'>can</span> <span m='5064130'>now</span> <span m='5064730'>enumerate</span>
  <span m='5067050'>the</span> <span m='5067210'>polynomials</span> <span m='5067870'>of</span>
  <span m='5067950'>each</span> <span m='5068190'>degree.</span> <span m='5069450'>We</span>
  <span m='5069820'>now</span> <span m='5070070'>have</span> <span m='5070290'>an</span>
  <span m='5070950'>expression.</span> <span m='5075350'>There</span> <span m='5075600'>are</span>
  <span m='5075680'>two</span> <span m='5076800'>irreducible</span> <span m='5077410'>polynomials</span>
  <span m='5078060'>of</span> <span m='5078130'>degree</span> <span m='5078440'>1.</span>
  <span m='5080360'>So</span> <span m='5080610'>how</span> <span m='5080770'>many</span>
  <span m='5080980'>more</span> <span m='5081330'>of</span> <span m='5081400'>degree</span>
  <span m='5081790'>2</span> <span m='5082120'>is</span> <span m='5082260'>it</span>
  <span m='5082340'>going</span> <span m='5082470'>to</span> <span m='5082590'>take</span>
  <span m='5082960'>to</span> <span m='5083070'>make</span> <span m='5083290'>the</span>
  <span m='5083420'>overall</span> <span m='5083780'>degree</span> <span m='5084130'>4?</span>
  <span m='5084770'>One</span> <span m='5085010'>of</span> <span m='5085070'>them.</span>
  <span m='5085560'>So</span> <span m='5085770'>we're</span> <span m='5086020'>looking</span>
  <span m='5086350'>for</span> <span m='5086530'>a</span> <span m='5086590'>single
  --</span> <span m='5087160'>there</span> <span m='5087290'>must</span> <span m='5087600'>be</span>
  <span m='5087800'>a</span> <span m='5087840'>single</span> <span m='5088280'>irreducible</span>
  <span m='5088870'>polynomial</span> <span m='5089420'>degree</span> <span m='5089720'>4.</span>
  <span m='5090620'>Similarly</span> <span m='5091080'>over</span> <span m='5091310'>here,</span>
  <span m='5093100'>all</span> <span m='5093210'>right,</span> <span m='5093410'>we've</span>
  <span m='5093560'>accounted</span> <span m='5094000'>for</span> <span m='5094150'>four</span>
  <span m='5094520'>of</span> <span m='5094580'>the</span> <span m='5094720'>elements</span>
  <span m='5095150'>of</span> <span m='5095260'>F16.</span> <span m='5096640'>The</span>
  <span m='5096820'>only</span> <span m='5097140'>other</span> <span m='5097410'>possible</span>
  <span m='5097870'>degree</span> <span m='5098250'>we could</span> <span m='5098580'>have</span>
  <span m='5098800'>is</span> <span m='5098970'>4.</span> <span m='5099810'>So</span>
  <span m='5100040'>how</span> <span m='5100360'>many</span> <span m='5100920'>irreducible</span>
  <span m='5101650'>polynomials</span> <span m='5102330'>are</span> <span m='5102500'>there</span>
  <span m='5103190'>of</span> <span m='5103320'>degree</span> <span m='5103680'>4</span>
  <span m='5104100'>over</span> <span m='5104620'>in</span> <span m='5104840'>F</span>
  <span m='5105010'>2 of x?</span> <span m='5107460'>Must</span> <span m='5107620'>be</span>
  <span m='5107730'>three of them.</span> <span m='5108320'>And</span> <span m='5108510'>it</span>
  <span m='5108600'>always</span> <span m='5108860'>works</span> <span m='5109150'>out.</span>
  </p><p><span m='5111240'>So,</span> <span m='5111600'>from</span> <span m='5111820'>this</span>
  <span m='5112050'>you</span> <span m='5112220'>can</span> <span m='5112390'>get</span>
  <span m='5112510'>a</span> <span m='5112620'>closed-form</span> <span m='5113260'>combinatorial</span>
  <span m='5114330'>formula</span> <span m='5114900'>again</span> <span m='5115190'>in</span>
  <span m='5115360'>terms</span> <span m='5115690'>of</span> <span m='5115830'>the</span>
  <span m='5116440'>Mobius</span> <span m='5116830'>inversion</span> <span m='5117490'>formula.</span>
  <span m='5118720'>By</span> <span m='5119000'>doing</span> <span m='5119410'>a</span>
  <span m='5119470'>sieve</span> <span m='5119750'>or</span> <span m='5120030'>by</span>
  <span m='5120230'>some</span> <span m='5120530'>other</span> <span m='5120750'>method,</span>
  <span m='5121670'>you</span> <span m='5121840'>can</span> <span m='5122050'>find</span>
  <span m='5122450'>out</span> <span m='5122740'>that</span> <span m='5122970'>the</span>
  <span m='5128960'>three</span> <span m='5129200'>irreducible</span> <span m='5129940'>polynomials</span>
  <span m='5130720'>of</span> <span m='5130810'>degree</span> <span m='5131190'>4</span>
  <span m='5131770'>are</span> <span m='5131840'>those</span> <span m='5132200'>three</span>
  <span m='5133360'>and</span> <span m='5134990'>the</span> <span m='5135360'>corresponding</span>
  <span m='5136120'>roots</span> <span m='5136850'>for</span> <span m='5137010'>this</span>
  <span m='5137320'>one --</span> <span m='5138580'>if</span> <span m='5138750'>this</span>
  <span m='5138970'>is</span> <span m='5139200'>the</span> <span m='5139840'>irreducible</span>
  <span m='5140380'>polynomial</span> <span m='5140640'>you</span> <span m='5140900'>use</span>
  <span m='5141240'>to</span> <span m='5141360'>define</span> <span m='5141790'>the</span>
  <span m='5141880'>field,</span> <span m='5142340'>then</span> <span m='5142540'>alpha</span>
  <span m='5143030'>is</span> <span m='5143230'>a</span> <span m='5143300'>root</span>
  <span m='5143530'>of</span> <span m='5143700'>it</span> <span m='5144530'>and</span>
  <span m='5144680'>you're going</span> <span m='5144970'>to get</span> <span m='5145230'>alpha,</span>
  <span m='5146370'>alpha</span> <span m='5146700'>squared,</span> <span m='5147660'>alpha</span>
  <span m='5148000'>fourth,</span> <span m='5149060'>alpha</span> <span m='5149380'>to
  the</span> <span m='5149600'>eightth.</span> <span m='5150560'>Alpha</span> <span
  m='5150770'>to the</span> <span m='5150920'>eightth</span> <span m='5151170'>squared</span>
  <span m='5151620'>is</span> <span m='5151730'>alpha</span> <span m='5151950'>to</span>
  <span m='5152040'>the</span> <span m='5152120'>16th,</span> <span m='5152530'>but</span>
  <span m='5152940'>that</span> <span m='5153110'>equals</span> <span m='5153450'>alpha,</span>
  <span m='5154810'>OK?</span> </p><p><span m='5155240'>So</span> <span m='5155470'>these</span>
  <span m='5155800'>are</span> <span m='5155880'>the</span> <span m='5155990'>roots</span>
  <span m='5156340'>of</span> <span m='5156410'>that</span> <span m='5157000'>equation.</span>
  <span m='5158670'>Here</span> <span m='5159010'>you</span> <span m='5159180'>get
  --</span> <span m='5162740'>sorry,</span> <span m='5163250'>x</span> <span m='5163520'>fourth</span>
  <span m='5163850'>plus</span> <span m='5164100'>x</span> <span m='5164340'>third</span>
  <span m='5164640'>plus</span> <span m='5164930'>1,</span> <span m='5165720'>since</span>
  <span m='5165990'>that's</span> <span m='5166310'>basically</span> <span m='5166940'>the</span>
  <span m='5167530'>reverse</span> <span m='5168300'>of</span> <span m='5168420'>this,</span>
  <span m='5169550'>turns</span> <span m='5169910'>out</span> <span m='5170350'>you</span>
  <span m='5170520'>get</span> <span m='5170690'>alpha</span> <span m='5170940'>to</span>
  <span m='5171010'>the</span> <span m='5171160'>minus</span> <span m='5171600'>1,</span>
  <span m='5172060'>which</span> <span m='5172340'>is</span> <span m='5173120'>alpha</span>
  <span m='5173600'>to</span> <span m='5173820'>the</span> <span m='5173960'>1fourth.</span>
  <span m='5176070'>Square</span> <span m='5176560'>that</span> <span m='5177340'>and</span>
  <span m='5177580'>you</span> <span m='5177720'>get</span> <span m='5177970'>alpha</span>
  <span m='5178350'>to the</span> <span m='5178550'>minus</span> <span m='5178980'>2,</span>
  <span m='5179280'>which</span> <span m='5179510'>is</span> <span m='5179640'>alpha</span>
  <span m='5179860'>to</span> <span m='5180000'>the</span> <span m='5180120'>13th,</span>
  <span m='5180930'>or</span> <span m='5181040'>equivalently,</span> <span m='5181670'>alpha</span>
  <span m='5181930'>to</span> <span m='5182060'>the</span> <span m='5182180'>28 --</span>
  <span m='5182950'>reduces</span> <span m='5183520'>to</span> <span m='5184010'>thirteen.</span>
  <span m='5185320'>This</span> <span m='5185620'>becomes</span> <span m='5186090'>alpha</span>
  <span m='5186410'>the</span> <span m='5186540'>11th,</span> <span m='5187600'>alpha</span>
  <span m='5188020'>to</span> <span m='5188210'>the</span> <span m='5188360'>seventh.</span>
  <span m='5188980'>and</span> <span m='5189070'>then</span> <span m='5189220'>alpha</span>
  <span m='5189420'>to</span> <span m='5189570'>the</span> <span m='5189810'>seventh</span>
  <span m='5190350'>gives you</span> <span m='5190620'>alpha to</span> <span m='5190840'>the</span>
  <span m='5191050'>1fourth</span> <span m='5191640'>again.</span> </p><p><span m='5191930'>AUDIENCE:</span>
  <span m='5192422'>[INAUDIBLE]</span> <span m='5193898'>same</span> <span m='5194390'>thing</span>
  <span m='5194882'>about</span> <span m='5195374'>taking the</span> <span m='5195866'>square</span>
  <span m='5196358'>[INAUDIBLE]?</span> </p><p><span m='5199310'>PROFESSOR:</span>
  <span m='5199802'>Correct.</span> </p><p><span m='5200294'>AUDIENCE:</span> <span
  m='5200786'> --from the</span> <span m='5201278'>[INAUDIBLE]?</span> </p><p><span
  m='5201770'>PROFESSOR:</span> <span m='5202770'>Because</span> <span m='5204320'>you
  go</span> <span m='5204590'>around</span> <span m='5204760'>in a</span> <span m='5204930'>circle.</span>
  <span m='5205390'>So</span> <span m='5205600'>it's</span> <span m='5205730'>a</span>
  <span m='5205780'>finite</span> <span m='5206270'>set.</span> <span m='5207090'>So</span>
  <span m='5207390'>you</span> <span m='5207630'>can</span> <span m='5208510'>obviously</span>
  <span m='5208950'>divide</span> <span m='5209300'>by</span> <span m='5209470'>2.</span>
  <span m='5211160'>So</span> <span m='5212740'>there's</span> <span m='5213070'>one</span>
  <span m='5213400'>cyclotomic</span> <span m='5214190'>coset.</span> <span m='5214840'>Here's</span>
  <span m='5215090'>the</span> <span m='5215330'>second</span> <span m='5215570'>one.</span>
  <span m='5216540'>And</span> <span m='5216750'>then</span> <span m='5216920'>the</span>
  <span m='5217010'>third</span> <span m='5217340'>one</span> <span m='5217550'>must</span>
  <span m='5217790'>be</span> <span m='5217910'>whatever's</span> <span m='5218320'>left</span>
  <span m='5218600'>over.</span> <span m='5218960'>What's</span> <span m='5219210'>left</span>
  <span m='5219460'>over?</span> <span m='5219710'>We</span> <span m='5219850'>don't</span>
  <span m='5220000'>have</span> <span m='5220220'>alpha</span> <span m='5220590'>to
  the</span> <span m='5220710'>third</span> <span m='5221090'>yet.</span> <span m='5222040'>Alpha</span>
  <span m='5222230'>to</span> <span m='5222390'>the</span> <span m='5222610'>third,</span>
  <span m='5223710'>alpha</span> <span m='5224170'>to</span> <span m='5224390'>the</span>
  <span m='5224540'>sixth,</span> <span m='5225720'>alpha</span> <span m='5226110'>to</span>
  <span m='5226310'>the</span> <span m='5226470'>12th,</span> <span m='5227680'>and</span>
  <span m='5227920'>then</span> <span m='5228110'>alpha</span> <span m='5228590'>to</span>
  <span m='5228730'>the</span> <span m='5228880'>2fourth,</span> <span m='5229680'>which</span>
  <span m='5229910'>is</span> <span m='5230040'>alpha</span> <span m='5230350'>to</span>
  <span m='5230450'>the</span> <span m='5230600'>ninth.</span> <span m='5231740'>And</span>
  <span m='5232160'>alpha</span> <span m='5232600'>to</span> <span m='5232880'>the</span>
  <span m='5233100'>18th</span> <span m='5233750'>is</span> <span m='5233960'>equal</span>
  <span m='5234480'>alpha</span> <span m='5234730'>to the third</span> <span m='5235120'>again.</span>
  </p><p><span m='5238190'>OK,</span> <span m='5239410'>what's</span> <span m='5239680'>the</span>
  <span m='5239770'>moral</span> <span m='5240170'>of this?</span> <span m='5241120'>We</span>
  <span m='5241240'>want</span> <span m='5241430'>to</span> <span m='5241480'>start</span>
  <span m='5241850'>off</span> <span m='5243100'>with --</span> <span m='5243660'>let's</span>
  <span m='5243910'>just</span> <span m='5244180'>take</span> <span m='5244400'>a</span>
  <span m='5244450'>look</span> <span m='5244640'>at</span> <span m='5244730'>the</span>
  <span m='5244820'>Reed-Solomon,</span> <span m='5245850'>the</span> <span m='5245930'>very</span>
  <span m='5246180'>first</span> <span m='5246560'>one.</span> <span m='5247380'>We</span>
  <span m='5247490'>just</span> <span m='5247710'>want</span> <span m='5248030'>n</span>
  <span m='5248230'>minus</span> <span m='5248560'>k</span> <span m='5248780'>to</span>
  <span m='5248860'>be</span> <span m='5249000'>1</span> <span m='5250290'>and</span>
  <span m='5250640'>we</span> <span m='5250790'>just</span> <span m='5251020'>want</span>
  <span m='5251170'>to</span> <span m='5251210'>have</span> <span m='5251400'>root</span>
  <span m='5251680'>alpha</span> <span m='5251945'>in</span> <span m='5252210'>here.</span>
  <span m='5254695'>Well,</span> <span m='5255140'>if</span> <span m='5255230'>we</span>
  <span m='5255290'>get</span> <span m='5255480'>root</span> <span m='5255720'>alpha,</span>
  <span m='5257460'>we're</span> <span m='5257630'>going to get</span> <span m='5257980'>root</span>
  <span m='5258270'>alpha</span> <span m='5258660'>squared,</span> <span m='5259160'>alpha</span>
  <span m='5259430'>fourth</span> <span m='5259870'>and</span> <span m='5262560'>alpha</span>
  <span m='5262860'>eightth</span> <span m='5264100'>along</span> <span m='5264450'>with</span>
  <span m='5264640'>it.</span> <span m='5265070'>If</span> <span m='5265510'>we</span>
  <span m='5265630'>want</span> <span m='5265790'>a</span> <span m='5265840'>binary</span>
  <span m='5266350'>polynomial</span> <span m='5267180'>with root</span> <span m='5267570'>alpha,</span>
  <span m='5267940'>it</span> <span m='5268080'>has</span> <span m='5268380'>to</span>
  <span m='5268510'>this</span> <span m='5268800'>one.</span> <span m='5269065'>And</span>
  <span m='5269330'>it's</span> <span m='5269590'>going</span> <span m='5269690'>to</span>
  <span m='5269730'>have</span> <span m='5269890'>four</span> <span m='5270320'>roots.</span>
  <span m='5272250'>All</span> <span m='5272350'>right.</span> </p><p><span m='5272700'>So</span>
  <span m='5275050'>for</span> <span m='5275930'>root</span> <span m='5278650'>alpha,</span>
  <span m='5280770'>we're</span> <span m='5280910'>going</span> <span m='5281040'>to</span>
  <span m='5281130'>get</span> <span m='5281970'>x</span> <span m='5283350'>fourth</span>
  <span m='5283920'>plus</span> <span m='5284360'>x</span> <span m='5284680'>plus</span>
  <span m='5285000'>1</span> <span m='5285370'>as</span> <span m='5285550'>our</span>
  <span m='5285670'>generator</span> <span m='5286210'>polynomial.</span> <span m='5287840'>And</span>
  <span m='5288090'>it's</span> <span m='5288280'>actually</span> <span m='5288630'>going</span>
  <span m='5288760'>to have</span> <span m='5288890'>roots</span> <span m='5289260'>alpha</span>
  <span m='5289630'>and</span> <span m='5289740'>alpha</span> <span m='5290080'>squared.</span>
  <span m='5291190'>So</span> <span m='5291370'>it's</span> <span m='5291510'>going</span>
  <span m='5291620'>to</span> <span m='5291660'>be</span> <span m='5291720'>the</span>
  <span m='5291850'>same</span> <span m='5292240'>one</span> <span m='5292620'>as
  you</span> <span m='5292870'>would</span> <span m='5293040'>get</span> <span m='5293270'>if</span>
  <span m='5293400'>you</span> <span m='5293540'>wanted</span> <span m='5293830'>alpha</span>
  <span m='5294180'>and</span> <span m='5294280'>alpha</span> <span m='5294600'>squared.</span>
  <span m='5295860'>That</span> <span m='5296030'>means</span> <span m='5296700'>n</span>
  <span m='5296890'>minus</span> <span m='5297300'>k</span> <span m='5301340'>is</span>
  <span m='5301510'>already</span> <span m='5301790'>up</span> <span m='5301930'>to</span>
  <span m='5302080'>2,</span> <span m='5303280'>which</span> <span m='5303480'>means</span>
  <span m='5303700'>your</span> <span m='5303850'>distance</span> <span m='5304180'>is</span>
  <span m='5304590'>already</span> <span m='5304930'>up</span> <span m='5305100'>to</span>
  <span m='5305240'>3.</span> <span m='5306900'>Distance</span> <span m='5307170'>is</span>
  <span m='5307440'>n</span> <span m='5307570'>minus</span> <span m='5307920'>k</span>
  <span m='5308110'>plus</span> <span m='5308470'>1.</span> <span m='5309760'>So</span>
  <span m='5310110'>this</span> <span m='5310610'>leads</span> <span m='5311060'>to</span>
  <span m='5311240'>a</span> <span m='5311340'>code</span> <span m='5311890'>with</span>
  <span m='5312860'>n</span> <span m='5313360'>equals</span> <span m='5314260'>16
  --</span> <span m='5316630'>is that</span> <span m='5317070'>right?</span> <span
  m='5317850'>Yes.</span> <span m='5320920'>BCH</span> <span m='5321510'>codes</span>
  <span m='5321810'>are always</span> <span m='5322210'>defined</span> <span m='5322650'>to</span>
  <span m='5322710'>be</span> <span m='5322840'>one</span> <span m='5323500'>shorter.</span>
  <span m='5325420'>We're</span> <span m='5325630'>going</span> <span m='5325730'>to</span>
  <span m='5325850'>have</span> <span m='5325960'>four</span> <span m='5326440'>redundant</span>
  <span m='5327000'>bits,</span> <span m='5327370'>so</span> <span m='5328040'>k</span>
  <span m='5328330'>equals</span> <span m='5328760'>12</span> <span m='5338660'>and</span>
  <span m='5340050'>distance</span> <span m='5340600'>equals</span> <span m='5341070'>3.</span>
  </p><p><span m='5344530'>I</span> <span m='5344610'>think</span> <span m='5344890'>that's</span>
  <span m='5345180'>not</span> <span m='5345340'>quite</span> <span m='5345670'>right.</span>
  <span m='5351430'>When</span> <span m='5351870'>we're</span> <span m='5352000'>doing</span>
  <span m='5352840'>BCH</span> <span m='5353610'>codes,</span> <span m='5353960'>they're</span>
  <span m='5354140'>always</span> <span m='5354400'>defined</span> <span m='5355910'>just</span>
  <span m='5356300'>on</span> <span m='5356490'>the</span> <span m='5356680'>non-zero</span>
  <span m='5357580'>elements</span> <span m='5358040'>of</span> <span m='5358110'>the</span>
  <span m='5358210'>field.</span> <span m='5360630'>So</span> <span m='5364050'>we</span>
  <span m='5364210'>start</span> <span m='5364500'>with</span> <span m='5364610'>the</span>
  <span m='5364690'>shorter</span> <span m='5365060'>Read-Solomon</span> <span m='5365730'>code</span>
  <span m='5367820'>of</span> <span m='5368090'>length</span> <span m='5368850'>q</span>
  <span m='5369070'>minus</span> <span m='5369430'>1.</span> <span m='5370960'>15</span>
  <span m='5371480'>in</span> <span m='5371600'>this</span> <span m='5371820'>case</span>
  <span m='5372160'>rather</span> <span m='5372450'>than</span> <span m='5372590'>16.</span>
  <span m='5375600'>And</span> <span m='5376890'>0</span> <span m='5377210'>never</span>
  <span m='5377530'>appears</span> <span m='5378010'>here</span> <span m='5378340'>as</span>
  <span m='5378470'>one</span> <span m='5378640'>of</span> <span m='5378690'>the</span>
  <span m='5378780'>possible</span> <span m='5379340'>roots.</span> <span m='5381530'>So</span>
  <span m='5381750'>let</span> <span m='5381910'>me</span> <span m='5382060'>just</span>
  <span m='5382350'>do</span> <span m='5382530'>that.</span> <span m='5382900'>I</span>
  <span m='5383430'>apologize</span> <span m='5384220'>I</span> <span m='5384290'>haven't</span>
  <span m='5385500'>carried</span> <span m='5385850'>through</span> <span m='5386080'>all</span>
  <span m='5386170'>the</span> <span m='5386260'>possible</span> <span m='5386800'>steps.</span>
  <span m='5388110'>So</span> <span m='5388290'>we're</span> <span m='5388750'>getting</span>
  <span m='5389130'>all</span> <span m='5389460'>of</span> <span m='5389630'>the</span>
  <span m='5390590'>polynomial</span> <span m='5391090'>multiples</span> <span m='5391620'>of</span>
  <span m='5391760'>x</span> <span m='5392000'>fourth</span> <span m='5392340'>plus</span>
  <span m='5392710'>x</span> <span m='5393920'>plus</span> <span m='5394670'>1</span>
  <span m='5395660'>of</span> <span m='5396080'>degree</span> <span m='5396480'>less</span>
  <span m='5396780'>or</span> <span m='5396890'>equal</span> <span m='5397140'>to</span>
  <span m='5397230'>14</span> <span m='5397920'>rather</span> <span m='5398210'>than</span>
  <span m='5398340'>15.</span> <span m='5399560'>So</span> <span m='5399790'>it's</span>
  <span m='5399960'>n</span> <span m='5400180'>equals</span> <span m='5400480'>15.</span>
  <span m='5401610'>n</span> <span m='5401820'>minus</span> <span m='5402240'>k</span>
  <span m='5403270'>is</span> <span m='5404300'>going</span> <span m='5404420'>to</span>
  <span m='5404540'>be</span> <span m='5404650'>4.</span> <span m='5405610'>So</span>
  <span m='5405770'>this</span> <span m='5406010'>is</span> <span m='5406100'>11.</span>
  <span m='5407220'>And</span> <span m='5407400'>the</span> <span m='5407480'>distance</span>
  <span m='5408210'>is</span> <span m='5408490'>going</span> <span m='5408670'>to</span>
  <span m='5408730'>be</span> <span m='5408890'>greater</span> <span m='5409370'>than</span>
  <span m='5409580'>equal</span> <span m='5409930'>to</span> <span m='5410110'>3.</span>
  <span m='5411280'>In fact,</span> <span m='5411630'>it is</span> <span m='5411980'>3.</span>
  <span m='5413160'>So</span> <span m='5413370'>it's</span> <span m='5413650'>a</span>
  <span m='5413810'>15,</span> <span m='5414530'>11,</span> <span m='5415820'>3</span>
  <span m='5416160'>code,</span> <span m='5417440'>which</span> <span m='5417930'>is,</span>
  <span m='5418060'>in</span> <span m='5418160'>fact,</span> <span m='5418530'>the</span>
  <span m='5418610'>Hamming</span> <span m='5418950'>code.</span> <span m='5420040'>Yes?</span>
  </p><p><span m='5420450'>AUDIENCE:</span> <span m='5420900'>[INAUDIBLE]</span> </p><p><span
  m='5421350'>PROFESSOR:</span> <span m='5421800'>Oh,</span> <span m='5422555'>I'm</span>
  <span m='5422920'>sorry.</span> <span m='5424110'>Wasn't</span> <span m='5424320'>this</span>
  <span m='5424510'>fun?</span> <span m='5427080'>You're</span> <span m='5427220'>supposed</span>
  <span m='5427410'>to</span> <span m='5427600'>do</span> <span m='5427750'>that,</span>
  <span m='5428150'>Ashish.</span> </p><p><span m='5428592'>AUDIENCE:</span> <span
  m='5429034'>[INAUDIBLE].</span> </p><p><span m='5429476'>PROFESSOR:</span> <span
  m='5429920'>OK,</span> <span m='5430510'>well,</span> <span m='5432550'>so</span>
  <span m='5432710'>you</span> <span m='5432840'>can</span> <span m='5432960'>see</span>
  <span m='5433150'>how</span> <span m='5433280'>it</span> <span m='5433430'>goes.</span>
  <span m='5434420'>So</span> <span m='5434580'>this</span> <span m='5434810'>gets</span>
  <span m='5435080'>us</span> <span m='5435260'>both</span> <span m='5435550'>roots</span>
  <span m='5435990'>alpha</span> <span m='5436360'>and</span> <span m='5436450'>alpha</span>
  <span m='5436760'>squared.</span> <span m='5437770'>If</span> <span m='5437920'>we</span>
  <span m='5438030'>want</span> <span m='5438500'>alpha</span> <span m='5438950'>third</span>
  <span m='5439730'>and</span> <span m='5440140'>alpha</span> <span m='5440570'>fourth,</span>
  <span m='5441080'>we</span> <span m='5441280'>already</span> <span m='5441580'>have</span>
  <span m='5442540'>alpha</span> <span m='5442860'>fourth</span> <span m='5443340'>from</span>
  <span m='5443550'>this</span> <span m='5443810'>polynomial.</span> <span m='5445000'>So</span>
  <span m='5445210'>all</span> <span m='5445360'>we</span> <span m='5445460'>need</span>
  <span m='5445720'>is</span> <span m='5445880'>this</span> <span m='5446150'>one,</span>
  <span m='5447090'>which</span> <span m='5447330'>gets</span> <span m='5447590'>us</span>
  <span m='5447780'>another.</span> <span m='5449800'>And</span> <span m='5450080'>that</span>
  <span m='5450300'>gives</span> <span m='5450590'>us</span> <span m='5450780'>an</span>
  <span m='5450950'>n</span> <span m='5451150'>equals</span> <span m='5451620'>15,</span>
  <span m='5452715'>k</span> <span m='5452970'>equals</span> <span m='5453430'>7,</span>
  <span m='5454550'>d</span> <span m='5454940'>greater than or</span> <span m='5455280'>equal</span>
  <span m='5455550'>to</span> <span m='5455630'>5,</span> <span m='5456320'>which,</span>
  <span m='5456500'>in fact,</span> <span m='5456900'>is</span> <span m='5457270'>a</span>
  <span m='5457763'>15,</span> <span m='5458256'>7,</span> <span m='5458750'>5</span>
  <span m='5459200'>code.</span> <span m='5461170'>So</span> <span m='5461900'>we</span>
  <span m='5462500'>get</span> <span m='5462690'>additional</span> <span m='5463150'>codes.</span>
  <span m='5463620'>There's</span> <span m='5463780'>a</span> <span m='5463840'>table</span>
  <span m='5464230'>in</span> <span m='5464320'>there</span> <span m='5464570'>that</span>
  <span m='5464670'>shows</span> <span m='5465010'>you</span> <span m='5465120'>that</span>
  <span m='5465300'>most</span> <span m='5465650'>the</span> <span m='5465780'>time</span>
  <span m='5466130'>for</span> <span m='5466270'>short</span> <span m='5466600'>block</span>
  <span m='5466950'>lengths</span> <span m='5467730'>for</span> <span m='5468410'>distances</span>
  <span m='5468970'>which</span> <span m='5469180'>are</span> <span m='5469260'>equal</span>
  <span m='5469580'>to</span> <span m='5469720'>a</span> <span m='5469790'>prime</span>
  <span m='5470150'>power,</span> <span m='5470990'>we</span> <span m='5471160'>get</span>
  <span m='5471360'>the</span> <span m='5471450'>same</span> <span m='5471730'>parameters</span>
  <span m='5472060'>as</span> <span m='5472390'>Reed-Muller</span> <span m='5472920'>codes.</span>
  <span m='5473320'>For</span> <span m='5474030'>lengths</span> <span m='5474290'>64</span>
  <span m='5474980'>and</span> <span m='5475040'>higher,</span> <span m='5475400'>sometimes</span>
  <span m='5475840'>we</span> <span m='5475940'>do</span> <span m='5476070'>a</span>
  <span m='5476120'>little</span> <span m='5476320'>bit</span> <span m='5476500'>better.</span>
  </p><p><span m='5477300'>In</span> <span m='5477390'>addition,</span> <span m='5477670'>we</span>
  <span m='5477740'>get</span> <span m='5477870'>a</span> <span m='5477940'>lot</span>
  <span m='5478170'>more</span> <span m='5478470'>codes</span> <span m='5478980'>for</span>
  <span m='5479240'>every,</span> <span m='5481130'>basically,</span> <span m='5481560'>odd</span>
  <span m='5481880'>distance</span> <span m='5482380'>when</span> <span m='5482510'>you</span>
  <span m='5482600'>take</span> <span m='5482880'>the</span> <span m='5482960'>length</span>
  <span m='5483230'>odd</span> <span m='5483680'>or</span> <span m='5483800'>even</span>
  <span m='5484130'>distance</span> <span m='5484630'>if</span> <span m='5484740'>you</span>
  <span m='5485180'>take</span> <span m='5485420'>the</span> <span m='5485520'>length</span>
  <span m='5485820'>even.</span> <span m='5490010'>And</span> <span m='5490170'>that's</span>
  <span m='5490480'>definitely</span> <span m='5490820'>an</span> <span m='5490890'>asset,</span>
  <span m='5491390'>that</span> <span m='5491520'>you</span> <span m='5491690'>have</span>
  <span m='5491850'>a</span> <span m='5491940'>larger</span> <span m='5492670'>number</span>
  <span m='5493010'>of</span> <span m='5493100'>codes</span> <span m='5493470'>to</span>
  <span m='5493620'>choose</span> <span m='5493960'>from.</span> <span m='5494620'>So</span>
  <span m='5495110'>there's</span> <span m='5495320'>no</span> <span m='5495490'>doubt</span>
  <span m='5495830'>that</span> <span m='5495950'>in</span> <span m='5496090'>terms</span>
  <span m='5496420'>n,</span> <span m='5496540'>k,</span> <span m='5496760'>d,</span>
  <span m='5497280'>BCH</span> <span m='5498010'>is</span> <span m='5498130'>the</span>
  <span m='5498210'>larger</span> <span m='5498800'>and,</span> <span m='5499620'>for</span>
  <span m='5500040'>longer</span> <span m='5500360'>block</span> <span m='5500660'>length,</span>
  <span m='5500910'>slightly</span> <span m='5501690'>better</span> <span m='5501980'>class</span>
  <span m='5502480'>than</span> <span m='5502590'>Reed-Muller</span> <span m='5503080'>codes.</span>
  <span m='5503750'>But</span> <span m='5503980'>as</span> <span m='5504110'>I</span>
  <span m='5504180'>said</span> <span m='5504420'>before,</span> <span m='5504850'>in</span>
  <span m='5504930'>terms</span> <span m='5505200'>of</span> <span m='5505280'>performance</span>
  <span m='5505780'>versus</span> <span m='5506110'>complexity,</span> <span m='5507330'>Reed-Muller</span>
  <span m='5507770'>might</span> <span m='5508020'>still</span> <span m='5508230'>be</span>
  <span m='5508340'>the</span> <span m='5508450'>ones</span> <span m='5508690'>you</span>
  <span m='5508830'>want</span> <span m='5508950'>to</span> <span m='5508990'>use.</span>
  <span m='5509730'>OK.</span> <span m='5510220'>Good</span> <span m='5510390'>luck</span>
  <span m='5510680'>in</span> <span m='5510850'>the</span> <span m='5510950'>review</span>
  <span m='5511490'>and</span> <span m='5511820'>good luck</span> <span m='5512030'>in
  the</span> <span m='5512120'>exam.</span> <span m='5512640'>I</span> <span m='5512700'>will</span>
  <span m='5512820'>see</span> <span m='5513010'>you</span> <span m='5513120'>Wednesday.</span>
  </p>
type: course
uid: e809be35f6c976eaf8e0103a99ec2ec0

---
None