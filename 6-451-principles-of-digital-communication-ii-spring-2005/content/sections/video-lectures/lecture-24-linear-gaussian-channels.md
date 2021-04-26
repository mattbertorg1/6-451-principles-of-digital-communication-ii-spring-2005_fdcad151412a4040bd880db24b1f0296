---
about_this_resource_text: '<p><strong>Topics covered:</strong> Linear Gaussian Channels</p><p><strong>Instructor:
  </strong>Prof. David Forney</p>'
course_id: 6-451-principles-of-digital-communication-ii-spring-2005
embedded_media:
- id: 24.jpg
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-24-linear-gaussian-channels/24.jpg
  title: 24.jpg
  type: null
  uid: 02535788c876bc64a6fadcb80f3cab22
- id: Video-YouTube-Stream
  media_location: CxgU2Gtg5ro
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Video-YouTube-Stream
  type: Video
  uid: 3c9f51ff2165b8138f562a697bb3c47d
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/CxgU2Gtg5ro/default.jpg
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b6a52dfb2c61c2c7ee19ed90d8179c9c
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597857
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Video-iTunes U-MP4
  type: Video
  uid: 0437e6942a2b2ace2046b44c7a544fe4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.451S05/24ocw-6.451_4-261-09may2005-220k.mp4
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3e31ff26bdf5cee93fb2804b90c0f42c
- id: Thumbnail-OCW-JPG
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: efbe9026537a3d720a5df3a968695741
- id: 3Play-3PlayYouTubeid-MP4
  media_location: CxgU2Gtg5ro
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: da7803764cb066a3920648629c711387
- id: CxgU2Gtg5ro.srt
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-24-linear-gaussian-channels/CxgU2Gtg5ro.srt
  title: 3play caption file
  type: null
  uid: 3d17eb0cc8732729607664b17cd98cb2
- id: CxgU2Gtg5ro.pdf
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-24-linear-gaussian-channels/CxgU2Gtg5ro.pdf
  title: 3play pdf file
  type: null
  uid: 426c3acf789058f3ca67b31cecb802b5
- id: Caption-3Play YouTube id-SRT
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1513efeed8a57dcc8f277ea6b32483c0
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e820ac2029ca835efefcae6ea0b8feb5
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 8b52a81cde7cfeecef38ead798ff9a33
inline_embed_id: 26206835lecture24:lineargaussianchannels62805513
layout: video
order_index: null
parent_uid: 73f9a1c91575f1a3abda44e7358df3a2
related_resources_text: ''
short_url: lecture-24-linear-gaussian-channels
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-24-linear-gaussian-channels
template_type: Tabbed
title: 'Lecture 24: Linear Gaussian Channels'
transcript: '<p><span m=''1620''>PROFESSOR: Today</span> <span m=''2130''>we</span>
  <span m=''3110''>finish</span> <span m=''3490''>up</span> <span m=''3790''>chapter</span>
  <span m=''4150''>13.</span> <span m=''4730''>I</span> <span m=''4770''>think</span>
  <span m=''4960''>we</span> <span m=''5110''>are</span> <span m=''5280''>finished,</span>
  <span m=''5720''>but</span> <span m=''5840''>I''ll</span> <span m=''6050''>take</span>
  <span m=''6260''>questions.</span> <span m=''7700''>We</span> <span m=''7870''>get</span>
  <span m=''8029''>into</span> <span m=''8189''>chapter</span> <span m=''8570''>14,</span>
  <span m=''9240''>which</span> <span m=''9630''>starts</span> <span m=''10070''>to</span>
  <span m=''10180''>get</span> <span m=''10380''>into</span> <span m=''11320''>coding</span>
  <span m=''11670''>for</span> <span m=''12520''>bandwidth-limited</span> <span m=''13890''>channels.</span>
  <span m=''15440''>Here</span> <span m=''15890''>we''re</span> <span m=''16230''>coding</span>
  <span m=''16630''>directly</span> <span m=''17140''>in</span> <span m=''17310''>terms</span>
  <span m=''17710''>of</span> <span m=''17860''>Euclidean</span> <span m=''18380''>space</span>
  <span m=''18910''>rather</span> <span m=''19230''>than</span> <span m=''19780''>in</span>
  <span m=''19930''>terms</span> <span m=''20280''>of</span> <span m=''20390''>Hamming</span>
  <span m=''20710''>space.</span> <span m=''21200''>And</span> <span m=''21300''>there''s</span>
  <span m=''21530''>this</span> <span m=''21670''>wonderful</span> <span m=''22970''>quote</span>
  <span m=''23320''>from</span> <span m=''23450''>Neil</span> <span m=''23710''>Sloane.</span>
  <span m=''24150''>&quot;Euclidean</span> <span m=''24620''>space</span> <span m=''25000''>coding</span>
  <span m=''25400''>is</span> <span m=''25455''>to</span> <span m=''25510''>Hamming</span>
  <span m=''25810''>space</span> <span m=''26210''>coding</span> <span m=''26990''>as</span>
  <span m=''27110''>classical</span> <span m=''27670''>music</span> <span m=''28050''>is</span>
  <span m=''28260''>to</span> <span m=''28380''>rock''n''roll.&quot;</span> <span
  m=''29960''>Meaning</span> <span m=''30400''>that,</span> <span m=''31510''>in</span>
  <span m=''31660''>the</span> <span m=''31850''>Euclidean</span> <span m=''32170''>space,</span>
  <span m=''32590''>things</span> <span m=''32840''>are</span> <span m=''32920''>continuous,</span>
  <span m=''33980''>whereas</span> <span m=''34650''>we</span> <span m=''34740''>were</span>
  <span m=''34830''>discrete</span> <span m=''35390''>back</span> <span m=''35670''>in</span>
  <span m=''35760''>Hamming</span> <span m=''36070''>space.</span> </p><p><span m=''36950''>Nonetheless,</span>
  <span m=''37580''>there</span> <span m=''37770''>are</span> <span m=''38300''>strong</span>
  <span m=''38750''>connections</span> <span m=''39410''>between</span> <span m=''39780''>the</span>
  <span m=''39900''>two,</span> <span m=''42110''>which</span> <span m=''43100''>in</span>
  <span m=''43310''>two</span> <span m=''43480''>lectures</span> <span m=''43980''>I''ll</span>
  <span m=''44060''>basically</span> <span m=''45560''>only</span> <span m=''45880''>have</span>
  <span m=''45970''>a</span> <span m=''46060''>chance</span> <span m=''46420''>to</span>
  <span m=''46610''>hint</span> <span m=''46710''>at.</span> <span m=''48830''>You</span>
  <span m=''49030''>were</span> <span m=''49880''>supposed</span> <span m=''50270''>to</span>
  <span m=''50350''>hand</span> <span m=''50650''>in</span> <span m=''50820''>problem</span>
  <span m=''51150''>set</span> <span m=''51590''>nine</span> <span m=''51980''>last</span>
  <span m=''52370''>Friday,</span> <span m=''52860''>or</span> <span m=''53270''>today</span>
  <span m=''53690''>if</span> <span m=''53820''>you</span> <span m=''53920''>haven''t</span>
  <span m=''54220''>already.</span> <span m=''56090''>Today,</span> <span m=''56170''>we''ll</span>
  <span m=''56500''>hand</span> <span m=''56730''>out</span> <span m=''56880''>the</span>
  <span m=''56990''>solutions</span> <span m=''57620''>for</span> <span m=''57770''>nine,</span>
  <span m=''58800''>and</span> <span m=''59010''>then</span> <span m=''59220''>chapter</span>
  <span m=''59610''>14</span> <span m=''60130''>and</span> <span m=''60290''>its</span>
  <span m=''60510''>problems,</span> <span m=''60940''>which</span> <span m=''61100''>are</span>
  <span m=''61170''>problem</span> <span m=''61620''>set</span> <span m=''61780''>10.</span>
  <span m=''62060''>These</span> <span m=''62350''>are</span> <span m=''62960''>not</span>
  <span m=''63830''>due.</span> <span m=''64610''>As</span> <span m=''65150''>always,</span>
  <span m=''65450''>I</span> <span m=''65519''>recommend</span> <span m=''66020''>you</span>
  <span m=''66150''>do</span> <span m=''66390''>them.</span> <span m=''68060''>The</span>
  <span m=''68110''>solutions</span> <span m=''68710''>will</span> <span m=''68800''>be</span>
  <span m=''68950''>handed</span> <span m=''69250''>out</span> <span m=''69420''>Wednesday.</span>
  </p><p><span m=''71650''>However,</span> <span m=''72060''>on</span> <span m=''72200''>the</span>
  <span m=''72340''>exam,</span> <span m=''72890''>the</span> <span m=''73000''>exam</span>
  <span m=''73390''>will</span> <span m=''73490''>not</span> <span m=''73740''>cover</span>
  <span m=''74020''>chapter</span> <span m=''74370''>14.</span> <span m=''76000''>So</span>
  <span m=''77900''>everything</span> <span m=''78220''>we</span> <span m=''78320''>do</span>
  <span m=''78480''>this</span> <span m=''78680''>week</span> <span m=''78970''>is</span>
  <span m=''79090''>gravy.</span> <span m=''81040''>The</span> <span m=''81260''>exam</span>
  <span m=''81800''>is</span> <span m=''82220''>a</span> <span m=''82290''>week</span>
  <span m=''82550''>from</span> <span m=''82730''>tomorrow</span> <span m=''83280''>in</span>
  <span m=''83370''>the</span> <span m=''83470''>morning.</span> <span m=''85180''>Ashish</span>
  <span m=''85700''>will</span> <span m=''85930''>administer</span> <span m=''86500''>it</span>
  <span m=''86620''>because</span> <span m=''86830''>I</span> <span m=''86920''>won''t</span>
  <span m=''87170''>be</span> <span m=''87300''>here.</span> <span m=''88960''>For</span>
  <span m=''89120''>this</span> <span m=''89700''>exam,</span> <span m=''90260''>it''s</span>
  <span m=''90800''>closed</span> <span m=''91210''>book,</span> <span m=''91540''>except</span>
  <span m=''91970''>you''re</span> <span m=''92120''>allowed</span> <span m=''92500''>to</span>
  <span m=''92620''>make</span> <span m=''92900''>five</span> <span m=''93190''>pages</span>
  <span m=''93610''>of</span> <span m=''93730''>notes,</span> <span m=''95270''>as</span>
  <span m=''95460''>you</span> <span m=''95620''>did</span> <span m=''95860''>three</span>
  <span m=''96120''>pages</span> <span m=''96590''>on</span> <span m=''96680''>the</span>
  <span m=''96770''>midterm.</span> <span m=''98010''>And</span> <span m=''98410''>I</span>
  <span m=''98490''>do</span> <span m=''98700''>recommend</span> <span m=''99190''>you</span>
  <span m=''99310''>bring</span> <span m=''100050''>a</span> <span m=''100400''>calculator,</span>
  <span m=''102230''>because</span> <span m=''102430''>for one</span> <span m=''102590''>of</span>
  <span m=''102660''>the</span> <span m=''102730''>problems</span> <span m=''103190''>the</span>
  <span m=''103270''>calculator</span> <span m=''103780''>will</span> <span m=''103950''>be</span>
  <span m=''104080''>helpful.</span> <span m=''106490''>And</span> <span m=''107230''>I</span>
  <span m=''107300''>was</span> <span m=''107510''>told</span> <span m=''107930''>that</span>
  <span m=''107970''>erasable</span> <span m=''108600''>memory</span> <span m=''108980''>should</span>
  <span m=''109180''>be</span> <span m=''109390''>cleared</span> <span m=''109645''>on</span>
  <span m=''109900''>the</span> <span m=''109990''>calculator,</span> <span m=''110415''>so</span>
  <span m=''111980''>point</span> <span m=''112180''>of</span> <span m=''112450''>honor</span>
  <span m=''112540''>if</span> <span m=''112650''>you</span> <span m=''112760''>do</span>
  <span m=''112940''>that.</span> </p><p><span m=''115410''>Any</span> <span m=''115630''>questions</span>
  <span m=''116270''>about</span> <span m=''117590''>the</span> <span m=''118210''>exam</span>
  <span m=''118920''>or</span> <span m=''120120''>chapter</span> <span m=''120480''>13?</span>
  <span m=''122710''>Yes?</span> </p><p><span m=''123100''>AUDIENCE: Are</span> <span
  m=''123342''>you</span> <span m=''123585''>including</span> <span m=''124070''>the</span>
  <span m=''124312''>midterm</span> <span m=''124555''>[UNINTELLIGIBLE]?</span> </p><p><span
  m=''126010''>PROFESSOR: Yeah,</span> <span m=''126350''>oh,</span> <span m=''126640''>everything</span>
  <span m=''126990''>in</span> <span m=''127070''>the</span> <span m=''127150''>course</span>
  <span m=''128220''>up</span> <span m=''128490''>to</span> <span m=''128750''>chapter</span>
  <span m=''129130''>13.</span> <span m=''131730''>The</span> <span m=''131820''>rule</span>
  <span m=''132110''>is</span> <span m=''132380''>everything</span> <span m=''132820''>that</span>
  <span m=''132900''>we</span> <span m=''133030''>covered</span> <span m=''133310''>in</span>
  <span m=''133440''>class.</span> <span m=''134660''>If</span> <span m=''135010''>we</span>
  <span m=''135075''>didn''t</span> <span m=''135140''>cover</span> <span m=''135285''>it</span>
  <span m=''135430''>in</span> <span m=''135510''>class,</span> <span m=''135910''>then</span>
  <span m=''136020''>you''re</span> <span m=''136175''>not</span> <span m=''136330''>responsible</span>
  <span m=''136760''>for</span> <span m=''136917''>it.</span> <span m=''139520''>Other</span>
  <span m=''139730''>questions?</span> <span m=''143140''>Any</span> <span m=''143360''>last</span>
  <span m=''143740''>questions</span> <span m=''144250''>on</span> <span m=''144360''>chapter</span>
  <span m=''144800''>13?</span> <span m=''147020''>This</span> <span m=''147310''>is</span>
  <span m=''147540''>kind</span> <span m=''147790''>of</span> <span m=''147990''>the</span>
  <span m=''148860''>finale</span> <span m=''149560''>for</span> <span m=''152460''>binary</span>
  <span m=''152960''>codes.</span> <span m=''153590''>We</span> <span m=''153770''>found</span>
  <span m=''154150''>that,</span> <span m=''154245''>at</span> <span m=''154340''>least</span>
  <span m=''154680''>on</span> <span m=''154770''>the</span> <span m=''154870''>binary</span>
  <span m=''155250''>erasure</span> <span m=''155630''>channel,</span> <span m=''157600''>we</span>
  <span m=''157740''>had</span> <span m=''157990''>techniques</span> <span m=''158365''>that</span>
  <span m=''158740''>would</span> <span m=''159030''>allow</span> <span m=''159370''>us</span>
  <span m=''159550''>to</span> <span m=''159680''>design</span> <span m=''160610''>LDPC</span>
  <span m=''161220''>codes</span> <span m=''161820''>that</span> <span m=''162460''>would</span>
  <span m=''162730''>get</span> <span m=''162930''>us</span> <span m=''163500''>as</span>
  <span m=''163680''>close</span> <span m=''164010''>to</span> <span m=''164500''>capacity</span>
  <span m=''165250''>as</span> <span m=''165380''>we</span> <span m=''165520''>liked,</span>
  <span m=''165930''>or</span> <span m=''166020''>at</span> <span m=''166060''>least</span>
  <span m=''166340''>I</span> <span m=''166370''>made</span> <span m=''166610''>that</span>
  <span m=''166790''>assertion,</span> <span m=''167850''>directed</span> <span m=''168500''>you</span>
  <span m=''168700''>to</span> <span m=''168800''>where</span> <span m=''168865''>you</span>
  <span m=''168930''>could</span> <span m=''169060''>find</span> <span m=''169320''>that</span>
  <span m=''169580''>done</span> <span m=''169710''>in</span> <span m=''169780''>the</span>
  <span m=''169850''>literature.</span> </p><p><span m=''170600''>And</span> <span
  m=''170980''>I</span> <span m=''171150''>further</span> <span m=''171520''>asserted</span>
  <span m=''171980''>that,</span> <span m=''172430''>at</span> <span m=''172610''>least</span>
  <span m=''172940''>for</span> <span m=''173880''>binary</span> <span m=''174290''>symmetric</span>
  <span m=''174840''>input</span> <span m=''175400''>channels,</span> <span m=''175910''>like</span>
  <span m=''176160''>the</span> <span m=''176250''>binary</span> <span m=''176820''>additive</span>
  <span m=''177250''>white</span> <span m=''177330''>Gaussian</span> <span m=''177820''>noise</span>
  <span m=''178600''>channels,</span> <span m=''180040''>you</span> <span m=''180300''>could</span>
  <span m=''180510''>do</span> <span m=''181220''>much</span> <span m=''181580''>the</span>
  <span m=''181700''>same</span> <span m=''182040''>thing</span> <span m=''182940''>using</span>
  <span m=''183320''>techniques</span> <span m=''183930''>like</span> <span m=''184670''>density</span>
  <span m=''185120''>evolution</span> <span m=''185750''>or</span> <span m=''185960''>EXIT</span>
  <span m=''186390''>charts.</span> <span m=''187350''>Again,</span> <span m=''187740''>the</span>
  <span m=''188000''>issue</span> <span m=''188130''>is</span> <span m=''188260''>to
  design</span> <span m=''188850''>code,</span> <span m=''189250''>such</span> <span
  m=''189580''>as</span> <span m=''189670''>this</span> <span m=''189790''>iterative</span>
  <span m=''190280''>decoding, after</span> <span m=''191690''>many,</span> <span
  m=''191900''>many,</span> <span m=''192120''>many</span> <span m=''192370''>iterations,</span>
  <span m=''193230''>will,</span> <span m=''194280''>with</span> <span m=''194850''>probability</span>
  <span m=''195370''>one,</span> <span m=''195740''>converge</span> <span m=''196520''>to</span>
  <span m=''197110''>the</span> <span m=''197500''>correct</span> <span m=''197790''>solution</span>
  <span m=''198510''>(or</span> <span m=''198950''>with</span> <span m=''199180''>probably</span>
  <span m=''199580''>one</span> <span m=''199760''>minus</span> <span m=''200040''>epsilon).</span>
  </p><p><span m=''202090''>So</span> <span m=''202350''>that''s</span> <span m=''202680''>the</span>
  <span m=''202750''>great</span> <span m=''203090''>conclusion</span> <span m=''203740''>to</span>
  <span m=''203870''>the</span> <span m=''204010''>story</span> <span m=''205660''>for</span>
  <span m=''206700''>binary</span> <span m=''207160''>codes,</span> <span m=''208920''>channels</span>
  <span m=''209370''>in</span> <span m=''209450''>which</span> <span m=''209670''>we</span>
  <span m=''209820''>want</span> <span m=''209990''>to</span> <span m=''210120''>have</span>
  <span m=''210270''>binary</span> <span m=''211140''>inputs.</span> <span m=''211800''>And</span>
  <span m=''213760''>way</span> <span m=''213950''>back</span> <span m=''214300''>in</span>
  <span m=''214360''>the</span> <span m=''214450''>beginning,</span> <span m=''214910''>we</span>
  <span m=''215060''>said</span> <span m=''215360''>that</span> <span m=''215880''>that</span>
  <span m=''216090''>was</span> <span m=''216290''>perfectly</span> <span m=''216690''>sufficient,</span>
  <span m=''217260''>really,</span> <span m=''219250''>for</span> <span m=''219520''>the</span>
  <span m=''219640''>general</span> <span m=''220180''>additive</span> <span m=''220400''>white</span>
  <span m=''220740''>Gaussian</span> <span m=''221240''>channel.</span> <span m=''222630''>When</span>
  <span m=''222890''>we</span> <span m=''223000''>were</span> <span m=''223150''>talking</span>
  <span m=''223650''>about</span> <span m=''225140''>binary</span> <span m=''225550''>code</span>
  <span m=''225830''>rates</span> <span m=''226210''>less</span> <span m=''226470''>than</span>
  <span m=''226560''>1/2,</span> <span m=''227250''>or</span> <span m=''228100''>nominal</span>
  <span m=''228460''>spectral</span> <span m=''228930''>efficiencies</span> <span
  m=''229610''>less</span> <span m=''229870''>than</span> <span m=''230640''>one</span>
  <span m=''230870''>bit</span> <span m=''231250''>per</span> <span m=''231470''>second</span>
  <span m=''231870''>per</span> <span m=''232000''>Hertz,</span> <span m=''233400''>which</span>
  <span m=''233930''>are</span> <span m=''233990''>equivalent</span> <span m=''234410''>statements.</span>
  </p><p><span m=''235690''>So</span> <span m=''235930''>what</span> <span m=''236090''>happens</span>
  <span m=''236480''>if</span> <span m=''236610''>we</span> <span m=''236700''>want</span>
  <span m=''236930''>to</span> <span m=''236970''>go</span> <span m=''237200''>over</span>
  <span m=''238190''>channels</span> <span m=''238680''>where</span> <span m=''238775''>we</span>
  <span m=''238870''>want</span> <span m=''239070''>to</span> <span m=''239120''>send</span>
  <span m=''239340''>at</span> <span m=''239420''>higher</span> <span m=''239800''>spectral</span>
  <span m=''240310''>efficiencies?</span> <span m=''243000''>We</span> <span m=''243140''>want</span>
  <span m=''243310''>to</span> <span m=''243480''>send</span> <span m=''243900''>four</span>
  <span m=''244190''>bits</span> <span m=''244540''>per</span> <span m=''244710''>second</span>
  <span m=''245100''>per</span> <span m=''245270''>Hertz,</span> <span m=''246960''>as</span>
  <span m=''247470''>we</span> <span m=''247630''>certainly</span> <span m=''248030''>do</span>
  <span m=''248340''>over,</span> <span m=''248705''>say,</span> <span m=''249470''>telephone</span>
  <span m=''249950''>line</span> <span m=''250270''>channels,</span> <span m=''250930''>which</span>
  <span m=''251230''>are</span> <span m=''252630''>3,000, or</span> <span m=''253050''>4,000-Hertz</span>
  <span m=''254020''>channels,</span> <span m=''254560''>over</span> <span m=''254710''>which</span>
  <span m=''254930''>we</span> <span m=''255050''>want</span> <span m=''255190''>to</span>
  <span m=''255340''>send</span> <span m=''256079''>tens</span> <span m=''256420''>of</span>
  <span m=''256529''>thousands</span> <span m=''257050''>of</span> <span m=''257130''>bits</span>
  <span m=''257420''>per</span> <span m=''257579''>second.</span> <span m=''258610''>Or</span>
  <span m=''259190''>many</span> <span m=''259470''>radio</span> <span m=''259839''>channels</span>
  <span m=''260339''>will</span> <span m=''260459''>support</span> <span m=''261579''>high</span>
  <span m=''262040''>numbers</span> <span m=''262450''>of</span> <span m=''262540''>bits</span>
  <span m=''262780''>per</span> <span m=''262920''>second</span> <span m=''263280''>per</span>
  <span m=''263410''>Hertz,</span> <span m=''263790''>and</span> <span m=''263890''>so</span>
  <span m=''264090''>forth.</span> <span m=''265560''>Well,</span> <span m=''265640''>obviously,</span>
  <span m=''266460''>you</span> <span m=''266610''>can''t</span> <span m=''266890''>do</span>
  <span m=''267040''>that</span> <span m=''267310''>with</span> <span m=''267910''>binary</span>
  <span m=''268340''>codes.</span> </p><p><span m=''270440''>So,</span> <span m=''272140''>today</span>
  <span m=''272750''>and</span> <span m=''274160''>Wednesday</span> <span m=''275260''>in</span>
  <span m=''275440''>this</span> <span m=''275670''>chapter,</span> <span m=''276780''>we</span>
  <span m=''277550''>very</span> <span m=''277930''>quickly,</span> <span m=''278330''>of</span>
  <span m=''278620''>course,</span> <span m=''278910''>go</span> <span m=''279100''>through</span>
  <span m=''280010''>the</span> <span m=''281100''>series</span> <span m=''281590''>of</span>
  <span m=''281680''>techniques</span> <span m=''281960''>that</span> <span m=''282240''>have</span>
  <span m=''282390''>been</span> <span m=''282540''>developed</span> <span m=''282960''>to</span>
  <span m=''283060''>go</span> <span m=''283230''>over</span> <span m=''283390''>bandwidth-limited</span>
  <span m=''284210''>channels</span> <span m=''284590''>such</span> <span m=''284940''>as</span>
  <span m=''285210''>the</span> <span m=''285520''>bandwidth-limited</span> <span
  m=''285980''>additive</span> <span m=''286460''>white</span> <span m=''286650''>Gaussian</span>
  <span m=''287050''>noise</span> <span m=''287370''>channel.</span> <span m=''288430''>Clearly,</span>
  <span m=''288760''>you''re</span> <span m=''288890''>going</span> <span m=''288990''>to</span>
  <span m=''289100''>need</span> <span m=''289400''>a</span> <span m=''289540''>non-binary</span>
  <span m=''290360''>constellation,</span> <span m=''291032''>and</span> <span m=''291370''>somehow</span>
  <span m=''292310''>code</span> <span m=''292630''>on</span> <span m=''292790''>that</span>
  <span m=''293430''>constellation.</span> </p><p><span m=''297330''>But</span> <span
  m=''297540''>what</span> <span m=''297710''>you''ll</span> <span m=''297840''>see</span>
  <span m=''298320''>is</span> <span m=''298680''>that</span> <span m=''299310''>both</span>
  <span m=''299590''>the</span> <span m=''299700''>techniques</span> <span m=''300500''>and</span>
  <span m=''300870''>much</span> <span m=''301140''>of</span> <span m=''301330''>the</span>
  <span m=''302070''>development</span> <span m=''304790''>are</span> <span m=''305040''>very</span>
  <span m=''305270''>reminiscent</span> <span m=''305880''>of</span> <span m=''305960''>the</span>
  <span m=''306040''>binary</span> <span m=''306460''>case.</span> <span m=''307660''>Historically,</span>
  <span m=''308480''>the</span> <span m=''308570''>binary</span> <span m=''308950''>case</span>
  <span m=''309260''>was</span> <span m=''309440''>always</span> <span m=''309970''>done</span>
  <span m=''310190''>first,</span> <span m=''311080''>and</span> <span m=''311290''>then</span>
  <span m=''311510''>the</span> <span m=''312250''>generalizations</span> <span m=''313050''>to</span>
  <span m=''313190''>non-binary</span> <span m=''314190''>followed.</span> <span m=''315820''>And</span>
  <span m=''316020''>so</span> <span m=''316430''>we''ll</span> <span m=''316800''>see
  --</span> <span m=''317450''>you</span> <span m=''317570''>can</span> <span m=''317700''>start</span>
  <span m=''318020''>off</span> <span m=''318300''>with</span> <span m=''318980''>very</span>
  <span m=''319250''>simple,</span> <span m=''319860''>hand-designed</span> <span
  m=''320630''>constellations,</span> <span m=''321610''>as</span> <span m=''322160''>we</span>
  <span m=''322360''>were</span> <span m=''322490''>doing</span> <span m=''323270''>back</span>
  <span m=''323610''>in</span> <span m=''323730''>the</span> <span m=''323860''>early</span>
  <span m=''324160''>chapters,</span> <span m=''324570''>four</span> <span m=''324980''>and</span>
  <span m=''325300''>five.</span> <span m=''326270''>We</span> <span m=''326410''>played</span>
  <span m=''326720''>around</span> <span m=''327250''>with</span> <span m=''327510''>little</span>
  <span m=''327850''>m</span> <span m=''328130''>equals</span> <span m=''328590''>eight</span>
  <span m=''328860''>constellations</span> <span m=''329780''>and</span> <span m=''329890''>tried</span>
  <span m=''330170''>to</span> <span m=''330270''>optimize</span> <span m=''330960''>them</span>
  <span m=''331590''>from</span> <span m=''331710''>the</span> <span m=''331840''>point</span>
  <span m=''332120''>of</span> <span m=''332200''>view</span> <span m=''332510''>of,</span>
  <span m=''332790''>say,</span> <span m=''333090''>minimizing</span> <span m=''333760''>power</span>
  <span m=''334870''>for</span> <span m=''335210''>a</span> <span m=''335410''>fixed</span>
  <span m=''335930''>minimum</span> <span m=''336250''>distance</span> <span m=''336670''>between</span>
  <span m=''337070''>points</span> <span m=''337590''>in</span> <span m=''337720''>a</span>
  <span m=''337780''>certain</span> <span m=''338080''>number</span> <span m=''338380''>of</span>
  <span m=''338460''>dimensions</span> <span m=''339130''>in</span> <span m=''339240''>Euclidean</span>
  <span m=''339710''>space.</span> </p><p><span m=''341740''>Now,</span> <span m=''341980''>we</span>
  <span m=''342060''>want</span> <span m=''342250''>to</span> <span m=''342290''>go</span>
  <span m=''342430''>up</span> <span m=''342620''>to</span> <span m=''342750''>considerably</span>
  <span m=''343590''>longer</span> <span m=''344000''>constellations.</span> <span
  m=''345310''>So</span> <span m=''345460''>that</span> <span m=''345630''>was</span>
  <span m=''345780''>kind</span> <span m=''346000''>of</span> <span m=''346910''>at</span>
  <span m=''347060''>the</span> <span m=''347160''>level</span> <span m=''347570''>of</span>
  <span m=''348310''>Hamming</span> <span m=''348690''>codes</span> <span m=''349240''>and</span>
  <span m=''350080''>single</span> <span m=''350430''>parity-check</span> <span m=''351000''>codes</span>
  <span m=''351430''>and</span> <span m=''351500''>very</span> <span m=''351770''>elementary</span>
  <span m=''353950''>binary</span> <span m=''354410''>coding</span> <span m=''354760''>techniques</span>
  <span m=''355370''>like</span> <span m=''355600''>that.</span> <span m=''357590''>So</span>
  <span m=''358240''>we</span> <span m=''358390''>want</span> <span m=''358580''>more</span>
  <span m=''358760''>complicated</span> <span m=''359400''>codes,</span> <span m=''359860''>let''s</span>
  <span m=''360100''>say</span> <span m=''360160''>moderate</span> <span m=''360620''>complexity</span>
  <span m=''361260''>codes.</span> <span m=''362200''>We</span> <span m=''362430''>will</span>
  <span m=''362630''>find</span> <span m=''362990''>things</span> <span m=''363420''>that</span>
  <span m=''363550''>are</span> <span m=''363670''>analogous</span> <span m=''364410''>to</span>
  <span m=''366300''>block</span> <span m=''366630''>codes,</span> <span m=''368290''>linear</span>
  <span m=''368670''>block</span> <span m=''368980''>codes,</span> <span m=''369450''>namely</span>
  <span m=''370230''>lattices.</span> <span m=''371650''>These</span> <span m=''371980''>are</span>
  <span m=''372760''>structures</span> <span m=''373440''>in</span> <span m=''373570''>Euclidean</span>
  <span m=''374070''>space</span> <span m=''374530''>that</span> <span m=''374630''>have</span>
  <span m=''374850''>the</span> <span m=''374940''>group</span> <span m=''375230''>property,</span>
  <span m=''375840''>as</span> <span m=''376070''>linear</span> <span m=''376800''>block</span>
  <span m=''377140''>codes</span> <span m=''377540''>do.</span> <span m=''379340''>And</span>
  <span m=''379530''>then</span> <span m=''379660''>we''ll</span> <span m=''379810''>find</span>
  <span m=''381060''>trellis</span> <span m=''381475''>codes,</span> <span m=''381890''>which</span>
  <span m=''382170''>are</span> <span m=''382310''>the</span> <span m=''382570''>Euclidean</span>
  <span m=''382960''>space</span> <span m=''383370''>analog</span> <span m=''383900''>of</span>
  <span m=''384540''>convolutional</span> <span m=''385330''>codes.</span> </p><p><span
  m=''386450''>And</span> <span m=''387170''>basically,</span> <span m=''387820''>our</span>
  <span m=''388030''>goal</span> <span m=''389060''>in</span> <span m=''389170''>the</span>
  <span m=''389260''>next</span> <span m=''389530''>two</span> <span m=''389960''>lectures</span>
  <span m=''390560''>is</span> <span m=''390710''>to</span> <span m=''390820''>get</span>
  <span m=''391040''>to</span> <span m=''391130''>the</span> <span m=''391210''>level</span>
  <span m=''391580''>of</span> <span m=''391700''>a</span> <span m=''392350''>union-bound</span>
  <span m=''393180''>estimate</span> <span m=''393830''>analysis</span> <span m=''394680''>of</span>
  <span m=''394790''>the</span> <span m=''394890''>performance</span> <span m=''395560''>of</span>
  <span m=''395670''>these</span> <span m=''396410''>kinds</span> <span m=''396780''>of</span>
  <span m=''396890''>coding</span> <span m=''397260''>techniques,</span> <span m=''397940''>which,</span>
  <span m=''399230''>like</span> <span m=''399620''>their</span> <span m=''400300''>binary</span>
  <span m=''400700''>analogs,</span> <span m=''401370''>sort</span> <span m=''401620''>of</span>
  <span m=''401680''>sit</span> <span m=''402010''>in</span> <span m=''402150''>a</span>
  <span m=''403260''>moderate</span> <span m=''403680''>complexity,</span> <span m=''404460''>pretty</span>
  <span m=''404760''>good</span> <span m=''404950''>performance,</span> <span m=''405780''>get</span>
  <span m=''405960''>up</span> <span m=''406110''>to</span> <span m=''406240''>6</span>
  <span m=''406720''>dB</span> <span m=''406940''>coding</span> <span m=''407340''>gain,</span>
  <span m=''408010''>can''t</span> <span m=''408300''>get</span> <span m=''408520''>to</span>
  <span m=''408630''>capacity.</span> <span m=''410540''>So</span> <span m=''411520''>that''s</span>
  <span m=''411820''>as</span> <span m=''411950''>far</span> <span m=''412210''>as</span>
  <span m=''412320''>we''ll</span> <span m=''412480''>be</span> <span m=''412680''>able</span>
  <span m=''412840''>to</span> <span m=''412900''>go</span> <span m=''413280''>in</span>
  <span m=''413390''>chapter</span> <span m=''413800''>14.</span> </p><p><span m=''414560''>In</span>
  <span m=''414840''>the</span> <span m=''415070''>last</span> <span m=''415630''>page</span>
  <span m=''415890''>or</span> <span m=''415990''>two</span> <span m=''416210''>of</span>
  <span m=''416430''>chapter</span> <span m=''416820''>14,</span> <span m=''417400''>I</span>
  <span m=''417460''>briefly</span> <span m=''417930''>mention</span> <span m=''419500''>higher</span>
  <span m=''419880''>performance</span> <span m=''420460''>techniques.</span> <span
  m=''421130''>And</span> <span m=''421950''>it''s</span> <span m=''422100''>generally</span>
  <span m=''422420''>accepted</span> <span m=''422960''>that</span> <span m=''423110''>you</span>
  <span m=''423260''>can</span> <span m=''423430''>get</span> <span m=''423630''>as</span>
  <span m=''423770''>close</span> <span m=''424050''>to</span> <span m=''424160''>capacity</span>
  <span m=''424490''>on</span> <span m=''425560''>these</span> <span m=''425740''>bandwidth-limited</span>
  <span m=''426230''>channels,</span> <span m=''426910''>additive</span> <span m=''427320''>white</span>
  <span m=''427370''>Gaussian</span> <span m=''427820''>noise</span> <span m=''428090''>channels</span>
  <span m=''428870''>as</span> <span m=''428980''>you</span> <span m=''429130''>can</span>
  <span m=''429280''>on</span> <span m=''429350''>the</span> <span m=''429430''>binary</span>
  <span m=''429840''>channels,</span> <span m=''430310''>in</span> <span m=''430400''>some</span>
  <span m=''430630''>cases</span> <span m=''431010''>just</span> <span m=''431250''>by</span>
  <span m=''431870''>adapting</span> <span m=''432480''>binary</span> <span m=''433030''>techniques</span>
  <span m=''433680''>in</span> <span m=''433780''>a</span> <span m=''433880''>kind</span>
  <span m=''434150''>of</span> <span m=''434950''>force-fit</span> <span m=''435540''>way,</span>
  <span m=''435950''>and</span> <span m=''436220''>others</span> <span m=''436920''>that</span>
  <span m=''437190''>are</span> <span m=''437640''>somewhat</span> <span m=''437980''>more</span>
  <span m=''438260''>principled,</span> <span m=''438850''>I</span> <span m=''438960''>might</span>
  <span m=''439130''>say.</span> </p><p><span m=''439840''>But</span> <span m=''440390''>in</span>
  <span m=''440500''>any</span> <span m=''440630''>case,</span> <span m=''441130''>by</span>
  <span m=''443140''>adapting</span> <span m=''443840''>the</span> <span m=''443950''>binary</span>
  <span m=''444350''>techniques,</span> <span m=''444960''>you</span> <span m=''445120''>can</span>
  <span m=''445290''>get</span> <span m=''445600''>turbo</span> <span m=''445940''>codes,</span>
  <span m=''446370''>low-density</span> <span m=''447090''>parity-check</span> <span
  m=''447820''>codes,</span> <span m=''448250''>capacity</span> <span m=''449330''>approaching</span>
  <span m=''449920''>codes</span> <span m=''450330''>of</span> <span m=''450440''>various</span>
  <span m=''450900''>types</span> <span m=''452130''>for</span> <span m=''452330''>the</span>
  <span m=''452540''>bandwidth-limited</span> <span m=''453200''>channel.</span> <span
  m=''454670''>But</span> <span m=''455320''>I</span> <span m=''455470''>just</span>
  <span m=''456050''>hint</span> <span m=''456340''>how</span> <span m=''456670''>that</span>
  <span m=''456780''>can</span> <span m=''456890''>be</span> <span m=''457000''>done</span>
  <span m=''457130''>in</span> <span m=''457265''>one</span> <span m=''457400''>page,</span>
  <span m=''457870''>and</span> <span m=''458740''>I</span> <span m=''459090''>can''t</span>
  <span m=''459550''>include</span> <span m=''459940''>it</span> <span m=''459995''>in</span>
  <span m=''460050''>the</span> <span m=''460170''>course.</span> <span m=''462610''>So</span>
  <span m=''462800''>that''s</span> <span m=''463030''>where</span> <span m=''463110''>we''re</span>
  <span m=''463260''>going.</span> </p><p><span m=''465870''>So</span> <span m=''469020''>basically,</span>
  <span m=''469940''>we''re</span> <span m=''470150''>trying</span> <span m=''470610''>to</span>
  <span m=''472520''>design</span> <span m=''473010''>a</span> <span m=''473100''>constellation</span>
  <span m=''475140''>set</span> <span m=''475430''>of</span> <span m=''475510''>signal</span>
  <span m=''475920''>points.</span> <span m=''479940''>Constellation</span> <span
  m=''481230''>c</span> <span m=''481490''>or</span> <span m=''482010''>signal</span>
  <span m=''482420''>set</span> <span m=''482790''>or</span> <span m=''483160''>alphabet,</span>
  <span m=''485000''>script</span> <span m=''485470''>c,</span> <span m=''485740''>if</span>
  <span m=''485880''>you</span> <span m=''486030''>like.</span> <span m=''487950''>And</span>
  <span m=''488290''>we''re</span> <span m=''488430''>doing</span> <span m=''488670''>the</span>
  <span m=''488770''>kind</span> <span m=''489060''>of</span> <span m=''489190''>things</span>
  <span m=''489600''>we</span> <span m=''489665''>were</span> <span m=''489730''>doing</span>
  <span m=''489960''>back</span> <span m=''490230''>in</span> <span m=''490320''>chapter</span>
  <span m=''490770''>four</span> <span m=''491080''>and</span> <span m=''491190''>five.</span>
  <span m=''494600''>What</span> <span m=''494870''>are</span> <span m=''494940''>some</span>
  <span m=''495120''>of</span> <span m=''495170''>the</span> <span m=''495230''>things</span>
  <span m=''495555''>that</span> <span m=''495880''>the</span> <span m=''496560''>parameters</span>
  <span m=''497240''>we</span> <span m=''497510''>have--</span> <span m=''498510''>we''re</span>
  <span m=''498630''>going</span> <span m=''498790''>to</span> <span m=''498830''>do</span>
  <span m=''499070''>this</span> <span m=''499410''>in</span> <span m=''499870''>n-dimensional</span>
  <span m=''500590''>space.</span> <span m=''501990''>We''re</span> <span m=''502280''>going</span>
  <span m=''502390''>to</span> <span m=''504340''>be</span> <span m=''504560''>concerned</span>
  <span m=''505000''>with</span> <span m=''505130''>the</span> <span m=''505220''>size</span>
  <span m=''505830''>of</span> <span m=''505920''>the</span> <span m=''506020''>constellation,</span>
  <span m=''507160''>the</span> <span m=''507300''>log</span> <span m=''507650''>of</span>
  <span m=''507730''>the</span> <span m=''507820''>size,</span> <span m=''508450''>the</span>
  <span m=''508550''>number</span> <span m=''508900''>of</span> <span m=''509330''>log</span>
  <span m=''509630''>2</span> <span m=''509870''>of</span> <span m=''509920''>the</span>
  <span m=''509970''>size,</span> <span m=''510460''>the</span> <span m=''510510''>number</span>
  <span m=''510760''>of</span> <span m=''510820''>bits</span> <span m=''511170''>we</span>
  <span m=''511320''>can</span> <span m=''511670''>send.</span> </p><p><span m=''514169''>We</span>
  <span m=''514390''>call</span> <span m=''514650''>this</span> <span m=''514929''>m</span>
  <span m=''515350''>at</span> <span m=''515429''>one</span> <span m=''515679''>point.</span>
  <span m=''518010''>That</span> <span m=''518220''>will</span> <span m=''518530''>determine</span>
  <span m=''519000''>the</span> <span m=''519090''>number</span> <span m=''519460''>of</span>
  <span m=''519549''>bits</span> <span m=''519980''>we</span> <span m=''520134''>can</span>
  <span m=''520289''>send</span> <span m=''520720''>per</span> <span m=''521789''>n</span>
  <span m=''522010''>dimensions,</span> <span m=''522860''>or</span> <span m=''523070''>we</span>
  <span m=''523190''>can</span> <span m=''523330''>normalize</span> <span m=''523880''>it</span>
  <span m=''524049''>per</span> <span m=''524270''>two</span> <span m=''524510''>dimensions.</span>
  <span m=''525210''>Typically,</span> <span m=''525740''>I</span> <span m=''525810''>said,</span>
  <span m=''525990''>in</span> <span m=''526180''>bandwidth-limited</span> <span m=''526830''>regime,</span>
  <span m=''527260''>we''ll</span> <span m=''527380''>normalize</span> <span m=''527890''>everything</span>
  <span m=''528270''>per</span> <span m=''528450''>two</span> <span m=''528630''>dimensions.</span>
  <span m=''530500''>We''re</span> <span m=''530760''>going</span> <span m=''530890''>to</span>
  <span m=''531090''>have</span> <span m=''531300''>an</span> <span m=''531440''>average</span>
  <span m=''532820''>power</span> <span m=''533290''>of</span> <span m=''533380''>the</span>
  <span m=''533480''>constellation,</span> <span m=''534370''>which</span> <span m=''534650''>I''m</span>
  <span m=''534780''>just</span> <span m=''534970''>going</span> <span m=''535060''>to</span>
  <span m=''535150''>write</span> <span m=''535430''>like</span> <span m=''535710''>that.</span>
  <span m=''536840''>We''re</span> <span m=''537130''>going</span> <span m=''537270''>to</span>
  <span m=''537340''>have</span> <span m=''537740''>a</span> <span m=''538230''>minimum</span>
  <span m=''538680''>squared</span> <span m=''539200''>distance</span> <span m=''539780''>between</span>
  <span m=''541040''>points</span> <span m=''541520''>in</span> <span m=''541610''>the</span>
  <span m=''541710''>constellation,</span> <span m=''544190''>which</span> <span m=''544490''>I''m</span>
  <span m=''544590''>going</span> <span m=''544690''>to</span> <span m=''544790''>write</span>
  <span m=''545010''>like</span> <span m=''545330''>that.</span> </p><p><span m=''546580''>And</span>
  <span m=''547460''>the</span> <span m=''547630''>idea</span> <span m=''548200''>is</span>
  <span m=''548540''>to</span> <span m=''549020''>optimize</span> <span m=''549630''>the</span>
  <span m=''549720''>trade-off</span> <span m=''550190''>between</span> <span m=''550540''>this</span>
  <span m=''550760''>and</span> <span m=''550860''>this.</span> <span m=''552210''>Clearly,</span>
  <span m=''552430''>if</span> <span m=''552620''>I</span> <span m=''552740''>take</span>
  <span m=''553080''>a</span> <span m=''553190''>given</span> <span m=''553530''>constellation</span>
  <span m=''554450''>and</span> <span m=''554620''>I</span> <span m=''555450''>scale</span>
  <span m=''555890''>it</span> <span m=''555970''>up,</span> <span m=''556500''>I''m</span>
  <span m=''556670''>going</span> <span m=''556790''>to</span> <span m=''556840''>get</span>
  <span m=''557030''>better</span> <span m=''557650''>minimum</span> <span m=''558080''>squared</span>
  <span m=''558420''>distance</span> <span m=''558960''>without</span> <span m=''559070''>the</span>
  <span m=''559360''>cost</span> <span m=''559710''>of</span> <span m=''559840''>increasing</span>
  <span m=''561010''>power.</span> <span m=''561480''>So</span> <span m=''562950''>I</span>
  <span m=''563080''>either</span> <span m=''563310''>fix</span> <span m=''563650''>the</span>
  <span m=''563850''>minimum</span> <span m=''564040''>squared</span> <span m=''564440''>distance</span>
  <span m=''564990''>between</span> <span m=''565380''>points</span> <span m=''565910''>and</span>
  <span m=''566030''>try</span> <span m=''566330''>to</span> <span m=''566680''>minimize</span>
  <span m=''567260''>the</span> <span m=''567360''>power,</span> <span m=''569210''>the</span>
  <span m=''570160''>average</span> <span m=''570600''>energy</span> <span m=''571210''>over</span>
  <span m=''571380''>the</span> <span m=''572120''>centroids</span> <span m=''572860''>of</span>
  <span m=''574060''>a</span> <span m=''574160''>bunch</span> <span m=''574400''>of</span>
  <span m=''574470''>spheres,</span> <span m=''575880''>or</span> <span m=''576760''>vice</span>
  <span m=''577080''>versa.</span> </p><p><span m=''579470''>So</span> <span m=''580170''>when</span>
  <span m=''580370''>we</span> <span m=''580500''>do</span> <span m=''580690''>this,</span>
  <span m=''581860''>this</span> <span m=''582080''>is</span> <span m=''582250''>kind</span>
  <span m=''582370''>of</span> <span m=''582500''>the</span> <span m=''582590''>game,</span>
  <span m=''583010''>we</span> <span m=''583160''>get</span> <span m=''583380''>into</span>
  <span m=''584370''>a</span> <span m=''584470''>classical</span> <span m=''585070''>problem</span>
  <span m=''585550''>called</span> <span m=''586640''>sphere-packing.</span> <span
  m=''592230''>If</span> <span m=''592430''>we</span> <span m=''592640''>say,</span>
  <span m=''592980''>hold</span> <span m=''593350''>the</span> <span m=''593400''>minimum</span>
  <span m=''593730''>squared</span> <span m=''594170''>distance</span> <span m=''594670''>constant,</span>
  <span m=''597250''>that</span> <span m=''597500''>means</span> <span m=''598580''>we</span>
  <span m=''598780''>want</span> <span m=''599120''>to</span> <span m=''600990''>have</span>
  <span m=''601150''>a</span> <span m=''601200''>certain</span> <span m=''601660''>minimum</span>
  <span m=''602000''>distance.</span> <span m=''602660''>Here</span> <span m=''602890''>I''ll</span>
  <span m=''603000''>make</span> <span m=''603250''>it</span> <span m=''603410''>d_min
  over 2.</span> <span m=''606180''>That</span> <span m=''606290''>means</span> <span
  m=''606620''>that</span> <span m=''606820''>there''s</span> <span m=''607080''>going</span>
  <span m=''607200''>to</span> <span m=''607320''>be</span> <span m=''607450''>a</span>
  <span m=''607510''>sphere</span> <span m=''608140''>of</span> <span m=''608460''>radius</span>
  <span m=''608920''>d_min over 2</span> <span m=''610810''>around</span> <span m=''611700''>each</span>
  <span m=''612030''>point</span> <span m=''612490''>in</span> <span m=''612640''>this</span>
  <span m=''612800''>space,</span> <span m=''613260''>which</span> <span m=''613480''>must</span>
  <span m=''613810''>not</span> <span m=''614030''>be</span> <span m=''614170''>violated</span>
  <span m=''615300''>by</span> <span m=''615480''>the</span> <span m=''615600''>sphere</span>
  <span m=''616080''>of</span> <span m=''616180''>any</span> <span m=''616420''>other</span>
  <span m=''616680''>point.</span> <span m=''617580''>So</span> <span m=''617720''>basically,</span>
  <span m=''618230''>we''re</span> <span m=''618350''>trying</span> <span m=''618670''>to</span>
  <span m=''619520''>pack</span> <span m=''619863''>spheres</span> <span m=''620550''>as</span>
  <span m=''620680''>closely</span> <span m=''621190''>together</span> <span m=''621710''>as</span>
  <span m=''621870''>we</span> <span m=''622010''>can.</span> <span m=''623200''>And</span>
  <span m=''623465''>we''re</span> <span m=''623730''>maybe</span> <span m=''623980''>given</span>
  <span m=''624280''>the</span> <span m=''624440''>dimension.</span> <span m=''625070''>Here</span>
  <span m=''625320''>I</span> <span m=''625390''>have</span> <span m=''625570''>two</span>
  <span m=''625750''>dimensions</span> <span m=''626280''>to</span> <span m=''626400''>play</span>
  <span m=''626630''>with.</span> <span m=''627400''>We</span> <span m=''627470''>may</span>
  <span m=''627630''>be</span> <span m=''627750''>given</span> <span m=''628190''>the</span>
  <span m=''628360''>number,</span> <span m=''628670''>m.</span> </p><p><span m=''630520''>In</span>
  <span m=''630740''>general</span> <span m=''631130''>now,</span> <span m=''632080''>we''re</span>
  <span m=''632160''>going</span> <span m=''632240''>to</span> <span m=''632320''>be</span>
  <span m=''632400''>thinking</span> <span m=''632830''>of</span> <span m=''633520''>m</span>
  <span m=''633760''>becoming</span> <span m=''634190''>very</span> <span m=''634420''>large.</span>
  <span m=''635090''>We</span> <span m=''635250''>want</span> <span m=''635430''>to</span>
  <span m=''635480''>go</span> <span m=''635620''>to</span> <span m=''635750''>arbitrarily</span>
  <span m=''636430''>large</span> <span m=''636850''>number</span> <span m=''637170''>of</span>
  <span m=''637300''>bits</span> <span m=''637620''>per</span> <span m=''638290''>second</span>
  <span m=''638710''>per</span> <span m=''638890''>Hertz.</span> <span m=''639890''>So</span>
  <span m=''640270''>think</span> <span m=''640560''>of</span> <span m=''640690''>schemes</span>
  <span m=''641300''>that</span> <span m=''641380''>will</span> <span m=''641590''>continue</span>
  <span m=''642010''>to</span> <span m=''642100''>work</span> <span m=''642490''>as</span>
  <span m=''642650''>we</span> <span m=''642830''>add</span> <span m=''643080''>more</span>
  <span m=''643360''>and</span> <span m=''643430''>more</span> <span m=''644830''>points.</span>
  <span m=''646390''>And</span> <span m=''646770''>if</span> <span m=''646940''>I</span>
  <span m=''647030''>do</span> <span m=''647240''>that</span> <span m=''647580''>in</span>
  <span m=''649450''>two</span> <span m=''649620''>dimensions,</span> <span m=''650620''>we</span>
  <span m=''650880''>get</span> <span m=''651670''>penny-packing.</span> <span m=''652750''>Take</span>
  <span m=''653200''>a</span> <span m=''653270''>bunch</span> <span m=''653600''>of</span>
  <span m=''653670''>seven</span> <span m=''654000''>pennies</span> <span m=''654430''>out</span>
  <span m=''654570''>of</span> <span m=''654670''>your</span> <span m=''654810''>pocket,</span>
  <span m=''655780''>and</span> <span m=''656060''>try</span> <span m=''656240''>to</span>
  <span m=''656340''>squeeze</span> <span m=''656790''>them</span> <span m=''656930''>together</span>
  <span m=''657450''>as</span> <span m=''657600''>tightly</span> <span m=''658010''>as</span>
  <span m=''658090''>you</span> <span m=''658230''>can.</span> <span m=''658565''>That''s</span>
  <span m=''658900''>effectively</span> <span m=''659280''>what</span> <span m=''659410''>we''re</span>
  <span m=''659580''>trying</span> <span m=''659870''>to</span> <span m=''659930''>do.</span>
  <span m=''661110''>They</span> <span m=''661390''>maintain</span> <span m=''661970''>their</span>
  <span m=''662360''>fixed</span> <span m=''662700''>radius,</span> <span m=''664470''>and</span>
  <span m=''664760''>you</span> <span m=''664950''>get</span> <span m=''665310''>something</span>
  <span m=''665800''>that</span> <span m=''666120''>quickly</span> <span m=''666490''>starts</span>
  <span m=''666840''>to</span> <span m=''666940''>look</span> <span m=''667140''>like</span>
  <span m=''667620''>what</span> <span m=''667810''>this</span> <span m=''668040''>is</span>
  <span m=''668170''>called,</span> <span m=''668880''>a</span> <span m=''668930''>hexagonal</span>
  <span m=''669630''>sphere-packing,</span> <span m=''670980''>because</span> <span
  m=''671680''>the</span> <span m=''671790''>centers</span> <span m=''673130''>line</span>
  <span m=''673460''>up</span> <span m=''673680''>on</span> <span m=''673910''>a</span>
  <span m=''674170''>hexagonal</span> <span m=''674920''>grid.</span> </p><p><span
  m=''678870''>And</span> <span m=''679160''>in</span> <span m=''679290''>fact,</span>
  <span m=''680370''>I</span> <span m=''680460''>forget</span> <span m=''680990''>exactly</span>
  <span m=''681410''>what</span> <span m=''681570''>we</span> <span m=''681680''>did.</span>
  <span m=''681910''>We</span> <span m=''682020''>did</span> <span m=''682760''>some</span>
  <span m=''683050''>of</span> <span m=''683130''>these</span> <span m=''683730''>back</span>
  <span m=''684080''>in</span> <span m=''684340''>the</span> <span m=''691710''>early</span>
  <span m=''692080''>chapters.</span> <span m=''693110''>And</span> <span m=''694810''>let</span>
  <span m=''694920''>me</span> <span m=''695050''>draw</span> <span m=''695630''>a</span>
  <span m=''695840''>16-point</span> <span m=''696750''>constellation,</span> <span
  m=''697550''>which</span> <span m=''697800''>I</span> <span m=''697860''>remember</span>
  <span m=''698160''>we</span> <span m=''698290''>did</span> <span m=''698550''>draw.</span>
  <span m=''701440''>Here''s</span> <span m=''701710''>a</span> <span m=''701770''>constellation</span>
  <span m=''702650''>consisting</span> <span m=''703240''>of</span> <span m=''703330''>16</span>
  <span m=''703960''>pennies.</span> <span m=''706470''>And</span> <span m=''706820''>subject</span>
  <span m=''707070''>to</span> <span m=''707220''>my</span> <span m=''707350''>drawing</span>
  <span m=''707790''>ability,</span> <span m=''708290''>it''s</span> <span m=''708510''>packed</span>
  <span m=''708950''>as</span> <span m=''709100''>closely</span> <span m=''709580''>as</span>
  <span m=''709730''>possible</span> <span m=''710900''>for</span> <span m=''711580''>a</span>
  <span m=''711630''>fixed</span> <span m=''712770''>minimum</span> <span m=''713180''>distance</span>
  <span m=''713760''>between</span> <span m=''714120''>the</span> <span m=''714200''>points.</span>
  </p><p><span m=''715510''>And</span> <span m=''716970''>as</span> <span m=''717140''>far</span>
  <span m=''717320''>as</span> <span m=''717500''>anyone</span> <span m=''717810''>knows,</span>
  <span m=''718900''>this</span> <span m=''720040''>constellation,</span> <span m=''720950''>consisting</span>
  <span m=''721470''>a</span> <span m=''721540''>set</span> <span m=''721780''>of</span>
  <span m=''721870''>points</span> <span m=''722240''>on</span> <span m=''722350''>a</span>
  <span m=''722380''>hexagonal</span> <span m=''722980''>grid,</span> <span m=''723640''>is</span>
  <span m=''723840''>the</span> <span m=''725720''>most</span> <span m=''726030''>dense</span>
  <span m=''726350''>packing</span> <span m=''726890''>of</span> <span m=''727070''>16</span>
  <span m=''727970''>points</span> <span m=''728470''>in</span> <span m=''728630''>two</span>
  <span m=''728800''>dimensions,</span> <span m=''729860''>as</span> <span m=''730090''>measured</span>
  <span m=''730520''>by</span> <span m=''730740''>the</span> <span m=''730930''>average</span>
  <span m=''731270''>power</span> <span m=''731600''>of</span> <span m=''731680''>the</span>
  <span m=''731760''>centers.</span> <span m=''733860''>And</span> <span m=''734200''>it''s</span>
  <span m=''734470''>not</span> <span m=''734620''>very</span> <span m=''734800''>symmetrical,</span>
  <span m=''736240''>but</span> <span m=''736500''>you</span> <span m=''736630''>can</span>
  <span m=''736740''>see</span> <span m=''736910''>it''s</span> <span m=''737120''>based</span>
  <span m=''737530''>on</span> <span m=''737800''>a</span> <span m=''737890''>symmetrical</span>
  <span m=''740220''>packing.</span> <span m=''741380''>This</span> <span m=''741890''>hexagonal,</span>
  <span m=''743140''>this</span> <span m=''743320''>is</span> <span m=''743460''>basically</span>
  <span m=''745270''>a</span> <span m=''745380''>subset</span> <span m=''745900''>of</span>
  <span m=''745960''>16</span> <span m=''746540''>points</span> <span m=''747040''>from</span>
  <span m=''748290''>the</span> <span m=''748490''>hexagonal</span> <span m=''749150''>lattice.</span>
  <span m=''750690''>If</span> <span m=''750870''>we</span> <span m=''751170''>extend</span>
  <span m=''752310''>these</span> <span m=''752530''>points</span> <span m=''752970''>in</span>
  <span m=''753070''>all</span> <span m=''753260''>directions--</span> <span m=''754210''>again,</span>
  <span m=''754265''>I</span> <span m=''754320''>haven''t</span> <span m=''754580''>done</span>
  <span m=''754740''>it</span> <span m=''754860''>very</span> <span m=''755110''>well--</span>
  <span m=''756020''>but</span> <span m=''757180''>the</span> <span m=''757440''>hexagonal</span>
  <span m=''758110''>lattice</span> <span m=''759670''>is</span> <span m=''759880''>simply</span>
  <span m=''761870''>the</span> <span m=''762040''>underlying</span> <span m=''762660''>lattice</span>
  <span m=''763160''>here.</span> </p><p><span m=''763440''>Let</span> <span m=''763720''>me</span>
  <span m=''763945''>just</span> <span m=''764170''>draw</span> <span m=''764470''>a</span>
  <span m=''765350''>set</span> <span m=''765640''>of</span> <span m=''765770''>points</span>
  <span m=''768684''>that</span> <span m=''769170''>look</span> <span m=''769480''>like</span>
  <span m=''769860''>this.</span> <span m=''773786''>I''m</span> <span m=''773937''>going</span>
  <span m=''774088''>to</span> <span m=''774240''>fail</span> <span m=''774610''>again.</span>
  <span m=''778660''>Sorry,</span> <span m=''778810''>I''m</span> <span m=''779150''>better</span>
  <span m=''779310''>at</span> <span m=''779470''>rock''n''roll</span> <span m=''779860''>than</span>
  <span m=''780250''>I</span> <span m=''780325''>am</span> <span m=''780400''>at</span>
  <span m=''780560''>classical</span> <span m=''781080''>music.</span> <span m=''783470''>Anyway,</span>
  <span m=''784520''>this</span> <span m=''784760''>is</span> <span m=''784910''>the</span>
  <span m=''785020''>lattice,</span> <span m=''786160''>and</span> <span m=''786850''>it''s</span>
  <span m=''787020''>called</span> <span m=''787310''>hexagonal</span> <span m=''787970''>because,</span>
  <span m=''788350''>if</span> <span m=''788500''>we</span> <span m=''788630''>draw</span>
  <span m=''788980''>the</span> <span m=''789660''>decision</span> <span m=''790140''>regions</span>
  <span m=''790690''>for</span> <span m=''790820''>this</span> <span m=''790960''>lattice,</span>
  <span m=''791610''>if</span> <span m=''791680''>we</span> <span m=''791790''>consider</span>
  <span m=''792250''>this</span> <span m=''794390''>as</span> <span m=''794700''>a</span>
  <span m=''794750''>set</span> <span m=''795130''>of</span> <span m=''796100''>points</span>
  <span m=''796460''>in</span> <span m=''796530''>a</span> <span m=''796610''>constellation</span>
  <span m=''797440''>and</span> <span m=''797570''>draw</span> <span m=''797860''>the</span>
  <span m=''797960''>decision</span> <span m=''798430''>regions,</span> <span m=''799630''>it</span>
  <span m=''799810''>looks</span> <span m=''800150''>like</span> <span m=''801470''>that,</span>
  <span m=''801730''>this</span> <span m=''801990''>little</span> <span m=''802370''>hexagon,</span>
  <span m=''806660''>defined</span> <span m=''807180''>by</span> <span m=''807430''>the</span>
  <span m=''807570''>six</span> <span m=''808080''>nearest</span> <span m=''808460''>neighbors.</span>
  <span m=''808940''>They</span> <span m=''809080''>define</span> <span m=''809580''>six</span>
  <span m=''810780''>sides</span> <span m=''811230''>of</span> <span m=''811340''>a</span>
  <span m=''811390''>hexagon.</span> </p><p><span m=''812630''>And</span> <span m=''812870''>so</span>
  <span m=''815010''>each</span> <span m=''815780''>lattice</span> <span m=''816220''>point</span>
  <span m=''816550''>has</span> <span m=''816760''>a</span> <span m=''816820''>little</span>
  <span m=''817060''>region</span> <span m=''817480''>of</span> <span m=''817550''>space</span>
  <span m=''818040''>that</span> <span m=''818120''>belongs</span> <span m=''818610''>to</span>
  <span m=''818760''>it,</span> <span m=''819020''>you</span> <span m=''819160''>can</span>
  <span m=''819300''>think</span> <span m=''819560''>of</span> <span m=''819740''>as
  its</span> <span m=''819960''>decision</span> <span m=''820450''>region.</span>
  <span m=''824330''>Now,</span> <span m=''824450''>what</span> <span m=''825040''>makes</span>
  <span m=''825300''>this</span> <span m=''825540''>a</span> <span m=''825610''>lattice?</span>
  <span m=''827940''>What''s</span> <span m=''828130''>the</span> <span m=''828320''>definition</span>
  <span m=''828890''>of</span> <span m=''828960''>a</span> <span m=''829030''>lattice?</span>
  <span m=''832200''>We''ll</span> <span m=''832260''>say</span> <span m=''832320''>an</span>
  <span m=''832445''>n-dimensional</span> <span m=''833110''>lattice.</span> <span
  m=''837010''>Very</span> <span m=''837280''>simple</span> <span m=''837690''>and</span>
  <span m=''837780''>elegant</span> <span m=''838300''>definition</span> <span m=''839810''>for</span>
  <span m=''839895''>a</span> <span m=''839980''>lattice.</span> <span m=''840520''>It''s</span>
  <span m=''840780''>a</span> <span m=''841470''>discrete</span> <span m=''843200''>subset.</span>
  <span m=''843700''>That</span> <span m=''843960''>means</span> <span m=''844310''>a</span>
  <span m=''844410''>set</span> <span m=''844850''>of</span> <span m=''845680''>discrete</span>
  <span m=''845880''>points</span> <span m=''848960''>of</span> <span m=''849800''>Rn,</span>
  <span m=''850540''>sitting</span> <span m=''850920''>in</span> <span m=''851570''>Euclidean</span>
  <span m=''852130''>n-space,</span> <span m=''854890''>that</span> <span m=''855090''>has</span>
  <span m=''855290''>the</span> <span m=''855370''>group</span> <span m=''855620''>property.</span>
  <span m=''869130''>And</span> <span m=''869680''>you</span> <span m=''869890''>now</span>
  <span m=''870170''>all</span> <span m=''870540''>remember</span> <span m=''870960''>what</span>
  <span m=''871065''>that</span> <span m=''871170''>means.</span> <span m=''871850''>It</span>
  <span m=''872300''>means</span> <span m=''875790''>the</span> <span m=''875980''>group</span>
  <span m=''876250''>property,</span> <span m=''876810''>under</span> <span m=''877190''>ordinary</span>
  <span m=''878590''>addition</span> <span m=''879000''>of</span> <span m=''879110''>vectors</span>
  <span m=''879420''>in</span> <span m=''880850''>Euclidean</span> <span m=''881390''>n-space,</span>
  <span m=''884870''>addition</span> <span m=''885230''>or</span> <span m=''885330''>subtraction,</span>
  <span m=''885960''>of</span> <span m=''886070''>course.</span> </p><p><span m=''888670''>What</span>
  <span m=''888820''>are</span> <span m=''888880''>some</span> <span m=''888966''>of</span>
  <span m=''889053''>the</span> <span m=''889140''>implications</span> <span m=''889485''>of</span>
  <span m=''889830''>having</span> <span m=''889955''>a</span> <span m=''890080''>group</span>
  <span m=''890380''>property?</span> <span m=''891060''>That</span> <span m=''891190''>means</span>
  <span m=''891500''>that</span> <span m=''891590''>the</span> <span m=''892650''>sum</span>
  <span m=''892960''>of</span> <span m=''893090''>any</span> <span m=''893310''>two</span>
  <span m=''893490''>vectors</span> <span m=''894050''>is</span> <span m=''894210''>another</span>
  <span m=''894490''>vector</span> <span m=''894880''>in</span> <span m=''894950''>the</span>
  <span m=''895040''>lattice.</span> <span m=''897470''>Does</span> <span m=''897800''>the</span>
  <span m=''898140''>lattice</span> <span m=''898580''>have</span> <span m=''898780''>to</span>
  <span m=''898920''>include</span> <span m=''899350''>the</span> <span m=''899470''>0,</span>
  <span m=''899950''>the</span> <span m=''900100''>origin</span> <span m=''900580''>point?</span>
  <span m=''906670''>Anybody?</span> <span m=''907980''>Oh,</span> <span m=''908360''>good.</span>
  <span m=''908530''>I''m</span> <span m=''908640''>going</span> <span m=''908750''>to</span>
  <span m=''908860''>ask</span> <span m=''909350''>this</span> <span m=''909400''>on</span>
  <span m=''909450''>the</span> <span m=''909550''>final.</span> <span m=''914980''>Come</span>
  <span m=''915125''>on.</span> <span m=''915270''>Does</span> <span m=''915480''>it</span>
  <span m=''915595''>or</span> <span m=''915710''>doesn''t</span> <span m=''916050''>it?</span>
  </p><p><span m=''916260''>AUDIENCE: It does.</span> </p><p><span m=''917800''>PROFESSOR:
  It</span> <span m=''917970''>does.</span> <span m=''918840''>Why?</span> </p><p><span
  m=''919580''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''925900''>PROFESSOR:
  OK,</span> <span m=''926260''>that''s</span> <span m=''927010''>one</span> <span
  m=''927320''>good</span> <span m=''927520''>answer.</span> <span m=''929050''>It</span>
  <span m=''929180''>has</span> <span m=''929400''>to</span> <span m=''929440''>be</span>
  <span m=''929570''>closed</span> <span m=''930090''>under</span> <span m=''930310''>addition</span>
  <span m=''930630''>and</span> <span m=''930760''>subtraction.</span> <span m=''932050''>Subtraction</span>
  <span m=''932380''>of</span> <span m=''932545''>the</span> <span m=''932710''>point</span>
  <span m=''933030''>from</span> <span m=''933220''>itself</span> <span m=''933670''>is</span>
  <span m=''933830''>going</span> <span m=''933950''>to</span> <span m=''933990''>give</span>
  <span m=''934200''>you</span> <span m=''934310''>0.</span> <span m=''935766''>A</span>
  <span m=''936200''>more</span> <span m=''936600''>mathematically</span> <span m=''937280''>trained</span>
  <span m=''937630''>person</span> <span m=''938070''>would</span> <span m=''938290''>probably,</span>
  <span m=''938570''>say,</span> <span m=''938770''>well,</span> <span m=''938920''>it</span>
  <span m=''939070''>obviously</span> <span m=''939460''>has</span> <span m=''939710''>to</span>
  <span m=''939810''>have</span> <span m=''939910''>an</span> <span m=''940000''>identity.</span>
  <span m=''941560''>Every</span> <span m=''941780''>group</span> <span m=''942090''>has</span>
  <span m=''942215''>an</span> <span m=''942340''>identity</span> <span m=''942840''>element.</span>
  <span m=''945890''>And</span> <span m=''946140''>that</span> <span m=''946370''>means,</span>
  <span m=''947050''>if</span> <span m=''947330''>lambda</span> <span m=''947870''>is</span>
  <span m=''948110''>in</span> <span m=''948200''>the</span> <span m=''948300''>lattice,</span>
  <span m=''948790''>does</span> <span m=''948940''>minus</span> <span m=''949330''>lambda</span>
  <span m=''949710''>have</span> <span m=''949900''>to</span> <span m=''950010''>be</span>
  <span m=''950120''>in</span> <span m=''950240''>the</span> <span m=''950320''>lattice?</span>
  <span m=''952200''>Yeah,</span> <span m=''952780''>every</span> <span m=''953155''>element</span>
  <span m=''953530''>has</span> <span m=''953600''>to</span> <span m=''953950''>have</span>
  <span m=''954100''>an</span> <span m=''954190''>additive</span> <span m=''954520''>inverse,</span>
  <span m=''955580''>and</span> <span m=''955760''>so</span> <span m=''955960''>forth.</span>
  </p><p><span m=''958850''>Well,</span> <span m=''959420''>so</span> <span m=''962500''>if</span>
  <span m=''962720''>I</span> <span m=''962830''>have</span> <span m=''962970''>a</span>
  <span m=''963110''>lattice</span> <span m=''963920''>like</span> <span m=''964300''>this,</span>
  <span m=''965650''>that</span> <span m=''965780''>means</span> <span m=''966030''>that</span>
  <span m=''966220''>one</span> <span m=''966480''>of</span> <span m=''966520''>these</span>
  <span m=''966760''>points</span> <span m=''967100''>has</span> <span m=''967300''>to</span>
  <span m=''967380''>be</span> <span m=''967620''>the</span> <span m=''967850''>origin,</span>
  <span m=''969320''>say</span> <span m=''969590''>this</span> <span m=''969860''>one.</span>
  <span m=''975740''>Now,</span> <span m=''975980''>of</span> <span m=''976150''>course,</span>
  <span m=''976320''>you</span> <span m=''976450''>can</span> <span m=''976590''>have</span>
  <span m=''976780''>a</span> <span m=''976840''>translate</span> <span m=''977155''>of</span>
  <span m=''977470''>a</span> <span m=''977580''>lattice,</span> <span m=''978080''>and</span>
  <span m=''978210''>geometrically</span> <span m=''979050''>it</span> <span m=''979160''>has</span>
  <span m=''979430''>all</span> <span m=''979610''>the</span> <span m=''979670''>same</span>
  <span m=''979920''>properties</span> <span m=''980295''>as</span> <span m=''980482''>the</span>
  <span m=''980670''>lattice</span> <span m=''981060''>itself,</span> <span m=''981540''>at</span>
  <span m=''981780''>any</span> <span m=''982350''>fixed</span> <span m=''982890''>t</span>
  <span m=''983350''>to</span> <span m=''983670''>all</span> <span m=''983990''>the</span>
  <span m=''984330''>lattice</span> <span m=''984670''>points.</span> <span m=''985180''>In</span>
  <span m=''985490''>other</span> <span m=''985685''>words,</span> <span m=''985880''>make</span>
  <span m=''986110''>the</span> <span m=''986300''>origin</span> <span m=''986590''>somewhere</span>
  <span m=''986990''>else.</span> <span m=''987730''>But</span> <span m=''987950''>that''s</span>
  <span m=''988250''>not</span> <span m=''988640''>itself</span> <span m=''989060''>a</span>
  <span m=''989130''>group.</span> <span m=''989520''>That''s</span> <span m=''989750''>the</span>
  <span m=''989840''>co-set</span> <span m=''990290''>of</span> <span m=''990400''>a</span>
  <span m=''990460''>group.</span> <span m=''990800''>It</span> <span m=''990960''>would</span>
  <span m=''991180''>translate</span> <span m=''991760''>as</span> <span m=''991850''>a</span>
  <span m=''991950''>co-set</span> <span m=''992410''>operation.</span> </p><p><span
  m=''993680''>So</span> <span m=''994920''>lambda</span> <span m=''995760''>must</span>
  <span m=''996090''>be</span> <span m=''996550''>a</span> <span m=''996690''>group,</span>
  <span m=''999390''>and</span> <span m=''999960''>lambda</span> <span m=''1000690''>plus</span>
  <span m=''1001120''>t,</span> <span m=''1001510''>any</span> <span m=''1001805''>lambda</span>
  <span m=''1002100''>translate</span> <span m=''1003330''>is</span> <span m=''1004110''>a</span>
  <span m=''1004415''>co-set</span> <span m=''1006250''>of</span> <span m=''1007120''>lambda.</span>
  <span m=''1009320''>So</span> <span m=''1009520''>most</span> <span m=''1009790''>of</span>
  <span m=''1009830''>the</span> <span m=''1009890''>things</span> <span m=''1010170''>you</span>
  <span m=''1010300''>say</span> <span m=''1010510''>about</span> <span m=''1010710''>lambda</span>
  <span m=''1011040''>are</span> <span m=''1011220''>also</span> <span m=''1011480''>true</span>
  <span m=''1011740''>for</span> <span m=''1011880''>lambda</span> <span m=''1012220''>plus</span>
  <span m=''1012590''>t,</span> <span m=''1013420''>but</span> <span m=''1013710''>in</span>
  <span m=''1013770''>order</span> <span m=''1013990''>to</span> <span m=''1014090''>fix</span>
  <span m=''1014450''>a</span> <span m=''1014500''>group,</span> <span m=''1014870''>we</span>
  <span m=''1014970''>need</span> <span m=''1015180''>the</span> <span m=''1015330''>origin</span>
  <span m=''1015660''>to</span> <span m=''1015770''>be</span> <span m=''1015880''>part</span>
  <span m=''1015990''>of</span> <span m=''1016155''>the</span> <span m=''1016320''>points
  set.</span> <span m=''1018400''>OK,</span> <span m=''1018880''>if</span> <span m=''1019000''>it''s</span>
  <span m=''1019170''>a</span> <span m=''1019240''>group,</span> <span m=''1019580''>what</span>
  <span m=''1019700''>does</span> <span m=''1019860''>that</span> <span m=''1020010''>mean?</span>
  <span m=''1020340''>That</span> <span m=''1020500''>means,</span> <span m=''1020740''>if</span>
  <span m=''1020900''>we</span> <span m=''1021030''>take</span> <span m=''1021840''>any</span>
  <span m=''1022010''>particular</span> <span m=''1022490''>point,</span> <span m=''1023010''>say</span>
  <span m=''1023170''>this</span> <span m=''1023420''>one,</span> <span m=''1023640''>regard</span>
  <span m=''1023879''>it</span> <span m=''1024119''>as</span> <span m=''1024210''>a</span>
  <span m=''1024310''>vector,</span> <span m=''1027849''>then</span> <span m=''1031530''>call</span>
  <span m=''1031810''>this</span> <span m=''1032599''>lambda_1</span> <span m=''1033010''>--</span>
  <span m=''1034159''>or</span> <span m=''1034609''>let</span> <span m=''1034740''>me</span>
  <span m=''1035070''>it</span> <span m=''1035400''>g1,</span> <span m=''1035730''>more</span>
  <span m=''1035960''>suggestively.</span> <span m=''1038000''>Does</span> <span m=''1038700''>g1</span>
  <span m=''1039089''>plus</span> <span m=''1039440''>g1</span> <span m=''1039900''>have</span>
  <span m=''1040119''>to</span> <span m=''1040250''>be</span> <span m=''1040480''>in</span>
  <span m=''1040680''>the</span> <span m=''1041020''>group?</span> <span m=''1043310''>Yes.</span>
  </p><p><span m=''1044119''>So</span> <span m=''1044470''>that</span> <span m=''1044829''>forces</span>
  <span m=''1045390''>this</span> <span m=''1045640''>point</span> <span m=''1046010''>to</span>
  <span m=''1046109''>be</span> <span m=''1046240''>in</span> <span m=''1046400''>there,</span>
  <span m=''1046760''>2g1,</span> <span m=''1048860''>3g1,</span> <span m=''1050720''>so</span>
  <span m=''1050960''>forth.</span> <span m=''1051310''>All</span> <span m=''1051560''>of</span>
  <span m=''1051700''>these</span> <span m=''1052070''>have</span> <span m=''1052280''>to</span>
  <span m=''1052400''>be</span> <span m=''1052560''>in</span> <span m=''1052700''>there,</span>
  <span m=''1052960''>as</span> <span m=''1053100''>well</span> <span m=''1053460''>as</span>
  <span m=''1055110''>minus</span> <span m=''1056670''>g1,</span> <span m=''1057860''>minus</span>
  <span m=''1058320''>2g1,</span> <span m=''1059180''>and</span> <span m=''1059380''>so</span>
  <span m=''1059570''>forth.</span> <span m=''1061450''>So</span> <span m=''1061750''>basically,</span>
  <span m=''1062390''>once</span> <span m=''1062700''>we</span> <span m=''1062810''>found</span>
  <span m=''1063050''>a</span> <span m=''1063150''>generator,</span> <span m=''1063790''>all</span>
  <span m=''1064080''>integers</span> <span m=''1064610''>times</span> <span m=''1064930''>that</span>
  <span m=''1065160''>generator</span> <span m=''1065760''>have</span> <span m=''1066240''>to</span>
  <span m=''1066340''>be</span> <span m=''1066490''>in</span> <span m=''1066570''>the</span>
  <span m=''1066650''>lattice.</span> <span m=''1067650''>So</span> <span m=''1067790''>that</span>
  <span m=''1067950''>means</span> <span m=''1068200''>there''s</span> <span m=''1068460''>a</span>
  <span m=''1068540''>cross-section</span> <span m=''1070870''>along</span> <span
  m=''1071290''>the</span> <span m=''1071660''>axis</span> <span m=''1072170''>defined</span>
  <span m=''1072620''>by</span> <span m=''1072760''>g1,</span> <span m=''1074250''>such</span>
  <span m=''1074570''>that</span> <span m=''1074650''>these</span> <span m=''1074890''>points</span>
  <span m=''1075290''>are</span> <span m=''1075380''>simply</span> <span m=''1075820''>the</span>
  <span m=''1076460''>integers,</span> <span m=''1078060''>scaled</span> <span m=''1078520''>by</span>
  <span m=''1079460''>whatever</span> <span m=''1079820''>the</span> <span m=''1080850''>norm</span>
  <span m=''1081260''>of</span> <span m=''1081500''>g1</span> <span m=''1081740''>is.</span>
  </p><p><span m=''1086730''>And</span> <span m=''1087040''>of</span> <span m=''1087140''>course,</span>
  <span m=''1087470''>that</span> <span m=''1087630''>holds</span> <span m=''1088020''>for</span>
  <span m=''1088380''>any</span> <span m=''1088453''>of</span> <span m=''1088526''>these</span>
  <span m=''1088600''>neighbors</span> <span m=''1089040''>here.</span> <span m=''1091770''>You</span>
  <span m=''1091910''>want</span> <span m=''1092040''>to</span> <span m=''1092090''>look</span>
  <span m=''1092320''>for</span> <span m=''1092680''>nearest</span> <span m=''1093110''>neighbors</span>
  <span m=''1093480''>of</span> <span m=''1093560''>0''s.</span> <span m=''1094190''>Take</span>
  <span m=''1094500''>g2</span> <span m=''1095773''>and</span> <span m=''1098380''>then,</span>
  <span m=''1098540''>of</span> <span m=''1098660''>course,</span> <span m=''1099050''>all</span>
  <span m=''1099220''>of</span> <span m=''1099400''>its</span> <span m=''1100710''>integer</span>
  <span m=''1101150''>multiples</span> <span m=''1101790''>have</span> <span m=''1101970''>to</span>
  <span m=''1102080''>be</span> <span m=''1102260''>in</span> <span m=''1102360''>the</span>
  <span m=''1102460''>lattice.</span> <span m=''1102940''>So</span> <span m=''1104110''>we''ve</span>
  <span m=''1104310''>got</span> <span m=''1105400''>a</span> <span m=''1105540''>set</span>
  <span m=''1107210''>here</span> <span m=''1107710''>that,</span> <span m=''1109040''>in</span>
  <span m=''1109160''>some</span> <span m=''1109410''>sense,</span> <span m=''1110850''>spans</span>
  <span m=''1111510''>n-space.</span> <span m=''1113800''>We</span> <span m=''1113930''>have</span>
  <span m=''1114100''>now</span> <span m=''1114290''>two</span> <span m=''1114540''>vectors,</span>
  <span m=''1115130''>g1,</span> <span m=''1115600''>g2,</span> <span m=''1116050''>which</span>
  <span m=''1116250''>are</span> <span m=''1116290''>not</span> <span m=''1116550''>linearly</span>
  <span m=''1116930''>dependent.</span> <span m=''1117570''>They''re</span> <span
  m=''1117690''>sitting</span> <span m=''1118020''>in</span> <span m=''1118300''>2-space.</span>
  <span m=''1119220''>So</span> <span m=''1119430''>if</span> <span m=''1119520''>we</span>
  <span m=''1119630''>take</span> <span m=''1119940''>all</span> <span m=''1120630''>real</span>
  <span m=''1121570''>linear</span> <span m=''1121910''>combinations</span> <span
  m=''1122610''>of</span> <span m=''1122690''>these</span> <span m=''1122920''>two</span>
  <span m=''1123080''>vectors,</span> <span m=''1123530''>we''re</span> <span m=''1123640''>going</span>
  <span m=''1123740''>to</span> <span m=''1123800''>get</span> <span m=''1123926''>all</span>
  <span m=''1124053''>of</span> <span m=''1124180''>2-space.</span> </p><p><span m=''1126490''>If</span>
  <span m=''1126600''>we</span> <span m=''1126700''>take</span> <span m=''1126990''>all</span>
  <span m=''1127280''>integer</span> <span m=''1127740''>linear</span> <span m=''1128150''>combinations</span>
  <span m=''1128930''>of</span> <span m=''1129030''>these</span> <span m=''1129280''>two</span>
  <span m=''1129460''>vectors,</span> <span m=''1131821''>they all must</span> <span
  m=''1132640''>be</span> <span m=''1132770''>in</span> <span m=''1132825''>the</span>
  <span m=''1132880''>lattice,</span> <span m=''1133330''>right?</span> <span m=''1133640''>By</span>
  <span m=''1133740''>the</span> <span m=''1133850''>group</span> <span m=''1134080''>property?</span>
  <span m=''1135860''>We''ve</span> <span m=''1136000''>already</span> <span m=''1136260''>proved</span>
  <span m=''1136670''>that</span> <span m=''1137150''>all</span> <span m=''1137410''>the</span>
  <span m=''1137500''>integer</span> <span m=''1137820''>multiples</span> <span m=''1138370''>of</span>
  <span m=''1138420''>either</span> <span m=''1138560''>of</span> <span m=''1138730''>them</span>
  <span m=''1138910''>is</span> <span m=''1139040''>in</span> <span m=''1139120''>the</span>
  <span m=''1139210''>lattice,</span> <span m=''1139640''>so</span> <span m=''1139790''>any</span>
  <span m=''1140480''>thing</span> <span m=''1140660''>plus</span> <span m=''1140940''>or</span>
  <span m=''1141000''>minus</span> <span m=''1141380''>those</span> <span m=''1141690''>two.</span>
  <span m=''1143010''>So</span> <span m=''1143350''>certainly,</span> <span m=''1143960''>the</span>
  <span m=''1144400''>lattice</span> <span m=''1144870''>includes</span> <span m=''1149120''>the</span>
  <span m=''1149250''>set</span> <span m=''1149830''>of</span> <span m=''1150120''>all</span>
  <span m=''1151750''>integer</span> <span m=''1152360''>multiples</span> <span m=''1153450''>of</span>
  <span m=''1155990''>a_i times gi, where</span> <span m=''1157270''>i</span> <span
  m=''1157600''>equals</span> <span m=''1157900''>1</span> <span m=''1158215''>to</span>
  <span m=''1158530''>2,</span> <span m=''1159410''>where</span> <span m=''1160150''>a1,</span>
  <span m=''1160910''>a2</span> <span m=''1161665''>is</span> <span m=''1162120''>in</span>
  <span m=''1162603''>the</span> <span m=''1163570''>two-dimensional</span> <span
  m=''1164330''>integer,</span> <span m=''1165410''>lattice</span> <span m=''1165650''>Z-squared.</span>
  </p><p><span m=''1172590''>Could</span> <span m=''1172780''>there</span> <span m=''1172900''>be</span>
  <span m=''1173080''>any</span> <span m=''1173270''>other</span> <span m=''1173460''>points?</span>
  <span m=''1178720''>There</span> <span m=''1179110''>actually</span> <span m=''1179420''>could,</span>
  <span m=''1179790''>if</span> <span m=''1179910''>you</span> <span m=''1180050''>made</span>
  <span m=''1180250''>a</span> <span m=''1180300''>mistake</span> <span m=''1180800''>and</span>
  <span m=''1180900''>picked</span> <span m=''1181200''>your</span> <span m=''1181500''>initial</span>
  <span m=''1181900''>vector</span> <span m=''1182340''>to</span> <span m=''1182470''>be</span>
  <span m=''1183030''>2g1,</span> <span m=''1184090''>because</span> <span m=''1184310''>then</span>
  <span m=''1185210''>you</span> <span m=''1185380''>wouldn''t</span> <span m=''1185700''>have</span>
  <span m=''1185810''>taken</span> <span m=''1186070''>account</span> <span m=''1186510''>of</span>
  <span m=''1186700''>g1.</span> <span m=''1187290''>So</span> <span m=''1187460''>you''ve</span>
  <span m=''1187550''>got</span> <span m=''1187700''>to</span> <span m=''1187790''>take</span>
  <span m=''1188090''>your</span> <span m=''1188210''>two</span> <span m=''1188460''>initial</span>
  <span m=''1189230''>vectors</span> <span m=''1189780''>to</span> <span m=''1189900''>be</span>
  <span m=''1190830''>two</span> <span m=''1191070''>of</span> <span m=''1191150''>the</span>
  <span m=''1191230''>minimum</span> <span m=''1191610''>norm</span> <span m=''1192200''>points</span>
  <span m=''1192630''>in</span> <span m=''1192730''>the</span> <span m=''1192830''>lattice.</span>
  <span m=''1193380''>But</span> <span m=''1193820''>if</span> <span m=''1193980''>you</span>
  <span m=''1194120''>do</span> <span m=''1194330''>that,</span> <span m=''1194970''>then</span>
  <span m=''1195170''>you</span> <span m=''1195310''>can</span> <span m=''1195690''>easily</span>
  <span m=''1196030''>prove</span> <span m=''1196450''>that</span> <span m=''1197600''>this</span>
  <span m=''1198230''>is</span> <span m=''1198480''>all</span> <span m=''1198810''>of</span>
  <span m=''1198855''>the</span> <span m=''1198900''>lattice</span> <span m=''1199320''>points.</span>
  </p><p><span m=''1199680''>So</span> <span m=''1199890''>in</span> <span m=''1200020''>fact,</span>
  <span m=''1200830''>a</span> <span m=''1200920''>two-dimensional</span> <span m=''1201860''>lattice</span>
  <span m=''1203000''>is</span> <span m=''1203220''>equal</span> <span m=''1204590''>to</span>
  <span m=''1206496''>a</span> <span m=''1206970''>set</span> <span m=''1207300''>of</span>
  <span m=''1207545''>all</span> <span m=''1207790''>integer</span> <span m=''1208190''>linear</span>
  <span m=''1208580''>combinations</span> <span m=''1209330''>of</span> <span m=''1209450''>two</span>
  <span m=''1209660''>generators,</span> <span m=''1210760''>which</span> <span m=''1210990''>we</span>
  <span m=''1211120''>can</span> <span m=''1211270''>write</span> <span m=''1211540''>as</span>
  <span m=''1211710''>a</span> <span m=''1211780''>little</span> <span m=''1212090''>two-by-two</span>
  <span m=''1212630''>generator</span> <span m=''1213100''>matrix,</span> <span m=''1213670''>G.</span>
  <span m=''1215040''>Or</span> <span m=''1215540''>very</span> <span m=''1215800''>briefly,</span>
  <span m=''1216400''>we</span> <span m=''1216550''>could</span> <span m=''1216710''>write</span>
  <span m=''1217590''>lambda</span> <span m=''1218270''>as</span> <span m=''1218630''>G</span>
  <span m=''1219060''>times</span> <span m=''1219700''>Z-squared,</span> <span m=''1220920''>and</span>
  <span m=''1221140''>we</span> <span m=''1221270''>can</span> <span m=''1221410''>view</span>
  <span m=''1221730''>it</span> <span m=''1221763''>as</span> <span m=''1221796''>just</span>
  <span m=''1221960''>some</span> <span m=''1222260''>linear</span> <span m=''1222590''>transformation</span>
  <span m=''1223400''>of</span> <span m=''1223700''>Z-squared.</span> </p><p><span
  m=''1226040''>So</span> <span m=''1226310''>in</span> <span m=''1226425''>this</span>
  <span m=''1226540''>hexagonal</span> <span m=''1227010''>lattice,</span> <span m=''1227550''>we</span>
  <span m=''1227690''>can</span> <span m=''1228060''>view</span> <span m=''1228330''>it</span>
  <span m=''1228610''>as</span> <span m=''1229900''>starting</span> <span m=''1230400''>out</span>
  <span m=''1230660''>with</span> <span m=''1230930''>a</span> <span m=''1231760''>square</span>
  <span m=''1232540''>grid.</span> <span m=''1232820''>Of</span> <span m=''1233100''>course,</span>
  <span m=''1233620''>Z-squared</span> <span m=''1234010''>itself</span> <span m=''1234490''>is</span>
  <span m=''1234840''>a</span> <span m=''1234950''>lattice.</span> <span m=''1237090''>Z-squared</span>
  <span m=''1237470''>is</span> <span m=''1237590''>a</span> <span m=''1237640''>group.</span>
  <span m=''1239840''>This</span> <span m=''1240030''>is</span> <span m=''1240120''>just</span>
  <span m=''1240360''>the</span> <span m=''1240430''>square</span> <span m=''1240790''>lattice</span>
  <span m=''1241280''>in</span> <span m=''1241440''>two</span> <span m=''1241600''>dimensions.</span>
  <span m=''1243320''>We</span> <span m=''1243460''>have</span> <span m=''1243610''>Z_n</span>
  <span m=''1244150''>as</span> <span m=''1244340''>a</span> <span m=''1244410''>lattice</span>
  <span m=''1244890''>in</span> <span m=''1245130''>n</span> <span m=''1245400''>dimensions,</span>
  <span m=''1245980''>in</span> <span m=''1246060''>general.</span> <span m=''1248350''>So</span>
  <span m=''1248560''>I</span> <span m=''1248650''>take</span> <span m=''1249580''>Z-squared,</span>
  <span m=''1250160''>Z_n,</span> <span m=''1250650''>more</span> <span m=''1250830''>generally,</span>
  <span m=''1251210''>and</span> <span m=''1251590''>I</span> <span m=''1251760''>distort</span>
  <span m=''1252220''>it.</span> <span m=''1253300''>I</span> <span m=''1253750''>just</span>
  <span m=''1254130''>run</span> <span m=''1254390''>it</span> <span m=''1254490''>through</span>
  <span m=''1254780''>some</span> <span m=''1256840''>g,</span> <span m=''1258740''>which</span>
  <span m=''1259170''>is</span> <span m=''1259230''>a</span> <span m=''1259290''>linear</span>
  <span m=''1259620''>transformation,</span> <span m=''1261395''>and</span> <span
  m=''1261850''>slants</span> <span m=''1262920''>some</span> <span m=''1263220''>of</span>
  <span m=''1263370''>the</span> <span m=''1265030''>generator</span> <span m=''1265530''>points.</span>
  </p><p><span m=''1266130''>And</span> <span m=''1266260''>that''s</span> <span m=''1266660''>a</span>
  <span m=''1266730''>general</span> <span m=''1267050''>way</span> <span m=''1267190''>of</span>
  <span m=''1267300''>getting</span> <span m=''1267530''>a</span> <span m=''1267970''>lattice.</span>
  <span m=''1268270''>That''s</span> <span m=''1268830''>not</span> <span m=''1268980''>the</span>
  <span m=''1269050''>way</span> <span m=''1269190''>we</span> <span m=''1269340''>usually</span>
  <span m=''1269650''>visualize</span> <span m=''1270330''>the</span> <span m=''1270410''>hexagonal</span>
  <span m=''1270970''>lattice.</span> <span m=''1271400''>We</span> <span m=''1271530''>usually</span>
  <span m=''1271900''>visualize</span> <span m=''1272470''>it</span> <span m=''1272540''>in</span>
  <span m=''1272630''>such</span> <span m=''1272900''>a</span> <span m=''1272960''>way</span>
  <span m=''1273740''>as</span> <span m=''1274000''>to</span> <span m=''1274290''>recognize</span>
  <span m=''1274660''>that</span> <span m=''1275030''>it</span> <span m=''1275310''>has</span>
  <span m=''1275500''>six-fold</span> <span m=''1276090''>symmetry.</span> <span m=''1278000''>But</span>
  <span m=''1279660''>that''s</span> <span m=''1279890''>certainly</span> <span m=''1280280''>a</span>
  <span m=''1280370''>way</span> <span m=''1280530''>to</span> <span m=''1280680''>get</span>
  <span m=''1280990''>it.</span> <span m=''1284740''>And</span> <span m=''1284920''>this</span>
  <span m=''1285150''>has</span> <span m=''1285790''>one</span> <span m=''1286050''>interesting</span>
  <span m=''1286650''>consequence.</span> <span m=''1288426''>One</span> <span m=''1288613''>of</span>
  <span m=''1288800''>the</span> <span m=''1289040''>measures</span> <span m=''1289570''>we</span>
  <span m=''1289690''>want</span> <span m=''1290020''>for</span> <span m=''1290160''>a</span>
  <span m=''1290230''>lattice</span> <span m=''1290710''>is</span> <span m=''1290930''>the</span>
  <span m=''1291030''>volume</span> <span m=''1291530''>per</span> <span m=''1291800''>lattice</span>
  <span m=''1292260''>point.</span> <span m=''1294500''>In</span> <span m=''1294680''>here,</span>
  <span m=''1296600''>the</span> <span m=''1296690''>volume,</span> <span m=''1297600''>you</span>
  <span m=''1297890''>can</span> <span m=''1298210''>divide</span> <span m=''1298600''>this</span>
  <span m=''1298840''>up</span> <span m=''1299080''>into</span> <span m=''1300350''>volumes</span>
  <span m=''1301210''>that</span> <span m=''1301430''>are</span> <span m=''1301570''>all</span>
  <span m=''1301870''>of</span> <span m=''1301970''>equal</span> <span m=''1302240''>size,</span>
  <span m=''1302530''>and</span> <span m=''1302910''>we</span> <span m=''1303110''>call</span>
  <span m=''1303410''>that</span> <span m=''1303770''>the</span> <span m=''1303840''>volume</span>
  <span m=''1304390''>of</span> <span m=''1304650''>A2.</span> <span m=''1305180''>This</span>
  <span m=''1305450''>lattice --</span> <span m=''1306280''>hexagonal</span> <span
  m=''1306900''>lattice,</span> <span m=''1307320''>is</span> <span m=''1307480''>called</span>
  <span m=''1307830''>A2,</span> <span m=''1309400''>and</span> <span m=''1309540''>it''s</span>
  <span m=''1309750''>the</span> <span m=''1309830''>volume</span> <span m=''1310300''>of</span>
  <span m=''1310450''>that</span> <span m=''1310680''>hexagon.</span> </p><p><span
  m=''1313200''>1</span> <span m=''1313440''>over</span> <span m=''1313670''>the</span>
  <span m=''1313770''>volume</span> <span m=''1314160''>of</span> <span m=''1314380''>that</span>
  <span m=''1314590''>hexagon</span> <span m=''1315380''>is</span> <span m=''1315720''>the</span>
  <span m=''1315820''>density</span> <span m=''1316610''>of</span> <span m=''1317410''>points</span>
  <span m=''1317930''>in</span> <span m=''1318210''>2-space,</span> <span m=''1318920''>if</span>
  <span m=''1319060''>you</span> <span m=''1319200''>like.</span> <span m=''1319600''>So</span>
  <span m=''1320170''>density</span> <span m=''1320670''>is</span> <span m=''1320840''>1/volume.</span>
  <span m=''1323490''>I</span> <span m=''1323685''>mean,</span> <span m=''1324040''>think</span>
  <span m=''1324190''>of</span> <span m=''1324260''>every</span> <span m=''1324520''>point</span>
  <span m=''1324840''>as</span> <span m=''1325000''>having</span> <span m=''1325715''>a</span>
  <span m=''1325980''>unique</span> <span m=''1326360''>volume,</span> <span m=''1326645''>and</span>
  <span m=''1326930''>if</span> <span m=''1327870''>we</span> <span m=''1327990''>basically</span>
  <span m=''1330380''>consider</span> <span m=''1330780''>the</span> <span m=''1330880''>cells</span>
  <span m=''1331360''>around</span> <span m=''1331640''>each</span> <span m=''1331880''>lattice</span>
  <span m=''1332270''>point,</span> <span m=''1332600''>they</span> <span m=''1332730''>fill</span>
  <span m=''1332980''>up</span> <span m=''1333150''>2-space,</span> <span m=''1334910''>or</span>
  <span m=''1335140''>the</span> <span m=''1335550''>perfect</span> <span m=''1336260''>tessellation</span>
  <span m=''1337070''>tiling</span> <span m=''1337560''>of</span> <span m=''1338290''>2-space.</span>
  <span m=''1339920''>These</span> <span m=''1340100''>hexagons</span> <span m=''1340650''>will.</span>
  </p><p><span m=''1342360''>One</span> <span m=''1342740''>easy</span> <span m=''1343100''>consequence</span>
  <span m=''1343820''>of</span> <span m=''1343880''>the</span> <span m=''1343940''>group</span>
  <span m=''1344230''>property</span> <span m=''1344790''>is</span> <span m=''1344960''>that</span>
  <span m=''1345050''>all</span> <span m=''1345240''>the</span> <span m=''1345310''>decision</span>
  <span m=''1345710''>regions</span> <span m=''1346170''>have</span> <span m=''1346360''>to</span>
  <span m=''1346480''>be</span> <span m=''1346800''>congruent,</span> <span m=''1348260''>in</span>
  <span m=''1348590''>fact,</span> <span m=''1348890''>just</span> <span m=''1349190''>translates</span>
  <span m=''1349800''>of</span> <span m=''1349870''>one</span> <span m=''1350020''>another</span>
  <span m=''1350300''>by</span> <span m=''1350470''>lattice</span> <span m=''1350890''>points.</span>
  <span m=''1352170''>The</span> <span m=''1352620''>decision</span> <span m=''1353030''>region</span>
  <span m=''1353440''>around</span> <span m=''1354620''>this</span> <span m=''1354890''>point</span>
  <span m=''1355220''>is</span> <span m=''1355350''>the</span> <span m=''1355430''>same</span>
  <span m=''1355730''>as</span> <span m=''1355830''>the</span> <span m=''1355920''>decision</span>
  <span m=''1356310''>region</span> <span m=''1356660''>about</span> <span m=''1356960''>0,</span>
  <span m=''1357370''>translated</span> <span m=''1358000''>by</span> <span m=''1358160''>a</span>
  <span m=''1358370''>lattice</span> <span m=''1358580''>point,</span> <span m=''1359510''>namely</span>
  <span m=''1359830''>the</span> <span m=''1359960''>center</span> <span m=''1360290''>of</span>
  <span m=''1360480''>that</span> <span m=''1360670''>decision</span> <span m=''1361015''>region.</span>
  <span m=''1361360''>I</span> <span m=''1361620''>won''t</span> <span m=''1361880''>prove</span>
  <span m=''1362190''>that</span> <span m=''1362825''>but</span> <span m=''1363100''>it''s</span>
  <span m=''1363310''>true</span> <span m=''1363590''>and</span> <span m=''1363730''>easy</span>
  <span m=''1363960''>to</span> <span m=''1364161''>prove.</span> </p><p><span m=''1365950''>So</span>
  <span m=''1366130''>that''s</span> <span m=''1366370''>one</span> <span m=''1366600''>way</span>
  <span m=''1366890''>of</span> <span m=''1367010''>finding</span> <span m=''1367390''>what''s</span>
  <span m=''1367570''>the</span> <span m=''1367740''>volume.</span> <span m=''1368435''>The</span>
  <span m=''1368720''>volume</span> <span m=''1369150''>will</span> <span m=''1369280''>mean</span>
  <span m=''1369520''>the</span> <span m=''1369610''>volume</span> <span m=''1369990''>of</span>
  <span m=''1370080''>2-space</span> <span m=''1370720''>per</span> <span m=''1370910''>lattice</span>
  <span m=''1371280''>point.</span> <span m=''1371590''>But</span> <span m=''1371920''>what''s</span>
  <span m=''1372230''>another</span> <span m=''1372940''>way</span> <span m=''1373140''>to</span>
  <span m=''1373250''>do</span> <span m=''1373450''>that?</span> <span m=''1373700''>Another</span>
  <span m=''1373780''>way</span> <span m=''1373940''>is</span> <span m=''1374360''>just</span>
  <span m=''1374480''>to</span> <span m=''1374690''>take</span> <span m=''1375890''>this</span>
  <span m=''1376200''>little</span> <span m=''1376630''>parallelotope,</span> <span
  m=''1377550''>whose</span> <span m=''1377770''>volume</span> <span m=''1378200''>is</span>
  <span m=''1378890''>easier</span> <span m=''1379470''>to</span> <span m=''1381550''>calculate.</span>
  <span m=''1383410''>And</span> <span m=''1383590''>we</span> <span m=''1383730''>can</span>
  <span m=''1383870''>see</span> <span m=''1384230''>that</span> <span m=''1385150''>we</span>
  <span m=''1385480''>can</span> <span m=''1385610''>equally</span> <span m=''1385940''>well</span>
  <span m=''1386290''>tile</span> <span m=''1387040''>2-space</span> <span m=''1387700''>with</span>
  <span m=''1387810''>these</span> <span m=''1388050''>little</span> <span m=''1388270''>parallelograms,</span>
  <span m=''1390550''>just</span> <span m=''1390940''>anchor --</span> <span m=''1391550''>in</span>
  <span m=''1391900''>this</span> <span m=''1392240''>case,</span> <span m=''1392570''>this</span>
  <span m=''1392750''>is</span> <span m=''1392890''>the</span> <span m=''1392980''>one</span>
  <span m=''1393210''>that''s</span> <span m=''1393420''>anchored</span> <span m=''1393850''>in</span>
  <span m=''1393930''>the</span> <span m=''1394020''>lower</span> <span m=''1394280''>left</span>
  <span m=''1394550''>corner</span> <span m=''1394920''>by</span> <span m=''1395570''>the</span>
  <span m=''1395760''>origin.</span> </p><p><span m=''1396830''>Then</span> <span
  m=''1396950''>we</span> <span m=''1397070''>take</span> <span m=''1397290''>another</span>
  <span m=''1397570''>one</span> <span m=''1397750''>that''s</span> <span m=''1397930''>anchored</span>
  <span m=''1398340''>by</span> <span m=''1398520''>this</span> <span m=''1398800''>point.</span>
  <span m=''1399120''>We</span> <span m=''1399540''>take</span> <span m=''1400040''>another</span>
  <span m=''1400163''>one</span> <span m=''1400286''>that''s</span> <span m=''1400410''>anchored</span>
  <span m=''1400850''>by</span> <span m=''1401010''>this</span> <span m=''1401300''>point,</span>
  <span m=''1401830''>another</span> <span m=''1401976''>one</span> <span m=''1402123''>that''s</span>
  <span m=''1402270''>anchored</span> <span m=''1402590''>by</span> <span m=''1402720''>this</span>
  <span m=''1402950''>point.</span> <span m=''1403760''>And</span> <span m=''1403890''>it''s</span>
  <span m=''1404030''>clear</span> <span m=''1404320''>that''s</span> <span m=''1404750''>another</span>
  <span m=''1405230''>tiling</span> <span m=''1405930''>of</span> <span m=''1406230''>2-space</span>
  <span m=''1406940''>by</span> <span m=''1407980''>regions,</span> <span m=''1408590''>one</span>
  <span m=''1408900''>for</span> <span m=''1409080''>each</span> <span m=''1409350''>lattice</span>
  <span m=''1409710''>point</span> <span m=''1410070''>that</span> <span m=''1410180''>completely</span>
  <span m=''1410680''>fills</span> <span m=''1411110''>2-space</span> <span m=''1411880''>with</span>
  <span m=''1412300''>overlaps</span> <span m=''1412850''>only</span> <span m=''1413070''>on</span>
  <span m=''1413180''>the</span> <span m=''1413270''>boundary,</span> <span m=''1413710''>which</span>
  <span m=''1413960''>don''t</span> <span m=''1414200''>count.</span> </p><p><span
  m=''1416570''>So</span> <span m=''1417010''>the</span> <span m=''1417110''>volume</span>
  <span m=''1417330''>of</span> <span m=''1417550''>A2</span> <span m=''1417950''>is</span>
  <span m=''1418120''>also</span> <span m=''1418580''>the</span> <span m=''1418670''>volume</span>
  <span m=''1419070''>of</span> <span m=''1419310''>that,</span> <span m=''1419970''>what''s</span>
  <span m=''1420140''>called</span> <span m=''1420340''>a</span> <span m=''1420410''>fundamental</span>
  <span m=''1420940''>parallelotope.</span> <span m=''1422780''>And</span> <span m=''1422920''>what''s</span>
  <span m=''1423170''>the</span> <span m=''1423250''>volume</span> <span m=''1423650''>of</span>
  <span m=''1423730''>that</span> <span m=''1423950''>fundamental</span> <span m=''1424420''>parallelotope?</span>
  <span m=''1426690''>Well,</span> <span m=''1426960''>one</span> <span m=''1427110''>way</span>
  <span m=''1427260''>of</span> <span m=''1427380''>calculating</span> <span m=''1428130''>it</span>
  <span m=''1428310''>is</span> <span m=''1428630''>to</span> <span m=''1430320''>take</span>
  <span m=''1432290''>the</span> <span m=''1432450''>volume</span> <span m=''1433720''>of</span>
  <span m=''1434120''>Z-squared.</span> <span m=''1435420''>We</span> <span m=''1435550''>can</span>
  <span m=''1435690''>view</span> <span m=''1435900''>this</span> <span m=''1436220''>as</span>
  <span m=''1436420''>the</span> <span m=''1436520''>distortion</span> <span m=''1436915''>of</span>
  <span m=''1439110''>Z-squared,</span> <span m=''1439630''>which</span> <span m=''1439840''>looks</span>
  <span m=''1440100''>like</span> <span m=''1440360''>this.</span> <span m=''1443690''>So</span>
  <span m=''1443930''>if</span> <span m=''1443970''>this</span> <span m=''1444220''>is</span>
  <span m=''1444630''>Z-squared,</span> <span m=''1445680''>what''s</span> <span m=''1445900''>the</span>
  <span m=''1446520''>fundamental</span> <span m=''1447120''>volume</span> <span m=''1447490''>of</span>
  <span m=''1447860''>Z-squared?</span> <span m=''1449320''>The</span> <span m=''1449480''>volume</span>
  <span m=''1449720''>of</span> <span m=''1449800''>Z-squared</span> <span m=''1450200''>per</span>
  <span m=''1450300''>lattice</span> <span m=''1450700''>point.</span> <span m=''1451640''>This</span>
  <span m=''1451870''>is</span> <span m=''1452100''>(0,1,-1,1, so forth,1,1).</span>
  <span m=''1459150''>What''s</span> <span m=''1459500''>the</span> <span m=''1459580''>volume</span>
  <span m=''1459995''>of</span> <span m=''1460660''>Z-squared</span> <span m=''1461140''>per--</span>
  </p><p><span m=''1461520''>AUDIENCE: 1</span> </p><p><span m=''1462720''>PROFESSOR:
  --1.</span> <span m=''1463370''>Clearly.</span> <span m=''1465176''>And</span> <span
  m=''1465640''>we</span> <span m=''1465815''>have</span> <span m=''1465902''>this</span>
  <span m=''1465990''>decision</span> <span m=''1466470''>region.</span> <span m=''1466850''>This</span>
  <span m=''1467010''>is</span> <span m=''1467310''>little</span> <span m=''1467760''>square</span>
  <span m=''1468230''>side</span> <span m=''1468630''>1,</span> <span m=''1469030''>or</span>
  <span m=''1469170''>this</span> <span m=''1469430''>parallelotope</span> <span m=''1469900''>is</span>
  <span m=''1470010''>also</span> <span m=''1470300''>little</span> <span m=''1470900''>square</span>
  <span m=''1471300''>side</span> <span m=''1471590''>1.</span> <span m=''1471930''>It''s</span>
  <span m=''1472200''>volume</span> <span m=''1472390''>is</span> <span m=''1472760''>1.</span>
  <span m=''1476220''>General</span> <span m=''1476590''>geometric</span> <span m=''1477270''>principle,</span>
  <span m=''1478010''>if</span> <span m=''1478130''>we</span> <span m=''1478270''>take</span>
  <span m=''1478990''>this</span> <span m=''1479320''>and</span> <span m=''1479450''>distort</span>
  <span m=''1479760''>it</span> <span m=''1480070''>by</span> <span m=''1480280''>G,</span>
  <span m=''1482980''>then</span> <span m=''1483160''>what''s</span> <span m=''1483370''>the</span>
  <span m=''1483570''>volume</span> <span m=''1485060''>of,</span> <span m=''1485800''>say,</span>
  <span m=''1486190''>this</span> <span m=''1486830''>parallelotope</span> <span m=''1487570''>going</span>
  <span m=''1487810''>to</span> <span m=''1488050''>be?</span> <span m=''1488610''>This</span>
  <span m=''1489470''>parallelotope</span> <span m=''1490390''>goes</span> <span m=''1490700''>by</span>
  <span m=''1490850''>G</span> <span m=''1491270''>into</span> <span m=''1491530''>this</span>
  <span m=''1491790''>one,</span> <span m=''1493240''>and</span> <span m=''1493410''>its</span>
  <span m=''1493580''>volume</span> <span m=''1494080''>is</span> <span m=''1494330''>the</span>
  <span m=''1494470''>Jacobian,</span> <span m=''1495330''>which</span> <span m=''1495600''>is</span>
  <span m=''1495820''>the</span> <span m=''1496490''>determinant</span> <span m=''1497040''>of</span>
  <span m=''1497170''>G.</span> </p><p><span m=''1499010''>So</span> <span m=''1499790''>the</span>
  <span m=''1499870''>volume</span> <span m=''1500380''>of</span> <span m=''1500420''>a</span>
  <span m=''1500480''>lattice</span> <span m=''1500930''>is</span> <span m=''1501380''>the</span>
  <span m=''1501570''>determinant</span> <span m=''1502970''>of</span> <span m=''1503110''>any</span>
  <span m=''1504950''>generator</span> <span m=''1505440''>matrix</span> <span m=''1505940''>for</span>
  <span m=''1506040''>that</span> <span m=''1506270''>lattice.</span> <span m=''1506730''>Just</span>
  <span m=''1507650''>a</span> <span m=''1507740''>nice</span> <span m=''1508100''>little</span>
  <span m=''1508260''>side</span> <span m=''1508690''>fact,</span> <span m=''1511710''>but</span>
  <span m=''1512080''>it''s</span> <span m=''1512550''>an</span> <span m=''1512600''>example</span>
  <span m=''1512965''>of</span> <span m=''1513147''>the</span> <span m=''1513330''>kind</span>
  <span m=''1513540''>of</span> <span m=''1513620''>things</span> <span m=''1513870''>you</span>
  <span m=''1514030''>get</span> <span m=''1514290''>in</span> <span m=''1514530''>Euclidean</span>
  <span m=''1515000''>space</span> <span m=''1515460''>that</span> <span m=''1515550''>you</span>
  <span m=''1515660''>don''t</span> <span m=''1515890''>get</span> <span m=''1516080''>in</span>
  <span m=''1516240''>Hamming</span> <span m=''1516740''>space.</span> <span m=''1518980''>Of</span>
  <span m=''1519100''>course,</span> <span m=''1519430''>there</span> <span m=''1519630''>are</span>
  <span m=''1519960''>various</span> <span m=''1521780''>generator</span> <span m=''1522220''>matrices</span>
  <span m=''1522860''>that</span> <span m=''1522940''>you</span> <span m=''1523110''>could</span>
  <span m=''1523290''>use</span> <span m=''1523600''>to</span> <span m=''1523710''>generate</span>
  <span m=''1524170''>this</span> <span m=''1524390''>lattice.</span> <span m=''1524900''>But</span>
  <span m=''1525960''>whichever</span> <span m=''1526310''>one</span> <span m=''1526480''>you</span>
  <span m=''1526610''>choose,</span> <span m=''1527030''>this</span> <span m=''1527200''>is</span>
  <span m=''1527320''>going</span> <span m=''1527470''>to</span> <span m=''1527520''>be</span>
  <span m=''1527630''>true.</span> </p><p><span m=''1529340''>So</span> <span m=''1529580''>this</span>
  <span m=''1529780''>is</span> <span m=''1529920''>an</span> <span m=''1530170''>invariant</span>
  <span m=''1530820''>among</span> <span m=''1531100''>all</span> <span m=''1531280''>the</span>
  <span m=''1531370''>generating</span> <span m=''1531830''>matrices.</span> <span
  m=''1534880''>So</span> <span m=''1535620''>that''s</span> <span m=''1535850''>a</span>
  <span m=''1535910''>lattice.</span> <span m=''1537504''>I</span> <span m=''1537956''>haven''t</span>
  <span m=''1538410''>mentioned</span> <span m=''1539430''>what''s</span> <span m=''1539620''>the</span>
  <span m=''1539810''>most</span> <span m=''1540100''>important</span> <span m=''1540780''>thing</span>
  <span m=''1541020''>for</span> <span m=''1541230''>us</span> <span m=''1541490''>about</span>
  <span m=''1541710''>a</span> <span m=''1541770''>lattice.</span> <span m=''1542065''>A</span>
  <span m=''1542360''>lattice</span> <span m=''1542830''>is</span> <span m=''1542970''>a</span>
  <span m=''1543040''>group.</span> <span m=''1545610''>What''s</span> <span m=''1545920''>the</span>
  <span m=''1546230''>fundamental</span> <span m=''1546830''>property</span> <span
  m=''1547480''>of</span> <span m=''1547670''>a</span> <span m=''1550420''>group,</span>
  <span m=''1556920''>which</span> <span m=''1557270''>I</span> <span m=''1557340''>guess</span>
  <span m=''1557600''>was</span> <span m=''1557770''>embodied</span> <span m=''1558320''>in</span>
  <span m=''1559210''>the</span> <span m=''1559740''>alternate</span> <span m=''1560270''>set</span>
  <span m=''1560470''>of</span> <span m=''1560580''>axioms</span> <span m=''1561200''>for</span>
  <span m=''1561310''>the</span> <span m=''1561420''>group?</span> <span m=''1563620''>If</span>
  <span m=''1563860''>I</span> <span m=''1563990''>take</span> <span m=''1565850''>the</span>
  <span m=''1566300''>group</span> <span m=''1567690''>plus</span> <span m=''1568800''>any</span>
  <span m=''1569000''>element</span> <span m=''1569360''>of</span> <span m=''1569400''>the</span>
  <span m=''1569480''>group,</span> <span m=''1570800''>what</span> <span m=''1570900''>do</span>
  <span m=''1570950''>I</span> <span m=''1571050''>get?</span> </p><p><span m=''1573300''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''1574510''>PROFESSOR: The</span> <span m=''1574590''>group</span>
  <span m=''1574840''>again.</span> <span m=''1579000''>Let''s</span> <span m=''1579350''>interpret</span>
  <span m=''1579860''>that</span> <span m=''1580090''>geometrically.</span> <span
  m=''1580870''>One</span> <span m=''1580940''>of</span> <span m=''1581010''>the</span>
  <span m=''1581080''>nice</span> <span m=''1581480''>things</span> <span m=''1581720''>about</span>
  <span m=''1581900''>this</span> <span m=''1582010''>subject</span> <span m=''1582440''>is</span>
  <span m=''1582610''>you''re</span> <span m=''1582690''>constantly</span> <span m=''1583130''>going</span>
  <span m=''1583350''>back</span> <span m=''1583620''>and</span> <span m=''1583720''>forth</span>
  <span m=''1584010''>between</span> <span m=''1584240''>algebra</span> <span m=''1584525''>and</span>
  <span m=''1585130''>geometry.</span> <span m=''1587100''>Geometrically,</span> <span
  m=''1587850''>what</span> <span m=''1587990''>does</span> <span m=''1588150''>that</span>
  <span m=''1588320''>mean?</span> <span m=''1588600''>That</span> <span m=''1588760''>means,</span>
  <span m=''1589580''>if</span> <span m=''1589720''>we</span> <span m=''1589840''>take</span>
  <span m=''1590520''>this</span> <span m=''1590770''>lattice,</span> <span m=''1591030''>say</span>
  <span m=''1591290''>the</span> <span m=''1591530''>origin</span> <span m=''1591960''>is</span>
  <span m=''1592100''>here,</span> <span m=''1594400''>and</span> <span m=''1594870''>we</span>
  <span m=''1595020''>shift</span> <span m=''1595410''>it,</span> <span m=''1595620''>say,</span>
  <span m=''1596110''>so</span> <span m=''1596380''>that</span> <span m=''1596460''>the</span>
  <span m=''1596600''>origin</span> <span m=''1597060''>is</span> <span m=''1597200''>up</span>
  <span m=''1597410''>here,</span> <span m=''1599960''>then</span> <span m=''1600070''>nothing</span>
  <span m=''1600340''>changes.</span> <span m=''1601350''>Everything</span> <span
  m=''1601670''>is</span> <span m=''1601800''>invariant</span> <span m=''1602260''>to</span>
  <span m=''1602590''>this</span> <span m=''1602740''>shift.</span> <span m=''1605280''>We</span>
  <span m=''1605340''>can</span> <span m=''1605460''>do</span> <span m=''1605575''>this</span>
  <span m=''1605690''>for</span> <span m=''1605840''>any</span> <span m=''1605990''>lattice</span>
  <span m=''1606400''>point.</span> </p><p><span m=''1608260''>That</span> <span m=''1608940''>shows</span>
  <span m=''1609370''>you</span> <span m=''1609680''>that</span> <span m=''1609830''>all</span>
  <span m=''1610070''>the</span> <span m=''1610140''>decision</span> <span m=''1610580''>regions</span>
  <span m=''1611050''>have</span> <span m=''1611270''>to</span> <span m=''1611330''>be</span>
  <span m=''1611470''>congruent.</span> <span m=''1612990''>It</span> <span m=''1613140''>shows</span>
  <span m=''1613490''>you</span> <span m=''1613800''>that</span> <span m=''1616340''>the</span>
  <span m=''1621080''>number</span> <span m=''1621470''>of</span> <span m=''1621600''>nearest</span>
  <span m=''1622070''>neighbors,</span> <span m=''1623480''>the</span> <span m=''1624000''>minimum</span>
  <span m=''1624510''>distance</span> <span m=''1625140''>from</span> <span m=''1625450''>any</span>
  <span m=''1625720''>point</span> <span m=''1626220''>to</span> <span m=''1626410''>its</span>
  <span m=''1627330''>nearest</span> <span m=''1627820''>neighbors</span> <span m=''1629840''>is</span>
  <span m=''1630070''>always</span> <span m=''1630360''>the</span> <span m=''1630440''>same</span>
  <span m=''1630900''>for</span> <span m=''1631050''>any</span> <span m=''1631210''>lattice</span>
  <span m=''1631630''>point.</span> <span m=''1632470''>Basically --</span> <span
  m=''1634240''>it''s</span> <span m=''1634910''>a</span> <span m=''1635340''>lattice</span>
  <span m=''1635790''>is</span> <span m=''1635970''>geometrically</span> <span m=''1636710''>uniform.</span>
  <span m=''1638030''>That</span> <span m=''1638220''>means</span> <span m=''1638490''>you</span>
  <span m=''1638680''>can</span> <span m=''1639570''>stand</span> <span m=''1640030''>on</span>
  <span m=''1640180''>any</span> <span m=''1640470''>of</span> <span m=''1640510''>the</span>
  <span m=''1640600''>points</span> <span m=''1641470''>and</span> <span m=''1641650''>the</span>
  <span m=''1641720''>world</span> <span m=''1642030''>around</span> <span m=''1642370''>you</span>
  <span m=''1642510''>looks</span> <span m=''1642770''>the</span> <span m=''1642880''>same,</span>
  <span m=''1643400''>as</span> <span m=''1643610''>if</span> <span m=''1643730''>you</span>
  <span m=''1643890''>stood</span> <span m=''1644240''>on</span> <span m=''1644420''>any</span>
  <span m=''1644630''>of</span> <span m=''1644670''>the</span> <span m=''1644830''>other</span>
  <span m=''1645000''>points.</span> </p><p><span m=''1646310''>Think</span> <span
  m=''1646480''>of</span> <span m=''1646540''>these</span> <span m=''1646680''>as</span>
  <span m=''1646820''>stars</span> <span m=''1647430''>in</span> <span m=''1647480''>the</span>
  <span m=''1647530''>universe,</span> <span m=''1648980''>and</span> <span m=''1649740''>somebody</span>
  <span m=''1650160''>blindfolds</span> <span m=''1650890''>you</span> <span m=''1651130''>and</span>
  <span m=''1651260''>drops</span> <span m=''1651650''>you</span> <span m=''1651820''>on</span>
  <span m=''1651960''>one</span> <span m=''1652150''>of</span> <span m=''1652240''>these</span>
  <span m=''1652500''>points.</span> <span m=''1653770''>Can</span> <span m=''1653870''>you</span>
  <span m=''1654030''>tell</span> <span m=''1654340''>which</span> <span m=''1654530''>one</span>
  <span m=''1654680''>of</span> <span m=''1654810''>those</span> <span m=''1654940''>points</span>
  <span m=''1655250''>you''ve</span> <span m=''1655380''>been</span> <span m=''1655510''>dropped</span>
  <span m=''1655920''>on</span> <span m=''1657260''>if</span> <span m=''1657490''>nobody''s</span>
  <span m=''1657840''>written</span> <span m=''1658130''>anything</span> <span m=''1658520''>on</span>
  <span m=''1658600''>these</span> <span m=''1658810''>points?</span> <span m=''1660330''>No,</span>
  <span m=''1660510''>you</span> <span m=''1660670''>can''t</span> <span m=''1660970''>tell.</span>
  <span m=''1661270''>The</span> <span m=''1661340''>world</span> <span m=''1661610''>looks</span>
  <span m=''1661850''>the</span> <span m=''1661940''>same</span> <span m=''1662330''>from</span>
  <span m=''1662500''>whichever</span> <span m=''1662790''>one</span> <span m=''1663000''>you</span>
  <span m=''1663100''>drop</span> <span m=''1663490''>on.</span> <span m=''1664350''>So</span>
  <span m=''1664560''>that</span> <span m=''1664750''>means</span> <span m=''1665420''>the</span>
  <span m=''1665540''>minimum</span> <span m=''1665790''>square</span> <span m=''1666620''>distance</span>
  <span m=''1667160''>from</span> <span m=''1667380''>any</span> <span m=''1667570''>point</span>
  <span m=''1667870''>is</span> <span m=''1667980''>the</span> <span m=''1668070''>same</span>
  <span m=''1668340''>as</span> <span m=''1668470''>every</span> <span m=''1668720''>other.</span>
  </p><p><span m=''1669150''>So</span> <span m=''1670290''>the</span> <span m=''1670460''>number</span>
  <span m=''1670790''>of</span> <span m=''1670910''>nearest</span> <span m=''1671300''>neighbors</span>
  <span m=''1671990''>at</span> <span m=''1672330''>minimum</span> <span m=''1672690''>square</span>
  <span m=''1673040''>distance</span> <span m=''1673470''>is</span> <span m=''1673610''>the</span>
  <span m=''1673710''>same.</span> <span m=''1674640''>It</span> <span m=''1674800''>means</span>
  <span m=''1675120''>the</span> <span m=''1675230''>total</span> <span m=''1675590''>distance</span>
  <span m=''1676030''>profile,</span> <span m=''1676730''>starting</span> <span m=''1677080''>from</span>
  <span m=''1677270''>any</span> <span m=''1677390''>point,</span> <span m=''1677980''>is</span>
  <span m=''1678250''>the</span> <span m=''1678530''>same.</span> <span m=''1678950''>It</span>
  <span m=''1679115''>means</span> <span m=''1679280''>if</span> <span m=''1679460''>we</span>
  <span m=''1680215''>were</span> <span m=''1680600''>to</span> <span m=''1680790''>take</span>
  <span m=''1681080''>one</span> <span m=''1681210''>of</span> <span m=''1681250''>these</span>
  <span m=''1681470''>points</span> <span m=''1681930''>and</span> <span m=''1682010''>send</span>
  <span m=''1682230''>it</span> <span m=''1682340''>over</span> <span m=''1682650''>a</span>
  <span m=''1682700''>Gaussian</span> <span m=''1684060''>channel</span> <span m=''1684820''>from</span>
  <span m=''1685030''>a</span> <span m=''1685150''>very</span> <span m=''1685410''>large</span>
  <span m=''1685810''>set,</span> <span m=''1686200''>and</span> <span m=''1686295''>we</span>
  <span m=''1686390''>take</span> <span m=''1686620''>one</span> <span m=''1686740''>of</span>
  <span m=''1686790''>the</span> <span m=''1686860''>points</span> <span m=''1687250''>from</span>
  <span m=''1687320''>the</span> <span m=''1687440''>interior</span> <span m=''1688400''>and</span>
  <span m=''1688690''>send</span> <span m=''1689000''>it</span> <span m=''1689125''>over</span>
  <span m=''1689250''>an</span> <span m=''1690140''>additive</span> <span m=''1690370''>white</span>
  <span m=''1690600''>Gaussian</span> <span m=''1691000''>noise</span> <span m=''1691330''>channel,</span>
  <span m=''1691960''>the</span> <span m=''1692050''>probability</span> <span m=''1692570''>of</span>
  <span m=''1692620''>error</span> <span m=''1692910''>is</span> <span m=''1693060''>going</span>
  <span m=''1693170''>to</span> <span m=''1693280''>be</span> <span m=''1693390''>the</span>
  <span m=''1693490''>same,</span> <span m=''1693840''>regardless</span> <span m=''1694380''>of</span>
  <span m=''1694460''>which</span> <span m=''1695030''>point</span> <span m=''1695600''>we</span>
  <span m=''1695720''>send</span> <span m=''1695940''>it</span> <span m=''1696130''>from,</span>
  <span m=''1696390''>because</span> <span m=''1696730''>the</span> <span m=''1696800''>probability</span>
  <span m=''1697230''>of</span> <span m=''1697290''>error</span> <span m=''1697490''>is</span>
  <span m=''1697610''>the</span> <span m=''1697690''>probability</span> <span m=''1698180''>of</span>
  <span m=''1698630''>falling</span> <span m=''1699120''>outside</span> <span m=''1699580''>your</span>
  <span m=''1699720''>decision</span> <span m=''1700180''>region.</span> <span m=''1702050''>And</span>
  <span m=''1702210''>since</span> <span m=''1702390''>the</span> <span m=''1702600''>decision</span>
  <span m=''1702740''>region</span> <span m=''1703220''>always</span> <span m=''1703580''>has</span>
  <span m=''1703650''>the</span> <span m=''1703785''>same</span> <span m=''1703920''>shape,</span>
  <span m=''1705260''>it''s</span> <span m=''1706380''>invariant</span> <span m=''1706685''>to</span>
  <span m=''1706990''>which</span> <span m=''1707230''>point</span> <span m=''1707500''>you</span>
  <span m=''1707610''>send.</span> </p><p><span m=''1708410''>So</span> <span m=''1708730''>this</span>
  <span m=''1709220''>geometrical</span> <span m=''1709970''>uniformity</span> <span
  m=''1710730''>property,</span> <span m=''1713830''>which</span> <span m=''1714820''>that''s</span>
  <span m=''1715460''>the</span> <span m=''1715580''>general</span> <span m=''1716010''>name</span>
  <span m=''1716280''>for</span> <span m=''1716760''>it</span> <span m=''1717055''>and</span>
  <span m=''1717202''>it</span> <span m=''1717350''>has</span> <span m=''1717426''>all</span>
  <span m=''1717503''>these</span> <span m=''1717580''>specific</span> <span m=''1718200''>consequences</span>
  <span m=''1718665''>that</span> <span m=''1719130''>I</span> <span m=''1719320''>just</span>
  <span m=''1719590''>listed,</span> <span m=''1720670''>is</span> <span m=''1721080''>the</span>
  <span m=''1723060''>principal</span> <span m=''1725780''>geometrical</span> <span
  m=''1726490''>property</span> <span m=''1727050''>of</span> <span m=''1727140''>a</span>
  <span m=''1727240''>lattice.</span> <span m=''1729140''>This</span> <span m=''1729590''>just</span>
  <span m=''1729790''>follows</span> <span m=''1730200''>from</span> <span m=''1730410''>its</span>
  <span m=''1731040''>group</span> <span m=''1731290''>property.</span> <span m=''1734170''>You</span>
  <span m=''1734340''>don''t</span> <span m=''1734530''>have</span> <span m=''1734700''>to</span>
  <span m=''1734880''>be</span> <span m=''1735050''>a</span> <span m=''1735215''>lattice</span>
  <span m=''1735590''>to</span> <span m=''1735700''>have</span> <span m=''1735890''>this</span>
  <span m=''1736120''>property.</span> <span m=''1737680''>For</span> <span m=''1738050''>instance,</span>
  <span m=''1738800''>the</span> <span m=''1738960''>translate</span> <span m=''1739255''>of</span>
  <span m=''1739402''>a</span> <span m=''1739550''>lattice</span> <span m=''1740080''>is</span>
  <span m=''1740230''>not</span> <span m=''1740470''>a</span> <span m=''1740510''>group,</span>
  <span m=''1741350''>technically,</span> <span m=''1742350''>but</span> <span m=''1742590''>it</span>
  <span m=''1742730''>obviously</span> <span m=''1743230''>has</span> <span m=''1743450''>the</span>
  <span m=''1743550''>same</span> <span m=''1743840''>geometrical</span> <span m=''1744700''>uniformity</span>
  <span m=''1745330''>property.</span> <span m=''1746360''>And</span> <span m=''1746440''>there</span>
  <span m=''1746530''>are</span> <span m=''1746620''>more</span> <span m=''1747130''>elaborate</span>
  <span m=''1747580''>examples</span> <span m=''1748190''>of</span> <span m=''1748320''>things</span>
  <span m=''1748750''>that</span> <span m=''1749590''>look</span> <span m=''1749850''>less</span>
  <span m=''1750160''>like</span> <span m=''1750410''>lattices</span> <span m=''1750990''>that</span>
  <span m=''1751110''>are</span> <span m=''1751190''>nonetheless</span> <span m=''1751730''>geometrically</span>
  <span m=''1752230''>uniform.</span> <span m=''1752740''>On</span> <span m=''1752830''>the</span>
  <span m=''1752940''>other</span> <span m=''1753060''>hand,</span> <span m=''1753260''>lattices</span>
  <span m=''1753810''>definitely</span> <span m=''1754200''>are</span> <span m=''1754350''>geometrically</span>
  <span m=''1754990''>uniform.</span> </p><p><span m=''1756130''>So</span> <span m=''1756370''>this</span>
  <span m=''1756470''>seems</span> <span m=''1756720''>to</span> <span m=''1756820''>be</span>
  <span m=''1756930''>a</span> <span m=''1756980''>good</span> <span m=''1757210''>thing</span>
  <span m=''1757410''>to</span> <span m=''1757530''>do,</span> <span m=''1758050''>because</span>
  <span m=''1758400''>what''s</span> <span m=''1758640''>our</span> <span m=''1758770''>objective?</span>
  <span m=''1759290''>We''re</span> <span m=''1759430''>trying</span> <span m=''1759790''>to</span>
  <span m=''1760350''>have</span> <span m=''1760860''>d_min-squared</span> <span m=''1762000''>be</span>
  <span m=''1762140''>the</span> <span m=''1762260''>same</span> <span m=''1762730''>for</span>
  <span m=''1762900''>every</span> <span m=''1763140''>point</span> <span m=''1763430''>in</span>
  <span m=''1763530''>our</span> <span m=''1763680''>constellation.</span> <span m=''1766990''>We</span>
  <span m=''1767450''>want</span> <span m=''1767700''>to</span> <span m=''1767960''>tack</span>
  <span m=''1768265''>these</span> <span m=''1768570''>pennies</span> <span m=''1769030''>as</span>
  <span m=''1769170''>close</span> <span m=''1769470''>together</span> <span m=''1769850''>as</span>
  <span m=''1769960''>we</span> <span m=''1770070''>can.</span> <span m=''1770420''>That</span>
  <span m=''1770550''>means</span> <span m=''1770750''>we</span> <span m=''1770840''>want</span>
  <span m=''1771040''>to</span> <span m=''1771080''>hold</span> <span m=''1771320''>d_min-squared</span>
  <span m=''1772090''>constant</span> <span m=''1772690''>for</span> <span m=''1772860''>every</span>
  <span m=''1774430''>point</span> <span m=''1774690''>that</span> <span m=''1774740''>we''re</span>
  <span m=''1774790''>going</span> <span m=''1774910''>to</span> <span m=''1774950''>use.</span>
  <span m=''1776080''>And</span> <span m=''1776550''>so</span> <span m=''1776740''>lattices</span>
  <span m=''1777390''>have</span> <span m=''1777630''>that</span> <span m=''1777870''>property.</span>
  <span m=''1779650''>So</span> <span m=''1779920''>that</span> <span m=''1780860''>seems</span>
  <span m=''1781090''>like</span> <span m=''1781270''>a</span> <span m=''1781310''>good</span>
  <span m=''1781520''>way</span> <span m=''1781740''>to</span> <span m=''1781850''>do</span>
  <span m=''1781980''>sphere-packing.</span> </p><p><span m=''1783430''>And</span>
  <span m=''1783680''>in</span> <span m=''1783820''>fact,</span> <span m=''1785280''>sphere-packing,</span>
  <span m=''1786410''>in</span> <span m=''1786820''>n-dimensions,</span> <span m=''1787740''>is</span>
  <span m=''1787980''>a</span> <span m=''1788060''>very</span> <span m=''1788370''>old</span>
  <span m=''1788800''>mathematical</span> <span m=''1789580''>subject.</span> <span
  m=''1793130''>How</span> <span m=''1793260''>many</span> <span m=''1793440''>spheres</span>
  <span m=''1794320''>can</span> <span m=''1794470''>you</span> <span m=''1794590''>pack</span>
  <span m=''1794950''>around</span> <span m=''1795160''>a</span> <span m=''1795370''>three</span>
  <span m=''1795650''>sphere,</span> <span m=''1795935''>is</span> <span m=''1796220''>it</span>
  <span m=''1796320''>12</span> <span m=''1796720''>or</span> <span m=''1796800''>13?</span>
  <span m=''1797835''>That</span> <span m=''1798160''>was</span> <span m=''1798680''>debated</span>
  <span m=''1799350''>in</span> <span m=''1799460''>the</span> <span m=''1799610''>18th</span>
  <span m=''1800110''>and</span> <span m=''1800230''>19th</span> <span m=''1800700''>centuries,</span>
  <span m=''1801270''>and</span> <span m=''1801350''>I</span> <span m=''1801400''>think</span>
  <span m=''1801610''>it''s</span> <span m=''1801810''>only</span> <span m=''1802080''>finally</span>
  <span m=''1802490''>just</span> <span m=''1802730''>been</span> <span m=''1802860''>resolved</span>
  <span m=''1803370''>a</span> <span m=''1803420''>few</span> <span m=''1803650''>years</span>
  <span m=''1803960''>ago.</span> <span m=''1804910''>This</span> <span m=''1805990''>turns</span>
  <span m=''1806350''>out</span> <span m=''1807170''>to</span> <span m=''1807210''>be</span>
  <span m=''1807310''>not</span> <span m=''1807520''>an</span> <span m=''1807620''>easy</span>
  <span m=''1808040''>problem.</span> <span m=''1809780''>The</span> <span m=''1809890''>densest</span>
  <span m=''1810550''>sphere-packing</span> <span m=''1811400''>in</span> <span m=''1811490''>four</span>
  <span m=''1811760''>dimensions</span> <span m=''1812360''>was</span> <span m=''1812550''>found</span>
  <span m=''1812840''>in</span> <span m=''1812920''>the</span> <span m=''1813000''>mid-19th</span>
  <span m=''1813860''>century.</span> <span m=''1815230''>In</span> <span m=''1815590''>eight</span>
  <span m=''1815790''>dimensions,</span> <span m=''1816390''>I</span> <span m=''1816540''>think</span>
  <span m=''1816700''>around</span> <span m=''1816880''>the</span> <span m=''1817060''>turn</span>
  <span m=''1817330''>of</span> <span m=''1817410''>the</span> <span m=''1817500''>20th</span>
  <span m=''1817880''>century.</span> <span m=''1819080''>In</span> <span m=''1819600''>16</span>
  <span m=''1820380''>dimensions,</span> <span m=''1821010''>it''s</span> <span m=''1821200''>the</span>
  <span m=''1821290''>Barnes-Wall</span> <span m=''1822000''>lattice,</span> <span
  m=''1822420''>which</span> <span m=''1822620''>we''ll</span> <span m=''1822720''>see</span>
  <span m=''1822852''>a</span> <span m=''1822985''>little</span> <span m=''1823250''>later,</span>
  <span m=''1823410''>which</span> <span m=''1823630''>was</span> <span m=''1823840''>found</span>
  <span m=''1824180''>in</span> <span m=''1824660''>''54,</span> <span m=''1825530''>about</span>
  <span m=''1825635''>the</span> <span m=''1825740''>same</span> <span m=''1825970''>time</span>
  <span m=''1826260''>as</span> <span m=''1826430''>Reed-Muller</span> <span m=''1826960''>codes,</span>
  <span m=''1828010''>or</span> <span m=''1828090''>maybe</span> <span m=''1828360''>it</span>
  <span m=''1828430''>was</span> <span m=''1828500''>''59,</span> <span m=''1829620''>maybe</span>
  <span m=''1829760''>a</span> <span m=''1829790''>little</span> <span m=''1830000''>later</span>
  <span m=''1830280''>than</span> <span m=''1830390''>Reed-Muller</span> <span m=''1830870''>codes.</span>
  </p><p><span m=''1833150''>The</span> <span m=''1834870''>Leech</span> <span m=''1835180''>lattice</span>
  <span m=''1835770''>was</span> <span m=''1835950''>certainly</span> <span m=''1836290''>found</span>
  <span m=''1837040''>a</span> <span m=''1837380''>little</span> <span m=''1837600''>earlier</span>
  <span m=''1837950''>than</span> <span m=''1838100''>that,</span> <span m=''1838460''>but</span>
  <span m=''1839080''>around</span> <span m=''1839250''>the</span> <span m=''1839430''>same</span>
  <span m=''1839740''>time</span> <span m=''1840150''>as</span> <span m=''1840370''>the</span>
  <span m=''1840450''>Golay</span> <span m=''1840980''>code,</span> <span m=''1841190''>to</span>
  <span m=''1841400''>which</span> <span m=''1841630''>it''s</span> <span m=''1841770''>a</span>
  <span m=''1841910''>very</span> <span m=''1842120''>close</span> <span m=''1842450''>cousin.</span>
  <span m=''1843320''>And</span> <span m=''1843450''>so</span> <span m=''1843640''>forth.</span>
  <span m=''1843920''>So</span> <span m=''1844980''>you</span> <span m=''1845210''>might</span>
  <span m=''1845460''>think</span> <span m=''1845720''>that</span> <span m=''1846210''>these</span>
  <span m=''1846430''>questions</span> <span m=''1846880''>had</span> <span m=''1846975''>all</span>
  <span m=''1847070''>been</span> <span m=''1847220''>settled,</span> <span m=''1847710''>but</span>
  <span m=''1847760''>in</span> <span m=''1847810''>fact</span> <span m=''1848200''>they''re</span>
  <span m=''1848330''>still</span> <span m=''1848640''>open</span> <span m=''1849030''>for</span>
  <span m=''1849190''>most</span> <span m=''1849440''>specific</span> <span m=''1850010''>dimensions,</span>
  <span m=''1850600''>n.</span> <span m=''1853300''>Conway</span> <span m=''1853680''>and</span>
  <span m=''1853800''>Sloane</span> <span m=''1854430''>have</span> <span m=''1854590''>the</span>
  <span m=''1855210''>authoritative</span> <span m=''1855930''>book</span> <span m=''1856220''>on</span>
  <span m=''1856400''>this,</span> <span m=''1856680''>which</span> <span m=''1856930''>basically</span>
  <span m=''1857350''>lists</span> <span m=''1858120''>what</span> <span m=''1858340''>we</span>
  <span m=''1858480''>know</span> <span m=''1858730''>about</span> <span m=''1859000''>the</span>
  <span m=''1859080''>densest</span> <span m=''1859690''>sphere-packings</span> <span
  m=''1860430''>in</span> <span m=''1860580''>all</span> <span m=''1860790''>dimensions.</span>
  </p><p><span m=''1862600''>So</span> <span m=''1865240''>here''s</span> <span m=''1865490''>our</span>
  <span m=''1865660''>idea.</span> <span m=''1866930''>Our</span> <span m=''1867140''>idea</span>
  <span m=''1867720''>is</span> <span m=''1867860''>we''re</span> <span m=''1868010''>going</span>
  <span m=''1868140''>to</span> <span m=''1868370''>go</span> <span m=''1868950''>consult</span>
  <span m=''1869510''>the</span> <span m=''1869590''>mathematicians</span> <span m=''1870430''>and</span>
  <span m=''1870520''>find</span> <span m=''1870830''>out</span> <span m=''1870970''>what</span>
  <span m=''1871170''>the</span> <span m=''1871260''>densest</span> <span m=''1872000''>sphere-packings</span>
  <span m=''1872790''>that</span> <span m=''1873010''>they</span> <span m=''1873160''>found</span>
  <span m=''1873560''>are</span> <span m=''1873780''>in</span> <span m=''1873850''>various</span>
  <span m=''1874240''>dimensions.</span> <span m=''1875280''>In</span> <span m=''1875420''>two</span>
  <span m=''1875590''>dimensions,</span> <span m=''1876160''>it''s</span> <span m=''1876320''>the</span>
  <span m=''1876380''>hexagonal</span> <span m=''1877010''>lattice.</span> <span m=''1877910''>In</span>
  <span m=''1878010''>one</span> <span m=''1878210''>dimension,</span> <span m=''1878740''>it''s</span>
  <span m=''1878810''>the</span> <span m=''1878880''>integer,</span> <span m=''1879800''>and</span>
  <span m=''1879920''>basically</span> <span m=''1880995''>the</span> <span m=''1881300''>integers</span>
  <span m=''1881870''>are</span> <span m=''1881910''>the</span> <span m=''1882200''>only</span>
  <span m=''1883100''>packing</span> <span m=''1883590''>with</span> <span m=''1883740''>regularity</span>
  <span m=''1884350''>properties</span> <span m=''1884625''>in</span> <span m=''1884900''>one</span>
  <span m=''1885130''>dimension.</span> <span m=''1885690''>And</span> <span m=''1885840''>two</span>
  <span m=''1886100''>dimensions,</span> <span m=''1886690''>you</span> <span m=''1886840''>could</span>
  <span m=''1887020''>consider</span> <span m=''1888260''>Z-squared,</span> <span
  m=''1888770''>or</span> <span m=''1888910''>you</span> <span m=''1889060''>can</span>
  <span m=''1889380''>consider</span> <span m=''1890090''>A2.</span> <span m=''1891260''>These</span>
  <span m=''1891450''>are</span> <span m=''1891525''>the</span> <span m=''1891600''>two</span>
  <span m=''1891830''>obvious</span> <span m=''1892310''>candidates,</span> <span
  m=''1893060''>the</span> <span m=''1893150''>square</span> <span m=''1893600''>and</span>
  <span m=''1893660''>the</span> <span m=''1893720''>hexagonal</span> <span m=''1894390''>packings.</span>
  </p><p><span m=''1895560''>In</span> <span m=''1895670''>three</span> <span m=''1895910''>dimensions,</span>
  <span m=''1896640''>you</span> <span m=''1896790''>get</span> <span m=''1897160''>face-centered</span>
  <span m=''1897870''>cubic</span> <span m=''1898280''>packing.</span> <span m=''1898840''>And</span>
  <span m=''1899920''>what''s</span> <span m=''1900110''>the</span> <span m=''1900310''>BCC?</span>
  <span m=''1901110''>The</span> <span m=''1901210''>base-centered</span> <span m=''1902080''>cubic</span>
  <span m=''1902460''>packing,</span> <span m=''1902910''>I</span> <span m=''1902990''>guess.</span>
  </p><p><span m=''1903410''>AUDIENCE: Body-centered.</span> </p><p><span m=''1904930''>PROFESSOR:
  Say</span> <span m=''1905210''>again.</span> </p><p><span m=''1905490''>AUDIENCE:
  Body</span> <span m=''1905893''>center.</span> </p><p><span m=''1906700''>PROFESSOR:
  Body-centered,</span> <span m=''1907420''>thank</span> <span m=''1907690''>you.</span>
  <span m=''1908250''>I''m</span> <span m=''1908570''>sure</span> <span m=''1908670''>you''re</span>
  <span m=''1908870''>right.</span> <span m=''1910510''>So</span> <span m=''1910840''>anyway,</span>
  <span m=''1911120''>there''s</span> <span m=''1911330''>some</span> <span m=''1911480''>things</span>
  <span m=''1911820''>that</span> <span m=''1911885''>are</span> <span m=''1911950''>known</span>
  <span m=''1912160''>about</span> <span m=''1912440''>this</span> <span m=''1912690''>from</span>
  <span m=''1914570''>classical</span> <span m=''1915060''>mathematics</span> <span
  m=''1915940''>and</span> <span m=''1916290''>current</span> <span m=''1916600''>mathematics.</span>
  <span m=''1919250''>So</span> <span m=''1920340''>our</span> <span m=''1920600''>idea</span>
  <span m=''1921040''>is</span> <span m=''1921350''>we''re</span> <span m=''1921470''>going</span>
  <span m=''1921580''>to</span> <span m=''1921670''>try</span> <span m=''1921890''>to</span>
  <span m=''1921970''>find</span> <span m=''1922310''>the</span> <span m=''1922410''>densest</span>
  <span m=''1922950''>possible</span> <span m=''1924190''>lattice</span> <span m=''1925190''>in</span>
  <span m=''1926750''>n</span> <span m=''1926980''>dimensions.</span> <span m=''1928930''>But</span>
  <span m=''1929430''>for</span> <span m=''1930270''>digital</span> <span m=''1930630''>communications,</span>
  <span m=''1931690''>for</span> <span m=''1931980''>coding,</span> <span m=''1932840''>we</span>
  <span m=''1932970''>only</span> <span m=''1933180''>want</span> <span m=''1933370''>a</span>
  <span m=''1933420''>finite</span> <span m=''1933860''>number</span> <span m=''1934110''>of</span>
  <span m=''1934180''>points</span> <span m=''1934610''>from</span> <span m=''1934750''>that</span>
  <span m=''1936480''>constellation.</span> <span m=''1938970''>So</span> <span m=''1939405''>what</span>
  <span m=''1939550''>we''re</span> <span m=''1939695''>going</span> <span m=''1939840''>to</span>
  <span m=''1939900''>do</span> <span m=''1940100''>is</span> <span m=''1940270''>we''re</span>
  <span m=''1940420''>going</span> <span m=''1940560''>to</span> <span m=''1941620''>create</span>
  <span m=''1942040''>our</span> <span m=''1942240''>constellation</span> <span m=''1944280''>based</span>
  <span m=''1944680''>on</span> <span m=''1944840''>a</span> <span m=''1944930''>lattice</span>
  <span m=''1946270''>and</span> <span m=''1946560''>on</span> <span m=''1947040''>a</span>
  <span m=''1947210''>region</span> <span m=''1947550''>of</span> <span m=''1948310''>n-space.</span>
  <span m=''1950130''>And</span> <span m=''1950580''>the</span> <span m=''1950720''>idea</span>
  <span m=''1951230''>is</span> <span m=''1951400''>simple.</span> <span m=''1951860''>We''re</span>
  <span m=''1951960''>just</span> <span m=''1952240''>going</span> <span m=''1952400''>to</span>
  <span m=''1952560''>intersect</span> <span m=''1953380''>the</span> <span m=''1953490''>lattice.</span>
  <span m=''1955060''>Or</span> <span m=''1955220''>maybe</span> <span m=''1955525''>let</span>
  <span m=''1955830''>me</span> <span m=''1956000''>allow</span> <span m=''1956310''>a</span>
  <span m=''1956410''>translate</span> <span m=''1956740''>of</span> <span m=''1957070''>a</span>
  <span m=''1957360''>lattice</span> <span m=''1960570''>with</span> <span m=''1960710''>the</span>
  <span m=''1960850''>region.</span> </p><p><span m=''1963510''>And</span> <span m=''1964360''>make</span>
  <span m=''1964690''>this</span> <span m=''1965110''>a</span> <span m=''1965580''>finite,</span>
  <span m=''1966330''>compact</span> <span m=''1966950''>region.</span> <span m=''1968580''>And</span>
  <span m=''1968910''>this</span> <span m=''1969110''>will</span> <span m=''1969220''>give</span>
  <span m=''1969470''>us</span> <span m=''1970000''>a</span> <span m=''1970800''>certain</span>
  <span m=''1971510''>finite</span> <span m=''1972110''>subset</span> <span m=''1972580''>of</span>
  <span m=''1972660''>the</span> <span m=''1972750''>points</span> <span m=''1973130''>in</span>
  <span m=''1973210''>the</span> <span m=''1973300''>lattice.</span> <span m=''1976620''>Now,</span>
  <span m=''1976710''>when</span> <span m=''1976850''>I</span> <span m=''1976930''>draw</span>
  <span m=''1977260''>a</span> <span m=''1977320''>constellation</span> <span m=''1978090''>like</span>
  <span m=''1978340''>this</span> <span m=''1978590''>one,</span> <span m=''1978980''>of</span>
  <span m=''1981900''>a</span> <span m=''1981980''>size</span> <span m=''1982360''>16,</span>
  <span m=''1982930''>that''s</span> <span m=''1983110''>what</span> <span m=''1983230''>I''ve</span>
  <span m=''1983310''>done.</span> <span m=''1983620''>I''ve</span> <span m=''1983690''>basically</span>
  <span m=''1984290''>taken</span> <span m=''1984680''>A2.</span> <span m=''1985540''>Or</span>
  <span m=''1985870''>it''s</span> <span m=''1986120''>actually</span> <span m=''1986470''>a</span>
  <span m=''1986530''>translate</span> <span m=''1986825''>of</span> <span m=''1987120''>A2.</span>
  <span m=''1987740''>I</span> <span m=''1988015''>think</span> <span m=''1988290''>the</span>
  <span m=''1988490''>origin</span> <span m=''1988910''>is</span> <span m=''1989060''>in</span>
  <span m=''1989170''>here</span> <span m=''1989440''>somewhere.</span> <span m=''1990800''>And</span>
  <span m=''1991150''>I</span> <span m=''1991230''>draw</span> <span m=''1991600''>a</span>
  <span m=''1991660''>sphere</span> <span m=''1992240''>around</span> <span m=''1992500''>the</span>
  <span m=''1992650''>origin.</span> <span m=''1994870''>And</span> <span m=''1995120''>I</span>
  <span m=''1995220''>take</span> <span m=''1995710''>the</span> <span m=''1995830''>16</span>
  <span m=''1996400''>points</span> <span m=''1996840''>that</span> <span m=''1996950''>happen</span>
  <span m=''1997240''>to</span> <span m=''1997330''>fall</span> <span m=''1997630''>within</span>
  <span m=''1997890''>that</span> <span m=''1998110''>sphere.</span> <span m=''1998560''>And</span>
  <span m=''1998660''>I</span> <span m=''1998710''>call</span> <span m=''1999010''>that</span>
  <span m=''1999200''>my</span> <span m=''1999320''>constellation.</span> </p><p><span
  m=''2001470''>So</span> <span m=''2001610''>that''s</span> <span m=''2001850''>the</span>
  <span m=''2002000''>idea</span> <span m=''2002300''>in</span> <span m=''2002410''>general.</span>
  <span m=''2003430''>Think</span> <span m=''2003550''>of</span> <span m=''2004120''>the</span>
  <span m=''2004220''>region,</span> <span m=''2004620''>r,</span> <span m=''2004940''>as</span>
  <span m=''2005060''>a</span> <span m=''2005130''>cookie</span> <span m=''2005480''>cutter.</span>
  <span m=''2007050''>We''re</span> <span m=''2007250''>going</span> <span m=''2007390''>to</span>
  <span m=''2007800''>take</span> <span m=''2008020''>the</span> <span m=''2008130''>cookie</span>
  <span m=''2008450''>cutter</span> <span m=''2008820''>and</span> <span m=''2008980''>chop</span>
  <span m=''2009290''>out</span> <span m=''2010070''>a</span> <span m=''2010150''>finite</span>
  <span m=''2010610''>number</span> <span m=''2010960''>of</span> <span m=''2011350''>points</span>
  <span m=''2011860''>from</span> <span m=''2012170''>this</span> <span m=''2013410''>nice,</span>
  <span m=''2013780''>regular,</span> <span m=''2014360''>infinite</span> <span m=''2014840''>grid.</span>
  <span m=''2015900''>And</span> <span m=''2016140''>that</span> <span m=''2016340''>will</span>
  <span m=''2016620''>give</span> <span m=''2016790''>us</span> <span m=''2016930''>a</span>
  <span m=''2017000''>constellation.</span> <span m=''2018930''>So</span> <span m=''2019910''>especially</span>
  <span m=''2020290''>for</span> <span m=''2020460''>large</span> <span m=''2020830''>constellations,</span>
  <span m=''2021610''>we''ll</span> <span m=''2021730''>be</span> <span m=''2021910''>able</span>
  <span m=''2022060''>to</span> <span m=''2022110''>make</span> <span m=''2022330''>some</span>
  <span m=''2022490''>approximations</span> <span m=''2024020''>that</span> <span
  m=''2024140''>will</span> <span m=''2024250''>allow</span> <span m=''2024630''>us</span>
  <span m=''2024850''>to</span> <span m=''2024980''>analyze</span> <span m=''2025950''>that</span>
  <span m=''2026260''>kind</span> <span m=''2026380''>of</span> <span m=''2026500''>constellation</span>
  <span m=''2027230''>very</span> <span m=''2027750''>easily.</span> </p><p><span
  m=''2028660''>And</span> <span m=''2029910''>actually,</span> <span m=''2030360''>the</span>
  <span m=''2030480''>best</span> <span m=''2030820''>constellations</span> <span
  m=''2031195''>that</span> <span m=''2031570''>we</span> <span m=''2031730''>know</span>
  <span m=''2032060''>are</span> <span m=''2032140''>of</span> <span m=''2032260''>this</span>
  <span m=''2032380''>type.</span> <span m=''2035610''>We''ve</span> <span m=''2036000''>taken</span>
  <span m=''2036330''>this</span> <span m=''2036490''>baseline,</span> <span m=''2037300''>m-PAM.</span>
  <span m=''2038810''>Well,</span> <span m=''2039100''>what''s</span> <span m=''2039380''>m-PAM?</span>
  <span m=''2040340''>We</span> <span m=''2040470''>take</span> <span m=''2043030''>the</span>
  <span m=''2043260''>lattice</span> <span m=''2043980''>plus</span> <span m=''2044490''>t,</span>
  <span m=''2045500''>let''s</span> <span m=''2045760''>say</span> <span m=''2046040''>to</span>
  <span m=''2046240''>be</span> <span m=''2047580''>Z</span> <span m=''2048080''>plus</span>
  <span m=''2048570''>1/2.</span> <span m=''2052199''>So</span> <span m=''2052429''>that</span>
  <span m=''2052650''>means</span> <span m=''2053110''>we</span> <span m=''2054889''>don''t</span>
  <span m=''2055179''>take</span> <span m=''2055409''>the</span> <span m=''2055570''>origin,</span>
  <span m=''2055830''>but</span> <span m=''2056090''>we</span> <span m=''2056310''>take</span>
  <span m=''2056580''>the</span> <span m=''2056980''>points</span> <span m=''2057440''>1/2</span>
  <span m=''2058230''>minus</span> <span m=''2058679''>1/2,</span> <span m=''2060210''>3/2.</span>
  <span m=''2062199''>They''re</span> <span m=''2062440''>equally</span> <span m=''2062969''>spaced</span>
  <span m=''2063510''>points,</span> <span m=''2064570''>but</span> <span m=''2064889''>we''ve</span>
  <span m=''2065050''>shifted</span> <span m=''2065469''>them</span> <span m=''2065679''>so</span>
  <span m=''2065899''>as</span> <span m=''2066120''>to</span> <span m=''2066199''>be</span>
  <span m=''2066360''>symmetric</span> <span m=''2066949''>about</span> <span m=''2067280''>the</span>
  <span m=''2067440''>origin.</span> <span m=''2068790''>5/2</span> <span m=''2070000''>minus</span>
  <span m=''2070639''>minus,</span> <span m=''2071179''>so</span> <span m=''2071480''>forth.</span>
  <span m=''2072460''>So</span> <span m=''2072739''>this</span> <span m=''2073010''>is</span>
  <span m=''2073920''>Z</span> <span m=''2074540''>plus</span> <span m=''2074880''>1/2</span>
  <span m=''2075770''>is</span> <span m=''2075980''>our</span> <span m=''2076120''>lattice.</span>
  <span m=''2077230''>And</span> <span m=''2077389''>then</span> <span m=''2077530''>if</span>
  <span m=''2077659''>we</span> <span m=''2077739''>want</span> <span m=''2078050''>4-PAM,</span>
  <span m=''2079580''>we</span> <span m=''2079739''>take</span> <span m=''2080020''>a</span>
  <span m=''2080120''>cookie</span> <span m=''2080489''>cutter</span> <span m=''2081219''>consisting</span>
  <span m=''2081880''>of</span> <span m=''2082100''>this</span> <span m=''2082300''>region.</span>
  </p><p><span m=''2084070''>So</span> <span m=''2084290''>this</span> <span m=''2084480''>is</span>
  <span m=''2084580''>the</span> <span m=''2084670''>region</span> <span m=''2085070''>going</span>
  <span m=''2085340''>from</span> <span m=''2085530''>minus</span> <span m=''2085949''>2</span>
  <span m=''2086290''>to</span> <span m=''2086489''>2.</span> <span m=''2088900''>It''s</span>
  <span m=''2089050''>not</span> <span m=''2089260''>unreasonable</span> <span m=''2089850''>to</span>
  <span m=''2089960''>expect</span> <span m=''2090240''>that,</span> <span m=''2090520''>if</span>
  <span m=''2090679''>we</span> <span m=''2090810''>take</span> <span m=''2091130''>a</span>
  <span m=''2091219''>region</span> <span m=''2092150''>of</span> <span m=''2092300''>length</span>
  <span m=''2092620''>4,</span> <span m=''2092919''>we''re</span> <span m=''2093219''>going</span>
  <span m=''2093340''>to</span> <span m=''2093389''>get</span> <span m=''2093580''>4</span>
  <span m=''2093810''>points,</span> <span m=''2096190''>if,</span> <span m=''2096670''>again,</span>
  <span m=''2097070''>it''s</span> <span m=''2097290''>symmetric</span> <span m=''2097800''>around</span>
  <span m=''2098150''>the</span> <span m=''2098620''>corner,</span> <span m=''2098950''>because</span>
  <span m=''2099570''>each</span> <span m=''2099820''>of</span> <span m=''2099940''>these</span>
  <span m=''2100070''>points</span> <span m=''2100470''>takes</span> <span m=''2100770''>up</span>
  <span m=''2100900''>about</span> <span m=''2101160''>one</span> <span m=''2101340''>unit</span>
  <span m=''2101470''>of</span> <span m=''2101700''>space</span> <span m=''2102150''>over</span>
  <span m=''2102390''>here.</span> <span m=''2103800''>So</span> <span m=''2104300''>if</span>
  <span m=''2104475''>we</span> <span m=''2104650''>made</span> <span m=''2104880''>it</span>
  <span m=''2105020''>from</span> <span m=''2105210''>minus</span> <span m=''2106100''>4</span>
  <span m=''2106400''>to</span> <span m=''2106930''>plus</span> <span m=''2107320''>4,</span>
  <span m=''2107750''>we''d</span> <span m=''2107880''>have</span> <span m=''2108200''>a</span>
  <span m=''2108280''>region</span> <span m=''2108650''>of</span> <span m=''2108750''>length</span>
  <span m=''2108970''>8,</span> <span m=''2109340''>and</span> <span m=''2109430''>we''d</span>
  <span m=''2109520''>get</span> <span m=''2109690''>8</span> <span m=''2109820''>points.</span>
  <span m=''2110950''>And</span> <span m=''2111280''>so</span> <span m=''2111490''>forth.</span>
  <span m=''2113510''>So</span> <span m=''2113720''>that''s</span> <span m=''2113990''>how</span>
  <span m=''2114130''>we</span> <span m=''2114280''>do</span> <span m=''2115830''>m-PAM,</span>
  <span m=''2116750''>and</span> <span m=''2116930''>then</span> <span m=''2117110''>scale</span>
  <span m=''2117580''>it</span> <span m=''2119140''>if</span> <span m=''2119250''>we</span>
  <span m=''2119340''>want</span> <span m=''2119670''>to.</span> <span m=''2120000''>But</span>
  <span m=''2120170''>this</span> <span m=''2120390''>is</span> <span m=''2120560''>the</span>
  <span m=''2120630''>basic</span> <span m=''2121070''>idea.</span> </p><p><span m=''2121610''>Similarly,</span>
  <span m=''2122260''>for</span> <span m=''2123440''>m by m</span> <span m=''2124430''>QAM,</span>
  <span m=''2126850''>like</span> <span m=''2127160''>everything</span> <span m=''2127610''>else,</span>
  <span m=''2127930''>it''s</span> <span m=''2128040''>just</span> <span m=''2128360''>doing</span>
  <span m=''2128640''>the</span> <span m=''2128720''>same</span> <span m=''2129010''>thing</span>
  <span m=''2129410''>independently</span> <span m=''2130120''>in</span> <span m=''2130230''>two</span>
  <span m=''2130420''>dimensions.</span> <span m=''2131890''>Here</span> <span m=''2132280''>we</span>
  <span m=''2132480''>take</span> <span m=''2133660''>our</span> <span m=''2133860''>lattice</span>
  <span m=''2134510''>to</span> <span m=''2134680''>be</span> <span m=''2136480''>Z</span>
  <span m=''2136780''>plus</span> <span m=''2137160''>1/2</span> <span m=''2137700''>squared,</span>
  <span m=''2139340''>which</span> <span m=''2139590''>is</span> <span m=''2139780''>just</span>
  <span m=''2140110''>the</span> <span m=''2141030''>offset</span> <span m=''2142450''>Z-squared,</span>
  <span m=''2143420''>offset</span> <span m=''2144050''>so</span> <span m=''2144310''>as</span>
  <span m=''2144500''>to</span> <span m=''2144580''>be</span> <span m=''2144780''>four-way,</span>
  <span m=''2147120''>to</span> <span m=''2147200''>be</span> <span m=''2147320''>roughly</span>
  <span m=''2148890''>symmetrical</span> <span m=''2149235''>to</span> <span m=''2149580''>four-way</span>
  <span m=''2150200''>rotations,</span> <span m=''2151030''>90-degree</span> <span
  m=''2151610''>rotations.</span> </p><p><span m=''2153620''>So</span> <span m=''2153940''>here</span>
  <span m=''2154310''>is</span> <span m=''2154740''>Z-squared</span> <span m=''2155250''>plus</span>
  <span m=''2156060''>(1/2, 1/2).</span> <span m=''2159690''>And</span> <span m=''2159830''>then,</span>
  <span m=''2160310''>again,</span> <span m=''2162250''>here</span> <span m=''2163030''>to</span>
  <span m=''2163170''>get</span> <span m=''2164300''>16-QAM,</span> <span m=''2164970''>for</span>
  <span m=''2165150''>instance,</span> <span m=''2165500''>we</span> <span m=''2165630''>might</span>
  <span m=''2165930''>take</span> <span m=''2166770''>the</span> <span m=''2166880''>region</span>
  <span m=''2167550''>to</span> <span m=''2167730''>be</span> <span m=''2171040''>what?</span>
  <span m=''2172860''>(-2,2)-squared</span> <span m=''2177170''>which,</span> <span
  m=''2177570''>again,</span> <span m=''2177870''>has</span> <span m=''2178160''>area</span>
  <span m=''2178490''>16.</span> <span m=''2180280''>You</span> <span m=''2180400''>might</span>
  <span m=''2180610''>think</span> <span m=''2180820''>of</span> <span m=''2180930''>this</span>
  <span m=''2181230''>as</span> <span m=''2181360''>just</span> <span m=''2181610''>taking</span>
  <span m=''2182510''>the</span> <span m=''2182580''>little</span> <span m=''2182820''>square</span>
  <span m=''2183370''>around</span> <span m=''2183650''>each</span> <span m=''2183870''>of</span>
  <span m=''2183950''>these.</span> <span m=''2184890''>Each</span> <span m=''2185100''>of</span>
  <span m=''2185280''>these</span> <span m=''2185470''>squares</span> <span m=''2186180''>has</span>
  <span m=''2186450''>area</span> <span m=''2186800''>1.</span> <span m=''2187746''>So</span>
  <span m=''2189570''>when</span> <span m=''2190030''>we</span> <span m=''2190240''>take</span>
  <span m=''2190800''>the</span> <span m=''2190880''>union</span> <span m=''2191220''>of</span>
  <span m=''2191310''>all</span> <span m=''2191530''>those</span> <span m=''2191710''>squares,</span>
  <span m=''2192330''>we</span> <span m=''2192450''>get</span> <span m=''2192660''>the</span>
  <span m=''2192750''>region.</span> </p><p><span m=''2193160''>That''s</span> <span
  m=''2193410''>another</span> <span m=''2193680''>way</span> <span m=''2193890''>of</span>
  <span m=''2194020''>characterizing</span> <span m=''2194800''>this</span> <span
  m=''2195000''>region.</span> <span m=''2195480''>It''s</span> <span m=''2195860''>just</span>
  <span m=''2196630''>the</span> <span m=''2196820''>union</span> <span m=''2197220''>of</span>
  <span m=''2197340''>all</span> <span m=''2197570''>the</span> <span m=''2197660''>decision</span>
  <span m=''2198120''>regions</span> <span m=''2198415''>of</span> <span m=''2198710''>the</span>
  <span m=''2199130''>points</span> <span m=''2199530''>that</span> <span m=''2199650''>we</span>
  <span m=''2199780''>want.</span> <span m=''2200210''>If</span> <span m=''2200360''>you</span>
  <span m=''2200440''>had</span> <span m=''2200520''>started</span> <span m=''2200940''>from</span>
  <span m=''2201030''>the</span> <span m=''2201130''>points,</span> <span m=''2202090''>you</span>
  <span m=''2202210''>could</span> <span m=''2202350''>certainly</span> <span m=''2203020''>invent</span>
  <span m=''2203370''>a</span> <span m=''2203440''>region</span> <span m=''2204310''>that</span>
  <span m=''2204570''>is</span> <span m=''2204730''>the</span> <span m=''2204830''>union</span>
  <span m=''2205160''>of</span> <span m=''2205200''>those</span> <span m=''2205450''>decision</span>
  <span m=''2205910''>regions.</span> <span m=''2206430''>It</span> <span m=''2206500''>would</span>
  <span m=''2206770''>have</span> <span m=''2209460''>an</span> <span m=''2209600''>area</span>
  <span m=''2210040''>equal</span> <span m=''2210540''>to</span> <span m=''2211100''>the</span>
  <span m=''2211200''>number</span> <span m=''2211440''>of</span> <span m=''2211510''>points</span>
  <span m=''2212040''>times</span> <span m=''2212520''>the</span> <span m=''2212640''>volume</span>
  <span m=''2212925''>of</span> <span m=''2213920''>2-space</span> <span m=''2214570''>per</span>
  <span m=''2214780''>each</span> <span m=''2215010''>point.</span> </p><p><span m=''2217290''>That''s</span>
  <span m=''2217570''>the</span> <span m=''2217660''>kind</span> <span m=''2217940''>of</span>
  <span m=''2218530''>approximation</span> <span m=''2219380''>we''re</span> <span
  m=''2219480''>going</span> <span m=''2219620''>to</span> <span m=''2219660''>use.</span>
  <span m=''2220800''>The</span> <span m=''2220970''>bounding</span> <span m=''2221420''>region</span>
  <span m=''2221960''>is</span> <span m=''2222360''>clearly</span> <span m=''2222700''>going</span>
  <span m=''2222850''>to</span> <span m=''2222930''>have</span> <span m=''2224380''>something</span>
  <span m=''2224900''>like</span> <span m=''2225270''>the</span> <span m=''2225420''>number</span>
  <span m=''2225640''>of</span> <span m=''2225700''>points</span> <span m=''2226050''>in</span>
  <span m=''2226105''>the</span> <span m=''2226160''>constellation,</span> <span m=''2227020''>times</span>
  <span m=''2227730''>the</span> <span m=''2228240''>fundamental</span> <span m=''2229170''>volume</span>
  <span m=''2229740''>as</span> <span m=''2229940''>its</span> <span m=''2230100''>volume.</span>
  <span m=''2236720''>So</span> <span m=''2237110''>this</span> <span m=''2237330''>is</span>
  <span m=''2237480''>our</span> <span m=''2237650''>idea.</span> <span m=''2238610''>This</span>
  <span m=''2238880''>is</span> <span m=''2239010''>what</span> <span m=''2239170''>we''re</span>
  <span m=''2239270''>going</span> <span m=''2239410''>to</span> <span m=''2239500''>call</span>
  <span m=''2239900''>a</span> <span m=''2240000''>lattice</span> <span m=''2240500''>constellation.</span>
  <span m=''2242660''>And</span> <span m=''2242965''>we''re</span> <span m=''2243066''>going</span>
  <span m=''2243168''>to</span> <span m=''2244020''>investigate</span> <span m=''2244680''>the</span>
  <span m=''2244780''>properties</span> <span m=''2245400''>of</span> <span m=''2245520''>lattice</span>
  <span m=''2245940''>constellations,</span> <span m=''2248080''>not</span> <span
  m=''2248370''>the</span> <span m=''2248430''>most</span> <span m=''2248720''>general</span>
  <span m=''2249060''>thing</span> <span m=''2249270''>we</span> <span m=''2249420''>could</span>
  <span m=''2249600''>think</span> <span m=''2249860''>of</span> <span m=''2250090''>but</span>
  <span m=''2250520''>good</span> <span m=''2250770''>enough.</span> </p><p><span
  m=''2253270''>Seem</span> <span m=''2253440''>to</span> <span m=''2253550''>have</span>
  <span m=''2253850''>the</span> <span m=''2253940''>right</span> <span m=''2254240''>sort</span>
  <span m=''2254500''>of</span> <span m=''2254630''>property.</span> <span m=''2258490''>And</span>
  <span m=''2259170''>we''re</span> <span m=''2259350''>going</span> <span m=''2259470''>to</span>
  <span m=''2259600''>take</span> <span m=''2259860''>it</span> <span m=''2259930''>at</span>
  <span m=''2260000''>least</span> <span m=''2260320''>as</span> <span m=''2260470''>far</span>
  <span m=''2260760''>as</span> <span m=''2260910''>the</span> <span m=''2261250''>union-bound</span>
  <span m=''2261670''>estimate,</span> <span m=''2262200''>so</span> <span m=''2262310''>we</span>
  <span m=''2262400''>can</span> <span m=''2262510''>get</span> <span m=''2262620''>a</span>
  <span m=''2262650''>good</span> <span m=''2264560''>estimate</span> <span m=''2264970''>of</span>
  <span m=''2265090''>probability</span> <span m=''2265680''>of</span> <span m=''2265770''>error</span>
  <span m=''2266180''>if</span> <span m=''2266470''>we</span> <span m=''2267330''>take</span>
  <span m=''2267620''>one</span> <span m=''2267760''>of</span> <span m=''2267880''>these</span>
  <span m=''2268010''>constellations,</span> <span m=''2268890''>like</span> <span
  m=''2269120''>m-by-m</span> <span m=''2269680''>QAM,</span> <span m=''2270300''>and</span>
  <span m=''2270420''>use</span> <span m=''2270710''>it</span> <span m=''2270900''>to</span>
  <span m=''2271060''>transmit</span> <span m=''2271660''>over</span> <span m=''2271980''>a</span>
  <span m=''2274230''>Gaussian</span> <span m=''2274610''>noise</span> <span m=''2274950''>channel.</span>
  <span m=''2276690''>And</span> <span m=''2276870''>furthermore,</span> <span m=''2277880''>for</span>
  <span m=''2278990''>large</span> <span m=''2279450''>constellations,</span> <span
  m=''2283160''>meaning</span> <span m=''2283490''>as</span> <span m=''2283640''>we</span>
  <span m=''2283760''>get</span> <span m=''2284120''>well</span> <span m=''2284400''>up</span>
  <span m=''2284640''>into</span> <span m=''2285100''>the</span> <span m=''2285310''>bandwidth-limited</span>
  <span m=''2286130''>regions</span> <span m=''2286460''>of</span> <span m=''2286790''>large</span>
  <span m=''2287460''>nominal</span> <span m=''2287830''>spectral</span> <span m=''2288320''>densities,</span>
  <span m=''2289910''>we''re</span> <span m=''2290020''>going</span> <span m=''2290140''>to</span>
  <span m=''2290550''>be</span> <span m=''2290730''>able</span> <span m=''2290960''>to</span>
  <span m=''2291130''>separate</span> <span m=''2291820''>the</span> <span m=''2291950''>analysis</span>
  <span m=''2296800''>into</span> <span m=''2297340''>lattice</span> <span m=''2297800''>properties</span>
  <span m=''2298700''>and</span> <span m=''2298880''>region</span> <span m=''2299270''>properties.</span>
  <span m=''2303955''>And</span> <span m=''2304240''>we''ll</span> <span m=''2304400''>basically</span>
  <span m=''2304860''>be</span> <span m=''2305050''>able</span> <span m=''2305135''>to</span>
  <span m=''2305220''>just</span> <span m=''2305520''>add</span> <span m=''2305800''>these</span>
  <span m=''2306090''>up</span> <span m=''2307730''>to</span> <span m=''2308260''>get</span>
  <span m=''2308450''>the</span> <span m=''2308600''>overall</span> <span m=''2308970''>analysis,</span>
  <span m=''2314140''>by</span> <span m=''2314490''>making</span> <span m=''2314890''>some</span>
  <span m=''2316500''>judicious</span> <span m=''2317080''>approximations</span> <span
  m=''2317980''>that</span> <span m=''2318180''>become</span> <span m=''2318920''>exact</span>
  <span m=''2319460''>in</span> <span m=''2319550''>the</span> <span m=''2319640''>large</span>
  <span m=''2319960''>constellation</span> <span m=''2320710''>limit.</span> </p><p><span
  m=''2324180''>So</span> <span m=''2324330''>let''s</span> <span m=''2325550''>now</span>
  <span m=''2326970''>restrict</span> <span m=''2327420''>ourselves</span> <span m=''2328010''>to</span>
  <span m=''2329130''>lattices,</span> <span m=''2330690''>or</span> <span m=''2330970''>translates</span>
  <span m=''2331640''>of</span> <span m=''2331750''>lattices,</span> <span m=''2333320''>and</span>
  <span m=''2335210''>start</span> <span m=''2335970''>to</span> <span m=''2336040''>analyze</span>
  <span m=''2336670''>them.</span> <span m=''2336840''>What</span> <span m=''2337020''>are</span>
  <span m=''2337180''>their</span> <span m=''2337490''>key</span> <span m=''2337770''>parameters</span>
  <span m=''2345020''>for</span> <span m=''2345600''>our</span> <span m=''2345840''>application,</span>
  <span m=''2346520''>which</span> <span m=''2346790''>is</span> <span m=''2347630''>digital</span>
  <span m=''2347990''>communications?</span> <span m=''2349770''>Well,</span> <span
  m=''2350310''>one</span> <span m=''2350610''>is</span> <span m=''2350960''>the</span>
  <span m=''2351470''>minimum</span> <span m=''2351820''>squared</span> <span m=''2352230''>distance</span>
  <span m=''2352730''>between</span> <span m=''2353090''>lattice</span> <span m=''2353510''>points.</span>
  <span m=''2355050''>We''ve</span> <span m=''2355260''>seen</span> <span m=''2355520''>that</span>
  <span m=''2355730''>doesn''t</span> <span m=''2356050''>depend</span> <span m=''2356490''>on</span>
  <span m=''2356680''>the</span> <span m=''2356880''>particular</span> <span m=''2357400''>point.</span>
  <span m=''2359060''>So</span> <span m=''2359450''>this</span> <span m=''2359790''>is</span>
  <span m=''2360030''>the</span> <span m=''2360140''>minimum</span> <span m=''2360200''>squared</span>
  <span m=''2360530''>distance</span> <span m=''2360940''>from</span> <span m=''2361040''>any</span>
  <span m=''2361350''>lattice</span> <span m=''2361760''>point.</span> <span m=''2364130''>The</span>
  <span m=''2364370''>number</span> <span m=''2364770''>of</span> <span m=''2364940''>nearest</span>
  <span m=''2365370''>neighbors.</span> <span m=''2371320''>The</span> <span m=''2374080''>volume</span>
  <span m=''2377750''>per</span> <span m=''2377950''>lattice</span> <span m=''2378360''>point.</span>
  <span m=''2382130''>And</span> <span m=''2384175''>is</span> <span m=''2384540''>there</span>
  <span m=''2384640''>anything</span> <span m=''2384880''>else?</span> <span m=''2390020''>It</span>
  <span m=''2390163''>seems</span> <span m=''2390306''>to</span> <span m=''2390450''>me</span>
  <span m=''2390655''>there''s</span> <span m=''2390860''>a</span> <span m=''2390920''>fourth</span>
  <span m=''2391310''>one.</span> <span m=''2402360''>No.</span> <span m=''2404010''>I</span>
  <span m=''2404460''>guess that''s</span> <span m=''2404710''>all</span> <span m=''2404770''>we</span>
  <span m=''2404830''>need</span> <span m=''2405060''>to</span> <span m=''2405170''>know.</span>
  </p><p><span m=''2411370''>So</span> <span m=''2412190''>I</span> <span m=''2412320''>want</span>
  <span m=''2412520''>to</span> <span m=''2412580''>combine</span> <span m=''2413030''>these</span>
  <span m=''2413330''>into</span> <span m=''2413900''>a</span> <span m=''2414380''>key</span>
  <span m=''2414790''>figure</span> <span m=''2415290''>of</span> <span m=''2415360''>merit</span>
  <span m=''2415870''>for</span> <span m=''2416030''>coding.</span> <span m=''2417600''>Again,</span>
  <span m=''2417770''>we</span> <span m=''2417880''>did</span> <span m=''2418070''>this</span>
  <span m=''2418310''>back</span> <span m=''2418660''>in</span> <span m=''2427410''>chapter</span>
  <span m=''2427810''>four</span> <span m=''2428220''>for</span> <span m=''2428970''>a</span>
  <span m=''2429060''>complete</span> <span m=''2429510''>constellation.</span> <span
  m=''2430320''>We</span> <span m=''2430460''>found</span> <span m=''2430770''>the</span>
  <span m=''2430900''>figure</span> <span m=''2431280''>of</span> <span m=''2431340''>merit</span>
  <span m=''2431830''>by</span> <span m=''2433010''>holding</span> <span m=''2433420''>the</span>
  <span m=''2433580''>average</span> <span m=''2433950''>power</span> <span m=''2434340''>fixed</span>
  <span m=''2435380''>for</span> <span m=''2435880''>a</span> <span m=''2436020''>fixed</span>
  <span m=''2436410''>number</span> <span m=''2436790''>of</span> <span m=''2437280''>points,</span>
  <span m=''2437740''>m,</span> <span m=''2438130''>on</span> <span m=''2438250''>a</span>
  <span m=''2438310''>fixed</span> <span m=''2438620''>dimension,</span> <span m=''2439150''>n,</span>
  <span m=''2440000''>and</span> <span m=''2440820''>maximizing</span> <span m=''2441600''>the</span>
  <span m=''2441790''>minimum</span> <span m=''2441990''>square</span> <span m=''2442250''>distance,</span>
  <span m=''2442780''>or,</span> <span m=''2443460''>conversely,</span> <span m=''2444240''>holding</span>
  <span m=''2444550''>the</span> <span m=''2444660''>minimum</span> <span m=''2444970''>squared</span>
  <span m=''2445320''>distance</span> <span m=''2445740''>fixed</span> <span m=''2446160''>and</span>
  <span m=''2446420''>minimizing</span> <span m=''2447010''>the</span> <span m=''2447130''>average</span>
  <span m=''2447460''>power.</span> <span m=''2448270''>So</span> <span m=''2448480''>we</span>
  <span m=''2448590''>get</span> <span m=''2448840''>some</span> <span m=''2449870''>figure</span>
  <span m=''2450190''>of</span> <span m=''2450270''>merit</span> <span m=''2450670''>that</span>
  <span m=''2450760''>was</span> <span m=''2451230''>kind</span> <span m=''2451430''>of</span>
  <span m=''2451510''>normalized,</span> <span m=''2452440''>and</span> <span m=''2452620''>we</span>
  <span m=''2452890''>could</span> <span m=''2453020''>just</span> <span m=''2453150''>optimize</span>
  <span m=''2453710''>that</span> <span m=''2453850''>one</span> <span m=''2454050''>thing.</span>
  </p><p><span m=''2455050''>The</span> <span m=''2455160''>key</span> <span m=''2455390''>figure</span>
  <span m=''2455740''>of</span> <span m=''2455820''>merit</span> <span m=''2457410''>was</span>
  <span m=''2457710''>called</span> <span m=''2458070''>by</span> <span m=''2459220''>19th-century</span>
  <span m=''2461900''>mathematician,</span> <span m=''2462760''>Hermite''s</span>
  <span m=''2463290''>parameter,</span> <span m=''2466892''>but</span> <span m=''2467390''>we</span>
  <span m=''2467900''>are</span> <span m=''2468030''>going</span> <span m=''2468210''>to</span>
  <span m=''2468300''>call</span> <span m=''2468680''>it</span> <span m=''2469430''>the</span>
  <span m=''2469890''>nominal</span> <span m=''2470400''>coding</span> <span m=''2470780''>gain</span>
  <span m=''2472110''>because</span> <span m=''2472500''>that''s</span> <span m=''2472720''>what</span>
  <span m=''2473020''>it''s</span> <span m=''2473070''>going</span> <span m=''2473120''>to</span>
  <span m=''2473200''>turn</span> <span m=''2473490''>out</span> <span m=''2473730''>to</span>
  <span m=''2473820''>be.</span> <span m=''2477570''>And</span> <span m=''2477840''>it''s</span>
  <span m=''2478440''>just</span> <span m=''2478670''>defined</span> <span m=''2479110''>as</span>
  <span m=''2479270''>follows.</span> <span m=''2480455''>The</span> <span m=''2480920''>nominal</span>
  <span m=''2481430''>coding</span> <span m=''2481790''>gain</span> <span m=''2482200''>of</span>
  <span m=''2482250''>a</span> <span m=''2482300''>lattice</span> <span m=''2483030''>is</span>
  <span m=''2483300''>just</span> <span m=''2484560''>this</span> <span m=''2485010''>minimum</span>
  <span m=''2485360''>squared</span> <span m=''2485850''>distance,</span> <span m=''2486160''>so</span>
  <span m=''2486470''>it</span> <span m=''2487610''>goes</span> <span m=''2487930''>up</span>
  <span m=''2488180''>as</span> <span m=''2488530''>the</span> <span m=''2488610''>minimum</span>
  <span m=''2488900''>squared</span> <span m=''2489310''>distance.</span> <span m=''2490470''>But</span>
  <span m=''2490640''>then</span> <span m=''2490800''>we</span> <span m=''2490970''>want</span>
  <span m=''2491230''>to</span> <span m=''2491480''>normalize</span> <span m=''2492260''>this.</span>
  <span m=''2492840''>And</span> <span m=''2493070''>the</span> <span m=''2493190''>obvious</span>
  <span m=''2493600''>thing</span> <span m=''2493780''>to</span> <span m=''2493910''>normalize</span>
  <span m=''2494510''>it</span> <span m=''2494670''>by,</span> <span m=''2495530''>we</span>
  <span m=''2495680''>want</span> <span m=''2495960''>something</span> <span m=''2496380''>that''s</span>
  <span m=''2496620''>going</span> <span m=''2496720''>to</span> <span m=''2496830''>scale</span>
  <span m=''2498650''>as</span> <span m=''2498940''>a</span> <span m=''2499070''>two-dimensional</span>
  <span m=''2499750''>quantity.</span> <span m=''2501275''>If</span> <span m=''2501620''>the</span>
  <span m=''2501770''>lattice</span> <span m=''2501920''>was</span> <span m=''2502210''>scaled</span>
  <span m=''2502570''>by</span> <span m=''2502770''>alpha,</span> <span m=''2504040''>then</span>
  <span m=''2504410''>this</span> <span m=''2504580''>would</span> <span m=''2504650''>go</span>
  <span m=''2504870''>up</span> <span m=''2504970''>as</span> <span m=''2505140''>alpha</span>
  <span m=''2505420''>squared.</span> <span m=''2506550''>So</span> <span m=''2506780''>we</span>
  <span m=''2506920''>want</span> <span m=''2507230''>something</span> <span m=''2507540''>that''ll</span>
  <span m=''2507730''>scale</span> <span m=''2508170''>in</span> <span m=''2508225''>the</span>
  <span m=''2508280''>same</span> <span m=''2508610''>way.</span> </p><p><span m=''2509670''>And</span>
  <span m=''2509830''>what</span> <span m=''2510000''>we</span> <span m=''2510160''>choose</span>
  <span m=''2511020''>to</span> <span m=''2511140''>normalize</span> <span m=''2511690''>it</span>
  <span m=''2511850''>by</span> <span m=''2512200''>is</span> <span m=''2512530''>the</span>
  <span m=''2512610''>volume</span> <span m=''2513800''>of</span> <span m=''2513970''>lambda</span>
  <span m=''2514420''>per</span> <span m=''2516630''>two</span> <span m=''2516800''>dimensions,</span>
  <span m=''2517360''>if</span> <span m=''2517470''>you</span> <span m=''2517620''>like.</span>
  <span m=''2519530''>So</span> <span m=''2519950''>you</span> <span m=''2520170''>can</span>
  <span m=''2520300''>see</span> <span m=''2520490''>immediately,</span> <span m=''2520950''>this</span>
  <span m=''2521160''>is</span> <span m=''2521380''>invariant</span> <span m=''2521930''>to</span>
  <span m=''2522020''>scaling,</span> <span m=''2522405''>that</span> <span m=''2522790''>the</span>
  <span m=''2524240''>nominal</span> <span m=''2524620''>coding</span> <span m=''2524940''>gain</span>
  <span m=''2525360''>of</span> <span m=''2525550''>lambda</span> <span m=''2525920''>is</span>
  <span m=''2526100''>the</span> <span m=''2526190''>same</span> <span m=''2526510''>as</span>
  <span m=''2526670''>the</span> <span m=''2526740''>nominal</span> <span m=''2527070''>coding</span>
  <span m=''2527340''>gain</span> <span m=''2527560''>of</span> <span m=''2527690''>alpha</span>
  <span m=''2528040''>lambda.</span> <span m=''2530610''>Is</span> <span m=''2530780''>alpha</span>
  <span m=''2531060''>lambda</span> <span m=''2531670''>a</span> <span m=''2531800''>lattice,</span>
  <span m=''2532290''>by</span> <span m=''2532430''>the</span> <span m=''2532580''>way?</span>
  <span m=''2533890''>If</span> <span m=''2534110''>lambda''s</span> <span m=''2534570''>a</span>
  <span m=''2534630''>group,</span> <span m=''2535040''>and</span> <span m=''2535140''>we</span>
  <span m=''2535290''>have</span> <span m=''2535450''>any</span> <span m=''2536190''>scale</span>
  <span m=''2536540''>factor</span> <span m=''2537030''>alpha</span> <span m=''2537360''>greater</span>
  <span m=''2537600''>than</span> <span m=''2537720''>0,</span> <span m=''2538690''>then</span>
  <span m=''2538840''>alpha</span> <span m=''2539190''>times</span> <span m=''2539520''>lambda</span>
  <span m=''2540750''>is</span> <span m=''2540930''>also</span> <span m=''2541290''>a</span>
  <span m=''2541340''>group.</span> <span m=''2542550''>Everything''s</span> <span
  m=''2542830''>just</span> <span m=''2543110''>multiplied</span> <span m=''2543530''>by</span>
  <span m=''2543720''>alpha.</span> <span m=''2544350''>So</span> <span m=''2544810''>alpha</span>
  <span m=''2545150''>lambda</span> <span m=''2545520''>is</span> <span m=''2545690''>a</span>
  <span m=''2545760''>lattice.</span> </p><p><span m=''2546990''>And</span> <span
  m=''2547950''>this</span> <span m=''2548170''>is</span> <span m=''2548210''>actually</span>
  <span m=''2548500''>one</span> <span m=''2548620''>of</span> <span m=''2548670''>the</span>
  <span m=''2548740''>homework</span> <span m=''2549150''>problems.</span> <span m=''2549620''>If</span>
  <span m=''2549730''>you</span> <span m=''2549840''>scale</span> <span m=''2550240''>everything</span>
  <span m=''2550600''>by</span> <span m=''2550780''>alpha,</span> <span m=''2551840''>d_min-squared</span>
  <span m=''2552610''>goes</span> <span m=''2552840''>up</span> <span m=''2553010''>by</span>
  <span m=''2553170''>alpha</span> <span m=''2553530''>squared.</span> <span m=''2554530''>The</span>
  <span m=''2554630''>volume</span> <span m=''2555050''>goes</span> <span m=''2555320''>up</span>
  <span m=''2555510''>by</span> <span m=''2555630''>alpha</span> <span m=''2556000''>to</span>
  <span m=''2556080''>the</span> <span m=''2556250''>n,</span> <span m=''2556690''>for</span>
  <span m=''2556870''>an</span> <span m=''2556970''>n-dimensional</span> <span m=''2557570''>lattice.</span>
  <span m=''2558690''>But</span> <span m=''2558970''>when</span> <span m=''2559180''>we</span>
  <span m=''2559330''>take</span> <span m=''2559680''>2 over n,</span> <span m=''2560350''>we''re</span>
  <span m=''2560480''>going</span> <span m=''2560560''>to</span> <span m=''2560620''>get</span>
  <span m=''2560800''>back</span> <span m=''2561030''>to</span> <span m=''2561120''>alpha</span>
  <span m=''2561450''>squared.</span> <span m=''2562360''>So</span> <span m=''2563670''>alpha</span>
  <span m=''2565180''>c</span> <span m=''2565450''>of</span> <span m=''2565570''>lambda</span>
  <span m=''2566340''>is</span> <span m=''2566650''>alpha</span> <span m=''2566910''>c</span>
  <span m=''2567170''>of</span> <span m=''2567300''>alpha</span> <span m=''2567610''>lambda.</span>
  <span m=''2568890''>So</span> <span m=''2570650''>this</span> <span m=''2570750''>is</span>
  <span m=''2570860''>what</span> <span m=''2571020''>you</span> <span m=''2571180''>want.</span>
  <span m=''2571570''>You</span> <span m=''2571720''>want</span> <span m=''2571840''>a</span>
  <span m=''2571960''>kind</span> <span m=''2572170''>of</span> <span m=''2572250''>scale-free</span>
  <span m=''2573600''>version</span> <span m=''2573960''>of</span> <span m=''2574030''>a</span>
  <span m=''2574100''>lattice,</span> <span m=''2574550''>because,</span> <span m=''2575270''>obviously,</span>
  <span m=''2575670''>when</span> <span m=''2575800''>we</span> <span m=''2575930''>use</span>
  <span m=''2576230''>this,</span> <span m=''2576480''>we''re</span> <span m=''2576610''>going</span>
  <span m=''2576720''>to</span> <span m=''2576810''>feel</span> <span m=''2577060''>free</span>
  <span m=''2577300''>to</span> <span m=''2577370''>amplify</span> <span m=''2578050''>it</span>
  <span m=''2578160''>or</span> <span m=''2578710''>compress</span> <span m=''2579090''>it</span>
  <span m=''2579470''>any</span> <span m=''2579630''>way</span> <span m=''2579690''>we</span>
  <span m=''2579750''>want,</span> <span m=''2580170''>so</span> <span m=''2580410''>we</span>
  <span m=''2580590''>do</span> <span m=''2580750''>with</span> <span m=''2580910''>QAM.</span>
  </p><p><span m=''2582880''>All</span> <span m=''2582970''>right,</span> <span m=''2583240''>so</span>
  <span m=''2583400''>this</span> <span m=''2583600''>is</span> <span m=''2583760''>normalized</span>
  <span m=''2584580''>in</span> <span m=''2584770''>that</span> <span m=''2585040''>way.</span>
  <span m=''2587230''>We</span> <span m=''2587470''>prove</span> <span m=''2587910''>in</span>
  <span m=''2587955''>the</span> <span m=''2588000''>homework</span> <span m=''2588500''>it''s</span>
  <span m=''2588690''>also</span> <span m=''2589590''>invariant</span> <span m=''2589760''>to</span>
  <span m=''2590200''>other</span> <span m=''2590440''>things.</span> <span m=''2590830''>If</span>
  <span m=''2590940''>you</span> <span m=''2591660''>took,</span> <span m=''2593430''>say,</span>
  <span m=''2593770''>an</span> <span m=''2593890''>orthogonal</span> <span m=''2594580''>transformation</span>
  <span m=''2595370''>of</span> <span m=''2595510''>this</span> <span m=''2595650''>lattice,</span>
  <span m=''2596430''>a</span> <span m=''2596500''>rotation,</span> <span m=''2597870''>reflection,</span>
  <span m=''2599430''>multiply</span> <span m=''2599980''>it</span> <span m=''2600130''>by</span>
  <span m=''2600390''>a</span> <span m=''2600650''>matrix</span> <span m=''2604640''>that</span>
  <span m=''2604990''>doesn''t</span> <span m=''2605840''>change</span> <span m=''2606160''>the</span>
  <span m=''2606260''>scale,</span> <span m=''2608250''>think</span> <span m=''2608400''>of</span>
  <span m=''2608470''>it</span> <span m=''2608540''>geometrically</span> <span m=''2609170''>as</span>
  <span m=''2609320''>an</span> <span m=''2609380''>orthogonal</span> <span m=''2609930''>transformation,</span>
  <span m=''2611730''>is</span> <span m=''2611910''>that</span> <span m=''2612140''>going</span>
  <span m=''2612270''>to</span> <span m=''2612340''>be</span> <span m=''2612480''>a</span>
  <span m=''2612540''>lattice?</span> <span m=''2615560''>It</span> <span m=''2615690''>is</span>
  <span m=''2615860''>going</span> <span m=''2615970''>to</span> <span m=''2616010''>be</span>
  <span m=''2616110''>a</span> <span m=''2616180''>lattice.</span> <span m=''2617020''>Everything''s</span>
  <span m=''2617460''>just</span> <span m=''2617690''>going</span> <span m=''2617760''>to</span>
  <span m=''2619250''>have</span> <span m=''2619390''>some</span> <span m=''2620080''>h</span>
  <span m=''2620235''>out</span> <span m=''2620390''>here,</span> <span m=''2621060''>times</span>
  <span m=''2621460''>G times Z-squared,</span> <span m=''2622555''>and</span> <span
  m=''2622820''>that''s</span> <span m=''2623090''>still</span> <span m=''2623940''>of</span>
  <span m=''2624080''>the</span> <span m=''2624180''>form</span> <span m=''2624470''>of</span>
  <span m=''2624500''>a</span> <span m=''2624530''>lattice.</span> <span m=''2626830''>Or</span>
  <span m=''2627510''>call</span> <span m=''2627623''>it</span> <span m=''2627736''>U</span>
  <span m=''2627850''>for</span> <span m=''2628130''>orthogonal,</span> <span m=''2629230''>unitary.</span>
  </p><p><span m=''2632650''>So</span> <span m=''2633060''>we</span> <span m=''2633170''>multiply</span>
  <span m=''2633280''>it</span> <span m=''2633460''>by</span> <span m=''2633740''>some</span>
  <span m=''2634070''>orthogonal</span> <span m=''2634580''>matrix,</span> <span m=''2635060''>U.</span>
  <span m=''2635900''>It''s</span> <span m=''2636090''>still</span> <span m=''2636350''>a</span>
  <span m=''2636450''>lattice.</span> <span m=''2637980''>If</span> <span m=''2638030''>we</span>
  <span m=''2638130''>look</span> <span m=''2638350''>in</span> <span m=''2638470''>here,</span>
  <span m=''2639140''>orthogonal</span> <span m=''2639620''>transformations</span>
  <span m=''2640470''>don''t</span> <span m=''2640750''>change</span> <span m=''2641080''>squared</span>
  <span m=''2641410''>distances.</span> <span m=''2645270''>We''re</span> <span m=''2645330''>not</span>
  <span m=''2645510''>going</span> <span m=''2645600''>to</span> <span m=''2645700''>change
  this --</span> <span m=''2645980''>it</span> <span m=''2646300''>doesn''t</span>
  <span m=''2646540''>matter.</span> <span m=''2649260''>Actually,</span> <span m=''2652810''>I</span>
  <span m=''2652870''>might.</span> <span m=''2656430''>No.</span> <span m=''2657100''>It''s</span>
  <span m=''2657320''>a</span> <span m=''2657380''>rigid</span> <span m=''2657820''>rotation,</span>
  <span m=''2658470''>I''m</span> <span m=''2658580''>sorry.</span> <span m=''2659090''>Everything</span>
  <span m=''2659440''>here</span> <span m=''2659630''>stays</span> <span m=''2659990''>the</span>
  <span m=''2660070''>same.</span> <span m=''2660740''>Hexagonal</span> <span m=''2661320''>lattice</span>
  <span m=''2661530''>still</span> <span m=''2661825''>is</span> <span m=''2662120''>hexagonal</span>
  <span m=''2662790''>lattice,</span> <span m=''2663220''>because</span> <span m=''2663390''>it''s</span>
  <span m=''2663580''>a</span> <span m=''2664100''>rigid</span> <span m=''2664490''>rotation</span>
  <span m=''2665110''>or</span> <span m=''2665170''>reflection</span> <span m=''2666990''>geometrically.</span>
  <span m=''2668330''>And</span> <span m=''2668640''>the</span> <span m=''2668700''>volume</span>
  <span m=''2669270''>clearly</span> <span m=''2671140''>stays</span> <span m=''2671580''>the</span>
  <span m=''2671660''>same,</span> <span m=''2672020''>so</span> <span m=''2672220''>none</span>
  <span m=''2672420''>of</span> <span m=''2672490''>these</span> <span m=''2672750''>things</span>
  <span m=''2673040''>changes.</span> <span m=''2673670''>And</span> <span m=''2675390''>orthogonal</span>
  <span m=''2675860''>transformation</span> <span m=''2676640''>isn''t</span> <span
  m=''2676880''>going</span> <span m=''2677030''>to</span> <span m=''2677180''>change</span>
  <span m=''2677520''>this</span> <span m=''2677990''>quantity</span> <span m=''2678275''>either.</span>
  </p><p><span m=''2679400''>So</span> <span m=''2679610''>we</span> <span m=''2679750''>can</span>
  <span m=''2679880''>rotate</span> <span m=''2680460''>this</span> <span m=''2680960''>or</span>
  <span m=''2681435''>do</span> <span m=''2681720''>whatever.</span> <span m=''2683680''>And</span>
  <span m=''2684020''>then,</span> <span m=''2685110''>finally,</span> <span m=''2685490''>there''s</span>
  <span m=''2685660''>an</span> <span m=''2685750''>even</span> <span m=''2685930''>more</span>
  <span m=''2686190''>interesting</span> <span m=''2686710''>one,</span> <span m=''2686990''>which</span>
  <span m=''2687240''>is,</span> <span m=''2687670''>if</span> <span m=''2687960''>we</span>
  <span m=''2688110''>take</span> <span m=''2689550''>the</span> <span m=''2689620''>lattice,</span>
  <span m=''2690650''>lambda</span> <span m=''2691090''>to</span> <span m=''2691155''>the</span>
  <span m=''2691220''>m,</span> <span m=''2692630''>this</span> <span m=''2692860''>is</span>
  <span m=''2692980''>simply</span> <span m=''2693560''>the</span> <span m=''2693900''>Cartesian</span>
  <span m=''2694530''>product.</span> <span m=''2695110''>It''s</span> <span m=''2695280''>the</span>
  <span m=''2695370''>set</span> <span m=''2695750''>of</span> <span m=''2695840''>all</span>
  <span m=''2696650''>lambda_1,</span> <span m=''2697180''>lambda_2,</span> <span
  m=''2699250''>lambda_m,</span> <span m=''2701040''>such</span> <span m=''2701580''>that</span>
  <span m=''2702490''>each</span> <span m=''2702790''>of</span> <span m=''2703000''>these</span>
  <span m=''2703220''>lambda_k</span> <span m=''2704232''>is</span> <span m=''2704590''>in</span>
  <span m=''2704750''>Lambda.</span> <span m=''2706580''>So</span> <span m=''2706790''>it''s</span>
  <span m=''2706930''>the</span> <span m=''2707010''>set</span> <span m=''2707280''>of</span>
  <span m=''2707370''>all</span> <span m=''2707690''>n-tuples</span> <span m=''2708220''>of</span>
  <span m=''2708630''>elements</span> <span m=''2709090''>of</span> <span m=''2709200''>Lambda.</span>
  <span m=''2710460''>This</span> <span m=''2710800''>clearly</span> <span m=''2711320''>lives</span>
  <span m=''2711715''>in</span> <span m=''2712110''>dimension</span> <span m=''2714210''>mn,</span>
  <span m=''2715325''>so</span> <span m=''2715710''>it''s</span> <span m=''2715920''>a</span>
  <span m=''2715970''>much</span> <span m=''2716200''>higher-dimensional</span> <span
  m=''2717060''>lattice.</span> <span m=''2718770''>The</span> <span m=''2719060''>simplest</span>
  <span m=''2719520''>case</span> <span m=''2719940''>is</span> <span m=''2720360''>Z</span>
  <span m=''2720630''>to</span> <span m=''2720720''>the</span> <span m=''2720890''>m
  - it</span> <span m=''2721770''>lives</span> <span m=''2722110''>in</span> <span
  m=''2722220''>m</span> <span m=''2722430''>dimensions,</span> <span m=''2722745''>whereas</span>
  <span m=''2723300''>Z</span> <span m=''2723650''>is down</span> <span m=''2724190''>in</span>
  <span m=''2724280''>one</span> <span m=''2724480''>dimension.</span> </p><p><span
  m=''2727190''>So</span> <span m=''2727680''>it</span> <span m=''2727880''>lives</span>
  <span m=''2728075''>in</span> <span m=''2728270''>dimension</span> <span m=''2728760''>mn.</span>
  <span m=''2729230''>It''s</span> <span m=''2729440''>a</span> <span m=''2729500''>way</span>
  <span m=''2729700''>of</span> <span m=''2729830''>constructing</span> <span m=''2730380''>high-dimensional</span>
  <span m=''2731090''>lattices</span> <span m=''2731750''>from</span> <span m=''2731870''>low-dimensional</span>
  <span m=''2732395''>lattices.</span> <span m=''2734560''>It''s</span> <span m=''2735080''>something</span>
  <span m=''2735540''>that,</span> <span m=''2735680''>in</span> <span m=''2735800''>communications,</span>
  <span m=''2736650''>we</span> <span m=''2736800''>consider</span> <span m=''2737730''>to</span>
  <span m=''2737990''>be</span> <span m=''2738270''>almost</span> <span m=''2739350''>a</span>
  <span m=''2739400''>non-event.</span> <span m=''2741180''>Sending</span> <span m=''2741910''>a</span>
  <span m=''2742020''>sequence</span> <span m=''2743860''>of</span> <span m=''2744010''>elements</span>
  <span m=''2744500''>of</span> <span m=''2744620''>lambda</span> <span m=''2745960''>is</span>
  <span m=''2746180''>the</span> <span m=''2746260''>same</span> <span m=''2746570''>as</span>
  <span m=''2746940''>sending</span> <span m=''2746965''>a</span> <span m=''2746990''>sequence</span>
  <span m=''2747450''>of</span> <span m=''2747530''>elements</span> <span m=''2747940''>of</span>
  <span m=''2748040''>lambda_m.</span> <span m=''2751080''>In</span> <span m=''2751200''>fact,</span>
  <span m=''2751570''>if</span> <span m=''2751680''>we</span> <span m=''2751790''>just</span>
  <span m=''2753460''>send</span> <span m=''2753680''>a</span> <span m=''2753860''>sequence</span>
  <span m=''2754390''>of</span> <span m=''2754550''>things</span> <span m=''2754870''>from</span>
  <span m=''2755020''>here,</span> <span m=''2755340''>and</span> <span m=''2755390''>a</span>
  <span m=''2755440''>sequence</span> <span m=''2755860''>of</span> <span m=''2755960''>things</span>
  <span m=''2756240''>from</span> <span m=''2756370''>lambda,</span> <span m=''2756710''>there''s</span>
  <span m=''2756960''>no</span> <span m=''2757110''>difference</span> <span m=''2758360''>from</span>
  <span m=''2758505''>a</span> <span m=''2758650''>receiver''s</span> <span m=''2759230''>point</span>
  <span m=''2759470''>of</span> <span m=''2759720''>view.</span> <span m=''2760010''>So</span>
  <span m=''2760870''>we</span> <span m=''2761170''>regard</span> <span m=''2761690''>these</span>
  <span m=''2762870''>two</span> <span m=''2763060''>lattices</span> <span m=''2763660''>as</span>
  <span m=''2763810''>equivalent,</span> <span m=''2764370''>from</span> <span m=''2764530''>a</span>
  <span m=''2764630''>communications</span> <span m=''2765340''>point</span> <span
  m=''2765610''>of</span> <span m=''2765833''>view.</span> </p><p><span m=''2768190''>Well,</span>
  <span m=''2768640''>what</span> <span m=''2768820''>happens</span> <span m=''2769150''>to</span>
  <span m=''2769270''>d_min-squared?</span> <span m=''2770670''>d_min-squared</span>
  <span m=''2771270''>doesn''t</span> <span m=''2771600''>change,</span> <span m=''2772810''>because</span>
  <span m=''2773420''>we</span> <span m=''2773570''>can</span> <span m=''2773740''>always--</span>
  <span m=''2775140''>d_min-squared is,</span> <span m=''2776900''>by</span> <span
  m=''2777040''>the</span> <span m=''2777180''>way,</span> <span m=''2777420''>the</span>
  <span m=''2777560''>weight</span> <span m=''2778000''>of</span> <span m=''2778170''>the</span>
  <span m=''2778270''>smallest--</span> <span m=''2779335''>should</span> <span m=''2779527''>have</span>
  <span m=''2779720''>said</span> <span m=''2779990''>that.</span> <span m=''2784310''>You</span>
  <span m=''2784460''>can</span> <span m=''2784580''>always</span> <span m=''2784890''>do</span>
  <span m=''2785060''>things</span> <span m=''2785390''>relative</span> <span m=''2785660''>to</span>
  <span m=''2785930''>0.</span> <span m=''2787110''>d_min-squared,</span> <span m=''2787850''>therefore,</span>
  <span m=''2788390''>is</span> <span m=''2788650''>the</span> <span m=''2793050''>squared
  norm or lowest</span> <span m=''2793500''>squared</span> <span m=''2793910''>energy</span>
  <span m=''2794330''>of</span> <span m=''2794440''>any</span> <span m=''2794630''>non-zero</span>
  <span m=''2795210''>lattice</span> <span m=''2795590''>point,</span> <span m=''2796570''>same</span>
  <span m=''2796850''>as</span> <span m=''2796960''>we</span> <span m=''2797070''>did</span>
  <span m=''2797230''>with</span> <span m=''2797390''>Hamming</span> <span m=''2797730''>codes,</span>
  <span m=''2798620''>just</span> <span m=''2798820''>by</span> <span m=''2798950''>the</span>
  <span m=''2799060''>group</span> <span m=''2799330''>property.</span> <span m=''2800430''>K_min</span>
  <span m=''2801020''>is</span> <span m=''2801500''>the</span> <span m=''2801960''>number</span>
  <span m=''2802980''>of</span> <span m=''2803120''>such</span> <span m=''2803480''>lowest</span>
  <span m=''2804930''>Euclidean</span> <span m=''2805450''>weight</span> <span m=''2806400''>points.</span>
  </p><p><span m=''2808340''>OK,</span> <span m=''2808520''>here,</span> <span m=''2808810''>what''s</span>
  <span m=''2809000''>the</span> <span m=''2809190''>lowest</span> <span m=''2809630''>weight</span>
  <span m=''2810700''>point?</span> <span m=''2811320''>It</span> <span m=''2811440''>would</span>
  <span m=''2811600''>look</span> <span m=''2811770''>something</span> <span m=''2812070''>like</span>
  <span m=''2812310''>this,</span> <span m=''2813330''>where</span> <span m=''2813490''>this</span>
  <span m=''2813750''>is</span> <span m=''2813890''>one</span> <span m=''2814020''>of</span>
  <span m=''2814060''>the</span> <span m=''2814110''>lowest</span> <span m=''2814450''>weight</span>
  <span m=''2814680''>points</span> <span m=''2814980''>in</span> <span m=''2815060''>lambda.</span>
  <span m=''2815865''>So</span> <span m=''2816240''>d_min-squared</span> <span m=''2817360''>doesn''t</span>
  <span m=''2817700''>change.</span> <span m=''2820010''>This</span> <span m=''2821040''>changes,</span>
  <span m=''2821640''>but</span> <span m=''2822030''>we''re</span> <span m=''2822430''>not</span>
  <span m=''2822770''>considering</span> <span m=''2823290''>that.</span> <span m=''2824150''>The</span>
  <span m=''2824580''>volume,</span> <span m=''2825050''>what</span> <span m=''2825230''>is</span>
  <span m=''2825390''>the</span> <span m=''2825480''>volume?</span> <span m=''2825970''>It</span>
  <span m=''2826150''>turns</span> <span m=''2826330''>out</span> <span m=''2826600''>that</span>
  <span m=''2827506''>it''s</span> <span m=''2827960''>not</span> <span m=''2828050''>hard</span>
  <span m=''2828170''>to</span> <span m=''2828290''>show</span> <span m=''2828600''>that</span>
  <span m=''2828910''>V(lambda</span> <span m=''2829940''>to</span> <span m=''2830050''>the</span>
  <span m=''2830250''>m)</span> <span m=''2831502''>is</span> <span m=''2831910''>V(lambda)
  to the m.</span> <span m=''2833700''>And</span> <span m=''2834870''>therefore,</span>
  <span m=''2835340''>you</span> <span m=''2835490''>can</span> <span m=''2835650''>show</span>
  <span m=''2836010''>that</span> <span m=''2837520''>this</span> <span m=''2837930''>is</span>
  <span m=''2838490''>figure</span> <span m=''2838780''>of</span> <span m=''2838830''>merit</span>
  <span m=''2839150''>doesn''t</span> <span m=''2839450''>change,</span> <span m=''2840110''>even</span>
  <span m=''2840280''>if</span> <span m=''2840360''>you</span> <span m=''2840480''>take</span>
  <span m=''2840790''>Cartesian</span> <span m=''2841300''>products.</span> </p><p><span
  m=''2845490''>So</span> <span m=''2845800''>for</span> <span m=''2846010''>instance,</span>
  <span m=''2846790''>I</span> <span m=''2846960''>chose</span> <span m=''2847305''>that</span>
  <span m=''2848980''>the</span> <span m=''2849570''>nominal</span> <span m=''2850010''>coding</span>
  <span m=''2850370''>gain</span> <span m=''2850820''>of</span> <span m=''2851530''>to</span>
  <span m=''2851650''>the</span> <span m=''2851860''>m</span> <span m=''2852880''>is</span>
  <span m=''2853130''>equal</span> <span m=''2853540''>to</span> <span m=''2853800''>the</span>
  <span m=''2854020''>nominal</span> <span m=''2854460''>coding</span> <span m=''2854870''>gain</span>
  <span m=''2855240''>of</span> <span m=''2855770''>Z.</span> <span m=''2857700''>Which</span>
  <span m=''2857900''>is</span> <span m=''2858020''>what,</span> <span m=''2858270''>by</span>
  <span m=''2858380''>the</span> <span m=''2858490''>way?</span> <span m=''2858600''>I</span>
  <span m=''2858910''>should</span> <span m=''2859090''>have</span> <span m=''2859230''>done</span>
  <span m=''2859420''>this</span> <span m=''2859680''>as</span> <span m=''2859820''>the</span>
  <span m=''2859910''>first</span> <span m=''2860270''>example.</span> <span m=''2863490''>What''s</span>
  <span m=''2863720''>the</span> <span m=''2863940''>minimum</span> <span m=''2864130''>squared</span>
  <span m=''2864460''>distance</span> <span m=''2864765''>of</span> <span m=''2865070''>Z?</span>
  <span m=''2867230''>1.</span> <span m=''2868250''>What''s</span> <span m=''2868740''>the</span>
  <span m=''2868840''>volume</span> <span m=''2869230''>of</span> <span m=''2869430''>Z?</span>
  <span m=''2870530''>1.</span> <span m=''2871670''>So</span> <span m=''2872035''>this</span>
  <span m=''2872400''>is</span> <span m=''2872610''>1,</span> <span m=''2873926''>or</span>
  <span m=''2874400''>0 dB.</span> <span m=''2874870''>We''re</span> <span m=''2875290''>going</span>
  <span m=''2875430''>to</span> <span m=''2875610''>measure</span> <span m=''2875950''>nominal</span>
  <span m=''2876350''>coding</span> <span m=''2876750''>gain</span> <span m=''2877160''>in</span>
  <span m=''2877590''>dB,</span> <span m=''2879020''>which,</span> <span m=''2880586''>well,</span>
  <span m=''2881240''>we''re</span> <span m=''2881490''>getting</span> <span m=''2881790''>us</span>
  <span m=''2881950''>into</span> <span m=''2882170''>communications.</span> </p><p><span
  m=''2884410''>What''s</span> <span m=''2884950''>the</span> <span m=''2885660''>nominal</span>
  <span m=''2886150''>coding</span> <span m=''2886350''>gain</span> <span m=''2886570''>of</span>
  <span m=''2886840''>the</span> <span m=''2887050''>hexagonal</span> <span m=''2887670''>lattice?</span>
  <span m=''2890640''>By</span> <span m=''2890800''>asking</span> <span m=''2891170''>this</span>
  <span m=''2891360''>question,</span> <span m=''2891720''>I''m</span> <span m=''2891830''>basically</span>
  <span m=''2892320''>asking,</span> <span m=''2893580''>is</span> <span m=''2893970''>the</span>
  <span m=''2894420''>hexagonal</span> <span m=''2895030''>lattice</span> <span m=''2895490''>denser</span>
  <span m=''2896650''>than</span> <span m=''2897650''>Z-squared</span> <span m=''2898400''>in</span>
  <span m=''2898680''>two</span> <span m=''2898830''>dimensions</span> <span m=''2900150''>than</span>
  <span m=''2900230''>the</span> <span m=''2900310''>square</span> <span m=''2900660''>lattice</span>
  <span m=''2901100''>in</span> <span m=''2901210''>two</span> <span m=''2901360''>dimensions?</span>
  <span m=''2901920''>And</span> <span m=''2902620''>if</span> <span m=''2902830''>so,</span>
  <span m=''2903110''>quantitatively,</span> <span m=''2903910''>how</span> <span
  m=''2904050''>much</span> <span m=''2904300''>denser</span> <span m=''2904760''>is</span>
  <span m=''2904910''>it?</span> </p><p><span m=''2905872''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''2907800''>PROFESSOR: OK,</span> <span m=''2908310''>well,</span>
  <span m=''2910180''>there''s</span> <span m=''2910400''>a</span> <span m=''2910460''>root</span>
  <span m=''2910680''>3</span> <span m=''2910960''>in</span> <span m=''2911100''>it,</span>
  <span m=''2911310''>but</span> <span m=''2911480''>that</span> <span m=''2911600''>isn''t</span>
  <span m=''2912790''>exactly</span> <span m=''2913135''>the</span> <span m=''2913480''>answer,</span>
  <span m=''2913780''>I</span> <span m=''2913950''>don''t</span> <span m=''2914120''>think.</span>
  <span m=''2918780''>There</span> <span m=''2918890''>are</span> <span m=''2918910''>various</span>
  <span m=''2919340''>ways</span> <span m=''2919860''>that</span> <span m=''2920020''>you</span>
  <span m=''2920190''>can</span> <span m=''2921320''>do</span> <span m=''2921520''>it,</span>
  <span m=''2921680''>but</span> <span m=''2921780''>one</span> <span m=''2921960''>of</span>
  <span m=''2922030''>the</span> <span m=''2922110''>ways</span> <span m=''2922550''>is</span>
  <span m=''2922700''>to</span> <span m=''2922830''>take,</span> <span m=''2923140''>as</span>
  <span m=''2923240''>a</span> <span m=''2923350''>generator</span> <span m=''2923890''>matrix,</span>
  <span m=''2924520''>(1,</span> <span m=''2924950''>0;</span> <span m=''2926240''>1/2,</span>
  <span m=''2926910''>root</span> <span m=''2927040''>3</span> <span m=''2927650''>over</span>
  <span m=''2927890''>2).</span> <span m=''2930310''>You</span> <span m=''2930410''>like</span>
  <span m=''2930610''>that</span> <span m=''2930820''>as</span> <span m=''2930970''>a</span>
  <span m=''2931010''>generator</span> <span m=''2931450''>matrix</span> <span m=''2932060''>for</span>
  <span m=''2932230''>the--</span> <span m=''2933480''>That''s</span> <span m=''2934520''>taking</span>
  <span m=''2934890''>this</span> <span m=''2935360''>and</span> <span m=''2935580''>this</span>
  <span m=''2935910''>as</span> <span m=''2936060''>the</span> <span m=''2936160''>two</span>
  <span m=''2936390''>generators,</span> <span m=''2937080''>and</span> <span m=''2937390''>recognizing</span>
  <span m=''2937670''>this</span> <span m=''2938140''>as</span> <span m=''2939060''>1/2,</span>
  <span m=''2939710''>and</span> <span m=''2939840''>this</span> <span m=''2940060''>as</span>
  <span m=''2940340''>root</span> <span m=''2940710''>3</span> <span m=''2940980''>over</span>
  <span m=''2941170''>2.</span> <span m=''2943220''>That</span> <span m=''2943470''>makes</span>
  <span m=''2944100''>the</span> <span m=''2944220''>length</span> <span m=''2944540''>of</span>
  <span m=''2944650''>this</span> <span m=''2944960''>equal</span> <span m=''2945220''>to</span>
  <span m=''2945290''>1/4</span> <span m=''2945820''>plus</span> <span m=''2946080''>3/4,</span>
  <span m=''2946940''>equals</span> <span m=''2947220''>1</span> <span m=''2947560''>square</span>
  <span m=''2947900''>root,</span> <span m=''2948270''>and</span> <span m=''2948360''>it''s</span>
  <span m=''2948450''>1.</span> </p><p><span m=''2949310''>So</span> <span m=''2949480''>these</span>
  <span m=''2949740''>are</span> <span m=''2949800''>my</span> <span m=''2949990''>two</span>
  <span m=''2950220''>generators</span> <span m=''2950980''>of</span> <span m=''2951120''>length</span>
  <span m=''2951400''>1</span> <span m=''2951780''>in</span> <span m=''2951890''>a</span>
  <span m=''2951920''>hexagonal</span> <span m=''2952550''>lattice</span> <span m=''2953040''>of</span>
  <span m=''2956450''>minimum</span> <span m=''2956680''>squared</span> <span m=''2957030''>distance</span>
  <span m=''2957510''>1.</span> <span m=''2958690''>So</span> <span m=''2958910''>based</span>
  <span m=''2959290''>on</span> <span m=''2959460''>that,</span> <span m=''2959810''>I</span>
  <span m=''2959920''>can</span> <span m=''2960180''>say</span> <span m=''2960530''>that</span>
  <span m=''2960690''>the</span> <span m=''2960850''>volume</span> <span m=''2961760''>of</span>
  <span m=''2962380''>A2</span> <span m=''2962590''>is</span> <span m=''2963060''>what?</span>
  </p><p><span m=''2964346''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''2967820''>PROFESSOR:
  Root</span> <span m=''2968020''>3</span> <span m=''2968260''>over</span> <span m=''2968450''>2.</span>
  <span m=''2969000''>Not</span> <span m=''2969310''>hard</span> <span m=''2969650''>to</span>
  <span m=''2969955''>take</span> <span m=''2970107''>the</span> <span m=''2970260''>determinant</span>
  <span m=''2970550''>of</span> <span m=''2970840''>that,</span> <span m=''2971140''>right?</span>
  <span m=''2973490''>And</span> <span m=''2977670''>what''s</span> <span m=''2977900''>the</span>
  <span m=''2978130''>minimum</span> <span m=''2978480''>squared</span> <span m=''2978740''>distance</span>
  <span m=''2979340''>in</span> <span m=''2979450''>this</span> <span m=''2979560''>scaling?</span>
  <span m=''2980310''>What''s</span> <span m=''2980670''>the</span> <span m=''2980920''>minimum</span>
  <span m=''2981320''>non-zero</span> <span m=''2981890''>weight --</span> <span m=''2983480''>squared</span>
  <span m=''2984930''>norm,</span> <span m=''2985400''>it''s</span> <span m=''2985890''>1.</span>
  <span m=''2986610''>So</span> <span m=''2987210''>this</span> <span m=''2987500''>is</span>
  <span m=''2987690''>equal</span> <span m=''2988530''>to</span> <span m=''2988690''>1</span>
  <span m=''2989220''>over</span> <span m=''2990170''>root</span> <span m=''2990590''>3</span>
  <span m=''2990960''>over</span> <span m=''2991260''>2,</span> <span m=''2992390''>which</span>
  <span m=''2992670''>is</span> <span m=''2992850''>equal</span> <span m=''2993190''>to</span>
  <span m=''2993310''>2</span> <span m=''2993840''>over</span> <span m=''2994130''>root</span>
  <span m=''2994500''>3.</span> <span m=''2996060''>Which</span> <span m=''2996540''>is</span>
  <span m=''2996770''>equal</span> <span m=''2997070''>to</span> <span m=''2997180''>what?</span>
  <span m=''2997500''>This</span> <span m=''2997740''>is</span> <span m=''2997900''>3
  dB.</span> <span m=''2999420''>This</span> <span m=''2999730''>is</span> <span m=''3000650''>4.8
  dB,</span> <span m=''3001950''>roughly.</span> <span m=''3002450''>Square</span>
  <span m=''3002810''>root</span> <span m=''3003030''>is</span> <span m=''3003170''>2.4
  dB.</span> <span m=''3005450''>So</span> <span m=''3005800''>this</span> <span m=''3006030''>is</span>
  <span m=''3006180''>about</span> <span m=''3007140''>0.6 dB.</span> </p><p><span
  m=''3012850''>That''s</span> <span m=''3013250''>where</span> <span m=''3013540''>it</span>
  <span m=''3014120''>pays</span> <span m=''3014510''>to</span> <span m=''3014590''>be</span>
  <span m=''3014760''>facile</span> <span m=''3015050''>with</span> <span m=''3015750''>dB''s.</span>
  <span m=''3018040''>This</span> <span m=''3019340''>area,</span> <span m=''3019700''>by</span>
  <span m=''3019920''>the</span> <span m=''3020050''>way,</span> <span m=''3020260''>if</span>
  <span m=''3020370''>you</span> <span m=''3020500''>tried</span> <span m=''3020770''>to</span>
  <span m=''3020860''>compute</span> <span m=''3021280''>the</span> <span m=''3021410''>area</span>
  <span m=''3021660''>of</span> <span m=''3021720''>this</span> <span m=''3021930''>little</span>
  <span m=''3022110''>hexagon</span> <span m=''3022690''>here,</span> <span m=''3023400''>what</span>
  <span m=''3023950''>would</span> <span m=''3024090''>it</span> <span m=''3024220''>be?</span>
  <span m=''3026578''>If</span> <span m=''3027060''>the</span> <span m=''3027240''>area</span>
  <span m=''3027550''>of</span> <span m=''3027660''>this</span> <span m=''3027890''>parallelotope</span>
  <span m=''3028530''>is</span> <span m=''3028780''>the</span> <span m=''3028870''>square</span>
  <span m=''3029230''>root</span> <span m=''3029340''>of</span> <span m=''3029410''>3/2,</span>
  <span m=''3031150''>what''s</span> <span m=''3031300''>the</span> <span m=''3031450''>area</span>
  <span m=''3031720''>of</span> <span m=''3031790''>this</span> <span m=''3032010''>hexagon?</span>
  <span m=''3034770''>The</span> <span m=''3034950''>same,</span> <span m=''3035350''>right?</span>
  <span m=''3035840''>They''re</span> <span m=''3035960''>both</span> <span m=''3036250''>space</span>
  <span m=''3036660''>filling</span> <span m=''3037550''>when</span> <span m=''3037920''>centered</span>
  <span m=''3038880''>on</span> <span m=''3039830''>lattice</span> <span m=''3040220''>points.</span>
  <span m=''3042810''>So</span> <span m=''3043000''>they</span> <span m=''3043120''>have</span>
  <span m=''3043240''>to have</span> <span m=''3043410''>the</span> <span m=''3043490''>same</span>
  <span m=''3043790''>area.</span> <span m=''3046290''>So</span> <span m=''3046570''>that''s</span>
  <span m=''3046830''>an</span> <span m=''3046930''>easy</span> <span m=''3047180''>way</span>
  <span m=''3047330''>of</span> <span m=''3047450''>computing</span> <span m=''3047930''>the</span>
  <span m=''3048510''>area</span> <span m=''3048730''>of</span> <span m=''3048840''>a</span>
  <span m=''3048880''>hexagon,</span> <span m=''3050795''>or</span> <span m=''3050987''>of</span>
  <span m=''3051180''>this</span> <span m=''3051550''>particular</span> <span m=''3051980''>hexagon</span>
  <span m=''3052540''>anyway.</span> </p><p><span m=''3054350''>But</span> <span m=''3054440''>you</span>
  <span m=''3054530''>would</span> <span m=''3054700''>get</span> <span m=''3054930''>the</span>
  <span m=''3055020''>same</span> <span m=''3055290''>result</span> <span m=''3055690''>in</span>
  <span m=''3055780''>either</span> <span m=''3055980''>way.</span> <span m=''3057020''>So</span>
  <span m=''3059250''>comparing</span> <span m=''3059840''>this</span> <span m=''3060210''>with</span>
  <span m=''3060890''>Z-squared,</span> <span m=''3062900''>I</span> <span m=''3063080''>now</span>
  <span m=''3063330''>have</span> <span m=''3063550''>a</span> <span m=''3063630''>quantitative</span>
  <span m=''3064360''>measure</span> <span m=''3065550''>of</span> <span m=''3065690''>how</span>
  <span m=''3065860''>much</span> <span m=''3066160''>denser</span> <span m=''3068480''>A2</span>
  <span m=''3069050''>is</span> <span m=''3069340''>than</span> <span m=''3069740''>Z-squared.</span>
  <span m=''3070740''>Put</span> <span m=''3071060''>in</span> <span m=''3071120''>one</span>
  <span m=''3071330''>way,</span> <span m=''3071540''>if</span> <span m=''3071720''>I</span>
  <span m=''3071800''>fix</span> <span m=''3072190''>the</span> <span m=''3072625''>minimum</span>
  <span m=''3072990''>squared</span> <span m=''3073370''>distance</span> <span m=''3073790''>of</span>
  <span m=''3073870''>each</span> <span m=''3074100''>of</span> <span m=''3074150''>them</span>
  <span m=''3074290''>to</span> <span m=''3074360''>be</span> <span m=''3074490''>1,</span>
  <span m=''3074860''>if</span> <span m=''3075010''>I''m</span> <span m=''3075110''>doing</span>
  <span m=''3075350''>penny-packing</span> <span m=''3075930''>and</span> <span m=''3076200''>I</span>
  <span m=''3076320''>say</span> <span m=''3076440''>I</span> <span m=''3076630''>want</span>
  <span m=''3077480''>pennies</span> <span m=''3077950''>of</span> <span m=''3078040''>a</span>
  <span m=''3078100''>certain</span> <span m=''3078440''>radius</span> <span m=''3079050''>to</span>
  <span m=''3079170''>be</span> <span m=''3079400''>packed</span> <span m=''3079820''>into</span>
  <span m=''3080160''>two-dimensional</span> <span m=''3080980''>space,</span> <span
  m=''3082160''>then</span> <span m=''3084160''>this</span> <span m=''3084410''>is</span>
  <span m=''3084570''>1</span> <span m=''3084890''>over</span> <span m=''3085120''>the</span>
  <span m=''3085350''>volume,</span> <span m=''3086530''>which</span> <span m=''3086720''>is</span>
  <span m=''3086840''>basically</span> <span m=''3087230''>the</span> <span m=''3087350''>density.</span>
  <span m=''3088450''>The</span> <span m=''3088570''>density</span> <span m=''3089500''>of</span>
  <span m=''3089800''>A2</span> <span m=''3090390''>is</span> <span m=''3090580''>2</span>
  <span m=''3090810''>over</span> <span m=''3091050''>root</span> <span m=''3091470''>3,</span>
  <span m=''3091880''>times</span> <span m=''3092290''>[UNINTELLIGIBLE]</span> <span
  m=''3093140''>as</span> <span m=''3093340''>the</span> <span m=''3093440''>density</span>
  <span m=''3094080''>of</span> <span m=''3094200''>points</span> <span m=''3094700''>in</span>
  <span m=''3094870''>z</span> <span m=''3095090''>squared.</span> <span m=''3095540''>I</span>
  <span m=''3095590''>get</span> <span m=''3095860''>more</span> <span m=''3096160''>points</span>
  <span m=''3096610''>per</span> <span m=''3096770''>unit</span> <span m=''3097100''>area</span>
  <span m=''3098780''>with</span> <span m=''3098920''>the</span> <span m=''3099000''>same</span>
  <span m=''3100040''>distance</span> <span m=''3100480''>between</span> <span m=''3100840''>them</span>
  <span m=''3101350''>using</span> <span m=''3101760''>A2</span> <span m=''3102500''>than</span>
  <span m=''3102820''>I</span> <span m=''3102925''>can</span> <span m=''3103030''>with</span>
  <span m=''3103240''>Z-squared.</span> </p><p><span m=''3104210''>So</span> <span
  m=''3104400''>that''s</span> <span m=''3104670''>the</span> <span m=''3104740''>significance</span>
  <span m=''3105520''>of</span> <span m=''3107650''>this</span> <span m=''3107930''>parameter.</span>
  <span m=''3109510''>So</span> <span m=''3109860''>it''s</span> <span m=''3110170''>an</span>
  <span m=''3110230''>obvious</span> <span m=''3110650''>thing</span> <span m=''3110850''>for</span>
  <span m=''3111160''>Hermite</span> <span m=''3111440''>to</span> <span m=''3111670''>have</span>
  <span m=''3111755''>come</span> <span m=''3111840''>up</span> <span m=''3112050''>with.</span>
  <span m=''3112460''>It''s</span> <span m=''3113110''>going</span> <span m=''3113260''>to</span>
  <span m=''3113410''>turn</span> <span m=''3113610''>out</span> <span m=''3113780''>to</span>
  <span m=''3113860''>be</span> <span m=''3113990''>equally</span> <span m=''3114260''>fundamental</span>
  <span m=''3114770''>for</span> <span m=''3115010''>us.</span> <span m=''3120920''>So</span>
  <span m=''3122045''>that</span> <span m=''3122540''>may</span> <span m=''3122725''>be</span>
  <span m=''3122910''>all</span> <span m=''3123080''>we</span> <span m=''3123190''>want</span>
  <span m=''3123340''>to</span> <span m=''3123490''>do</span> <span m=''3123830''>on</span>
  <span m=''3124020''>lattices</span> <span m=''3124710''>for</span> <span m=''3124800''>the</span>
  <span m=''3124940''>time</span> <span m=''3125270''>being.</span> <span m=''3127754''>Yeah,</span>
  <span m=''3128690''>seems</span> <span m=''3129160''>to</span> <span m=''3129270''>be.</span>
  </p><p><span m=''3134150''>So</span> <span m=''3136800''>we''re</span> <span m=''3136930''>talking</span>
  <span m=''3137230''>about</span> <span m=''3137390''>lattice</span> <span m=''3137760''>constellations.</span>
  <span m=''3138760''>The</span> <span m=''3138940''>other</span> <span m=''3139860''>thing</span>
  <span m=''3140030''>we</span> <span m=''3140140''>have</span> <span m=''3140280''>to</span>
  <span m=''3140430''>develop</span> <span m=''3140860''>is</span> <span m=''3141020''>the</span>
  <span m=''3141110''>properties</span> <span m=''3141680''>of</span> <span m=''3141790''>regions.</span>
  <span m=''3145490''>So</span> <span m=''3146280''>let</span> <span m=''3146350''>me</span>
  <span m=''3146520''>talk</span> <span m=''3146870''>about</span> <span m=''3147620''>regions,</span>
  <span m=''3149820''>R --</span> <span m=''3152050''>I''m</span> <span m=''3152220''>thinking</span>
  <span m=''3152700''>of</span> <span m=''3152850''>a</span> <span m=''3153130''>compact</span>
  <span m=''3153780''>region</span> <span m=''3154360''>in</span> <span m=''3156290''>an</span>
  <span m=''3156460''>n-dimensional</span> <span m=''3157310''>space.</span> <span
  m=''3158397''>So</span> <span m=''3159590''>again,</span> <span m=''3159930''>let</span>
  <span m=''3160020''>me</span> <span m=''3160110''>fix</span> <span m=''3160470''>the</span>
  <span m=''3160550''>dimension</span> <span m=''3161020''>to</span> <span m=''3161210''>n.</span>
  <span m=''3162160''>And</span> <span m=''3162420''>we''re</span> <span m=''3162790''>going</span>
  <span m=''3162910''>to</span> <span m=''3162950''>have</span> <span m=''3163160''>a</span>
  <span m=''3163210''>certain</span> <span m=''3163660''>volume.</span> <span m=''3164690''>That''s</span>
  <span m=''3164810''>obviously</span> <span m=''3165390''>an</span> <span m=''3165480''>important</span>
  <span m=''3168000''>characteristic</span> <span m=''3168750''>of</span> <span m=''3168840''>a</span>
  <span m=''3168910''>region.</span> <span m=''3169570''>And</span> <span m=''3169770''>I''m</span>
  <span m=''3169860''>going</span> <span m=''3170000''>to</span> <span m=''3170070''>assume</span>
  <span m=''3170460''>that</span> <span m=''3170570''>this</span> <span m=''3170680''>is</span>
  <span m=''3170830''>finite.</span> </p><p><span m=''3172520''>And</span> <span m=''3172900''>what''s</span>
  <span m=''3173220''>the</span> <span m=''3173370''>other</span> <span m=''3173580''>thing</span>
  <span m=''3174930''>that</span> <span m=''3175180''>we</span> <span m=''3175350''>basically</span>
  <span m=''3175880''>want?</span> <span m=''3177650''>Well,</span> <span m=''3177800''>when</span>
  <span m=''3177960''>I</span> <span m=''3178050''>pick</span> <span m=''3178370''>a</span>
  <span m=''3178450''>constellation</span> <span m=''3179210''>like</span> <span m=''3179480''>this,</span>
  <span m=''3179780''>by</span> <span m=''3179920''>intersecting</span> <span m=''3180850''>a</span>
  <span m=''3180970''>lattice</span> <span m=''3182180''>with</span> <span m=''3182590''>a</span>
  <span m=''3185950''>region,</span> <span m=''3190110''>eventually</span> <span m=''3190710''>I''m</span>
  <span m=''3190840''>going</span> <span m=''3191020''>to</span> <span m=''3191110''>let</span>
  <span m=''3191460''>the</span> <span m=''3192300''>points</span> <span m=''3192750''>in</span>
  <span m=''3192840''>this</span> <span m=''3193020''>constellation</span> <span m=''3193800''>be</span>
  <span m=''3193970''>equiprobable,</span> <span m=''3194695''>as</span> <span m=''3195100''>I</span>
  <span m=''3195250''>always</span> <span m=''3195550''>do</span> <span m=''3196010''>in</span>
  <span m=''3197050''>digital</span> <span m=''3197410''>communications.</span> <span
  m=''3198170''>16</span> <span m=''3198780''>points.</span> <span m=''3199190''>Say</span>
  <span m=''3199410''>they</span> <span m=''3199680''>all</span> <span m=''3199775''>have</span>
  <span m=''3199870''>probably</span> <span m=''3200350''>1/16,</span> <span m=''3201160''>the</span>
  <span m=''3201240''>uniform</span> <span m=''3201820''>probability</span> <span
  m=''3202570''>over</span> <span m=''3202830''>the</span> <span m=''3203210''>discrete</span>
  <span m=''3203700''>points.</span> </p><p><span m=''3209750''>One of the approximations
  I am going to make -- so</span> <span m=''3209870''>what''s</span> <span m=''3210100''>the</span>
  <span m=''3210260''>average</span> <span m=''3210580''>power</span> <span m=''3210900''>of</span>
  <span m=''3211005''>that</span> <span m=''3211110''>constellation?</span> <span
  m=''3213430''>We</span> <span m=''3213650''>could</span> <span m=''3215560''>figure</span>
  <span m=''3215910''>it</span> <span m=''3215970''>out</span> <span m=''3216500''>by</span>
  <span m=''3217370''>taking</span> <span m=''3217890''>1/16</span> <span m=''3218960''>times</span>
  <span m=''3219510''>the</span> <span m=''3220150''>energy.</span> <span m=''3221270''>I</span>
  <span m=''3221640''>should</span> <span m=''3221830''>say</span> <span m=''3222020''>the</span>
  <span m=''3222180''>average</span> <span m=''3222490''>energy,</span> <span m=''3222910''>I''m</span>
  <span m=''3223010''>sorry.</span> <span m=''3223250''>We''re</span> <span m=''3223350''>not</span>
  <span m=''3223510''>talking</span> <span m=''3223800''>power</span> <span m=''3224130''>here.</span>
  <span m=''3224300''>We''re</span> <span m=''3224420''>talking</span> <span m=''3224780''>energy,</span>
  <span m=''3225160''>but</span> <span m=''3225260''>I</span> <span m=''3225360''>read</span>
  <span m=''3225460''>it</span> <span m=''3225530''>as</span> <span m=''3225800''>P.</span>
  <span m=''3226750''>What''s</span> <span m=''3227290''>the</span> <span m=''3227450''>average</span>
  <span m=''3227830''>energy?</span> <span m=''3228270''>It''s</span> <span m=''3228450''>1/16</span>
  <span m=''3229440''>times</span> <span m=''3229970''>the</span> <span m=''3231170''>L2</span>
  <span m=''3231650''>norm</span> <span m=''3232310''>of</span> <span m=''3232450''>each</span>
  <span m=''3232660''>of</span> <span m=''3232730''>these</span> <span m=''3232980''>points,</span>
  <span m=''3233950''>if</span> <span m=''3234060''>you</span> <span m=''3234170''>like</span>
  <span m=''3234400''>that.</span> <span m=''3235045''>It''s</span> <span m=''3235370''>simply</span>
  <span m=''3235790''>the</span> <span m=''3238700''>Euclidean</span> <span m=''3239060''>squared</span>
  <span m=''3239500''>norm.</span> </p><p><span m=''3242760''>And</span> <span m=''3242910''>we</span>
  <span m=''3243030''>get</span> <span m=''3243270''>some</span> <span m=''3243530''>average.</span>
  <span m=''3245210''>But</span> <span m=''3245360''>here''s</span> <span m=''3245670''>the</span>
  <span m=''3245720''>key</span> <span m=''3245980''>approximation</span> <span m=''3246890''>principle.</span>
  <span m=''3248090''>I''m</span> <span m=''3248500''>going</span> <span m=''3248620''>to</span>
  <span m=''3248680''>say</span> <span m=''3248950''>the</span> <span m=''3249150''>average</span>
  <span m=''3249610''>power</span> <span m=''3250070''>of</span> <span m=''3250190''>this</span>
  <span m=''3250420''>constellation,</span> <span m=''3251240''>especially</span>
  <span m=''3251780''>as</span> <span m=''3251910''>the</span> <span m=''3251990''>constellations</span>
  <span m=''3252760''>get</span> <span m=''3252920''>large,</span> <span m=''3254170''>is</span>
  <span m=''3254280''>simply</span> <span m=''3254570''>going</span> <span m=''3254670''>to</span>
  <span m=''3254770''>be</span> <span m=''3254870''>approximated</span> <span m=''3255880''>as</span>
  <span m=''3256220''>the</span> <span m=''3256400''>average</span> <span m=''3256860''>energy</span>
  <span m=''3259010''>of</span> <span m=''3259180''>a</span> <span m=''3259240''>uniform</span>
  <span m=''3259790''>distribution</span> <span m=''3260470''>over</span> <span m=''3260660''>this</span>
  <span m=''3260890''>bounding</span> <span m=''3261290''>region.</span> <span m=''3263090''>Suppose</span>
  <span m=''3263580''>I</span> <span m=''3263670''>simply</span> <span m=''3264690''>put</span>
  <span m=''3265170''>a</span> <span m=''3265530''>uniform</span> <span m=''3266050''>continuous</span>
  <span m=''3266650''>distribution</span> <span m=''3267410''>over</span> <span m=''3267670''>this</span>
  <span m=''3269000''>circle,</span> <span m=''3269730''>this</span> <span m=''3269900''>sphere,</span>
  <span m=''3270520''>two</span> <span m=''3270690''>sphere</span> <span m=''3271080''>that</span>
  <span m=''3271230''>I''ve</span> <span m=''3271370''>used</span> <span m=''3271740''>to</span>
  <span m=''3272800''>be</span> <span m=''3272940''>my</span> <span m=''3273080''>cookie</span>
  <span m=''3273450''>cutter.</span> <span m=''3274650''>I''m</span> <span m=''3274700''>going</span>
  <span m=''3274750''>to</span> <span m=''3274800''>say</span> <span m=''3275060''>that''s</span>
  <span m=''3275350''>going</span> <span m=''3275460''>to</span> <span m=''3275510''>be</span>
  <span m=''3275640''>a</span> <span m=''3275680''>good</span> <span m=''3275910''>approximation</span>
  <span m=''3276850''>to</span> <span m=''3276950''>the</span> <span m=''3277090''>average</span>
  <span m=''3277440''>energy</span> <span m=''3277880''>of</span> <span m=''3277970''>the</span>
  <span m=''3278120''>16</span> <span m=''3278650''>discrete</span> <span m=''3279110''>points,</span>
  <span m=''3279500''>which</span> <span m=''3279770''>are,</span> <span m=''3280890''>by</span>
  <span m=''3281080''>construction,</span> <span m=''3281810''>they''re</span> <span
  m=''3281920''>spread</span> <span m=''3282310''>uniformly</span> <span m=''3282940''>over</span>
  <span m=''3283070''>this</span> <span m=''3283280''>region.</span> </p><p><span
  m=''3284560''>The</span> <span m=''3284670''>approximation</span> <span m=''3285530''>is,</span>
  <span m=''3285800''>I''m</span> <span m=''3285910''>kind</span> <span m=''3286170''>of</span>
  <span m=''3286650''>approximating</span> <span m=''3287810''>a</span> <span m=''3288630''>unit</span>
  <span m=''3289600''>impulse</span> <span m=''3289910''>of</span> <span m=''3290220''>weight</span>
  <span m=''3290790''>there</span> <span m=''3291100''>by</span> <span m=''3292150''>distributed</span>
  <span m=''3292770''>weight</span> <span m=''3293230''>across</span> <span m=''3293890''>its--</span>
  <span m=''3295170''>well,</span> <span m=''3295620''>actually</span> <span m=''3296030''>across</span>
  <span m=''3296670''>its</span> <span m=''3297040''>whole</span> <span m=''3297190''>little</span>
  <span m=''3298190''>region.</span> <span m=''3298620''>If</span> <span m=''3298780''>we</span>
  <span m=''3298990''>have</span> <span m=''3299200''>a</span> <span m=''3299570''>hexagon</span>
  <span m=''3300160''>around</span> <span m=''3300450''>each</span> <span m=''3300690''>one,</span>
  <span m=''3301480''>uniform</span> <span m=''3301980''>distribution</span> <span
  m=''3302280''>over</span> <span m=''3302580''>the</span> <span m=''3302800''>hexagon.</span>
  <span m=''3304206''>And</span> <span m=''3304620''>if</span> <span m=''3304820''>that''s</span>
  <span m=''3305130''>a</span> <span m=''3305190''>reasonable</span> <span m=''3305690''>approximation,</span>
  <span m=''3307740''>then</span> <span m=''3308420''>it''s</span> <span m=''3308640''>reasonable</span>
  <span m=''3309130''>to</span> <span m=''3309305''>say</span> <span m=''3309480''>that</span>
  <span m=''3309585''>the</span> <span m=''3309690''>average</span> <span m=''3310380''>power</span>
  <span m=''3310690''>of</span> <span m=''3310740''>the</span> <span m=''3310790''>whole</span>
  <span m=''3311010''>constellation</span> <span m=''3312970''>is</span> <span m=''3313320''>just</span>
  <span m=''3313550''>the</span> <span m=''3313690''>average</span> <span m=''3313960''>power</span>
  <span m=''3314200''>of</span> <span m=''3314300''>a</span> <span m=''3314350''>uniform</span>
  <span m=''3314840''>distribution</span> <span m=''3315450''>over</span> <span m=''3315610''>this</span>
  <span m=''3315810''>region.</span> </p><p><span m=''3319100''>It''s</span> <span
  m=''3319260''>good</span> <span m=''3319400''>exercise</span> <span m=''3320030''>to</span>
  <span m=''3320160''>try</span> <span m=''3320510''>it</span> <span m=''3320810''>for</span>
  <span m=''3321940''>some</span> <span m=''3322210''>moderate</span> <span m=''3322590''>size</span>
  <span m=''3322980''>cases.</span> <span m=''3323460''>And</span> <span m=''3323530''>you''ll</span>
  <span m=''3323650''>find</span> <span m=''3323960''>it</span> <span m=''3324060''>is</span>
  <span m=''3324630''>a</span> <span m=''3324720''>very</span> <span m=''3324980''>good</span>
  <span m=''3325370''>approximation.</span> <span m=''3326730''>In</span> <span m=''3326830''>any</span>
  <span m=''3327010''>case,</span> <span m=''3327350''>it''s</span> <span m=''3327550''>the</span>
  <span m=''3327660''>one</span> <span m=''3327770''>we''re</span> <span m=''3327810''>going</span>
  <span m=''3327935''>to</span> <span m=''3328060''>use.</span> <span m=''3329520''>So</span>
  <span m=''3329880''>the</span> <span m=''3332990''>other</span> <span m=''3334600''>key</span>
  <span m=''3334890''>parameter</span> <span m=''3335630''>is</span> <span m=''3335950''>going</span>
  <span m=''3336120''>to</span> <span m=''3336290''>be</span> <span m=''3337050''>P(R),</span>
  <span m=''3338320''>which</span> <span m=''3338640''>is,</span> <span m=''3339060''>in</span>
  <span m=''3339260''>words,</span> <span m=''3340550''>the</span> <span m=''3340750''>average</span>
  <span m=''3342280''>energy</span> <span m=''3345530''>of</span> <span m=''3346240''>uniform</span>
  <span m=''3346950''>distribution</span> <span m=''3350370''>over</span> <span m=''3350770''>R.</span>
  <span m=''3353665''>Sorry,</span> <span m=''3355460''>script</span> <span m=''3355810''>R.</span>
  <span m=''3359510''>Now,</span> <span m=''3360520''>when</span> <span m=''3360810''>we</span>
  <span m=''3360960''>write</span> <span m=''3361260''>this</span> <span m=''3361510''>out,</span>
  <span m=''3361860''>this</span> <span m=''3362060''>actually</span> <span m=''3362500''>gets</span>
  <span m=''3362830''>a</span> <span m=''3362900''>little</span> <span m=''3365090''>formidable.</span>
  <span m=''3365730''>So</span> <span m=''3365990''>I</span> <span m=''3366110''>think</span>
  <span m=''3366270''>it''s</span> <span m=''3366430''>better</span> <span m=''3366770''>to</span>
  <span m=''3367260''>remember</span> <span m=''3368390''>what</span> <span m=''3368650''>we''re</span>
  <span m=''3368830''>actually</span> <span m=''3369160''>trying</span> <span m=''3369540''>to</span>
  <span m=''3371010''>compute.</span> <span m=''3371920''>Oh,</span> <span m=''3372290''>and</span>
  <span m=''3373470''>one</span> <span m=''3373640''>last</span> <span m=''3374010''>thing,</span>
  <span m=''3374330''>we''re</span> <span m=''3374540''>going</span> <span m=''3374640''>to</span>
  <span m=''3374700''>normalize</span> <span m=''3375370''>it</span> <span m=''3375520''>per</span>
  <span m=''3375700''>dimension.</span> </p><p><span m=''3382480''>So</span> <span
  m=''3382800''>what</span> <span m=''3382876''>do</span> <span m=''3382953''>I</span>
  <span m=''3383030''>mean?</span> <span m=''3383570''>What''s</span> <span m=''3383960''>a</span>
  <span m=''3384170''>uniform</span> <span m=''3384780''>distribution</span> <span
  m=''3388050''>over</span> <span m=''3388370''>R?</span> <span m=''3393670''>This</span>
  <span m=''3394150''>is</span> <span m=''3395910''>P(x equals 1)</span> <span m=''3400190''>over</span>
  <span m=''3400690''>the</span> <span m=''3400820''>volume</span> <span m=''3401690''>of</span>
  <span m=''3401930''>R</span> <span m=''3403230''>for</span> <span m=''3404030''>x</span>
  <span m=''3404790''>in</span> <span m=''3405150''>R</span> <span m=''3407090''>and</span>
  <span m=''3409000''>0</span> <span m=''3409880''>otherwise.</span> <span m=''3416330''>Uniform</span>
  <span m=''3416890''>within,</span> <span m=''3417360''>0</span> <span m=''3417750''>outside.</span>
  <span m=''3418590''>And</span> <span m=''3418760''>what</span> <span m=''3418900''>does</span>
  <span m=''3418960''>it</span> <span m=''3419020''>have</span> <span m=''3419175''>to</span>
  <span m=''3419330''>equal?</span> <span m=''3419540''>It</span> <span m=''3419860''>has</span>
  <span m=''3420160''>to</span> <span m=''3420210''>be</span> <span m=''3420260''>equal</span>
  <span m=''3420450''>to</span> <span m=''3420640''>1 over V(R),</span> <span m=''3421870''>because</span>
  <span m=''3422090''>its</span> <span m=''3422450''>integral</span> <span m=''3422850''>has</span>
  <span m=''3423040''>to</span> <span m=''3423105''>be</span> <span m=''3423170''>equal</span>
  <span m=''3423325''>to</span> <span m=''3423480''>1</span> <span m=''3423860''>if</span>
  <span m=''3424155''>it''s</span> <span m=''3424302''>a</span> <span m=''3424450''>probability</span>
  <span m=''3425000''>distribution.</span> </p><p><span m=''3427260''>So</span> <span
  m=''3427820''>to</span> <span m=''3427890''>compute</span> <span m=''3428400''>P(R),</span>
  <span m=''3433910''>we</span> <span m=''3434750''>basically</span> <span m=''3435500''>take</span>
  <span m=''3436940''>the</span> <span m=''3437080''>integral</span> <span m=''3437790''>from</span>
  <span m=''3438650''>over</span> <span m=''3439670''>R,</span> <span m=''3443810''>of</span>
  <span m=''3445370''>this</span> <span m=''3445610''>probability</span> <span m=''3446160''>distribution,</span>
  <span m=''3446960''>1 over V(R),</span> <span m=''3449960''>times</span> <span m=''3450340''>what?</span>
  <span m=''3450680''>The</span> <span m=''3450790''>energy</span> <span m=''3451300''>per</span>
  <span m=''3451520''>dimension.</span> <span m=''3452640''>The</span> <span m=''3452770''>total</span>
  <span m=''3453150''>energy</span> <span m=''3453860''>of</span> <span m=''3454190''>x</span>
  <span m=''3455490''>is</span> <span m=''3456830''>x-squared, the</span> <span m=''3459380''>L2</span>
  <span m=''3460790''>norm</span> <span m=''3461115''>of</span> <span m=''3461440''>x.</span>
  <span m=''3463070''>Normalize</span> <span m=''3463620''>per</span> <span m=''3463790''>dimension
  -- we''re</span> <span m=''3464550''>going</span> <span m=''3464580''>to</span>
  <span m=''3464610''>put</span> <span m=''3464790''>an</span> <span m=''3464910''>n</span>
  <span m=''3465150''>over</span> <span m=''3465390''>there --</span> <span m=''3467080''>dx.</span>
  <span m=''3470620''>So</span> <span m=''3470820''>that''s</span> <span m=''3471290''>an</span>
  <span m=''3471970''>equation</span> <span m=''3472560''>for</span> <span m=''3473020''>what</span>
  <span m=''3473550''>it</span> <span m=''3473610''>is</span> <span m=''3473820''>I</span>
  <span m=''3473880''>wanted</span> <span m=''3474040''>to</span> <span m=''3474190''>compute.</span>
  </p><p><span m=''3480380''>I</span> <span m=''3480510''>think</span> <span m=''3480670''>it''s</span>
  <span m=''3480840''>much</span> <span m=''3480980''>harder</span> <span m=''3481205''>to</span>
  <span m=''3481430''>remember</span> <span m=''3481780''>the</span> <span m=''3481880''>terms</span>
  <span m=''3482280''>in</span> <span m=''3482410''>this</span> <span m=''3482770''>than</span>
  <span m=''3482870''>to</span> <span m=''3482960''>remember</span> <span m=''3483390''>this</span>
  <span m=''3485580''>verbal</span> <span m=''3485940''>description</span> <span m=''3486550''>of</span>
  <span m=''3486670''>what</span> <span m=''3486840''>we</span> <span m=''3486960''>want.</span>
  <span m=''3489270''>But</span> <span m=''3489490''>you</span> <span m=''3489610''>may</span>
  <span m=''3489760''>be</span> <span m=''3489920''>more</span> <span m=''3490100''>literate</span>
  <span m=''3490490''>than</span> <span m=''3490660''>I.</span> <span m=''3492600''>Now,</span>
  <span m=''3495930''>let''s</span> <span m=''3496210''>define --</span> <span m=''3497220''>we</span>
  <span m=''3497440''>want</span> <span m=''3497600''>to</span> <span m=''3497760''>normalize</span>
  <span m=''3498470''>quantity</span> <span m=''3499060''>comparable</span> <span
  m=''3499780''>to</span> <span m=''3501590''>Hermite</span> <span m=''3501995''>or</span>
  <span m=''3502270''>coding</span> <span m=''3502620''>gain</span> <span m=''3502940''>over</span>
  <span m=''3503170''>here.</span> <span m=''3504550''>The</span> <span m=''3505370''>normalized</span>
  <span m=''3506020''>quantity</span> <span m=''3506430''>we''re</span> <span m=''3506640''>going</span>
  <span m=''3506850''>to</span> <span m=''3507060''>use -- </span> <span m=''3507960''>we</span>
  <span m=''3508090''>want</span> <span m=''3508270''>to</span> <span m=''3508440''>take</span>
  <span m=''3509010''>P(R) -- and</span> <span m=''3511470''>what</span> <span m=''3511920''>should</span>
  <span m=''3512100''>we</span> <span m=''3512260''>normalize</span> <span m=''3512830''>it</span>
  <span m=''3512970''>by</span> <span m=''3515170''>to</span> <span m=''3515300''>make</span>
  <span m=''3515520''>it</span> <span m=''3515660''>scale-invariant,</span> <span
  m=''3516040''>let''s</span> <span m=''3516285''>say</span> <span m=''3517030''>again?</span>
  </p><p><span m=''3519220''>Again,</span> <span m=''3519550''>if</span> <span m=''3519680''>I</span>
  <span m=''3519740''>take</span> <span m=''3520040''>the</span> <span m=''3520130''>region,</span>
  <span m=''3521480''>I</span> <span m=''3521600''>scale</span> <span m=''3521825''>the</span>
  <span m=''3522050''>region</span> <span m=''3522390''>by</span> <span m=''3522550''>alpha</span>
  <span m=''3523150''>and</span> <span m=''3523350''>get</span> <span m=''3523550''>alpha_R.</span>
  <span m=''3525590''>What''s</span> <span m=''3526030''>going</span> <span m=''3526130''>to</span>
  <span m=''3526220''>happen</span> <span m=''3526710''>to</span> <span m=''3527050''>the</span>
  <span m=''3527220''>average</span> <span m=''3527590''>energy</span> <span m=''3527970''>of</span>
  <span m=''3528025''>a</span> <span m=''3528080''>uniform</span> <span m=''3528550''>distribution</span>
  <span m=''3529200''>over</span> <span m=''3529490''>R?</span> </p><p><span m=''3533070''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''3534450''>PROFESSOR: It''s</span> <span m=''3534640''>going</span>
  <span m=''3534780''>to</span> <span m=''3534840''>go</span> <span m=''3534970''>up</span>
  <span m=''3535120''>as</span> <span m=''3535270''>alpha</span> <span m=''3535695''>squared.</span>
  <span m=''3537760''>Energy</span> <span m=''3538230''>scarce,</span> <span m=''3539480''>goes</span>
  <span m=''3539800''>as</span> <span m=''3539950''>the</span> <span m=''3540030''>square</span>
  <span m=''3540480''>of</span> <span m=''3540640''>the</span> <span m=''3540720''>scale</span>
  <span m=''3541060''>factor.</span> <span m=''3542430''>So</span> <span m=''3542760''>again,</span>
  <span m=''3543150''>I</span> <span m=''3543350''>want</span> <span m=''3543550''>to</span>
  <span m=''3544010''>normalize</span> <span m=''3544380''>it</span> <span m=''3544750''>by</span>
  <span m=''3545010''>V(R)</span> <span m=''3545680''>over</span> <span m=''3547180''>2</span>
  <span m=''3547360''>to</span> <span m=''3547430''>the</span> <span m=''3547590''>n,</span>
  <span m=''3549850''>because</span> <span m=''3550170''>this</span> <span m=''3550380''>is</span>
  <span m=''3550530''>also</span> <span m=''3550840''>something</span> <span m=''3551300''>that</span>
  <span m=''3551420''>will</span> <span m=''3551630''>go</span> <span m=''3551790''>up</span>
  <span m=''3551930''>as</span> <span m=''3552110''>alpha</span> <span m=''3552390''>squared</span>
  <span m=''3552835''>if</span> <span m=''3553280''>I</span> <span m=''3553380''>scale</span>
  <span m=''3556280''>R</span> <span m=''3556650''>by</span> <span m=''3556850''>alpha.</span>
  </p><p><span m=''3560960''>So</span> <span m=''3561180''>this</span> <span m=''3561410''>is</span>
  <span m=''3561580''>what''s</span> <span m=''3561950''>known</span> <span m=''3562450''>as</span>
  <span m=''3562910''>the</span> <span m=''3564500''>dimension-less</span> <span m=''3568360''>or</span>
  <span m=''3570550''>normalized--</span> <span m=''3571830''>it</span> <span m=''3572270''>has</span>
  <span m=''3572710''>both</span> <span m=''3573030''>names--</span> <span m=''3578060''>second</span>
  <span m=''3578370''>moment.</span> <span m=''3584190''>Another</span> <span m=''3586430''>name</span>
  <span m=''3586680''>for</span> <span m=''3586840''>this</span> <span m=''3587250''>is</span>
  <span m=''3587510''>the</span> <span m=''3587780''>second</span> <span m=''3588050''>moment</span>
  <span m=''3588500''>per</span> <span m=''3588720''>dimension</span> <span m=''3590580''>of</span>
  <span m=''3590970''>a</span> <span m=''3591040''>uniform</span> <span m=''3591490''>distribution</span>
  <span m=''3592160''>over</span> <span m=''3592440''>R.</span> <span m=''3593210''>This</span>
  <span m=''3593450''>is</span> <span m=''3593640''>a</span> <span m=''3593730''>normalized</span>
  <span m=''3594520''>or</span> <span m=''3594660''>dimension-less</span> <span m=''3595550''>second</span>
  <span m=''3595930''>moment.</span> <span m=''3598620''>I</span> <span m=''3598740''>think</span>
  <span m=''3598850''>I</span> <span m=''3598890''>call</span> <span m=''3599140''>it</span>
  <span m=''3599220''>normalized</span> <span m=''3599550''>in</span> <span m=''3599880''>the</span>
  <span m=''3600100''>notes,</span> <span m=''3600330''>but</span> <span m=''3601850''>it''s</span>
  <span m=''3602040''>always</span> <span m=''3602200''>called</span> <span m=''3602490''>G</span>
  <span m=''3602820''>in</span> <span m=''3602930''>the</span> <span m=''3603030''>literature.</span>
  </p><p><span m=''3605100''>And</span> <span m=''3605300''>let</span> <span m=''3605420''>me</span>
  <span m=''3605710''>just</span> <span m=''3606110''>introduce</span> <span m=''3606680''>here--</span>
  <span m=''3609420''>well,</span> <span m=''3609650''>what''s</span> <span m=''3609950''>the</span>
  <span m=''3610390''>normalized</span> <span m=''3611990''>second</span> <span m=''3612460''>moment</span>
  <span m=''3612940''>of</span> <span m=''3613910''>an</span> <span m=''3614040''>interval?</span>
  <span m=''3614810''>Say,</span> <span m=''3615300''>a</span> <span m=''3615790''>symmetric</span>
  <span m=''3616350''>interval</span> <span m=''3616940''>around</span> <span m=''3617270''>the</span>
  <span m=''3617400''>origin.</span> <span m=''3619590''>G</span> <span m=''3619900''>to</span>
  <span m=''3619935''>the</span> <span m=''3619970''>minus</span> <span m=''3620400''>1</span>
  <span m=''3620710''>to</span> <span m=''3620820''>the</span> <span m=''3620930''>1,</span>
  <span m=''3621240''>which</span> <span m=''3621480''>is</span> <span m=''3621760''>like</span>
  <span m=''3622010''>the</span> <span m=''3622130''>interval</span> <span m=''3622510''>that</span>
  <span m=''3622630''>we</span> <span m=''3622740''>used</span> <span m=''3623120''>to</span>
  <span m=''3623270''>pull</span> <span m=''3623580''>out</span> <span m=''3623830''>the</span>
  <span m=''3624100''>m-PAM</span> <span m=''3625450''>signal</span> <span m=''3625800''>structure.</span>
  <span m=''3626330''>So</span> <span m=''3626510''>let''s</span> <span m=''3627670''>take</span>
  <span m=''3631200''>n</span> <span m=''3631550''>to</span> <span m=''3631640''>be</span>
  <span m=''3631820''>equal</span> <span m=''3632080''>to</span> <span m=''3632150''>1,</span>
  <span m=''3632650''>R</span> <span m=''3633060''>just</span> <span m=''3633360''>to</span>
  <span m=''3633450''>be</span> <span m=''3634020''>the</span> <span m=''3634200''>interval</span>
  <span m=''3634670''>from</span> <span m=''3634900''>-1 to +1.</span> <span m=''3637680''>And</span>
  <span m=''3638030''>V(R)</span> <span m=''3639760''>equals</span> <span m=''3640330''>what?</span>
  <span m=''3642206''>It''s</span> <span m=''3642690''>the</span> <span m=''3642900''>length</span>
  <span m=''3643160''>of</span> <span m=''3643310''>R,</span> <span m=''3643590''>which</span>
  <span m=''3643790''>is</span> <span m=''3643950''>2.</span> </p><p><span m=''3649640''>What''s</span>
  <span m=''3650490''>P(R)?</span> <span m=''3654860''>The</span> <span m=''3655230''>integral</span>
  <span m=''3655430''>from</span> <span m=''3656030''>-1</span> <span m=''3657010''>to</span>
  <span m=''3657370''>1,</span> <span m=''3657980''>x</span> <span m=''3658190''>squared,</span>
  <span m=''3659520''>dx,</span> <span m=''3660870''>which</span> <span m=''3661480''>is</span>
  <span m=''3662050''>2/3.</span> <span m=''3667490''>I</span> <span m=''3667575''>think</span>
  <span m=''3667660''>so.</span> </p><p><span m=''3669716''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''3674150''>PROFESSOR: Right,</span> <span m=''3674640''>1/2.</span>
  <span m=''3675540''>Thank</span> <span m=''3675780''>you.</span> <span m=''3678660''>That''s</span>
  <span m=''3678820''>1/3.</span> <span m=''3684290''>All</span> <span m=''3684550''>right,</span>
  <span m=''3684970''>so</span> <span m=''3685360''>what</span> <span m=''3685600''>is</span>
  <span m=''3686270''>G(R)</span> <span m=''3686860''>going</span> <span m=''3687020''>to</span>
  <span m=''3687180''>be,</span> <span m=''3687330''>or</span> <span m=''3687570''>G</span>
  <span m=''3687830''>going</span> <span m=''3687990''>to</span> <span m=''3688050''>be?</span>
  <span m=''3688290''>This</span> <span m=''3688520''>is</span> <span m=''3688680''>going</span>
  <span m=''3688870''>to</span> <span m=''3689020''>be</span> <span m=''3691590''>P(R)</span>
  <span m=''3692390''>over</span> <span m=''3693070''>V(R)-squared.</span> <span m=''3696070''>And</span>
  <span m=''3696450''>so</span> <span m=''3696630''>this</span> <span m=''3696810''>is</span>
  <span m=''3696960''>going</span> <span m=''3697090''>to</span> <span m=''3697220''>be</span>
  <span m=''3697340''>1/3</span> <span m=''3698380''>over</span> <span m=''3698870''>4,</span>
  <span m=''3700100''>or</span> <span m=''3700470''>1/12.</span> <span m=''3705050''>OK,</span>
  <span m=''3705390''>that''s</span> <span m=''3705770''>not</span> <span m=''3706000''>as</span>
  <span m=''3706150''>nice</span> <span m=''3706810''>as</span> <span m=''3707070''>this</span>
  <span m=''3707540''>over</span> <span m=''3707800''>here,</span> <span m=''3708840''>but</span>
  <span m=''3709480''>it</span> <span m=''3709630''>is</span> <span m=''3709840''>what</span>
  <span m=''3710000''>it</span> <span m=''3710110''>is.</span> </p><p><span m=''3711940''>There''s</span>
  <span m=''3712180''>a</span> <span m=''3712230''>number</span> <span m=''3712520''>that</span>
  <span m=''3712680''>shows</span> <span m=''3713030''>up</span> <span m=''3713230''>in</span>
  <span m=''3713440''>quantization,</span> <span m=''3714150''>for</span> <span m=''3714350''>instance,</span>
  <span m=''3716000''>uniform</span> <span m=''3716500''>scalar</span> <span m=''3716930''>quantizer,</span>
  <span m=''3717530''>you''ll</span> <span m=''3717700''>find</span> <span m=''3717960''>a</span>
  <span m=''3718020''>1/12</span> <span m=''3718620''>in</span> <span m=''3718690''>there.</span>
  <span m=''3718890''>Why?</span> <span m=''3719590''>It''s</span> <span m=''3719870''>because</span>
  <span m=''3720260''>of</span> <span m=''3720330''>this</span> <span m=''3720540''>equation.</span>
  <span m=''3727901''>If</span> <span m=''3728380''>we</span> <span m=''3728520''>ask</span>
  <span m=''3728820''>again</span> <span m=''3729230''>about</span> <span m=''3729640''>the</span>
  <span m=''3729930''>invariances</span> <span m=''3730890''>of</span> <span m=''3731030''>this--</span>
  <span m=''3731830''>this</span> <span m=''3732110''>is</span> <span m=''3732530''>the</span>
  <span m=''3732790''>last</span> <span m=''3733040''>homework</span> <span m=''3733390''>problem</span>
  <span m=''3733690''>for</span> <span m=''3733810''>this</span> <span m=''3734080''>week--</span>
  <span m=''3735000''>it''s</span> <span m=''3735430''>invariant</span> <span m=''3735960''>not</span>
  <span m=''3736150''>only</span> <span m=''3736380''>to</span> <span m=''3736480''>scaling,</span>
  <span m=''3737510''>but,</span> <span m=''3737720''>again,</span> <span m=''3738160''>it''s</span>
  <span m=''3738390''>invariant</span> <span m=''3738670''>to</span> <span m=''3738950''>orthogonal</span>
  <span m=''3739590''>transformations,</span> <span m=''3740520''>because</span> <span
  m=''3740810''>orthogonal</span> <span m=''3741420''>transformations</span> <span
  m=''3742320''>won''t</span> <span m=''3742910''>affect</span> <span m=''3743360''>either</span>
  <span m=''3743680''>of</span> <span m=''3743750''>these</span> <span m=''3744040''>things.</span>
  <span m=''3744420''>A</span> <span m=''3744510''>rigid</span> <span m=''3744880''>rotation,</span>
  <span m=''3746590''>about</span> <span m=''3747280''>the</span> <span m=''3747420''>origin,</span>
  <span m=''3747940''>won''t</span> <span m=''3748210''>affect</span> <span m=''3748710''>V(R)</span>
  <span m=''3749700''>or</span> <span m=''3749730''>P(R).</span> <span m=''3752330''>And</span>
  <span m=''3752630''>furthermore,</span> <span m=''3753340''>it''s</span> <span m=''3753720''>invariant</span>
  <span m=''3754290''>to</span> <span m=''3754520''>Cartesian</span> <span m=''3755110''>products,</span>
  <span m=''3756730''>again.</span> </p><p><span m=''3757045''>If</span> <span m=''3757360''>we</span>
  <span m=''3757460''>just</span> <span m=''3758090''>have</span> <span m=''3758280''>a</span>
  <span m=''3758330''>series</span> <span m=''3758810''>of</span> <span m=''3758940''>regions,</span>
  <span m=''3759520''>a</span> <span m=''3759560''>region</span> <span m=''3760020''>made</span>
  <span m=''3760260''>up</span> <span m=''3760920''>basically as</span> <span m=''3761870''>the</span>
  <span m=''3762840''>Cartesian</span> <span m=''3763440''>product,</span> <span m=''3763870''>like</span>
  <span m=''3764040''>an</span> <span m=''3764140''>n-cube</span> <span m=''3767110''>is</span>
  <span m=''3767310''>a</span> <span m=''3767370''>Cartesian</span> <span m=''3767980''>product.</span>
  <span m=''3768540''>We</span> <span m=''3768670''>just</span> <span m=''3768970''>pick</span>
  <span m=''3769230''>each</span> <span m=''3769490''>of</span> <span m=''3769570''>the</span>
  <span m=''3769650''>dimensions</span> <span m=''3771090''>independently</span> <span
  m=''3772010''>from</span> <span m=''3772350''>some</span> <span m=''3772640''>set</span>
  <span m=''3772970''>R.</span> <span m=''3775450''>Then</span> <span m=''3775650''>that''s</span>
  <span m=''3775950''>not</span> <span m=''3776130''>going</span> <span m=''3776230''>to</span>
  <span m=''3776280''>affect</span> <span m=''3776730''>the</span> <span m=''3776820''>normalized</span>
  <span m=''3777360''>second</span> <span m=''3777700''>moment</span> <span m=''3778040''>either.</span>
  <span m=''3778450''>Exercise</span> <span m=''3779120''>for</span> <span m=''3779230''>the</span>
  <span m=''3779330''>student.</span> </p><p><span m=''3781600''>So</span> <span m=''3783550''>from</span>
  <span m=''3783850''>that</span> <span m=''3784120''>result,</span> <span m=''3784780''>I</span>
  <span m=''3784980''>can</span> <span m=''3786290''>say</span> <span m=''3786700''>that</span>
  <span m=''3786860''>G([-1 1])</span> <span m=''3788990''>to</span> <span m=''3789160''>the</span>
  <span m=''3789380''>m.</span> <span m=''3791110''>Which</span> <span m=''3791330''>is</span>
  <span m=''3791470''>what?</span> <span m=''3794640''>This</span> <span m=''3794860''>is</span>
  <span m=''3795010''>an</span> <span m=''3795150''>m-cube</span> <span m=''3795420''>of</span>
  <span m=''3795860''>side</span> <span m=''3797010''>2.</span> <span m=''3800570''>If</span>
  <span m=''3801070''>I</span> <span m=''3801490''>say</span> <span m=''3801930''>each</span>
  <span m=''3802260''>of</span> <span m=''3802450''>the</span> <span m=''3803220''>coordinates,</span>
  <span m=''3804060''>x1,</span> <span m=''3805080''>x2,</span> <span m=''3806150''>x3,</span>
  <span m=''3807340''>up</span> <span m=''3807720''>to</span> <span m=''3808050''>xm,</span>
  <span m=''3809345''>has</span> <span m=''3809650''>got</span> <span m=''3809850''>to</span>
  <span m=''3810150''>be</span> <span m=''3810720''>xk n times </span> <span m=''3812780''>[-1
  1],</span> <span m=''3814770''>then</span> <span m=''3814960''>what</span> <span
  m=''3815140''>I''m</span> <span m=''3815500''>going</span> <span m=''3815640''>to</span>
  <span m=''3815690''>get,</span> <span m=''3816130''>the</span> <span m=''3816210''>region</span>
  <span m=''3816560''>defined</span> <span m=''3817010''>by</span> <span m=''3817170''>that</span>
  <span m=''3817550''>is</span> <span m=''3817790''>an</span> <span m=''3817890''>m-cubed,</span>
  <span m=''3818960''>centered</span> <span m=''3819360''>on</span> <span m=''3819470''>the</span>
  <span m=''3819620''>origin</span> <span m=''3820240''>of</span> <span m=''3820460''>side</span>
  <span m=''3820760''>2.</span> </p><p><span m=''3824260''>So</span> <span m=''3825590''>the</span>
  <span m=''3825710''>normalized</span> <span m=''3826220''>second</span> <span m=''3826540''>moment</span>
  <span m=''3826820''>of</span> <span m=''3826900''>that</span> <span m=''3827585''>is</span>
  <span m=''3827910''>going</span> <span m=''3828090''>to</span> <span m=''3828200''>be</span>
  <span m=''3828380''>1/12.</span> <span m=''3832650''>This</span> <span m=''3833680''>is</span>
  <span m=''3833790''>where</span> <span m=''3833940''>the</span> <span m=''3834050''>shortcut</span>
  <span m=''3834690''>begins</span> <span m=''3835070''>to</span> <span m=''3835180''>help</span>
  <span m=''3835470''>you.</span> <span m=''3839340''>I</span> <span m=''3839430''>guess</span>
  <span m=''3839670''>I''m</span> <span m=''3839740''>trying</span> <span m=''3839880''>to</span>
  <span m=''3840020''>put</span> <span m=''3840310''>too</span> <span m=''3840440''>much</span>
  <span m=''3840720''>on</span> <span m=''3840810''>one</span> <span m=''3841060''>board.</span>
  <span m=''3842560''>But</span> <span m=''3843160''>the</span> <span m=''3843260''>last</span>
  <span m=''3843770''>thing</span> <span m=''3844010''>I</span> <span m=''3844070''>want</span>
  <span m=''3844270''>to</span> <span m=''3844320''>put</span> <span m=''3844520''>up</span>
  <span m=''3844730''>on</span> <span m=''3844850''>here</span> <span m=''3845280''>is</span>
  <span m=''3845670''>the</span> <span m=''3846430''>shaping</span> <span m=''3846730''>gain.</span>
  <span m=''3847320''>The</span> <span m=''3847640''>shape</span> <span m=''3848000''>gain</span>
  <span m=''3848360''>of</span> <span m=''3848580''>a</span> <span m=''3848680''>region</span>
  <span m=''3853910''>is</span> <span m=''3854190''>defined</span> <span m=''3854970''>as</span>
  <span m=''3855800''>the</span> <span m=''3855900''>shaping</span> <span m=''3856370''>gain</span>
  <span m=''3857580''>of</span> <span m=''3857760''>the</span> <span m=''3857880''>region</span>
  <span m=''3859240''>is</span> <span m=''3859550''>equal</span> <span m=''3859900''>to</span>
  <span m=''3860860''>1/12.</span> <span m=''3863120''>So</span> <span m=''3863350''>we''re</span>
  <span m=''3863470''>kind</span> <span m=''3863640''>of</span> <span m=''3863720''>taking</span>
  <span m=''3864100''>as</span> <span m=''3864210''>a</span> <span m=''3864310''>baseline,</span>
  <span m=''3865615''>the</span> <span m=''3865890''>m-cube,</span> <span m=''3867110''>in</span>
  <span m=''3867390''>any</span> <span m=''3867460''>number</span> <span m=''3867890''>of</span>
  <span m=''3868090''>dimensions</span> <span m=''3868760''>n,</span> <span m=''3870170''>over</span>
  <span m=''3871430''>G(the region).</span> </p><p><span m=''3876190''>In</span> <span
  m=''3876455''>other</span> <span m=''3876587''>words,</span> <span m=''3878120''>how</span>
  <span m=''3878300''>much</span> <span m=''3878670''>less</span> <span m=''3879510''>is</span>
  <span m=''3879810''>the</span> <span m=''3880040''>dimension-less</span> <span m=''3881060''>second</span>
  <span m=''3881460''>moment,</span> <span m=''3881840''>the</span> <span m=''3881940''>normalized</span>
  <span m=''3882470''>second</span> <span m=''3882820''>moment,</span> <span m=''3883950''>than</span>
  <span m=''3884100''>what</span> <span m=''3884280''>you</span> <span m=''3884440''>would</span>
  <span m=''3884830''>get</span> <span m=''3884856''>for</span> <span m=''3884883''>an</span>
  <span m=''3884910''>m-cube?</span> <span m=''3887450''>In</span> <span m=''3887640''>every</span>
  <span m=''3888960''>dimension</span> <span m=''3892370''>except</span> <span m=''3892670''>for</span>
  <span m=''3892800''>one,</span> <span m=''3894000''>a</span> <span m=''3894100''>sphere</span>
  <span m=''3895500''>is</span> <span m=''3895710''>going</span> <span m=''3895830''>to</span>
  <span m=''3895950''>be</span> <span m=''3896260''>a</span> <span m=''3896650''>better</span>
  <span m=''3898020''>region,</span> <span m=''3898530''>from</span> <span m=''3899810''>a</span>
  <span m=''3901300''>second</span> <span m=''3901670''>moment</span> <span m=''3902020''>point</span>
  <span m=''3902270''>of</span> <span m=''3902360''>view,</span> <span m=''3904090''>than</span>
  <span m=''3904650''>an</span> <span m=''3904800''>m-cube.</span> <span m=''3905330''>An</span>
  <span m=''3905520''>m-cube</span> <span m=''3905970''>has</span> <span m=''3906295''>corners.</span>
  <span m=''3907460''>Really,</span> <span m=''3907900''>it''s</span> <span m=''3908550''>pretty</span>
  <span m=''3908940''>obvious</span> <span m=''3909450''>that,</span> <span m=''3909540''>if</span>
  <span m=''3909620''>you</span> <span m=''3909750''>want</span> <span m=''3909930''>to</span>
  <span m=''3909980''>minimize</span> <span m=''3911540''>the</span> <span m=''3912020''>normalized</span>
  <span m=''3912520''>second</span> <span m=''3912840''>moment</span> <span m=''3913190''>in</span>
  <span m=''3913310''>any</span> <span m=''3913490''>number</span> <span m=''3913720''>of</span>
  <span m=''3913820''>dimensions,</span> <span m=''3914310''>you</span> <span m=''3914510''>would</span>
  <span m=''3914820''>choose</span> <span m=''3914860''>an</span> <span m=''3914900''>m-sphere,</span>
  <span m=''3917370''>because</span> <span m=''3918780''>if</span> <span m=''3919040''>you</span>
  <span m=''3919116''>have</span> <span m=''3919193''>any</span> <span m=''3919270''>wrinkle</span>
  <span m=''3919690''>that</span> <span m=''3919760''>comes</span> <span m=''3920000''>out</span>
  <span m=''3920063''>of</span> <span m=''3920126''>an</span> <span m=''3920190''>m-sphere,</span>
  <span m=''3921760''>anything</span> <span m=''3922130''>that''s</span> <span m=''3922300''>not</span>
  <span m=''3922440''>an</span> <span m=''3922580''>m-sphere,</span> <span m=''3923080''>you</span>
  <span m=''3923170''>should</span> <span m=''3923390''>try</span> <span m=''3923540''>to</span>
  <span m=''3923640''>squash</span> <span m=''3924080''>it</span> <span m=''3924180''>back</span>
  <span m=''3924460''>in</span> <span m=''3924635''>it.</span> <span m=''3924810''>And</span>
  <span m=''3925030''>that''ll</span> <span m=''3925270''>make</span> <span m=''3925500''>it</span>
  <span m=''3925660''>an</span> <span m=''3925740''>m-sphere.</span> </p><p><span
  m=''3926150''>You''ll</span> <span m=''3926330''>take</span> <span m=''3926590''>higher</span>
  <span m=''3926930''>energy</span> <span m=''3927610''>and</span> <span m=''3927730''>make</span>
  <span m=''3927910''>it</span> <span m=''3927990''>lower</span> <span m=''3928340''>energy</span>
  <span m=''3929220''>for</span> <span m=''3929320''>the</span> <span m=''3929430''>same</span>
  <span m=''3929660''>little</span> <span m=''3929920''>unit</span> <span m=''3930280''>of</span>
  <span m=''3931750''>Play-Doh</span> <span m=''3932270''>or</span> <span m=''3933450''>mass</span>
  <span m=''3933880''>stuff.</span> <span m=''3935100''>So</span> <span m=''3935435''>a</span>
  <span m=''3935770''>sphere</span> <span m=''3937140''>will</span> <span m=''3937280''>give</span>
  <span m=''3937470''>you</span> <span m=''3937640''>the</span> <span m=''3937770''>best</span>
  <span m=''3939910''>normalized</span> <span m=''3940410''>second</span> <span m=''3940730''>moment</span>
  <span m=''3941060''>in</span> <span m=''3941170''>any</span> <span m=''3941350''>number</span>
  <span m=''3941610''>of</span> <span m=''3941850''>dimensions</span> <span m=''3942210''>n,</span>
  <span m=''3942550''>so</span> <span m=''3942770''>you''re</span> <span m=''3942970''>always</span>
  <span m=''3943220''>going</span> <span m=''3943340''>to</span> <span m=''3943390''>get</span>
  <span m=''3944160''>a</span> <span m=''3944280''>G(R)</span> <span m=''3944940''>that''s</span>
  <span m=''3945250''>less</span> <span m=''3945640''>than</span> <span m=''3945960''>1/12.</span>
  <span m=''3946830''>That''s</span> <span m=''3947120''>good.</span> <span m=''3948220''>And</span>
  <span m=''3948530''>this</span> <span m=''3948750''>measures</span> <span m=''3949360''>the</span>
  <span m=''3950880''>amount</span> <span m=''3951120''>of</span> <span m=''3951240''>gain.</span>
  </p><p><span m=''3952000''>Again,</span> <span m=''3952600''>you</span> <span m=''3952750''>can</span>
  <span m=''3952890''>measure</span> <span m=''3953170''>this</span> <span m=''3953490''>in</span>
  <span m=''3953960''>dB.</span> <span m=''3955026''>That''s</span> <span m=''3955502''>going</span>
  <span m=''3955741''>to</span> <span m=''3955980''>translate</span> <span m=''3956600''>directly</span>
  <span m=''3957080''>to</span> <span m=''3957250''>dB.</span> <span m=''3963080''>I</span>
  <span m=''3963210''>suppose</span> <span m=''3963540''>I</span> <span m=''3963590''>could</span>
  <span m=''3963730''>do</span> <span m=''3963840''>an</span> <span m=''3963920''>example</span>
  <span m=''3964490''>for</span> <span m=''3964660''>the</span> <span m=''3964920''>sphere</span>
  <span m=''3965430''>in</span> <span m=''3966040''>two</span> <span m=''3966190''>dimensions,</span>
  <span m=''3966720''>but</span> <span m=''3966810''>I</span> <span m=''3966860''>won''t.</span>
  <span m=''3967150''>How</span> <span m=''3967370''>are</span> <span m=''3967455''>we</span>
  <span m=''3967540''>doing</span> <span m=''3967800''>on</span> <span m=''3967950''>time?</span>
  <span m=''3980080''>Let</span> <span m=''3980240''>me</span> <span m=''3980400''>see</span>
  <span m=''3980670''>if</span> <span m=''3980850''>I</span> <span m=''3980970''>can</span>
  <span m=''3982960''>do</span> <span m=''3983630''>the</span> <span m=''3983800''>union-bound</span>
  <span m=''3984710''>estimate.</span> <span m=''3988310''>That</span> <span m=''3988750''>would</span>
  <span m=''3988850''>be</span> <span m=''3988950''>a</span> <span m=''3989050''>trick,</span>
  <span m=''3989430''>but</span> <span m=''3989600''>I</span> <span m=''3989760''>think</span>
  <span m=''3989910''>it''s</span> <span m=''3989980''>doable,</span> <span m=''3993400''>because</span>
  <span m=''3993870''>this</span> <span m=''3994050''>is</span> <span m=''3994200''>where</span>
  <span m=''3994420''>we''re</span> <span m=''3994560''>going.</span> </p><p><span
  m=''3998160''>So</span> <span m=''3998770''>the</span> <span m=''3998880''>union-bound</span>
  <span m=''3999630''>estimate,</span> <span m=''4008380''>which</span> <span m=''4008680''>is</span>
  <span m=''4008780''>something</span> <span m=''4009160''>we</span> <span m=''4009290''>did</span>
  <span m=''4009530''>way</span> <span m=''4009750''>back</span> <span m=''4010110''>in</span>
  <span m=''4010180''>chapter</span> <span m=''4010600''>five</span> <span m=''4011010''>or</span>
  <span m=''4011160''>something,</span> <span m=''4016740''>is</span> <span m=''4016980''>basically,</span>
  <span m=''4018260''>given</span> <span m=''4018650''>a</span> <span m=''4018880''>constellation,</span>
  <span m=''4020400''>which</span> <span m=''4020700''>we''re</span> <span m=''4020880''>going</span>
  <span m=''4020953''>to</span> <span m=''4021026''>have</span> <span m=''4021100''>a</span>
  <span m=''4021320''>lattice</span> <span m=''4021740''>constellation</span> <span
  m=''4022560''>based</span> <span m=''4023010''>on</span> <span m=''4024160''>some</span>
  <span m=''4024420''>lattice</span> <span m=''4024890''>lambda</span> <span m=''4025640''>and</span>
  <span m=''4025970''>some</span> <span m=''4027430''>region.</span> <span m=''4034200''>So</span>
  <span m=''4034690''>this</span> <span m=''4034840''>is</span> <span m=''4035000''>like</span>
  <span m=''4035290''>our</span> <span m=''4036970''>m-by-m</span> <span m=''4037570''>QAM,</span>
  <span m=''4038280''>or</span> <span m=''4038450''>it</span> <span m=''4038510''>might</span>
  <span m=''4038740''>be</span> <span m=''4038890''>this</span> <span m=''4039160''>guy,</span>
  <span m=''4039410''>which</span> <span m=''4039650''>is</span> <span m=''4039900''>better</span>
  <span m=''4040230''>than</span> <span m=''4040410''>16-QAM,</span> <span m=''4042530''>in</span>
  <span m=''4042650''>some</span> <span m=''4043320''>sense.</span> <span m=''4044930''>In</span>
  <span m=''4045380''>two</span> <span m=''4045660''>senses,</span> <span m=''4046270''>actually.</span>
  </p><p><span m=''4049440''>The</span> <span m=''4049550''>union-bound</span> <span
  m=''4050110''>estimate,</span> <span m=''4051180''>what</span> <span m=''4051420''>is</span>
  <span m=''4051590''>it?</span> <span m=''4054310''>The</span> <span m=''4054750''>probability</span>
  <span m=''4055520''>of</span> <span m=''4055620''>error</span> <span m=''4056000''>is</span>
  <span m=''4056130''>approximately</span> <span m=''4056960''>equal</span> <span
  m=''4057350''>to--</span> <span m=''4060280''>let</span> <span m=''4060390''>me</span>
  <span m=''4060530''>do</span> <span m=''4060750''>it</span> <span m=''4060900''>per</span>
  <span m=''4061130''>block.</span> <span m=''4061910''>So</span> <span m=''4062210''>I''ll</span>
  <span m=''4062270''>have</span> <span m=''4062470''>the</span> <span m=''4062570''>number</span>
  <span m=''4062880''>of</span> <span m=''4063000''>nearest</span> <span m=''4063450''>neighbors</span>
  <span m=''4064050''>per</span> <span m=''4064290''>block</span> <span m=''4065772''>of</span>
  <span m=''4066120''>our</span> <span m=''4066490''>constellation times</span> <span
  m=''4071920''>Q</span> <span m=''4072330''>to</span> <span m=''4072500''>the</span>
  <span m=''4072590''>square</span> <span m=''4073090''>root</span> <span m=''4073450''>of</span>
  <span m=''4074650''>d_min-squared</span> <span m=''4075740''>of</span> <span m=''4075860''>our</span>
  <span m=''4076050''>constellation,</span> <span m=''4077890''>over</span> <span
  m=''4078450''>what</span> <span m=''4078630''>is</span> <span m=''4078810''>it?</span>
  <span m=''4078960''>4</span> <span m=''4079360''>sigma</span> <span m=''4079710''>squared?</span>
  <span m=''4085930''>4</span> <span m=''4086180''>sigma</span> <span m=''4086550''>squared.</span>
  </p><p><span m=''4095600''>And</span> <span m=''4096050''>if</span> <span m=''4096130''>you</span>
  <span m=''4096310''>remember</span> <span m=''4096689''>how</span> <span m=''4096819''>we</span>
  <span m=''4096950''>got</span> <span m=''4097250''>this,</span> <span m=''4097680''>we</span>
  <span m=''4098770''>took</span> <span m=''4098979''>the</span> <span m=''4099350''>union-bound,</span>
  <span m=''4099859''>we</span> <span m=''4099979''>took</span> <span m=''4100189''>all</span>
  <span m=''4100359''>the</span> <span m=''4100430''>pairwise</span> <span m=''4101060''>error</span>
  <span m=''4101310''>probabilities,</span> <span m=''4103490''>and</span> <span m=''4103950''>from</span>
  <span m=''4104130''>that,</span> <span m=''4104460''>we</span> <span m=''4104609''>get</span>
  <span m=''4105010''>contributions</span> <span m=''4105920''>from</span> <span m=''4108279''>kd</span>
  <span m=''4109149''>at</span> <span m=''4109240''>every</span> <span m=''4110550''>kd</span>
  <span m=''4110960''>contributions</span> <span m=''4111355''>at</span> <span m=''4111830''>distance</span>
  <span m=''4112490''>d.</span> <span m=''4113380''>We</span> <span m=''4113880''>added</span>
  <span m=''4114100''>them</span> <span m=''4114240''>all</span> <span m=''4114399''>up</span>
  <span m=''4114590''>in</span> <span m=''4114635''>the</span> <span m=''4114680''>union-bound.</span>
  <span m=''4115340''>We</span> <span m=''4115450''>said,</span> <span m=''4115680''>well,</span>
  <span m=''4117250''>for</span> <span m=''4117399''>moderate</span> <span m=''4118200''>complexity</span>
  <span m=''4118930''>and</span> <span m=''4119029''>performance,</span> <span m=''4119710''>at</span>
  <span m=''4119779''>least</span> <span m=''4120109''>this</span> <span m=''4120290''>is</span>
  <span m=''4120430''>going</span> <span m=''4120540''>to</span> <span m=''4120580''>be</span>
  <span m=''4120700''>dominated</span> <span m=''4121300''>by</span> <span m=''4121450''>the</span>
  <span m=''4121569''>minimum</span> <span m=''4121920''>distance.</span> <span m=''4122920''>So</span>
  <span m=''4123189''>this</span> <span m=''4123390''>is</span> <span m=''4123580''>the</span>
  <span m=''4124930''>minimum</span> <span m=''4125229''>distance</span> <span m=''4125630''>terms.</span>
  <span m=''4126109''>This</span> <span m=''4126300''>is</span> <span m=''4126450''>the</span>
  <span m=''4126560''>number</span> <span m=''4126930''>of</span> <span m=''4127020''>minimum</span>
  <span m=''4127380''>distance</span> <span m=''4127840''>terms.</span> <span m=''4129310''>And</span>
  <span m=''4129569''>this</span> <span m=''4129800''>is</span> <span m=''4129939''>error</span>
  <span m=''4130359''>probability --</span> <span m=''4130739''>the</span> <span m=''4130790''>pairwise</span>
  <span m=''4131370''>error</span> <span m=''4131649''>probability</span> <span m=''4132140''>we</span>
  <span m=''4132279''>get</span> <span m=''4132540''>for</span> <span m=''4132680''>each</span>
  <span m=''4132920''>minimum</span> <span m=''4133220''>distance</span> <span m=''4133660''>term.</span>
  </p><p><span m=''4140300''>Now,</span> <span m=''4140779''>to</span> <span m=''4141950''>compute</span>
  <span m=''4142470''>this,</span> <span m=''4143970''>I''m</span> <span m=''4144100''>going</span>
  <span m=''4144250''>to</span> <span m=''4144340''>use</span> <span m=''4146880''>three</span>
  <span m=''4147200''>approximations,</span> <span m=''4148579''>but</span> <span
  m=''4148939''>two</span> <span m=''4149120''>important</span> <span m=''4149580''>ones,</span>
  <span m=''4152120''>this</span> <span m=''4152390''>continuous</span> <span m=''4153060''>approximation</span>
  <span m=''4153400''>that</span> <span m=''4153740''>I''ve</span> <span m=''4154080''>already</span>
  <span m=''4154580''>referred</span> <span m=''4155069''>to.</span> <span m=''4158670''>First,</span>
  <span m=''4159250''>I''m</span> <span m=''4159350''>going</span> <span m=''4159479''>to</span>
  <span m=''4159569''>say</span> <span m=''4160630''>that</span> <span m=''4160819''>the</span>
  <span m=''4161020''>average</span> <span m=''4161950''>power</span> <span m=''4164700''>of</span>
  <span m=''4164960''>my</span> <span m=''4165140''>constellation</span> <span m=''4169120''>is</span>
  <span m=''4169560''>approximately</span> <span m=''4170300''>equal</span> <span
  m=''4170689''>to</span> <span m=''4171950''>just</span> <span m=''4172790''>the</span>
  <span m=''4172930''>second</span> <span m=''4173470''>moment</span> <span m=''4174509''>of</span>
  <span m=''4174859''>R.</span> <span m=''4177240''>The</span> <span m=''4177590''>average</span>
  <span m=''4177939''>energy</span> <span m=''4178680''>per</span> <span m=''4178979''>dimension</span>
  <span m=''4179510''>of</span> <span m=''4179640''>R.</span> </p><p><span m=''4186609''>And</span>
  <span m=''4186760''>then</span> <span m=''4186899''>I''m</span> <span m=''4187029''>going</span>
  <span m=''4187160''>to</span> <span m=''4187279''>say,</span> <span m=''4189170''>furthermore,</span>
  <span m=''4189910''>how</span> <span m=''4190100''>many</span> <span m=''4190310''>points</span>
  <span m=''4191080''>are</span> <span m=''4191200''>there</span> <span m=''4191390''>in</span>
  <span m=''4191460''>the</span> <span m=''4191540''>constellation?</span> <span m=''4192279''>This</span>
  <span m=''4192490''>will</span> <span m=''4192700''>affect</span> <span m=''4193130''>what</span>
  <span m=''4193290''>rate</span> <span m=''4193620''>I</span> <span m=''4193700''>can</span>
  <span m=''4193960''>go</span> <span m=''4194370''>at.</span> <span m=''4197300''>The</span>
  <span m=''4197540''>average</span> <span m=''4198020''>number</span> <span m=''4198330''>of</span>
  <span m=''4198430''>points</span> <span m=''4199050''>in</span> <span m=''4199200''>the</span>
  <span m=''4199290''>constellation --</span> <span m=''4201350''>also</span> <span
  m=''4201730''>mention</span> <span m=''4202150''>this--</span> <span m=''4203110''>is</span>
  <span m=''4203250''>going</span> <span m=''4203350''>to</span> <span m=''4203450''>be</span>
  <span m=''4203610''>approximately</span> <span m=''4204490''>equal</span> <span
  m=''4204850''>to</span> <span m=''4205830''>simply</span> <span m=''4206520''>the</span>
  <span m=''4207630''>volume</span> <span m=''4208230''>of</span> <span m=''4208470''>my</span>
  <span m=''4208640''>bounding</span> <span m=''4209190''>region,</span> <span m=''4209890''>V(R),</span>
  <span m=''4211750''>over</span> <span m=''4212330''>the</span> <span m=''4213240''>volume</span>
  <span m=''4213850''>taken</span> <span m=''4214160''>up</span> <span m=''4214330''>by</span>
  <span m=''4214480''>each</span> <span m=''4214800''>point</span> <span m=''4215310''>in</span>
  <span m=''4215550''>my</span> <span m=''4216240''>lattice.</span> </p><p><span m=''4220330''>That</span>
  <span m=''4220440''>makes</span> <span m=''4220710''>sense,</span> <span m=''4221040''>doesn''t</span>
  <span m=''4221240''>it?</span> <span m=''4223590''>What</span> <span m=''4223720''>I</span>
  <span m=''4223750''>want</span> <span m=''4223980''>to</span> <span m=''4224020''>do</span>
  <span m=''4224220''>here</span> <span m=''4224460''>to</span> <span m=''4224510''>get</span>
  <span m=''4224730''>16</span> <span m=''4225180''>points</span> <span m=''4225700''>is</span>
  <span m=''4225970''>I</span> <span m=''4226100''>take</span> <span m=''4226500''>a</span>
  <span m=''4227330''>sphere</span> <span m=''4228580''>whose</span> <span m=''4229600''>area</span>
  <span m=''4229905''>is</span> <span m=''4230210''>roughly</span> <span m=''4230590''>16</span>
  <span m=''4231160''>times</span> <span m=''4231570''>the</span> <span m=''4231710''>area</span>
  <span m=''4232040''>of</span> <span m=''4232220''>one</span> <span m=''4232350''>of</span>
  <span m=''4232390''>these</span> <span m=''4232590''>little</span> <span m=''4232760''>hexagons</span>
  <span m=''4233400''>or</span> <span m=''4233540''>one</span> <span m=''4233670''>of</span>
  <span m=''4233710''>these</span> <span m=''4233930''>little</span> <span m=''4234770''>parallelograms.</span>
  <span m=''4235910''>And</span> <span m=''4236040''>I''ll</span> <span m=''4236190''>get</span>
  <span m=''4236580''>about</span> <span m=''4236860''>16</span> <span m=''4237280''>points,</span>
  <span m=''4238840''>because</span> <span m=''4239310''>that''s</span> <span m=''4239840''>the</span>
  <span m=''4239950''>density</span> <span m=''4240500''>of</span> <span m=''4240600''>it.</span>
  </p><p><span m=''4243200''>And</span> <span m=''4244060''>there''s</span> <span
  m=''4244240''>a</span> <span m=''4244290''>final little</span> <span m=''4244870''>approximation,</span>
  <span m=''4245840''>which</span> <span m=''4246120''>is</span> <span m=''4246350''>that</span>
  <span m=''4248400''>I''m</span> <span m=''4248420''>going</span> <span m=''4248440''>to</span>
  <span m=''4248460''>assume</span> <span m=''4248900''>that</span> <span m=''4249340''>we''re</span>
  <span m=''4249500''>somewhere</span> <span m=''4249870''>in</span> <span m=''4249950''>the</span>
  <span m=''4250080''>interior</span> <span m=''4250540''>of</span> <span m=''4250710''>the</span>
  <span m=''4250880''>lattice,</span> <span m=''4251230''>so</span> <span m=''4251420''>that</span>
  <span m=''4251505''>the</span> <span m=''4251590''>average</span> <span m=''4252110''>number</span>
  <span m=''4252600''>of</span> <span m=''4255030''>nearest</span> <span m=''4255450''>neighbors</span>
  <span m=''4255960''>in</span> <span m=''4256050''>the</span> <span m=''4256130''>constellation</span>
  <span m=''4257040''>is</span> <span m=''4257120''>simply</span> <span m=''4257560''>equal</span>
  <span m=''4257890''>to</span> <span m=''4258000''>the</span> <span m=''4259480''>number</span>
  <span m=''4259760''>of</span> <span m=''4259860''>nearest</span> <span m=''4260200''>neighbors</span>
  <span m=''4260540''>in</span> <span m=''4260610''>the</span> <span m=''4260690''>lattice.</span>
  <span m=''4261125''>So</span> <span m=''4261560''>that''s</span> <span m=''4261820''>a</span>
  <span m=''4261880''>reasonable</span> <span m=''4262280''>approximation,</span>
  <span m=''4263585''>and</span> <span m=''4263980''>that''s</span> <span m=''4264950''>a</span>
  <span m=''4264990''>very</span> <span m=''4265200''>obvious</span> <span m=''4265650''>one.</span>
  <span m=''4266310''>If</span> <span m=''4266380''>I</span> <span m=''4266450''>take</span>
  <span m=''4266790''>any</span> <span m=''4267910''>constellation</span> <span m=''4268790''>based</span>
  <span m=''4269190''>on</span> <span m=''4269280''>the</span> <span m=''4269330''>hexagonal</span>
  <span m=''4269960''>lattice,</span> <span m=''4270820''>for</span> <span m=''4270915''>a</span>
  <span m=''4271010''>large</span> <span m=''4271320''>enough</span> <span m=''4271510''>constellation,</span>
  <span m=''4272230''>the</span> <span m=''4272360''>average</span> <span m=''4272720''>number</span>
  <span m=''4272980''>of</span> <span m=''4273070''>nearest</span> <span m=''4273430''>neighbors</span>
  <span m=''4273570''>is</span> <span m=''4273710''>going</span> <span m=''4273790''>to</span>
  <span m=''4273870''>be</span> <span m=''4273950''>6.</span> <span m=''4275490''>If</span>
  <span m=''4275535''>I</span> <span m=''4275580''>take</span> <span m=''4275870''>it</span>
  <span m=''4275980''>on</span> <span m=''4276230''>the</span> <span m=''4276610''>square</span>
  <span m=''4277010''>lattice,</span> <span m=''4277480''>the</span> <span m=''4277590''>average</span>
  <span m=''4277830''>number</span> <span m=''4278040''>of</span> <span m=''4278110''>nearest</span>
  <span m=''4278450''>neighbors</span> <span m=''4278760''>is</span> <span m=''4278792''>going</span>
  <span m=''4278825''>to</span> <span m=''4278857''>be</span> <span m=''4278890''>4.</span>
  </p><p><span m=''4279990''>But</span> <span m=''4280490''>we</span> <span m=''4280770''>know</span>
  <span m=''4281940''>we''re</span> <span m=''4282100''>not</span> <span m=''4282850''>terribly</span>
  <span m=''4283290''>interested</span> <span m=''4283620''>in</span> <span m=''4283720''>that</span>
  <span m=''4285010''>either.</span> <span m=''4288730''>Let</span> <span m=''4289140''>me</span>
  <span m=''4289270''>do</span> <span m=''4289440''>a</span> <span m=''4289510''>little</span>
  <span m=''4289720''>manipulation</span> <span m=''4290560''>here.</span> <span m=''4293490''>I''m</span>
  <span m=''4293570''>going</span> <span m=''4293680''>to</span> <span m=''4293720''>write</span>
  <span m=''4294040''>this</span> <span m=''4294480''>as</span> <span m=''4294900''>Q</span>
  <span m=''4295390''>of</span> <span m=''4296710''>d_min-squared</span> <span m=''4299430''>of</span>
  <span m=''4302360''>c,</span> <span m=''4302960''>which</span> <span m=''4305000''>clearly</span>
  <span m=''4305480''>I''m</span> <span m=''4305650''>going</span> <span m=''4305870''>to</span>
  <span m=''4306180''>also</span> <span m=''4306640''>assume</span> <span m=''4306920''>that</span>
  <span m=''4307690''>d_min-squared of c</span> <span m=''4309600''>is</span> <span
  m=''4309840''>equal</span> <span m=''4310250''>to</span> <span m=''4311100''>d_min-squared</span>
  <span m=''4311830''>of</span> <span m=''4311970''>the</span> <span m=''4312110''>lattice.</span>
  <span m=''4313460''>So</span> <span m=''4313760''>I''ll</span> <span m=''4313870''>make</span>
  <span m=''4314110''>that</span> <span m=''4314580''>d_min-squared</span> <span m=''4315400''>of</span>
  <span m=''4315500''>the</span> <span m=''4315600''>lattice.</span> <span m=''4318810''>And</span>
  <span m=''4319520''>I</span> <span m=''4319550''>want</span> <span m=''4319700''>to</span>
  <span m=''4319860''>normalize</span> <span m=''4320590''>that</span> <span m=''4320930''>by</span>
  <span m=''4321160''>v</span> <span m=''4321415''>of</span> <span m=''4321670''>lambda,</span>
  <span m=''4324865''>to</span> <span m=''4325160''>the</span> <span m=''4325880''>2/n,</span>
  <span m=''4327670''>whatever</span> <span m=''4328245''>dimension</span> <span m=''4328920''>n</span>
  <span m=''4329180''>I''m</span> <span m=''4329290''>in,</span> <span m=''4330650''>to</span>
  <span m=''4330800''>get</span> <span m=''4331070''>something</span> <span m=''4332045''>that</span>
  <span m=''4332440''>we''re</span> <span m=''4332620''>familiar</span> <span m=''4333080''>with.</span>
  <span m=''4333450''>So</span> <span m=''4333610''>I</span> <span m=''4333710''>need</span>
  <span m=''4333820''>a</span> <span m=''4333940''>V(n)</span> <span m=''4334730''>over</span>
  <span m=''4335030''>2</span> <span m=''4335350''>to</span> <span m=''4335510''>the</span>
  <span m=''4335670''>n.</span> </p><p><span m=''4337010''>And</span> <span m=''4339830''>anticipating</span>
  <span m=''4340660''>a</span> <span m=''4340730''>little,</span> <span m=''4340940''>I''m</span>
  <span m=''4341410''>going</span> <span m=''4341780''>to</span> <span m=''4342100''>put</span>
  <span m=''4342340''>a</span> <span m=''4342580''>V(R)</span> <span m=''4343180''>over</span>
  <span m=''4343305''>2</span> <span m=''4343430''>to</span> <span m=''4343655''>the</span>
  <span m=''4343880''>n.</span> <span m=''4345864''>And</span> <span m=''4346360''>then</span>
  <span m=''4346750''>over</span> <span m=''4346980''>here,</span> <span m=''4347640''>I''m</span>
  <span m=''4347730''>going</span> <span m=''4347880''>to</span> <span m=''4347950''>put</span>
  <span m=''4348720''>V(R)</span> <span m=''4350380''>over--</span> <span m=''4352035''>Is</span>
  <span m=''4352450''>this</span> <span m=''4352476''>going</span> <span m=''4352503''>to</span>
  <span m=''4352530''>come</span> <span m=''4352750''>out</span> <span m=''4352855''>right?--</span>
  <span m=''4353450''>over</span> <span m=''4354160''>2</span> <span m=''4354380''>to</span>
  <span m=''4354535''>the</span> <span m=''4354690''>n,</span> <span m=''4356650''>over--</span>
  <span m=''4358980''>this</span> <span m=''4359130''>seems</span> <span m=''4359450''>upside-down.</span>
  <span m=''4380100''>Ah,</span> <span m=''4380410''>no,</span> <span m=''4380720''>it</span>
  <span m=''4380990''>isn''t</span> <span m=''4381280''>upside-down.</span> <span
  m=''4385960''>Because</span> <span m=''4387540''>I''m</span> <span m=''4387700''>using</span>
  <span m=''4388330''>this</span> <span m=''4388640''>expression</span> <span m=''4389320''>here,</span>
  <span m=''4390480''>I</span> <span m=''4390560''>do</span> <span m=''4390770''>want</span>
  <span m=''4391130''>1 over G(R).</span> </p><p><span m=''4396340''>So</span> <span
  m=''4396660''>this</span> <span m=''4397840''>is</span> <span m=''4398160''>1 over
  G(R).</span> <span m=''4400450''>If</span> <span m=''4400760''>I</span> <span m=''4401410''>multiply</span>
  <span m=''4401940''>this</span> <span m=''4402300''>by</span> <span m=''4403660''>1/12,</span>
  <span m=''4407400''>now</span> <span m=''4407520''>I</span> <span m=''4407760''>get</span>
  <span m=''4407890''>1 over G(R),</span> <span m=''4408780''>so</span> <span m=''4409100''>I</span>
  <span m=''4409170''>need</span> <span m=''4409240''>to</span> <span m=''4409310''>put</span>
  <span m=''4409700''>a</span> <span m=''4410710''>1/12</span> <span m=''4412050''>here.</span>
  <span m=''4414440''>And</span> <span m=''4415112''>then</span> <span m=''4415450''>I</span>
  <span m=''4415900''>have</span> <span m=''4416080''>a</span> <span m=''4417480''>P(R)</span>
  <span m=''4419400''>over</span> <span m=''4419880''>4</span> <span m=''4421430''>sigma</span>
  <span m=''4421850''>squared.</span> <span m=''4424810''>So</span> <span m=''4425100''>does</span>
  <span m=''4425220''>everyone</span> <span m=''4425470''>agree</span> <span m=''4425760''>I</span>
  <span m=''4425840''>can</span> <span m=''4425990''>write</span> <span m=''4426170''>it</span>
  <span m=''4426300''>that</span> <span m=''4426540''>way?</span> <span m=''4430260''>This''ll</span>
  <span m=''4430460''>be</span> <span m=''4430600''>good.</span> <span m=''4432280''>Go</span>
  <span m=''4432720''>out</span> <span m=''4433160''>with</span> <span m=''4433220''>a</span>
  <span m=''4433280''>bang.</span> </p><p><span m=''4436200''>So</span> <span m=''4436590''>what</span>
  <span m=''4436820''>are</span> <span m=''4437080''>all</span> <span m=''4437220''>these</span>
  <span m=''4437480''>things?</span> <span m=''4439220''>This</span> <span m=''4439720''>is</span>
  <span m=''4441920''>the</span> <span m=''4442620''>coding</span> <span m=''4443010''>gain</span>
  <span m=''4443530''>of</span> <span m=''4443690''>lambda.</span> <span m=''4446860''>This,</span>
  <span m=''4447740''>according</span> <span m=''4448170''>to</span> <span m=''4448320''>this,</span>
  <span m=''4448860''>is</span> <span m=''4449250''>the</span> <span m=''4450370''>size</span>
  <span m=''4450970''>of</span> <span m=''4451060''>the</span> <span m=''4451160''>constellation</span>
  <span m=''4453090''>to</span> <span m=''4453220''>the</span> <span m=''4453340''>2
  over n,</span> <span m=''4454430''>approximately.</span> <span m=''4455960''>The</span>
  <span m=''4456440''>rate</span> <span m=''4456980''>of</span> <span m=''4457080''>the</span>
  <span m=''4457200''>constellation</span> <span m=''4459330''>is</span> <span m=''4460830''>log</span>
  <span m=''4461290''>2</span> <span m=''4461710''>times</span> <span m=''4462130''>the</span>
  <span m=''4462220''>size</span> <span m=''4463810''>of</span> <span m=''4463900''>lambda,
  R.</span> <span m=''4466510''>So</span> <span m=''4467970''>the</span> <span m=''4468100''>rate</span>
  <span m=''4468540''>is</span> <span m=''4469500''>equal</span> <span m=''4469960''>to</span>
  <span m=''4470410''>just</span> <span m=''4472020''>log</span> <span m=''4472350''>2</span>
  <span m=''4472600''>of</span> <span m=''4472860''>this</span> <span m=''4473330''>quantity.</span>
  <span m=''4476450''>So</span> <span m=''4477540''>I</span> <span m=''4477650''>can</span>
  <span m=''4477770''>say</span> <span m=''4478170''>2</span> <span m=''4478380''>to</span>
  <span m=''4478520''>the</span> <span m=''4478660''>R.</span> <span m=''4479530''>This</span>
  <span m=''4479770''>is</span> <span m=''4479920''>2</span> <span m=''4480190''>to</span>
  <span m=''4480280''>the</span> <span m=''4480370''>R</span> <span m=''4480740''>equals</span>
  <span m=''4481240''>this.</span> <span m=''4482680''>So</span> <span m=''4482830''>this</span>
  <span m=''4483100''>would</span> <span m=''4483270''>be</span> <span m=''4484990''>2</span>
  <span m=''4485690''>to</span> <span m=''4486020''>the</span> <span m=''4490620''>2
  over n,</span> <span m=''4491980''>2R over n.</span> <span m=''4494780''>Is</span>
  <span m=''4495260''>that</span> <span m=''4495520''>right?</span> <span m=''4496880''>Again,</span>
  <span m=''4496970''>I''m</span> <span m=''4498230''>unsure</span> <span m=''4498730''>if</span>
  <span m=''4499210''>that''s</span> <span m=''4499580''>what</span> <span m=''4499720''>I</span>
  <span m=''4499770''>want.</span> </p><p><span m=''4500280''>This</span> <span m=''4500580''>is</span>
  <span m=''4501680''>the</span> <span m=''4501860''>shaping</span> <span m=''4502410''>gain</span>
  <span m=''4502890''>of</span> <span m=''4503160''>the</span> <span m=''4503660''>region,</span>
  <span m=''4505610''>these</span> <span m=''4505900''>three</span> <span m=''4506160''>things</span>
  <span m=''4506680''>together,</span> <span m=''4510600''>times</span> <span m=''4511340''>3,</span>
  <span m=''4512110''>times--</span> <span m=''4512510''>what''s</span> <span m=''4512790''>P(R)</span>
  <span m=''4513470''>over</span> <span m=''4513690''>sigma</span> <span m=''4514040''>squared?</span>
  <span m=''4514440''>That''s</span> <span m=''4514680''>the</span> <span m=''4514800''>SNR.</span>
  <span m=''4515960''>That''s</span> <span m=''4516240''>the</span> <span m=''4516400''>average</span>
  <span m=''4516760''>power</span> <span m=''4517150''>per</span> <span m=''4517760''>dimension.</span>
  <span m=''4519130''>And</span> <span m=''4519220''>this</span> <span m=''4519420''>is</span>
  <span m=''4519550''>the</span> <span m=''4519680''>average</span> <span m=''4519990''>noise</span>
  <span m=''4520300''>power</span> <span m=''4520600''>per</span> <span m=''4520790''>dimension.</span>
  <span m=''4524230''>I''ve</span> <span m=''4524390''>used</span> <span m=''4524750''>up</span>
  <span m=''4525000''>these</span> <span m=''4525530''>in</span> <span m=''4525760''>that.</span>
  <span m=''4526740''>So</span> <span m=''4526940''>I''ve</span> <span m=''4527120''>got</span>
  <span m=''4527230''>a</span> <span m=''4527340''>1</span> <span m=''4527560''>over</span>
  <span m=''4527790''>1/12.</span> <span m=''4528530''>That''s</span> <span m=''4528780''>12</span>
  <span m=''4529140''>times</span> <span m=''4529560''>that.</span> <span m=''4529890''>So</span>
  <span m=''4530030''>this</span> <span m=''4530280''>is</span> <span m=''4531060''>3</span>
  <span m=''4531500''>times</span> <span m=''4531950''>SNR.</span> </p><p><span m=''4535340''>And</span>
  <span m=''4537720''>let''s</span> <span m=''4537990''>see.</span> <span m=''4539200''>This</span>
  <span m=''4539520''>is</span> <span m=''4542340''>2R over n</span> <span m=''4543570''>is</span>
  <span m=''4543890''>just</span> <span m=''4544150''>2</span> <span m=''4544370''>to</span>
  <span m=''4544760''>the--</span> </p><p><span m=''4545657''>AUDIENCE: Isn''t</span>
  <span m=''4545890''>that</span> <span m=''4546124''>just</span> <span m=''4546357''>2R?</span>
  <span m=''4547525''>Because</span> <span m=''4547992''>[UNINTELLIGIBLE]</span> <span
  m=''4548459''>normalized</span> <span m=''4548926''>by</span> <span m=''4549163''>the</span>
  <span m=''4549400''>dimension.</span> </p><p><span m=''4549753''>PROFESSOR: Yeah.</span>
  <span m=''4558320''>And</span> <span m=''4561800''>furthermore,</span> <span m=''4562370''>it''s</span>
  <span m=''4562520''>minus,</span> <span m=''4563640''>because</span> <span m=''4564050''>it''s</span>
  <span m=''4564870''>upside-down.</span> <span m=''4565830''>So</span> <span m=''4566170''>it''s</span>
  <span m=''4568010''>2</span> <span m=''4568220''>to</span> <span m=''4568290''>the</span>
  <span m=''4568840''>- 2R.</span> <span m=''4571480''>Actually,</span> <span m=''4571850''>what</span>
  <span m=''4572040''>I</span> <span m=''4572090''>want</span> <span m=''4572500''>is</span>
  <span m=''4572820''>the</span> <span m=''4573020''>spectral</span> <span m=''4573560''>efficiency.</span>
  <span m=''4575360''>And</span> <span m=''4575910''>the</span> <span m=''4576020''>spectral</span>
  <span m=''4576510''>efficiency</span> <span m=''4577340''>is</span> <span m=''4578360''>the</span>
  <span m=''4578540''>rate</span> <span m=''4578930''>per</span> <span m=''4579330''>two</span>
  <span m=''4579510''>dimensions.</span> <span m=''4581330''>So</span> <span m=''4581560''>this</span>
  <span m=''4581810''>is</span> <span m=''4581940''>just</span> <span m=''4582340''>2</span>
  <span m=''4582580''>to</span> <span m=''4582650''>the</span> <span m=''4582720''>minus</span>
  <span m=''4583160''>rho.</span> <span m=''4590060''>So</span> <span m=''4590320''>with</span>
  <span m=''4590426''>a</span> <span m=''4590533''>little</span> <span m=''4590640''>help</span>
  <span m=''4590990''>for</span> <span m=''4591100''>my</span> <span m=''4591250''>friends,</span>
  <span m=''4593070''>what''s</span> <span m=''4593250''>SNR</span> <span m=''4594030''>over</span>
  <span m=''4594260''>2</span> <span m=''4594460''>to</span> <span m=''4594540''>the</span>
  <span m=''4594650''>rho?</span> </p><p><span m=''4599320''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''4599780''>PROFESSOR: It''s</span> <span m=''4600240''>approximately</span>
  <span m=''4600890''>SNR</span> <span m=''4601370''>norm.</span> <span m=''4602210''>Certainly</span>
  <span m=''4602600''>true</span> <span m=''4602900''>as</span> <span m=''4603060''>row</span>
  <span m=''4603320''>becomes</span> <span m=''4603770''>large.</span> <span m=''4604960''>It''s</span>
  <span m=''4605070''>actually</span> <span m=''4605510''>SNR</span> <span m=''4606100''>over</span>
  <span m=''4606260''>2</span> <span m=''4606470''>to</span> <span m=''4606563''>the</span>
  <span m=''4606656''>rho</span> <span m=''4606750''>minus</span> <span m=''4607150''>1.</span>
  <span m=''4608320''>So</span> <span m=''4608620''>this</span> <span m=''4608860''>is</span>
  <span m=''4610580''>SNR</span> <span m=''4610690''>norm.</span> <span m=''4613890''>OK,</span>
  <span m=''4614360''>so</span> <span m=''4614800''>with</span> <span m=''4615240''>a</span>
  <span m=''4615260''>little</span> <span m=''4615530''>hand</span> <span m=''4615780''>waving</span>
  <span m=''4616340''>and</span> <span m=''4616470''>a</span> <span m=''4616520''>few</span>
  <span m=''4617790''>high</span> <span m=''4618050''>SNR</span> <span m=''4618830''>approximations,</span>
  <span m=''4621400''>we</span> <span m=''4621590''>get</span> <span m=''4623265''>that,</span>
  <span m=''4626950''>in</span> <span m=''4627080''>summary,</span> <span m=''4627690''>for</span>
  <span m=''4627970''>the</span> <span m=''4628210''>UBE,</span> <span m=''4629495''>the</span>
  <span m=''4629960''>probability</span> <span m=''4630520''>of</span> <span m=''4630730''>error</span>
  <span m=''4632410''>is</span> <span m=''4633100''>approximately</span> <span m=''4635440''>K_min(lambda)</span>
  <span m=''4637930''>times</span> <span m=''4638660''>Q</span> <span m=''4639060''>to</span>
  <span m=''4639230''>the</span> <span m=''4639320''>square</span> <span m=''4639830''>root</span>
  <span m=''4640090''>of</span> <span m=''4641260''>the</span> <span m=''4642500''>coding</span>
  <span m=''4642860''>gain</span> <span m=''4643260''>of</span> <span m=''4643490''>the</span>
  <span m=''4643600''>lattice,</span> <span m=''4644880''>times the</span> <span m=''4645110''>shaping</span>
  <span m=''4645680''>gain</span> <span m=''4647070''>of</span> <span m=''4649180''>the</span>
  <span m=''4649320''>region,</span> <span m=''4651650''>times</span> <span m=''4654810''>3SNR</span>
  <span m=''4655640''>norm.</span> <span m=''4660860''>And</span> <span m=''4661060''>that''s</span>
  <span m=''4661300''>a</span> <span m=''4661360''>wonderful</span> <span m=''4661820''>approximation.</span>
  </p><p><span m=''4665590''>Let</span> <span m=''4665690''>me</span> <span m=''4665820''>just</span>
  <span m=''4666490''>call</span> <span m=''4666800''>out</span> <span m=''4667070''>some</span>
  <span m=''4667220''>of</span> <span m=''4667300''>its</span> <span m=''4667440''>properties</span>
  <span m=''4667960''>to</span> <span m=''4668140''>you,</span> <span m=''4668300''>and</span>
  <span m=''4668380''>then</span> <span m=''4668460''>we''ll</span> <span m=''4668590''>talk</span>
  <span m=''4668890''>about</span> <span m=''4669190''>them</span> <span m=''4669900''>next</span>
  <span m=''4670210''>time.</span> <span m=''4672550''>But</span> <span m=''4673000''>first</span>
  <span m=''4673390''>of</span> <span m=''4673460''>all,</span> <span m=''4674170''>there''s</span>
  <span m=''4674380''>nothing</span> <span m=''4674660''>here--</span> <span m=''4675450''>all</span>
  <span m=''4675690''>these</span> <span m=''4675940''>terms</span> <span m=''4676330''>involve</span>
  <span m=''4676820''>either</span> <span m=''4677080''>lambda</span> <span m=''4677660''>or</span>
  <span m=''4677900''>R.</span> <span m=''4679330''>So</span> <span m=''4679450''>we</span>
  <span m=''4679570''>have</span> <span m=''4679790''>completely</span> <span m=''4680300''>separated,</span>
  <span m=''4682210''>in</span> <span m=''4682400''>this</span> <span m=''4682620''>analysis,</span>
  <span m=''4683420''>the</span> <span m=''4683540''>effects</span> <span m=''4684110''>of</span>
  <span m=''4684420''>the</span> <span m=''4685190''>region</span> <span m=''4685740''>from</span>
  <span m=''4685910''>the</span> <span m=''4686030''>effects</span> <span m=''4686480''>of</span>
  <span m=''4686570''>the</span> <span m=''4686660''>lattice.</span> <span m=''4687180''>We</span>
  <span m=''4687300''>can</span> <span m=''4687450''>choose</span> <span m=''4688080''>the</span>
  <span m=''4688180''>lattice</span> <span m=''4689190''>and</span> <span m=''4689360''>the</span>
  <span m=''4689430''>region</span> <span m=''4689820''>independently.</span> <span
  m=''4692240''>And</span> <span m=''4692490''>they</span> <span m=''4693820''>independently</span>
  <span m=''4694520''>affect</span> <span m=''4695130''>how</span> <span m=''4695320''>good</span>
  <span m=''4695510''>a</span> <span m=''4695560''>performance</span> <span m=''4696170''>we</span>
  <span m=''4696310''>get.</span> <span m=''4698810''>For</span> <span m=''4700136''>the</span>
  <span m=''4700480''>baseline,</span> <span m=''4702730''>which</span> <span m=''4703210''>was</span>
  <span m=''4703370''>either</span> <span m=''4703650''>m-PAM</span> <span m=''4704290''>or</span>
  <span m=''4704700''>m-by-m</span> <span m=''4705410''>QAM,</span> <span m=''4706090''>we</span>
  <span m=''4706260''>have,</span> <span m=''4707320''>for</span> <span m=''4707820''>the</span>
  <span m=''4708370''>baseline</span> <span m=''4709830''>PAM</span> <span m=''4709990''>or</span>
  <span m=''4710420''>QAM,</span> <span m=''4712250''>we''ve</span> <span m=''4712660''>set</span>
  <span m=''4713000''>it</span> <span m=''4713095''>up</span> <span m=''4713190''>so</span>
  <span m=''4713430''>that</span> <span m=''4713680''>both</span> <span m=''4714160''>the</span>
  <span m=''4717280''>coding</span> <span m=''4717720''>gain</span> <span m=''4717773''>of</span>
  <span m=''4717826''>the</span> <span m=''4717880''>lattice</span> <span m=''4718490''>and</span>
  <span m=''4718560''>the</span> <span m=''4718630''>shaping</span> <span m=''4719110''>gain</span>
  <span m=''4719280''>of</span> <span m=''4719365''>the</span> <span m=''4719450''>region</span>
  <span m=''4719860''>are</span> <span m=''4719950''>equal</span> <span m=''4720190''>to</span>
  <span m=''4720250''>1.</span> </p><p><span m=''4721330''>So</span> <span m=''4721670''>for</span>
  <span m=''4721800''>the</span> <span m=''4721890''>baseline,</span> <span m=''4723800''>this</span>
  <span m=''4724060''>gives</span> <span m=''4724400''>us</span> <span m=''4724610''>what</span>
  <span m=''4724840''>we</span> <span m=''4725040''>already</span> <span m=''4725340''>developed</span>
  <span m=''4725980''>back</span> <span m=''4726310''>in</span> <span m=''4726450''>the</span>
  <span m=''4726630''>early</span> <span m=''4727210''>stages.</span> <span m=''4729250''>I</span>
  <span m=''4729340''>won''t</span> <span m=''4729560''>worry</span> <span m=''4729790''>about</span>
  <span m=''4730110''>this --</span> <span m=''4731130''>Q-hat,</span> <span m=''4732160''>but</span>
  <span m=''4732460''>it</span> <span m=''4732580''>does</span> <span m=''4732830''>give</span>
  <span m=''4733010''>you</span> <span m=''4733100''>the</span> <span m=''4733200''>right</span>
  <span m=''4733480''>coefficient</span> <span m=''4734060''>out</span> <span m=''4734200''>here,</span>
  <span m=''4734430''>too,</span> <span m=''4735780''>depending</span> <span m=''4736180''>on</span>
  <span m=''4736270''>whether</span> <span m=''4736480''>you</span> <span m=''4736560''>normalize</span>
  <span m=''4737220''>it</span> <span m=''4737390''>per</span> <span m=''4738280''>two</span>
  <span m=''4738440''>dimensions</span> <span m=''4739110''>or</span> <span m=''4739200''>what.</span>
  <span m=''4739960''>It</span> <span m=''4740110''>just</span> <span m=''4740350''>gives</span>
  <span m=''4740550''>you</span> <span m=''4741340''>Q</span> <span m=''4741600''>to</span>
  <span m=''4741645''>the</span> <span m=''4741690''>square</span> <span m=''4742070''>root</span>
  <span m=''4742280''>of</span> <span m=''4742380''>3SNR</span> <span m=''4743170''>norm,</span>
  <span m=''4744850''>which</span> <span m=''4745250''>I</span> <span m=''4745380''>hope</span>
  <span m=''4745570''>you</span> <span m=''4745690''>remember</span> <span m=''4746130''>from</span>
  <span m=''4746310''>chapter</span> <span m=''4746730''>five.</span> <span m=''4747590''>So</span>
  <span m=''4747830''>this</span> <span m=''4748030''>is</span> <span m=''4748250''>our</span>
  <span m=''4748930''>baseline</span> <span m=''4749710''>curve</span> <span m=''4750600''>for</span>
  <span m=''4752260''>m-PAM</span> <span m=''4753450''>or</span> <span m=''4753820''>m-by-m</span>
  <span m=''4754460''>QAM.</span> </p><p><span m=''4755920''>We</span> <span m=''4756050''>just</span>
  <span m=''4757290''>plotted</span> <span m=''4758000''>versus</span> <span m=''4758490''>SNR</span>
  <span m=''4759110''>norm,</span> <span m=''4760200''>the</span> <span m=''4760760''>probability</span>
  <span m=''4761540''>of</span> <span m=''4761650''>error</span> <span m=''4762100''>per</span>
  <span m=''4762400''>two</span> <span m=''4762630''>dimensions,</span> <span m=''4763810''>which</span>
  <span m=''4764120''>is</span> <span m=''4764265''>what</span> <span m=''4764410''>I</span>
  <span m=''4764600''>recommended.</span> <span m=''4765860''>And</span> <span m=''4765990''>we</span>
  <span m=''4766120''>got</span> <span m=''4766370''>some</span> <span m=''4766630''>curve.</span>
  <span m=''4768410''>So</span> <span m=''4768620''>this</span> <span m=''4768810''>is</span>
  <span m=''4768970''>the</span> <span m=''4769500''>baseline.</span> <span m=''4773910''>And</span>
  <span m=''4774090''>now</span> <span m=''4774290''>we''ve</span> <span m=''4774480''>got</span>
  <span m=''4774650''>everything</span> <span m=''4775030''>separated</span> <span
  m=''4775650''>out</span> <span m=''4775900''>in</span> <span m=''4775975''>a</span>
  <span m=''4776050''>nice</span> <span m=''4776400''>way,</span> <span m=''4777390''>so</span>
  <span m=''4777610''>that</span> <span m=''4777830''>if</span> <span m=''4778110''>somebody</span>
  <span m=''4778430''>gives</span> <span m=''4778690''>us</span> <span m=''4778820''>a</span>
  <span m=''4778880''>lattice</span> <span m=''4779440''>with</span> <span m=''4779610''>a</span>
  <span m=''4779660''>certain</span> <span m=''4780000''>coding</span> <span m=''4780350''>gain</span>
  <span m=''4782270''>and</span> <span m=''4782450''>a</span> <span m=''4782500''>region</span>
  <span m=''4782900''>with</span> <span m=''4783020''>a</span> <span m=''4783140''>certain</span>
  <span m=''4783460''>shaping</span> <span m=''4783890''>gain,</span> <span m=''4785280''>those</span>
  <span m=''4785520''>both</span> <span m=''4785770''>just</span> <span m=''4786030''>add</span>
  <span m=''4786260''>up</span> <span m=''4786430''>as</span> <span m=''4786630''>gains.</span>
  </p><p><span m=''4787970''>If</span> <span m=''4788150''>that''s</span> <span m=''4788410''>all</span>
  <span m=''4788600''>we</span> <span m=''4788760''>had,</span> <span m=''4789140''>forget</span>
  <span m=''4789450''>the</span> <span m=''4789550''>coefficient,</span> <span m=''4790730''>we</span>
  <span m=''4790910''>would</span> <span m=''4791040''>just</span> <span m=''4791550''>move</span>
  <span m=''4792670''>to</span> <span m=''4792800''>the</span> <span m=''4792920''>right</span>
  <span m=''4793230''>here,</span> <span m=''4793530''>and</span> <span m=''4793830''>it</span>
  <span m=''4794300''>would</span> <span m=''4794630''>give</span> <span m=''4794790''>us</span>
  <span m=''4794950''>effective</span> <span m=''4795570''>reductions</span> <span
  m=''4796240''>and</span> <span m=''4796330''>the required</span> <span m=''4796900''>SNR</span>
  <span m=''4797450''>norm</span> <span m=''4798260''>by</span> <span m=''4798620''>the</span>
  <span m=''4798980''>coding</span> <span m=''4799300''>gain</span> <span m=''4799680''>of</span>
  <span m=''4799800''>the</span> <span m=''4799920''>lattice</span> <span m=''4800560''>and</span>
  <span m=''4800685''>the</span> <span m=''4800810''>shaping</span> <span m=''4801075''>gain</span>
  <span m=''4801340''>of</span> <span m=''4801530''>the</span> <span m=''4801730''>region.</span>
  <span m=''4803240''>And</span> <span m=''4803510''>we''d</span> <span m=''4803660''>get</span>
  <span m=''4803960''>the</span> <span m=''4804050''>same</span> <span m=''4804450''>curve</span>
  <span m=''4805390''>moved</span> <span m=''4805740''>out</span> <span m=''4805940''>over</span>
  <span m=''4806160''>here.</span> </p><p><span m=''4807340''>Again,</span> <span
  m=''4807800''>as</span> <span m=''4808170''>in</span> <span m=''4808280''>the</span>
  <span m=''4808360''>binary</span> <span m=''4808850''>case,</span> <span m=''4810590''>typically</span>
  <span m=''4811050''>we''re</span> <span m=''4811190''>going</span> <span m=''4811300''>to</span>
  <span m=''4811380''>get</span> <span m=''4811610''>a</span> <span m=''4811690''>larger</span>
  <span m=''4812420''>number</span> <span m=''4812680''>of</span> <span m=''4812760''>near</span>
  <span m=''4812980''>neighbors,</span> <span m=''4814050''>leading</span> <span m=''4814370''>to</span>
  <span m=''4814610''>a</span> <span m=''4814710''>larger</span> <span m=''4815580''>coefficient</span>
  <span m=''4816190''>out</span> <span m=''4816390''>here.</span> <span m=''4817070''>We</span>
  <span m=''4817210''>want</span> <span m=''4817320''>to</span> <span m=''4817440''>normalize</span>
  <span m=''4818010''>this</span> <span m=''4818230''>per</span> <span m=''4818390''>two</span>
  <span m=''4818560''>dimensions.</span> <span m=''4819320''>Per</span> <span m=''4819490''>two</span>
  <span m=''4819650''>dimensions,</span> <span m=''4820260''>it''s</span> <span m=''4820440''>only</span>
  <span m=''4821110''>4</span> <span m=''4821610''>for</span> <span m=''4821770''>the</span>
  <span m=''4821860''>baseline.</span> <span m=''4823080''>But</span> <span m=''4824140''>in</span>
  <span m=''4824290''>general,</span> <span m=''4824670''>we''re</span> <span m=''4824780''>going</span>
  <span m=''4824890''>to</span> <span m=''4824960''>get</span> <span m=''4825240''>a</span>
  <span m=''4825660''>KS</span> <span m=''4826800''>of</span> <span m=''4827210''>lambda,</span>
  <span m=''4827620''>the</span> <span m=''4827940''>number</span> <span m=''4828220''>of</span>
  <span m=''4828310''>nearest</span> <span m=''4828650''>neighbors</span> <span m=''4828970''>per</span>
  <span m=''4829110''>two</span> <span m=''4829260''>dimensions,</span> <span m=''4830260''>which</span>
  <span m=''4830440''>is</span> <span m=''4830590''>going</span> <span m=''4830730''>to</span>
  <span m=''4830810''>raise</span> <span m=''4831160''>this</span> <span m=''4831215''>a</span>
  <span m=''4831270''>little.</span> <span m=''4832690''>And</span> <span m=''4832900''>that</span>
  <span m=''4833090''>will</span> <span m=''4833250''>lower</span> <span m=''4833650''>the</span>
  <span m=''4834490''>effective</span> <span m=''4835140''>coding</span> <span m=''4835520''>gain</span>
  <span m=''4836560''>down</span> <span m=''4836770''>here.</span> </p><p><span m=''4837650''>But</span>
  <span m=''4837780''>we''ve</span> <span m=''4837920''>basically,</span> <span m=''4838920''>by</span>
  <span m=''4839150''>these</span> <span m=''4840420''>large</span> <span m=''4840770''>constellation,</span>
  <span m=''4841610''>high</span> <span m=''4842100''>SNR</span> <span m=''4842350''>approximations,</span>
  <span m=''4843310''>we''ve</span> <span m=''4843910''>really</span> <span m=''4844150''>reduced</span>
  <span m=''4845310''>the</span> <span m=''4845470''>analysis</span> <span m=''4846620''>of</span>
  <span m=''4846750''>lattice</span> <span m=''4847120''>constellations</span> <span
  m=''4848000''>to</span> <span m=''4848130''>a</span> <span m=''4848180''>very</span>
  <span m=''4848450''>simple</span> <span m=''4848840''>task,</span> <span m=''4849380''>just</span>
  <span m=''4849620''>to</span> <span m=''4849890''>analyze</span> <span m=''4852120''>what''s</span>
  <span m=''4852400''>the</span> <span m=''4852570''>coding</span> <span m=''4852640''>gain,</span>
  <span m=''4853250''>what''s</span> <span m=''4853440''>the</span> <span m=''4853530''>shaping</span>
  <span m=''4853785''>gain,</span> <span m=''4854420''>number</span> <span m=''4854690''>of</span>
  <span m=''4854770''>nearest</span> <span m=''4855130''>neighbors,</span> <span m=''4855690''>plot</span>
  <span m=''4855840''>the</span> <span m=''4855990''>performance</span> <span m=''4856610''>curve,</span>
  <span m=''4856990''>end</span> <span m=''4857170''>of</span> <span m=''4857250''>story.</span>
  <span m=''4860020''>So</span> <span m=''4860430''>we''ll</span> <span m=''4860530''>start</span>
  <span m=''4860830''>there</span> <span m=''4861130''>next</span> <span m=''4861280''>time.</span>
  </p>'
type: course
uid: e820ac2029ca835efefcae6ea0b8feb5

---
None