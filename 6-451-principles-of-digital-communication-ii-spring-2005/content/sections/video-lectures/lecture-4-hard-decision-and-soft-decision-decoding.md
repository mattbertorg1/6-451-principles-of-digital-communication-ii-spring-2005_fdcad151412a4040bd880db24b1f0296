---
about_this_resource_text: '<p><strong>Topics covered: </strong>Hard-decision and Soft-decision
  Decoding</p><p><strong>Instructor: </strong>Prof. David Forney</p>'
course_id: 6-451-principles-of-digital-communication-ii-spring-2005
embedded_media:
- id: 4.jpg
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-4-hard-decision-and-soft-decision-decoding/4.jpg
  title: 4.jpg
  type: null
  uid: 454288f3c3c843687d65ce1ddf55317d
- id: Video-YouTube-Stream
  media_location: vXB3QmTg8YQ
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: Video-YouTube-Stream
  type: Video
  uid: c527ffdf0f864883526a0f16de89d094
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/vXB3QmTg8YQ/default.jpg
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: bb4c3814f2f156f0f804c5f66960dd0a
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597857
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: Video-iTunes U-MP4
  type: Video
  uid: b6e8aba02a0b24645dacc2a782af44f1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.451S05/4ocw-6.451_4-261-14feb2005-220k.mp4
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: Video-Internet Archive-MP4
  type: Video
  uid: 158ca8f8f827e9a5f69a65cb70255eb9
- id: 3Play-3PlayYouTubeid-MP4
  media_location: vXB3QmTg8YQ
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 466b8d70536d5426971709db247b7c64
- id: vXB3QmTg8YQ.srt
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-4-hard-decision-and-soft-decision-decoding/vXB3QmTg8YQ.srt
  title: 3play caption file
  type: null
  uid: dedde0fa6016289cac86c6ebe1e08941
- id: vXB3QmTg8YQ.pdf
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-4-hard-decision-and-soft-decision-decoding/vXB3QmTg8YQ.pdf
  title: 3play pdf file
  type: null
  uid: ef73fbc32664b8ff4453efe71f5edaf1
- id: Caption-3Play YouTube id-SRT
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7d247a73c0fe44dc8a8f276ca0bb8732
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c4eb2579c9a4e913ac695873cdaf4c45
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 53a803b45b97934643970cb851246efe
inline_embed_id: 11672667lecture4:hard-decisionandsoft-decisiondecoding56465748
layout: video
order_index: null
parent_uid: 73f9a1c91575f1a3abda44e7358df3a2
related_resources_text: <p>Hard-decision and Soft-decision Decoding (<a href="./resolveuid/9c669af76ebf74ffe46645541f1ff6b3"
  target="_blank" title="Open in a new window.">PDF</a>)</p>
short_url: lecture-4-hard-decision-and-soft-decision-decoding
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-4-hard-decision-and-soft-decision-decoding
template_type: Tabbed
title: 'Lecture 4: Hard-decision and Soft-decision Decoding'
transcript: '<p><span m=''0''>PROFESSOR:</span> <span m=''3880''>So</span> <span m=''5350''>the</span>
  <span m=''5540''>idea</span> <span m=''5850''>behind</span> <span m=''6300''>the</span>
  <span m=''6440''>encoder</span> <span m=''7090''>is</span> <span m=''8890''>increase</span>
  <span m=''13440''>the</span> <span m=''13560''>minimum</span> <span m=''14070''>distance</span>
  <span m=''18190''>at</span> <span m=''18890''>the cost</span> <span m=''19310''>of</span>
  <span m=''22510''>spectral</span> <span m=''23320''>efficiency.</span> <span m=''32170''>The</span>
  <span m=''32299''>idea</span> <span m=''32600''>behind</span> <span m=''32940''>the</span>
  <span m=''33050''>decoder</span> <span m=''36930''>was</span> <span m=''37280''>the</span>
  <span m=''37380''>following.</span> <span m=''38070''>You</span> <span m=''38190''>have</span>
  <span m=''38470''>a</span> <span m=''38610''>received</span> <span m=''39140''>signal,</span>
  <span m=''39820''>y.</span> <span m=''41710''>And</span> <span m=''42390''>the</span>
  <span m=''42520''>job</span> <span m=''42810''>of</span> <span m=''42940''>the</span>
  <span m=''43230''>decoder</span> <span m=''47140''>is</span> <span m=''47360''>to</span>
  <span m=''47510''>find</span> <span m=''48050''>x</span> <span m=''48300''>hat,</span>
  <span m=''49260''>which</span> <span m=''49530''>belongs</span> <span m=''49930''>to</span>
  <span m=''50040''>the</span> <span m=''50140''>signal</span> <span m=''50580''>set</span>
  <span m=''51880''>so</span> <span m=''52150''>that</span> <span m=''52360''>you</span>
  <span m=''52460''>minimize</span> <span m=''54460''>your</span> <span m=''54660''>probability</span>
  <span m=''55380''>of</span> <span m=''55520''>error.</span> <span m=''55920''>And</span>
  <span m=''56320''>the</span> <span m=''56390''>probability</span> <span m=''57000''>of</span>
  <span m=''57110''>error</span> <span m=''58260''>x</span> <span m=''58470''>is</span>
  <span m=''58610''>not</span> <span m=''58960''>equal to</span> <span m=''59245''>x-hat.</span>
  <span m=''61840''>That''s</span> <span m=''62040''>the</span> <span m=''62140''>probability</span>
  <span m=''62710''>of</span> <span m=''62870''>error</span> <span m=''64269''>for</span>
  <span m=''64480''>your</span> <span m=''64569''>decoder.</span> </p><p><span m=''65780''>And</span>
  <span m=''65930''>we</span> <span m=''66090''>saw</span> <span m=''66450''>a</span>
  <span m=''66480''>bunch of</span> <span m=''66770''>equivalence</span> <span m=''67470''>rules</span>
  <span m=''68630''> -- we</span> <span m=''68830''>said</span> <span m=''69090''>that</span>
  <span m=''69230''>the</span> <span m=''69320''>minimum</span> <span m=''69770''>probability</span>
  <span m=''69950''>of</span> <span m=''70020''>error</span> <span m=''70230''>rule,</span>
  <span m=''71700''>which</span> <span m=''71860''>is</span> <span m=''71990''>this</span>
  <span m=''72080''>rule</span> <span m=''72440''>here,</span> <span m=''75040''>is</span>
  <span m=''75160''>the same</span> <span m=''75600''>as</span> <span m=''75810''>the</span>
  <span m=''76000''>maximum</span> <span m=''76700''>a posteriori</span> <span m=''76960''>rule.</span>
  <span m=''78900''>And</span> <span m=''79120''>this</span> <span m=''79310''>just</span>
  <span m=''79510''>follows</span> <span m=''79830''>by</span> <span m=''79930''>the</span>
  <span m=''80040''>definition.</span> <span m=''82410''>This</span> <span m=''82670''>was
  the</span> <span m=''82820''>same</span> <span m=''84940''>as</span> <span m=''85180''>the</span>
  <span m=''85290''>maximum</span> <span m=''85810''>likelihood</span> <span m=''86440''>rule.</span>
  <span m=''88160''>And here</span> <span m=''88250''>we made</span> <span m=''88470''>one</span>
  <span m=''88610''>assumption</span> <span m=''89730''>that</span> <span m=''90000''>all</span>
  <span m=''90250''>the</span> <span m=''90350''>signals</span> <span m=''91370''>in</span>
  <span m=''91570''>your</span> <span m=''92060''>signal</span> <span m=''92470''>set</span>
  <span m=''92670''>A</span> <span m=''93010''>are</span> <span m=''93130''>equally</span>
  <span m=''93470''>likely.</span> <span m=''95840''>And</span> <span m=''96450''>this</span>
  <span m=''96710''>was</span> <span m=''97270''>shown</span> <span m=''97590''>to</span>
  <span m=''97740''>be</span> <span m=''97860''>equivalent</span> <span m=''98890''>to</span>
  <span m=''99020''>your</span> <span m=''99170''>minimum</span> <span m=''99660''>distance</span>
  <span m=''100070''>decision</span> <span m=''100680''>rule.</span> <span m=''102130''>And</span>
  <span m=''103150''>in order</span> <span m=''103670''>to show this</span> <span
  m=''103840''>equivalence,</span> <span m=''104570''>we</span> <span m=''104710''>use</span>
  <span m=''104980''>the</span> <span m=''105110''>fact</span> <span m=''105580''>that</span>
  <span m=''105650''>the</span> <span m=''105760''>noise</span> <span m=''106110''>was</span>
  <span m=''106900''>White and</span> <span m=''107040''>Gaussian.</span> <span m=''108630''>So</span>
  <span m=''109940''>this</span> <span m=''110000''>assumes</span> <span m=''111320''>equi-probable</span>
  <span m=''112140''>signals.</span> <span m=''119290''>And</span> <span m=''119500''>this</span>
  <span m=''119710''>assumes</span> <span m=''120230''>AWGN</span> <span m=''121080''>channel.  OK.</span>
  </p><p><span m=''128259''>In</span> <span m=''129120''>fact,</span> <span m=''129360''>the</span>
  <span m=''129460''>minimum</span> <span m=''129800''>distance</span> <span m=''130169''>decisions</span>
  <span m=''130750''>has</span> <span m=''131020''>very nice</span> <span m=''131840''>geometrical</span>
  <span m=''132460''>properties.</span> <span m=''137720''>We</span> <span m=''138010''>basically</span>
  <span m=''138490''>said</span> <span m=''138680''>that</span> <span m=''138800''>the</span>
  <span m=''138890''>decision</span> <span m=''139420''>regions</span> <span m=''139910''>had</span>
  <span m=''140050''>a</span> <span m=''140190''>particular</span> <span m=''140790''>shape.</span>
  <span m=''141250''>They</span> <span m=''141660''>were</span> <span m=''141930''>convex</span>
  <span m=''142090''>polytopes.</span> <span m=''143100''>And</span> <span m=''145110''>they</span>
  <span m=''145590''>were</span> <span m=''145720''>also</span> <span m=''145980''>known</span>
  <span m=''146130''>as</span> <span m=''146470''>Voronoi</span> <span m=''146660''>regions.</span>
  <span m=''147720''>However,</span> <span m=''148290''>finding</span> <span m=''148680''>the</span>
  <span m=''148760''>exact</span> <span m=''149110''>expression</span> <span m=''149560''>for</span>
  <span m=''149670''>the</span> <span m=''149780''>probability</span> <span m=''150370''>of</span>
  <span m=''150630''>error</span> <span m=''150850''>seemed</span> <span m=''151190''>quite</span>
  <span m=''151540''>tedious</span> <span m=''153020''>so</span> <span m=''153350''>we</span>
  <span m=''153440''>decided</span> <span m=''153850''>to</span> <span m=''153920''>settle
  with</span> <span m=''154370''>bounds.</span> <span m=''155640''>And</span> <span
  m=''155960''>we</span> <span m=''156070''>developed</span> <span m=''156240''>some</span>
  <span m=''156660''>bounds</span> <span m=''157020''>for</span> <span m=''157170''>the</span>
  <span m=''157280''>probability</span> <span m=''157600''>of</span> <span m=''157970''>error.</span>
  <span m=''162530''>And</span> <span m=''162830''>the</span> <span m=''162940''>main</span>
  <span m=''163200''>bounds</span> <span m=''163680''>were --</span> <span m=''163940''>we</span>
  <span m=''164030''>had</span> <span m=''164210''>a</span> <span m=''164420''>strict</span>
  <span m=''164710''>upper</span> <span m=''164890''>bound,</span> <span m=''166140''>which</span>
  <span m=''166350''>was</span> <span m=''166640''>the</span> <span m=''166730''>summation.   OK.</span>
  <span m=''181220''>This</span> <span m=''181390''>is</span> <span m=''181520''>a</span>
  <span m=''181580''>strict</span> <span m=''181910''>upper</span> <span m=''182050''>bound.</span>
  <span m=''183230''>Well,</span> <span m=''183500''>the</span> <span m=''183770''>inequality</span>
  <span m=''184085''>here, say it''s</span> <span m=''184400''>a strict</span> <span
  m=''184880''>upper</span> <span m=''185400''>bound.</span> </p><p><span m=''186890''>We</span>
  <span m=''187320''>also</span> <span m=''187560''>had</span> <span m=''187760''>a</span>
  <span m=''188020''>union</span> <span m=''188500''>bound</span> <span m=''188760''>estimate.</span>
  <span m=''190450''>Because</span> <span m=''190760''>this</span> <span m=''190890''>is</span>
  <span m=''190980''>a</span> <span m=''191040''>sum</span> <span m=''191280''>of</span>
  <span m=''191440''>various</span> <span m=''191830''>Q</span> <span m=''192010''>functions,</span>
  <span m=''192650''>this</span> <span m=''192800''>is</span> <span m=''192910''>still</span>
  <span m=''193160''>a</span> <span m=''193330''>very</span> <span m=''194100''>cumbersome</span>
  <span m=''194770''>expression</span> <span m=''195290''>to</span> <span m=''195430''>evaluate.</span>
  <span m=''196270''>So</span> <span m=''196480''>we</span> <span m=''196590''>wanted</span>
  <span m=''196890''>a</span> <span m=''196930''>simpler</span> <span m=''197380''>expression.</span>
  <span m=''198440''>So</span> <span m=''198710''>we</span> <span m=''199040''>then</span>
  <span m=''199290''>approximated</span> <span m=''200160''>this</span> <span m=''200470''>by</span>
  <span m=''201410''>K_min</span> <span m=''201920''>of</span> <span m=''202090''>aj</span>
  <span m=''205890''>times</span> <span m=''206360''>Q</span> <span m=''206670''>of</span>
  <span m=''208650''>d_min</span> <span m=''210790''>over</span> <span m=''211460''>2</span>
  <span m=''211730''>sigma.</span> <span m=''213410''>OK,</span> <span m=''214820''>and</span>
  <span m=''215080''>now</span> <span m=''215330''>if</span> <span m=''215580''>we
  take</span> <span m=''215890''>the</span> <span m=''216060''>average on</span> <span
  m=''216170''>both</span> <span m=''216440''>sides,</span> <span m=''217200''>what</span>
  <span m=''217570''>we</span> <span m=''217750''>get</span> <span m=''217970''>is</span>
  <span m=''218130''>the</span> <span m=''218460''>probability</span> <span m=''218820''>of</span>
  <span m=''218930''>error</span> <span m=''219400''>is</span> <span m=''222320''>approximately</span>
  <span m=''223310''>equal</span> <span m=''223650''>to</span> <span m=''224850''>K_min</span>
  <span m=''225130''>of</span> <span m=''225420''>the</span> <span m=''225560''>constellation,</span>
  <span m=''226770''>which</span> <span m=''226990''>is</span> <span m=''227100''>the</span>
  <span m=''227160''>average</span> <span m=''227530''>number</span> <span m=''227840''>of</span>
  <span m=''227980''>nearest</span> <span m=''228470''>neighbors,</span> <span m=''229870''>times</span>
  <span m=''230560''>Q</span> <span m=''230830''>of</span> <span m=''233340''>d_min</span>
  <span m=''234940''>over</span> <span m=''235530''>2 sigma.</span> <span m=''238690''>And</span>
  <span m=''238950''>this</span> <span m=''239290''>expression</span> <span m=''239860''>is</span>
  <span m=''239950''>known</span> <span m=''240180''>as</span> <span m=''240390''>the</span>
  <span m=''241200''>union</span> <span m=''241680''>bound</span> <span m=''242120''>estimate.</span>
  <span m=''250280''>We</span> <span m=''250400''>call</span> <span m=''250610''>it</span>
  <span m=''250740''>an</span> <span m=''250870''>estimate</span> <span m=''251310''>because</span>
  <span m=''251540''>it''s</span> <span m=''251710''>not</span> <span m=''251810''>a</span>
  <span m=''251920''>bound</span> <span m=''252240''>anymore.</span> <span m=''253120''>We</span>
  <span m=''253280''>have</span> <span m=''253500''>made an</span> <span m=''253660''>approximation</span>
  <span m=''254510''>going</span> <span m=''254710''>from</span> <span m=''254940''>here</span>
  <span m=''255190''>to</span> <span m=''255320''>here.</span> <span m=''256370''>So</span>
  <span m=''256610''>this</span> <span m=''256769''>is</span> <span m=''256890''>what</span>
  <span m=''257079''>we</span> <span m=''257180''>came</span> <span m=''257390''>up</span>
  <span m=''257490''>with</span> <span m=''257630''>last time.</span> </p><p><span
  m=''258910''>Throughout</span> <span m=''259560''>the</span> <span m=''259839''>analysis</span>
  <span m=''260500''>today,</span> <span m=''261839''>whenever</span> <span m=''262200''>we</span>
  <span m=''262600''>have</span> <span m=''262750''>a</span> <span m=''262910''>probability
  of error</span> <span m=''263730''>expression,</span> <span m=''264350''>we will</span>
  <span m=''264910''>be estimating</span> <span m=''265220''>it</span> <span m=''265450''>by</span>
  <span m=''265550''>the</span> <span m=''265680''>union</span> <span m=''265970''>bound</span>
  <span m=''266230''>estimate.</span> <span m=''267170''>So</span> <span m=''267390''>this</span>
  <span m=''268900''>union</span> <span m=''269000''>bound</span> <span m=''269210''>estimate</span>
  <span m=''269570''>is</span> <span m=''269710''>quite</span> <span m=''269910''>important.</span>
  <span m=''271310''>Are</span> <span m=''271480''>there any</span> <span m=''271640''>questions</span>
  <span m=''272140''>on</span> <span m=''272270''>this?</span> </p><p><span m=''274420''>OK,</span>
  <span m=''276770''>so</span> <span m=''277120''>today</span> <span m=''277370''>we
  will</span> <span m=''277560''>start</span> <span m=''277890''>by</span> <span m=''278040''>introducing</span>
  <span m=''280050''>the</span> <span m=''280190''>notion</span> <span m=''280445''>of</span>
  <span m=''280700''>effective</span> <span m=''281250''>coding</span> <span m=''281620''>gain.</span>
  <span m=''298240''>And</span> <span m=''298430''>we''ll</span> <span m=''298700''>use</span>
  <span m=''298880''>the</span> <span m=''298930''>symbol</span> <span m=''299890''>gamma</span>
  <span m=''300140''>sub f</span> <span m=''301080''>for</span> <span m=''301670''>that.</span>
  <span m=''303330''>What</span> <span m=''303540''>do</span> <span m=''303640''>we</span>
  <span m=''303740''>mean</span> <span m=''304010''>by</span> <span m=''304190''>effective</span>
  <span m=''304560''>coding</span> <span m=''304940''>gain?</span> <span m=''305790''>First</span>
  <span m=''306010''>you</span> <span m=''306120''>have</span> <span m=''306230''>to</span>
  <span m=''306350''>decide</span> <span m=''306640''>what</span> <span m=''306820''>region</span>
  <span m=''307190''>you''re</span> <span m=''307360''>operating</span> <span m=''307860''>in.</span>
  <span m=''308630''>It''s</span> <span m=''308790''>defined</span> <span m=''309200''>for</span>
  <span m=''309340''>both</span> <span m=''309680''>bandwidth-limited</span> <span
  m=''310660''>regime</span> <span m=''311160''>and</span> <span m=''311300''>power-limited</span>
  <span m=''311850''>regimes.</span> <span m=''312800''>So</span> <span m=''313020''>let</span>
  <span m=''313170''>us</span> <span m=''313260''>start</span> <span m=''313670''>with</span>
  <span m=''313800''>the</span> <span m=''313930''>power-limited</span> <span m=''314740''>regime.</span>
  <span m=''324610''>Remember</span> <span m=''325010''>in</span> <span m=''325100''>the</span>
  <span m=''325210''>power-limited</span> <span m=''326000''>regime,</span> <span
  m=''326550''>the</span> <span m=''326700''>trade-off</span> <span m=''327160''>we</span>
  <span m=''327300''>care</span> <span m=''327600''>about</span> <span m=''328540''>is</span>
  <span m=''328860''>the</span> <span m=''328950''>probability</span> <span m=''329620''>of</span>
  <span m=''329950''>bit</span> <span m=''330140''>error</span> <span m=''332080''>versus</span>
  <span m=''332850''>Eb</span> <span m=''333331''>over</span> <span m=''333812''>N_0.</span>
  <span m=''335740''>The</span> <span m=''335900''>baseline</span> <span m=''336440''>scheme</span>
  <span m=''336770''>is</span> <span m=''336920''>2-PAM.</span> <span m=''345100''>And</span>
  <span m=''345280''>for</span> <span m=''345720''>2-PAM,</span> <span m=''346610''>we</span>
  <span m=''346750''>showed</span> <span m=''347920''>two</span> <span m=''348010''>lectures</span>
  <span m=''348390''>ago</span> <span m=''349240''>that</span> <span m=''349540''>the</span>
  <span m=''349630''>probability</span> <span m=''350310''>of</span> <span m=''351130''>bit
  error</span> <span m=''351485''>is</span> <span m=''351970''>given</span> <span
  m=''352340''>by</span> <span m=''352780''>Q</span> <span m=''353090''>of</span>
  <span m=''354520''>root</span> <span m=''356300''>2</span> <span m=''356470''>Eb
  N_0.</span> <span m=''361160''>OK,</span> <span m=''361340''>it</span> <span m=''361710''>should</span>
  <span m=''361930''>be --</span> <span m=''364310''>so</span> <span m=''364580''>now</span>
  <span m=''365290''>the</span> <span m=''365400''>idea</span> <span m=''365720''>is</span>
  <span m=''365910''>to</span> <span m=''366040''>plot</span> <span m=''366805''>your</span>
  <span m=''367170''>probability</span> <span m=''367750''>of</span> <span m=''367850''>bit</span>
  <span m=''368100''>error</span> <span m=''370870''>as</span> <span m=''371040''>a</span>
  <span m=''371120''>function</span> <span m=''371610''>of</span> <span m=''371700''>Eb
  N_0.</span> <span m=''376150''>Eb N_0</span> <span m=''376570''>is</span> <span
  m=''376700''>always</span> <span m=''376910''>plotted</span> <span m=''377300''>in</span>
  <span m=''377560''>dB</span> <span m=''378400''>on</span> <span m=''378580''>the</span>
  <span m=''378760''>x-axis.</span> <span m=''379760''>The</span> <span m=''379860''>probability</span>
  <span m=''380270''>of</span> <span m=''380580''>bit error</span> <span m=''380890''>we</span>
  <span m=''381040''>also</span> <span m=''381290''>plot</span> <span m=''383630''>on</span>
  <span m=''383790''>a</span> <span m=''383840''>logarithmic</span> <span m=''384460''>scale.</span>
  <span m=''385750''>So</span> <span m=''385960''>this</span> <span m=''386160''>is</span>
  <span m=''386310''>ten</span> <span m=''386510''>to</span> <span m=''386600''>the</span>
  <span m=''386720''>minus</span> <span m=''387110''>six.</span> <span m=''387590''>This</span>
  <span m=''387770''>is</span> <span m=''387920''>ten</span> <span m=''388110''>to</span>
  <span m=''388240''>the</span> <span m=''388360''>minus</span> <span m=''388820''>five,</span>
  <span m=''390012''>ten to the</span> <span m=''390390''>minus</span> <span m=''390820''>four</span>
  <span m=''391040''>and</span> <span m=''391250''>so</span> <span m=''391460''>on.</span>
  <span m=''393840''>The</span> <span m=''393970''>Shannon</span> <span m=''394410''>limit</span>
  <span m=''396460''>is</span> <span m=''396620''>at --</span> <span m=''397420''>this</span>
  <span m=''397600''>is</span> <span m=''397720''>the</span> <span m=''397790''>Shannon</span>
  <span m=''398150''>limit --</span> <span m=''399412''>is</span> <span m=''399790''>at</span>
  <span m=''400130''>minus</span> <span m=''400580''>1.59</span> <span m=''402100''>dB.</span>
  <span m=''405830''>OK?</span> </p><p><span m=''406580''>For</span> <span m=''406650''>the</span>
  <span m=''406750''>power-limited</span> <span m=''407500''>regime,</span> <span
  m=''410140''>the</span> <span m=''410450''>performance</span> <span m=''410630''>of</span>
  <span m=''410940''>2-PAM,</span> <span m=''412750''>which</span> <span m=''412970''>is</span>
  <span m=''413090''>given</span> <span m=''413350''>by</span> <span m=''413480''>this</span>
  <span m=''413690''>expression,</span> <span m=''414390''>is</span> <span m=''415130''>here.</span>
  <span m=''417350''>And</span> <span m=''418460''>we</span> <span m=''418710''>basically</span>
  <span m=''419230''>go to say</span> <span m=''419920''>that</span> <span m=''420850''>when</span>
  <span m=''420900''>the</span> <span m=''420940''>probability</span> <span m=''421060''>of</span>
  <span m=''421260''>bit error</span> <span m=''421870''>is</span> <span m=''421990''>ten</span>
  <span m=''422200''>to</span> <span m=''422280''>the</span> <span m=''422400''>minus</span>
  <span m=''422870''>five,</span> <span m=''424030''>the</span> <span m=''425030''>EbN
  _0</span> <span m=''425380''>that you</span> <span m=''425600''>require</span> <span
  m=''426660''>is</span> <span m=''426910''>9.6</span> <span m=''428790''>dB.</span>
  <span m=''431310''>This is a nine.</span> <span m=''435510''>So</span> <span m=''436100''>what''s</span>
  <span m=''436340''>the</span> <span m=''436410''>idea</span> <span m=''436720''>behind</span>
  <span m=''437030''>the</span> <span m=''437100''>effective</span> <span m=''437570''>coding</span>
  <span m=''437950''>gain?</span> <span m=''439540''>Well,</span> <span m=''439850''>suppose</span>
  <span m=''440200''>I</span> <span m=''440270''>give</span> <span m=''440490''>you</span>
  <span m=''440620''>a</span> <span m=''440670''>certain</span> <span m=''441030''>constellation,</span>
  <span m=''442480''>OK,</span> <span m=''443160''>a</span> <span m=''443440''>certain</span>
  <span m=''443680''>signal</span> <span m=''444160''>set.</span> <span m=''444940''>And</span>
  <span m=''445300''>you</span> <span m=''445860''>find</span> <span m=''446100''>the</span>
  <span m=''446180''>probability</span> <span m=''446740''>of</span> <span m=''446850''>bit
  error</span> <span m=''447100''>for</span> <span m=''447360''>that,</span> <span
  m=''448370''>and</span> <span m=''448500''>you</span> <span m=''448630''>plot it.</span>
  <span m=''449070''>And</span> <span m=''449310''>it</span> <span m=''449430''>comes</span>
  <span m=''449680''>out</span> <span m=''449850''>to be</span> <span m=''450040''>something</span>
  <span m=''450400''>like</span> <span m=''450650''>this.</span> <span m=''451970''>So</span>
  <span m=''452150''>this</span> <span m=''452310''>is</span> <span m=''452440''>the</span>
  <span m=''453420''>performance</span> <span m=''454340''>for</span> <span m=''454710''>some</span>
  <span m=''455280''>given</span> <span m=''455630''>signal</span> <span m=''456080''>set</span>
  <span m=''456270''>A.</span> <span m=''457220''>This</span> <span m=''457470''>is</span>
  <span m=''457620''>your</span> <span m=''458290''>2-PAM.</span> </p><p><span m=''463150''>And</span>
  <span m=''463440''>now</span> <span m=''463620''>you</span> <span m=''463760''>want</span>
  <span m=''464040''>to</span> <span m=''464160''>quantify</span> <span m=''464860''>how</span>
  <span m=''465120''>much</span> <span m=''465390''>better</span> <span m=''465610''>is</span>
  <span m=''465940''>the</span> <span m=''466060''>signal</span> <span m=''466470''>set</span>
  <span m=''466990''>over</span> <span m=''467160''>the</span> <span m=''467270''>baseline</span>
  <span m=''467750''>system.</span> <span m=''469390''>Now,</span> <span m=''469690''>so</span>
  <span m=''469810''>in</span> <span m=''469910''>other</span> <span m=''470010''>words</span>
  <span m=''470370''>you</span> <span m=''470490''>want</span> <span m=''470720''>to</span>
  <span m=''470800''>look</span> <span m=''470980''>at</span> <span m=''471100''>the</span>
  <span m=''471200''>gap</span> <span m=''471510''>between</span> <span m=''471850''>the</span>
  <span m=''472000''>two</span> <span m=''472260''>curves.</span> <span m=''473490''>Now</span>
  <span m=''473620''>clearly</span> <span m=''473990''>the</span> <span m=''474110''>gap</span>
  <span m=''474380''>is</span> <span m=''474530''>going</span> <span m=''474680''>to</span>
  <span m=''474840''>be</span> <span m=''474960''>a</span> <span m=''475010''>function</span>
  <span m=''475420''>of</span> <span m=''475500''>the</span> <span m=''475580''>probability</span>
  <span m=''475840''>of bit</span> <span m=''476100''>error,</span> <span m=''477060''>right?</span>
  <span m=''478100''>But</span> <span m=''479630''>the</span> <span m=''479730''>basic</span>
  <span m=''480110''>idea</span> <span m=''480450''>now</span> <span m=''480640''>is</span>
  <span m=''480770''>you</span> <span m=''480890''>want</span> <span m=''481050''>to</span>
  <span m=''481120''>fix</span> <span m=''481380''>a</span> <span m=''481480''>certain</span>
  <span m=''481990''>probability</span> <span m=''482330''>of</span> <span m=''482450''>bit</span>
  <span m=''482800''>error</span> <span m=''483520''>because</span> <span m=''483800''>if</span>
  <span m=''483910''>you''re</span> <span m=''484030''>designing</span> <span m=''484470''>a</span>
  <span m=''484530''>system,</span> <span m=''485400''>the</span> <span m=''485560''>probability</span>
  <span m=''485835''>of</span> <span m=''486110''>bit</span> <span m=''486290''>error
  is</span> <span m=''486600''>something</span> <span m=''486890''>that</span> <span
  m=''486990''>the</span> <span m=''487070''>system</span> <span m=''487480''>tolerates</span>
  <span m=''487740''>and</span> <span m=''488000''>is</span> <span m=''488230''>going</span>
  <span m=''488340''>to</span> <span m=''488460''>be</span> <span m=''488570''>fixed</span>
  <span m=''488920''>throughout</span> <span m=''489170''>the analysis.</span> </p><p><span
  m=''490480''>So</span> <span m=''490650''>in</span> <span m=''490740''>this</span>
  <span m=''490960''>course,</span> <span m=''491220''>we''ll be</span> <span m=''491440''>fixing</span>
  <span m=''491820''>it</span> <span m=''492040''>at</span> <span m=''492220''>ten</span>
  <span m=''492320''>to the</span> <span m=''492410''>minus</span> <span m=''492830''>five.</span>
  <span m=''493920''>You</span> <span m=''494090''>fix</span> <span m=''494360''>this</span>
  <span m=''494550''>probability</span> <span m=''495210''>of bit</span> <span m=''495380''>error</span>
  <span m=''495610''>to ten</span> <span m=''495930''>to</span> <span m=''495990''>the</span>
  <span m=''496090''>minus</span> <span m=''496510''>five,</span> <span m=''497120''>and</span>
  <span m=''497240''>you</span> <span m=''497360''>look</span> <span m=''497550''>at
  how</span> <span m=''497690''>much</span> <span m=''497950''>a</span> <span m=''497990''>gap</span>
  <span m=''498260''>you</span> <span m=''498430''>have</span> <span m=''498610''>between</span>
  <span m=''498910''>the</span> <span m=''499250''>two curves.</span> <span m=''501520''>And</span>
  <span m=''501690''>this</span> <span m=''501930''>gap</span> <span m=''502290''>is</span>
  <span m=''502460''>going</span> <span m=''502630''>to</span> <span m=''502810''>be</span>
  <span m=''503050''>your</span> <span m=''503140''>effective</span> <span m=''503630''>coding</span>
  <span m=''504000''>gain</span> <span m=''506000''>in</span> <span m=''506370''>dB.</span>
  <span m=''513049''>So</span> <span m=''513230''>in</span> <span m=''513350''>other</span>
  <span m=''513610''>words,</span> <span m=''514059''>effective</span> <span m=''514549''>coding</span>
  <span m=''514940''>gain,</span> <span m=''516120''>I can</span> <span m=''516429''>write</span>
  <span m=''516669''>here,</span> <span m=''517010''>is</span> <span m=''517190''>the</span>
  <span m=''519530''>gap</span> <span m=''520299''>between</span> <span m=''525360''>a</span>
  <span m=''525460''>given</span> <span m=''527180''>signal</span> <span m=''527830''>set</span>
  <span m=''531431''>and</span> <span m=''533960''>concordant</span> <span m=''534340''>system,</span>
  <span m=''534840''>2-PAM,</span> <span m=''536770''>at</span> <span m=''537000''>a</span>
  <span m=''537070''>fixed</span> <span m=''539178''>probability</span> <span m=''539664''>of</span>
  <span m=''540640''>bit</span> <span m=''540930''>error.</span> <span m=''545300''>OK?</span>
  </p><p><span m=''546060''>So</span> <span m=''546230''>now</span> <span m=''546390''>let
  us</span> <span m=''546640''>try</span> <span m=''546830''>to</span> <span m=''546910''>quantify</span>
  <span m=''547520''>this</span> <span m=''548260''>effective</span> <span m=''548600''>coding</span>
  <span m=''548710''>gain</span> <span m=''549470''>using</span> <span m=''549760''>the</span>
  <span m=''549870''>union</span> <span m=''550200''>bound</span> <span m=''550450''>estimate</span>
  <span m=''550930''>that</span> <span m=''551100''>we</span> <span m=''551280''>have</span>
  <span m=''551470''>here.</span> <span m=''552690''>So</span> <span m=''552920''>if</span>
  <span m=''553100''>I</span> <span m=''553170''>have</span> <span m=''553420''>a</span>
  <span m=''553480''>certain</span> <span m=''553850''>signal</span> <span m=''554340''>set,</span>
  <span m=''554580''>A,</span> <span m=''556380''>then</span> <span m=''556660''>I</span>
  <span m=''556730''>know</span> <span m=''556990''>from</span> <span m=''557980''>the</span>
  <span m=''558120''>union</span> <span m=''558530''>bound</span> <span m=''558840''>estimate</span>
  <span m=''559840''>that</span> <span m=''560130''>the</span> <span m=''560220''>probability</span>
  <span m=''561160''>of</span> <span m=''561350''>error</span> <span m=''562565''>is</span>
  <span m=''562970''>given</span> <span m=''563370''>by</span> <span m=''564950''>K_min</span>
  <span m=''565280''>of</span> <span m=''565660''>A</span> <span m=''567650''>times</span>
  <span m=''568590''>approximately</span> <span m=''570070''>Q</span> <span m=''570410''>of</span>
  <span m=''573060''>d_min</span> <span m=''573640''>over</span> <span m=''573880''>2</span>
  <span m=''574460''>sigma.</span> <span m=''577160''>So</span> <span m=''577430''>since</span>
  <span m=''577700''>I</span> <span m=''577870''>want</span> <span m=''578040''>that</span>
  <span m=''578170''>expression</span> <span m=''578640''>in terms</span> <span m=''578900''>of</span>
  <span m=''579200''>probability</span> <span m=''579330''>of</span> <span m=''579760''>bit</span>
  <span m=''579950''>error,</span> <span m=''581500''>I</span> <span m=''581640''>will</span>
  <span m=''581780''>use</span> <span m=''582550''>the</span> <span m=''582710''>fact</span>
  <span m=''583080''>that</span> <span m=''583360''>probability</span> <span m=''583620''>of</span>
  <span m=''583930''>bit</span> <span m=''584380''>error</span> <span m=''584985''>is</span>
  <span m=''585440''>probability</span> <span m=''585750''>of error</span> <span m=''586460''>per</span>
  <span m=''586620''>symbols</span> <span m=''587430''>or</span> <span m=''587660''>the</span>
  <span m=''587780''>number</span> <span m=''588130''>of</span> <span m=''589120''>bits
  per symobl.</span> <span m=''591130''>Since</span> <span m=''591510''>I</span> <span
  m=''591570''>have</span> <span m=''591720''>endpoints</span> <span m=''592310''>in</span>
  <span m=''592520''>my</span> <span m=''592710''>signal</span> <span m=''593140''>set,</span>
  <span m=''594800''>I</span> <span m=''594940''>have</span> <span m=''595130''>logM</span>
  <span m=''595630''>bits per symbol. </span> <span m=''599450''>And</span> <span
  m=''599900''>this</span> <span m=''600160''>is</span> <span m=''602392''>then</span>
  <span m=''603860''>K_min</span> <span m=''604180''>of</span> <span m=''604330''>A</span>
  <span m=''606820''>over</span> <span m=''608540''>logM</span> <span m=''610730''>base</span>
  <span m=''611140''>2</span> <span m=''613120''>times</span> <span m=''613420''>Q</span>
  <span m=''613660''>of</span> <span m=''615980''>d_min</span> <span m=''616630''>over</span>
  <span m=''616950''>2</span> <span m=''617300''>sigma.</span> </p><p><span m=''633910''>So</span>
  <span m=''634810''>I''m</span> <span m=''634990''>going</span> <span m=''635220''>to</span>
  <span m=''635830''>rewrite</span> <span m=''636020''>my</span> <span m=''636070''>probability</span>
  <span m=''636300''>of</span> <span m=''636620''>bit</span> <span m=''636810''>error</span>
  <span m=''637100''>expression</span> <span m=''637780''>now</span> <span m=''639570''>in</span>
  <span m=''639740''>this --</span> <span m=''640620''>in</span> <span m=''640760''>fact</span>
  <span m=''640870''>the</span> <span m=''640940''>right side</span> <span m=''641690''>in</span>
  <span m=''641880''>this</span> <span m=''642150''>quad.</span> <span m=''644080''>K_b</span>
  <span m=''644620''>of</span> <span m=''644910''>A</span> <span m=''647390''>times</span>
  <span m=''647850''>Q</span> <span m=''648300''>of</span> <span m=''649780''>root</span>
  <span m=''650270''>2</span> <span m=''651890''>gamma_c</span> <span m=''652470''>of</span>
  <span m=''652740''>A</span> <span m=''656390''>times</span> <span m=''656780''>Eb</span>
  <span m=''657000''>over</span> <span m=''657467''>N_0.</span> <span m=''658870''>So</span>
  <span m=''659000''>I''m</span> <span m=''659140''>just</span> <span m=''659290''>going</span>
  <span m=''659390''>to</span> <span m=''659500''>define</span> <span m=''660070''>the</span>
  <span m=''660200''>right</span> <span m=''660380''>hand</span> <span m=''660520''>side</span>
  <span m=''660790''>in</span> <span m=''660920''>this</span> <span m=''661180''>way.</span>
  <span m=''661880''>And</span> <span m=''662040''>I''m</span> <span m=''662140''>going</span>
  <span m=''662300''>to</span> <span m=''662470''>relate</span> <span m=''662800''>gamma_c</span>
  <span m=''663140''>of</span> <span m=''663450''>A</span> <span m=''663740''>and</span>
  <span m=''664020''>K_b</span> <span m=''664220''>of A</span> <span m=''665170''>to</span>
  <span m=''665290''>the</span> <span m=''665410''>parameters</span> <span m=''666020''>I</span>
  <span m=''666090''>have</span> <span m=''666270''>on</span> <span m=''666360''>the</span>
  <span m=''666450''>right</span> <span m=''666600''>hand</span> <span m=''666790''>side</span>
  <span m=''667100''>there.</span> <span m=''668620''>And</span> <span m=''668790''>why</span>
  <span m=''669040''>do I</span> <span m=''669130''>want</span> <span m=''669390''>to</span>
  <span m=''669520''>do it</span> <span m=''669750''>this</span> <span m=''670020''>way?</span>
  <span m=''670690''>Because</span> <span m=''671000''>I</span> <span m=''671070''>want</span>
  <span m=''671290''>to</span> <span m=''671360''>get</span> <span m=''671530''>an</span>
  <span m=''671650''>expression</span> <span m=''672290''>as</span> <span m=''672510''>close</span>
  <span m=''673350''>as</span> <span m=''673620''>possible</span> <span m=''674180''>to</span>
  <span m=''674310''>the</span> <span m=''674710''>performance</span> <span m=''675120''>of</span>
  <span m=''675220''>an</span> <span m=''675350''>uncoded</span> <span m=''675830''>2-PAM</span>
  <span m=''676370''>system</span> <span m=''677330''>because</span> <span m=''677640''>that
  way</span> <span m=''678640''>things</span> <span m=''678840''>will</span> <span
  m=''678970''>be</span> <span m=''679060''>easier</span> <span m=''679540''>to</span>
  <span m=''679950''>do</span> <span m=''680310''>if</span> <span m=''680530''>I</span>
  <span m=''680590''>want</span> <span m=''680810''>to</span> <span m=''680900''>calculate</span>
  <span m=''681370''>the</span> <span m=''681440''>effective</span> <span m=''681860''>coding</span>
  <span m=''682180''>gain,</span> <span m=''683900''>OK?</span> </p><p><span m=''684530''>So</span>
  <span m=''684780''>how</span> <span m=''684960''>do</span> <span m=''685350''>the</span>
  <span m=''685700''>parameters</span> <span m=''686210''>relate?</span> <span m=''687240''>Well,</span>
  <span m=''688810''>K_b</span> <span m=''689030''>of</span> <span m=''689300''>A</span>
  <span m=''693880''>is</span> <span m=''694170''>K_min</span> <span m=''694470''>of</span>
  <span m=''694820''>A</span> <span m=''696310''>over</span> <span m=''698380''>logM</span>
  <span m=''698970''>to</span> <span m=''699060''>the</span> <span m=''699220''>base</span>
  <span m=''699630''>2.</span> <span m=''700810''>And</span> <span m=''701080''>this</span>
  <span m=''701260''>is</span> <span m=''701520''>the</span> <span m=''702710''>average</span>
  <span m=''705260''>number</span> <span m=''705740''>of</span> <span m=''707530''>nearest</span>
  <span m=''708250''>neighbors</span> <span m=''715040''>per</span> <span m=''716430''>information</span>
  <span m=''722200''>bit.</span> <span m=''724110''>If</span> <span m=''724260''>I</span>
  <span m=''724320''>compare</span> <span m=''724790''>the</span> <span m=''725130''>arguments</span>
  <span m=''725660''>inside</span> <span m=''726040''>the</span> <span m=''726170''>Q</span>
  <span m=''726410''>function,</span> <span m=''727690''>what</span> <span m=''727930''>I</span>
  <span m=''728060''>have</span> <span m=''728380''>is</span> <span m=''730770''>2</span>
  <span m=''730920''>gamma_c</span> <span m=''731620''>of</span> <span m=''732030''>A</span>
  <span m=''734630''>times</span> <span m=''736230''>Eb N_0</span> <span m=''738660''>is</span>
  <span m=''739480''>the</span> <span m=''739710''>argument</span> <span m=''740260''>d_min</span>
  <span m=''740570''>over</span> <span m=''741770''>2</span> <span m=''742200''>sigma</span>
  <span m=''742630''>squared,</span> <span m=''743490''>which</span> <span m=''743560''>I
  will</span> <span m=''743690''>write</span> <span m=''743900''>as</span> <span m=''744070''>d_min</span>
  <span m=''744910''>squared</span> <span m=''745350''>over</span> <span m=''745580''>4</span>
  <span m=''745900''>sigma</span> <span m=''746320''>squared.</span> </p><p><span
  m=''748960''>So</span> <span m=''750460''>remember</span> <span m=''750850''>sigma</span>
  <span m=''751030''>squared</span> <span m=''751330''>is</span> <span m=''751560''>N_0</span>
  <span m=''751980''>over</span> <span m=''752320''>2.</span> <span m=''752950''>So</span>
  <span m=''753150''>if</span> <span m=''753330''>I</span> <span m=''753410''>simplify</span>
  <span m=''754020''>this</span> <span m=''754220''>expression,</span> <span m=''755550''>what</span>
  <span m=''755800''>I</span> <span m=''755940''>will end</span> <span m=''756260''>up
  getting</span> <span m=''756810''>is</span> <span m=''756960''>gamma_c</span> <span
  m=''757460''>of</span> <span m=''757610''>A</span> <span m=''759150''>is</span>
  <span m=''761850''>d_min</span> <span m=''762430''>squared</span> <span m=''764950''>over</span>
  <span m=''765190''>4 Eb.</span> <span m=''768860''>Gamma_c</span> <span m=''769460''>of
  A</span> <span m=''769780''>is</span> <span m=''769890''>known</span> <span m=''770160''>as</span>
  <span m=''770290''>the</span> <span m=''770390''>nominal</span> <span m=''770720''>coding</span>
  <span m=''771260''>gain.</span> <span m=''783680''>It''s</span> <span m=''783850''>not</span>
  <span m=''784010''>the</span> <span m=''784110''>same</span> <span m=''784370''>as</span>
  <span m=''784480''>the</span> <span m=''784640''>effective</span> <span m=''784910''>coding</span>
  <span m=''785300''>gain,</span> <span m=''785900''>which</span> <span m=''786060''>is</span>
  <span m=''786130''>the</span> <span m=''786200''>distance</span> <span m=''786560''>between</span>
  <span m=''786850''>the</span> <span m=''786970''>two</span> <span m=''787170''>curves.</span>
  <span m=''788880''>OK,</span> <span m=''790290''>are</span> <span m=''790380''>there</span>
  <span m=''790530''>any</span> <span m=''790680''>questions</span> <span m=''791090''>so</span>
  <span m=''791380''>far?</span> </p><p><span m=''793730''>So</span> <span m=''794050''>far</span>
  <span m=''794450''>what I</span> <span m=''794560''>have</span> <span m=''794790''>done</span>
  <span m=''794990''>is</span> <span m=''795610''>given</span> <span m=''795920''>a</span>
  <span m=''796010''>constellation</span> <span m=''797170''>A,</span> <span m=''798090''>I</span>
  <span m=''798230''>can</span> <span m=''798440''>find</span> <span m=''798960''>two</span>
  <span m=''799220''>parameters.</span> <span m=''800870''>I</span> <span m=''800960''>can</span>
  <span m=''801180''>find</span> <span m=''801480''>the</span> <span m=''801540''>nominal</span>
  <span m=''801940''>coding</span> <span m=''802410''>gain,</span> <span m=''803966''>and</span>
  <span m=''804370''>I</span> <span m=''804650''>can</span> <span m=''804890''>find</span>
  <span m=''805270''>the</span> <span m=''805490''>average</span> <span m=''805710''>number</span>
  <span m=''805920''>of</span> <span m=''806170''>nearest</span> <span m=''806670''>neighbors</span>
  <span m=''807300''>per</span> <span m=''807490''>information</span> <span m=''807855''>bit.</span>
  <span m=''810000''>And</span> <span m=''810170''>using</span> <span m=''810520''>these</span>
  <span m=''810720''>two</span> <span m=''810850''>parameters,</span> <span m=''811300''>we
  will</span> <span m=''811830''>try</span> <span m=''812220''>to</span> <span m=''812610''>get
  a</span> <span m=''812650''>handle</span> <span m=''813160''>over</span> <span m=''813300''>the
  effective</span> <span m=''813710''>coding gain.</span> <span m=''815360''>So</span>
  <span m=''815560''>that''s</span> <span m=''815830''>the</span> <span m=''815960''>idea.</span>
  </p><p><span m=''816990''>So</span> <span m=''817410''>how</span> <span m=''817610''>can</span>
  <span m=''817800''>we</span> <span m=''817880''>plot --</span> <span m=''818490''>so</span>
  <span m=''818650''>given</span> <span m=''818940''>this</span> <span m=''819120''>constellation</span>
  <span m=''819860''>A,</span> <span m=''820450''>we</span> <span m=''820580''>want</span>
  <span m=''820840''>to</span> <span m=''820920''>plot</span> <span m=''821320''>the</span>
  <span m=''821420''>probability</span> <span m=''822010''>of</span> <span m=''822250''>bit</span>
  <span m=''822430''>error</span> <span m=''822580''>curve</span> <span m=''822830''>like</span>
  <span m=''823040''>this.</span> <span m=''824050''>But</span> <span m=''824160''>instead</span>
  <span m=''824390''>of</span> <span m=''824510''>plotting</span> <span m=''824790''>the</span>
  <span m=''824870''>exact</span> <span m=''825330''>curve</span> <span m=''826010''>we
  will</span> <span m=''826300''>be</span> <span m=''826430''>plotting</span> <span
  m=''826980''>this</span> <span m=''827270''>curve</span> <span m=''827530''>here,</span>
  <span m=''828450''>which</span> <span m=''828710''>is</span> <span m=''828890''>the</span>
  <span m=''828970''>union</span> <span m=''829350''>bound</span> <span m=''829600''>estimate</span>
  <span m=''830070''>of</span> <span m=''830160''>your</span> <span m=''830320''>probability</span>
  <span m=''830690''>of bit error.</span> <span m=''832270''>So</span> <span m=''832460''>we</span>
  <span m=''832580''>will</span> <span m=''832975''>always be</span> <span m=''833370''>plotting</span>
  <span m=''833720''>the</span> <span m=''834090''>union</span> <span m=''834445''>bound</span>
  <span m=''834900''>estimate.</span> </p><p><span m=''837290''>So</span> <span m=''837620''>how</span>
  <span m=''837830''>do</span> <span m=''837960''>we</span> <span m=''838090''>do</span>
  <span m=''838240''>that?</span> <span m=''839200''>So</span> <span m=''839440''>we''ll
  again</span> <span m=''839760''>start</span> <span m=''840070''>with</span> <span
  m=''840190''>a</span> <span m=''840310''>curve</span> <span m=''840560''>like</span>
  <span m=''840800''>that.</span> <span m=''842270''>Probability</span> <span m=''842760''>of</span>
  <span m=''843190''>bit</span> <span m=''843310''>error</span> <span m=''845050''>as</span>
  <span m=''845200''>a</span> <span m=''845280''>function</span> <span m=''845770''>of</span>
  <span m=''846130''>Eb</span> <span m=''846480''>N_0.</span> <span m=''847930''>This</span>
  <span m=''848080''>is</span> <span m=''848210''>in</span> <span m=''848660''>dB.</span>
  <span m=''851020''>The</span> <span m=''851190''>y-axis</span> <span m=''851720''>is</span>
  <span m=''851790''>also</span> <span m=''852060''>in</span> <span m=''852430''>dB.</span>
  <span m=''853980''>Sorry,</span> <span m=''854350''>not</span> <span m=''854470''>in</span>
  <span m=''854600''>dB</span> <span m=''854910''>but</span> <span m=''855080''>on</span>
  <span m=''855160''>the</span> <span m=''855260''>log</span> <span m=''855530''>scale.</span>
  <span m=''862995''>And</span> <span m=''863480''>so</span> <span m=''863910''>on.</span>
  <span m=''864760''>This</span> <span m=''864950''>is</span> <span m=''865070''>the</span>
  <span m=''865160''>Shannon</span> <span m=''865610''>limit</span> <span m=''868180''>at</span>
  <span m=''868370''>minus</span> <span m=''868740''>1. 59</span> <span m=''869610''>dB.</span>
  <span m=''874270''>This</span> <span m=''874500''>is</span> <span m=''874660''>the</span>
  <span m=''874770''>2-PAM</span> <span m=''875730''>performance.</span> </p><p><span
  m=''879420''>So</span> <span m=''879650''>if</span> <span m=''879870''>we</span>
  <span m=''880250''>want</span> <span m=''880520''>to</span> <span m=''880610''>plot</span>
  <span m=''881050''>this</span> <span m=''882240''>union</span> <span m=''882590''>bound</span>
  <span m=''883060''>estimate,</span> <span m=''883510''>you</span> <span m=''883720''>will
  be</span> <span m=''883820''>doing</span> <span m=''884170''>two</span> <span m=''884290''>steps.</span>
  <span m=''885250''>First,</span> <span m=''886040''>we''ll</span> <span m=''886420''>be</span>
  <span m=''886660''>plotting this Q</span> <span m=''886870''>function,</span> <span
  m=''887155''>a</span> <span m=''887440''>curve</span> <span m=''888170''>corresponding</span>
  <span m=''888420''>to</span> <span m=''888520''>the</span> <span m=''888660''>Q</span>
  <span m=''888900''>function.</span> <span m=''889780''>And</span> <span m=''889940''>then</span>
  <span m=''890060''>we''ll</span> <span m=''890230''>be</span> <span m=''890350''>scaling</span>
  <span m=''890820''>it.</span> <span m=''892110''>So</span> <span m=''893670''>if</span>
  <span m=''893810''>I</span> <span m=''893870''>just</span> <span m=''894050''>want</span>
  <span m=''894230''>to</span> <span m=''894300''>plot</span> <span m=''894650''>this</span>
  <span m=''894880''>Q</span> <span m=''895080''>function,</span> <span m=''895990''>how</span>
  <span m=''896210''>will it</span> <span m=''896400''>compare</span> <span m=''896970''>to</span>
  <span m=''897120''>this</span> <span m=''897240''>curve</span> <span m=''897640''>here?</span>
  <span m=''905620''>Well,</span> <span m=''906040''>you''re</span> <span m=''906230''>just</span>
  <span m=''906500''>scaling</span> <span m=''906800''>the</span> <span m=''907530''>argument</span>
  <span m=''907970''>inside</span> <span m=''908380''>the</span> <span m=''908470''>Q</span>
  <span m=''908660''>function,</span> <span m=''909150''>right?</span> <span m=''910130''>But</span>
  <span m=''910550''>now</span> <span m=''910740''>because</span> <span m=''911170''>we
  are</span> <span m=''911330''>plotting</span> <span m=''912060''>the</span> <span
  m=''912170''>x-axis</span> <span m=''912730''>on</span> <span m=''912810''>a</span>
  <span m=''912900''>dB</span> <span m=''913280''>scale,</span> <span m=''914310''>it</span>
  <span m=''914480''>simply</span> <span m=''915290''>means</span> <span m=''915590''>that</span>
  <span m=''915740''>we are</span> <span m=''915900''>translating</span> <span m=''916540''>to</span>
  <span m=''916660''>the</span> <span m=''916790''>left</span> <span m=''917420''>by</span>
  <span m=''917770''>an</span> <span m=''917890''>amount</span> <span m=''918200''>of</span>
  <span m=''918310''>gamma_c</span> <span m=''918970''>in</span> <span m=''919350''>dB.</span>
  <span m=''920670''>Is that</span> <span m=''920920''>clear?</span> </p><p><span
  m=''922920''>Well,</span> <span m=''923260''>let''s</span> <span m=''923590''>see.</span>
  <span m=''923850''>What</span> <span m=''924860''>we are</span> <span m=''925030''>doing</span>
  <span m=''925290''>is</span> <span m=''925420''>we are</span> <span m=''925590''>going</span>
  <span m=''925740''>to</span> <span m=''925900''>scale</span> <span m=''926340''>the</span>
  <span m=''927340''>x-axis</span> <span m=''928030''>by</span> <span m=''928210''>a</span>
  <span m=''928500''>certain</span> <span m=''928710''>constant.</span> <span m=''929790''>So</span>
  <span m=''929920''>this</span> <span m=''930090''>means</span> <span m=''930300''>that</span>
  <span m=''930410''>we will</span> <span m=''930570''>have</span> <span m=''930730''>to</span>
  <span m=''930820''>scale</span> <span m=''931270''>x-axis</span> <span m=''931930''>here.</span>
  <span m=''933210''>But,</span> <span m=''933940''>our</span> <span m=''934020''>Eb</span>
  <span m=''934160''>N_0</span> <span m=''934260''>is</span> <span m=''934620''>being</span>
  <span m=''934870''>plotted</span> <span m=''935300''>on</span> <span m=''935410''>a</span>
  <span m=''935510''>dB</span> <span m=''935860''>scale,</span> <span m=''936340''>right?</span>
  <span m=''937480''>So</span> <span m=''937710''>multiplying</span> <span m=''939310''>in</span>
  <span m=''939610''>the</span> <span m=''939720''>linear</span> <span m=''940070''>scale</span>
  <span m=''940950''>corresponds</span> <span m=''941400''>to</span> <span m=''941510''>an</span>
  <span m=''941610''>addition on the</span> <span m=''942060''>logarithmic</span>
  <span m=''942550''>scale.</span> <span m=''943680''>An</span> <span m=''943860''>addition</span>
  <span m=''943920''>on the</span> <span m=''944330''>logarithmic</span> <span m=''944900''>scale</span>
  <span m=''945550''>simply</span> <span m=''945940''>implies</span> <span m=''946330''>a</span>
  <span m=''946400''>shift</span> <span m=''947240''>on</span> <span m=''947420''>the</span>
  <span m=''947600''>x-axis</span> <span m=''948610''>so</span> <span m=''949830''>that''s</span>
  <span m=''950180''>the</span> <span m=''950300''>constant</span> <span m=''950820''>shift</span>
  <span m=''951220''>on</span> <span m=''951320''>the</span> <span m=''951400''>x-axis.</span>
  <span m=''952170''>I''m</span> <span m=''952320''>going</span> <span m=''952530''>to</span>
  <span m=''952650''>plot</span> <span m=''952910''>it</span> <span m=''953180''>here.</span>
  <span m=''953800''>This</span> <span m=''954110''>curve</span> <span m=''954260''>is
  going</span> <span m=''954400''>to</span> <span m=''954550''>be</span> <span m=''954670''>parallel</span>
  <span m=''956660''>to the</span> <span m=''956980''>original</span> <span m=''957310''>2-PAM</span>
  <span m=''958020''>curve</span> <span m=''958510''>to</span> <span m=''958580''>the</span>
  <span m=''958640''>best</span> <span m=''958910''>of</span> <span m=''959020''>my</span>
  <span m=''959210''>abilities.</span> <span m=''961310''>OK,</span> <span m=''961970''>so</span>
  <span m=''962210''>this</span> <span m=''962370''>is</span> <span m=''962490''>what</span>
  <span m=''962680''>we</span> <span m=''962820''>get</span> <span m=''963060''>as</span>
  <span m=''963300''>your</span> <span m=''963470''>Q</span> <span m=''963650''>function.</span>
  </p><p><span m=''965010''>Now</span> <span m=''965260''>we</span> <span m=''965380''>are</span>
  <span m=''965490''>going</span> <span m=''965670''>to</span> <span m=''965860''>scale</span>
  <span m=''966290''>the</span> <span m=''966420''>y-axis</span> <span m=''967120''>by</span>
  <span m=''967300''>this</span> <span m=''967590''>factor</span> <span m=''967990''>here,</span>
  <span m=''968800''>K_b</span> <span m=''969000''>of</span> <span m=''969150''>A.</span>
  <span m=''970140''>But</span> <span m=''970280''>remember</span> <span m=''970670''>the</span>
  <span m=''970880''>y-axis</span> <span m=''971450''>is</span> <span m=''971570''>also</span>
  <span m=''971910''>on a</span> <span m=''974300''>logarithmic</span> <span m=''974320''>scale,</span>
  <span m=''975000''>rather</span> <span m=''975570''>than the</span> <span m=''975860''>linear</span>
  <span m=''976010''>scale.</span> <span m=''976970''>So</span> <span m=''977270''>multiply</span>
  <span m=''977430''>[INAUDIBLE]</span> <span m=''977750''>by</span> <span m=''977890''>a</span>
  <span m=''978030''>factor</span> <span m=''978400''>of</span> <span m=''978490''>K_b</span>
  <span m=''978690''>of</span> <span m=''978830''>A</span> <span m=''979890''>implies</span>
  <span m=''980620''>a</span> <span m=''981010''>vertical</span> <span m=''981300''>shift</span>
  <span m=''981640''>by</span> <span m=''982480''>a</span> <span m=''982930''>certain</span>
  <span m=''983060''>factor.</span> <span m=''984590''>So</span> <span m=''986030''>I''m</span>
  <span m=''986170''>going</span> <span m=''986330''>to</span> <span m=''986500''>do</span>
  <span m=''986710''>a</span> <span m=''986990''>vertical</span> <span m=''987350''>shift
  here.</span> <span m=''994600''>So</span> <span m=''994830''>let</span> <span m=''995910''>me</span>
  <span m=''996010''>make</span> <span m=''996240''>that</span> <span m=''996620''>darker</span>
  <span m=''997180''>now.</span> <span m=''998510''>So</span> <span m=''998720''>this</span>
  <span m=''998910''>is</span> <span m=''999040''>what</span> <span m=''999180''>I</span>
  <span m=''999330''>end</span> <span m=''999460''>up</span> <span m=''999600''>getting.</span>
  </p><p><span m=''1003700''>OK,</span> <span m=''1003940''>now</span> <span m=''1004190''>note</span>
  <span m=''1004440''>that</span> <span m=''1004700''>the</span> <span m=''1004780''>distance</span>
  <span m=''1005290''>between</span> <span m=''1005600''>these</span> <span m=''1005760''>two</span>
  <span m=''1005870''>curves</span> <span m=''1006120''>is</span> <span m=''1006250''>not</span>
  <span m=''1006420''>fixed</span> <span m=''1006750''>anymore.</span> <span m=''1007960''>If</span>
  <span m=''1008120''>the</span> <span m=''1008230''>slope</span> <span m=''1008640''>is</span>
  <span m=''1009100''>steeper,</span> <span m=''1010140''>then</span> <span m=''1010350''>this</span>
  <span m=''1010520''>distance</span> <span m=''1010930''>is</span> <span m=''1011030''>small,</span>
  <span m=''1011460''>meaning</span> <span m=''1011710''>that</span> <span m=''1011890''>this</span>
  <span m=''1012030''>distance</span> <span m=''1012390''>here</span> <span m=''1012570''>is</span>
  <span m=''1012790''>large.</span> <span m=''1013790''>On</span> <span m=''1013940''>the</span>
  <span m=''1014090''>other</span> <span m=''1014240''>hand,</span> <span m=''1014450''>if</span>
  <span m=''1014560''>the</span> <span m=''1014700''>slope</span> <span m=''1015220''>is</span>
  <span m=''1015930''>going</span> <span m=''1016180''>to</span> <span m=''1016330''>be</span>
  <span m=''1017280''>smaller</span> <span m=''1017830''>here,</span> <span m=''1018130''>then</span>
  <span m=''1018390''>this</span> <span m=''1018560''>distance</span> <span m=''1018990''>is</span>
  <span m=''1019160''>large.</span> <span m=''1021330''>So</span> <span m=''1021530''>this</span>
  <span m=''1021720''>means</span> <span m=''1021960''>that</span> <span m=''1022060''>a</span>
  <span m=''1022160''>distance</span> <span m=''1022520''>between</span> <span m=''1022840''>these</span>
  <span m=''1023110''>two</span> <span m=''1023230''>curves</span> <span m=''1023530''>is</span>
  <span m=''1023650''>no</span> <span m=''1023770''>longer</span> <span m=''1024109''>fixed.</span>
  <span m=''1025099''>And</span> <span m=''1025200''>basically</span> <span m=''1025660''>what</span>
  <span m=''1025880''>we''re</span> <span m=''1026050''>saying</span> <span m=''1026349''>here</span>
  <span m=''1027230''>is</span> <span m=''1027490''>that</span> <span m=''1027650''>if</span>
  <span m=''1027760''>the</span> <span m=''1027859''>probability</span> <span m=''1028410''>of
  error</span> <span m=''1028800''>is</span> <span m=''1028980''>large,</span> <span
  m=''1029750''>then</span> <span m=''1029950''>the</span> <span m=''1030250''>number</span>
  <span m=''1030579''>of</span> <span m=''1030700''>nearest</span> <span m=''1031109''>neighbors</span>
  <span m=''1031420''>matters</span> <span m=''1031890''>much</span> <span m=''1032180''>more.</span>
  <span m=''1033069''>But if</span> <span m=''1033339''>the</span> <span m=''1033470''>probability</span>
  <span m=''1034030''>of</span> <span m=''1034160''>error</span> <span m=''1034380''>is</span>
  <span m=''1034560''>going</span> <span m=''1034710''>to</span> <span m=''1034869''>be</span>
  <span m=''1034990''>quite</span> <span m=''1035280''>small,</span> <span m=''1036310''>then</span>
  <span m=''1037089''>the</span> <span m=''1037220''>more</span> <span m=''1037440''>important</span>
  <span m=''1037920''>factor</span> <span m=''1038380''>is your exponent,</span> <span
  m=''1039079''>how</span> <span m=''1039400''>fast</span> <span m=''1039680''>the</span>
  <span m=''1039790''>slope</span> <span m=''1039960''>decays</span> <span m=''1040760''>as</span>
  <span m=''1040930''>opposed</span> <span m=''1041260''>to</span> <span m=''1041310''>the</span>
  <span m=''1041380''>number</span> <span m=''1041650''>of</span> <span m=''1041750''>nearest</span>
  <span m=''1042180''>neighbors,</span> <span m=''1043880''>OK?</span> </p><p><span
  m=''1046349''>This</span> <span m=''1046700''>distance</span> <span m=''1047109''>here</span>
  <span m=''1048010''>is</span> <span m=''1048470''>your</span> <span m=''1048580''>effective</span>
  <span m=''1049090''>coding</span> <span m=''1049470''>gain.</span> <span m=''1051630''>And</span>
  <span m=''1052090''>this</span> <span m=''1052270''>constant</span> <span m=''1052740''>horizontal</span>
  <span m=''1053410''>distance</span> <span m=''1053820''>here</span> <span m=''1054930''>is</span>
  <span m=''1055160''>your</span> <span m=''1057000''>nominal</span> <span m=''1057420''>coding</span>
  <span m=''1057920''>gain</span> <span m=''1058410''>in</span> <span m=''1058887''>dB.</span>
  <span m=''1065570''>Are</span> <span m=''1065670''>there</span> <span m=''1065780''>any</span>
  <span m=''1065950''>questions</span> <span m=''1066480''>on</span> <span m=''1066960''>this</span>
  <span m=''1067170''>curve?</span> </p><p><span m=''1069280''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''1071842''>on</span> <span m=''1072304''>the right</span> <span m=''1072766''>of</span>
  <span m=''1073228''>four</span> <span m=''1073690''>2-PAM</span> <span m=''1075076''>because</span>
  <span m=''1075538''>these are</span> <span m=''1076000''>the</span> <span m=''1076462''>logM.</span>
  </p><p><span m=''1077800''>PROFESSOR: So</span> <span m=''1079070''>so</span> <span
  m=''1079370''>what</span> <span m=''1080110''>I''m</span> <span m=''1080420''>really</span>
  <span m=''1080610''>assuming</span> <span m=''1080980''>is that</span> <span m=''1081340''>gamma_c</span>
  <span m=''1081810''>of A is</span> <span m=''1082070''>greater</span> <span m=''1082370''>than</span>
  <span m=''1082570''>1.</span> <span m=''1083350''>So</span> <span m=''1083550''>if</span>
  <span m=''1083650''>I''m</span> <span m=''1083800''>adding</span> <span m=''1084140''>it,</span>
  <span m=''1084520''>then</span> <span m=''1084710''>I''m</span> <span m=''1084780''>going</span>
  <span m=''1084940''>to</span> <span m=''1084980''>shift</span> <span m=''1085250''>to</span>
  <span m=''1085330''>the</span> <span m=''1085530''>left,</span> <span m=''1085720''>right?</span>
  <span m=''1099600''>OK,</span> <span m=''1099850''>so</span> <span m=''1100060''>a</span>
  <span m=''1100170''>couple</span> <span m=''1100410''>of</span> <span m=''1100710''>remarks.</span>
  <span m=''1111980''>I''m</span> <span m=''1112150''>just</span> <span m=''1112410''>summarizing</span>
  <span m=''1113360''>a</span> <span m=''1113840''>few</span> <span m=''1114140''>remarks</span>
  <span m=''1114600''>I made</span> <span m=''1114860''>while</span> <span m=''1114970''>plotting</span>
  <span m=''1115390''>the</span> <span m=''1115510''>curve.</span> <span m=''1116430''>First</span>
  <span m=''1116730''>is</span> <span m=''1117030''>the</span> <span m=''1117130''>log-log</span>
  <span m=''1117650''>scale</span> <span m=''1122880''>is</span> <span m=''1123040''>very</span>
  <span m=''1123300''>convenient</span> <span m=''1132640''>because</span> <span m=''1133260''>any</span>
  <span m=''1133430''>multiplicative</span> <span m=''1134110''>factor</span> <span
  m=''1134480''>simply</span> <span m=''1135000''>involves</span> <span m=''1135370''>a</span>
  <span m=''1135440''>translation</span> <span m=''1136060''>along</span> <span m=''1136280''>the</span>
  <span m=''1136350''>x</span> <span m=''1136540''>and</span> <span m=''1136660''>y</span>
  <span m=''1137590''>directions.</span> </p><p><span m=''1140040''>The</span> <span
  m=''1140400''>second</span> <span m=''1140790''>point</span> <span m=''1141170''>is</span>
  <span m=''1141410''>that</span> <span m=''1142070''>the</span> <span m=''1142450''>accuracy</span>
  <span m=''1143270''>we</span> <span m=''1143560''>have</span> <span m=''1147270''>in</span>
  <span m=''1147430''>the</span> <span m=''1147510''>effective</span> <span m=''1147980''>coding</span>
  <span m=''1148410''>gain</span> <span m=''1148840''>in this</span> <span m=''1149100''>way</span>
  <span m=''1150020''>is</span> <span m=''1155680''>determined</span> <span m=''1159710''>by</span>
  <span m=''1160780''>the</span> <span m=''1160900''>union</span> <span m=''1161330''>bound</span>
  <span m=''1161600''>estimate</span> <span m=''1163210''>because</span> <span m=''1163520''>that''s</span>
  <span m=''1163720''>all we are</span> <span m=''1164200''>plotting.</span> <span
  m=''1166020''>We are</span> <span m=''1166130''>not really</span> <span m=''1166820''>plotting</span>
  <span m=''1167090''>the</span> <span m=''1167270''>exact</span> <span m=''1167690''>curve.</span>
  <span m=''1172210''>And</span> <span m=''1172430''>the</span> <span m=''1172550''>third</span>
  <span m=''1172970''>point</span> <span m=''1173420''>is</span> <span m=''1173610''>that</span>
  <span m=''1174390''>we</span> <span m=''1174490''>have</span> <span m=''1174720''>a</span>
  <span m=''1175120''>rule of thumb.</span> <span m=''1181770''>Because</span> <span
  m=''1182170''>the</span> <span m=''1182270''>distance</span> <span m=''1182930''>between</span>
  <span m=''1183200''>the</span> <span m=''1183520''>curves</span> <span m=''1183790''>is</span>
  <span m=''1183930''>not</span> <span m=''1184250''>fixed,</span> <span m=''1184790''>it''s</span>
  <span m=''1185190''>still too tedious</span> <span m=''1186050''>to</span> <span
  m=''1186150''>find</span> <span m=''1186390''>the</span> <span m=''1186460''>exact</span>
  <span m=''1186840''>numerical</span> <span m=''1187320''>value</span> <span m=''1187650''>of</span>
  <span m=''1187720''>effective</span> <span m=''1188210''>coding</span> <span m=''1188690''>gain.</span>
  <span m=''1189610''>So</span> <span m=''1190360''>what</span> <span m=''1190510''>we</span>
  <span m=''1190620''>can</span> <span m=''1190800''>find</span> <span m=''1191170''>is
  the</span> <span m=''1191270''>value</span> <span m=''1191620''>of</span> <span
  m=''1191800''>the</span> <span m=''1191930''>nominal</span> <span m=''1192220''>coding</span>
  <span m=''1192750''>gain</span> <span m=''1193580''>and</span> <span m=''1193950''>K_b</span>
  <span m=''1194150''>of</span> <span m=''1194350''>A</span> <span m=''1194910''>exactly,</span>
  <span m=''1195500''>given</span> <span m=''1195810''>a</span> <span m=''1196030''>constellation.</span>
  <span m=''1197390''>So</span> <span m=''1197630''>we</span> <span m=''1197770''>want</span>
  <span m=''1198150''>to</span> <span m=''1198260''>have</span> <span m=''1198480''>a</span>
  <span m=''1198500''>rule</span> <span m=''1198790''>of</span> <span m=''1198940''>thumb</span>
  <span m=''1199240''>for</span> <span m=''1199540''>the</span> <span m=''1200320''>effective</span>
  <span m=''1200760''>coding</span> <span m=''1201190''>gain.</span> </p><p><span
  m=''1202200''>And</span> <span m=''1202520''>the</span> <span m=''1203000''>rule</span>
  <span m=''1203270''>of thumb</span> <span m=''1203460''>is</span> <span m=''1203730''>that</span>
  <span m=''1203910''>the</span> <span m=''1203990''>effective</span> <span m=''1204350''>coding</span>
  <span m=''1204930''>gain</span> <span m=''1206050''>is</span> <span m=''1206280''>given</span>
  <span m=''1206720''>by</span> <span m=''1208120''>the nominal</span> <span m=''1208670''>coding</span>
  <span m=''1209010''>gain in</span> <span m=''1209440''>dB</span> <span m=''1211240''>minus</span>
  <span m=''1211680''>0.2</span> <span m=''1212160''>log2</span> <span m=''1213660''>of</span>
  <span m=''1216050''>K_b</span> <span m=''1216310''>of</span> <span m=''1216570''>A.</span>
  <span m=''1218760''>This</span> <span m=''1218940''>is</span> <span m=''1219100''>in</span>
  <span m=''1219320''>dB.</span> <span m=''1220620''>What this</span> <span m=''1220910''>means</span>
  <span m=''1221300''>is</span> <span m=''1221580''>every</span> <span m=''1221840''>factor</span>
  <span m=''1222140''>of</span> <span m=''1222280''>two</span> <span m=''1222510''>increase</span>
  <span m=''1222940''>is</span> <span m=''1224610''>K_b</span> <span m=''1225450''>results</span>
  <span m=''1225840''>in</span> <span m=''1225910''>a</span> <span m=''1225990''>loss</span>
  <span m=''1226250''>of</span> <span m=''1226380''>0.2</span> <span m=''1226820''>dB</span>
  <span m=''1227240''>in the</span> <span m=''1227390''>effective</span> <span m=''1227850''>coding</span>
  <span m=''1228170''>gain.</span> <span m=''1229590''>OK,</span> <span m=''1230340''>and</span>
  <span m=''1230500''>this</span> <span m=''1230660''>is</span> <span m=''1230790''>our</span>
  <span m=''1231180''>probability</span> <span m=''1231220''>of</span> <span m=''1231420''>bit
  error</span> <span m=''1234930''>of</span> <span m=''1235520''>ten</span> <span
  m=''1235750''>to the minus</span> <span m=''1236220''>five.</span> <span m=''1237600''>So</span>
  <span m=''1238680''>that''s</span> <span m=''1239060''>the</span> <span m=''1239370''>region</span>
  <span m=''1239650''>that</span> <span m=''1239820''>we will</span> <span m=''1240060''>be</span>
  <span m=''1240260''>doing our</span> <span m=''1240530''>analysis</span> <span m=''1240865''>in.</span>
  <span m=''1242060''>So</span> <span m=''1242210''>this</span> <span m=''1242430''>rule</span>
  <span m=''1242750''>of thumb</span> <span m=''1242960''>is</span> <span m=''1243100''>quite</span>
  <span m=''1243320''>helpful.</span> <span m=''1244610''>Are there</span> <span m=''1244760''>any</span>
  <span m=''1245020''>questions?</span> </p><p><span m=''1246594''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1249340''>PROFESSOR: This rule</span> <span m=''1249600''>of thumb?</span>
  <span m=''1250530''>Well,</span> <span m=''1250700''>it</span> <span m=''1250840''>works</span>
  <span m=''1251110''>quite</span> <span m=''1251310''>well</span> <span m=''1251480''>in</span>
  <span m=''1251660''>practice</span> <span m=''1252610''>so</span> <span m=''1253100''>you</span>
  <span m=''1253360''>want to use that rule.</span> </p><p><span m=''1254860''>AUDIENCE:
  [INAUDIBLE]</span> </p><p><span m=''1257360''>PROFESSOR: Right.</span> <span m=''1266360''>If</span>
  <span m=''1266470''>things</span> <span m=''1266800''>are</span> <span m=''1266950''>clear,</span>
  <span m=''1268050''>let</span> <span m=''1268370''>us do</span> <span m=''1268540''>some</span>
  <span m=''1268710''>examples.</span> <span m=''1277090''>So</span> <span m=''1277270''>let
  us</span> <span m=''1277520''>start</span> <span m=''1277860''>with</span> <span
  m=''1277990''>a</span> <span m=''1278090''>2-PAM</span> <span m=''1278560''>for</span>
  <span m=''1279060''>examples.</span> <span m=''1284810''>The</span> <span m=''1284910''>first</span>
  <span m=''1285290''>is</span> <span m=''1285570''>2-PAM</span> <span m=''1286210''>system.</span>
  <span m=''1289760''>What''s</span> <span m=''1289930''>the</span> <span m=''1290170''>effective</span>
  <span m=''1290270''>coding</span> <span m=''1290680''>gain</span> <span m=''1290870''>going</span>
  <span m=''1291090''>to</span> <span m=''1291190''>be</span> <span m=''1291350''>for</span>
  <span m=''1291610''>this</span> <span m=''1292950''>constellation?</span> <span
  m=''1295790''>It''s</span> <span m=''1296420''>going</span> <span m=''1296530''>to</span>
  <span m=''1296640''>be</span> <span m=''1296750''>0</span> <span m=''1297070''>dB,</span>
  <span m=''1297463''>right?</span> <span m=''1298250''>It</span> <span m=''1298320''>just</span>
  <span m=''1298560''>follows</span> <span m=''1298770''>from</span> <span m=''1299020''>the</span>
  <span m=''1299130''>definition.</span> <span m=''1302718''>I</span> <span m=''1303150''>mean</span>
  <span m=''1303465''>the</span> <span m=''1303780''>effective</span> <span m=''1304150''>coding</span>
  <span m=''1304480''>gain</span> <span m=''1305090''>tells</span> <span m=''1305250''>us</span>
  <span m=''1305370''>how</span> <span m=''1305580''>much</span> <span m=''1305850''>gap</span>
  <span m=''1306190''>we</span> <span m=''1306790''>have</span> <span m=''1306970''>between</span>
  <span m=''1307350''>this</span> <span m=''1307560''>new</span> <span m=''1307720''>constellation</span>
  <span m=''1308550''>and</span> <span m=''1308770''>2-PAM.</span> <span m=''1310000''>If</span>
  <span m=''1310150''>your</span> <span m=''1310460''>new</span> <span m=''1310650''>constellation</span>
  <span m=''1311200''>is</span> <span m=''1311310''>2-PAM</span> <span m=''1311920''>itself,</span>
  <span m=''1312400''>we</span> <span m=''1312480''>don''t</span> <span m=''1312730''>have</span>
  <span m=''1312990''>any</span> <span m=''1313790''>effective</span> <span m=''1314240''>coding</span>
  <span m=''1314580''>gain.</span> </p><p><span m=''1316100''>What</span> <span m=''1316550''>about</span>
  <span m=''1316790''>the</span> <span m=''1316960''>4-QAM?</span> <span m=''1321120''>It''s</span>
  <span m=''1321270''>going</span> <span m=''1321380''>to</span> <span m=''1321490''>be</span>
  <span m=''1321600''>still</span> <span m=''1321820''>0,</span> <span m=''1322240''>because</span>
  <span m=''1322540''>a</span> <span m=''1322600''>4-QAM</span> <span m=''1323540''>is</span>
  <span m=''1323640''>a</span> <span m=''1323710''>Cartesian</span> <span m=''1324230''>product</span>
  <span m=''1324600''>of</span> <span m=''1324780''>two</span> <span m=''1325140''>2-PAM</span>
  <span m=''1325550''>constellations.</span> <span m=''1326820''>And</span> <span
  m=''1327020''>we</span> <span m=''1327230''>argued</span> <span m=''1327370''>last</span>
  <span m=''1327670''>time</span> <span m=''1327900''>that</span> <span m=''1328050''>there</span>
  <span m=''1328170''>is</span> <span m=''1328280''>no</span> <span m=''1328430''>coding</span>
  <span m=''1328780''>gain</span> <span m=''1329050''>if you use</span> <span m=''1329410''>a</span>
  <span m=''1329890''>Cartesian</span> <span m=''1330380''>product.</span> <span m=''1331970''>If</span>
  <span m=''1332120''>you</span> <span m=''1332270''>want</span> <span m=''1332460''>to</span>
  <span m=''1332530''>verify</span> <span m=''1333130''>it</span> <span m=''1334400''>using</span>
  <span m=''1335150''>the</span> <span m=''1335320''>framework</span> <span m=''1335820''>that</span>
  <span m=''1335960''>we</span> <span m=''1336100''>have</span> <span m=''1336290''>just</span>
  <span m=''1336830''>developed,</span> <span m=''1338970''>say</span> <span m=''1339420''>we</span>
  <span m=''1339560''>have</span> <span m=''1339800''>four</span> <span m=''1340060''>points.</span>
  <span m=''1341420''>This</span> <span m=''1341620''>point</span> <span m=''1341950''>is</span>
  <span m=''1342370''>alpha,</span> <span m=''1342690''>alpha.</span> <span m=''1344070''>This</span>
  <span m=''1344380''>point</span> <span m=''1344750''>is</span> <span m=''1346260''>minus</span>
  <span m=''1346630''>alpha,</span> <span m=''1347000''>alpha,</span> <span m=''1348450''>minus</span>
  <span m=''1348880''>alpha,</span> <span m=''1349360''>minus</span> <span m=''1350580''>alpha,</span>
  <span m=''1350835''>and</span> <span m=''1351710''>alpha</span> <span m=''1351940''>minus</span>
  <span m=''1352340''>alpha.</span> <span m=''1353600''>The</span> <span m=''1353760''>nominal</span>
  <span m=''1354170''>coding</span> <span m=''1354660''>gain</span> <span m=''1357100''>is</span>
  <span m=''1357350''>given</span> <span m=''1357780''>by</span> <span m=''1358490''>d_min</span>
  <span m=''1359010''>squared</span> <span m=''1359600''>over</span> <span m=''1359870''>4</span>
  <span m=''1360330''>Eb.</span> <span m=''1365080''>The</span> <span m=''1365250''>minimum</span>
  <span m=''1365720''>distance</span> <span m=''1366770''>is</span> <span m=''1367150''>3</span>
  <span m=''1367510''>alpha</span> <span m=''1367780''>between</span> <span m=''1368080''>any</span>
  <span m=''1368290''>two</span> <span m=''1368440''>points.</span> <span m=''1369820''>So</span>
  <span m=''1370020''>we</span> <span m=''1370140''>have</span> <span m=''1370350''>4</span>
  <span m=''1370800''>alpha</span> <span m=''1371110''>squared.</span> </p><p><span
  m=''1372250''>Then</span> <span m=''1372490''>what''s the</span> <span m=''1372910''>energy</span>
  <span m=''1373190''>per</span> <span m=''1373440''>bit?</span> <span m=''1374040''>Well,
  the</span> <span m=''1374170''>energy</span> <span m=''1374570''>per</span> <span
  m=''1374850''>symbol</span> <span m=''1375210''>is</span> <span m=''1375310''>2</span>
  <span m=''1375570''>alpha</span> <span m=''1375950''>squared.</span> <span m=''1377210''>Then</span>
  <span m=''1377400''>we</span> <span m=''1377500''>have</span> <span m=''1377700''>two</span>
  <span m=''1377910''>bits</span> <span m=''1378370''>per</span> <span m=''1378410''>symbol,</span>
  <span m=''1379100''>so</span> <span m=''1379310''>the</span> <span m=''1379600''>energy</span>
  <span m=''1379910''>per bit</span> <span m=''1380240''>is</span> <span m=''1380420''>alpha</span>
  <span m=''1380660''>squared.</span> <span m=''1381520''>So</span> <span m=''1381730''>we</span>
  <span m=''1381890''>have</span> <span m=''1382060''>4</span> <span m=''1382460''>alpha</span>
  <span m=''1382820''>squared,</span> <span m=''1383290''>and</span> <span m=''1383760''>so</span>
  <span m=''1383820''>that''s</span> <span m=''1384110''>1.</span> <span m=''1385080''>So</span>
  <span m=''1385250''>we</span> <span m=''1385350''>do not</span> <span m=''1385550''>have</span>
  <span m=''1385760''>any</span> <span m=''1385900''>nominal</span> <span m=''1386350''>coding</span>
  <span m=''1386690''>gain.</span> <span m=''1388060''>K_b</span> <span m=''1388270''>of</span>
  <span m=''1388700''>A,</span> <span m=''1389310''>what''s</span> <span m=''1389550''>that</span>
  <span m=''1389770''>going</span> <span m=''1390020''>to</span> <span m=''1390280''>be?</span>
  <span m=''1390600''>Well,</span> <span m=''1390870''>we</span> <span m=''1391130''>have</span>
  <span m=''1391740''>two</span> <span m=''1391900''>nearest</span> <span m=''1392300''>neighbors</span>
  <span m=''1392710''>per</span> <span m=''1393020''>symbol,</span> <span m=''1393180''>but</span>
  <span m=''1393770''>we</span> <span m=''1393870''>also</span> <span m=''1394130''>have</span>
  <span m=''1394300''>two</span> <span m=''1394460''>bits</span> <span m=''1394806''>per
  symbol.</span> <span m=''1395830''>So</span> <span m=''1396080''>the</span> <span
  m=''1396200''>number</span> <span m=''1396480''>of</span> <span m=''1396630''>nearest</span>
  <span m=''1397040''>neighbors</span> <span m=''1397470''>per</span> <span m=''1397640''>bit</span>
  <span m=''1397910''>is</span> <span m=''1398070''>going</span> <span m=''1398220''>to</span>
  <span m=''1398380''>be</span> <span m=''1398530''>one.</span> <span m=''1398940''>So</span>
  <span m=''1399350''>your nominal</span> <span m=''1399980''>coding</span> <span
  m=''1400310''>gain</span> <span m=''1400560''>is</span> <span m=''1400700''>1,</span>
  <span m=''1401400''>K_b</span> <span m=''1401690''>of</span> <span m=''1401870''>A</span>
  <span m=''1402200''>is</span> <span m=''1402480''>going</span> <span m=''1402650''>to</span>
  <span m=''1402810''>be</span> <span m=''1402980''>1.</span> <span m=''1403960''>And</span>
  <span m=''1404170''>so</span> <span m=''1404330''>we</span> <span m=''1404430''>do</span>
  <span m=''1404500''>not</span> <span m=''1404710''>see</span> <span m=''1404980''>any</span>
  <span m=''1407590''>coding</span> <span m=''1407800''>gain</span> <span m=''1408220''>for</span>
  <span m=''1408610''>the</span> <span m=''1408700''>4-QAM</span> <span m=''1409250''>system.</span>
  </p><p><span m=''1410880''>Now</span> <span m=''1411060''>let</span> <span m=''1411240''>me</span>
  <span m=''1411420''>do</span> <span m=''1411640''>a</span> <span m=''1411690''>slightly</span>
  <span m=''1412160''>different</span> <span m=''1412610''>case.</span> <span m=''1413660''>Let
  me</span> <span m=''1414230''>start</span> <span m=''1414520''>with</span> <span
  m=''1414630''>a</span> <span m=''1414740''>4-QAM,</span> <span m=''1415870''>but</span>
  <span m=''1416220''>I remove</span> <span m=''1416660''>two</span> <span m=''1416820''>points.</span>
  <span m=''1417770''>I</span> <span m=''1417790''>remove</span> <span m=''1418020''>this</span>
  <span m=''1418240''>point,</span> <span m=''1419770''>and</span> <span m=''1419910''>I</span>
  <span m=''1420070''>remove</span> <span m=''1420230''>this</span> <span m=''1420540''>point.</span>
  <span m=''1420860''>And I</span> <span m=''1421020''>only</span> <span m=''1421310''>keep</span>
  <span m=''1421540''>the</span> <span m=''1421680''>two</span> <span m=''1421860''>points</span>
  <span m=''1422260''>here.</span> <span m=''1423610''>So</span> <span m=''1423830''>I</span>
  <span m=''1423930''>have</span> <span m=''1424050''>a</span> <span m=''1424170''>constellation,</span>
  <span m=''1424890''>say,</span> <span m=''1425750''>A</span> <span m=''1425890''>prime,</span>
  <span m=''1427730''>which</span> <span m=''1428230''>only</span> <span m=''1428470''>has</span>
  <span m=''1428710''>two</span> <span m=''1428880''>points,</span> <span m=''1429300''>one</span>
  <span m=''1429550''>point</span> <span m=''1429790''>here</span> <span m=''1430330''>and</span>
  <span m=''1430500''>one</span> <span m=''1430670''>point</span> <span m=''1430950''>here.</span>
  <span m=''1432490''>So</span> <span m=''1432590''>this</span> <span m=''1432820''>point</span>
  <span m=''1433130''>is</span> <span m=''1433230''>alpha,</span> <span m=''1433640''>alpha,</span>
  <span m=''1434270''>and</span> <span m=''1434460''>this</span> <span m=''1434640''>point</span>
  <span m=''1434960''>is</span> <span m=''1435060''>minus</span> <span m=''1435400''>alpha,</span>
  <span m=''1435750''>minus</span> <span m=''1436140''>alpha.</span> <span m=''1438180''>Any</span>
  <span m=''1438430''>idea</span> <span m=''1438710''>what</span> <span m=''1439380''>the</span>
  <span m=''1439440''>effective</span> <span m=''1439860''>coding</span> <span m=''1440140''>gain</span>
  <span m=''1440480''>will be for</span> <span m=''1440820''>this</span> <span m=''1441190''>case?</span>
  </p><p><span m=''1446000''>AUDIENCE: I think</span> <span m=''1446480''>it''s the
  same.</span> </p><p><span m=''1447920''>PROFESSOR: It''s</span> <span m=''1448160''>still</span>
  <span m=''1448400''>zero,</span> <span m=''1448510''>right?</span> </p><p><span
  m=''1448900''>AUDIENCE: Yeah,</span> <span m=''1449361''>because</span> <span m=''1449822''>it''s</span>
  <span m=''1450283''>saying</span> <span m=''1450744''>that''s 2-PAM.</span> </p><p><span
  m=''1452130''>PROFESSOR: Exactly.</span> <span m=''1452820''>All</span> <span m=''1453100''>this</span>
  <span m=''1453260''>is</span> <span m=''1453470''>a</span> <span m=''1454170''>2-PAM</span>
  <span m=''1454750''>constellation</span> <span m=''1455570''>embedded</span> <span
  m=''1456020''>in</span> <span m=''1457420''>two</span> <span m=''1457600''>dimensions.</span>
  <span m=''1458910''>It''s</span> <span m=''1459180''>2-PAM</span> <span m=''1459840''>along</span>
  <span m=''1460090''>this</span> <span m=''1460340''>line,</span> <span m=''1460700''>right?</span>
  <span m=''1462130''>So</span> <span m=''1462410''>I</span> <span m=''1462500''>cannot</span>
  <span m=''1462760''>hope</span> <span m=''1463070''>to</span> <span m=''1463180''>have</span>
  <span m=''1463360''>a</span> <span m=''1463400''>higher</span> <span m=''1463650''>coding</span>
  <span m=''1464050''>gain</span> <span m=''1464270''>for</span> <span m=''1464440''>this</span>
  <span m=''1464780''>constellation</span> <span m=''1465660''>over the</span> <span
  m=''1466100''>original</span> <span m=''1466330''>one.</span> <span m=''1467620''>I</span>
  <span m=''1467650''>mean</span> <span m=''1467800''>I</span> <span m=''1467870''>told</span>
  <span m=''1468180''>you</span> <span m=''1468350''>the</span> <span m=''1468630''>story</span>
  <span m=''1469030''>that</span> <span m=''1469200''>we</span> <span m=''1469330''>can</span>
  <span m=''1469540''>take</span> <span m=''1469710''>a</span> <span m=''1469760''>subset</span>
  <span m=''1470190''>of</span> <span m=''1470340''>points,</span> <span m=''1471220''>and</span>
  <span m=''1472290''>we</span> <span m=''1472430''>can</span> <span m=''1472650''>increase</span>
  <span m=''1472890''>the</span> <span m=''1472990''>minimum</span> <span m=''1473350''>distance</span>
  <span m=''1473750''>by</span> <span m=''1473860''>throwing</span> <span m=''1474300''>away</span>
  <span m=''1474460''>some</span> <span m=''1474750''>points.</span> <span m=''1475360''>But</span>
  <span m=''1475520''>one</span> <span m=''1475640''>has</span> <span m=''1475780''>to</span>
  <span m=''1475880''>be</span> <span m=''1476000''>careful</span> <span m=''1476460''>in</span>
  <span m=''1476570''>that</span> <span m=''1477240''>analysis.</span> <span m=''1478700''>There</span>
  <span m=''1478920''>could</span> <span m=''1479030''>be</span> <span m=''1479120''>examples</span>
  <span m=''1479445''>where</span> <span m=''1479770''>you''re</span> <span m=''1479990''>strictly</span>
  <span m=''1480650''>improving</span> <span m=''1481170''>the</span> <span m=''1481280''>minimum</span>
  <span m=''1481660''>distance.</span> <span m=''1482760''>Note</span> <span m=''1482950''>that
  the</span> <span m=''1483140''>minimum</span> <span m=''1483490''>distance</span>
  <span m=''1483930''>here</span> <span m=''1488080''>is</span> <span m=''1488260''>going</span>
  <span m=''1488420''>to</span> <span m=''1488580''>8</span> <span m=''1488860''>alpha</span>
  <span m=''1489460''>squared</span> <span m=''1489760''>now.</span> <span m=''1492230''>OK,</span>
  <span m=''1492770''>so</span> <span m=''1493260''>the</span> <span m=''1493330''>minimum
  distance is</span> <span m=''1493710''>strictly</span> <span m=''1494090''>improved.</span>
  </p><p><span m=''1494970''>But</span> <span m=''1495180''>what</span> <span m=''1495360''>happens</span>
  <span m=''1495730''>to</span> <span m=''1495820''>be</span> <span m=''1495890''>your</span>
  <span m=''1496350''>energy</span> <span m=''1496470''>per</span> <span m=''1496820''>bit?</span>
  <span m=''1498530''>Well,</span> <span m=''1498890''>the</span> <span m=''1499040''>energy</span>
  <span m=''1499370''>per</span> <span m=''1499620''>symbol</span> <span m=''1499990''>is</span>
  <span m=''1500140''>2</span> <span m=''1500450''>alpha</span> <span m=''1500850''>squared.</span>
  <span m=''1501780''>But you</span> <span m=''1501900''>only</span> <span m=''1502120''>have</span>
  <span m=''1502300''>one</span> <span m=''1502540''>bit</span> <span m=''1502795''>per</span>
  <span m=''1503050''>symbol,</span> <span m=''1504440''>so</span> <span m=''1504640''>the</span>
  <span m=''1504760''>energy</span> <span m=''1505110''>per</span> <span m=''1505430''>bit</span>
  <span m=''1505650''>is</span> <span m=''1505880''>2</span> <span m=''1505940''>alpha</span>
  <span m=''1506110''>squared.</span> <span m=''1507760''>So your</span> <span m=''1508050''>nominal</span>
  <span m=''1508540''>coding</span> <span m=''1508910''>gain</span> <span m=''1510640''>is</span>
  <span m=''1511350''>d_min</span> <span m=''1511770''>squared</span> <span m=''1512120''>over</span>
  <span m=''1512210''>4</span> <span m=''1512440''>Eb,</span> <span m=''1513560''>which</span>
  <span m=''1513710''>follows</span> <span m=''1514060''>from</span> <span m=''1514280''>the</span>
  <span m=''1514400''>relation</span> <span m=''1514860''>we</span> <span m=''1514970''>have</span>
  <span m=''1515180''>here.</span> <span m=''1517130''>And</span> <span m=''1517450''>d_min</span>
  <span m=''1517740''>squared</span> <span m=''1518060''>is</span> <span m=''1518300''>8</span>
  <span m=''1518620''>alpha</span> <span m=''1518840''>squared.</span> <span m=''1519310''>4</span>
  <span m=''1519720''>Eb</span> <span m=''1520000''>is</span> <span m=''1520280''>also</span>
  <span m=''1520700''>8</span> <span m=''1520990''>alpha</span> <span m=''1521280''>squared,</span>
  <span m=''1521490''>so</span> <span m=''1521630''>the</span> <span m=''1521750''>nominal</span>
  <span m=''1522050''>coding</span> <span m=''1522450''>gain</span> <span m=''1522790''>is
  1,</span> <span m=''1523530''>or</span> <span m=''1523950''>0</span> <span m=''1524210''>dB.</span>
  </p><p><span m=''1527890''>The</span> <span m=''1528250''>average</span> <span m=''1528610''>number</span>
  <span m=''1528920''>of</span> <span m=''1529060''>nearest</span> <span m=''1529500''>neighbors,</span>
  <span m=''1530040''>well,</span> <span m=''1530440''>we only</span> <span m=''1530660''>have</span>
  <span m=''1530810''>one</span> <span m=''1531410''>nearest</span> <span m=''1531740''>neighbor,</span>
  <span m=''1532080''>and</span> <span m=''1532310''>we</span> <span m=''1532440''>have</span>
  <span m=''1532725''>one bit per</span> <span m=''1533010''>symbol,</span> <span
  m=''1533900''>so</span> <span m=''1534120''>that''s --</span> <span m=''1534460''>and</span>
  <span m=''1534790''>this is</span> <span m=''1534910''>A</span> <span m=''1535010''>prime</span>
  <span m=''1535505''>by the way --</span> <span m=''1537950''>is</span> <span m=''1538110''>going</span>
  <span m=''1538280''>to</span> <span m=''1538450''>be</span> <span m=''1538610''>1.</span>
  <span m=''1539270''>And</span> <span m=''1539460''>so</span> <span m=''1540220''>the</span>
  <span m=''1540430''>effective</span> <span m=''1540720''>coding</span> <span m=''1541130''>gain</span>
  <span m=''1541170''>is</span> <span m=''1541440''>still</span> <span m=''1541710''>0</span>
  <span m=''1542150''>dB.</span> </p><p><span m=''1546920''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1551220''>PROFESSOR: So</span> <span m=''1551400''>probability</span>
  <span m=''1552110''>of</span> <span m=''1552240''>symbol</span> <span m=''1552630''>error</span>
  <span m=''1553460''>as</span> <span m=''1553650''>a</span> <span m=''1553700''>function</span>
  <span m=''1554080''>of</span> <span m=''1554170''>alpha</span> <span m=''1554600''>has</span>
  <span m=''1554860''>definitely</span> <span m=''1555370''>decreased,</span> <span
  m=''1555655''>right.</span> <span m=''1556250''>But</span> <span m=''1556810''>the</span>
  <span m=''1556910''>trade-off</span> <span m=''1557270''>we</span> <span m=''1557370''>care</span>
  <span m=''1557610''>about</span> <span m=''1557930''>is</span> <span m=''1558100''>probability</span>
  <span m=''1558290''>of</span> <span m=''1558360''>bit</span> <span m=''1558530''>error</span>
  <span m=''1558740''>as</span> <span m=''1559260''>a</span> <span m=''1559320''>function</span>
  <span m=''1559710''>of</span> <span m=''1559740''>Eb</span> <span m=''1559990''>N_0.</span>
  <span m=''1560740''>In</span> <span m=''1560900''>other words,</span> <span m=''1561525''>this
  curve</span> <span m=''1561800''>is</span> <span m=''1561870''>still</span> <span
  m=''1562130''>here.</span> <span m=''1562620''>It''s</span> <span m=''1562850''>not</span>
  <span m=''1563040''>changed.</span> <span m=''1564370''>I</span> <span m=''1564470''>just</span>
  <span m=''1564630''>shifted</span> <span m=''1565210''>right</span> <span m=''1565850''>by</span>
  <span m=''1566460''>reducing</span> <span m=''1566930''>my</span> <span m=''1567070''>spectral</span>
  <span m=''1567450''>efficiency. OK?</span> </p><p><span m=''1575560''>So</span>
  <span m=''1575710''>let''s</span> <span m=''1575940''>do</span> <span m=''1576060''>one</span>
  <span m=''1576270''>last</span> <span m=''1576590''>example</span> <span m=''1578340''>just</span>
  <span m=''1578560''>to</span> <span m=''1578640''>prove</span> <span m=''1578920''>that</span>
  <span m=''1579470''>it''s</span> <span m=''1579680''>not</span> <span m=''1579810''>always</span>
  <span m=''1580190''>the</span> <span m=''1580310''>case</span> <span m=''1580660''>that</span>
  <span m=''1580890''>you</span> <span m=''1581380''>get</span> <span m=''1581610''>nothing</span>
  <span m=''1581990''>by</span> <span m=''1582230''>removing</span> <span m=''1582990''>points.</span>
  <span m=''1655990''>OK,</span> <span m=''1657440''>so</span> <span m=''1657740''>the</span>
  <span m=''1657880''>contellation</span> <span m=''1658780''>that</span> <span m=''1659040''>I</span>
  <span m=''1659260''>have</span> <span m=''1659480''>in</span> <span m=''1659610''>mind</span>
  <span m=''1661140''>is</span> <span m=''1662350''>the</span> <span m=''1662530''>one</span>
  <span m=''1662690''>I</span> <span m=''1662770''>introduced</span> <span m=''1663290''>last</span>
  <span m=''1663690''>time.</span> <span m=''1665420''>We''ll</span> <span m=''1665590''>start</span>
  <span m=''1665910''>with</span> <span m=''1666010''>a</span> <span m=''1666100''>3,
  4</span> <span m=''1666670''>Cartesian</span> <span m=''1667250''>product</span>
  <span m=''1667640''>of</span> <span m=''1667870''>2-PAM.</span> <span m=''1670170''>OK,</span>
  <span m=''1670450''>so</span> <span m=''1670590''>in</span> <span m=''1670670''>three</span>
  <span m=''1670850''>dimensions</span> <span m=''1671480''>it''s</span> <span m=''1672120''>a</span>
  <span m=''1672370''>cube,</span> <span m=''1673220''>and</span> <span m=''1674310''>the</span>
  <span m=''1674460''>3,4</span> <span m=''1674980''>Cartesian</span> <span m=''1675570''>product</span>
  <span m=''1675900''>will</span> <span m=''1676060''>have</span> <span m=''1676770''>a</span>
  <span m=''1676860''>point</span> <span m=''1677220''>on</span> <span m=''1677360''>each</span>
  <span m=''1677840''>vertex</span> <span m=''1678360''>of</span> <span m=''1678490''>the</span>
  <span m=''1678620''>cube.</span> <span m=''1679260''>And</span> <span m=''1679530''>we</span>
  <span m=''1679580''>only</span> <span m=''1679720''>keep</span> <span m=''1679870''>four</span>
  <span m=''1680220''>points.</span> <span m=''1681150''>So</span> <span m=''1681480''>the</span>
  <span m=''1681570''>points</span> <span m=''1681940''>we</span> <span m=''1682140''>keep</span>
  <span m=''1682460''>are</span> <span m=''1682680''>these</span> <span m=''1682990''>four</span>
  <span m=''1683220''>points.  OK?</span> </p><p><span m=''1689800''>So</span> <span
  m=''1690140''>I</span> <span m=''1690300''>write</span> <span m=''1690910''>B,</span>
  <span m=''1695250''>the</span> <span m=''1695700''>coordinates</span> <span m=''1696880''>are</span>
  <span m=''1696940''>alpha,</span> <span m=''1697190''>alpha,</span> <span m=''1697270''>alpha,</span>
  <span m=''1698900''>minus</span> <span m=''1699300''>alpha,</span> <span m=''1699690''>minus</span>
  <span m=''1700060''>alpha,</span> <span m=''1700790''>alpha,</span> <span m=''1702410''>minus</span>
  <span m=''1702860''>alpha,</span> <span m=''1703390''>alpha,</span> <span m=''1703620''>minus</span>
  <span m=''1704540''>alpha,</span> <span m=''1706280''>and</span> <span m=''1708730''>alpha,</span>
  <span m=''1709520''>minus</span> <span m=''1709920''>alpha,</span> <span m=''1710640''>minus</span>
  <span m=''1711000''>alpha.</span> <span m=''1711770''>So</span> <span m=''1711980''>these</span>
  <span m=''1712240''>are</span> <span m=''1712370''>the</span> <span m=''1712520''>vertices.</span>
  <span m=''1713650''>These</span> <span m=''1713780''>are</span> <span m=''1713880''>the
  coordinates</span> <span m=''1714230''>of</span> <span m=''1714740''>the</span>
  <span m=''1714840''>four</span> <span m=''1715160''>points</span> <span m=''1715570''>here</span>
  <span m=''1717260''>where</span> <span m=''1717510''>we have</span> <span m=''1717640''>the</span>
  <span m=''1717710''>standard</span> <span m=''1718190''>x,</span> <span m=''1718390''>y</span>
  <span m=''1718550''>and</span> <span m=''1718710''>z-axis,</span> <span m=''1719260''>which</span>
  <span m=''1719450''>I''m not</span> <span m=''1719770''>drawing</span> <span m=''1720190''>because</span>
  <span m=''1720550''>it will</span> <span m=''1720650''>just</span> <span m=''1721000''>look</span>
  <span m=''1721280''>confusing.</span> </p><p><span m=''1722360''>So</span> <span
  m=''1722550''>now</span> <span m=''1723350''>we''ll</span> <span m=''1723420''>see</span>
  <span m=''1723610''>that</span> <span m=''1723800''>for</span> <span m=''1724010''>this</span>
  <span m=''1724230''>particular</span> <span m=''1725190''>signal</span> <span m=''1725690''>set,</span>
  <span m=''1725950''>we</span> <span m=''1726100''>do</span> <span m=''1726320''>have</span>
  <span m=''1726510''>a</span> <span m=''1726930''>coding</span> <span m=''1727310''>gain,</span>
  <span m=''1728150''>OK?</span> <span m=''1729170''>Let''s</span> <span m=''1729440''>find</span>
  <span m=''1729690''>the</span> <span m=''1729770''>minimum</span> <span m=''1730200''>distance.</span>
  <span m=''1734160''>The</span> <span m=''1734270''>minimum</span> <span m=''1734660''>distance</span>
  <span m=''1735110''>here</span> <span m=''1735400''>is</span> <span m=''1735520''>what?</span>
  <span m=''1736740''>It''s</span> <span m=''1736950''>the</span> <span m=''1737040''>distance</span>
  <span m=''1737480''>along</span> <span m=''1737860''>a</span> <span m=''1737980''>diagonal.</span>
  <span m=''1740010''>And</span> <span m=''1740430''>the</span> <span m=''1740530''>diagonal</span>
  <span m=''1741020''>is</span> <span m=''1741290''>of length</span> <span m=''1742250''>to
  --</span> <span m=''1742590''>each</span> <span m=''1743020''>side</span> <span
  m=''1743640''>of</span> <span m=''1743800''>the</span> <span m=''1743910''>cube</span>
  <span m=''1744200''>is</span> <span m=''1744390''>off-length</span> <span m=''1744810''>to</span>
  <span m=''1744990''>alpha.</span> <span m=''1748790''>So</span> <span m=''1749060''>the</span>
  <span m=''1749210''>diagonal</span> <span m=''1749710''>is</span> <span m=''1749920''>of
  length</span> <span m=''1751110''>to</span> <span m=''1752770''>alpha.</span> <span
  m=''1753930''>So</span> <span m=''1754290''>d_min</span> <span m=''1754490''>squared</span>
  <span m=''1755010''>is</span> <span m=''1755180''>8</span> <span m=''1755360''>alpha</span>
  <span m=''1755820''>squared.</span> </p><p><span m=''1759450''>What</span> <span
  m=''1759650''>is</span> <span m=''1759770''>the</span> <span m=''1760050''>energy</span>
  <span m=''1760330''>per bit</span> <span m=''1760690''>going</span> <span m=''1760890''>to</span>
  <span m=''1761080''>be</span> <span m=''1761270''>in</span> <span m=''1761370''>this</span>
  <span m=''1761600''>case?</span> <span m=''1773030''>Well,</span> <span m=''1773330''>what''s
  the energy</span> <span m=''1773670''>per</span> <span m=''1773880''>symbol</span>
  <span m=''1774310''>now?</span> </p><p><span m=''1775226''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1777520''>PROFESSOR: 3</span> <span m=''1777890''>alpha</span>
  <span m=''1778340''>squared</span> <span m=''1778590''>over</span> <span m=''1778900''>2</span>
  <span m=''1779140''>is the</span> <span m=''1779370''>Eb,</span> <span m=''1779870''>right?</span>
  <span m=''1780140''>We have</span> <span m=''1780680''>3</span> <span m=''1781070''>alpha</span>
  <span m=''1781435''>squared</span> <span m=''1782190''>units of</span> <span m=''1782400''>energy</span>
  <span m=''1782990''>per</span> <span m=''1783340''>symbol.</span> <span m=''1783890''>We</span>
  <span m=''1784030''>have</span> <span m=''1784730''>four</span> <span m=''1785360''>points,</span>
  <span m=''1785860''>so we</span> <span m=''1786170''>have</span> <span m=''1786760''>two
  bits</span> <span m=''1787123''>per symbol.</span> <span m=''1788230''>So the</span>
  <span m=''1788600''>energy</span> <span m=''1789000''>per</span> <span m=''1789380''>bit</span>
  <span m=''1790990''>is</span> <span m=''1791280''>3</span> <span m=''1791700''>alpha</span>
  <span m=''1792105''>squared</span> <span m=''1792510''>over</span> <span m=''1792988''>2.</span>
  <span m=''1794900''>So</span> <span m=''1795580''>now</span> <span m=''1795810''>if</span>
  <span m=''1795970''>I</span> <span m=''1796040''>look</span> <span m=''1796220''>at</span>
  <span m=''1796390''>my</span> <span m=''1796520''>nominal</span> <span m=''1796940''>coding</span>
  <span m=''1797380''>gain,</span> <span m=''1800800''>that''s</span> <span m=''1801070''>going</span>
  <span m=''1801270''>to</span> <span m=''1801470''>be</span> <span m=''1802430''>d_min</span>
  <span m=''1802970''>squared</span> <span m=''1803950''>over</span> <span m=''1804820''>4</span>
  <span m=''1805360''>Eb.</span> <span m=''1807210''>d_min</span> <span m=''1807690''>squared</span>
  <span m=''1808180''>is</span> <span m=''1808300''>8</span> <span m=''1808700''>alpha</span>
  <span m=''1809100''>squared.</span> <span m=''1810640''>4</span> <span m=''1810980''>dB</span>
  <span m=''1811410''>is</span> <span m=''1811520''>6</span> <span m=''1812090''>alpha</span>
  <span m=''1812380''>squared.</span> <span m=''1814170''>So</span> <span m=''1814430''>that''s</span>
  <span m=''1814830''>4/3.</span> <span m=''1817080''>On</span> <span m=''1817320''>a
  linear</span> <span m=''1817690''>scale</span> <span m=''1818310''>and</span> <span
  m=''1818470''>on</span> <span m=''1818710''>a</span> <span m=''1818860''>dB</span>
  <span m=''1819230''>scale,</span> <span m=''1820670''>this</span> <span m=''1820880''>is</span>
  <span m=''1821010''>going</span> <span m=''1821280''>to</span> <span m=''1821410''>be?</span>
  <span m=''1832680''>You guys</span> <span m=''1832830''>should</span> <span m=''1833060''>remember</span>
  <span m=''1833410''>your</span> <span m=''1833710''>dB</span> <span m=''1834188''>tables.</span>
  </p><p><span m=''1837534''>AUDIENCE: 0.2?</span> </p><p><span m=''1839446''>PROFESSOR:
  12.</span> <span m=''1840410''>You</span> <span m=''1840460''>have</span> <span
  m=''1840620''>to</span> <span m=''1840800''>multiply</span> <span m=''1840840''>by</span>
  <span m=''1841080''>ten.</span> <span m=''1842510''>So</span> <span m=''1842990''>actually</span>
  <span m=''1843380''>I</span> <span m=''1843430''>think</span> <span m=''1843590''>it''s</span>
  <span m=''1843710''>1.3,</span> <span m=''1844360''>more</span> <span m=''1844560''>like</span>
  <span m=''1844720''>1.3</span> <span m=''1845485''>dB</span> <span m=''1845800''>if</span>
  <span m=''1845990''>you look at the</span> <span m=''1846510''>last</span> <span
  m=''1846700''>significant</span> <span m=''1847430''>digit.</span> <span m=''1850730''>OK,</span>
  <span m=''1851650''>so</span> <span m=''1853910''>what''s</span> <span m=''1854250''>K_b</span>
  <span m=''1854640''>of</span> <span m=''1854700''>A</span> <span m=''1854960''>going</span>
  <span m=''1855120''>to</span> <span m=''1855280''>be</span> <span m=''1855430''>in</span>
  <span m=''1855540''>this</span> <span m=''1855780''>case?</span> <span m=''1856760''>Or</span>
  <span m=''1856890''>K_b</span> <span m=''1857050''>of</span> <span m=''1857290''>B</span>
  <span m=''1857760''>I</span> <span m=''1857830''>should</span> <span m=''1858090''>say.</span>
  <span m=''1859055''>I''m calling</span> <span m=''1859390''>the</span> <span m=''1859510''>signal</span>
  <span m=''1859860''>set</span> <span m=''1860130''>B</span> <span m=''1860280''>here.</span>
  <span m=''1861650''>So</span> <span m=''1864250''>what</span> <span m=''1864500''>is</span>
  <span m=''1864760''>K_b</span> <span m=''1864980''>if</span> <span m=''1865290''>B</span>
  <span m=''1865440''>going</span> <span m=''1865680''>to</span> <span m=''1865810''>be?</span>
  </p><p><span m=''1873820''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''1875260''>PROFESSOR:
  3 by 2, right?</span> <span m=''1877180''>You have</span> <span m=''1877680''>three</span>
  <span m=''1877890''>nearest</span> <span m=''1878060''>neighbors</span> <span m=''1878330''>per</span>
  <span m=''1878500''>point,</span> <span m=''1879380''>for</span> <span m=''1879570''>each</span>
  <span m=''1879760''>point</span> <span m=''1880010''>has</span> <span m=''1880140''>three</span>
  <span m=''1880380''>nearest</span> <span m=''1880800''>neighbors.</span> <span m=''1881150''>They''re</span>
  <span m=''1881350''>all</span> <span m=''1881480''>equidistant.</span> <span m=''1882840''>And</span>
  <span m=''1883210''>you</span> <span m=''1883370''>have</span> <span m=''1883530''>two
  bits</span> <span m=''1883660''>per symbol.  OK?</span> <span m=''1886680''>So</span>
  <span m=''1887070''>if</span> <span m=''1887160''>you</span> <span m=''1887280''>work</span>
  <span m=''1887380''>out your</span> <span m=''1887830''>effective</span> <span m=''1888290''>coding</span>
  <span m=''1888640''>again</span> <span m=''1889350''>using</span> <span m=''1889650''>this</span>
  <span m=''1890000''>rule</span> <span m=''1890250''>of thumb</span> <span m=''1890510''>here,</span>
  <span m=''1891980''>take</span> <span m=''1892100''>gamma_c</span> <span m=''1892680''>of</span>
  <span m=''1893030''>A</span> <span m=''1893200''>in</span> <span m=''1893370''>dB</span>
  <span m=''1893540''>and subtract</span> <span m=''1893950''>0.2</span> <span m=''1894370''>log2</span>
  <span m=''1895540''>you</span> <span m=''1895690''>will</span> <span m=''1895810''>see</span>
  <span m=''1896030''>that the</span> <span m=''1896170''>effective</span> <span m=''1896710''>coding</span>
  <span m=''1897110''>gain</span> <span m=''1897460''>is</span> <span m=''1897830''>approximately</span>
  <span m=''1898610''>1</span> <span m=''1898870''>dB.</span> <span m=''1915730''>Are
  there any</span> <span m=''1915910''>questions?</span> </p><p><span m=''1920970''>OK,</span>
  <span m=''1921250''>so</span> <span m=''1921590''>it might</span> <span m=''1921680''>seem</span>
  <span m=''1921970''>that</span> <span m=''1922240''>this is</span> <span m=''1922580''>still</span>
  <span m=''1922750''>not a</span> <span m=''1922800''>very</span> <span m=''1923000''>impressive</span>
  <span m=''1923480''>number.</span> <span m=''1923760''>Yes,</span> <span m=''1923950''>you</span>
  <span m=''1924140''>had a question.</span> </p><p><span m=''1925100''>AUDIENCE:
  What</span> <span m=''1925430''>was it</span> <span m=''1925760''>about</span> <span
  m=''1926070''>this</span> <span m=''1926250''>constellation</span> <span m=''1927060''>that</span>
  <span m=''1927580''>gave</span> <span m=''1927810''>us</span> <span m=''1928000''>coding</span>
  <span m=''1928340''>gain?</span> <span m=''1929082''>Was is the face</span> <span
  m=''1929554''>that we went to</span> <span m=''1930026''>higher</span> <span m=''1930498''>dimensions?</span>
  </p><p><span m=''1932390''>PROFESSOR: Right,</span> <span m=''1932920''>so</span>
  <span m=''1933430''>usually</span> <span m=''1934000''>you do</span> <span m=''1934130''>get</span>
  <span m=''1934260''>a</span> <span m=''1934460''>coding</span> <span m=''1934810''>gain</span>
  <span m=''1935040''>if</span> <span m=''1935240''>you</span> <span m=''1936180''>trade-off</span>
  <span m=''1936830''>minimum</span> <span m=''1937200''>distance</span> <span m=''1938340''>with</span>
  <span m=''1938550''>spectral</span> <span m=''1939010''>efficiency.</span> <span
  m=''1940400''>So</span> <span m=''1940530''>that''s</span> <span m=''1940710''>usually</span>
  <span m=''1941670''>the</span> <span m=''1941900''>case.</span> <span m=''1942820''>So</span>
  <span m=''1942980''>that''s</span> <span m=''1943210''>why</span> <span m=''1943520''>I</span>
  <span m=''1943580''>presented</span> <span m=''1943980''>you an</span> <span m=''1944150''>example</span>
  <span m=''1944670''>of</span> <span m=''1944810''>that</span> <span m=''1945030''>case.</span>
  <span m=''1946200''>It''s just</span> <span m=''1946420''>that this</span> <span
  m=''1946550''>was</span> <span m=''1946800''>a very</span> <span m=''1946900''>special</span>
  <span m=''1947390''>case</span> <span m=''1947730''>where you end</span> <span m=''1948090''>up</span>
  <span m=''1948180''>with</span> <span m=''1948290''>a</span> <span m=''1948400''>2-PAM</span>
  <span m=''1948980''>constellation</span> <span m=''1949690''>to</span> <span m=''1949800''>start</span>
  <span m=''1950290''>with.</span> </p><p><span m=''1956010''>OK,</span> <span m=''1958430''>so</span>
  <span m=''1959530''>the</span> <span m=''1959860''>comment</span> <span m=''1960270''>I</span>
  <span m=''1960350''>was</span> <span m=''1960430''>going</span> <span m=''1960590''>to</span>
  <span m=''1960740''>make</span> <span m=''1960980''>is</span> <span m=''1961120''>that</span>
  <span m=''1961260''>1.2</span> <span m=''1961760''>dB</span> <span m=''1961980''>still</span>
  <span m=''1962440''>might</span> <span m=''1962660''>not</span> <span m=''1962880''>be
  like</span> <span m=''1963230''>a</span> <span m=''1963290''>very</span> <span m=''1963510''>impressive</span>
  <span m=''1963990''>number.</span> <span m=''1964510''>I mean</span> <span m=''1965000''>after</span>
  <span m=''1965240''>all</span> <span m=''1965390''>the</span> <span m=''1965530''>hard
  work,</span> <span m=''1965825''>you</span> <span m=''1966120''>just</span> <span
  m=''1966360''>get</span> <span m=''1966520''>1</span> <span m=''1966860''>dB</span>
  <span m=''1967230''>effective</span> <span m=''1967640''>coding</span> <span m=''1967970''>gain.</span>
  <span m=''1968660''>So the</span> <span m=''1969070''>question</span> <span m=''1969450''>to
  ask</span> <span m=''1969970''>at</span> <span m=''1970140''>this</span> <span m=''1970330''>point</span>
  <span m=''1970740''>is</span> <span m=''1970920''>are</span> <span m=''1971050''>there</span>
  <span m=''1971170''>any</span> <span m=''1971290''>constellations</span> <span m=''1972580''>that</span>
  <span m=''1972770''>have</span> <span m=''1972890''>much</span> <span m=''1973140''>higher</span>
  <span m=''1973440''>coding</span> <span m=''1973770''>gains?</span> <span m=''1974980''>In</span>
  <span m=''1975130''>particular,</span> <span m=''1976480''>other</span> <span m=''1976910''>constellations</span>
  <span m=''1977690''>that</span> <span m=''1977910''>come</span> <span m=''1978100''>close</span>
  <span m=''1978440''>to</span> <span m=''1978550''>the</span> <span m=''1978650''>Shannon</span>
  <span m=''1979030''>limit</span> <span m=''1979160''>at</span> <span m=''1979280''>all.</span>
  </p><p><span m=''1981340''>And</span> <span m=''1981670''>we''ll</span> <span m=''1981780''>look</span>
  <span m=''1981940''>at</span> <span m=''1982100''>one</span> <span m=''1982830''>interesting</span>
  <span m=''1983380''>class</span> <span m=''1983770''>of</span> <span m=''1983880''>signal</span>
  <span m=''1984280''>sets,</span> <span m=''1985170''>which</span> <span m=''1985370''>are</span>
  <span m=''1985470''>known</span> <span m=''1985760''>as</span> <span m=''1986140''>orthogonal</span>
  <span m=''1986410''>signal</span> <span m=''1986510''>sets.</span> <span m=''1998540''>And</span>
  <span m=''1999030''>you</span> <span m=''1999170''>probably</span> <span m=''1999510''>saw</span>
  <span m=''1999750''>these</span> <span m=''1999930''>examples</span> <span m=''2000590''>back</span>
  <span m=''2000790''>in</span> <span m=''2000920''>6.450,</span> <span m=''2001970''>but</span>
  <span m=''2002140''>we''re just</span> <span m=''2002430''>reviewing it</span> <span
  m=''2002940''>again</span> <span m=''2003140''>here.</span> <span m=''2004070''>And</span>
  <span m=''2004330''>these</span> <span m=''2004490''>signal</span> <span m=''2004810''>sets</span>
  <span m=''2005130''>have</span> <span m=''2005250''>a</span> <span m=''2005370''>property</span>
  <span m=''2006310''>that</span> <span m=''2007010''>as</span> <span m=''2007120''>you</span>
  <span m=''2007440''>increase</span> <span m=''2007620''>the</span> <span m=''2007720''>number</span>
  <span m=''2007940''>of</span> <span m=''2008140''>dimensions,</span> <span m=''2009410''>you</span>
  <span m=''2009630''>come</span> <span m=''2010040''>arbitrarily</span> <span m=''2010530''>close</span>
  <span m=''2010780''>to</span> <span m=''2010880''>the</span> <span m=''2010960''>Shannon</span>
  <span m=''2011340''>limit.</span> <span m=''2012770''>So</span> <span m=''2013080''>the</span>
  <span m=''2013210''>definition</span> <span m=''2013790''>of</span> <span m=''2013930''>the</span>
  <span m=''2014050''>signal</span> <span m=''2014355''>sets</span> <span m=''2014660''>is</span>
  <span m=''2015780''>your</span> <span m=''2016090''>A --</span> <span m=''2017110''>it''s
  a</span> <span m=''2017450''>collection</span> <span m=''2017930''>of</span> <span
  m=''2018080''>signals</span> <span m=''2018620''>aj,</span> <span m=''2019825''>where</span>
  <span m=''2020160''>j</span> <span m=''2020430''>goes from</span> <span m=''2020920''>1
  to</span> <span m=''2021400''>M</span> <span m=''2023450''>such</span> <span m=''2023850''>that</span>
  <span m=''2024460''>the</span> <span m=''2024640''>inner</span> <span m=''2024920''>product</span>
  <span m=''2026250''>between</span> <span m=''2026770''>ai</span> <span m=''2027450''>and</span>
  <span m=''2027770''>aj</span> <span m=''2029360''>is</span> <span m=''2030780''>E</span>
  <span m=''2031085''>A</span> <span m=''2031950''>times</span> <span m=''2032450''>delta_i,j,</span>
  <span m=''2033970''>meaning</span> <span m=''2034260''>that</span> <span m=''2034420''>if
  i</span> <span m=''2034860''>is</span> <span m=''2035050''>not equal</span> <span
  m=''2035240''>to</span> <span m=''2035450''>j,</span> <span m=''2035740''>the two</span>
  <span m=''2036030''>signals</span> <span m=''2036440''>are</span> <span m=''2036620''>orthogonal.</span>
  <span m=''2036920''>And</span> <span m=''2037320''>if</span> <span m=''2037470''>i</span>
  <span m=''2037760''>equals</span> <span m=''2038110''>j,</span> <span m=''2039040''>the</span>
  <span m=''2039220''>energy</span> <span m=''2039700''>is</span> <span m=''2040140''>E(A).</span>
  </p><p><span m=''2041560''>Geometrically,</span> <span m=''2042870''>we</span> <span
  m=''2043050''>have</span> <span m=''2043250''>two</span> <span m=''2043430''>points.</span>
  <span m=''2045420''>The two</span> <span m=''2045570''>points</span> <span m=''2045710''>can
  be</span> <span m=''2045890''>thought of</span> <span m=''2046290''>as</span> <span
  m=''2047000''>two</span> <span m=''2047220''>points</span> <span m=''2047570''>on</span>
  <span m=''2047830''>the</span> <span m=''2048639''>two</span> <span m=''2048840''>axes.</span>
  <span m=''2049870''>So</span> <span m=''2050050''>this</span> <span m=''2050219''>is</span>
  <span m=''2050429''>a</span> <span m=''2050530''>case</span> <span m=''2050770''>when</span>
  <span m=''2050960''>M</span> <span m=''2051090''>equals</span> <span m=''2051370''>2.</span>
  <span m=''2052650''>When</span> <span m=''2053280''>M</span> <span m=''2053320''>equals</span>
  <span m=''2053550''>3,</span> <span m=''2054230''>the</span> <span m=''2054580''>three
  points</span> <span m=''2054909''>will</span> <span m=''2055170''>lie</span> <span
  m=''2055310''>on</span> <span m=''2055960''>those</span> <span m=''2056090''>three</span>
  <span m=''2056139''>corresponding</span> <span m=''2056570''>axes.</span> <span
  m=''2059650''>So</span> <span m=''2060230''>this</span> <span m=''2060469''>is</span>
  <span m=''2060590''>the</span> <span m=''2060710''>case</span> <span m=''2060940''>when</span>
  <span m=''2061409''>M</span> <span m=''2061530''>equals 3</span> <span m=''2062010''>and</span>
  <span m=''2062170''>so</span> <span m=''2062320''>on.</span> <span m=''2062870''>So</span>
  <span m=''2063040''>generally</span> <span m=''2063389''>when</span> <span m=''2063679''>you
  have</span> <span m=''2063850''>M points,</span> <span m=''2064489''>your</span>
  <span m=''2064760''>signal</span> <span m=''2065120''>spatializes</span> <span m=''2065375''>in</span>
  <span m=''2065989''>M</span> <span m=''2066110''>dimensions,</span> <span m=''2067170''>and</span>
  <span m=''2067330''>each</span> <span m=''2067480''>point</span> <span m=''2067739''>can</span>
  <span m=''2067860''>be</span> <span m=''2067900''>thought</span> <span m=''2068020''>of</span>
  <span m=''2068469''>as</span> <span m=''2068610''>a</span> <span m=''2068670''>point</span>
  <span m=''2068969''>on</span> <span m=''2069070''>one</span> <span m=''2069210''>of</span>
  <span m=''2069320''>the</span> <span m=''2069389''>axes.</span> </p><p><span m=''2071860''>So</span>
  <span m=''2073570''>if</span> <span m=''2073679''>you</span> <span m=''2073770''>look</span>
  <span m=''2073929''>at</span> <span m=''2074040''>the</span> <span m=''2074100''>distance</span>
  <span m=''2074530''>between</span> <span m=''2074810''>any</span> <span m=''2074989''>two</span>
  <span m=''2075179''>points,</span> <span m=''2076610''>it''s</span> <span m=''2076760''>the</span>
  <span m=''2076889''>norm</span> <span m=''2077190''>of</span> <span m=''2077659''>ai</span>
  <span m=''2079210''>minus</span> <span m=''2079659''>aj</span> <span m=''2080020''>squared.</span>
  <span m=''2081850''>I</span> <span m=''2081969''>could</span> <span m=''2082159''>simplify</span>
  <span m=''2082770''>this</span> <span m=''2083070''>simply</span> <span m=''2083480''>as</span>
  <span m=''2083639''>the</span> <span m=''2083730''>norm</span> <span m=''2084070''>of</span>
  <span m=''2084370''>ai</span> <span m=''2084530''>squared</span> <span m=''2085969''>plus</span>
  <span m=''2086210''>the</span> <span m=''2086300''>norm of</span> <span m=''2086860''>aj</span>
  <span m=''2087340''>squared</span> <span m=''2088880''>because</span> <span m=''2089310''>the</span>
  <span m=''2089409''>end</span> <span m=''2089719''>product</span> <span m=''2090050''>is</span>
  <span m=''2090170''>going</span> <span m=''2090330''>to</span> <span m=''2090480''>be</span>
  <span m=''2090630''>zero.</span> <span m=''2092630''>OK,</span> <span m=''2093500''>now</span>
  <span m=''2093710''>ai</span> <span m=''2094130''>squared</span> <span m=''2094290''>is</span>
  <span m=''2094420''>going</span> <span m=''2094590''>to</span> <span m=''2094710''>be</span>
  <span m=''2095110''>E(A).</span> <span m=''2095760''>aj</span> <span m=''2096040''>squared
  is</span> <span m=''2096130''>going</span> <span m=''2096290''>to</span> <span m=''2096440''>be</span>
  <span m=''2096810''>E(A).</span> <span m=''2097810''>So</span> <span m=''2098000''>this</span>
  <span m=''2098290''>is</span> <span m=''2099286''>2E(A).</span> <span m=''2101280''>So</span>
  <span m=''2101480''>what</span> <span m=''2101680''>we''re</span> <span m=''2101840''>saying</span>
  <span m=''2102230''>here</span> <span m=''2102530''>is</span> <span m=''2102630''>that</span>
  <span m=''2102780''>every</span> <span m=''2103030''>point</span> <span m=''2103330''>is</span>
  <span m=''2103440''>equidistant</span> <span m=''2104090''>from</span> <span m=''2104260''>every</span>
  <span m=''2104530''>other</span> <span m=''2104780''>point,</span> <span m=''2105540''>and</span>
  <span m=''2105700''>the</span> <span m=''2106410''>square</span> <span m=''2106700''>of</span>
  <span m=''2106790''>the</span> <span m=''2106880''>distance</span> <span m=''2107470''>is</span>
  <span m=''2108010''>2</span> <span m=''2108492''>E(A).</span> <span m=''2109940''>OK?</span>
  <span m=''2113440''>So</span> <span m=''2113830''>in other</span> <span m=''2114260''>words,</span>
  <span m=''2114640''>the</span> <span m=''2115460''>average</span> <span m=''2115810''>number</span>
  <span m=''2116110''>of</span> <span m=''2116220''>nearest</span> <span m=''2116700''>neighbors</span>
  <span m=''2118070''>is</span> <span m=''2118230''>always</span> <span m=''2118570''>going</span>
  <span m=''2118750''>to</span> <span m=''2118930''>be</span> <span m=''2119180''>a</span>
  <span m=''2119290''>M minus</span> <span m=''2119910''>1.</span> </p><p><span m=''2124310''>So</span>
  <span m=''2124560''>let</span> <span m=''2124790''>us</span> <span m=''2124940''>calculate</span>
  <span m=''2125510''>the</span> <span m=''2125610''>nominal</span> <span m=''2126100''>coding</span>
  <span m=''2126480''>gain</span> <span m=''2126790''>for</span> <span m=''2127470''>this</span>
  <span m=''2127700''>constellation.</span> <span m=''2132190''>That''s</span> <span
  m=''2132490''>going</span> <span m=''2132730''>to</span> <span m=''2132870''>be</span>
  <span m=''2133210''>d_min</span> <span m=''2133720''>squared</span> <span m=''2137710''>over</span>
  <span m=''2137940''>4</span> <span m=''2138300''>Eb.</span> <span m=''2141590''>d_min</span>
  <span m=''2142210''>squared</span> <span m=''2142760''>is</span> <span m=''2143140''>2E(A)</span>
  <span m=''2147520''>over</span> <span m=''2147840''>4</span> <span m=''2148270''>Eb.</span>
  <span m=''2149160''>Well,</span> <span m=''2149390''>the energy</span> <span m=''2149760''>per
  bit</span> <span m=''2150350''>is</span> <span m=''2150510''>the</span> <span m=''2150600''>energy</span>
  <span m=''2151050''>per</span> <span m=''2151250''>symbol,</span> <span m=''2152790''>which</span>
  <span m=''2153090''>is</span> <span m=''2153220''>E(A)</span> <span m=''2154050''>over</span>
  <span m=''2154380''>the</span> <span m=''2154460''>number</span> <span m=''2154580''>of</span>
  <span m=''2154690''>bits per</span> <span m=''2154960''>symbol,</span> <span m=''2156070''>which</span>
  <span m=''2156300''>is</span> <span m=''2156430''>log M</span> <span m=''2156890''>to</span>
  <span m=''2157000''>the</span> <span m=''2157120''>base</span> <span m=''2157530''>2.</span>
  <span m=''2159710''>And</span> <span m=''2163070''>this</span> <span m=''2163340''>I''m</span>
  <span m=''2163470''>going</span> <span m=''2163650''>to</span> <span m=''2163820''>write</span>
  <span m=''2164030''>here</span> <span m=''2167390''>is</span> <span m=''2168700''>1/2</span>
  <span m=''2169090''>log</span> <span m=''2169520''>M</span> <span m=''2169610''>to
  the</span> <span m=''2169830''>base</span> <span m=''2170080''>2.</span> <span m=''2171890''>So</span>
  <span m=''2172080''>as</span> <span m=''2172280''>I</span> <span m=''2172440''>increase</span>
  <span m=''2173150''>my</span> <span m=''2173410''>M,</span> <span m=''2173780''>my</span>
  <span m=''2173910''>number</span> <span m=''2174200''>of</span> <span m=''2174350''>dimensions,</span>
  <span m=''2175480''>my nominal</span> <span m=''2176050''>coding</span> <span m=''2176420''>gain</span>
  <span m=''2176670''>goes</span> <span m=''2176910''>to</span> <span m=''2176990''>infinity.  OK?</span>
  <span m=''2181240''>What</span> <span m=''2181460''>do we</span> <span m=''2181630''>expect</span>
  <span m=''2181940''>for</span> <span m=''2182030''>the</span> <span m=''2182120''>effective</span>
  <span m=''2182490''>coding</span> <span m=''2182990''>gain?</span> <span m=''2183310''>Will
  it</span> <span m=''2183530''>also</span> <span m=''2183860''>go</span> <span m=''2183970''>to</span>
  <span m=''2184070''>infinity?</span> </p><p><span m=''2190974''>AUDIENCE: It</span>
  <span m=''2191452''>approaches the</span> <span m=''2191930''>Shannon limit.</span>
  </p><p><span m=''2192408''>PROFESSOR: Well,</span> <span m=''2192890''>we</span>
  <span m=''2193290''>don''t</span> <span m=''2193500''>know</span> <span m=''2193570''>whether</span>
  <span m=''2193730''>it</span> <span m=''2193840''>approaches the</span> <span m=''2194300''>Shannon</span>
  <span m=''2194610''>limit</span> <span m=''2194900''>as</span> <span m=''2195090''>of</span>
  <span m=''2195250''>yet,</span> <span m=''2195520''>but</span> <span m=''2195670''>we</span>
  <span m=''2195780''>know</span> <span m=''2196050''>it cannot</span> <span m=''2196310''>go</span>
  <span m=''2196440''>to</span> <span m=''2196560''>infinity.</span> <span m=''2197250''>It''s</span>
  <span m=''2197420''>upper</span> <span m=''2197640''>bounded</span> <span m=''2198070''>by</span>
  <span m=''2198180''>the</span> <span m=''2198300''>Shannon limit.  Right?</span>
  <span m=''2200220''>So</span> <span m=''2200430''>the</span> <span m=''2200530''>effective</span>
  <span m=''2200830''>coding</span> <span m=''2201300''>gain</span> <span m=''2201590''>cannot</span>
  <span m=''2202340''>really</span> <span m=''2203720''>become</span> <span m=''2204090''>unbounded,</span>
  <span m=''2205180''>and</span> <span m=''2205330''>what''s really</span> <span m=''2205620''>happening</span>
  <span m=''2206310''>here?</span> </p><p><span m=''2208220''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2211890''>PROFESSOR: Right,</span> <span m=''2212200''>but</span>
  <span m=''2212510''>why does</span> <span m=''2212560''>the</span> <span m=''2213190''>effective</span>
  <span m=''2213570''>coding</span> <span m=''2213620''>gain</span> <span m=''2213950''>stay</span>
  <span m=''2214280''>bounded</span> <span m=''2214720''>and</span> <span m=''2214880''>the</span>
  <span m=''2214960''>nominal</span> <span m=''2215310''>coding</span> <span m=''2215700''>gain</span>
  <span m=''2215940''>blow up?</span> </p><p><span m=''2216610''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2218680''>PROFESSOR: Right,</span> <span m=''2219420''>the</span>
  <span m=''2219570''>number</span> <span m=''2219750''>of</span> <span m=''2219960''>nearest</span>
  <span m=''2220360''>neighbors</span> <span m=''2220760''>also</span> <span m=''2221010''>increases</span>
  <span m=''2221760''>with</span> <span m=''2221910''>M, right?</span> <span m=''2222440''>Not</span>
  <span m=''2222580''>just</span> <span m=''2222970''>the</span> <span m=''2223080''>nominal</span>
  <span m=''2223410''>coding</span> <span m=''2223860''>gain.</span> <span m=''2312330''>So</span>
  <span m=''2312820''>let''s</span> <span m=''2313060''>write</span> <span m=''2313170''>that</span>
  <span m=''2313450''>down.</span> <span m=''2314570''>If</span> <span m=''2314750''>I</span>
  <span m=''2314830''>look</span> <span m=''2314960''>at</span> <span m=''2315090''>the</span>
  <span m=''2315190''>number</span> <span m=''2315420''>of</span> <span m=''2315550''>nearest</span>
  <span m=''2315970''>neighbors</span> <span m=''2317210''>per</span> <span m=''2317460''>information</span>
  <span m=''2318250''>bit --</span> <span m=''2320690''>yes?</span> </p><p><span m=''2321510''>AUDIENCE:
  These</span> <span m=''2321950''>don''t</span> <span m=''2322390''>have</span> <span
  m=''2322830''>0</span> <span m=''2323270''>mean,</span> <span m=''2324150''>right?</span>
  </p><p><span m=''2324480''>PROFESSOR:  Right,</span> <span m=''2324620''>they</span>
  <span m=''2325070''>don''t have</span> <span m=''2325090''>0</span> <span m=''2325590''>mean.</span>
  <span m=''2325790''>That''s a</span> <span m=''2325840''>good</span> <span m=''2326010''>point.</span>
  </p><p><span m=''2331420''>PROFESSOR: Let''s</span> <span m=''2331700''>see,</span>
  <span m=''2335080''>what</span> <span m=''2335270''>happens to the</span> <span
  m=''2335400''>mean</span> <span m=''2335680''>as</span> <span m=''2335810''>M</span>
  <span m=''2335960''>goes</span> <span m=''2336170''>to</span> <span m=''2336260''>infinity?</span>
  <span m=''2340140''>If</span> <span m=''2340340''>we</span> <span m=''2340540''>look</span>
  <span m=''2340660''>at</span> <span m=''2340860''>what</span> <span m=''2340980''>happens</span>
  <span m=''2341080''>to the mean,</span> <span m=''2341180''>it</span> <span m=''2341380''>will</span>
  <span m=''2341410''>be</span> <span m=''2341620''>1</span> <span m=''2341810''>over</span>
  <span m=''2342140''>M.</span> <span m=''2342470''>You</span> <span m=''2342720''>find
  the</span> <span m=''2342830''>mean</span> <span m=''2343110''>of</span> <span m=''2343260''>this</span>
  <span m=''2343510''>guy,</span> <span m=''2344020''>it''s</span> <span m=''2344310''>1
  over 2</span> <span m=''2344660''>times</span> <span m=''2345140''>the</span> <span
  m=''2345410''>distance</span> <span m=''2345820''>here</span> <span m=''2346100''>times</span>
  <span m=''2346445''>distance</span> <span m=''2346790''>here is</span> <span m=''2347040''>1
  over 2</span> <span m=''2347380''>E(A),</span> <span m=''2348450''>E(A).</span>
  <span m=''2349300''>OK?</span> <span m=''2350260''>If</span> <span m=''2350400''>you</span>
  <span m=''2350480''>look</span> <span m=''2350630''>at</span> <span m=''2350790''>three</span>
  <span m=''2350970''>dimensions,</span> <span m=''2351480''>it''s</span> <span m=''2351630''>1
  over 3</span> <span m=''2352340''>E(A),</span> <span m=''2352690''>E(A),</span>
  <span m=''2352990''>E(A).</span> <span m=''2354050''>So in</span> <span m=''2354200''>M</span>
  <span m=''2354330''>dimensions,</span> <span m=''2354860''>it''s</span> <span m=''2355000''>going</span>
  <span m=''2355080''>to</span> <span m=''2355150''>be</span> <span m=''2355260''>1</span>
  <span m=''2355450''>over</span> <span m=''2355660''>M</span> <span m=''2355880''>times</span>
  <span m=''2356230''>all</span> <span m=''2356400''>these</span> <span m=''2356560''>coordinates.</span>
  <span m=''2357180''>If</span> <span m=''2357290''>we</span> <span m=''2357350''>look</span>
  <span m=''2357470''>at</span> <span m=''2357580''>the</span> <span m=''2357690''>mean</span>
  <span m=''2357880''>squared,</span> <span m=''2358280''>it</span> <span m=''2358380''>goes</span>
  <span m=''2358620''>to</span> <span m=''2358720''>0</span> <span m=''2359630''>as</span>
  <span m=''2359790''>M</span> <span m=''2359930''>goes</span> <span m=''2360190''>to</span>
  <span m=''2360350''>infinity.</span> <span m=''2361042''>So</span> <span m=''2361390''>that''s</span>
  <span m=''2361610''>a</span> <span m=''2361670''>good</span> <span m=''2361820''>point.</span>
  <span m=''2364390''>So the</span> <span m=''2364610''>mean</span> <span m=''2364920''>does</span>
  <span m=''2365120''>go</span> <span m=''2365240''>to</span> <span m=''2365390''>0,</span>
  <span m=''2365800''>and</span> <span m=''2365990''>so we approach</span> <span m=''2366420''>the</span>
  <span m=''2366910''>Shannon</span> <span m=''2367410''>limit.</span> </p><p><span
  m=''2370410''>So</span> <span m=''2370910''>we</span> <span m=''2371080''>have</span>
  <span m=''2371330''>K_b</span> <span m=''2371580''>of</span> <span m=''2371820''>A</span>
  <span m=''2373430''>over</span> <span m=''2373730''>logM</span> <span m=''2377860''>What''s</span>
  <span m=''2378160''>the</span> <span m=''2378260''>number</span> <span m=''2378530''>of</span>
  <span m=''2378680''>nearest</span> <span m=''2379130''>neighbors?</span> <span m=''2379610''>We</span>
  <span m=''2379730''>saw it</span> <span m=''2380050''>was</span> <span m=''2380230''>M</span>
  <span m=''2380360''>minus</span> <span m=''2380840''>1</span> <span m=''2382720''>over</span>
  <span m=''2384110''>log M.</span> <span m=''2386760''>And</span> <span m=''2387240''>that</span>
  <span m=''2387590''>goes</span> <span m=''2387860''>to</span> <span m=''2387990''>infinity</span>
  <span m=''2389330''>as</span> <span m=''2389510''>M</span> <span m=''2389690''>goes</span>
  <span m=''2389950''>to</span> <span m=''2390050''>infinity.</span> <span m=''2391990''>OK,</span>
  <span m=''2392380''>so</span> <span m=''2394360''>the average</span> <span m=''2394570''>number</span>
  <span m=''2394810''>of</span> <span m=''2394940''>nearest</span> <span m=''2395380''>neighbors</span>
  <span m=''2395810''>per</span> <span m=''2395980''>information</span> <span m=''2396710''>bit</span>
  <span m=''2398880''>also</span> <span m=''2399440''>go</span> <span m=''2399610''>to</span>
  <span m=''2399730''>infinity</span> <span m=''2400590''>as</span> <span m=''2400810''>M</span>
  <span m=''2401100''>goes</span> <span m=''2401320''>to</span> <span m=''2401440''>infinity.</span>
  <span m=''2402930''>And</span> <span m=''2403400''>if</span> <span m=''2403530''>we</span>
  <span m=''2403590''>look</span> <span m=''2403760''>at</span> <span m=''2403920''>the</span>
  <span m=''2404040''>mean --</span> <span m=''2404460''>just</span> <span m=''2404670''>to</span>
  <span m=''2406100''>write</span> <span m=''2406370''>down</span> <span m=''2406600''>the</span>
  <span m=''2406710''>comment</span> <span m=''2407060''>that</span> <span m=''2407200''>was</span>
  <span m=''2407400''>made.</span> <span m=''2409100''>If</span> <span m=''2409280''>we</span>
  <span m=''2409380''>look</span> <span m=''2409600''>at</span> <span m=''2409780''>the</span>
  <span m=''2409890''>mean</span> <span m=''2410220''>of</span> <span m=''2410360''>this</span>
  <span m=''2410540''>constellation,</span> <span m=''2412450''>that''s</span> <span
  m=''2412740''>going</span> <span m=''2412970''>to</span> <span m=''2413120''>be</span>
  <span m=''2414350''>1</span> <span m=''2414670''>over</span> <span m=''2416160''>the</span>
  <span m=''2416420''>number</span> <span m=''2416580''>of</span> <span m=''2416780''>points</span>
  <span m=''2418420''>times</span> <span m=''2418950''>root</span> <span m=''2419390''>E(A)</span>
  <span m=''2421570''>root</span> <span m=''2421960''>E(A)</span> <span m=''2423349''>and</span>
  <span m=''2424275''>root E(A).</span> <span m=''2426590''>So</span> <span m=''2427060''>there</span>
  <span m=''2427210''>are</span> <span m=''2427370''>M</span> <span m=''2427530''>coordinates.</span>
  <span m=''2428170''>So</span> <span m=''2428290''>that''s</span> <span m=''2428520''>going</span>
  <span m=''2428650''>to</span> <span m=''2428780''>be</span> <span m=''2428900''>the</span>
  <span m=''2429030''>mean</span> <span m=''2429750''>if</span> <span m=''2429910''>you</span>
  <span m=''2430020''>believe</span> <span m=''2430340''>this</span> <span m=''2430500''>is</span>
  <span m=''2430630''>the</span> <span m=''2430760''>coordinate</span> <span m=''2431270''>axis</span>
  <span m=''2431730''>here.</span> </p><p><span m=''2433300''>And</span> <span m=''2433640''>if
  you</span> <span m=''2433780''>we</span> <span m=''2433880''>look</span> <span m=''2434080''>at</span>
  <span m=''2434270''>the</span> <span m=''2436060''>norm</span> <span m=''2436750''>of</span>
  <span m=''2436940''>M(A)</span> <span m=''2437130''>squared,</span> <span m=''2439160''>then</span>
  <span m=''2439360''>it''s</span> <span m=''2439550''>going</span> <span m=''2439730''>to</span>
  <span m=''2439910''>be</span> <span m=''2440220''>E(A)</span> <span m=''2440520''>over</span>
  <span m=''2440950''>M.</span> <span m=''2444150''>And</span> <span m=''2444690''>as</span>
  <span m=''2444850''>M</span> <span m=''2445060''>goes</span> <span m=''2445330''>to</span>
  <span m=''2445420''>infinity,</span> <span m=''2446310''>this</span> <span m=''2446930''>goes
  to</span> <span m=''2447050''>0.</span> <span m=''2454508''>And</span> <span m=''2454990''>because</span>
  <span m=''2455320''>the</span> <span m=''2455350''>mean</span> <span m=''2455630''>goes</span>
  <span m=''2455900''>to</span> <span m=''2456000''>0,</span> <span m=''2456100''>it''s</span>
  <span m=''2456480''>not</span> <span m=''2456740''>unreasonable</span> <span m=''2457020''>to</span>
  <span m=''2457590''>expect</span> <span m=''2458020''>that</span> <span m=''2458330''>the</span>
  <span m=''2458970''>performance</span> <span m=''2459540''>does</span> <span m=''2459770''>approach</span>
  <span m=''2460200''>to</span> <span m=''2460270''>the</span> <span m=''2460510''>ultimate</span>
  <span m=''2460825''>Shanon limit.</span> </p><p><span m=''2463200''>OK,</span> <span
  m=''2463810''>so</span> <span m=''2464210''>so</span> <span m=''2464430''>far</span>
  <span m=''2464710''>we</span> <span m=''2464820''>have</span> <span m=''2465200''>looked</span>
  <span m=''2465500''>at</span> <span m=''2465730''>K_b</span> <span m=''2465910''>of</span>
  <span m=''2466070''>A</span> <span m=''2466910''>and gamma_c</span> <span m=''2467280''>of</span>
  <span m=''2467810''>A.</span> <span m=''2469060''>If</span> <span m=''2469190''>you</span>
  <span m=''2469320''>look</span> <span m=''2469470''>at</span> <span m=''2469620''>the</span>
  <span m=''2469710''>effective</span> <span m=''2470270''>coding</span> <span m=''2470620''>gain,</span>
  <span m=''2471970''>it is</span> <span m=''2472690''>still</span> <span m=''2473300''>bounded.</span>
  <span m=''2476930''>It''s</span> <span m=''2477170''>always</span> <span m=''2477310''>bounded.</span>
  <span m=''2478360''>It</span> <span m=''2478500''>is</span> <span m=''2478630''>not</span>
  <span m=''2478890''>clear</span> <span m=''2479140''>at</span> <span m=''2479350''>this</span>
  <span m=''2479590''>point</span> <span m=''2480270''>what</span> <span m=''2480560''>really</span>
  <span m=''2480810''>happens</span> <span m=''2481320''>to</span> <span m=''2481480''>it.</span>
  <span m=''2482280''>And</span> <span m=''2482440''>in</span> <span m=''2482550''>fact,</span>
  <span m=''2483430''>it''s</span> <span m=''2483880''>not</span> <span m=''2484080''>quite</span>
  <span m=''2484320''>straightforward</span> <span m=''2485250''>to</span> <span m=''2485330''>actually</span>
  <span m=''2485750''>show</span> <span m=''2486080''>what</span> <span m=''2486270''>happens</span>
  <span m=''2486560''>to</span> <span m=''2486660''>the</span> <span m=''2486770''>effective</span>
  <span m=''2487070''>coding</span> <span m=''2487600''>gain.</span> <span m=''2488440''>If</span>
  <span m=''2488690''>you</span> <span m=''2488930''>have taken</span> <span m=''2489190''>6.450,</span>
  <span m=''2490590''>then</span> <span m=''2490950''>Professor</span> <span m=''2491420''>Bob</span>
  <span m=''2491660''>Gallager</span> <span m=''2491980''>really</span> <span m=''2492260''>goes</span>
  <span m=''2492470''>into</span> <span m=''2492660''>the</span> <span m=''2492850''>details
  of</span> <span m=''2493330''>proving</span> <span m=''2494250''>how</span> <span
  m=''2494470''>the</span> <span m=''2494660''>effective</span> <span m=''2495470''>coding</span>
  <span m=''2495820''>gain</span> <span m=''2496100''>for</span> <span m=''2496290''>this</span>
  <span m=''2496490''>signal</span> <span m=''2496920''>set</span> <span m=''2497640''>indeed</span>
  <span m=''2497760''>does</span> <span m=''2497980''>approach</span> <span m=''2498390''>the</span>
  <span m=''2498490''>Shannon</span> <span m=''2498840''>limit.</span> </p><p><span
  m=''2500560''>But</span> <span m=''2501290''>it</span> <span m=''2501410''>can</span>
  <span m=''2501610''>be</span> <span m=''2501810''>shown</span> <span m=''2506470''>that</span>
  <span m=''2508790''>the</span> <span m=''2508960''>effective</span> <span m=''2509255''>coding</span>
  <span m=''2509550''>gain</span> <span m=''2510470''>does</span> <span m=''2510690''>approach</span>
  <span m=''2511360''>11.2</span> <span m=''2511950''>dB</span> <span m=''2513472''>as</span>
  <span m=''2513870''>M</span> <span m=''2514140''>goes to</span> <span m=''2514640''>infinity.</span>
  <span m=''2516790''>The</span> <span m=''2516950''>main</span> <span m=''2517300''>trick</span>
  <span m=''2517540''>here</span> <span m=''2517910''>is</span> <span m=''2518020''>that</span>
  <span m=''2518180''>union</span> <span m=''2518510''>bound</span> <span m=''2518760''>is</span>
  <span m=''2518840''>usually</span> <span m=''2519250''>quite</span> <span m=''2519560''>weak</span>
  <span m=''2519770''>if the</span> <span m=''2519940''>probability</span> <span m=''2520450''>of
  error</span> <span m=''2520880''>is</span> <span m=''2520960''>small.</span> <span
  m=''2521770''>So</span> <span m=''2521970''>we</span> <span m=''2522190''>replace</span>
  <span m=''2522500''>the</span> <span m=''2522600''>probability</span> <span m=''2522870''>of</span>
  <span m=''2522910''>error</span> <span m=''2523350''>just</span> <span m=''2523590''>by</span>
  <span m=''2523710''>1,</span> <span m=''2524040''>instead</span> <span m=''2524350''>of</span>
  <span m=''2524450''>the</span> <span m=''2524540''>union</span> <span m=''2524830''>bound,</span>
  <span m=''2525110''>at</span> <span m=''2525280''>some</span> <span m=''2525530''>point.</span>
  <span m=''2526240''>And</span> <span m=''2526360''>if</span> <span m=''2526450''>you</span>
  <span m=''2526570''>do</span> <span m=''2526700''>that</span> <span m=''2527700''>change,</span>
  <span m=''2528140''>then</span> <span m=''2528860''>things</span> <span m=''2529060''>work</span>
  <span m=''2529270''>out</span> <span m=''2529460''>nicely.</span> <span m=''2530300''>But</span>
  <span m=''2530510''>in</span> <span m=''2530630''>this</span> <span m=''2530860''>course,</span>
  <span m=''2531120''>we</span> <span m=''2531340''>will just</span> <span m=''2531760''>assert</span>
  <span m=''2532340''>that</span> <span m=''2532550''>the</span> <span m=''2533520''>orthogonal</span>
  <span m=''2534060''>signal</span> <span m=''2534390''>sets</span> <span m=''2534770''>do</span>
  <span m=''2534960''>achieve</span> <span m=''2535725''>the</span> <span m=''2536040''>ultimate</span>
  <span m=''2536540''>Shannon</span> <span m=''2536680''>limit.</span> <span m=''2537580''>And</span>
  <span m=''2538140''>you</span> <span m=''2538330''>can</span> <span m=''2538520''>see</span>
  <span m=''2540000''>6.450</span> <span m=''2540330''>notes</span> <span m=''2540970''>for</span>
  <span m=''2541370''>the</span> <span m=''2541690''>proof.</span> <span m=''2550560''>So</span>
  <span m=''2550810''>that''s</span> <span m=''2551180''>the</span> <span m=''2551460''>assertion</span>
  <span m=''2551680''>that</span> <span m=''2551850''>we</span> <span m=''2552000''>are
  making</span> <span m=''2552320''>right</span> <span m=''2552540''>now.</span> </p><p><span
  m=''2553570''>So</span> <span m=''2554110''>let''s</span> <span m=''2555430''>step</span>
  <span m=''2555700''>back</span> <span m=''2555960''>and</span> <span m=''2556100''>take</span>
  <span m=''2556270''>a</span> <span m=''2556340''>look</span> <span m=''2556560''>at</span>
  <span m=''2556670''>what''s</span> <span m=''2556910''>happening</span> <span m=''2557240''>so</span>
  <span m=''2557480''>far.</span> <span m=''2558740''>We</span> <span m=''2558890''>have</span>
  <span m=''2559100''>a</span> <span m=''2559180''>class</span> <span m=''2559660''>of</span>
  <span m=''2559740''>signal</span> <span m=''2560100''>sets</span> <span m=''2560260''>which</span>
  <span m=''2560570''>are</span> <span m=''2561130''>conceptually</span> <span m=''2561780''>quite</span>
  <span m=''2561990''>easy</span> <span m=''2562240''>to</span> <span m=''2562340''>describe.</span>
  <span m=''2563290''>They are</span> <span m=''2563560''>just</span> <span m=''2563860''>orthogonal</span>
  <span m=''2564010''>signal</span> <span m=''2564360''>sets.</span> <span m=''2565430''>They
  are</span> <span m=''2565790''>not</span> <span m=''2566230''>too</span> <span m=''2566330''>hard</span>
  <span m=''2566630''>to</span> <span m=''2566770''>analyze,</span> <span m=''2567460''>and</span>
  <span m=''2567630''>they</span> <span m=''2567870''>asymptotically</span> <span
  m=''2568500''>approach</span> <span m=''2569470''>the</span> <span m=''2569730''>ultimate</span>
  <span m=''2569980''>Shannon</span> <span m=''2570340''>limit.</span> <span m=''2571460''>So
  this</span> <span m=''2571600''>seems</span> <span m=''2572010''>quite</span> <span
  m=''2572280''>nice.</span> <span m=''2572730''>So</span> <span m=''2572820''>why</span>
  <span m=''2572950''>not</span> <span m=''2573140''>we</span> <span m=''2573260''>just</span>
  <span m=''2573460''>implement</span> <span m=''2573980''>them?</span> </p><p><span
  m=''2576010''>Now</span> <span m=''2576580''>it</span> <span m=''2576770''>turns</span>
  <span m=''2577130''>that</span> <span m=''2577360''>these</span> <span m=''2577530''>are</span>
  <span m=''2577610''>not</span> <span m=''2577890''>very</span> <span m=''2578150''>common</span>
  <span m=''2578480''>in</span> <span m=''2578590''>practice.</span> <span m=''2579180''>They
  are</span> <span m=''2579330''>not</span> <span m=''2579520''>implemented</span>
  <span m=''2580060''>as</span> <span m=''2580240''>often</span> <span m=''2580520''>as</span>
  <span m=''2580640''>you</span> <span m=''2580740''>might</span> <span m=''2581380''>think</span>
  <span m=''2581660''>when</span> <span m=''2581850''>you</span> <span m=''2581920''>first</span>
  <span m=''2582250''>look</span> <span m=''2582400''>at</span> <span m=''2582580''>them</span>
  <span m=''2583450''>and because</span> <span m=''2583740''>they</span> <span m=''2583830''>have</span>
  <span m=''2583980''>some</span> <span m=''2584490''>drawbacks.</span> <span m=''2585840''>And</span>
  <span m=''2585980''>there</span> <span m=''2586190''>are a</span> <span m=''2586240''>couple</span>
  <span m=''2586530''>of</span> <span m=''2586680''>drawbacks</span> <span m=''2588300''>which</span>
  <span m=''2588950''>make</span> <span m=''2589070''>them</span> <span m=''2589380''>very</span>
  <span m=''2589610''>less</span> <span m=''2589850''>appealing</span> <span m=''2590170''>than</span>
  <span m=''2591600''>what</span> <span m=''2591780''>you</span> <span m=''2591860''>might</span>
  <span m=''2592020''>otherwise</span> <span m=''2592210''>think.</span> <span m=''2595450''>And
  first</span> <span m=''2595795''>of</span> <span m=''2596140''>all,</span> <span
  m=''2596820''>what''s</span> <span m=''2597060''>the</span> <span m=''2597160''>spectral</span>
  <span m=''2597620''>efficiency</span> <span m=''2598310''>for these</span> <span
  m=''2598820''>signal</span> <span m=''2599130''>sets?</span> </p><p><span m=''2603316''>AUDIENCE:0,
  right?</span> </p><p><span m=''2604230''>PROFESSOR: It</span> <span m=''2604390''>goes</span>
  <span m=''2604640''>to</span> <span m=''2604790''>0.</span> <span m=''2605150''>And
  how</span> <span m=''2605290''>does</span> <span m=''2605450''>it</span> <span m=''2605590''>go</span>
  <span m=''2605770''>to</span> <span m=''2605810''>0?</span> <span m=''2607050''>It''s</span>
  <span m=''2607520''>2log M</span> <span m=''2608860''>to</span> <span m=''2608970''>the</span>
  <span m=''2609090''>base</span> <span m=''2609470''>2</span> <span m=''2609800''>over</span>
  <span m=''2609880''>M.</span> <span m=''2611710''>As</span> <span m=''2611890''>M</span>
  <span m=''2612070''>goes</span> <span m=''2612330''>to</span> <span m=''2612450''>infinity,</span>
  <span m=''2613370''>this</span> <span m=''2613580''>goes</span> <span m=''2613800''>to</span>
  <span m=''2613930''>0.</span> <span m=''2614960''>And</span> <span m=''2615170''>in</span>
  <span m=''2615270''>fact,</span> <span m=''2615490''>it</span> <span m=''2615620''>goes</span>
  <span m=''2615820''>to</span> <span m=''2616050''>0</span> <span m=''2616340''>quite</span>
  <span m=''2616580''>sharply.</span> <span m=''2619150''>Now</span> <span m=''2619620''>that''s</span>
  <span m=''2619990''>fine,</span> <span m=''2620390''>but</span> <span m=''2620540''>if</span>
  <span m=''2620640''>you</span> <span m=''2620730''>want</span> <span m=''2620860''>to</span>
  <span m=''2621000''>approach</span> <span m=''2621360''>Shannon</span> <span m=''2621740''>limit,</span>
  <span m=''2622240''>our</span> <span m=''2622500''>spectral</span> <span m=''2622760''>efficiency</span>
  <span m=''2623240''>should</span> <span m=''2623640''>indeed</span> <span m=''2623730''>go</span>
  <span m=''2623920''>to</span> <span m=''2624110''>0.</span> <span m=''2625300''>But</span>
  <span m=''2625950''>if</span> <span m=''2626050''>you''re</span> <span m=''2626180''>looking</span>
  <span m=''2626400''>at</span> <span m=''2626480''>the</span> <span m=''2627050''>system</span>
  <span m=''2627430''>design</span> <span m=''2627800''>problem,</span> <span m=''2628220''>what</span>
  <span m=''2628280''>do</span> <span m=''2628520''>you really</span> <span m=''2628920''>want?</span>
  </p><p><span m=''2630050''>You</span> <span m=''2630150''>have</span> <span m=''2630300''>a</span>
  <span m=''2630570''>certain</span> <span m=''2630780''>effective</span> <span m=''2631200''>coding</span>
  <span m=''2631550''>gain</span> <span m=''2631770''>that</span> <span m=''2631950''>you</span>
  <span m=''2632090''>have</span> <span m=''2632240''>in</span> <span m=''2632330''>mind,</span>
  <span m=''2633200''>and</span> <span m=''2633320''>suppose</span> <span m=''2633700''>you
  are</span> <span m=''2633900''>presented</span> <span m=''2634440''>with</span>
  <span m=''2634600''>a</span> <span m=''2634640''>list</span> <span m=''2634930''>of</span>
  <span m=''2635030''>several</span> <span m=''2635530''>different</span> <span m=''2635880''>signal</span>
  <span m=''2636310''>sets</span> <span m=''2636570''>that</span> <span m=''2637080''>achieve</span>
  <span m=''2637430''>this</span> <span m=''2637640''>effective</span> <span m=''2637960''>coding</span>
  <span m=''2638360''>gain.</span> <span m=''2639290''>And</span> <span m=''2639430''>your</span>
  <span m=''2639510''>job</span> <span m=''2639810''>is</span> <span m=''2639920''>to</span>
  <span m=''2640070''>pick</span> <span m=''2640540''>one</span> <span m=''2640690''>of</span>
  <span m=''2640900''>these</span> <span m=''2641470''>possible</span> <span m=''2641900''>signal</span>
  <span m=''2642250''>sets.</span> <span m=''2642700''>Which</span> <span m=''2642870''>one</span>
  <span m=''2643010''>will</span> <span m=''2643130''>you</span> <span m=''2643260''>pick?</span>
  </p><p><span m=''2644320''>Well,</span> <span m=''2644580''>there</span> <span m=''2644800''>are</span>
  <span m=''2644970''>two</span> <span m=''2645200''>things</span> <span m=''2645310''>you
  will</span> <span m=''2645440''>look for,</span> <span m=''2645780''>right?</span>
  <span m=''2646430''>You</span> <span m=''2646540''>will look</span> <span m=''2646770''>for</span>
  <span m=''2646860''>the</span> <span m=''2646960''>spectral</span> <span m=''2647350''>efficiency</span>
  <span m=''2647920''>that</span> <span m=''2648080''>these</span> <span m=''2648220''>different</span>
  <span m=''2648610''>signal</span> <span m=''2648760''>sets</span> <span m=''2649710''>require</span>
  <span m=''2650400''>or</span> <span m=''2650660''>achieve</span> <span m=''2651680''>in
  order</span> <span m=''2651850''>to get</span> <span m=''2652020''>this</span> <span
  m=''2652270''>effective</span> <span m=''2652720''>coding</span> <span m=''2653060''>gain.</span>
  <span m=''2653800''>And</span> <span m=''2654040''>the</span> <span m=''2654090''>higher</span>
  <span m=''2654380''>the</span> <span m=''2654480''>spectral</span> <span m=''2654840''>efficiency</span>
  <span m=''2655410''>the</span> <span m=''2655520''>better.</span> <span m=''2656650''>And</span>
  <span m=''2656940''>secondly,</span> <span m=''2657740''>you</span> <span m=''2657810''>will</span>
  <span m=''2657890''>also</span> <span m=''2658140''>want</span> <span m=''2658320''>to</span>
  <span m=''2658370''>look</span> <span m=''2658520''>at</span> <span m=''2658600''>the</span>
  <span m=''2658660''>implementation</span> <span m=''2659400''>complexity.</span>
  <span m=''2660600''>You do</span> <span m=''2660690''>not</span> <span m=''2660770''>want</span>
  <span m=''2661080''>something</span> <span m=''2661440''>which</span> <span m=''2661750''>really</span>
  <span m=''2662270''>takes</span> <span m=''2662640''>a lot of</span> <span m=''2662760''>time</span>
  <span m=''2662970''>to</span> <span m=''2663070''>decode.</span> </p><p><span m=''2665110''>OK?  So</span>
  <span m=''2665280''>it</span> <span m=''2665430''>turns</span> <span m=''2665740''>out
  that</span> <span m=''2666020''>because</span> <span m=''2666350''>the</span> <span
  m=''2666440''>spectral</span> <span m=''2666850''>efficiency</span> <span m=''2667520''>goes</span>
  <span m=''2667770''>to</span> <span m=''2667900''>0</span> <span m=''2668130''>so</span>
  <span m=''2668200''>sharply,</span> <span m=''2669580''>it''s</span> <span m=''2669790''>not</span>
  <span m=''2669950''>very</span> <span m=''2670130''>surprising</span> <span m=''2670850''>that</span>
  <span m=''2670970''>there</span> <span m=''2671080''>are</span> <span m=''2671180''>other</span>
  <span m=''2671370''>codes</span> <span m=''2672350''>that</span> <span m=''2672510''>have</span>
  <span m=''2672630''>the</span> <span m=''2672710''>same</span> <span m=''2673010''>effective</span>
  <span m=''2673340''>coding</span> <span m=''2673810''>gain</span> <span m=''2674050''>but</span>
  <span m=''2674380''>higher</span> <span m=''2674790''>spectral</span> <span m=''2674880''>efficiency.</span>
  <span m=''2676480''>So</span> <span m=''2680270''>there</span> <span m=''2680610''>are</span>
  <span m=''2680830''>binary</span> <span m=''2681220''>codes</span> <span m=''2689530''>that</span>
  <span m=''2689790''>have</span> <span m=''2691480''>a</span> <span m=''2691800''>higher</span>
  <span m=''2694890''>spectral</span> <span m=''2695460''>efficiency</span> <span
  m=''2697050''>for</span> <span m=''2698490''>same</span> <span m=''2699320''>effective</span>
  <span m=''2700020''>coding</span> <span m=''2700500''>gain.</span> <span m=''2703050''>And</span>
  <span m=''2703300''>so</span> <span m=''2703510''>they</span> <span m=''2703650''>would</span>
  <span m=''2703830''>be</span> <span m=''2703950''>a</span> <span m=''2704000''>natural</span>
  <span m=''2704460''>choice</span> <span m=''2704810''>over</span> <span m=''2705240''>the</span>
  <span m=''2705640''>orthogonal</span> <span m=''2705860''>signal</span> <span m=''2706300''>set.</span>
  <span m=''2706960''>Yes?</span> </p><p><span m=''2708130''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''2708590''>high-spectrum</span> <span m=''2709050''>efficiency</span> <span
  m=''2709510''>to mean</span> <span m=''2709970''>bandwidth?</span> </p><p><span
  m=''2711350''>PROFESSOR: Right,</span> <span m=''2711670''>because</span> <span
  m=''2712020''>in</span> <span m=''2712260''>practice,</span> <span m=''2712670''>bandwidth</span>
  <span m=''2712800''>is never</span> <span m=''2712990''>really</span> <span m=''2713220''>infinite,</span>
  <span m=''2713670''>right?</span> <span m=''2714320''>So</span> <span m=''2714600''>if</span>
  <span m=''2714760''>you are achieving the</span> <span m=''2714930''>same --</span>
  <span m=''2716850''>the</span> <span m=''2716980''>first</span> <span m=''2717210''>objective</span>
  <span m=''2717690''>is</span> <span m=''2717790''>to</span> <span m=''2717980''>have</span>
  <span m=''2718090''>a</span> <span m=''2718170''>certain</span> <span m=''2718440''>effective</span>
  <span m=''2718710''>coding</span> <span m=''2719010''>gain.</span> <span m=''2719530''>If</span>
  <span m=''2719640''>you</span> <span m=''2719740''>do</span> <span m=''2719860''>have</span>
  <span m=''2720090''>that,</span> <span m=''2720310''>you</span> <span m=''2720410''>want</span>
  <span m=''2720540''>to</span> <span m=''2720670''>pick</span> <span m=''2720910''>something</span>
  <span m=''2721240''>which</span> <span m=''2721380''>has</span> <span m=''2721470''>a</span>
  <span m=''2721680''>higher</span> <span m=''2722090''>spectral</span> <span m=''2722170''>efficiency.</span>
  <span m=''2724090''>And</span> <span m=''2724510''>indeed,</span> <span m=''2724840''>the</span>
  <span m=''2725570''>subject</span> <span m=''2726030''>of</span> <span m=''2726150''>chapters</span>
  <span m=''2726510''>six</span> <span m=''2726800''>and</span> <span m=''2727030''>eight</span>
  <span m=''2727720''>is</span> <span m=''2727940''>to</span> <span m=''2728120''>come</span>
  <span m=''2728300''>up</span> <span m=''2728410''>with</span> <span m=''2728540''>binary</span>
  <span m=''2728950''>codes</span> <span m=''2729300''>that</span> <span m=''2729460''>have
  a</span> <span m=''2729840''>much</span> <span m=''2730280''>better performance</span>
  <span m=''2730850''>than</span> <span m=''2730970''>the</span> <span m=''2731180''>orthogonal</span>
  <span m=''2731550''>signal</span> <span m=''2731910''>set</span> <span m=''2732470''>for</span>
  <span m=''2732580''>a</span> <span m=''2732630''>given</span> <span m=''2732970''>effective</span>
  <span m=''2733380''>coding</span> <span m=''2733710''>gain.</span> <span m=''2734430''>Chapter</span>
  <span m=''2734620''>six</span> <span m=''2734740''>deals</span> <span m=''2734920''>with
  the</span> <span m=''2735880''>the</span> <span m=''2735980''>block</span> <span
  m=''2736390''>codes,</span> <span m=''2736620''>whereas</span> <span m=''2736950''>chapter</span>
  <span m=''2737240''>eight</span> <span m=''2737330''>deals</span> <span m=''2738020''>with</span>
  <span m=''2738620''>convolutional</span> <span m=''2739330''>codes.</span> <span
  m=''2739880''>And</span> <span m=''2740060''>chapter</span> <span m=''2740380''>seven</span>
  <span m=''2740690''>basically</span> <span m=''2741690''>develops</span> <span m=''2742080''>all</span>
  <span m=''2742200''>the</span> <span m=''2742320''>finite</span> <span m=''2742810''>field</span>
  <span m=''2743220''>theory</span> <span m=''2743460''>that you</span> <span m=''2743700''>require</span>
  <span m=''2743975''>to</span> <span m=''2744250''>study</span> <span m=''2744640''>convolutional</span>
  <span m=''2745300''>codes.</span> <span m=''2746410''>So</span> <span m=''2746590''>the</span>
  <span m=''2747280''>point</span> <span m=''2747590''>is,</span> <span m=''2747840''>in</span>
  <span m=''2747940''>the</span> <span m=''2748190''>subsequent</span> <span m=''2748770''>lectures</span>
  <span m=''2749170''>we will</span> <span m=''2749330''>be</span> <span m=''2749430''>focusing</span>
  <span m=''2749960''>a</span> <span m=''2750040''>lot</span> <span m=''2750470''>on</span>
  <span m=''2751010''>improving</span> <span m=''2751480''>the</span> <span m=''2751590''>performance</span>
  <span m=''2752140''>over</span> <span m=''2752510''>orthogonal</span> <span m=''2752880''>signal</span>
  <span m=''2753210''>sets.</span> </p><p><span m=''2754940''>The</span> <span m=''2755050''>second</span>
  <span m=''2755450''>point I</span> <span m=''2755670''>mentioned</span> <span m=''2756390''>was</span>
  <span m=''2756590''>implementation</span> <span m=''2757410''>complexity.</span>
  <span m=''2767600''>Now</span> <span m=''2767790''>one</span> <span m=''2768020''>particular</span>
  <span m=''2768530''>way of</span> <span m=''2768870''>implementing</span> <span
  m=''2769520''>orthogonal</span> <span m=''2770130''>codes,</span> <span m=''2770670''>which</span>
  <span m=''2771090''>you</span> <span m=''2771210''>saw</span> <span m=''2771480''>in</span>
  <span m=''2771600''>the</span> <span m=''2771720''>first</span> <span m=''2772090''>homework,</span>
  <span m=''2772970''>was</span> <span m=''2773240''>using</span> <span m=''2774290''>this</span>
  <span m=''2774720''>idea</span> <span m=''2775100''>of</span> <span m=''2775540''>Hadamard</span>
  <span m=''2775760''>transforms,</span> <span m=''2776300''>right?</span> <span m=''2777100''>You
  have a</span> <span m=''2777310''>Hardamard</span> <span m=''2777560''>matrix,</span>
  <span m=''2777810''>which</span> <span m=''2778310''>is</span> <span m=''2778490''>an</span>
  <span m=''2778580''>M</span> <span m=''2778710''>by</span> <span m=''2778870''>M</span>
  <span m=''2779020''>matrix.</span> <span m=''2779940''>The</span> <span m=''2780090''>rows</span>
  <span m=''2780300''>of</span> <span m=''2780410''>the</span> <span m=''2780490''>Hadamard</span>
  <span m=''2780890''>matrix</span> <span m=''2781520''>are</span> <span m=''2781870''>your</span>
  <span m=''2782200''>orthogonal</span> <span m=''2782260''>signal</span> <span m=''2782640''>sets,</span>
  <span m=''2783590''>which are</span> <span m=''2783680''>elements</span> <span m=''2784250''>aj.</span>
  </p><p><span m=''2785400''>And</span> <span m=''2785670''>at</span> <span m=''2785780''>the</span>
  <span m=''2785850''>receiver,</span> <span m=''2786090''>what</span> <span m=''2786440''>you</span>
  <span m=''2786520''>would</span> <span m=''2786670''>do</span> <span m=''2787190''>is</span>
  <span m=''2787240''>when</span> <span m=''2787450''>you</span> <span m=''2787630''>get</span>
  <span m=''2787790''>the</span> <span m=''2787950''>signal</span> <span m=''2788320''>y,</span>
  <span m=''2788700''>you simply</span> <span m=''2789060''>multiply</span> <span
  m=''2789570''>by</span> <span m=''2789680''>the</span> <span m=''2790320''>Hadamard</span>
  <span m=''2790690''>matrix</span> <span m=''2791580''>and</span> <span m=''2791730''>look</span>
  <span m=''2791920''>at</span> <span m=''2792010''>the</span> <span m=''2792110''>coordinate</span>
  <span m=''2792600''>which</span> <span m=''2792770''>is</span> <span m=''2792860''>the</span>
  <span m=''2792950''>largest.</span> <span m=''2794050''>So</span> <span m=''2794130''>this</span>
  <span m=''2794240''>is</span> <span m=''2794340''>something</span> <span m=''2794670''>you</span>
  <span m=''2794870''>did</span> <span m=''2795070''>in the</span> <span m=''2795180''>first</span>
  <span m=''2795520''>homework</span> <span m=''2795940''>exercise.</span> <span m=''2797120''>And</span>
  <span m=''2797230''>how</span> <span m=''2797400''>many</span> <span m=''2797720''>computations</span>
  <span m=''2798410''>did</span> <span m=''2798560''>you</span> <span m=''2798640''>require</span>
  <span m=''2799900''>for</span> <span m=''2800050''>an</span> <span m=''2800140''>orthogonal</span>
  <span m=''2800680''>signal</span> <span m=''2801050''>set of</span> <span m=''2801400''>size</span>
  <span m=''2801740''>M?</span> </p><p><span m=''2806010''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2811420''>PROFESSOR: Sorry? OK,</span> <span m=''2811690''>so</span>
  <span m=''2812580''>I</span> <span m=''2812940''>meant</span> <span m=''2813320''>M</span>
  <span m=''2813600''>being the</span> <span m=''2813700''>size</span> <span m=''2813960''>of</span>
  <span m=''2814080''>the</span> <span m=''2814350''>orthogonal</span> <span m=''2814630''>signal</span>
  <span m=''2815090''>set.</span> </p><p><span m=''2815792''>AUDIENCE: Yeah,</span>
  <span m=''2816656''>[INAUDIBLE]</span> </p><p><span m=''2819030''>PROFESSOR: Right.</span>
  </p><p><span m=''2821778''>AUDIENCE: 2 to the M</span> <span m=''2822230''>by 2
  to the M.</span> </p><p><span m=''2823590''>PROFESSOR: If it is</span> <span m=''2823855''>2</span>
  <span m=''2824120''>to the M</span> <span m=''2824210''>by 2</span> <span m=''2824450''>to
  the M,</span> <span m=''2824650''>it is</span> <span m=''2824820''>M</span> <span
  m=''2825160''>times</span> <span m=''2825290''>2</span> <span m=''2825330''>to the
  M.</span> <span m=''2826200''>But</span> <span m=''2826620''>there</span> <span
  m=''2826720''>are</span> <span m=''2827100''>M</span> <span m=''2827760''>orthogonal</span>
  <span m=''2828020''>signal</span> <span m=''2828380''>sets,</span> <span m=''2829290''>then</span>
  <span m=''2829470''>it</span> <span m=''2829590''>will</span> <span m=''2829710''>be</span>
  <span m=''2829840''>M</span> <span m=''2830180''>log M,</span> <span m=''2836120''>where</span>
  <span m=''2836300''>M</span> <span m=''2836420''>is</span> <span m=''2836590''>the</span>
  <span m=''2836640''>number</span> <span m=''2836890''>of</span> <span m=''2837010''>signal</span>
  <span m=''2837510''>sets.</span> <span m=''2837950''>So</span> <span m=''2838080''>that''s</span>
  <span m=''2838310''>the</span> <span m=''2838370''>number</span> <span m=''2838610''>of</span>
  <span m=''2838720''>computations</span> <span m=''2839440''>that</span> <span m=''2839550''>you
  would</span> <span m=''2839800''>require.</span> </p><p><span m=''2840970''>Now,</span>
  <span m=''2842750''>the</span> <span m=''2842910''>question</span> <span m=''2843660''>to
  ask</span> <span m=''2843830''>is,</span> <span m=''2844010''>is this</span> <span
  m=''2844220''>fast</span> <span m=''2844660''>or</span> <span m=''2844800''>is this</span>
  <span m=''2844930''>slow?</span> <span m=''2846640''>Is</span> <span m=''2846760''>this</span>
  <span m=''2846940''>too</span> <span m=''2847050''>many</span> <span m=''2847260''>computations</span>
  <span m=''2847830''>or is</span> <span m=''2847950''>this</span> <span m=''2848140''>too</span>
  <span m=''2848270''>little</span> <span m=''2848670''>computations?</span> <span
  m=''2850090''>And</span> <span m=''2850270''>if</span> <span m=''2850390''>you''re</span>
  <span m=''2850540''>looking</span> <span m=''2850800''>in</span> <span m=''2850870''>the</span>
  <span m=''2850990''>power-limited</span> <span m=''2851760''>regime,</span> <span
  m=''2852490''>what</span> <span m=''2852640''>we really</span> <span m=''2852940''>want</span>
  <span m=''2853270''>is</span> <span m=''2853440''>to</span> <span m=''2853570''>see</span>
  <span m=''2853750''>the</span> <span m=''2853860''>complexity</span> <span m=''2854510''>per</span>
  <span m=''2854650''>information</span> <span m=''2854975''>bit</span> <span m=''2856270''>because</span>
  <span m=''2856420''>we</span> <span m=''2856850''>normalize</span> <span m=''2857090''>things</span>
  <span m=''2857250''>per</span> <span m=''2857480''>information</span> <span m=''2858070''>bit.</span>
  <span m=''2858810''>Now,</span> <span m=''2859190''>how</span> <span m=''2859400''>many</span>
  <span m=''2859620''>bits</span> <span m=''2860180''>are sent</span> <span m=''2860710''>when</span>
  <span m=''2860920''>you</span> <span m=''2861040''>have</span> <span m=''2861180''>orthogonal</span>
  <span m=''2861730''>signal</span> <span m=''2862050''>set</span> <span m=''2862280''>of</span>
  <span m=''2862390''>size</span> <span m=''2862750''>M?</span> <span m=''2863510''>We</span>
  <span m=''2863630''>have</span> <span m=''2863900''>log M</span> <span m=''2864230''>bits,</span>
  <span m=''2864525''>right?</span> <span m=''2865050''>So</span> <span m=''2865190''>this</span>
  <span m=''2865390''>quantity</span> <span m=''2865730''>is</span> <span m=''2865870''>actually</span>
  <span m=''2866170''>exponential</span> <span m=''2866840''>in</span> <span m=''2866960''>the</span>
  <span m=''2867090''>number</span> <span m=''2867190''>of</span> <span m=''2867290''>transmitted</span>
  <span m=''2867400''>bits</span> <span m=''2868280''>that</span> <span m=''2868490''>we
  are</span> <span m=''2868660''>sending,</span> <span m=''2869580''>and</span> <span
  m=''2869760''>so</span> <span m=''2869860''>in</span> <span m=''2869970''>fact</span>
  <span m=''2870200''>this</span> <span m=''2870360''>is</span> <span m=''2870510''>quite</span>
  <span m=''2870760''>slow.</span> <span m=''2872385''>Or</span> <span m=''2872790''>in
  other</span> <span m=''2873070''>words we are</span> <span m=''2873310''>saying</span>
  <span m=''2873690''>it</span> <span m=''2873790''>is</span> <span m=''2873900''>we
  require</span> <span m=''2874300''>M</span> <span m=''2874480''>times</span> <span
  m=''2874910''>2</span> <span m=''2875230''>to the M</span> <span m=''2875980''>computations,</span>
  <span m=''2876830''>where</span> <span m=''2876970''>M</span> <span m=''2877090''>is</span>
  <span m=''2877190''>the</span> <span m=''2877280''>number</span> <span m=''2877530''>of</span>
  <span m=''2877640''>information</span> <span m=''2878240''>bits</span> <span m=''2878530''>that
  we are</span> <span m=''2878820''>sending.</span> </p><p><span m=''2881295''>AUDIENCE:
  So</span> <span m=''2881630''>if</span> <span m=''2881975''>M</span> <span m=''2882320''>is
  the size</span> <span m=''2882590''>of</span> <span m=''2882860''>your</span> <span
  m=''2883320''>[INAUDIBLE]</span> <span m=''2884220''>then</span> <span m=''2884696''>you
  have</span> <span m=''2885172''>log M</span> <span m=''2885650''>bits?</span> </p><p><span
  m=''2886127''>PROFESSOR: Right.</span> </p><p><span m=''2887558''>AUDIENCE: So</span>
  <span m=''2888035''> M log M over log M is M. </span> </p><p><span m=''2889470''>PROFESSOR:
  Why</span> <span m=''2889940''>are you</span> <span m=''2890050''>adding</span>
  <span m=''2890430''>by</span> <span m=''2890810''>M?</span> </p><p><span m=''2891195''>AUDIENCE:
  You</span> <span m=''2891580''>need M log M</span> <span m=''2891925''>operations</span>
  <span m=''2892270''>to</span> <span m=''2892580''>decode a symbol.</span> </p><p><span
  m=''2893690''>PROFESSOR: To</span> <span m=''2893950''>decode</span> <span m=''2894340''>a</span>
  <span m=''2894765''>symbol.</span> </p><p><span m=''2895190''>AUDIENCE: And</span>
  <span m=''2895420''>each</span> <span m=''2895745''>symbol</span> <span m=''2896070''>gives</span>
  <span m=''2896530''>you</span> <span m=''2896810''>log</span> <span m=''2897190''>M</span>
  <span m=''2897340''>bits.</span> <span m=''2898020''>So</span> <span m=''2898487''>you</span>
  <span m=''2898954''>have</span> <span m=''2899421''>M</span> <span m=''2899888''>operations</span>
  <span m=''2900355''>per bit.</span> </p><p><span m=''2901650''>PROFESSOR: Well,</span>
  <span m=''2902600''>when</span> <span m=''2902820''>you send,</span> <span m=''2903230''>say,</span>
  <span m=''2903650''>log M bits,</span> <span m=''2903860''>right,</span> <span m=''2904080''>you
  can</span> <span m=''2904480''>only</span> <span m=''2904800''>send</span> <span
  m=''2905020''>one</span> <span m=''2905170''>of</span> <span m=''2905280''>the</span>
  <span m=''2905400''>M</span> <span m=''2905710''>possible</span> <span m=''2906020''>symbols.</span>
  <span m=''2909860''>And</span> <span m=''2910040''>when</span> <span m=''2910140''>you</span>
  <span m=''2910230''>want to decode</span> <span m=''2910770''>the</span> <span m=''2910940''>symbol,</span>
  <span m=''2911620''>you would</span> <span m=''2911860''>end</span> <span m=''2912040''>up</span>
  <span m=''2912100''>recovering</span> <span m=''2912570''>log M</span> <span m=''2912810''>bits.</span>
  <span m=''2915630''>So</span> <span m=''2915830''>you</span> <span m=''2915930''>should</span>
  <span m=''2916080''>not</span> <span m=''2916260''>be</span> <span m=''2916330''>dividing</span>
  <span m=''2916720''>by</span> <span m=''2916900''>M</span> <span m=''2916960''>here.</span>
  </p><p><span m=''2918928''>AUDIENCE: You''re dividing</span> <span m=''2919420''>by
  log</span> <span m=''2919912''>M</span> <span m=''2921220''>because you</span> <span
  m=''2921540''>want to</span> <span m=''2921870''>do it</span> <span m=''2922190''>per
  bit.</span> </p><p><span m=''2923730''>PROFESSOR: All</span> <span m=''2924150''>right.</span>
  <span m=''2924710''>You''re right.</span> <span m=''2924960''>So</span> <span m=''2925130''>you''re</span>
  <span m=''2925250''>dividing</span> <span m=''2925560''>by</span> <span m=''2925780''>log
  M.</span> <span m=''2926140''>You</span> <span m=''2926350''>have</span> <span m=''2926650''>M</span>
  <span m=''2926850''>log M</span> <span m=''2927060''>bits.</span> <span m=''2927330''>You''re
  dividing</span> <span m=''2927690''>by</span> <span m=''2927820''>log</span> <span
  m=''2928120''>M,</span> <span m=''2928730''>so</span> <span m=''2929000''>you</span>
  <span m=''2929170''>still</span> <span m=''2929370''>have --</span> </p><p><span
  m=''2931276''>AUDIENCE: You</span> <span m=''2931774''>have</span> <span m=''2932272''>M</span>
  <span m=''2933800''>calculations</span> <span m=''2934210''>per bit.</span> <span
  m=''2935240''>[INAUDIBLE]</span> </p><p><span m=''2942870''>PROFESSOR: So</span>
  <span m=''2943660''>we</span> <span m=''2944070''>are</span> <span m=''2944320''>sending
  --</span> <span m=''2944620''>so</span> <span m=''2944870''>I</span> <span m=''2945010''>need</span>
  <span m=''2945240''>this</span> <span m=''2945430''>many</span> <span m=''2946040''>computations</span>
  <span m=''2947620''>to</span> <span m=''2948850''>get</span> <span m=''2949050''>log
  M</span> <span m=''2949680''>bits.</span> <span m=''2952590''>So</span> <span m=''2954410''>is</span>
  <span m=''2954590''>this</span> <span m=''2954740''>expression</span> <span m=''2955190''>exponential</span>
  <span m=''2955565''>in</span> <span m=''2955940''>log M</span> <span m=''2956886''>or
  not?</span> <span m=''2960670''>So</span> <span m=''2961040''>that''s</span> <span
  m=''2961260''>all</span> <span m=''2961650''>I</span> <span m=''2962030''>was</span>
  <span m=''2962050''>saying.</span> </p><p><span m=''2963310''>AUDIENCE: I</span>
  <span m=''2963700''>just</span> <span m=''2964090''>put it</span> <span m=''2964480''>another
  way</span> <span m=''2964860''>that</span> <span m=''2964980''>you</span> <span
  m=''2965100''>could</span> <span m=''2965350''>divide</span> <span m=''2965530''>by
  log M.</span> </p><p><span m=''2967170''>PROFESSOR: M</span> <span m=''2967410''>for</span>
  <span m=''2967660''>information,</span> <span m=''2968050''>right.</span> <span
  m=''2972900''>OK,</span> <span m=''2973170''>are there any</span> <span m=''2973570''>questions?</span>
  <span m=''2975050''>I mean</span> <span m=''2975280''>we</span> <span m=''2975470''>are</span>
  <span m=''2975650''>both</span> <span m=''2975800''>agreeing</span> <span m=''2975960''>to
  the fact</span> <span m=''2976100''>that</span> <span m=''2976820''>this</span>
  <span m=''2976990''>is</span> <span m=''2977130''>too</span> <span m=''2977250''>many</span>
  <span m=''2977510''>computations</span> <span m=''2978230''>than</span> <span m=''2978390''>you</span>
  <span m=''2978510''>would want.</span> <span m=''2979030''>And</span> <span m=''2979870''>there</span>
  <span m=''2980050''>exist</span> <span m=''2980600''>other</span> <span m=''2980820''>decoding</span>
  <span m=''2981240''>algorithms</span> <span m=''2982000''>for</span> <span m=''2982180''>which</span>
  <span m=''2983390''>the</span> <span m=''2983730''>number</span> <span m=''2984100''>of</span>
  <span m=''2984220''>computations</span> <span m=''2985090''>is</span> <span m=''2985220''>much</span>
  <span m=''2985430''>smaller</span> <span m=''2985770''>than</span> <span m=''2986280''>exponential.</span>
  </p><p><span m=''2994290''>OK,</span> <span m=''2995390''>so</span> <span m=''2995850''>let''s</span>
  <span m=''2996170''>next</span> <span m=''2996480''>look</span> <span m=''2996650''>at</span>
  <span m=''2996820''>the</span> <span m=''2996930''>bandwidth-limited</span> <span
  m=''2997830''>regime.</span> <span m=''3012110''>Well,</span> <span m=''3012450''>actually</span>
  <span m=''3012760''>before</span> <span m=''3013040''>that</span> <span m=''3013220''>I</span>
  <span m=''3013290''>wanted</span> <span m=''3013700''>to</span> <span m=''3013780''>mention</span>
  <span m=''3014890''>a</span> <span m=''3015090''>couple</span> <span m=''3015290''>of</span>
  <span m=''3015500''>other</span> <span m=''3016320''>signal</span> <span m=''3016750''>sets</span>
  <span m=''3017090''>as</span> <span m=''3017280''>well.</span> <span m=''3018370''>So</span>
  <span m=''3018600''>there are</span> <span m=''3018900''>two</span> <span m=''3019060''>other</span>
  <span m=''3019630''>important</span> <span m=''3019750''>class of</span> <span m=''3020120''>signal</span>
  <span m=''3020450''>sets</span> <span m=''3020780''>which</span> <span m=''3021050''>are</span>
  <span m=''3021320''>related</span> <span m=''3021690''>to</span> <span m=''3021790''>the</span>
  <span m=''3022030''>orthogonal</span> <span m=''3022470''>signal</span> <span m=''3022840''>sets.</span>
  <span m=''3024050''>The</span> <span m=''3024130''>first</span> <span m=''3025400''>is</span>
  <span m=''3025710''>this</span> <span m=''3025940''>class</span> <span m=''3026310''>of</span>
  <span m=''3026420''>simplex</span> <span m=''3027050''>signal</span> <span m=''3027630''>sets.</span>
  <span m=''3031580''>And</span> <span m=''3031840''>the</span> <span m=''3032040''>other</span>
  <span m=''3032240''>class is</span> <span m=''3035220''>bi-orthogonal</span> <span
  m=''3040110''>signal</span> <span m=''3040630''>sets.</span> </p><p><span m=''3046960''>So</span>
  <span m=''3047290''>the</span> <span m=''3047380''>idea</span> <span m=''3047720''>behind</span>
  <span m=''3048010''>simplex</span> <span m=''3048500''>signal sets</span> <span
  m=''3049180''>goes</span> <span m=''3049440''>back</span> <span m=''3049750''>to</span>
  <span m=''3049840''>the</span> <span m=''3049910''>observation</span> <span m=''3050580''>that</span>
  <span m=''3050740''>was</span> <span m=''3050930''>made</span> <span m=''3051600''>that</span>
  <span m=''3051770''>we</span> <span m=''3051880''>have</span> <span m=''3052080''>a</span>
  <span m=''3052190''>non-zero</span> <span m=''3052540''>mean</span> <span m=''3053140''>for</span>
  <span m=''3053300''>this</span> <span m=''3053420''>signal</span> <span m=''3053810''>set
  here.</span> <span m=''3054960''>So</span> <span m=''3055130''>if</span> <span m=''3055300''>we</span>
  <span m=''3055410''>do,</span> <span m=''3056040''>we</span> <span m=''3056230''>can</span>
  <span m=''3056470''>indeed</span> <span m=''3056860''>subtract of</span> <span m=''3057010''>the</span>
  <span m=''3057130''>mean</span> <span m=''3057450''>and</span> <span m=''3057630''>get</span>
  <span m=''3057770''>a</span> <span m=''3057850''>performance</span> <span m=''3058970''>which</span>
  <span m=''3059190''>is</span> <span m=''3059330''>better</span> <span m=''3059730''>than</span>
  <span m=''3060120''>the</span> <span m=''3060430''>orthogonal</span> <span m=''3060740''>signal</span>
  <span m=''3061030''>set.</span> <span m=''3062070''>So</span> <span m=''3062220''>in</span>
  <span m=''3062280''>particular</span> <span m=''3062740''>if</span> <span m=''3062850''>I</span>
  <span m=''3063080''>subtract</span> <span m=''3063400''>of</span> <span m=''3063520''>the</span>
  <span m=''3063650''>mean</span> <span m=''3063890''>here,</span> <span m=''3064910''>I</span>
  <span m=''3065130''>get</span> <span m=''3065360''>a</span> <span m=''3065450''>signal</span>
  <span m=''3065870''>set,</span> <span m=''3067440''>which</span> <span m=''3067700''>is</span>
  <span m=''3068390''>like</span> <span m=''3068760''>this.</span> <span m=''3069560''>This</span>
  <span m=''3069750''>is</span> <span m=''3069880''>the</span> <span m=''3069930''>simplex</span>
  <span m=''3070430''>signal</span> <span m=''3070720''>set</span> <span m=''3071010''>when
  M</span> <span m=''3071290''>equals</span> <span m=''3071720''>2.</span> <span m=''3074090''>When</span>
  <span m=''3074290''>M</span> <span m=''3074340''>equals</span> <span m=''3074550''>3,</span>
  <span m=''3076530''>I''m</span> <span m=''3076680''>going</span> <span m=''3076870''>to</span>
  <span m=''3076940''>subtract</span> <span m=''3077150''>of</span> <span m=''3077520''>the</span>
  <span m=''3077640''>mean</span> <span m=''3078160''>from</span> <span m=''3078260''>this</span>
  <span m=''3078730''>plane here.</span> <span m=''3079390''>The</span> <span m=''3079900''>points</span>
  <span m=''3080200''>lie</span> <span m=''3080340''>on</span> <span m=''3080470''>this</span>
  <span m=''3080680''>particular</span> <span m=''3081190''>plane.</span> <span m=''3081980''>And</span>
  <span m=''3082130''>what</span> <span m=''3082350''>I</span> <span m=''3082390''>end</span>
  <span m=''3082540''>up</span> <span m=''3082970''>with</span> <span m=''3083430''>is</span>
  <span m=''3083550''>an</span> <span m=''3083720''>equilateral</span> <span m=''3083980''>triangle.</span>
  <span m=''3085570''>So</span> <span m=''3085720''>this</span> <span m=''3085890''>is</span>
  <span m=''3086010''>the</span> <span m=''3086140''>case</span> <span m=''3086480''>when</span>
  <span m=''3086610''>M</span> <span m=''3087020''>equals</span> <span m=''3087355''>3.</span>
  </p><p><span m=''3089580''>What</span> <span m=''3089730''>do</span> <span m=''3089890''>you</span>
  <span m=''3089960''>think</span> <span m=''3090210''>M</span> <span m=''3090310''>equals</span>
  <span m=''3090670''>4</span> <span m=''3090890''>would</span> <span m=''3091120''>look</span>
  <span m=''3091310''>like?</span> <span m=''3092960''>A tetrahedron</span> <span
  m=''3093330''>right</span> <span m=''3093670''>here.</span> <span m=''3096020''>That''s</span>
  <span m=''3096220''>a</span> <span m=''3096290''>simplex</span> <span m=''3096920''>signal</span>
  <span m=''3097330''>set.</span> <span m=''3099930''>So</span> <span m=''3101050''>basically,</span>
  <span m=''3102160''>it''s</span> <span m=''3102500''>also</span> <span m=''3102770''>not</span>
  <span m=''3103000''>too</span> <span m=''3103100''>hard</span> <span m=''3103450''>to</span>
  <span m=''3103570''>write</span> <span m=''3104730''>an</span> <span m=''3104890''>algebraic</span>
  <span m=''3105410''>expression</span> <span m=''3106000''>for</span> <span m=''3106150''>these</span>
  <span m=''3106300''>signal</span> <span m=''3106730''>sets.</span> <span m=''3107820''>E</span>
  <span m=''3107980''>of</span> <span m=''3108190''>A</span> <span m=''3108350''>prime</span>
  <span m=''3109200''>is</span> <span m=''3109390''>going</span> <span m=''3109590''>to</span>
  <span m=''3109710''>be</span> <span m=''3109920''>E</span> <span m=''3110260''>of</span>
  <span m=''3110707''>A</span> <span m=''3112050''>minus</span> <span m=''3112210''>M</span>
  <span m=''3112570''>of</span> <span m=''3112810''>A.</span> <span m=''3115600''>You</span>
  <span m=''3115720''>subtract</span> <span m=''3116090''>off</span> <span m=''3116200''>the</span>
  <span m=''3116300''>mean</span> <span m=''3116580''>from</span> <span m=''3116810''>your</span>
  <span m=''3117730''>orthogonal</span> <span m=''3117830''>signal</span> <span m=''3118300''>set.</span>
  <span m=''3120590''>If</span> <span m=''3121060''>I</span> <span m=''3121150''>want</span>
  <span m=''3121400''>to write it</span> <span m=''3121580''>in</span> <span m=''3121690''>terms</span>
  <span m=''3121970''>of</span> <span m=''3122050''>inner</span> <span m=''3122340''>products,</span>
  <span m=''3123340''>the inner</span> <span m=''3123460''>product</span> <span m=''3123810''>between</span>
  <span m=''3124320''>ai</span> <span m=''3124640''>and</span> <span m=''3124800''>aj</span>
  <span m=''3125780''>is</span> <span m=''3126100''>given</span> <span m=''3126490''>by</span>
  <span m=''3129630''>E(A)</span> <span m=''3130260''>if</span> <span m=''3130490''>i</span>
  <span m=''3130890''>equals</span> <span m=''3131150''>j.</span> <span m=''3133450''>And</span>
  <span m=''3133720''>it''s</span> <span m=''3134090''>I believe</span> <span m=''3136130''>minus
  of</span> <span m=''3136710''>1</span> <span m=''3136910''>over</span> <span m=''3137070''>M</span>
  <span m=''3137210''>minus</span> <span m=''3137740''>1</span> <span m=''3138690''>times</span>
  <span m=''3138900''>E(A)</span> <span m=''3139906''>if</span> <span m=''3140332''>i</span>
  <span m=''3141610''>is</span> <span m=''3141790''>not</span> <span m=''3142170''>equal</span>
  <span m=''3142370''>to</span> <span m=''3142795''>j.</span> <span m=''3143220''>So
  this</span> <span m=''3143400''>is</span> <span m=''3143540''>the</span> <span m=''3143700''>inner</span>
  <span m=''3143800''>product</span> <span m=''3144300''>between</span> <span m=''3144570''>ai</span>
  <span m=''3144720''>and</span> <span m=''3144970''>aj.</span> <span m=''3146340''>And</span>
  <span m=''3146710''>I</span> <span m=''3146740''>mean</span> <span m=''3146880''>there</span>
  <span m=''3147120''>are also</span> <span m=''3147240''>many</span> <span m=''3147540''>properties</span>
  <span m=''3148070''>of</span> <span m=''3148220''>this</span> <span m=''3148340''>simplex</span>
  <span m=''3148850''>signal set,</span> <span m=''3149080''>but</span> <span m=''3149690''>I</span>
  <span m=''3150180''>believe</span> <span m=''3150560''>that</span> <span m=''3150770''>that''s</span>
  <span m=''3151010''>going</span> <span m=''3151130''>to</span> <span m=''3151260''>be</span>
  <span m=''3151380''>in your next</span> <span m=''3151790''>homework</span> <span
  m=''3152220''>exercise</span> <span m=''3153270''>so</span> <span m=''3153440''>I''m</span>
  <span m=''3153560''>not</span> <span m=''3153770''>going</span> <span m=''3153960''>into</span>
  <span m=''3154180''>too</span> <span m=''3154300''>many</span> <span m=''3154550''>details.</span>
  </p><p><span m=''3155780''>What''</span> <span m=''3155930''>the</span> <span m=''3156360''>spectral</span>
  <span m=''3156530''>efficiency</span> <span m=''3157090''>in</span> <span m=''3157210''>this</span>
  <span m=''3157430''>case</span> <span m=''3157650''>going</span> <span m=''3157890''>to</span>
  <span m=''3158120''>be?</span> </p><p><span m=''3165346''>AUDIENCE: I have a question.</span>
  <span m=''3166850''>So</span> <span m=''3167290''>what</span> <span m=''3167730''>is</span>
  <span m=''3168110''>a</span> <span m=''3168575''>simplex?</span> <span m=''3169040''>Is
  a simplex</span> <span m=''3169505''>just a</span> <span m=''3169970''>reference</span>
  <span m=''3170435''>to anything with</span> <span m=''3170900''>[INAUDIBLE].</span>
  </p><p><span m=''3172270''>PROFESSOR: Simplex signal</span> <span m=''3172740''>set</span>
  <span m=''3172820''>is</span> <span m=''3173140''>derived</span> <span m=''3173950''>from</span>
  <span m=''3174360''>the</span> <span m=''3174470''>orthogonal</span> <span m=''3174990''>signal
  set</span> <span m=''3175270''>by</span> <span m=''3175370''>subtracting</span>
  <span m=''3175980''>off</span> <span m=''3176200''>its</span> <span m=''3176390''>mean.</span>
  </p><p><span m=''3177560''>AUDIENCE: Right, but in</span> <span m=''3178035''>general</span>
  <span m=''3178510''>simplex</span> <span m=''3178985''>means</span> <span m=''3179460''>anything</span>
  <span m=''3179935''>[INAUDIBLE]?</span> </p><p><span m=''3181840''>PROFESSOR: I''m</span>
  <span m=''3182000''>not</span> <span m=''3182200''>sure</span> <span m=''3182685''>about
  that.</span> <span m=''3188940''>What''s</span> <span m=''3189210''>the</span> <span
  m=''3189300''>spectral</span> <span m=''3189660''>efficiency</span> <span m=''3190220''>going</span>
  <span m=''3190420''>to</span> <span m=''3190620''>be?</span> </p><p><span m=''3192188''>AUDIENCE:
  [INAUDIBLE]</span> </p><p><span m=''3195840''>PROFESSOR: Well, almost.</span> </p><p><span
  m=''3198536''>AUDIENCE: You use one dimension.</span> </p><p><span m=''3199030''>PROFESSOR:
  Right,</span> <span m=''3199770''>you</span> <span m=''3200090''>just</span> <span
  m=''3200330''>use</span> <span m=''3200800''>one</span> <span m=''3200980''>dimension.</span>
  <span m=''3207230''>OK,</span> <span m=''3209120''>and</span> <span m=''3209330''>there</span>
  <span m=''3209460''>are</span> <span m=''3209560''>other</span> <span m=''3209750''>properties</span>
  <span m=''3210120''>that</span> <span m=''3210330''>you''ll be</span> <span m=''3210650''>looking</span>
  <span m=''3211020''>at</span> <span m=''3211140''>it</span> <span m=''3211210''>in</span>
  <span m=''3211470''>the homework.</span> <span m=''3212420''>Now</span> <span m=''3212580''>the</span>
  <span m=''3212660''>idea</span> <span m=''3212960''>behind</span> <span m=''3213300''>this
  --</span> </p><p><span m=''3214692''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3219660''>PROFESSOR:
  This is</span> <span m=''3219960''>2</span> <span m=''3220260''>log M</span> <span
  m=''3221290''>over</span> <span m=''3221732''>[INAUDIBLE].</span> <span m=''3224390''>So</span>
  <span m=''3224930''>the</span> <span m=''3225260''>idea</span> <span m=''3225630''>behind</span>
  <span m=''3225730''>the</span> <span m=''3226180''>bi-orthogonal</span> <span m=''3227050''>signal
  set</span> <span m=''3227870''>is</span> <span m=''3228510''>you</span> <span m=''3228630''>start</span>
  <span m=''3229020''>with</span> <span m=''3229140''>an</span> <span m=''3229380''>orthogonal</span>
  <span m=''3230020''>signal</span> <span m=''3230200''>set,</span> <span m=''3231060''>and</span>
  <span m=''3231370''>for</span> <span m=''3231630''>each</span> <span m=''3231870''>point,</span>
  <span m=''3232170''>you</span> <span m=''3232250''>also</span> <span m=''3232540''>put</span>
  <span m=''3232730''>the</span> <span m=''3232830''>negative</span> <span m=''3233260''>signal</span>
  <span m=''3233630''>of</span> <span m=''3233760''>it.</span> <span m=''3234240''>So</span>
  <span m=''3234660''>in</span> <span m=''3235170''>addition</span> <span m=''3235550''>to</span>
  <span m=''3235620''>this,</span> <span m=''3236180''>you will have a point here,</span>
  <span m=''3236490''>and</span> <span m=''3236830''>you will</span> <span m=''3236950''>have</span>
  <span m=''3237070''>a</span> <span m=''3237130''>point</span> <span m=''3237410''>here.</span>
  <span m=''3238520''>So</span> <span m=''3238700''>the</span> <span m=''3238860''>case</span>
  <span m=''3239180''>in two</span> <span m=''3240140''>dimensions,</span> <span m=''3240780''>M</span>
  <span m=''3241190''>equals</span> <span m=''3241540''>2,</span> <span m=''3243020''>you</span>
  <span m=''3243190''>will have</span> <span m=''3243510''>four</span> <span m=''3243770''>points</span>
  <span m=''3247100''>like</span> <span m=''3247540''>this.</span> <span m=''3249270''>So</span>
  <span m=''3249500''>in</span> <span m=''3249630''>this</span> <span m=''3249920''>case</span>
  <span m=''3250240''>you are</span> <span m=''3250400''>increasing</span> <span m=''3255860''>the</span>
  <span m=''3255980''>number</span> <span m=''3256250''>of</span> <span m=''3256510''>signal</span>
  <span m=''3256960''>points</span> <span m=''3264290''>by</span> <span m=''3264650''>a</span>
  <span m=''3264780''>factor</span> <span m=''3265160''>of</span> <span m=''3265440''>two.</span>
  <span m=''3270440''>But</span> <span m=''3270860''>this</span> <span m=''3271050''>does</span>
  <span m=''3271270''>come</span> <span m=''3271440''>at</span> <span m=''3271540''>a</span>
  <span m=''3271640''>price, right?</span> <span m=''3272380''>Because</span> <span
  m=''3273020''>if</span> <span m=''3273150''>you''re</span> <span m=''3273280''>increasing</span>
  <span m=''3273650''>the</span> <span m=''3273730''>number</span> <span m=''3273920''>of</span>
  <span m=''3274070''>signal</span> <span m=''3274440''>points,</span> <span m=''3275280''>the</span>
  <span m=''3275390''>number</span> <span m=''3275640''>of</span> <span m=''3275760''>nearest</span>
  <span m=''3276140''>neighbors</span> <span m=''3276440''>is</span> <span m=''3276530''>also</span>
  <span m=''3277260''>going</span> <span m=''3277320''>to increase</span> <span m=''3277780''>by</span>
  <span m=''3277930''>a</span> <span m=''3277970''>factor</span> <span m=''3278340''>of</span>
  <span m=''3278520''>two.</span> <span m=''3279300''>In</span> <span m=''3279400''>this</span>
  <span m=''3279620''>case,</span> <span m=''3279840''>you</span> <span m=''3279990''>have</span>
  <span m=''3280140''>two</span> <span m=''3280310''>nearest</span> <span m=''3280710''>neighbors</span>
  <span m=''3281120''>now.</span> <span m=''3307210''>So</span> <span m=''3307420''>you</span>
  <span m=''3307500''>have</span> <span m=''3307710''>both</span> <span m=''3307830''>of</span>
  <span m=''3307920''>the</span> <span m=''3308030''>effects</span> <span m=''3308400''>going</span>
  <span m=''3308720''>on.</span> <span m=''3309540''>I</span> <span m=''3309670''>mean</span>
  <span m=''3309790''>ultimately,</span> <span m=''3310480''>all</span> <span m=''3311060''>the</span>
  <span m=''3311410''>signal sets,</span> <span m=''3312050''>as</span> <span m=''3312210''>M</span>
  <span m=''3312370''>goes</span> <span m=''3312580''>to</span> <span m=''3312680''>infinity,</span>
  <span m=''3313300''>are</span> <span m=''3313410''>going</span> <span m=''3313730''>to</span>
  <span m=''3313820''>approach</span> <span m=''3314230''>the</span> <span m=''3314320''>Shannon</span>
  <span m=''3314510''>limit.</span> <span m=''3315570''>So</span> <span m=''3316170''>again,</span>
  <span m=''3316560''>but</span> <span m=''3316970''>they</span> <span m=''3317070''>do</span>
  <span m=''3317210''>suffer</span> <span m=''3317580''>from</span> <span m=''3317720''>the</span>
  <span m=''3317870''>same</span> <span m=''3318160''>kind</span> <span m=''3318400''>of</span>
  <span m=''3318510''>drawbacks</span> <span m=''3319010''>that</span> <span m=''3319180''>we</span>
  <span m=''3319360''>saw</span> <span m=''3319540''>for</span> <span m=''3319670''>the</span>
  <span m=''3319840''>orthogonal</span> <span m=''3320180''>signal</span> <span m=''3320520''>sets.</span>
  <span m=''3321270''>So</span> <span m=''3321420''>these</span> <span m=''3321640''>are
  more</span> <span m=''3321730''>of</span> <span m=''3321980''>theoretical</span>
  <span m=''3322880''>interest</span> <span m=''3323680''>as</span> <span m=''3323830''>opposed</span>
  <span m=''3324240''>to</span> <span m=''3325950''>real,</span> <span m=''3326280''>practical</span>
  <span m=''3326820''>implementation</span> <span m=''3327210''>points.</span> <span
  m=''3328130''>Any</span> <span m=''3328320''>questions?</span> </p><p><span m=''3333540''>AUDIENCE:
  Minus</span> <span m=''3333810''>[INAUDIBLE]</span> </p><p><span m=''3337310''>PROFESSOR:
  It''s</span> <span m=''3337730''>a</span> <span m=''3337790''>bit</span> <span m=''3338060''>involved</span>
  <span m=''3338330''>to</span> <span m=''3338410''>show.</span> <span m=''3338570''>I</span>
  <span m=''3338710''>think</span> <span m=''3338850''>you''ll</span> <span m=''3339300''>be</span>
  <span m=''3339440''>showing</span> <span m=''3339520''>it in the</span> <span m=''3339740''>homework</span>
  <span m=''3339830''>exercise</span> <span m=''3342330''>or</span> <span m=''3342760''>for</span>
  <span m=''3343010''>an</span> <span m=''3343100''>exam</span> <span m=''3343500''>problem</span>
  <span m=''3343780''>at</span> <span m=''3343860''>one</span> <span m=''3344040''>point.</span>
  <span m=''3346530''>You</span> <span m=''3346620''>basically</span> <span m=''3347080''>start</span>
  <span m=''3347510''>with</span> <span m=''3347750''>the</span> <span m=''3347950''>orthogonal</span>
  <span m=''3348050''>signal</span> <span m=''3348420''>sets</span> <span m=''3348685''>here,</span>
  <span m=''3350710''>look</span> <span m=''3351040''>at</span> <span m=''3351210''>the</span>
  <span m=''3351310''>inner product</span> <span m=''3351760''>here,</span> <span
  m=''3353740''>and</span> <span m=''3353850''>use</span> <span m=''3354070''>the</span>
  <span m=''3354140''>relation</span> <span m=''3354590''>between</span> <span m=''3354990''>the</span>
  <span m=''3355090''>simplex</span> <span m=''3355570''>signal</span> <span m=''3355890''>sets</span>
  <span m=''3356020''>and</span> <span m=''3356140''>the</span> <span m=''3356450''>orthogonal</span>
  <span m=''3356780''>signal</span> <span m=''3357110''>sets</span> <span m=''3357670''>to
  do</span> <span m=''3357770''>a</span> <span m=''3357880''>subtraction</span> <span
  m=''3358320''>of</span> <span m=''3358460''>the</span> <span m=''3358570''>mean.</span>
  <span m=''3359770''>And</span> <span m=''3359960''>then</span> <span m=''3360110''>you</span>
  <span m=''3360190''>can</span> <span m=''3360650''>derive</span> <span m=''3360790''>in
  a</span> <span m=''3360860''>product</span> <span m=''3361180''>expression.</span>
  </p><p><span m=''3419690''>OK,</span> <span m=''3420080''>so</span> <span m=''3420320''>let''s</span>
  <span m=''3420570''>now</span> <span m=''3420890''>move on</span> <span m=''3421290''>to</span>
  <span m=''3421360''>the</span> <span m=''3421460''>bandwidth-limited</span> <span
  m=''3422010''>regime.</span> <span m=''3438548''>OK,</span> <span m=''3439050''>so</span>
  <span m=''3439210''>the</span> <span m=''3439650''>main</span> <span m=''3440080''>difference</span>
  <span m=''3440310''>between --</span> <span m=''3440990''>yes?</span> </p><p><span
  m=''3442946''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3449220''>PROFESSOR:
  You mean</span> <span m=''3449420''>here?</span> <span m=''3451040''>For</span>
  <span m=''3451220''>each --</span> </p><p><span m=''3452120''>AUDIENCE: How far
  can</span> <span m=''3452581''>you</span> <span m=''3453042''>[INAUDIBLE]?</span>
  </p><p><span m=''3453503''>PROFESSOR: A</span> <span m=''3453964''>factor of two.</span>
  <span m=''3456270''>I</span> <span m=''3456430''>said a</span> <span m=''3456520''>factor</span>
  <span m=''3456950''>right?</span> <span m=''3457550''>So</span> <span m=''3457700''>if</span>
  <span m=''3457800''>you</span> <span m=''3457950''>have</span> <span m=''3458170''>M</span>
  <span m=''3458560''>points</span> <span m=''3458900''>in</span> <span m=''3458990''>the</span>
  <span m=''3459080''>orthogonal</span> <span m=''3459520''>signal set,</span> <span
  m=''3459720''>you</span> <span m=''3459850''>have</span> <span m=''3460160''>2M</span>
  <span m=''3460310''>points</span> <span m=''3460590''>in</span> <span m=''3460680''>the</span>
  <span m=''3460770''>bi-orthogonal</span> <span m=''3461450''>signal</span> <span
  m=''3461940''>set</span> <span m=''3464690''>because</span> <span m=''3464980''>for
  each --</span> </p><p><span m=''3468460''>AUDIENCE: In</span> <span m=''3468770''>the</span>
  <span m=''3469080''>orthogonal</span> <span m=''3469570''>sets you have 3.</span>
  </p><p><span m=''3472470''>PROFESSOR: And</span> <span m=''3472830''>in this</span>
  <span m=''3473010''>you have</span> <span m=''3473290''>6.</span> <span m=''3476050''>So</span>
  <span m=''3477590''>let''s</span> <span m=''3477930''>look</span> <span m=''3478080''>at</span>
  <span m=''3478180''>the</span> <span m=''3478270''>bandwidth-limited</span> <span
  m=''3479200''>regime.</span> <span m=''3480290''>The</span> <span m=''3480670''>trade-off</span>
  <span m=''3480890''>we</span> <span m=''3481030''>care</span> <span m=''3481310''>about</span>
  <span m=''3481730''>is</span> <span m=''3481880''>the</span> <span m=''3482080''>probability</span>
  <span m=''3482650''>of</span> <span m=''3483080''>error</span> <span m=''3483370''>for
  two</span> <span m=''3483590''>dimensions</span> <span m=''3485210''>as</span> <span
  m=''3485330''>a</span> <span m=''3485460''>function</span> <span m=''3485940''>of</span>
  <span m=''3486120''>SNR norm.</span> <span m=''3489410''>OK?</span> <span m=''3490960''>The</span>
  <span m=''3491320''>baseline</span> <span m=''3491880''>scheme</span> <span m=''3492240''>here</span>
  <span m=''3492590''>is</span> <span m=''3492730''>your</span> <span m=''3492900''>M-PAM</span>
  <span m=''3493600''>scheme.</span> <span m=''3495530''>And</span> <span m=''3495990''>we</span>
  <span m=''3496070''>showed</span> <span m=''3496520''>a</span> <span m=''3496710''>couple</span>
  <span m=''3496890''>of</span> <span m=''3497080''>lectures</span> <span m=''3497540''>ago</span>
  <span m=''3497880''>that</span> <span m=''3498040''>the</span> <span m=''3498210''>probability</span>
  <span m=''3498450''>of</span> <span m=''3498840''>error</span> <span m=''3499390''>for</span>
  <span m=''3499600''>two</span> <span m=''3499760''>dimensions</span> <span m=''3500970''>is</span>
  <span m=''3501170''>approximately</span> <span m=''3502070''>4</span> <span m=''3502460''>Q</span>
  <span m=''3503470''>times</span> <span m=''3503730''>root</span> <span m=''3504180''>3</span>
  <span m=''3504410''>SNR norm.  OK?</span> </p><p><span m=''3510420''>So</span> <span
  m=''3510730''>let''s</span> <span m=''3511140''>plot</span> <span m=''3511430''>the</span>
  <span m=''3511510''>performance</span> <span m=''3511980''>graph.</span> <span m=''3520576''>So</span>
  <span m=''3521060''>on</span> <span m=''3521290''>the</span> <span m=''3521360''>x-axis</span>
  <span m=''3521970''>I</span> <span m=''3522040''>plot</span> <span m=''3522540''>SNR
  norm.</span> <span m=''3523810''>On</span> <span m=''3523940''>the</span> <span
  m=''3524070''>y-axis</span> <span m=''3524820''>I</span> <span m=''3524900''>plot</span>
  <span m=''3525350''>Ps</span> <span m=''3525690''>of</span> <span m=''3525860''>E</span>
  <span m=''3526590''>again</span> <span m=''3526650''>on</span> <span m=''3526990''>a</span>
  <span m=''3527030''>log-log</span> <span m=''3527560''>scale.</span> <span m=''3533310''>This
  is</span> <span m=''3533490''>ten to the</span> <span m=''3533680''>negative six,</span>
  <span m=''3534070''>ten</span> <span m=''3534650''>to</span> <span m=''3534710''>the</span>
  <span m=''3534820''>negative</span> <span m=''3535340''>five,</span> <span m=''3535770''>ten
  to the</span> <span m=''3535900''>negative</span> <span m=''3536190''>four,</span>
  <span m=''3536480''>ten to the</span> <span m=''3536745''>negative</span> <span
  m=''3537010''>three</span> <span m=''3537870''>and</span> <span m=''3538070''>so</span>
  <span m=''3538270''>on.</span> <span m=''3539140''>The</span> <span m=''3539320''>intercept</span>
  <span m=''3539860''>is at</span> <span m=''3540060''>0</span> <span m=''3540410''>dB,</span>
  <span m=''3540470''>this</span> <span m=''3542010''>point</span> <span m=''3542280''>here.</span>
  <span m=''3542900''>So</span> <span m=''3542960''>this</span> <span m=''3543130''>is</span>
  <span m=''3543270''>your</span> <span m=''3543410''>Shannon</span> <span m=''3543870''>limit</span>
  <span m=''3544560''>in</span> <span m=''3544850''>the</span> <span m=''3545420''>bandwidth-limited</span>
  <span m=''3545840''>regime.</span> </p><p><span m=''3548320''>Now</span> <span m=''3548610''>your</span>
  <span m=''3550190''>performance</span> <span m=''3550960''>curve</span> <span m=''3551250''>is</span>
  <span m=''3551410''>going</span> <span m=''3551590''>to</span> <span m=''3551760''>be</span>
  <span m=''3551940''>something</span> <span m=''3552320''>like</span> <span m=''3552560''>this</span>
  <span m=''3552790''>for the</span> <span m=''3552990''>M-PAM</span> <span m=''3553570''>system.</span>
  <span m=''3562710''>And</span> <span m=''3565310''>we</span> <span m=''3565550''>want</span>
  <span m=''3565830''>to</span> <span m=''3565900''>basically</span> <span m=''3566670''>quantify</span>
  <span m=''3567270''>now</span> <span m=''3567990''>the</span> <span m=''3568130''>effective</span>
  <span m=''3568480''>coding</span> <span m=''3568890''>gain</span> <span m=''3569280''>in
  this</span> <span m=''3569500''>regime.</span> <span m=''3570650''>So</span> <span
  m=''3570800''>it''s</span> <span m=''3570910''>the</span> <span m=''3570990''>same</span>
  <span m=''3571200''>story</span> <span m=''3571460''>as</span> <span m=''3571720''>in</span>
  <span m=''3571800''>the</span> <span m=''3572130''>power-limited</span> <span m=''3572710''>regime.</span>
  <span m=''3573900''>We</span> <span m=''3574310''>will start</span> <span m=''3574780''>off</span>
  <span m=''3575060''>with</span> <span m=''3576090''>the</span> <span m=''3576200''>probability</span>
  <span m=''3576950''>of</span> <span m=''3577956''>error</span> <span m=''3579270''>using</span>
  <span m=''3579540''>the</span> <span m=''3579610''>union</span> <span m=''3580020''>bound</span>
  <span m=''3580460''>estimate,</span> <span m=''3581460''>which</span> <span m=''3581910''>is</span>
  <span m=''3582810''>K_min</span> <span m=''3583380''>of</span> <span m=''3583710''>A</span>
  <span m=''3587610''>times</span> <span m=''3588610''>Q</span> <span m=''3589030''>of</span>
  <span m=''3590710''>d_min</span> <span m=''3591000''>over</span> <span m=''3591980''>2</span>
  <span m=''3592180''>sigma.</span> <span m=''3595620''>Now</span> <span m=''3595910''>Ps</span>
  <span m=''3596150''>of</span> <span m=''3596270''>E</span> <span m=''3597766''>is
  the</span> <span m=''3598130''>probability</span> <span m=''3598560''>of</span>
  <span m=''3598820''>error</span> <span m=''3599160''>for</span> <span m=''3599300''>two</span>
  <span m=''3599690''>dimensions.</span> <span m=''3600460''>Assuming</span> <span
  m=''3600900''>we</span> <span m=''3601000''>have</span> <span m=''3601190''>N</span>
  <span m=''3601350''>dimensions</span> <span m=''3601990''>here,</span> <span m=''3602900''>it
  is</span> <span m=''3603080''>two</span> <span m=''3603300''>times</span> <span
  m=''3603940''>the</span> <span m=''3604740''>probability</span> <span m=''3604900''>of
  error</span> <span m=''3605495''>over</span> <span m=''3605850''>N.</span> <span
  m=''3608880''>So</span> <span m=''3608980''>this</span> <span m=''3609160''>is</span>
  <span m=''3610070''>probability</span> <span m=''3610290''>of error</span> <span
  m=''3611020''>per</span> <span m=''3611120''>symbol.</span> <span m=''3612140''>We
  are</span> <span m=''3612290''>dividing</span> <span m=''3612680''>by</span> <span
  m=''3612770''>the</span> <span m=''3612860''>number</span> <span m=''3613170''>of</span>
  <span m=''3613300''>dimensions</span> <span m=''3614550''>and</span> <span m=''3614930''>multiplying</span>
  <span m=''3615120''>by</span> <span m=''3615200''>two</span> <span m=''3615240''>because</span>
  <span m=''3616350''>it</span> <span m=''3616460''>is</span> <span m=''3616590''>for
  two</span> <span m=''3617000''>dimensions.</span> <span m=''3618770''>And</span>
  <span m=''3619030''>this</span> <span m=''3619200''>is</span> <span m=''3619380''>going</span>
  <span m=''3619640''>to</span> <span m=''3619800''>be</span> <span m=''3621410''>2</span>
  <span m=''3621650''>times</span> <span m=''3623530''>K_min</span> <span m=''3623910''>of</span>
  <span m=''3624360''>A</span> <span m=''3625890''>over</span> <span m=''3626220''>N,</span>
  <span m=''3628470''>times</span> <span m=''3628980''>Q of</span> <span m=''3630560''>d_min</span>
  <span m=''3630890''>over</span> <span m=''3631570''>2</span> <span m=''3631950''>sigma.</span>
  </p><p><span m=''3639530''>So</span> <span m=''3639770''>now</span> <span m=''3639930''>let''s</span>
  <span m=''3640190''>do</span> <span m=''3640280''>the</span> <span m=''3640400''>same</span>
  <span m=''3640710''>trick</span> <span m=''3640950''>that</span> <span m=''3641080''>we</span>
  <span m=''3641220''>did</span> <span m=''3641380''>in</span> <span m=''3641640''>the</span>
  <span m=''3641900''>power-limited</span> <span m=''3642570''>regime.</span> <span
  m=''3646110''>We will write</span> <span m=''3646620''>Ps</span> <span m=''3647070''>of</span>
  <span m=''3647540''>E</span> <span m=''3647920''>be</span> <span m=''3648300''>approximately
  --</span> <span m=''3649860''>and</span> <span m=''3650030''>instead</span> <span
  m=''3650250''>of</span> <span m=''3650370''>the</span> <span m=''3650460''>right</span>
  <span m=''3650640''>hand</span> <span m=''3650840''>side,</span> <span m=''3651550''>I</span>
  <span m=''3651650''>will write</span> <span m=''3651830''>it as</span> <span m=''3653190''>Ks</span>
  <span m=''3653530''>of</span> <span m=''3653980''>A</span> <span m=''3656210''>times</span>
  <span m=''3657680''>Q</span> <span m=''3657950''>of</span> <span m=''3658540''>root</span>
  <span m=''3658920''>3</span> <span m=''3661750''>SNR norm.</span> <span m=''3666390''>But</span>
  <span m=''3666570''>because</span> <span m=''3666680''>I</span> <span m=''3666830''>have
  a</span> <span m=''3667100''>factor</span> <span m=''3667440''>of</span> <span m=''3667510''>four</span>
  <span m=''3667810''>up there,</span> <span m=''3668380''>I</span> <span m=''3668500''>will</span>
  <span m=''3668560''>also</span> <span m=''3668900''>multiply</span> <span m=''3669030''>and</span>
  <span m=''3669550''>divide</span> <span m=''3669840''>by</span> <span m=''3669990''>4.</span>
  <span m=''3672790''>That''s</span> <span m=''3673030''>not</span> <span m=''3673160''>going</span>
  <span m=''3673290''>to</span> <span m=''3673430''>change</span> <span m=''3673720''>anything.</span>
  </p><p><span m=''3676024''>AUDIENCE: [INAUDIBLE]</span> <span m=''3677888''>per</span>
  <span m=''3678360''>two</span> <span m=''3678580''>dimensions</span> <span m=''3678810''>or</span>
  <span m=''3679140''>by symbol.</span> </p><p><span m=''3679470''>PROFESSOR: Per
  two</span> <span m=''3679820''>dimensions.</span> <span m=''3680925''>And</span>
  <span m=''3681690''>for</span> <span m=''3682005''>bandwidth-limited</span> <span
  m=''3682540''>regime,</span> <span m=''3682950''>we</span> <span m=''3683050''>normalize</span>
  <span m=''3683510''>everything</span> <span m=''3683900''>by</span> <span m=''3684020''>two</span>
  <span m=''3684210''>dimensions.</span> </p><p><span m=''3684600''>AUDIENCE: But</span>
  <span m=''3684990''>for</span> <span m=''3685470''>N</span> <span m=''3685950''>band</span>
  <span m=''3686910''>we</span> <span m=''3687210''>used</span> <span m=''3687510''>it</span>
  <span m=''3687866''>for symbols, right?</span> <span m=''3688222''>The calculations
  represent --</span> </p><p><span m=''3690790''>PROFESSOR: No, it was for two dimensions.</span>
  <span m=''3697720''>OK?,</span> <span m=''3698510''>so</span> <span m=''3698850''>now</span>
  <span m=''3699080''>let''s</span> <span m=''3699360''>compare</span> <span m=''3699790''>the</span>
  <span m=''3700030''>two</span> <span m=''3700200''>expressions.</span> <span m=''3702120''>We</span>
  <span m=''3702370''>have</span> <span m=''3702630''>Ks</span> <span m=''3703000''>of
  A,</span> <span m=''3705700''>which</span> <span m=''3706100''>we''ll</span> <span
  m=''3706600''>define</span> <span m=''3707095''>by</span> <span m=''3707590''>two</span>
  <span m=''3707860''>times</span> <span m=''3709910''>K_min</span> <span m=''3710200''>of</span>
  <span m=''3710310''>A</span> <span m=''3710960''>over</span> <span m=''3711030''>N.</span>
  <span m=''3712970''>And</span> <span m=''3713260''>this</span> <span m=''3713460''>is</span>
  <span m=''3713920''>the</span> <span m=''3714050''>number</span> <span m=''3714460''>of</span>
  <span m=''3716230''>nearest</span> <span m=''3716790''>neighbors</span> <span m=''3724040''>per</span>
  <span m=''3725670''>two</span> <span m=''3725810''>dimensions.</span> <span m=''3728740''>And</span>
  <span m=''3729390''>I</span> <span m=''3729490''>can</span> <span m=''3729720''>write</span>
  <span m=''3730000''>3</span> <span m=''3730300''>times</span> <span m=''3731110''>SNR
  norm</span> <span m=''3735060''>is</span> <span m=''3737760''>d_min</span> <span
  m=''3738530''>squared</span> <span m=''3739040''>over</span> <span m=''3739290''>4</span>
  <span m=''3739780''>sigma</span> <span m=''3740800''>squared,</span> <span m=''3745830''>OK?</span>
  <span m=''3747970''>Actually,</span> <span m=''3749190''>I</span> <span m=''3749320''>was</span>
  <span m=''3749450''>missing</span> <span m=''3749740''>this</span> <span m=''3749890''>factor</span>
  <span m=''3750220''>of</span> <span m=''3750320''>gamma.</span> <span m=''3750550''>I</span>
  <span m=''3750800''>knew I was</span> <span m=''3750940''>missing</span> <span m=''3751190''>something.</span>
  <span m=''3752070''>It''s</span> <span m=''3752240''>not</span> <span m=''3752410''>just</span>
  <span m=''3752685''>3</span> <span m=''3752960''>SNR norm.</span> <span m=''3754970''>It''s</span>
  <span m=''3755100''>3</span> <span m=''3755530''>times</span> <span m=''3755730''>this</span>
  <span m=''3755930''>nominal</span> <span m=''3756250''>coding</span> <span m=''3756900''>gain</span>
  <span m=''3758180''>times</span> <span m=''3758630''>SNR norm.</span> <span m=''3762080''>So</span>
  <span m=''3762330''>3</span> <span m=''3762520''>times</span> <span m=''3763150''>SNR
  norm</span> <span m=''3763380''>times</span> <span m=''3764900''>gamma_c</span>
  <span m=''3765130''>of</span> <span m=''3765240''>A</span> <span m=''3765900''>here.</span>
  <span m=''3767550''>So</span> <span m=''3767890''>this</span> <span m=''3768110''>is</span>
  <span m=''3768470''>d_min</span> <span m=''3768670''>squared</span> <span m=''3769050''>over</span>
  <span m=''3769580''>2N_0. </span> <span m=''3774850''>So</span> <span m=''3775110''>what</span>
  <span m=''3775330''>do</span> <span m=''3775420''>I</span> <span m=''3775500''>have</span>
  <span m=''3775810''>for</span> <span m=''3776140''>the gamma_c</span> <span m=''3776560''>c
  o</span> <span m=''3776820''>A</span> <span m=''3780610''>is</span> <span m=''3780720''>d_min</span>
  <span m=''3781510''>squared</span> <span m=''3782470''>over</span> <span m=''3783120''>6</span>
  <span m=''3783840''>N_0</span> <span m=''3785420''>times</span> <span m=''3785820''>SNR
  norm.</span> <span m=''3788740''>Remember</span> <span m=''3789080''>SNR norm</span>
  <span m=''3789420''>is</span> <span m=''3789550''>SNR</span> <span m=''3790230''>over</span>
  <span m=''3790510''>2</span> <span m=''3790630''>to the</span> <span m=''3790970''>rho</span>
  <span m=''3791360''>minus</span> <span m=''3791720''>1.</span> <span m=''3792480''>It''s</span>
  <span m=''3792980''>normalized</span> <span m=''3793760''>signal-to-noise ratio.</span>
  </p><p><span m=''3795730''>So</span> <span m=''3795860''>this</span> <span m=''3796100''>is</span>
  <span m=''3796390''>the</span> <span m=''3796510''>d_min</span> <span m=''3796730''>squared</span>
  <span m=''3797770''>times</span> <span m=''3798860''>2</span> <span m=''3799060''>to
  the</span> <span m=''3799520''>rho</span> <span m=''3800010''>minus</span> <span
  m=''3800420''>1</span> <span m=''3800890''>over</span> <span m=''3801880''>6</span>
  <span m=''3802280''>times</span> <span m=''3802820''>N_0</span> <span m=''3803230''>times</span>
  <span m=''3803610''>SNR.</span> <span m=''3804300''>But</span> <span m=''3804440''>N_0</span>
  <span m=''3804920''>times</span> <span m=''3805370''>SNR</span> <span m=''3805520''>is
  just</span> <span m=''3805840''>Es.</span> <span m=''3807390''>So</span> <span m=''3807590''>this</span>
  <span m=''3807770''>is</span> <span m=''3807870''>6</span> <span m=''3808230''>times</span>
  <span m=''3808750''>Es.</span> <span m=''3810180''>So</span> <span m=''3810330''>this</span>
  <span m=''3810490''>is</span> <span m=''3810620''>the</span> <span m=''3810720''>expression</span>
  <span m=''3811230''>you</span> <span m=''3811380''>have</span> <span m=''3811530''>for</span>
  <span m=''3811630''>the</span> <span m=''3811740''>nominal</span> <span m=''3812040''>coding</span>
  <span m=''3812490''>gain.</span> </p><p><span m=''3827760''>So</span> <span m=''3827960''>now</span>
  <span m=''3828230''>again,</span> <span m=''3828560''>given</span> <span m=''3829800''>a</span>
  <span m=''3829890''>signal</span> <span m=''3830160''>set</span> <span m=''3830430''>A,</span>
  <span m=''3831090''>I</span> <span m=''3831210''>can</span> <span m=''3831420''>find</span>
  <span m=''3831750''>those</span> <span m=''3831950''>two</span> <span m=''3832140''>parameters,</span>
  <span m=''3833130''>the</span> <span m=''3833760''>nominal</span> <span m=''3834290''>coding</span>
  <span m=''3834690''>gain</span> <span m=''3836180''>and</span> <span m=''3837090''>the</span>
  <span m=''3837950''>number</span> <span m=''3838360''>of</span> <span m=''3838500''>nearest</span>
  <span m=''3839370''>neighbors</span> <span m=''3839710''>per</span> <span m=''3839860''>two</span>
  <span m=''3840260''>dimensions.</span> <span m=''3841440''>And</span> <span m=''3841610''>I</span>
  <span m=''3841680''>can</span> <span m=''3842310''>use</span> <span m=''3842590''>those</span>
  <span m=''3842960''>to</span> <span m=''3843050''>plot</span> <span m=''3844020''>on</span>
  <span m=''3844310''>the</span> <span m=''3844850''>Ps</span> <span m=''3845580''>of
  E versus</span> <span m=''3845740''>SNR norm</span> <span m=''3846860''>curve.</span>
  </p><p><span m=''3847990''>Again,</span> <span m=''3848260''>the</span> <span m=''3848350''>exact</span>
  <span m=''3848730''>same</span> <span m=''3848920''>story.</span> <span m=''3852940''>If</span>
  <span m=''3853110''>I</span> <span m=''3853180''>have</span> <span m=''3853310''>a</span>
  <span m=''3853440''>certain</span> <span m=''3855460''>nominal</span> <span m=''3855750''>coding</span>
  <span m=''3856290''>gain,</span> <span m=''3857290''>I</span> <span m=''3857410''>will</span>
  <span m=''3857550''>simply</span> <span m=''3857920''>shift</span> <span m=''3859640''>my</span>
  <span m=''3860360''>curve</span> <span m=''3860730''>around the x-axis</span> <span
  m=''3861430''>by</span> <span m=''3861550''>that</span> <span m=''3861760''>factor</span>
  <span m=''3863320''>as</span> <span m=''3863410''>a</span> <span m=''3863460''>pure</span>
  <span m=''3863760''>translation.</span> <span m=''3865550''>And</span> <span m=''3865800''>then</span>
  <span m=''3866550''>because</span> <span m=''3866900''>I</span> <span m=''3866970''>have</span>
  <span m=''3867110''>a</span> <span m=''3867170''>factor</span> <span m=''3867540''>of</span>
  <span m=''3867710''>Ks</span> <span m=''3868830''>A</span> <span m=''3869110''>over</span>
  <span m=''3869320''>4,</span> <span m=''3871820''>I''m</span> <span m=''3872120''>going</span>
  <span m=''3872280''>to</span> <span m=''3872450''>plot --</span> <span m=''3873396''>how</span>
  <span m=''3873872''>did</span> <span m=''3874350''>that</span> <span m=''3874510''>expression</span>
  <span m=''3874980''>go?</span> <span m=''3875340''>This</span> <span m=''3875620''>expression</span>
  <span m=''3876040''>on</span> <span m=''3876140''>the</span> <span m=''3876260''>top.</span>
  <span m=''3877590''>Remember</span> <span m=''3877950''>this</span> <span m=''3878240''>curve</span>
  <span m=''3878410''>here</span> <span m=''3878630''>is</span> <span m=''3878770''>4</span>
  <span m=''3879060''>times</span> <span m=''3879330''>root</span> <span m=''3879790''>3</span>
  <span m=''3880040''> SNR norm,</span> <span m=''3880770''>right?</span> <span m=''3881440''>So</span>
  <span m=''3881610''>the</span> <span m=''3881690''>multiplicative</span> <span m=''3882360''>factor</span>
  <span m=''3882730''>I</span> <span m=''3882780''>have</span> <span m=''3882970''>is</span>
  <span m=''3883150''>Ks(A)</span> <span m=''3883620''>over</span> <span m=''3883870''>4.</span>
  <span m=''3884740''>So</span> <span m=''3885050''>I will</span> <span m=''3885170''>shift</span>
  <span m=''3885570''>my curve</span> <span m=''3885960''>up</span> <span m=''3886110''>by</span>
  <span m=''3886300''>that</span> <span m=''3886520''>factor.</span> <span m=''3890180''>And</span>
  <span m=''3890330''>I</span> <span m=''3890430''>will get</span> <span m=''3890700''>something</span>
  <span m=''3891340''>which</span> <span m=''3891490''>is</span> <span m=''3891640''>like</span>
  <span m=''3891880''>this.</span> <span m=''3897110''>And</span> <span m=''3897380''>that''s</span>
  <span m=''3897680''>my</span> <span m=''3897920''>union</span> <span m=''3898290''>bound</span>
  <span m=''3898560''>estimate</span> <span m=''3899100''>for</span> <span m=''3900020''>this</span>
  <span m=''3900260''>new</span> <span m=''3900430''>constellation</span> <span m=''3901200''>A.</span>
  </p><p><span m=''3904470''>The</span> <span m=''3904600''>distance</span> <span
  m=''3905100''>here</span> <span m=''3905530''>is</span> <span m=''3905880''>gamma</span>
  <span m=''3906090''>effective.</span> <span m=''3908990''>This</span> <span m=''3909200''>distance</span>
  <span m=''3909660''>here</span> <span m=''3909990''>is</span> <span m=''3910550''>gamma_c</span>
  <span m=''3910980''>of</span> <span m=''3911200''>A.</span> <span m=''3916940''>Are
  there any</span> <span m=''3917100''>questions?</span> <span m=''3919400''>So</span>
  <span m=''3919590''>now</span> <span m=''3919820''>we</span> <span m=''3919940''>also</span>
  <span m=''3920220''>have</span> <span m=''3920380''>a</span> <span m=''3920430''>similar</span>
  <span m=''3920850''>rule of</span> <span m=''3921250''>thumb</span> <span m=''3921520''>as</span>
  <span m=''3921660''>in</span> <span m=''3921760''>the</span> <span m=''3921870''>power-limited</span>
  <span m=''3922630''>regime.</span> <span m=''3924450''>I</span> <span m=''3924600''>will
  write</span> <span m=''3925010''>that</span> <span m=''3925240''>rule</span> <span
  m=''3925600''>of thumb</span> <span m=''3925870''>here.</span> <span m=''3927140''>We</span>
  <span m=''3927260''>have</span> <span m=''3927670''>that</span> <span m=''3928500''>gamma</span>
  <span m=''3928730''>effective</span> <span m=''3930740''>is</span> <span m=''3930940''>going</span>
  <span m=''3931170''>to</span> <span m=''3931380''>be</span> <span m=''3932120''>gamma_c</span>
  <span m=''3932500''>in</span> <span m=''3932870''>dB</span> <span m=''3934430''>minus</span>
  <span m=''3934980''>0.2</span> <span m=''3937480''>times</span> <span m=''3937660''>log2</span>
  <span m=''3938120''>times</span> <span m=''3938960''>Ks</span> <span m=''3939110''>of</span>
  <span m=''3939410''>A</span> <span m=''3939780''>over</span> <span m=''3940000''>4</span>
  <span m=''3942340''>in</span> <span m=''3942770''>dB.</span> <span m=''3946670''>OK,</span>
  <span m=''3946940''>so</span> <span m=''3947160''>again,</span> <span m=''3947470''>a</span>
  <span m=''3947510''>factor</span> <span m=''3947800''>of</span> <span m=''3948190''>2NKs</span>
  <span m=''3949010''>will</span> <span m=''3950180''>decrease</span> <span m=''3950490''>your</span>
  <span m=''3950950''>nominal</span> <span m=''3951400''>coding</span> <span m=''3951710''>gain</span>
  <span m=''3951950''>by</span> <span m=''3952420''>a</span> <span m=''3952520''>factor</span>
  <span m=''3952610''>of</span> <span m=''3952990''>0.2</span> <span m=''3954310''>in</span>
  <span m=''3954480''>dB.</span> <span m=''3958620''>Are</span> <span m=''3958790''>there</span>
  <span m=''3958960''>any</span> <span m=''3959040''>questions?</span> </p><p><span
  m=''3963260''>Well,</span> <span m=''3963840''>so</span> <span m=''3964120''>I</span>
  <span m=''3964170''>mean</span> <span m=''3964310''>this</span> <span m=''3964450''>is</span>
  <span m=''3964570''>the</span> <span m=''3964680''>end of</span> <span m=''3964940''>chapter</span>
  <span m=''3965320''>five.</span> <span m=''3966260''>We</span> <span m=''3966650''>still</span>
  <span m=''3966860''>have</span> <span m=''3967100''>like ten</span> <span m=''3967370''>minutes</span>
  <span m=''3967640''>remaining,</span> <span m=''3968160''>so</span> <span m=''3968350''>I</span>
  <span m=''3968450''>thought</span> <span m=''3968720''>I</span> <span m=''3968830''>would</span>
  <span m=''3968940''>give</span> <span m=''3969070''>you</span> <span m=''3969210''>a</span>
  <span m=''3969250''>preview</span> <span m=''3969690''>of</span> <span m=''3969800''>the</span>
  <span m=''3969960''>next</span> <span m=''3970130''>chapter.</span> <span m=''3971480''>Professor</span>
  <span m=''3971770''>Forney </span> <span m=''3972100''>will be</span> <span m=''3972270''>coming</span>
  <span m=''3972460''>next</span> <span m=''3972730''>class,</span> <span m=''3973070''>and</span>
  <span m=''3973190''>he</span> <span m=''3973340''>will</span> <span m=''3973510''>be</span>
  <span m=''3974030''>starting</span> <span m=''3974460''>chapter</span> <span m=''3974780''>six</span>
  <span m=''3975100''>all over</span> <span m=''3975500''>I</span> <span m=''3975580''>believe.</span>
  <span m=''3979030''>This</span> <span m=''3979180''>chalk</span> <span m=''3979470''>is</span>
  <span m=''3979590''>much</span> <span m=''3979770''>nicer</span> <span m=''3980240''>to
  erase</span> <span m=''3980570''>than</span> <span m=''3980700''>that</span> <span
  m=''3980810''>other one.</span> </p><p><span m=''4003000''>So</span> <span m=''4003200''>in</span>
  <span m=''4003370''>chapter</span> <span m=''4003780''>six,</span> <span m=''4007960''>we''ll
  be</span> <span m=''4008050''>looking</span> <span m=''4008410''>at</span> <span
  m=''4008570''>the</span> <span m=''4008650''>binary</span> <span m=''4009030''>block</span>
  <span m=''4009490''>codes.</span> <span m=''4020130''>OK,</span> <span m=''4021380''>and
  what is</span> <span m=''4021700''>the</span> <span m=''4021720''>main</span> <span
  m=''4022150''>architecture</span> <span m=''4022800''>of</span> <span m=''4022990''>these</span>
  <span m=''4023140''>codes?</span> <span m=''4024540''>Well,</span> <span m=''4025620''>for
  an</span> <span m=''4025960''>encoder,</span> <span m=''4026330''>remember</span>
  <span m=''4026690''>we</span> <span m=''4026840''>have</span> <span m=''4027310''>K
  bits</span> <span m=''4027560''>coming</span> <span m=''4027930''>in.</span> <span
  m=''4029700''>And</span> <span m=''4029970''>we</span> <span m=''4030090''>pass
  it</span> <span m=''4030610''>now</span> <span m=''4030980''>through</span> <span
  m=''4031170''>a</span> <span m=''4031350''>binary</span> <span m=''4031610''>block</span>
  <span m=''4032030''>code.</span> <span m=''4036070''>And</span> <span m=''4036310''>what</span>
  <span m=''4036520''>we</span> <span m=''4036670''>get</span> <span m=''4036860''>out</span>
  <span m=''4038370''>is</span> <span m=''4042090''>a</span> <span m=''4042170''>binary</span>
  <span m=''4042560''>sequence</span> <span m=''4043220''>of</span> <span m=''4043370''>length</span>
  <span m=''4043430''>N.</span> <span m=''4045210''>OK?  So</span> <span m=''4045910''>x</span>
  <span m=''4046070''>belongs</span> <span m=''4046360''>to</span> <span m=''4046650''>c,</span>
  <span m=''4047690''>where</span> <span m=''4047975''>c</span> <span m=''4048260''>is
  a subset</span> <span m=''4049480''>of</span> <span m=''4051180''>binary</span>
  <span m=''4051260''>sequences</span> <span m=''4051750''>of</span> <span m=''4051900''>length</span>
  <span m=''4052120''>N.</span> </p><p><span m=''4053550''>So</span> <span m=''4053730''>we</span>
  <span m=''4053860''>start</span> <span m=''4054150''>with</span> <span m=''4054370''>K
  bits,</span> <span m=''4055130''>and</span> <span m=''4055370''>we</span> <span
  m=''4055440''>convert</span> <span m=''4055800''>them</span> <span m=''4055990''>to</span>
  <span m=''4056280''>N bits,</span> <span m=''4057240''>where</span> <span m=''4057500''>N</span>
  <span m=''4057650''>is</span> <span m=''4057810''>going</span> <span m=''4058000''>to</span>
  <span m=''4058110''>be</span> <span m=''4058230''>greater</span> <span m=''4058520''>than</span>
  <span m=''4058650''>or</span> <span m=''4058810''>equal to</span> <span m=''4058940''>K.</span>
  <span m=''4062280''>Once</span> <span m=''4062500''>we</span> <span m=''4062610''>have</span>
  <span m=''4062720''>this</span> <span m=''4062870''>sequence</span> <span m=''4063290''>of</span>
  <span m=''4063440''>N bits,</span> <span m=''4064710''>what</span> <span m=''4064930''>we</span>
  <span m=''4065440''>end</span> <span m=''4065660''>up</span> <span m=''4065750''>doing</span>
  <span m=''4066080''>is</span> <span m=''4066335''>we</span> <span m=''4066590''>pass</span>
  <span m=''4066960''>it</span> <span m=''4067190''>through</span> <span m=''4068035''>a</span>
  <span m=''4068450''>binary</span> <span m=''4068780''>signal</span> <span m=''4069430''>constellation.</span>
  <span m=''4074710''>So</span> <span m=''4074900''>I''m writing in</span> <span m=''4075210''>as
  binary</span> <span m=''4075400''>signaling.</span> <span m=''4076690''>And</span>
  <span m=''4076910''>what</span> <span m=''4077150''>we</span> <span m=''4077260''>get</span>
  <span m=''4077490''>out</span> <span m=''4077820''>is</span> <span m=''4077990''>S</span>
  <span m=''4078120''>of</span> <span m=''4078510''>x,</span> <span m=''4080290''>which</span>
  <span m=''4080680''>is</span> <span m=''4082110''>a</span> <span m=''4082200''>sequence</span>
  <span m=''4082680''>of</span> <span m=''4082860''>N</span> <span m=''4082990''>symbols.</span>
  <span m=''4084940''>Each</span> <span m=''4085150''>symbol</span> <span m=''4085360''>can</span>
  <span m=''4085610''>either</span> <span m=''4085660''>take</span> <span m=''4085850''>value
  minus</span> <span m=''4086110''>alpha</span> <span m=''4086490''>or</span> <span
  m=''4086590''>alpha.</span> </p><p><span m=''4087110''>So</span> <span m=''4088250''>this</span>
  <span m=''4088550''>binary</span> <span m=''4089000''>signalling</span> <span m=''4089840''>is</span>
  <span m=''4089980''>actually</span> <span m=''4090300''>quite</span> <span m=''4090500''>a</span>
  <span m=''4090560''>trivial</span> <span m=''4091040''>step.</span> <span m=''4092130''>Basically,</span>
  <span m=''4092560''>the</span> <span m=''4092660''>relation</span> <span m=''4093120''>is</span>
  <span m=''4093230''>S</span> <span m=''4093430''>of</span> <span m=''4093560''>0</span>
  <span m=''4094360''>is</span> <span m=''4094540''>going</span> <span m=''4094710''>to</span>
  <span m=''4094870''>be</span> <span m=''4095020''>alpha,</span> <span m=''4096180''>S</span>
  <span m=''4096560''>of 1</span> <span m=''4096960''>is</span> <span m=''4097090''>going</span>
  <span m=''4097220''>to</span> <span m=''4097350''>be</span> <span m=''4097470''>minus</span>
  <span m=''4097859''>alpha.</span> <span m=''4098500''>If</span> <span m=''4098720''>I</span>
  <span m=''4098790''>have</span> <span m=''4098899''>a</span> <span m=''4099000''>0</span>
  <span m=''4099399''>coming</span> <span m=''4099680''>in,</span> <span m=''4100160''>I
  will</span> <span m=''4100510''>produce</span> <span m=''4100840''>an</span> <span
  m=''4100950''>alpha.</span> <span m=''4101520''>if</span> <span m=''4101689''>I</span>
  <span m=''4101740''>have</span> <span m=''4101830''>a</span> <span m=''4101920''>1</span>
  <span m=''4102130''>coming</span> <span m=''4102569''>in,  I will</span> <span m=''4102859''>produce</span>
  <span m=''4102930''>a</span> <span m=''4103069''>minus</span> <span m=''4103470''>alpha.</span>
  <span m=''4104520''>So</span> <span m=''4104700''>this</span> <span m=''4104960''>part</span>
  <span m=''4105430''>here is</span> <span m=''4105590''>trivial.</span> <span m=''4106689''>All</span>
  <span m=''4106949''>our</span> <span m=''4107210''>energy</span> <span m=''4107660''>will</span>
  <span m=''4107779''>be</span> <span m=''4107890''>focused</span> <span m=''4108420''>on</span>
  <span m=''4109000''>will</span> <span m=''4109130''>be to find</span> <span m=''4109500''>a</span>
  <span m=''4109870''>good code.</span> <span m=''4111340''>Given</span> <span m=''4111630''>a</span>
  <span m=''4111689''>sequence</span> <span m=''4112140''>of</span> <span m=''4112270''>input</span>
  <span m=''4112760''>bits,</span> <span m=''4112899''>we</span> <span m=''4113000''>want</span>
  <span m=''4113189''>to</span> <span m=''4113270''>find</span> <span m=''4113729''>a
  good</span> <span m=''4113970''>binary</span> <span m=''4114279''>code</span> <span
  m=''4115170''>in</span> <span m=''4115520''>order</span> <span m=''4118080''>to</span>
  <span m=''4118170''>optimize</span> <span m=''4118670''>the</span> <span m=''4118760''>minimum</span>
  <span m=''4119080''>distance</span> <span m=''4119510''>and</span> <span m=''4119700''>so</span>
  <span m=''4119890''>on.</span> <span m=''4120880''>So</span> <span m=''4121029''>that''s</span>
  <span m=''4121279''>the</span> <span m=''4121630''>architecture</span> <span m=''4121920''>that</span>
  <span m=''4122080''>we</span> <span m=''4122240''>will</span> <span m=''4122380''>be</span>
  <span m=''4122520''>using</span> <span m=''4123310''>for</span> <span m=''4123430''>the</span>
  <span m=''4123540''>binary</span> <span m=''4123689''>linear</span> <span m=''4124520''>codes.</span>
  <span m=''4125210''>Both</span> <span m=''4125450''>chapters</span> <span m=''4125810''>six</span>
  <span m=''4126090''>and</span> <span m=''4126229''>eight</span> <span m=''4126359''>will</span>
  <span m=''4126450''>be</span> <span m=''4126540''>only</span> <span m=''4126800''>focusing</span>
  <span m=''4127370''>on</span> <span m=''4127540''>this</span> <span m=''4127830''>part.</span>
  <span m=''4128250''>And</span> <span m=''4128490''>this</span> <span m=''4128630''>binary</span>
  <span m=''4128920''>signalling</span> <span m=''4129569''>scheme,</span> <span m=''4129890''>for</span>
  <span m=''4130029''>the</span> <span m=''4130200''>most</span> <span m=''4130359''>part,</span>
  <span m=''4130550''>will be</span> <span m=''4130689''>implicit</span> <span m=''4131660''>in</span>
  <span m=''4131790''>our</span> <span m=''4131970''>architecture.</span> </p><p><span
  m=''4135069''>So</span> <span m=''4135300''>at</span> <span m=''4135470''>this</span>
  <span m=''4135670''>point,</span> <span m=''4135979''>one</span> <span m=''4136010''>might</span>
  <span m=''4136340''>ask</span> <span m=''4136750''>is</span> <span m=''4137330''>there</span>
  <span m=''4137470''>anything</span> <span m=''4137760''>to lose</span> <span m=''4138399''>in</span>
  <span m=''4139020''>having imposed</span> <span m=''4139510''>this</span> <span
  m=''4139689''>type</span> <span m=''4139850''>of</span> <span m=''4140000''>architecture?</span>
  <span m=''4141359''>Remember,</span> <span m=''4141689''>the</span> <span m=''4141810''>nice</span>
  <span m=''4142080''>thing</span> <span m=''4142260''>about</span> <span m=''4142529''>this</span>
  <span m=''4143090''>architecture</span> <span m=''4143479''>is</span> <span m=''4143609''>we</span>
  <span m=''4143760''>have</span> <span m=''4143899''>coding,</span> <span m=''4144390''>which</span>
  <span m=''4144520''>is</span> <span m=''4144630''>going</span> <span m=''4144899''>on</span>
  <span m=''4145040''>here,</span> <span m=''4145810''>and</span> <span m=''4146050''>we</span>
  <span m=''4146200''>have</span> <span m=''4146359''>modulation</span> <span m=''4146910''>that</span>
  <span m=''4147069''>is</span> <span m=''4147170''>happening</span> <span m=''4147529''>here.</span>
  <span m=''4148460''>And</span> <span m=''4148569''>the</span> <span m=''4148640''>modulation</span>
  <span m=''4149170''>step</span> <span m=''4149430''>is</span> <span m=''4149609''>quite</span>
  <span m=''4149850''>simple.</span> <span m=''4150960''>So</span> <span m=''4151149''>we</span>
  <span m=''4151290''>have</span> <span m=''4151560''>a</span> <span m=''4151630''>separation</span>
  <span m=''4157220''>between</span> <span m=''4159450''>coding</span> <span m=''4162529''>and</span>
  <span m=''4162939''>modulation.  OK?</span> </p><p><span m=''4169689''>And</span>
  <span m=''4170149''>the</span> <span m=''4170250''>question</span> <span m=''4170600''>is,</span>
  <span m=''4170830''>is this</span> <span m=''4170979''>the</span> <span m=''4171250''>right</span>
  <span m=''4171380''>thing</span> <span m=''4171710''>to</span> <span m=''4171850''>do?</span>
  <span m=''4172600''>Now,</span> <span m=''4172800''>it turns</span> <span m=''4173029''>out</span>
  <span m=''4173160''>that</span> <span m=''4173370''>if</span> <span m=''4173609''>we</span>
  <span m=''4173859''>are going to</span> <span m=''4174010''>live</span> <span m=''4174240''>in</span>
  <span m=''4174380''>this</span> <span m=''4174520''>binary</span> <span m=''4174990''>world</span>
  <span m=''4175830''>where</span> <span m=''4176120''>we are only</span> <span m=''4176399''>constrained
  ourselves</span> <span m=''4176729''>to</span> <span m=''4176984''>sending</span>
  <span m=''4177380''>binary</span> <span m=''4177880''>signals</span> <span m=''4178210''>over</span>
  <span m=''4178470''>the</span> <span m=''4178649''>channel,</span> <span m=''4179439''>this</span>
  <span m=''4179609''>is</span> <span m=''4179740''>in</span> <span m=''4179859''>fact</span>
  <span m=''4180134''>an</span> <span m=''4180410''>economical</span> <span m=''4180899''>structure.</span>
  <span m=''4181800''>There</span> <span m=''4181920''>isn''t</span> <span m=''4181970''>much</span>
  <span m=''4182350''>improvement</span> <span m=''4182840''>we</span> <span m=''4182960''>can</span>
  <span m=''4183210''>get,</span> <span m=''4183490''>and</span> <span m=''4183760''>that</span>
  <span m=''4183939''>is</span> <span m=''4184069''>quite</span> <span m=''4184310''>obvious,</span>
  <span m=''4184689''>right?</span> <span m=''4185424''>But</span> <span m=''4185779''>it</span>
  <span m=''4185920''>turns</span> <span m=''4186240''>out</span> <span m=''4186420''>that</span>
  <span m=''4186580''>if</span> <span m=''4186790''>you</span> <span m=''4186990''>are</span>
  <span m=''4187340''>going to go</span> <span m=''4187560''>for</span> <span m=''4187689''>non-binary</span>
  <span m=''4188410''>signaling,</span> <span m=''4189020''>particularly</span> <span
  m=''4189630''>in</span> <span m=''4189790''>the</span> <span m=''4190149''>bandwidth-limited</span>
  <span m=''4190740''>regime,</span> <span m=''4191870''>there is</span> <span m=''4192010''>a</span>
  <span m=''4192160''>cost</span> <span m=''4192550''>to</span> <span m=''4192649''>be</span>
  <span m=''4192810''>paid</span> <span m=''4193450''>for</span> <span m=''4193590''>this</span>
  <span m=''4193830''>kind</span> <span m=''4194050''>of</span> <span m=''4194140''>separation.</span>
  <span m=''4195460''>In</span> <span m=''4195610''>fact,</span> <span m=''4195850''>in
  the</span> <span m=''4195940''>1980''s</span> <span m=''4196610''>there</span> <span
  m=''4196750''>was</span> <span m=''4196890''>this</span> <span m=''4197130''>whole</span>
  <span m=''4197270''>idea</span> <span m=''4197580''>of</span> <span m=''4197950''>turbo-coded
  modulation</span> <span m=''4198800''>or</span> <span m=''4199130''>trellis-coded</span>
  <span m=''4199860''>modulation.</span> <span m=''4201060''>And</span> <span m=''4201320''>the</span>
  <span m=''4201660''>idea there</span> <span m=''4201910''>was</span> <span m=''4202110''>to</span>
  <span m=''4202250''>combine</span> <span m=''4202580''>coding</span> <span m=''4203020''>and</span>
  <span m=''4203120''>modulation</span> <span m=''4203680''>in</span> <span m=''4203810''>one</span>
  <span m=''4203990''>step.</span> <span m=''4205110''>So</span> <span m=''4205860''>this</span>
  <span m=''4206070''>is</span> <span m=''4206300''>not</span> <span m=''4208310''>optimal</span>
  <span m=''4210760''>for</span> <span m=''4211520''>non-binary</span> <span m=''4215140''>signalling,</span>
  <span m=''4219010''>but''s</span> <span m=''4219440''>it''s</span> <span m=''4221580''>OK</span>
  <span m=''4221920''>for</span> <span m=''4224800''>binary.</span> <span m=''4230570''>So</span>
  <span m=''4230960''>we will be</span> <span m=''4231060''>focusing</span> <span
  m=''4231550''>on</span> <span m=''4231670''>this</span> <span m=''4231970''>type
  of an</span> <span m=''4232230''>architecture.</span> </p><p><span m=''4233820''>The
  other</span> <span m=''4234200''>issue</span> <span m=''4234610''>is</span> <span
  m=''4234960''>OK,</span> <span m=''4235550''>nobody</span> <span m=''4235950''>told</span>
  <span m=''4236120''>us</span> <span m=''4236290''>that you</span> <span m=''4236560''>can</span>
  <span m=''4236710''>only</span> <span m=''4236820''>send</span> <span m=''4237130''>binary</span>
  <span m=''4237510''>signals</span> <span m=''4237910''>over</span> <span m=''4238240''>the</span>
  <span m=''4238380''>channel.</span> <span m=''4239080''>If</span> <span m=''4239240''>you</span>
  <span m=''4239380''>want</span> <span m=''4239600''>to</span> <span m=''4239810''>achieve</span>
  <span m=''4239940''>the</span> <span m=''4240040''>Shannon</span> <span m=''4240410''>limit,</span>
  <span m=''4241480''>when</span> <span m=''4241570''>we</span> <span m=''4241700''>derived</span>
  <span m=''4242270''>the</span> <span m=''4243330''>capacity</span> <span m=''4243800''>expression
  --</span> <span m=''4244580''>or</span> <span m=''4244770''>we just</span> <span
  m=''4244990''>stated</span> <span m=''4245150''>it</span> <span m=''4245260''>but</span>
  <span m=''4245750''>you</span> <span m=''4245890''>can</span> <span m=''4246070''>derive
  it.</span> <span m=''4246970''>We</span> <span m=''4247190''>said</span> <span m=''4247460''>that</span>
  <span m=''4247720''>the</span> <span m=''4247950''>Shannon</span> <span m=''4248300''>limit</span>
  <span m=''4248480''>is</span> <span m=''4249150''>always</span> <span m=''4249330''>less</span>
  <span m=''4249660''>than</span> <span m=''4250580''>log2</span> <span m=''4251450''>1</span>
  <span m=''4251750''>plus</span> <span m=''4252090''>SNR.</span> <span m=''4252830''>And</span>
  <span m=''4253330''>we</span> <span m=''4253430''>never</span> <span m=''4253690''>said</span>
  <span m=''4253940''>that</span> <span m=''4254130''>we</span> <span m=''4254540''>can</span>
  <span m=''4254600''>only send</span> <span m=''4254830''>binary</span> <span m=''4255180''>signals</span>
  <span m=''4255620''>over</span> <span m=''4255980''>the channel.</span> <span m=''4256840''>So</span>
  <span m=''4257000''>it could</span> <span m=''4257110''>be</span> <span m=''4257250''>that</span>
  <span m=''4257440''>this is</span> <span m=''4257620''>some</span> <span m=''4257910''>inherence
  of</span> <span m=''4258050''>optimality</span> <span m=''4259070''>in</span> <span
  m=''4259360''>this</span> <span m=''4259860''>type of</span> <span m=''4260160''>architecture.</span>
  <span m=''4260770''>Why</span> <span m=''4261230''>send</span> <span m=''4261410''>binary</span>
  <span m=''4261580''>signals</span> <span m=''4262050''>in</span> <span m=''4262140''>the</span>
  <span m=''4262390''>first</span> <span m=''4262630''>place?</span> </p><p><span
  m=''4263730''>Again,</span> <span m=''4264070''>it</span> <span m=''4264210''>turns</span>
  <span m=''4264550''>out</span> <span m=''4264840''>that</span> <span m=''4265360''>the</span>
  <span m=''4265470''>regime</span> <span m=''4265830''>that</span> <span m=''4266040''>we</span>
  <span m=''4266470''>are</span> <span m=''4266800''>interested in</span> <span m=''4267080''>here</span>
  <span m=''4267380''>is</span> <span m=''4267460''>the</span> <span m=''4267550''>power-limited</span>
  <span m=''4268330''>regime</span> <span m=''4269320''>because</span> <span m=''4269650''>the</span>
  <span m=''4269740''>spectral</span> <span m=''4270130''>efficiency</span> <span
  m=''4270650''>can</span> <span m=''4270840''>never</span> <span m=''4271090''>be</span>
  <span m=''4271190''>more</span> <span m=''4271380''>than</span> <span m=''4271590''>two</span>
  <span m=''4271680''>bits</span> <span m=''4271950''>per two</span> <span m=''4272220''>dimensions,</span>
  <span m=''4272485''>right?</span> <span m=''4273810''>Remember,</span> <span m=''4274070''>rho</span>
  <span m=''4274240''>is</span> <span m=''4274480''>2K</span> <span m=''4274690''>over</span>
  <span m=''4274830''>N</span> <span m=''4274980''>here,</span> <span m=''4275550''>and</span>
  <span m=''4275720''>K</span> <span m=''4275840''>is</span> <span m=''4275980''>going</span>
  <span m=''4276100''>to</span> <span m=''4276220''>be</span> <span m=''4276340''>less</span>
  <span m=''4276590''>than</span> <span m=''4276740''>that.</span> </p><p><span m=''4277290''>So</span>
  <span m=''4277460''>we</span> <span m=''4277570''>are</span> <span m=''4278060''>inherently</span>
  <span m=''4278490''>in</span> <span m=''4278690''>the</span> <span m=''4280760''>power-limited</span>
  <span m=''4281250''>regime.</span> <span m=''4282130''>And</span> <span m=''4282320''>so</span>
  <span m=''4282640''>a</span> <span m=''4282850''>natural</span> <span m=''4283050''>thing</span>
  <span m=''4283250''>to</span> <span m=''4283430''>do</span> <span m=''4283830''>in
  order to</span> <span m=''4284100''>understand</span> <span m=''4284610''>how</span>
  <span m=''4284770''>much</span> <span m=''4284990''>fundamental</span> <span m=''4285620''>loss</span>
  <span m=''4285960''>we</span> <span m=''4286260''>have</span> <span m=''4286800''>in</span>
  <span m=''4286930''>imposing</span> <span m=''4287410''>this</span> <span m=''4287610''>type
  of</span> <span m=''4288120''>binary</span> <span m=''4289030''>constraint</span>
  <span m=''4289620''>over</span> <span m=''4289830''>the</span> <span m=''4289950''>signals</span>
  <span m=''4290810''>is</span> <span m=''4291070''>to</span> <span m=''4291660''>not</span>
  <span m=''4291920''>look</span> <span m=''4292050''>at</span> <span m=''4292190''>this</span>
  <span m=''4292360''>expression,</span> <span m=''4293400''>but</span> <span m=''4293730''>to</span>
  <span m=''4293820''>find</span> <span m=''4294210''>the</span> <span m=''4294300''>best</span>
  <span m=''4294920''>possible</span> <span m=''4295400''>performance</span> <span
  m=''4296160''>we</span> <span m=''4296470''>can</span> <span m=''4296755''>have</span>
  <span m=''4297330''>if</span> <span m=''4297580''>we</span> <span m=''4297740''>constrain</span>
  <span m=''4298005''>ourselves</span> <span m=''4298670''>to</span> <span m=''4298770''>binary</span>
  <span m=''4298940''>signals</span> <span m=''4299390''>over</span> <span m=''4299840''>the</span>
  <span m=''4299970''>channel.</span> <span m=''4301090''>If</span> <span m=''4301260''>we</span>
  <span m=''4301400''>impose</span> <span m=''4301780''>a</span> <span m=''4301850''>certain</span>
  <span m=''4302160''>signaling</span> <span m=''4302620''>constraint,</span> <span
  m=''4303550''>we</span> <span m=''4303710''>can</span> <span m=''4303910''>find</span>
  <span m=''4304710''>another</span> <span m=''4305050''>fundamental</span> <span
  m=''4305750''>limit</span> <span m=''4306510''>on</span> <span m=''4306670''>the</span>
  <span m=''4306780''>spectral</span> <span m=''4307230''>efficiency.</span> <span
  m=''4309330''>So</span> <span m=''4310290''>the</span> <span m=''4310550''>point</span>
  <span m=''4310900''>being,</span> <span m=''4311060''>the</span> <span m=''4311170''>best</span>
  <span m=''4311440''>possible</span> <span m=''4311870''>binary</span> <span m=''4312330''>code</span>
  <span m=''4312620''>can</span> <span m=''4312790''>only</span> <span m=''4313070''>achieve</span>
  <span m=''4313710''>this</span> <span m=''4313920''>upper</span> <span m=''4314230''>bound</span>
  <span m=''4314500''>here.</span> <span m=''4315450''>Now,</span> <span m=''4315550''>this</span>
  <span m=''4315650''>upper bound</span> <span m=''4315940''>has</span> <span m=''4316390''>to</span>
  <span m=''4316500''>be</span> <span m=''4316600''>less</span> <span m=''4316820''>than</span>
  <span m=''4317050''>log2</span> <span m=''4317370''>1</span> <span m=''4317540''>plus</span>
  <span m=''4317710''>SNR,</span> <span m=''4318050''>right?</span> <span m=''4323170''>Because</span>
  <span m=''4323450''>the</span> <span m=''4323530''>Shannon</span> <span m=''4324270''>code</span>
  <span m=''4325120''>assumes</span> <span m=''4325260''>the</span> <span m=''4325440''>binary</span>
  <span m=''4325620''>signaling</span> <span m=''4326070''>is</span> <span m=''4326160''>a</span>
  <span m=''4326230''>special</span> <span m=''4326660''>case.</span> </p><p><span
  m=''4327640''>So</span> <span m=''4328020''>it</span> <span m=''4328190''>turns</span>
  <span m=''4328370''>out</span> <span m=''4328540''>that</span> <span m=''4328660''>this</span>
  <span m=''4328770''>expression</span> <span m=''4329160''>is</span> <span m=''4329230''>actually</span>
  <span m=''4330070''>quite</span> <span m=''4330700''>tedious</span> <span m=''4331190''>to
  write</span> <span m=''4331580''>out.</span> <span m=''4332310''>I''m</span> <span
  m=''4332520''>not even</span> <span m=''4332970''>sure</span> <span m=''4333040''>if</span>
  <span m=''4333180''>the</span> <span m=''4333770''>closed-form</span> <span m=''4334020''>expression</span>
  <span m=''4334530''>exists,</span> <span m=''4335090''>but</span> <span m=''4335230''>you</span>
  <span m=''4335330''>can</span> <span m=''4335510''>calculate</span> <span m=''4335930''>this</span>
  <span m=''4336100''>numerically.</span> <span m=''4336820''>It''s</span> <span m=''4336960''>just</span>
  <span m=''4337080''>some</span> <span m=''4337270''>kind</span> <span m=''4337470''>of</span>
  <span m=''4337600''>a</span> <span m=''4337810''>convex</span> <span m=''4337990''>optimization</span>
  <span m=''4338710''>problem.</span> </p><p><span m=''4339760''>And</span> <span
  m=''4339960''>now,</span> <span m=''4340280''>to</span> <span m=''4340520''>understand</span>
  <span m=''4340990''>how</span> <span m=''4341130''>much</span> <span m=''4341370''>loss</span>
  <span m=''4341640''>we</span> <span m=''4341770''>have,</span> <span m=''4342010''>we</span>
  <span m=''4342140''>can</span> <span m=''4342350''>compare</span> <span m=''4342640''>the</span>
  <span m=''4342840''>two</span> <span m=''4342970''>expressions</span> <span m=''4343690''>in</span>
  <span m=''4343780''>the</span> <span m=''4343890''>power-limited</span> <span m=''4344410''>regime.</span>
  <span m=''4346090''>So</span> <span m=''4346850''>I''m</span> <span m=''4347010''>going</span>
  <span m=''4347280''>to</span> <span m=''4347370''>plot</span> <span m=''4347820''>the</span>
  <span m=''4348000''>curves</span> <span m=''4348460''>for</span> <span m=''4348650''>the</span>
  <span m=''4348900''>two</span> <span m=''4349310''>cases.</span> <span m=''4350690''>I''m</span>
  <span m=''4350850''>going</span> <span m=''4351020''>to</span> <span m=''4351190''>plot</span>
  <span m=''4352140''>the</span> <span m=''4352220''>spectral</span> <span m=''4352640''>efficiency</span>
  <span m=''4353320''>on</span> <span m=''4353440''>the</span> <span m=''4353550''>y-axis</span>
  <span m=''4355100''>as</span> <span m=''4355290''>a</span> <span m=''4355350''>function</span>
  <span m=''4355810''>of</span> <span m=''4355850''>Eb</span> <span m=''4356090''>N_0.</span>
  <span m=''4356500''>You</span> <span m=''4356620''>can</span> <span m=''4356780''>easily</span>
  <span m=''4357080''>convert</span> <span m=''4357450''>from</span> <span m=''4357640''>SNR</span>
  <span m=''4357830''>to</span> <span m=''4358110''>Eb N_0</span> <span m=''4358670''>using</span>
  <span m=''4358920''>the</span> <span m=''4359000''>relations</span> <span m=''4359490''>we</span>
  <span m=''4359550''>discussed</span> <span m=''4359970''>in</span> <span m=''4360040''>chapter</span>
  <span m=''4360440''>four.</span> </p><p><span m=''4362210''>Now</span> <span m=''4363500''>we
  first</span> <span m=''4363770''>plot</span> <span m=''4363920''>the</span> <span
  m=''4364060''>Shannon</span> <span m=''4364500''>limit.</span> <span m=''4365030''>The</span>
  <span m=''4365210''>ultimate</span> <span m=''4365600''>Shannon</span> <span m=''4365950''>limit
  is</span> <span m=''4366340''>minus</span> <span m=''4366680''>1.59</span> <span
  m=''4367140''>dB.</span> <span m=''4368920''>This is</span> <span m=''4369170''>going</span>
  <span m=''4369320''>to</span> <span m=''4369460''>be</span> <span m=''4369600''>0</span>
  <span m=''4369950''>dB</span> <span m=''4370260''>here.</span> <span m=''4372000''>And</span>
  <span m=''4372150''>if</span> <span m=''4372290''>I''m</span> <span m=''4372340''>plot</span>
  <span m=''4372740''>the</span> <span m=''4372830''>Shannon</span> <span m=''4373410''>limit,</span>
  <span m=''4373850''>it</span> <span m=''4373960''>will be</span> <span m=''4374100''>some</span>
  <span m=''4374410''>code</span> <span m=''4374800''>like</span> <span m=''4375030''>this.</span>
  <span m=''4376260''>It</span> <span m=''4376450''>increases</span> <span m=''4376670''>with</span>
  <span m=''4376750''>Eb N_0.</span> <span m=''4378080''>And</span> <span m=''4378670''>minus</span>
  <span m=''4378970''>1.59</span> <span m=''4379110''>dB</span> <span m=''4379860''>is</span>
  <span m=''4380180''>0.</span> <span m=''4381210''>This</span> <span m=''4381430''>point</span>
  <span m=''4381700''>here</span> <span m=''4381940''>is</span> <span m=''4382080''>1.</span>
  <span m=''4383130''>Some</span> <span m=''4383710''>point</span> <span m=''4383910''>here
  is</span> <span m=''4384130''>2.</span> <span m=''4385070''>So actually</span> <span
  m=''4385390''>I want</span> <span m=''4385750''>to</span> <span m=''4386000''>draw
  this</span> <span m=''4386620''>horizontal</span> <span m=''4386860''>asymptote</span>
  <span m=''4388920''>at</span> <span m=''4389200''>two</span> <span m=''4389970''>when</span>
  <span m=''4390660''>rho</span> <span m=''4390950''>Shannon</span> <span m=''4391220''>equals</span>
  <span m=''4391672''>2.</span> </p><p><span m=''4393030''>So</span> <span m=''4393220''>this</span>
  <span m=''4393400''>is</span> <span m=''4393500''>my</span> <span m=''4393670''>rho</span>
  <span m=''4393940''>Shannon.</span> <span m=''4395720''>Now,</span> <span m=''4395900''>I</span>
  <span m=''4396000''>can</span> <span m=''4396110''>now</span> <span m=''4396430''>
  also plot</span> <span m=''4396800''>rho</span> <span m=''4397000''>binary</span>
  <span m=''4398700''>from</span> <span m=''4399200''>this</span> <span m=''4399390''>expression</span>
  <span m=''4399960''>here.</span> <span m=''4401020''>I</span> <span m=''4401120''>can</span>
  <span m=''4401310''>never</span> <span m=''4401440''>exceed</span> <span m=''4401660''>two</span>
  <span m=''4401880''>bits</span> <span m=''4402190''>per two</span> <span m=''4402620''>dimensions.</span>
  <span m=''4403220''>So</span> <span m=''4403590''>I</span> <span m=''4403750''>had</span>
  <span m=''4403910''>plotted</span> <span m=''4404240''>this</span> <span m=''4404390''>horizontal</span>
  <span m=''4404950''>line.</span> <span m=''4405720''>So as</span> <span m=''4406180''>Eb
  N_0</span> <span m=''4406390''>goes to</span> <span m=''4406500''>infinity,</span>
  <span m=''4407110''>the</span> <span m=''4407230''>most</span> <span m=''4407570''>I</span>
  <span m=''4407630''>can</span> <span m=''4408000''>get</span> <span m=''4408160''>is</span>
  <span m=''4408290''>two bits</span> <span m=''4408720''>per two</span> <span m=''4408850''>dimensions.</span>
  <span m=''4410250''>If</span> <span m=''4410410''>Eb N_0</span> <span m=''4410620''>is</span>
  <span m=''4410810''>smaller,</span> <span m=''4413020''>I</span> <span m=''4413060''>cannot</span>
  <span m=''4413360''>do</span> <span m=''4413440''>better</span> <span m=''4413970''>so
  I</span> <span m=''4414100''>will</span> <span m=''4414330''>be</span> <span m=''4414560''>doing</span>
  <span m=''4415380''>worse and</span> <span m=''4415870''>worse,</span> <span m=''4416420''>and</span>
  <span m=''4416530''>I</span> <span m=''4416620''>will</span> <span m=''4416700''>always</span>
  <span m=''4416800''>be</span> <span m=''4417370''>below this line.</span> <span
  m=''4418210''>Ultimately,</span> <span m=''4419090''>it</span> <span m=''4419580''>can</span>
  <span m=''4419740''>be</span> <span m=''4419820''>shown</span> <span m=''4420200''>that</span>
  <span m=''4420350''>I</span> <span m=''4420400''>will have</span> <span m=''4420670''>the</span>
  <span m=''4420750''>same</span> <span m=''4421330''>Shannon</span> <span m=''4421650''>limit</span>
  <span m=''4422030''>here.</span> <span m=''4423210''>So</span> <span m=''4423380''>this</span>
  <span m=''4423560''>is</span> <span m=''4424150''>rho</span> <span m=''4424630''>binary.</span>
  </p><p><span m=''4428380''>And</span> <span m=''4428830''>the</span> <span m=''4429040''>main</span>
  <span m=''4429420''>observation</span> <span m=''4430110''>here</span> <span m=''4430460''>is</span>
  <span m=''4430600''>if</span> <span m=''4430770''>I''m</span> <span m=''4430920''>in</span>
  <span m=''4431000''>the</span> <span m=''4431080''>power-limited</span> <span m=''4431830''>regime,</span>
  <span m=''4432760''>which</span> <span m=''4432950''>is</span> <span m=''4433170''>say,</span>
  <span m=''4433410''>in this</span> <span m=''4433860''>part</span> <span m=''4434090''>of</span>
  <span m=''4434210''>the</span> <span m=''4434370''>curve --</span> <span m=''4435150''>like,</span>
  <span m=''4435340''>say</span> <span m=''4435630''>around</span> <span m=''4435780''>one</span>
  <span m=''4435970''>bit</span> <span m=''4436170''>per two</span> <span m=''4436550''>dimension
  --</span> <span m=''4437020''>the</span> <span m=''4437140''>gap</span> <span m=''4437480''>here</span>
  <span m=''4437650''>is</span> <span m=''4437820''>quite</span> <span m=''4438080''>small.</span>
  <span m=''4439390''>In</span> <span m=''4439540''>fact,</span> <span m=''4439790''>this</span>
  <span m=''4440020''>gap</span> <span m=''4440310''>can</span> <span m=''4440470''>be</span>
  <span m=''4440630''>shown</span> <span m=''4441030''>to</span> <span m=''4441130''>be</span>
  <span m=''4441350''>at</span> <span m=''4441480''>most</span> <span m=''4441780''>0.2</span>
  <span m=''4442270''>dB.</span> <span m=''4445190''>So</span> <span m=''4445340''>if</span>
  <span m=''4445450''>I</span> <span m=''4445510''>want</span> <span m=''4445780''>to</span>
  <span m=''4445990''>achieve</span> <span m=''4446170''>a</span> <span m=''4446210''>certain</span>
  <span m=''4446520''>spectral</span> <span m=''4446880''>efficiency,</span> <span
  m=''4448130''>if</span> <span m=''4448340''>I</span> <span m=''4448550''>impose</span>
  <span m=''4448710''>a</span> <span m=''4448860''>binary</span> <span m=''4449220''>signaling</span>
  <span m=''4449700''>constraint,</span> <span m=''4450020''>the</span> <span m=''4450340''>additional</span>
  <span m=''4450740''>Eb N_0</span> <span m=''4451560''>that</span> <span m=''4451700''>I</span>
  <span m=''4451940''>require</span> <span m=''4452810''>when</span> <span m=''4452940''>the</span>
  <span m=''4453020''>spectral</span> <span m=''4453390''>efficiency</span> <span
  m=''4453980''>is</span> <span m=''4454100''>1</span> <span m=''4454360''>dB,</span>
  <span m=''4455300''>one</span> <span m=''4455590''>bit per</span> <span m=''4455740''>two</span>
  <span m=''4456020''>dimensions,</span> <span m=''4456540''>is</span> <span m=''4456640''>at</span>
  <span m=''4456780''>most</span> <span m=''4457030''>0.2</span> <span m=''4457440''>dB.</span>
  <span m=''4458360''>So</span> <span m=''4458500''>there</span> <span m=''4458650''>is</span>
  <span m=''4458750''>not</span> <span m=''4459490''>much to</span> <span m=''4459790''>lose</span>
  <span m=''4460630''>by</span> <span m=''4460850''>imposing</span> <span m=''4461360''>a</span>
  <span m=''4461410''>binary</span> <span m=''4461790''>signaling</span> <span m=''4462280''>constraint.</span>
  </p><p><span m=''4463870''>Said in </span> <span m=''4464260''>different words</span>
  <span m=''4464660''>words</span> <span m=''4464950''>if</span> <span m=''4465080''>you</span>
  <span m=''4465190''>had</span> <span m=''4465360''>the</span> <span m=''4465440''>best</span>
  <span m=''4465760''>possible</span> <span m=''4466220''>binary</span> <span m=''4466550''>linear</span>
  <span m=''4466840''>code,</span> <span m=''4467790''>followed</span> <span m=''4468340''>by</span>
  <span m=''4468500''>a</span> <span m=''4468800''>binary signaling</span> <span m=''4469150''>constellation,</span>
  <span m=''4470320''>the</span> <span m=''4470440''>most</span> <span m=''4470720''>you</span>
  <span m=''4470830''>can</span> <span m=''4471070''>lose</span> <span m=''4471290''>is</span>
  <span m=''4471470''>0.2</span> <span m=''4471890''>dB.</span> <span m=''4473210''>And</span>
  <span m=''4473390''>so</span> <span m=''4473510''>this</span> <span m=''4473670''>type</span>
  <span m=''4473820''>of</span> <span m=''4473980''>an</span> <span m=''4474050''>architecture</span>
  <span m=''4474570''>does</span> <span m=''4474820''>make</span> <span m=''4475030''>sense.</span>
  <span m=''4476070''>There</span> <span m=''4476370''>are a</span> <span m=''4476430''>lot</span>
  <span m=''4476640''>of</span> <span m=''4476790''>details</span> <span m=''4477320''>that</span>
  <span m=''4478290''>the</span> <span m=''4478890''>next</span> <span m=''4479160''>powerpoint</span>
  <span m=''4479620''>will be to</span> <span m=''4480870''>kind of formalize</span>
  <span m=''4481500''>the</span> <span m=''4481600''>notion</span> <span m=''4481970''>of</span>
  <span m=''4482110''>a</span> <span m=''4482160''>binary</span> <span m=''4483470''>block</span>
  <span m=''4483900''>code,</span> <span m=''4484680''>then</span> <span m=''4484870''>specialize</span>
  <span m=''4485360''>it</span> <span m=''4485540''>to the</span> <span m=''4485660''>case</span>
  <span m=''4486010''>of</span> <span m=''4486400''>binary</span> <span m=''4486750''>linear</span>
  <span m=''4486850''>codes</span> <span m=''4487210''>and</span> <span m=''4487430''>so</span>
  <span m=''4487650''>on.</span> </p><p><span m=''4488450''>Unfortunately,</span>
  <span m=''4489060''>the</span> <span m=''4489860''>first</span> <span m=''4490270''>thing
  to</span> <span m=''4490380''>do</span> <span m=''4490660''>is to</span> <span m=''4490790''>start</span>
  <span m=''4491070''>with</span> <span m=''4491190''>some</span> <span m=''4491370''>finite</span>
  <span m=''4491790''>field</span> <span m=''4492240''>theory</span> <span m=''4492900''>because</span>
  <span m=''4493790''>there''s</span> <span m=''4493940''>a</span> <span m=''4493970''>lot</span>
  <span m=''4494120''>of</span> <span m=''4494200''>finite</span> <span m=''4494580''>field</span>
  <span m=''4494970''>algebra</span> <span m=''4495520''>involved</span> <span m=''4495830''>in
  this</span> <span m=''4496440''>algebraic</span> <span m=''4496890''>block</span>
  <span m=''4497260''>codes.</span> <span m=''4497780''>So</span> <span m=''4497940''>how</span>
  <span m=''4498130''>many</span> <span m=''4498320''>of</span> <span m=''4498450''>you</span>
  <span m=''4498640''>have seen</span> <span m=''4498960''>finite</span> <span m=''4499440''>field</span>
  <span m=''4499650''>theory</span> <span m=''4500020''>before?</span> <span m=''4502580''>OK,</span>
  <span m=''4503620''>if</span> <span m=''4503760''>you</span> <span m=''4503860''>haven''t</span>
  <span m=''4504150''>seen</span> <span m=''4504380''>it,</span> <span m=''4504490''>don''t</span>
  <span m=''4504700''>worry</span> <span m=''4504960''>about</span> <span m=''4505300''>it.</span>
  <span m=''4505810''>We''ll be</span> <span m=''4506010''>starting</span> <span m=''4506470''>right</span>
  <span m=''4506670''>from</span> <span m=''4506880''>the</span> <span m=''4507090''>basics.</span>
  <span m=''4508570''>But</span> <span m=''4508750''>I</span> <span m=''4508880''>think</span>
  <span m=''4509000''>I will</span> <span m=''4509070''>be</span> <span m=''4509210''>stopping</span>
  <span m=''4509570''>here</span> <span m=''4509830''>for</span> <span m=''4510130''>today</span>
  <span m=''4510660''>because</span> <span m=''4511340''>I</span> <span m=''4511430''>don''t</span>
  <span m=''4511580''>want</span> <span m=''4511730''>to</span> <span m=''4511790''>go</span>
  <span m=''4511960''>into</span> <span m=''4512210''>those</span> <span m=''4512920''>details</span>
  <span m=''4513270''>today.</span> </p>'
type: course
uid: c4eb2579c9a4e913ac695873cdaf4c45

---
None