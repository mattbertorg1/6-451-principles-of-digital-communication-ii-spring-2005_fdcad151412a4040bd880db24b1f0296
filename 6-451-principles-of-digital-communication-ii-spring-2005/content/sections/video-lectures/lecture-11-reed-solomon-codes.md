---
about_this_resource_text: '<p><strong>Topics covered:</strong> Reed-Solomon Codes</p><p><strong>Instructor:
  </strong>Prof. David Forney</p>'
course_id: 6-451-principles-of-digital-communication-ii-spring-2005
embedded_media:
- id: 11.jpg
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-11-reed-solomon-codes/11.jpg
  title: 11.jpg
  type: null
  uid: eb0d2986e382de10ba9ffaec4873d4c0
- id: Video-YouTube-Stream
  media_location: mnkTn0Y6GsU
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Video-YouTube-Stream
  type: Video
  uid: 631d4dd9e7f7c1b74e63fd1aff0d24b4
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/mnkTn0Y6GsU/default.jpg
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 15724dbe171d48537558194c45a684ab
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597857
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Video-iTunes U-MP4
  type: Video
  uid: 779f35dab7a89578d9a414da5148190b
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.451S05/11ocw-6.451_4-261-09mar2005-220k.mp4
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Video-Internet Archive-MP4
  type: Video
  uid: 24e95d44c5e8b544cb68ccd9fa8d164f
- id: Thumbnail-OCW-JPG
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 863d27d425aaeeae875bc2485b6eb1ec
- id: 3Play-3PlayYouTubeid-MP4
  media_location: mnkTn0Y6GsU
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 657cfc010970089c51608f93cfa1ffc4
- id: mnkTn0Y6GsU.srt
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-11-reed-solomon-codes/mnkTn0Y6GsU.srt
  title: 3play caption file
  type: null
  uid: 954a47e7f2e0505a7e7a2b5737e595e9
- id: mnkTn0Y6GsU.pdf
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-11-reed-solomon-codes/mnkTn0Y6GsU.pdf
  title: 3play pdf file
  type: null
  uid: 2717629c83d90e1d8a89c7949fd33e73
- id: Caption-3Play YouTube id-SRT
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f209212653c37f615f8b4ee58f944f18
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b0b90c8a2a42ab2a7c3bf7391f004c6d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b166648fb42505e6c9a70138a7141886
inline_embed_id: 74953105lecture11:reed-solomoncodes49790069
layout: video
order_index: null
parent_uid: 73f9a1c91575f1a3abda44e7358df3a2
related_resources_text: <p>Reed-Solomon Codes (<a title="Open in a new window." target="_blank"
  href="./resolveuid/01060b08ba74792ee8d85eb82b9efdb4">PDF</a>)</p>
short_url: lecture-11-reed-solomon-codes
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-11-reed-solomon-codes
template_type: Tabbed
title: 'Lecture 11: Reed-Solomon Codes'
transcript: '<p><span m=''390''>PROFESSOR: So</span> <span m=''780''>OK,</span> <span
  m=''1030''>what</span> <span m=''1160''>did we</span> <span m=''1280''>do</span>
  <span m=''1460''>last</span> <span m=''1810''>time?</span> <span m=''2060''>Thanks</span>
  <span m=''2320''>for</span> <span m=''2420''>coming</span> <span m=''2680''>back</span>
  <span m=''2900''>by</span> <span m=''3020''>the</span> <span m=''3350''>way.</span>
  <span m=''5334''>So</span> <span m=''5830''>last time,</span> <span m=''6170''>we
  did</span> <span m=''8109''>MDS</span> <span m=''8620''>codes.</span> <span m=''15760''>MDS</span>
  <span m=''16309''>codes,</span> <span m=''16700''>and</span> <span m=''16820''>we</span>
  <span m=''16950''>looked</span> <span m=''17150''>at</span> <span m=''17270''>this.</span>
  <span m=''17600''>And</span> <span m=''18320''>we</span> <span m=''18990''>derived</span>
  <span m=''19320''>some</span> <span m=''19570''>generic</span> <span m=''19980''>properties</span>
  <span m=''20630''>of</span> <span m=''20740''>these</span> <span m=''20980''>things</span>
  <span m=''21390''>if they</span> <span m=''21460''>existed.</span> </p><p><span
  m=''22380''>And</span> <span m=''22640''>then</span> <span m=''23710''>eventually,</span>
  <span m=''27170''>we</span> <span m=''27310''>moved to</span> <span m=''27570''>Reed-Solomon</span>
  <span m=''27760''>codes.</span> <span m=''30730''>And</span> <span m=''30930''>so</span>
  <span m=''31130''>indeed,</span> <span m=''31480''>they</span> <span m=''31880''>exist.</span>
  <span m=''32759''>We</span> <span m=''32900''>talked</span> <span m=''33200''>a</span>
  <span m=''33240''>little</span> <span m=''33450''>bit</span> <span m=''33640''>about</span>
  <span m=''33900''>existence</span> <span m=''34450''>altogether,</span> <span m=''35070''>the</span>
  <span m=''35900''>main</span> <span m=''36170''>conjection,</span> <span m=''36800''>MDS</span>
  <span m=''37270''>codes,</span> <span m=''37640''>I</span> <span m=''37740''>just</span>
  <span m=''38030''>wrote it</span> <span m=''38350''>down.</span> <span m=''39425''>And</span>
  <span m=''39820''>like</span> <span m=''40060''>I</span> <span m=''40090''>said,</span>
  <span m=''40390''>you</span> <span m=''40490''>want</span> <span m=''40610''>to</span>
  <span m=''40660''>be</span> <span m=''40790''>rich</span> <span m=''41020''>and</span>
  <span m=''41120''>famous,</span> <span m=''41580''>solve</span> <span m=''41890''>this.</span>
  <span m=''43890''>There''s</span> <span m=''48230''>people</span> <span m=''48480''>doing</span>
  <span m=''48670''>geometry</span> <span m=''49210''>in</span> <span m=''49350''>math</span>
  <span m=''49650''>that</span> <span m=''49740''>would</span> <span m=''49910''>be</span>
  <span m=''50050''>deliriously</span> <span m=''50510''>happy</span> <span m=''50800''>if
  you</span> <span m=''51000''>solved</span> <span m=''51050''>it.</span> <span m=''52460''>So</span>
  <span m=''52790''>if for</span> <span m=''53050''>nothing</span> <span m=''53360''>else.</span>
  </p><p><span m=''54780''>So</span> <span m=''55060''>the</span> <span m=''55160''>last</span>
  <span m=''55510''>thing</span> <span m=''55870''>I</span> <span m=''55920''>wrote</span>
  <span m=''56250''>down</span> <span m=''56530''>last</span> <span m=''56900''>time</span>
  <span m=''57350''>was</span> <span m=''57500''>something</span> <span m=''58180''>about</span>
  <span m=''59240''>a</span> <span m=''59360''>matrix</span> <span m=''59920''>which</span>
  <span m=''60110''>somebody</span> <span m=''60480''>recognized</span> <span m=''61070''>as</span>
  <span m=''61220''>some</span> <span m=''61490''>Fourier</span> <span m=''61800''>transform</span>
  <span m=''62400''>matrix.</span> <span m=''62890''>And</span> <span m=''63040''>that''s</span>
  <span m=''63870''>where</span> <span m=''63970''>I</span> <span m=''64040''>want</span>
  <span m=''64220''>to</span> <span m=''64269''>pick</span> <span m=''64500''>up</span>
  <span m=''64690''>here,</span> <span m=''65770''>at least</span> <span m=''66110''>quickly</span>
  <span m=''66530''>make</span> <span m=''66780''>that</span> <span m=''66970''>connection.</span>
  <span m=''68460''>So</span> <span m=''68660''>let</span> <span m=''68850''>me</span>
  <span m=''70700''>rewrite</span> <span m=''71350''>the</span> <span m=''71410''>definition</span>
  <span m=''71930''>of</span> <span m=''72030''>Reed-Solomon</span> <span m=''72500''>codes</span>
  <span m=''72810''>again.</span> <span m=''74330''>And</span> <span m=''76110''>so</span>
  <span m=''76520''>a</span> <span m=''76760''>Reed-Solomon</span> <span m=''77120''>code,</span>
  <span m=''78720''>the</span> <span m=''78800''>way</span> <span m=''78980''>we</span>
  <span m=''79060''>defined</span> <span m=''79430''>it</span> <span m=''79530''>last</span>
  <span m=''79870''>time</span> <span m=''80170''>was</span> <span m=''80590''>all</span>
  <span m=''80750''>field</span> <span m=''81170''>elements,</span> <span m=''81425''>we
  would</span> <span m=''81680''>evaluate</span> <span m=''82400''>the polynomial</span>
  <span m=''83240''>in all</span> <span m=''83570''>field</span> <span m=''83760''>elements.</span>
  <span m=''84880''>Now</span> <span m=''85120''>we</span> <span m=''85200''>do</span>
  <span m=''85330''>it</span> <span m=''85430''>slightly</span> <span m=''85800''>different.</span>
  </p><p><span m=''89980''>Let me</span> <span m=''90110''>make</span> <span m=''90310''>it</span>
  <span m=''91300''>Solomon-Stein</span> <span m=''92260''>in</span> <span m=''92500''>order</span>
  <span m=''92640''>to</span> <span m=''92760''>denote</span> <span m=''93330''>that</span>
  <span m=''94590''>difference.</span> <span m=''95320''>And</span> <span m=''95810''>let''s</span>
  <span m=''96100''>say</span> <span m=''96400''>this</span> <span m=''96670''>is</span>
  <span m=''98640''>beta</span> <span m=''99130''>0,</span> <span m=''105335''>beta</span>
  <span m=''105810''>n.</span> <span m=''119420''>So</span> <span m=''119600''>that''s</span>
  <span m=''119800''>the</span> <span m=''119900''>old</span> <span m=''120080''>definition.</span>
  <span m=''120730''>Only</span> <span m=''121710''>the,</span> <span m=''123820''>let''s
  say,</span> <span m=''124140''>the</span> <span m=''124395''>beta</span> <span m=''124650''>0,</span>
  <span m=''125180''>beta</span> <span m=''125270''>1,</span> <span m=''125660''>up</span>
  <span m=''125710''>to</span> <span m=''125990''>beta</span> <span m=''126270''>n,</span>
  <span m=''131310''>they</span> <span m=''131530''>are the</span> <span m=''131630''>non-zero</span>
  <span m=''132160''>elements</span> <span m=''132610''>now.</span> </p><p><span m=''133730''>And</span>
  <span m=''133900''>just</span> <span m=''134110''>for</span> <span m=''134200''>the</span>
  <span m=''134300''>heck</span> <span m=''134470''>of</span> <span m=''134620''>it,</span>
  <span m=''135990''>so</span> <span m=''136180''>we</span> <span m=''136270''>talked</span>
  <span m=''136510''>about</span> <span m=''136700''>punctured</span> <span m=''137390''>Reed-Solomon</span>
  <span m=''137860''>codes</span> <span m=''138150''>last</span> <span m=''138450''>time</span>
  <span m=''138780''>that</span> <span m=''138980''>it</span> <span m=''139160''>would</span>
  <span m=''139360''>still</span> <span m=''139600''>be</span> <span m=''139710''>MDS</span>
  <span m=''140160''>codes.</span> <span m=''140600''>So nothing</span> <span m=''140880''>has</span>
  <span m=''141160''>changed</span> <span m=''141510''>there.</span> <span m=''142185''>In
  particular,</span> <span m=''142560''>all</span> <span m=''142820''>the</span> <span
  m=''142950''>arguments</span> <span m=''143440''>would</span> <span m=''143590''>be</span>
  <span m=''143710''>the</span> <span m=''143810''>same.</span> <span m=''145510''>In</span>
  <span m=''145540''>particular,</span> <span m=''146010''>just to</span> <span m=''146350''>humor</span>
  <span m=''146580''>me,</span> <span m=''147810''>let''s</span> <span m=''148090''>say</span>
  <span m=''149360''>beta</span> <span m=''150030''>i</span> <span m=''151620''>is</span>
  <span m=''151790''>omega</span> <span m=''152170''>to</span> <span m=''152360''>the</span>
  <span m=''152550''>i,</span> <span m=''153890''>where</span> <span m=''155860''>omega</span>
  <span m=''156215''>is</span> <span m=''156470''>primitive</span> <span m=''160900''>in</span>
  <span m=''161100''>Fq.</span> <span m=''162920''>So</span> <span m=''163090''>what</span>
  <span m=''163250''>that</span> <span m=''163420''>means,</span> <span m=''163870''>you
  remember</span> <span m=''164290''>that</span> <span m=''165870''>primitive</span>
  <span m=''166090''>means</span> <span m=''166790''>that</span> <span m=''166970''>the</span>
  <span m=''167060''>powers</span> <span m=''167430''>of</span> <span m=''167560''>omega</span>
  <span m=''167870''>cycle</span> <span m=''168070''>through</span> <span m=''168270''>all</span>
  <span m=''168460''>the</span> <span m=''168810''>non-zero</span> <span m=''169020''>elements.</span>
  </p><p><span m=''171040''>Remember</span> <span m=''171470''>the</span> <span m=''172570''>non-zero</span>
  <span m=''173070''>elements</span> <span m=''173260''>are a</span> <span m=''173440''>multiplicative</span>
  <span m=''174440''>group.</span> <span m=''174760''>And</span> <span m=''174940''>it''s</span>
  <span m=''175100''>a</span> <span m=''175150''>cyclic</span> <span m=''175500''>group.</span>
  <span m=''175830''>And</span> <span m=''175950''>it''s the</span> <span m=''176040''>generator</span>
  <span m=''176310''>of the</span> <span m=''176580''>group.</span> <span m=''179970''>Good.</span>
  <span m=''186020''>So</span> <span m=''186450''>once</span> <span m=''186650''>we</span>
  <span m=''186830''>write</span> <span m=''187080''>it</span> <span m=''187170''>like</span>
  <span m=''187430''>this,</span> <span m=''189960''>we</span> <span m=''190060''>can</span>
  <span m=''190260''>actually</span> <span m=''198520''>write</span> <span m=''198780''>down</span>
  <span m=''199060''>the</span> <span m=''199180''>whole</span> <span m=''200295''>Reed-Solomon</span>
  <span m=''201100''>code</span> <span m=''201370''>in</span> <span m=''201470''>some</span>
  <span m=''201680''>sort</span> <span m=''201970''>of</span> <span m=''202830''>transfer</span>
  <span m=''203260''>domain</span> <span m=''203680''>description</span> <span m=''204050''>in
  the</span> <span m=''204420''>Fourier</span> <span m=''204710''>transform.</span>
  <span m=''205855''>And</span> <span m=''206220''>the</span> <span m=''206340''>way</span>
  <span m=''206520''>this</span> <span m=''206750''>goes</span> <span m=''207030''>is</span>
  <span m=''207160''>the</span> <span m=''207230''>following.</span> </p><p><span
  m=''208710''>So</span> <span m=''208900''>from</span> <span m=''209150''>now</span>
  <span m=''209380''>on,</span> <span m=''210340''>I</span> <span m=''210420''>will</span>
  <span m=''210600''>make</span> <span m=''212310''>implicit</span> <span m=''213990''>identification</span>
  <span m=''216000''>without</span> <span m=''217330''>making</span> <span m=''217660''>them.</span>
  <span m=''217950''>So</span> <span m=''218170''>this</span> <span m=''218380''>is</span>
  <span m=''218530''>an</span> <span m=''218680''>identification</span> <span m=''219430''>which</span>
  <span m=''219610''>I</span> <span m=''219680''>just</span> <span m=''219950''>jump</span>
  <span m=''220190''>around</span> <span m=''220490''>between.</span> <span m=''221360''>A</span>
  <span m=''221450''>vector --</span> <span m=''222790''>so</span> <span m=''222950''>this</span>
  <span m=''223160''>one</span> <span m=''223350''>would</span> <span m=''223470''>be</span>
  <span m=''228310''>a</span> <span m=''228850''>Fqn.</span> <span m=''229280''>And</span>
  <span m=''229520''>Fx</span> <span m=''230860''>would</span> <span m=''231100''>be</span>
  <span m=''235535''>maybe</span> <span m=''235790''>0</span> <span m=''236140''>to</span>
  <span m=''236628''>MDS</span> <span m=''237116''>1.</span> <span m=''250370''>Let''s</span>
  <span m=''250540''>leave</span> <span m=''250700''>it</span> <span m=''250770''>at
  that.</span> <span m=''251310''>So</span> <span m=''251450''>I</span> <span m=''251570''>make</span>
  <span m=''251830''>this --</span> </p><p><span m=''252080''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''253820''>PROFESSOR: Yeah,</span> <span m=''254810''>let''s</span>
  <span m=''255030''>make</span> <span m=''255740''>this</span> <span m=''255950''>identification</span>
  <span m=''256850''>free.</span> <span m=''258430''>It''s</span> <span m=''258589''>just</span>
  <span m=''258839''>a</span> <span m=''258890''>vector</span> <span m=''259250''>of</span>
  <span m=''259399''>length</span> <span m=''259720''>n</span> <span m=''260430''>and</span>
  <span m=''260640''>a</span> <span m=''260800''>polynomial</span> <span m=''260860''>of
  length</span> <span m=''261260''>n.</span> <span m=''261570''>And</span> <span m=''261800''>so</span>
  <span m=''261920''>whenever</span> <span m=''262270''>I</span> <span m=''262390''>want</span>
  <span m=''262680''>this</span> <span m=''262800''>to</span> <span m=''262910''>have</span>
  <span m=''263480''>a</span> <span m=''263540''>low</span> <span m=''263750''>degree,</span>
  <span m=''264180''>the</span> <span m=''264240''>polynomial,</span> <span m=''265340''>then</span>
  <span m=''265500''>I just</span> <span m=''265790''>write</span> <span m=''266080''>that</span>
  <span m=''266180''>expression.</span> </p><p><span m=''269010''>So</span> <span
  m=''269190''>this</span> <span m=''269390''>identification</span> <span m=''270110''>we</span>
  <span m=''270190''>make</span> <span m=''270410''>freely</span> <span m=''270710''>now.</span>
  <span m=''272490''>And</span> <span m=''272730''>then</span> <span m=''273110''>how</span>
  <span m=''273260''>can</span> <span m=''273430''>we</span> <span m=''273550''>write</span>
  <span m=''275370''>F?</span> <span m=''276620''>Let</span> <span m=''278540''>F</span>
  <span m=''279010''>now</span> <span m=''280450''>be</span> <span m=''280580''>code
  word</span> <span m=''287520''>in</span> <span m=''287750''>the</span> <span m=''287840''>Reed-Solomon</span>
  <span m=''288430''>code.</span> <span m=''288820''>And</span> <span m=''288960''>then</span>
  <span m=''289110''>I</span> <span m=''289150''>say</span> <span m=''289470''>Fi.</span>
  <span m=''290000''>What</span> <span m=''290170''>is</span> <span m=''290430''>Fi?</span>
  <span m=''291620''>The</span> <span m=''291870''>i is</span> <span m=''292230''>element.</span>
  </p><p><span m=''294390''>Well,</span> <span m=''297170''>we</span> <span m=''297350''>know</span>
  <span m=''297690''>that</span> <span m=''297900''>this</span> <span m=''298130''>is</span>
  <span m=''299960''>F</span> <span m=''300270''>of</span> <span m=''300430''>omega</span>
  <span m=''301200''>to</span> <span m=''301280''>the</span> <span m=''301460''>i.</span>
  <span m=''303400''>So</span> <span m=''303990''>this</span> <span m=''304200''>is,</span>
  <span m=''304390''>at</span> <span m=''304750''>the</span> <span m=''304910''>moment,</span>
  <span m=''305250''>counted</span> <span m=''305580''>from</span> <span m=''305820''>0.</span>
  <span m=''307200''>So</span> <span m=''307510''>this</span> <span m=''307770''>is
  --</span> <span m=''309100''>you</span> <span m=''309890''>write</span> <span m=''310150''>it</span>
  <span m=''310300''>out --</span> <span m=''316820''>Fj</span> <span m=''320190''>omega</span>
  <span m=''320810''>to</span> <span m=''321020''>the</span> <span m=''321270''>i</span>
  <span m=''322902''>to the</span> <span m=''323380''>j,</span> <span m=''323700''>which</span>
  <span m=''323950''>is</span> <span m=''329710''>omega</span> <span m=''330000''>i</span>
  <span m=''330400''>j.</span> </p><p><span m=''332340''>And now,</span> <span m=''332650''>at</span>
  <span m=''332740''>this</span> <span m=''332950''>point</span> <span m=''333170''>in</span>
  <span m=''333240''>time,</span> <span m=''333530''>everybody</span> <span m=''333950''>recognizes</span>
  <span m=''334355''>this.</span> <span m=''338000''>This</span> <span m=''338280''>would</span>
  <span m=''338440''>be</span> <span m=''338610''>the</span> <span m=''338720''>discrete</span>
  <span m=''339150''>Fourier</span> <span m=''339420''>transform</span> <span m=''339970''>of
  a</span> <span m=''340120''>vector.</span> <span m=''341670''>This</span> <span
  m=''341890''>is</span> <span m=''343010''>an</span> <span m=''343150''>element</span>
  <span m=''343640''>of</span> <span m=''343800''>order</span> <span m=''344150''>n.</span>
  <span m=''345940''>Usually,</span> <span m=''346290''>there''s</span> <span m=''346450''>e</span>
  <span m=''346670''>to</span> <span m=''346800''>the</span> <span m=''346960''>j</span>
  <span m=''347320''>and</span> <span m=''347510''>then</span> <span m=''347710''>an</span>
  <span m=''347840''>element</span> <span m=''348150''>of</span> <span m=''348270''>order</span>
  <span m=''348470''>n.</span> <span m=''348970''>Now</span> <span m=''349290''>it''s
  in the</span> <span m=''349360''>finite</span> <span m=''349710''>field.</span>
  </p><p><span m=''350240''>But</span> <span m=''350530''>what''s</span> <span m=''350640''>the</span>
  <span m=''350750''>difference?</span> <span m=''353100''>This</span> <span m=''353330''>would</span>
  <span m=''353480''>be</span> <span m=''353640''>the</span> <span m=''353740''>Fourier</span>
  <span m=''354040''>transform.</span> <span m=''355180''>So</span> <span m=''355440''>a</span>
  <span m=''355640''>code</span> <span m=''355990''>word</span> <span m=''356270''>would
  be</span> <span m=''356660''>the</span> <span m=''356730''>Fourier</span> <span
  m=''357070''>transform</span> <span m=''357710''>of</span> <span m=''357810''>a</span>
  <span m=''357920''>vector</span> <span m=''358450''>F.</span> <span m=''360350''>Let''s</span>
  <span m=''360740''>just</span> <span m=''361100''>make</span> <span m=''361320''>sure</span>
  <span m=''361690''>it</span> <span m=''361780''>also</span> <span m=''362070''>goes</span>
  <span m=''362370''>the</span> <span m=''362500''>other</span> <span m=''362680''>direction.</span>
  </p><p><span m=''363350''>So</span> <span m=''363530''>I</span> <span m=''363630''>claim</span>
  <span m=''365020''>that</span> <span m=''367090''>Fl</span> <span m=''370650''>would</span>
  <span m=''370910''>be --</span> <span m=''371350''>so</span> <span m=''371500''>what</span>
  <span m=''371860''>would be</span> <span m=''372020''>the</span> <span m=''372100''>Fourier</span>
  <span m=''372410''>transform</span> <span m=''373520''>if</span> <span m=''373710''>it,</span>
  <span m=''373910''>indeed,</span> <span m=''374280''>is</span> <span m=''374520''>the</span>
  <span m=''374680''>Fourier</span> <span m=''374850''>transform?</span> <span m=''376630''>It</span>
  <span m=''377910''>is</span> <span m=''378120''>a</span> <span m=''378180''>minus,</span>
  <span m=''380020''>and</span> <span m=''380230''>then it</span> <span m=''380470''>goes</span>
  <span m=''382812''>n</span> <span m=''383240''>minus</span> <span m=''383670''>1</span>
  <span m=''385680''>Fj</span> <span m=''388040''>omega</span> <span m=''388660''>minus</span>
  <span m=''390630''>jl.</span> <span m=''391450''>So</span> <span m=''391660''>the</span>
  <span m=''391750''>question</span> <span m=''392190''>is</span> <span m=''392370''>is
  that</span> <span m=''392600''>true?</span> <span m=''394560''>Because</span> <span
  m=''394820''>that</span> <span m=''395010''>would</span> <span m=''395170''>be</span>
  <span m=''395570''>the</span> <span m=''395720''>inverse.</span> <span m=''397400''>Is</span>
  <span m=''397590''>that</span> <span m=''397830''>true?</span> <span m=''398978''>Well,</span>
  <span m=''399436''>let''s</span> <span m=''401270''>do</span> <span m=''401400''>what</span>
  <span m=''401600''>we</span> <span m=''401710''>do</span> <span m=''402060''>with</span>
  <span m=''402570''>proofs</span> <span m=''403150''>of</span> <span m=''403210''>this</span>
  <span m=''403450''>type.</span> <span m=''406860''>I</span> <span m=''407010''>need</span>
  <span m=''407150''>that</span> <span m=''407230''>space</span> <span m=''407580''>here.</span>
  </p><p><span m=''407860''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''408286''>PROFESSOR:
  Sorry?</span> </p><p><span m=''408712''>AUDIENCE: [INAUDIBLE].</span> </p><p><span
  m=''409990''>PROFESSOR: Yeah.</span> <span m=''410420''>So</span> <span m=''410630''>let''s</span>
  <span m=''410860''>do</span> <span m=''411080''>what we</span> <span m=''411160''>do</span>
  <span m=''411270''>with</span> <span m=''411450''>proofs</span> <span m=''411820''>of</span>
  <span m=''412010''>this</span> <span m=''412210''>type.</span> <span m=''412540''>That</span>
  <span m=''412740''>means</span> <span m=''414200''>we</span> <span m=''414480''>write</span>
  <span m=''414800''>it</span> <span m=''414930''>out.</span> <span m=''416970''>That''s</span>
  <span m=''417210''>another</span> <span m=''417490''>beautiful</span> <span m=''417970''>thing</span>
  <span m=''418200''>about</span> <span m=''418450''>finite</span> <span m=''418810''>fields.</span>
  <span m=''419170''>You</span> <span m=''419270''>never</span> <span m=''419590''>have
  to</span> <span m=''419870''>worry about</span> <span m=''420150''>convergence.</span>
  <span m=''422790''>So</span> <span m=''423866''>for</span> <span m=''424242''>the</span>
  <span m=''424620''>F,</span> <span m=''424970''>we</span> <span m=''425060''>just</span>
  <span m=''425330''>plug</span> <span m=''425600''>that</span> <span m=''425750''>in</span>
  <span m=''425950''>here.</span> <span m=''427310''>Sum,</span> <span m=''429260''>this</span>
  <span m=''429450''>would</span> <span m=''429660''>be --</span> <span m=''430310''>what</span>
  <span m=''430595''>do</span> <span m=''430880''>we</span> <span m=''431030''>call</span>
  <span m=''431350''>it --</span> <span m=''445970''>Fi</span> <span m=''449548''>omega</span>
  <span m=''450456''>to</span> <span m=''450910''>the</span> <span m=''451240''>ij.</span>
  <span m=''453920''>So</span> <span m=''456030''>this</span> <span m=''456280''>would</span>
  <span m=''456440''>be</span> <span m=''456600''>Fj.</span> <span m=''458860''>And</span>
  <span m=''459100''>then</span> <span m=''459350''>I</span> <span m=''459540''>want</span>
  <span m=''459930''>omega</span> <span m=''460140''>minus</span> <span m=''460330''>jl.</span>
  <span m=''462600''>So</span> <span m=''462830''>is</span> <span m=''463010''>that</span>
  <span m=''463220''>true?</span> <span m=''463535''>Is</span> <span m=''463850''>the</span>
  <span m=''464120''>identity</span> <span m=''464740''>now</span> <span m=''465020''>true?</span>
  <span m=''465930''>Well,</span> <span m=''466220''>we see</span> <span m=''466600''>two</span>
  <span m=''466750''>sums.</span> <span m=''467420''>What</span> <span m=''467580''>do</span>
  <span m=''467710''>we</span> <span m=''467890''>do with two</span> <span m=''468020''>sums?</span>
  <span m=''470200''>If we''re</span> <span m=''470410''>compelled</span> <span m=''470830''>to</span>
  <span m=''470910''>exchange</span> <span m=''471190''>the</span> <span m=''471470''>order,</span>
  <span m=''471730''>that''s</span> <span m=''472000''>always</span> <span m=''472210''>what</span>
  <span m=''472760''>we</span> <span m=''472850''>do.</span> <span m=''475570''>So</span>
  <span m=''481490''>Fi</span> <span m=''481700''>goes out.</span> <span m=''482150''>And</span>
  <span m=''482280''>then</span> <span m=''483050''>you</span> <span m=''483170''>get</span>
  <span m=''487480''>omega</span> <span m=''488030''>to</span> <span m=''488600''>the
  --</span> <span m=''489900''>what</span> <span m=''490040''>do</span> <span m=''490190''>we</span>
  <span m=''490340''>do --</span> <span m=''492160''>i</span> <span m=''492490''>minus</span>
  <span m=''492980''>l</span> <span m=''494710''>times</span> <span m=''495100''>j.</span>
  </p><p><span m=''503100''>We</span> <span m=''503330''>have</span> <span m=''503600''>this.</span>
  <span m=''505970''>And</span> <span m=''506550''>so</span> <span m=''506650''>what</span>
  <span m=''506820''>is</span> <span m=''506980''>this?</span> <span m=''510480''>How
  can</span> <span m=''510600''>we</span> <span m=''510700''>work</span> <span m=''510950''>this</span>
  <span m=''511120''>out?</span> <span m=''513270''>Well,</span> <span m=''513679''>you</span>
  <span m=''513760''>know</span> <span m=''514039''>how</span> <span m=''514179''>to</span>
  <span m=''514330''>express</span> <span m=''514770''>the</span> <span m=''514860''>sum.</span>
  </p><p><span m=''515280''>So</span> <span m=''515450''>this</span> <span m=''515679''>part</span>
  <span m=''515929''>of</span> <span m=''516070''>the</span> <span m=''516159''>sum</span>
  <span m=''516539''>is</span> <span m=''516640''>really</span> <span m=''516900''>just</span>
  <span m=''518080''>omega</span> <span m=''518659''>i</span> <span m=''520010''>minus</span>
  <span m=''520490''>l</span> <span m=''522120''>to</span> <span m=''522280''>the</span>
  <span m=''523500''>n</span> <span m=''523809''>minus</span> <span m=''524220''>1</span>
  <span m=''527730''>minus</span> <span m=''528040''>1.</span> <span m=''529472''>Well,</span>
  <span m=''529920''>that''s a</span> <span m=''529980''>standard</span> <span m=''530510''>formula</span>
  <span m=''530860''>for</span> <span m=''531250''>summing</span> <span m=''531690''>these</span>
  <span m=''531860''>things</span> <span m=''532130''>up.</span> <span m=''532840''>But</span>
  <span m=''533070''>omega</span> <span m=''533290''>is</span> <span m=''533530''>an</span>
  <span m=''533600''>element</span> <span m=''533960''>of</span> <span m=''534070''>order</span>
  <span m=''534380''>n.</span> <span m=''537280''>Omega</span> <span m=''537620''>was</span>
  <span m=''537810''>an</span> <span m=''537890''>element</span> <span m=''538230''>of</span>
  <span m=''538330''>order</span> <span m=''538600''>n.</span> <span m=''538900''>That''s</span>
  <span m=''539060''>how</span> <span m=''539130''>we</span> <span m=''539270''>chose</span>
  <span m=''539610''>it.</span> </p><p><span m=''539870''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''540750''>PROFESSOR: It''s</span> <span m=''541190''>what?</span>
  </p><p><span m=''541595''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''544040''>PROFESSOR:
  You</span> <span m=''544170''>multiplied</span> <span m=''544680''>omega --</span>
  <span m=''546680''>it''s</span> <span m=''546940''>primitive</span> <span m=''547400''>in</span>
  <span m=''547490''>the</span> <span m=''547590''>field,</span> <span m=''548010''>so</span>
  <span m=''548240''>omega --</span> <span m=''549630''>we</span> <span m=''549800''>have</span>
  <span m=''550740''>omega</span> <span m=''551110''>da-da-da-da-da</span> <span m=''552260''>i</span>
  <span m=''553800''>unequal</span> <span m=''554300''>to</span> <span m=''554420''>1</span>
  <span m=''555960''>for</span> <span m=''556070''>all</span> <span m=''556780''>i</span>
  <span m=''557050''>less</span> <span m=''557430''>than</span> <span m=''557700''>n</span>
  <span m=''558870''>and</span> <span m=''559110''>omega</span> <span m=''559520''>n
  is</span> <span m=''559960''>equal</span> <span m=''560240''>to</span> <span m=''560370''>1.</span>
  <span m=''562300''>So</span> <span m=''562690''>OK.</span> <span m=''567640''>That''s</span>
  <span m=''568101''>fine.</span> </p><p><span m=''568570''>So</span> <span m=''568920''>it''s</span>
  <span m=''569060''>an</span> <span m=''569230''>element</span> <span m=''569340''>of
  order</span> <span m=''569420''>n.</span> <span m=''569910''>That</span> <span m=''570060''>means</span>
  <span m=''570330''>the</span> <span m=''570630''>n-th</span> <span m=''570870''>power.</span>
  <span m=''571360''>We</span> <span m=''571430''>can</span> <span m=''571790''>interchange</span>
  <span m=''572090''>this.</span> <span m=''575080''>So</span> <span m=''575250''>this</span>
  <span m=''575430''>is</span> <span m=''575570''>1</span> <span m=''576330''>to</span>
  <span m=''576500''>the</span> <span m=''576830''>some</span> <span m=''577220''>power</span>
  <span m=''578370''>remains</span> <span m=''578720''>1.</span> <span m=''579070''>So</span>
  <span m=''579230''>1</span> <span m=''579410''>minus</span> <span m=''579660''>1
  is</span> <span m=''579890''>0.</span> </p><p><span m=''580790''>The</span> <span
  m=''580900''>denominator --</span> <span m=''581620''>well,</span> <span m=''582355''>actually,</span>
  <span m=''582730''>we</span> <span m=''582950''>get</span> <span m=''583160''>two</span>
  <span m=''583280''>results</span> <span m=''583450''>here.</span> <span m=''584140''>If</span>
  <span m=''586270''>i</span> <span m=''586550''>is</span> <span m=''586660''>unequal</span>
  <span m=''587240''>to</span> <span m=''587420''>l,</span> <span m=''589950''>then</span>
  <span m=''590910''>this</span> <span m=''591100''>is</span> <span m=''591230''>0.</span>
  <span m=''596720''>If</span> <span m=''596920''>i is</span> <span m=''597050''>equal
  to</span> <span m=''597390''>l,</span> <span m=''597675''>then this</span> <span
  m=''597960''>was</span> <span m=''598170''>just</span> <span m=''599140''>the</span>
  <span m=''599280''>sum</span> <span m=''599640''>of</span> <span m=''599940''>n</span>
  <span m=''600270''>once.</span> <span m=''602590''>So</span> <span m=''602720''>we</span>
  <span m=''602840''>get</span> <span m=''603110''>n</span> <span m=''603450''>here.</span>
  <span m=''605240''>i</span> <span m=''605430''>equal</span> <span m=''605600''>to</span>
  <span m=''605700''>0.</span> </p><p><span m=''605970''>But</span> <span m=''606180''>n</span>
  <span m=''606520''>was</span> <span m=''608150''>q</span> <span m=''608380''>minus</span>
  <span m=''608840''>1,</span> <span m=''612440''>the</span> <span m=''612760''>number</span>
  <span m=''613020''>of</span> <span m=''613130''>non-zero</span> <span m=''613590''>field</span>
  <span m=''613790''>elements</span> <span m=''614440''>because</span> <span m=''614715''>it
  was</span> <span m=''614990''>primitive</span> <span m=''615430''>in</span> <span
  m=''615540''>the</span> <span m=''615620''>field.</span> <span m=''617050''>And</span>
  <span m=''617180''>this</span> <span m=''617370''>one</span> <span m=''621460''>is</span>
  <span m=''621620''>just</span> <span m=''621830''>minus</span> <span m=''622160''>1</span>
  <span m=''623380''>in</span> <span m=''623580''>the</span> <span m=''623670''>field.</span>
  <span m=''623990''>Because</span> <span m=''624300''>q,</span> <span m=''625190''>we</span>
  <span m=''625330''>compute</span> <span m=''626350''>q</span> <span m=''626550''>is
  the</span> <span m=''626660''>power</span> <span m=''627420''>of</span> <span m=''627695''>the</span>
  <span m=''627970''>prime</span> <span m=''628440''>of</span> <span m=''628877''>p.</span>
  <span m=''630190''>So</span> <span m=''630320''>that</span> <span m=''630530''>would
  be</span> <span m=''630740''>0.</span> <span m=''631220''>If</span> <span m=''631350''>we</span>
  <span m=''631420''>just</span> <span m=''631670''>come</span> <span m=''631880''>out</span>
  <span m=''631970''>as</span> <span m=''632090''>minus</span> <span m=''632390''>1,</span>
  <span m=''633070''>that</span> <span m=''633220''>explains</span> <span m=''633650''>this</span>
  <span m=''634070''>minus</span> <span m=''634470''>here.</span> </p><p><span m=''634650''>And</span>
  <span m=''634900''>we</span> <span m=''634990''>can</span> <span m=''635190''>get</span>
  <span m=''635360''>rid</span> <span m=''635530''>of</span> <span m=''635680''>the</span>
  <span m=''636120''>question</span> <span m=''636560''>mark.</span> <span m=''639810''>Look</span>
  <span m=''639960''>correct?</span> <span m=''642180''>All</span> <span m=''642360''>right.</span>
  <span m=''642550''>According</span> <span m=''642880''>to</span> <span m=''643000''>popular</span>
  <span m=''643350''>vote,</span> <span m=''643570''>it</span> <span m=''643660''>is.</span>
  </p><p><span m=''647470''>So</span> <span m=''647600''>what</span> <span m=''647740''>do</span>
  <span m=''647970''>we</span> <span m=''648210''>really have</span> <span m=''648480''>here?</span>
  <span m=''648740''>We</span> <span m=''648830''>have</span> <span m=''649340''>everything</span>
  <span m=''649710''>we</span> <span m=''649840''>want</span> <span m=''650100''>from
  a</span> <span m=''650480''>Fourier</span> <span m=''650530''>transform.</span>
  <span m=''651340''>We</span> <span m=''651470''>have</span> <span m=''652406''>a</span>
  <span m=''652782''>Fourier</span> <span m=''653160''>transform</span> <span m=''653450''>pair.</span>
  <span m=''660130''>We</span> <span m=''660390''>have</span> <span m=''661860''>a</span>
  <span m=''662260''>vector</span> <span m=''662650''>f,</span> <span m=''663240''>which</span>
  <span m=''663430''>we</span> <span m=''663520''>can</span> <span m=''663720''>think</span>
  <span m=''663990''>of</span> <span m=''664160''>as</span> <span m=''664400''>being</span>
  <span m=''664690''>in the</span> <span m=''664780''>frequency</span> <span m=''665280''>domain.</span>
  <span m=''668800''>Then</span> <span m=''668980''>we</span> <span m=''669290''>have</span>
  <span m=''670438''>a vector</span> <span m=''671680''>F,</span> <span m=''674870''>which</span>
  <span m=''675230''>is</span> <span m=''675370''>a</span> <span m=''675420''>Fourier</span>
  <span m=''675700''>transform</span> <span m=''676170''>of</span> <span m=''676510''>that.</span>
  <span m=''677920''>This</span> <span m=''678230''>one</span> <span m=''682520''>would</span>
  <span m=''682680''>be</span> <span m=''682930''>in</span> <span m=''683090''>the</span>
  <span m=''683210''>code</span> <span m=''690240''>if</span> <span m=''690560''>the</span>
  <span m=''690670''>degree</span> <span m=''691060''>of</span> <span m=''691170''>this</span>
  <span m=''691390''>polynomial</span> <span m=''691805''>here</span> <span m=''692220''>would
  be</span> <span m=''692400''>less</span> <span m=''692570''>than</span> <span m=''692700''>k.</span>
  </p><p><span m=''696410''>So</span> <span m=''696600''>now</span> <span m=''696790''>how</span>
  <span m=''697030''>can we</span> <span m=''697260''>understand</span> <span m=''697780''>Reed-Solomon</span>
  <span m=''698130''>codes</span> <span m=''698470''>now</span> <span m=''698990''>from</span>
  <span m=''699180''>an</span> <span m=''699260''>engineering</span> <span m=''699800''>point</span>
  <span m=''700120''>of</span> <span m=''700240''>view?</span> <span m=''701010''>Classical
  --</span> <span m=''703150''>what</span> <span m=''703320''>about</span> <span m=''703680''>band-limited</span>
  <span m=''704480''>functions?</span> <span m=''705110''>What</span> <span m=''705260''>do
  we</span> <span m=''705390''>know</span> <span m=''705550''>about</span> <span m=''705810''>band-limited</span>
  <span m=''706360''>functions?</span> <span m=''707936''>Because</span> <span m=''708300''>in</span>
  <span m=''708400''>a</span> <span m=''708460''>sense,</span> <span m=''710300''>the</span>
  <span m=''710570''>degree</span> <span m=''710855''>less</span> <span m=''711140''>than</span>
  <span m=''711280''>k,</span> <span m=''712700''>this</span> <span m=''712940''>means</span>
  <span m=''713410''>that</span> <span m=''714442''>Fi</span> <span m=''715135''>is</span>
  <span m=''715430''>0</span> <span m=''716720''>for</span> <span m=''717150''>all</span>
  <span m=''717580''>i</span> <span m=''717980''>greater</span> <span m=''718300''>than</span>
  <span m=''718520''>k.</span> <span m=''721320''>That''s</span> <span m=''721470''>what</span>
  <span m=''721640''>it</span> <span m=''721700''>means.</span> </p><p><span m=''722820''>So</span>
  <span m=''723880''>in</span> <span m=''723990''>a</span> <span m=''724040''>sense,</span>
  <span m=''724320''>it''s</span> <span m=''724450''>nothing</span> <span m=''724730''>but</span>
  <span m=''724860''>a</span> <span m=''725125''>band-limited</span> <span m=''725510''>function</span>
  <span m=''725960''>if</span> <span m=''726070''>this</span> <span m=''726300''>is</span>
  <span m=''726410''>a</span> <span m=''726490''>frequency</span> <span m=''726940''>domain,</span>
  <span m=''727400''>if</span> <span m=''727860''>you</span> <span m=''728320''>consider</span>
  <span m=''728680''>this</span> <span m=''728820''>as a</span> <span m=''729060''>frequency</span>
  <span m=''729510''>domain.</span> <span m=''730320''>So</span> <span m=''730530''>what</span>
  <span m=''730720''>do</span> <span m=''730820''>we</span> <span m=''730920''>know</span>
  <span m=''731100''>about</span> <span m=''731330''>the</span> <span m=''731400''>band-limited</span>
  <span m=''731950''>function?</span> <span m=''734600''>Well,</span> <span m=''734860''>if</span>
  <span m=''736550''>a</span> <span m=''736630''>function</span> <span m=''736950''>is</span>
  <span m=''737060''>band</span> <span m=''737410''>limited,</span> <span m=''738590''>it</span>
  <span m=''738730''>cannot</span> <span m=''739030''>be</span> <span m=''739140''>impulsive.</span>
  <span m=''740780''>We</span> <span m=''740880''>know</span> <span m=''741070''>that.</span>
  <span m=''742000''>It''s a</span> <span m=''742270''>part</span> <span m=''742840''>of</span>
  <span m=''742990''>the</span> <span m=''743640''>frequency,</span> <span m=''744230''>and</span>
  <span m=''744300''>the</span> <span m=''744370''>frequency</span> <span m=''744810''>domain</span>
  <span m=''745400''>is</span> <span m=''745940''>inversely</span> <span m=''746400''>relational</span>
  <span m=''748460''>to</span> <span m=''748680''>the</span> <span m=''748730''>support</span>
  <span m=''749100''>of</span> <span m=''749310''>the</span> <span m=''750190''>function.</span>
  </p><p><span m=''750520''>So</span> <span m=''750980''>the</span> <span m=''751120''>whole</span>
  <span m=''751280''>idea</span> <span m=''751610''>of</span> <span m=''751780''>Reed-Solomon</span>
  <span m=''752280''>codes,</span> <span m=''752520''>in</span> <span m=''752610''>a</span>
  <span m=''752660''>sense,</span> <span m=''753830''>can</span> <span m=''754040''>actually</span>
  <span m=''754420''>be</span> <span m=''754560''>understood,</span> <span m=''755140''>at</span>
  <span m=''755250''>least</span> <span m=''755540''>intuitively,</span> <span m=''756210''>from</span>
  <span m=''756410''>Fourier</span> <span m=''756650''>transform</span> <span m=''757180''>and</span>
  <span m=''757380''>the</span> <span m=''757480''>duality</span> <span m=''757960''>between</span>
  <span m=''758460''>time</span> <span m=''758720''>and</span> <span m=''759020''>frequency.</span>
  <span m=''760162''>Yeah.</span> </p><p><span m=''761094''>AUDIENCE: Was q</span>
  <span m=''761560''>a prime</span> <span m=''762026''>number?</span> </p><p><span
  m=''763430''>PROFESSOR: q</span> <span m=''763610''>is</span> <span m=''763720''>not</span>
  <span m=''763940''>prime.</span> <span m=''764250''>q is a</span> <span m=''764480''>power</span>
  <span m=''764950''>of a prime.</span> <span m=''767722''>q to</span> <span m=''768184''>the
  n.</span> </p><p><span m=''769000''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''772930''>PROFESSOR:
  There</span> <span m=''773120''>always</span> <span m=''773430''>is.</span> <span
  m=''774840''>Oh,</span> <span m=''775140''>sorry.</span> </p><p><span m=''775400''>AUDIENCE:
  [INAUDIBLE]</span> <span m=''776350''>or because</span> <span m=''777300''>for any</span>
  <span m=''777775''>q,</span> <span m=''778250''>there would be</span> <span m=''778725''>always
  a primitive?</span> </p><p><span m=''779820''>PROFESSOR: Why</span> <span m=''780050''>there''s</span>
  <span m=''780580''>always</span> <span m=''780940''>a</span> <span m=''781040''>primitive</span>
  <span m=''781450''>element</span> <span m=''782740''>in</span> <span m=''782860''>the</span>
  <span m=''782950''>field --</span> <span m=''786350''>yeah,</span> <span m=''786730''>sorry.</span>
  <span m=''787360''>I thought</span> <span m=''787730''>you had</span> <span m=''788190''>gone</span>
  <span m=''788350''>through</span> <span m=''788600''>that.</span> <span m=''791710''>It''s</span>
  <span m=''791940''>because</span> <span m=''793050''>the</span> <span m=''793520''>non-zero</span>
  <span m=''794070''>elements</span> <span m=''794510''>in</span> <span m=''794640''>a</span>
  <span m=''794700''>field</span> <span m=''795000''>always</span> <span m=''795370''>make
  up</span> <span m=''795730''>a multiplicative</span> <span m=''796462''>group.</span>
  <span m=''798110''>And</span> <span m=''798290''>it''s</span> <span m=''798480''>always
  a</span> <span m=''798950''>cyclic</span> <span m=''799300''>multiplicative</span>
  <span m=''799990''>group.</span> <span m=''801640''>So it''s</span> <span m=''801950''>a</span>
  <span m=''802030''>cyclic</span> <span m=''802350''>multiplicative</span> <span
  m=''803060''>group.</span> <span m=''805690''>And</span> <span m=''806000''>it''s</span>
  <span m=''806420''>just</span> <span m=''806640''>the</span> <span m=''806700''>generator</span>
  <span m=''807160''>of</span> <span m=''807310''>that</span> <span m=''807460''>group.</span>
  </p><p><span m=''808932''>AUDIENCE: [INAUDIBLE]</span> <span m=''809373''>it was</span>
  <span m=''809814''>a --</span> </p><p><span m=''810700''>PROFESSOR: It''s</span>
  <span m=''811095''>the same</span> <span m=''811490''>statement</span> <span m=''811860''>as</span>
  <span m=''811930''>saying,</span> <span m=''812280''>a</span> <span m=''812340''>cyclic</span>
  <span m=''812800''>group</span> <span m=''813120''>has a</span> <span m=''813300''>generator.</span>
  </p><p><span m=''818394''>AUDIENCE: If</span> <span m=''818848''>Fq,</span> <span
  m=''819302''>for example,</span> <span m=''820210''>was a</span> <span m=''820680''>z,</span>
  <span m=''822032''>zq,</span> <span m=''823024''>then</span> <span m=''823520''>q</span>
  <span m=''824020''>has to be</span> <span m=''824240''>prime.</span> </p><p><span
  m=''826680''>PROFESSOR: Yeah.</span> <span m=''827290''>Yeah,</span> <span m=''827740''>in
  order for</span> <span m=''827990''>it to</span> <span m=''828070''>be</span> <span
  m=''828230''>a field,</span> <span m=''828610''>q has to be</span> <span m=''829000''>prime.</span>
  <span m=''829480''>Right.</span> <span m=''829905''>That''s</span> <span m=''830330''>true.</span>
  <span m=''831180''>That''s</span> <span m=''831605''>true.</span> <span m=''832030''>But</span>
  <span m=''832800''>we are</span> <span m=''833010''>not</span> <span m=''833030''>worried</span>
  <span m=''833310''>about --</span> <span m=''835490''>There''s</span> <span m=''835820''>also
  a</span> <span m=''836160''>beautiful</span> <span m=''836600''>theory</span> <span
  m=''837040''>[UNINTELLIGIBLE PHRASE]</span> <span m=''838150''>rings</span> <span
  m=''839240''>if</span> <span m=''839360''>this</span> <span m=''839550''>would</span>
  <span m=''839690''>not</span> <span m=''839910''>be</span> <span m=''840020''>a</span>
  <span m=''840090''>prime,</span> <span m=''840845''>very</span> <span m=''841190''>nice</span>
  <span m=''841510''>theory,</span> <span m=''841950''>becomes</span> <span m=''842280''>a
  little bit more</span> <span m=''842760''>technical.</span> <span m=''843775''>You
  see,</span> <span m=''844140''>more</span> <span m=''844310''>technical,</span>
  <span m=''845030''>then</span> <span m=''845340''>more</span> <span m=''845560''>difficult.</span>
  </p><p><span m=''849960''>I</span> <span m=''850080''>just</span> <span m=''850300''>wanted</span>
  <span m=''850550''>to</span> <span m=''851530''>give</span> <span m=''851740''>you</span>
  <span m=''851850''>this</span> <span m=''852080''>correspondence</span> <span m=''852760''>on</span>
  <span m=''852850''>the</span> <span m=''852940''>Fourier</span> <span m=''853210''>transform</span>
  <span m=''853770''>because</span> <span m=''854110''>it''s,</span> <span m=''854790''>from</span>
  <span m=''855010''>an</span> <span m=''855100''>engineering</span> <span m=''855590''>point</span>
  <span m=''855870''>of</span> <span m=''855960''>view,</span> <span m=''856170''>a</span>
  <span m=''856230''>very</span> <span m=''856430''>nice</span> <span m=''856700''>insight.</span>
  <span m=''859200''>One</span> <span m=''859370''>of</span> <span m=''859470''>the</span>
  <span m=''859580''>reasons</span> <span m=''860030''>one</span> <span m=''860200''>can</span>
  <span m=''860320''>understand</span> <span m=''860630''>that</span> <span m=''860980''>Reed-Solomon</span>
  <span m=''861510''>codes</span> <span m=''861760''>have a</span> <span m=''861890''>good</span>
  <span m=''862170''>minimum</span> <span m=''862490''>distance</span> <span m=''863430''>is</span>
  <span m=''863580''>because</span> <span m=''863970''>it has</span> <span m=''864090''>a</span>
  <span m=''864220''>transform</span> <span m=''864690''>of a</span> <span m=''864995''>band-limited</span>
  <span m=''865300''>function.</span> <span m=''869890''>So</span> <span m=''870040''>that''s</span>
  <span m=''870240''>what</span> <span m=''870370''>I</span> <span m=''870420''>wanted</span>
  <span m=''870670''>to</span> <span m=''870750''>say</span> <span m=''870900''>about</span>
  <span m=''871090''>the</span> <span m=''871170''>Fourier</span> <span m=''871640''>transforms</span>
  <span m=''871910''>here.</span> <span m=''873240''>I do not</span> <span m=''873340''>want
  to</span> <span m=''873770''>spend</span> <span m=''874040''>too</span> <span m=''874150''>much</span>
  <span m=''874390''>time.</span> <span m=''874820''>I have to</span> <span m=''874910''>get</span>
  <span m=''875180''>through</span> <span m=''875420''>decoding</span> <span m=''875750''>here.</span>
  </p><p><span m=''880280''>Since</span> <span m=''880560''>we</span> <span m=''880660''>have</span>
  <span m=''881000''>now</span> <span m=''881110''>this</span> <span m=''881280''>Fourier</span>
  <span m=''881480''>transform</span> <span m=''882020''>correspondence,</span> <span
  m=''882740''>we</span> <span m=''882820''>can</span> <span m=''883000''>do</span>
  <span m=''883110''>another</span> <span m=''883430''>thing.</span> <span m=''883740''>We</span>
  <span m=''883850''>can,</span> <span m=''884170''>namely,</span> <span m=''884260''>say,</span>
  <span m=''885090''>well,</span> <span m=''886710''>F</span> <span m=''888200''>is</span>
  <span m=''888620''>in</span> <span m=''888860''>the</span> <span m=''888990''>code</span>
  <span m=''891980''>if</span> <span m=''892230''>and</span> <span m=''892420''>only</span>
  <span m=''892870''>if</span> <span m=''900720''>the</span> <span m=''900910''>Fourier</span>
  <span m=''901210''>transform --</span> <span m=''902420''>so</span> <span m=''902590''>that</span>
  <span m=''902960''>was</span> <span m=''904390''>the</span> <span m=''904460''>back</span>
  <span m=''904690''>transform</span> <span m=''905290''>here.</span> <span m=''909340''>Also</span>
  <span m=''909590''>now,</span> <span m=''909770''>the</span> <span m=''909900''>code
  word,</span> <span m=''910370''>we</span> <span m=''910450''>can</span> <span m=''910630''>interpret</span>
  <span m=''910710''>the</span> <span m=''910820''>code</span> <span m=''911075''>word</span>
  <span m=''911330''>as</span> <span m=''911480''>a polynomial.</span> <span m=''912180''>And
  the</span> <span m=''912490''>inverse</span> <span m=''912780''>transform</span>
  <span m=''913040''>is</span> <span m=''913300''>just</span> <span m=''914790''>evaluating</span>
  <span m=''915460''>it</span> <span m=''917540''>at</span> <span m=''917680''>an</span>
  <span m=''917770''>omega</span> <span m=''918160''>again.</span> <span m=''919980''>F
  is in</span> <span m=''920430''>the</span> <span m=''920530''>code</span> <span
  m=''920790''>if</span> <span m=''920900''>and</span> <span m=''921070''>only</span>
  <span m=''921410''>the</span> <span m=''922670''>transform</span> <span m=''923870''>of</span>
  <span m=''924170''>a</span> <span m=''924270''>code</span> <span m=''924500''>word</span>
  <span m=''926010''>is</span> <span m=''926210''>0</span> <span m=''928140''>for</span>
  <span m=''928530''>all</span> <span m=''930590''>i</span> <span m=''930710''>greater</span>
  <span m=''931070''>than</span> <span m=''931260''>k</span> <span m=''932801''>up
  to n</span> <span m=''933210''>minus</span> <span m=''933530''>1.</span> <span m=''934385''>Yeah.</span>
  </p><p><span m=''934850''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''938790''>PROFESSOR:
  So</span> <span m=''940150''>it</span> <span m=''940240''>basically</span> <span
  m=''940640''>just</span> <span m=''940850''>means</span> <span m=''941000''>the</span>
  <span m=''941090''>support.</span> <span m=''946400''>If</span> <span m=''946600''>this</span>
  <span m=''946820''>one</span> <span m=''947250''>is</span> <span m=''947410''>band</span>
  <span m=''947640''>limited,</span> <span m=''948520''>then</span> <span m=''948670''>this</span>
  <span m=''949000''>one</span> <span m=''949210''>cannot</span> <span m=''949300''>have</span>
  <span m=''949650''>arbitrarily</span> <span m=''949990''>small</span> <span m=''950270''>support.</span>
  <span m=''951610''>That''s</span> <span m=''951800''>what it</span> <span m=''952272''>means.</span>
  <span m=''955110''>That''s</span> <span m=''955310''>really</span> <span m=''955520''>all</span>
  <span m=''955670''>I</span> <span m=''955710''>wanted</span> <span m=''955990''>to</span>
  <span m=''956090''>say.</span> </p><p><span m=''962510''>i</span> <span m=''962650''>greater</span>
  <span m=''962980''>than</span> <span m=''963290''>k</span> <span m=''963590''>and</span>
  <span m=''967025''>less</span> <span m=''967502''>than</span> <span m=''967980''>n.</span>
  <span m=''969620''>So</span> <span m=''971360''>we</span> <span m=''971440''>have</span>
  <span m=''971660''>that</span> <span m=''971840''>F</span> <span m=''973170''>is</span>
  <span m=''973440''>in</span> <span m=''973770''>the</span> <span m=''974050''>code</span>
  <span m=''974410''>if</span> <span m=''974540''>and</span> <span m=''974680''>only</span>
  <span m=''975370''>the</span> <span m=''975470''>polynomial</span> <span m=''975820''>evaluates</span>
  <span m=''976630''>to</span> <span m=''976770''>0</span> <span m=''977160''>at</span>
  <span m=''978016''>a</span> <span m=''978452''>bunch</span> <span m=''978890''>of</span>
  <span m=''979030''>points.</span> <span m=''980700''>Now</span> <span m=''980810''>that</span>
  <span m=''981170''>leads to</span> <span m=''981580''>something</span> <span m=''981950''>interesting.</span>
  <span m=''983060''>Because</span> <span m=''983380''>now</span> <span m=''983630''>we</span>
  <span m=''983740''>can</span> <span m=''983980''>say,</span> <span m=''985660''>well,</span>
  <span m=''987160''>so</span> <span m=''987420''>what</span> <span m=''987680''>if</span>
  <span m=''987910''>we''ve</span> <span m=''988260''>just</span> <span m=''988700''>construct</span>
  <span m=''989830''>our</span> <span m=''990490''>set</span> <span m=''990730''>of</span>
  <span m=''990870''>vectors</span> <span m=''991410''>F</span> <span m=''992980''>so</span>
  <span m=''993290''>that</span> <span m=''993720''>they</span> <span m=''993880''>evaluate</span>
  <span m=''994380''>to</span> <span m=''994480''>0</span> <span m=''994860''>somewhere</span>
  <span m=''995380''>where</span> <span m=''995430''>we</span> <span m=''995570''>want</span>
  <span m=''995780''>them</span> <span m=''995950''>to</span> <span m=''996040''>zero.</span>
  <span m=''997190''>We</span> <span m=''997290''>construct</span> <span m=''997800''>them</span>
  <span m=''998270''>somewhat</span> <span m=''998610''>differently</span> <span m=''999170''>than</span>
  <span m=''999360''>here.</span> </p><p><span m=''1000630''>And</span> <span m=''1000740''>in</span>
  <span m=''1000810''>particular,</span> <span m=''1002685''>let''s</span> <span m=''1003140''>define</span>
  <span m=''1004630''>g</span> <span m=''1006720''>as</span> <span m=''1006920''>a</span>
  <span m=''1006990''>product</span> <span m=''1007670''>of</span> <span m=''1007970''>i</span>
  <span m=''1008250''>equal</span> <span m=''1009960''>k</span> <span m=''1010430''>up
  to</span> <span m=''1010760''>n</span> <span m=''1010970''>minus</span> <span m=''1011330''>1</span>
  <span m=''1012820''>of</span> <span m=''1013210''>x</span> <span m=''1013560''>minus</span>
  <span m=''1015410''>omega</span> <span m=''1017500''>minus</span> <span m=''1017750''>i.</span>
  <span m=''1018560''>So</span> <span m=''1018760''>it''s</span> <span m=''1018910''>a</span>
  <span m=''1018960''>polynomial.</span> <span m=''1020950''>This</span> <span m=''1021210''>is</span>
  <span m=''1021330''>a</span> <span m=''1021400''>polynomial</span> <span m=''1023520''>which</span>
  <span m=''1024300''>satisfies</span> <span m=''1024660''>this.</span> <span m=''1027369''>So</span>
  <span m=''1027550''>in</span> <span m=''1027630''>particular,</span> <span m=''1028230''>we</span>
  <span m=''1028329''>have</span> <span m=''1029079''>g</span> <span m=''1031261''>of</span>
  <span m=''1031680''>omega</span> <span m=''1032480''>minus</span> <span m=''1032920''>i</span>
  <span m=''1034119''>is</span> <span m=''1034230''>equal</span> <span m=''1034490''>to</span>
  <span m=''1034660''>0</span> <span m=''1036210''>for</span> <span m=''1036565''>all</span>
  <span m=''1037365''>i</span> <span m=''1037810''>less</span> <span m=''1038089''>than</span>
  <span m=''1038300''>n</span> <span m=''1039680''>less</span> <span m=''1040020''>than
  --</span> <span m=''1040481''>I''m</span> <span m=''1040942''>sorry --</span> <span
  m=''1041864''>and</span> <span m=''1042329''>greater</span> <span m=''1042829''>than</span>
  <span m=''1043040''>k.</span> </p><p><span m=''1046540''>So</span> <span m=''1048260''>this</span>
  <span m=''1048460''>is</span> <span m=''1048569''>a</span> <span m=''1048640''>code</span>
  <span m=''1048945''>word,</span> <span m=''1049250''>right?</span> <span m=''1050700''>We
  are</span> <span m=''1050810''>agreed</span> <span m=''1051100''>this</span> <span
  m=''1051250''>is a</span> <span m=''1051400''>code</span> <span m=''1051880''>word?</span>
  <span m=''1053116''>Good.</span> <span m=''1053940''>So</span> <span m=''1054180''>we</span>
  <span m=''1054300''>found</span> <span m=''1054540''>a</span> <span m=''1054630''>code</span>
  <span m=''1054910''>word</span> <span m=''1055170''>without</span> <span m=''1055540''>going</span>
  <span m=''1055840''>through</span> <span m=''1056060''>this</span> <span m=''1056330''>here,</span>
  <span m=''1057390''>without</span> <span m=''1057730''>going</span> <span m=''1057980''>through</span>
  <span m=''1058170''>the</span> <span m=''1058860''>evaluation</span> <span m=''1059165''>map.</span>
  <span m=''1060020''>We</span> <span m=''1060120''>found</span> <span m=''1060400''>it</span>
  <span m=''1060530''>straight</span> <span m=''1060910''>away.</span> </p><p><span
  m=''1062000''>But</span> <span m=''1062180''>not</span> <span m=''1062390''>only</span>
  <span m=''1062630''>did</span> <span m=''1062820''>we</span> <span m=''1062910''>find</span>
  <span m=''1063260''>this.</span> <span m=''1064210''>This</span> <span m=''1064460''>has</span>
  <span m=''1064720''>degree</span> <span m=''1065140''>n</span> <span m=''1065300''>minus</span>
  <span m=''1065660''>k.</span> <span m=''1068470''>This</span> <span m=''1068680''>has</span>
  <span m=''1068950''>degree</span> <span m=''1070440''>n</span> <span m=''1070650''>minus</span>
  <span m=''1070970''>k.</span> <span m=''1071190''>So</span> <span m=''1071330''>maybe</span>
  <span m=''1072100''>there''s</span> <span m=''1072890''>another</span> <span m=''1073180''>interpretation.</span>
  <span m=''1073990''>Now</span> <span m=''1074070''>we</span> <span m=''1074170''>can</span>
  <span m=''1074400''>give</span> <span m=''1076420''>a</span> <span m=''1076510''>whole</span>
  <span m=''1076800''>new</span> <span m=''1077010''>definition</span> <span m=''1077840''>of</span>
  <span m=''1078105''>the</span> <span m=''1078370''>Reed-Solomon</span> <span m=''1079000''>code,</span>
  <span m=''1079420''>namely,</span> <span m=''1085090''>as</span> <span m=''1085310''>a</span>
  <span m=''1085370''>set</span> <span m=''1085610''>of</span> <span m=''1085730''>polynomials,</span>
  <span m=''1087630''>which are</span> <span m=''1087890''>sort</span> <span m=''1088010''>of</span>
  <span m=''1088110''>implicitly</span> <span m=''1088680''>identified</span> <span
  m=''1089260''>with</span> <span m=''1089370''>a</span> <span m=''1089450''>set</span>
  <span m=''1089650''>of</span> <span m=''1089720''>vectors</span> <span m=''1091580''>such</span>
  <span m=''1092000''>that</span> <span m=''1096910''>times</span> <span m=''1097490''>this</span>
  <span m=''1097740''>g</span> <span m=''1097970''>of</span> <span m=''1098170''>x</span>
  <span m=''1101820''>and</span> <span m=''1102310''>h</span> <span m=''1102550''>of</span>
  <span m=''1102740''>x</span> <span m=''1107680''>is</span> <span m=''1107780''>less</span>
  <span m=''1107950''>then</span> <span m=''1108180''>k</span> <span m=''1108410''>again.</span>
  </p><p><span m=''1110830''>So</span> <span m=''1111010''>what</span> <span m=''1111170''>we</span>
  <span m=''1111340''>have</span> <span m=''1111510''>here,</span> <span m=''1112080''>it''s</span>
  <span m=''1112530''>again,</span> <span m=''1113860''>you</span> <span m=''1113940''>take</span>
  <span m=''1114210''>a</span> <span m=''1114270''>vector</span> <span m=''1114640''>space</span>
  <span m=''1115330''>of</span> <span m=''1115480''>functions</span> <span m=''1116180''>the</span>
  <span m=''1116340''>h.</span> <span m=''1118050''>It''s</span> <span m=''1118210''>a</span>
  <span m=''1118340''>k</span> <span m=''1118460''>dimensional</span> <span m=''1118950''>vector</span>
  <span m=''1119270''>space.</span> <span m=''1120800''>And</span> <span m=''1120970''>we</span>
  <span m=''1121050''>multiplied</span> <span m=''1121680''>with</span> <span m=''1121850''>this</span>
  <span m=''1122060''>g.</span> <span m=''1123426''>It''s</span> <span m=''1123820''>again</span>
  <span m=''1124040''>a linear</span> <span m=''1124580''>map,</span> <span m=''1124890''>this</span>
  <span m=''1125040''>multiplication</span> <span m=''1125830''>with</span> <span
  m=''1125920''>a</span> <span m=''1125970''>fixed</span> <span m=''1126280''>polynomial.</span>
  <span m=''1129220''>A</span> <span m=''1129560''>linear</span> <span m=''1129640''>map</span>
  <span m=''1129920''>of</span> <span m=''1130060''>this</span> <span m=''1130210''>vector</span>
  <span m=''1130520''>space</span> <span m=''1130940''>gives</span> <span m=''1131150''>us,</span>
  <span m=''1131300''>again,</span> <span m=''1132240''>a</span> <span m=''1132340''>vector</span>
  <span m=''1132640''>space</span> <span m=''1133000''>of</span> <span m=''1133120''>dimension</span>
  <span m=''1133640''>k.</span> <span m=''1134810''>And</span> <span m=''1135030''>all</span>
  <span m=''1135330''>elements</span> <span m=''1136140''>in</span> <span m=''1136270''>this</span>
  <span m=''1136450''>vector</span> <span m=''1136800''>space</span> <span m=''1138280''>evaluate</span>
  <span m=''1139490''>to</span> <span m=''1139610''>0</span> <span m=''1141040''>for
  all</span> <span m=''1141480''>omega</span> <span m=''1141910''>to</span> <span
  m=''1142020''>the</span> <span m=''1142100''>minus</span> <span m=''1142380''>i.</span>
  </p><p><span m=''1144270''>That''s</span> <span m=''1144450''>just</span> <span
  m=''1144670''>the</span> <span m=''1144730''>same</span> <span m=''1144980''>again,</span>
  <span m=''1145770''>just</span> <span m=''1146040''>the</span> <span m=''1146140''>Reed-Solomon</span>
  <span m=''1146590''>code</span> <span m=''1146900''>again.</span> <span m=''1147570''>So</span>
  <span m=''1147810''>it''s</span> <span m=''1147940''>a</span> <span m=''1147980''>very</span>
  <span m=''1148150''>nice</span> <span m=''1150650''>complementary</span> <span m=''1151310''>description</span>
  <span m=''1151990''>to</span> <span m=''1152140''>the</span> <span m=''1152690''>same</span>
  <span m=''1154010''>Reed-Solomon</span> <span m=''1154520''>code</span> <span m=''1155240''>we
  could</span> <span m=''1155530''>define</span> <span m=''1155940''>up</span> <span
  m=''1156110''>here,</span> <span m=''1156990''>we</span> <span m=''1157080''>have</span>
  <span m=''1157210''>found</span> <span m=''1157530''>again</span> <span m=''1157890''>down</span>
  <span m=''1158220''>here.</span> <span m=''1163300''>What is so</span> <span m=''1163560''>nice</span>
  <span m=''1163910''>about</span> <span m=''1164210''>this?</span> <span m=''1170350''>Yeah,</span>
  <span m=''1170480''>what</span> <span m=''1170640''>do you</span> <span m=''1170750''>think</span>
  <span m=''1170860''>is</span> <span m=''1170970''>so</span> <span m=''1171020''>nice</span>
  <span m=''1171270''>about this?</span> <span m=''1173830''>About</span> <span m=''1173990''>this</span>
  <span m=''1174170''>description?</span> <span m=''1179960''>So</span> <span m=''1180120''>now</span>
  <span m=''1180280''>you</span> <span m=''1180360''>have</span> <span m=''1180490''>to</span>
  <span m=''1180580''>think</span> <span m=''1180800''>as</span> <span m=''1180920''>engineers.</span>
  </p><p><span m=''1182344''>AUDIENCE: You can</span> <span m=''1182751''>still</span>
  <span m=''1183160''>evaluate it.</span> <span m=''1183710''>There, we</span> <span
  m=''1184180''>have to</span> <span m=''1184650''>evaluate it</span> <span m=''1185120''>at</span>
  <span m=''1185590''>end</span> <span m=''1185880''>points</span> <span m=''1186310''>of
  function.</span> </p><p><span m=''1187930''>PROFESSOR: Yeah,</span> <span m=''1188410''>exactly.</span>
  <span m=''1188930''>This</span> <span m=''1189130''>is</span> <span m=''1189230''>so</span>
  <span m=''1189580''>easy</span> <span m=''1189920''>to</span> <span m=''1190040''>implement.</span>
  </p><p><span m=''1191710''>So</span> <span m=''1191850''>now</span> <span m=''1192070''>we</span>
  <span m=''1192760''>think</span> <span m=''1192960''>a little</span> <span m=''1193150''>bit</span>
  <span m=''1193260''>about</span> <span m=''1193690''>encoder.</span> <span m=''1195730''>An</span>
  <span m=''1195920''>encoder</span> <span m=''1200230''>for</span> <span m=''1201540''>a</span>
  <span m=''1202040''>Reed-Solomon</span> <span m=''1202490''>code.</span> <span m=''1204320''>How</span>
  <span m=''1204400''>would</span> <span m=''1204580''>we</span> <span m=''1204670''>do</span>
  <span m=''1204820''>that?</span> <span m=''1207710''>You</span> <span m=''1207850''>look</span>
  <span m=''1208050''>at</span> <span m=''1208170''>this</span> <span m=''1208390''>here.</span>
  <span m=''1208760''>Hey,</span> <span m=''1209250''>let''s</span> <span m=''1209480''>do</span>
  <span m=''1209620''>this.</span> <span m=''1209950''>Let''s</span> <span m=''1210140''>exactly</span>
  <span m=''1210640''>do</span> <span m=''1210820''>this.</span> </p><p><span m=''1211550''>Meaning</span>
  <span m=''1212010''>in</span> <span m=''1212220''>VLSI,</span> <span m=''1217800''>we</span>
  <span m=''1217930''>do</span> <span m=''1218130''>something</span> <span m=''1218570''>like
  --</span> <span m=''1236720''>and</span> <span m=''1237070''>here,</span> <span
  m=''1237380''>you</span> <span m=''1237570''>would</span> <span m=''1237750''>write
  --</span> <span m=''1238060''>and</span> <span m=''1238170''>this</span> <span m=''1238340''>is</span>
  <span m=''1238450''>just</span> <span m=''1239340''>a</span> <span m=''1239460''>delay</span>
  <span m=''1239840''>element.</span> <span m=''1241700''>This</span> <span m=''1242010''>one</span>
  <span m=''1242230''>would</span> <span m=''1242500''>be</span> <span m=''1243200''>g</span>
  <span m=''1245700''>n</span> <span m=''1245910''>minus</span> <span m=''1246440''>k.</span>
  <span m=''1248290''>This</span> <span m=''1248610''>one --</span> <span m=''1254150''>so</span>
  <span m=''1254290''>these</span> <span m=''1254540''>would</span> <span m=''1254690''>be</span>
  <span m=''1254850''>the</span> <span m=''1254970''>coefficients.</span> </p><p><span
  m=''1256120''>This</span> <span m=''1256720''>polynomial,</span> <span m=''1257410''>we</span>
  <span m=''1257520''>can</span> <span m=''1257730''>evaluate</span> <span m=''1258200''>once</span>
  <span m=''1258430''>and</span> <span m=''1258550''>for</span> <span m=''1258780''>all.</span>
  <span m=''1258990''>We</span> <span m=''1259290''>do</span> <span m=''1259450''>that</span>
  <span m=''1259790''>once</span> <span m=''1260140''>before</span> <span m=''1260440''>we</span>
  <span m=''1260540''>start</span> <span m=''1260880''>our</span> <span m=''1261050''>communication.</span>
  <span m=''1261790''>We</span> <span m=''1262220''>evaluate</span> <span m=''1262720''>that</span>
  <span m=''1262830''>polynomial</span> <span m=''1263380''>once</span> <span m=''1263600''>and
  for</span> <span m=''1263770''>all.</span> <span m=''1264040''>We</span> <span m=''1264140''>know</span>
  <span m=''1264380''>these</span> <span m=''1264610''>coefficients.</span> <span
  m=''1266050''>So</span> <span m=''1266410''>these</span> <span m=''1266620''>are</span>
  <span m=''1266690''>multipliers</span> <span m=''1269081''>which</span> <span m=''1269560''>multiply</span>
  <span m=''1270330''>with</span> <span m=''1270510''>those</span> <span m=''1270770''>corresponding</span>
  <span m=''1271360''>coefficients.</span> <span m=''1272060''>And</span> <span m=''1272190''>we</span>
  <span m=''1272320''>feed</span> <span m=''1272680''>into</span> <span m=''1272970''>here</span>
  <span m=''1277870''>the</span> <span m=''1278110''>coefficients</span> <span m=''1278830''>of</span>
  <span m=''1279080''>this</span> <span m=''1279450''>polynomial.</span> <span m=''1280160''>This</span>
  <span m=''1280400''>is our</span> <span m=''1280600''>information</span> <span m=''1281170''>symbols,</span>
  <span m=''1281425''>which</span> <span m=''1281680''>we</span> <span m=''1281840''>simply</span>
  <span m=''1282180''>feed</span> <span m=''1282430''>into</span> <span m=''1282660''>this</span>
  <span m=''1282980''>circuitry.</span> <span m=''1285930''>And</span> <span m=''1286180''>into
  this</span> <span m=''1286380''>circuit,</span> <span m=''1287060''>out</span> <span
  m=''1287475''>comes</span> <span m=''1289351''>F,</span> <span m=''1289840''>out</span>
  <span m=''1290040''>comes</span> <span m=''1290330''>the</span> <span m=''1290410''>coefficient.</span>
  <span m=''1292290''>Polynomial</span> <span m=''1292590''>multiplication.</span>
  </p><p><span m=''1294300''>If</span> <span m=''1294440''>you</span> <span m=''1294530''>show</span>
  <span m=''1294800''>that</span> <span m=''1295020''>to a VLSI</span> <span m=''1295177''>designer,</span>
  <span m=''1297050''>they are</span> <span m=''1297350''>deliriously</span> <span
  m=''1297870''>happy.</span> <span m=''1299330''>They</span> <span m=''1299480''>say,</span>
  <span m=''1300020''>you</span> <span m=''1300120''>know</span> <span m=''1300220''>what?</span>
  <span m=''1300470''>I</span> <span m=''1300620''>implement</span> <span m=''1300910''>you</span>
  <span m=''1301200''>this</span> <span m=''1301320''>thing.</span> <span m=''1301690''>I</span>
  <span m=''1301800''>implement</span> <span m=''1302150''>you</span> <span m=''1302500''>in</span>
  <span m=''1303140''>5,000</span> <span m=''1303800''>gates,</span> <span m=''1304930''>which</span>
  <span m=''1305420''>is</span> <span m=''1305590''>close</span> <span m=''1305840''>to</span>
  <span m=''1305940''>nothing</span> <span m=''1306270''>nowadays.</span> <span m=''1309760''>Maybe</span>
  <span m=''1309830''>not.</span> <span m=''1310240''>Maybe</span> <span m=''1310460''>10,000.</span>
  </p><p><span m=''1313690''>And</span> <span m=''1313880''>there</span> <span m=''1314060''>you</span>
  <span m=''1314130''>get</span> <span m=''1314300''>to</span> <span m=''1314390''>the</span>
  <span m=''1314480''>second</span> <span m=''1315940''>reason</span> <span m=''1316300''>that</span>
  <span m=''1316500''>Reed-Solomon</span> <span m=''1316810''>codes</span> <span m=''1317060''>are</span>
  <span m=''1317460''>so</span> <span m=''1317910''>extremely</span> <span m=''1318680''>important</span>
  <span m=''1319240''>in</span> <span m=''1319370''>practice.</span> <span m=''1320540''>On</span>
  <span m=''1320650''>the</span> <span m=''1320770''>one</span> <span m=''1320990''>hand,</span>
  <span m=''1321600''>they are</span> <span m=''1321790''>MDS</span> <span m=''1322130''>codes,</span>
  <span m=''1323640''>meaning</span> <span m=''1323940''>they</span> <span m=''1324050''>are</span>
  <span m=''1324360''>about</span> <span m=''1324660''>as</span> <span m=''1324870''>good</span>
  <span m=''1325080''>as</span> <span m=''1325220''>it</span> <span m=''1325280''>gets.</span>
  <span m=''1327820''>And</span> <span m=''1328010''>on</span> <span m=''1328150''>the</span>
  <span m=''1328320''>other</span> <span m=''1328490''>hand,</span> <span m=''1329660''>they</span>
  <span m=''1329960''>are</span> <span m=''1330270''>algorithms.</span> <span m=''1330615''>They
  are</span> <span m=''1330960''>circuitry</span> <span m=''1331600''>for</span> <span
  m=''1331740''>these</span> <span m=''1331990''>things</span> <span m=''1334720''>whose</span>
  <span m=''1334860''>cost</span> <span m=''1335180''>is</span> <span m=''1335280''>close</span>
  <span m=''1335580''>to nothing</span> <span m=''1337830''>at</span> <span m=''1338000''>least</span>
  <span m=''1338280''>today.</span> </p><p><span m=''1338970''>When</span> <span m=''1339090''>they</span>
  <span m=''1339170''>were</span> <span m=''1339290''>invented,</span> <span m=''1339960''>that</span>
  <span m=''1340100''>was</span> <span m=''1340320''>quite</span> <span m=''1340550''>different.</span>
  <span m=''1341770''>In</span> <span m=''1341890''>the</span> <span m=''1341980''>''60s,</span>
  <span m=''1343120''>that</span> <span m=''1343330''>would</span> <span m=''1343430''>have</span>
  <span m=''1343540''>not</span> <span m=''1343930''>been</span> <span m=''1344100''>implementable</span>
  <span m=''1345080''>with</span> <span m=''1345250''>transistors</span> <span m=''1346010''>on</span>
  <span m=''1346080''>a</span> <span m=''1346150''>board</span> <span m=''1346560''>or
  something</span> <span m=''1346933''>like that.</span> <span m=''1347680''>But</span>
  <span m=''1347880''>today,</span> <span m=''1348250''>the</span> <span m=''1348350''>cost
  is</span> <span m=''1348710''>close</span> <span m=''1349010''>to nothing.</span>
  <span m=''1349920''>So</span> <span m=''1350250''>the</span> <span m=''1350450''>whole</span>
  <span m=''1350680''>algorithmic</span> <span m=''1351290''>treatment</span> <span
  m=''1351750''>of</span> <span m=''1352030''>Reed-Solomon</span> <span m=''1352380''>codes</span>
  <span m=''1353400''>is</span> <span m=''1353540''>very</span> <span m=''1353900''>well</span>
  <span m=''1354110''>developed.</span> <span m=''1356000''>The encoder</span> <span
  m=''1356390''>you</span> <span m=''1356560''>could</span> <span m=''1356710''>do</span>
  <span m=''1356820''>like</span> <span m=''1357030''>this.</span> <span m=''1357570''>Yeah.</span>
  </p><p><span m=''1358886''>AUDIENCE: Question</span> <span m=''1359352''>about</span>
  <span m=''1359818''>why</span> <span m=''1359973''>do you</span> <span m=''1360128''>still</span>
  <span m=''1360284''>require</span> <span m=''1360750''>that degree</span> <span
  m=''1361216''>[INAUDIBLE]?</span> </p><p><span m=''1363546''>PROFESSOR: You</span>
  <span m=''1364020''>don''t</span> <span m=''1364310''>need</span> <span m=''1364500''>to
  do</span> <span m=''1364840''>that.</span> <span m=''1365095''>But</span> <span
  m=''1365350''>then</span> <span m=''1365510''>the</span> <span m=''1365600''>mapping</span>
  <span m=''1365950''>is</span> <span m=''1366070''>not</span> <span m=''1366220''>one-to-one</span>
  <span m=''1366780''>anymore.</span> <span m=''1370580''>Then</span> <span m=''1370910''>the</span>
  <span m=''1371000''>mapping</span> <span m=''1371350''>is</span> <span m=''1371480''>not</span>
  <span m=''1371620''>one-to-one</span> <span m=''1372170''>anymore.</span> <span
  m=''1376120''>Let''s</span> <span m=''1376270''>put</span> <span m=''1376410''>it</span>
  <span m=''1376610''>other</span> <span m=''1376880''>ways.</span> </p><p><span m=''1378170''>You</span>
  <span m=''1378310''>want</span> <span m=''1378390''>code</span> <span m=''1378600''>words</span>
  <span m=''1378830''>of</span> <span m=''1379040''>length</span> <span m=''1379440''>n.</span>
  <span m=''1380280''>If</span> <span m=''1380430''>the</span> <span m=''1380530''>degree</span>
  <span m=''1380970''>is</span> <span m=''1381170''>larger,</span> <span m=''1381535''>you</span>
  <span m=''1381900''>run</span> <span m=''1382150''>over.</span> <span m=''1383590''>In</span>
  <span m=''1383760''>order</span> <span m=''1383970''>to</span> <span m=''1384070''>still</span>
  <span m=''1384350''>get</span> <span m=''1384510''>a</span> <span m=''1384580''>code</span>
  <span m=''1384835''>word,</span> <span m=''1385090''>then</span> <span m=''1385560''>you</span>
  <span m=''1385680''>have</span> <span m=''1385810''>to</span> <span m=''1385920''>take</span>
  <span m=''1386150''>it</span> <span m=''1386250''>modular</span> <span m=''1386670''>x</span>
  <span m=''1386880''>to</span> <span m=''1386990''>the</span> <span m=''1387100''>n</span>
  <span m=''1387250''>minus</span> <span m=''1387520''>1.</span> <span m=''1388840''>And</span>
  <span m=''1389270''>that</span> <span m=''1389620''>would fold</span> <span m=''1389820''>the</span>
  <span m=''1390020''>coefficients</span> <span m=''1390590''>back.</span> <span m=''1391340''>And</span>
  <span m=''1391640''>still,</span> <span m=''1391950''>it gives</span> <span m=''1392260''>you
  a</span> <span m=''1392530''>valid</span> <span m=''1392800''>code</span> <span
  m=''1393060''>word</span> <span m=''1393360''>then,</span> <span m=''1393550''>but</span>
  <span m=''1393750''>this</span> <span m=''1393890''>is</span> <span m=''1394020''>not</span>
  <span m=''1394180''>one-to-one</span> <span m=''1394910''>anymore.</span> <span
  m=''1396900''>Anyway,</span> <span m=''1397740''>the</span> <span m=''1398100''>short</span>
  <span m=''1398500''>answer</span> <span m=''1398600''>is</span> <span m=''1398830''>if</span>
  <span m=''1398930''>you</span> <span m=''1399070''>allow</span> <span m=''1399320''>more,</span>
  <span m=''1399650''>then</span> <span m=''1399830''>they</span> <span m=''1399980''>become</span>
  <span m=''1401550''>longer</span> <span m=''1401810''>than</span> <span m=''1401960''>n.</span>
  </p><p><span m=''1405410''>So</span> <span m=''1406491''>what''s the</span> <span
  m=''1406972''>time?</span> <span m=''1409860''>OK.</span> <span m=''1411050''>So</span>
  <span m=''1411240''>this</span> <span m=''1411440''>is</span> <span m=''1411570''>a</span>
  <span m=''1411630''>nice</span> <span m=''1411920''>encoder.</span> <span m=''1412880''>There
  even</span> <span m=''1413130''>is</span> <span m=''1413320''>a</span> <span m=''1413380''>nicer</span>
  <span m=''1413710''>encoder,</span> <span m=''1414910''>which</span> <span m=''1417700''>I</span>
  <span m=''1417820''>just</span> <span m=''1418110''>want</span> <span m=''1418270''>to</span>
  <span m=''1419300''>give</span> <span m=''1419650''>the</span> <span m=''1419730''>formula</span>
  <span m=''1420240''>for.</span> <span m=''1421950''>The</span> <span m=''1422240''>one</span>
  <span m=''1422490''>reason</span> <span m=''1422800''>that</span> <span m=''1422990''>people</span>
  <span m=''1423250''>still</span> <span m=''1423500''>have</span> <span m=''1423600''>a</span>
  <span m=''1423690''>problem</span> <span m=''1424100''>with</span> <span m=''1424260''>this</span>
  <span m=''1424540''>is</span> <span m=''1424780''>it''s</span> <span m=''1424920''>not</span>
  <span m=''1425110''>systematic.</span> <span m=''1426860''>People</span> <span m=''1429660''>like</span>
  <span m=''1429950''>to</span> <span m=''1430050''>see</span> <span m=''1430290''>the</span>
  <span m=''1430370''>symbols</span> <span m=''1431020''>in</span> <span m=''1431270''>the</span>
  <span m=''1431370''>code words</span> <span m=''1431850''>themselves.</span> <span
  m=''1432185''>They want</span> <span m=''1432520''>the</span> <span m=''1432730''>systematic</span>
  <span m=''1433035''>part.</span> </p><p><span m=''1434226''>How</span> <span m=''1434670''>could</span>
  <span m=''1434810''>we</span> <span m=''1434950''>achieve</span> <span m=''1435350''>that?</span>
  <span m=''1436890''>Well,</span> <span m=''1437280''>we</span> <span m=''1437350''>go</span>
  <span m=''1437590''>from the</span> <span m=''1437900''>same</span> <span m=''1439170''>description</span>
  <span m=''1439560''>here.</span> <span m=''1440150''>We</span> <span m=''1440240''>say,</span>
  <span m=''1441260''>well,</span> <span m=''1444000''>let</span> <span m=''1444160''>h</span>
  <span m=''1444320''>of x</span> <span m=''1445800''>be</span> <span m=''1446240''>given.</span>
  <span m=''1449970''>Then</span> <span m=''1450060''>compute</span> <span m=''1455630''>x</span>
  <span m=''1456120''>to</span> <span m=''1456220''>the</span> <span m=''1456400''>n</span>
  <span m=''1456640''>minus</span> <span m=''1457080''>k</span> <span m=''1458660''>times</span>
  <span m=''1459030''>h</span> <span m=''1459320''>of</span> <span m=''1459750''>x</span>
  <span m=''1461470''>modular</span> <span m=''1461780''>g</span> <span m=''1462010''>of</span>
  <span m=''1462360''>x.</span> </p><p><span m=''1463060''>So</span> <span m=''1465600''>we</span>
  <span m=''1465710''>divide</span> <span m=''1466090''>this</span> <span m=''1466310''>polynomial</span>
  <span m=''1467430''>by</span> <span m=''1467720''>this</span> <span m=''1467910''>polynomial</span>
  <span m=''1468430''>g --</span> <span m=''1468910''>it</span> <span m=''1469290''>has</span>
  <span m=''1469520''>a</span> <span m=''1469590''>name.</span> <span m=''1469860''>It''s</span>
  <span m=''1470150''>called</span> <span m=''1470310''>the</span> <span m=''1470410''>generator</span>
  <span m=''1470880''>polynomial.</span> <span m=''1472240''>We</span> <span m=''1472360''>divide</span>
  <span m=''1472730''>it</span> <span m=''1472850''>by</span> <span m=''1473020''>g.</span>
  <span m=''1474790''>And</span> <span m=''1474990''>out</span> <span m=''1475190''>comes</span>
  <span m=''1477330''>some</span> <span m=''1477570''>polynomial</span> <span m=''1478230''>r</span>
  <span m=''1478290''>of</span> <span m=''1478770''>x</span> <span m=''1482830''>of</span>
  <span m=''1483000''>some</span> <span m=''1483230''>low</span> <span m=''1483470''>degree,</span>
  <span m=''1483960''>degree</span> <span m=''1484370''>less</span> <span m=''1484640''>than
  g.</span> <span m=''1487960''>And</span> <span m=''1488060''>degree</span> <span
  m=''1490010''>r</span> <span m=''1490500''>of</span> <span m=''1490720''>x</span>
  <span m=''1492980''>less</span> <span m=''1493240''>than</span> <span m=''1493380''>n</span>
  <span m=''1493530''>minus</span> <span m=''1493910''>k</span> <span m=''1494150''>in</span>
  <span m=''1494310''>particular.</span> </p><p><span m=''1496900''>So</span> <span
  m=''1497110''>and</span> <span m=''1497250''>then</span> <span m=''1497440''>we</span>
  <span m=''1497540''>can</span> <span m=''1497940''>form</span> <span m=''1498330''>a</span>
  <span m=''1498420''>code</span> <span m=''1498650''>word.</span> <span m=''1499100''>I</span>
  <span m=''1499180''>claim</span> <span m=''1499830''>F</span> <span m=''1500130''>of</span>
  <span m=''1501670''>x,</span> <span m=''1502080''>no,</span> <span m=''1502230''>F</span>
  <span m=''1504180''>is --</span> <span m=''1505110''>and here</span> <span m=''1505270''>we</span>
  <span m=''1505430''>write</span> <span m=''1505730''>r,</span> <span m=''1506960''>and</span>
  <span m=''1507370''>here</span> <span m=''1507570''>we</span> <span m=''1507730''>write</span>
  <span m=''1509730''>h.</span> <span m=''1512040''>The</span> <span m=''1512150''>coefficient</span>
  <span m=''1512610''>vector</span> <span m=''1513180''>of</span> <span m=''1513610''>h</span>
  <span m=''1514930''>and</span> <span m=''1515130''>the</span> <span m=''1515220''>coefficient</span>
  <span m=''1515720''>vector</span> <span m=''1516130''>of r.</span> <span m=''1517870''>Why</span>
  <span m=''1518090''>is</span> <span m=''1518160''>that</span> <span m=''1518300''>a</span>
  <span m=''1518360''>code</span> <span m=''1518620''>word?</span> <span m=''1520870''>Why</span>
  <span m=''1521060''>is</span> <span m=''1521170''>that</span> <span m=''1521290''>a</span>
  <span m=''1521360''>code</span> <span m=''1521640''>word?</span> <span m=''1521850''>Maybe</span>
  <span m=''1522090''>minus</span> <span m=''1522320''>here.</span> <span m=''1523190''>I''m</span>
  <span m=''1523330''>always</span> <span m=''1523680''>thinking</span> <span m=''1524040''>characteristic</span>
  <span m=''1524700''>2</span> <span m=''1524950''>anyway.</span> <span m=''1525270''>So</span>
  <span m=''1526620''>why</span> <span m=''1526950''>is this</span> <span m=''1527205''>a</span>
  <span m=''1527460''>code word?</span> <span m=''1528180''>Anybody,</span> <span
  m=''1528490''>it''s</span> <span m=''1528800''>clear?</span> </p><p><span m=''1532534''>What</span>
  <span m=''1533030''>this is</span> <span m=''1533390''>in</span> <span m=''1533500''>terms</span>
  <span m=''1533720''>of</span> <span m=''1534060''>F</span> <span m=''1534300''>of</span>
  <span m=''1534700''>x</span> <span m=''1536920''>is</span> <span m=''1538460''>r</span>
  <span m=''1538790''>of</span> <span m=''1539030''>x</span> <span m=''1539440''>plus</span>
  <span m=''1541852''>h</span> <span m=''1542290''>of</span> <span m=''1542730''>x.</span>
  <span m=''1545545''>Oh,</span> <span m=''1545820''>minus</span> <span m=''1546160''>r</span>
  <span m=''1546220''>of x.</span> <span m=''1548000''>That''s</span> <span m=''1548170''>because</span>
  <span m=''1548500''>we</span> <span m=''1548580''>wrote</span> <span m=''1548840''>it</span>
  <span m=''1548880''>like this.</span> <span m=''1550240''>If</span> <span m=''1550360''>we</span>
  <span m=''1550470''>now</span> <span m=''1550700''>take</span> <span m=''1551060''>the</span>
  <span m=''1552470''>F</span> <span m=''1552720''>of</span> <span m=''1552920''>x</span>
  <span m=''1555510''>modular</span> <span m=''1557720''>g</span> <span m=''1557990''>of</span>
  <span m=''1558190''>x,</span> <span m=''1559220''>well,</span> <span m=''1559610''>this</span>
  <span m=''1559870''>part</span> <span m=''1561310''>has</span> <span m=''1561590''>degree</span>
  <span m=''1562060''>low.</span> <span m=''1562400''>It''s</span> <span m=''1562800''>not</span>
  <span m=''1562900''>affected</span> <span m=''1563260''>by this</span> <span m=''1563550''>modular</span>
  <span m=''1564010''>operation.</span> </p><p><span m=''1565130''>This</span> <span
  m=''1565410''>would</span> <span m=''1565580''>be</span> <span m=''1565750''>minus</span>
  <span m=''1566160''>r</span> <span m=''1566400''>of</span> <span m=''1566520''>x</span>
  <span m=''1567720''>plus</span> <span m=''1569440''>this</span> <span m=''1569660''>one,</span>
  <span m=''1569870''>modular</span> <span m=''1570030''>g of</span> <span m=''1570290''>x,</span>
  <span m=''1570820''>which</span> <span m=''1571040''>is</span> <span m=''1571160''>r
  of</span> <span m=''1571470''>x.</span> <span m=''1573940''>So</span> <span m=''1574190''>the</span>
  <span m=''1574260''>whole</span> <span m=''1574420''>thing</span> <span m=''1574630''>is</span>
  <span m=''1574740''>0.</span> <span m=''1576860''>If</span> <span m=''1577100''>this</span>
  <span m=''1577310''>is</span> <span m=''1577440''>0,</span> <span m=''1578180''>that</span>
  <span m=''1578380''>means</span> <span m=''1578740''>g</span> <span m=''1578950''>of</span>
  <span m=''1579140''>x</span> <span m=''1579410''>is</span> <span m=''1579510''>a</span>
  <span m=''1579560''>factor</span> <span m=''1580900''>of</span> <span m=''1581070''>F.</span>
  <span m=''1581790''>Hence,</span> <span m=''1582000''>it''s a</span> <span m=''1582255''>code</span>
  <span m=''1582510''>word.</span> </p><p><span m=''1583930''>So</span> <span m=''1584090''>we</span>
  <span m=''1584160''>have</span> <span m=''1584290''>a</span> <span m=''1584420''>code</span>
  <span m=''1584680''>word</span> <span m=''1584840''>here.</span> <span m=''1585650''>And</span>
  <span m=''1585880''>in</span> <span m=''1586010''>the</span> <span m=''1586120''>code</span>
  <span m=''1586410''>word,</span> <span m=''1586800''>pop</span> <span m=''1587050''>up</span>
  <span m=''1588830''>our</span> <span m=''1588970''>symbols</span> <span m=''1589190''>right</span>
  <span m=''1589420''>away,</span> <span m=''1591440''>our</span> <span m=''1592150''>encoded</span>
  <span m=''1592590''>information</span> <span m=''1593090''>symbols</span> <span
  m=''1593525''>right away.</span> <span m=''1593960''>So</span> <span m=''1594110''>we</span>
  <span m=''1594220''>get</span> <span m=''1594390''>some nice</span> <span m=''1594730''>systematic</span>
  <span m=''1595360''>encoding</span> <span m=''1595620''>going.</span> </p><p><span
  m=''1597770''>This</span> <span m=''1598140''>division</span> <span m=''1598570''>circuit</span>
  <span m=''1599060''>by</span> <span m=''1599230''>g</span> <span m=''1599820''>is</span>
  <span m=''1599970''>pretty</span> <span m=''1600180''>much</span> <span m=''1600430''>the</span>
  <span m=''1600500''>same</span> <span m=''1600770''>size</span> <span m=''1601110''>as</span>
  <span m=''1601320''>this.</span> <span m=''1601790''>It''s not</span> <span m=''1602120''>larger</span>
  <span m=''1603140''>at</span> <span m=''1603320''>all.</span> <span m=''1605060''>So</span>
  <span m=''1605240''>there,</span> <span m=''1605460''>we</span> <span m=''1605530''>get</span>
  <span m=''1605850''>beautiful</span> <span m=''1606230''>algorithms.</span> <span
  m=''1606790''>This</span> <span m=''1606870''>is</span> <span m=''1607000''>actually</span>
  <span m=''1607300''>what''s</span> <span m=''1607490''>implemented.</span> <span
  m=''1608736''>If we</span> <span m=''1609120''>go</span> <span m=''1609390''>to</span>
  <span m=''1609540''>any</span> <span m=''1609690''>disc</span> <span m=''1609860''>drive</span>
  <span m=''1610250''>[UNINTELLIGIBLE],</span> <span m=''1611180''>that</span> <span
  m=''1611490''>is</span> <span m=''1611610''>usually</span> <span m=''1612000''>what</span>
  <span m=''1612230''>is</span> <span m=''1612688''>implemented</span> <span m=''1613146''>in
  there,</span> <span m=''1613604''>exactly</span> <span m=''1614062''>this.</span>
  </p><p><span m=''1616610''>Algorithms.</span> <span m=''1617990''>Algorithmic</span>
  <span m=''1618580''>treatment</span> <span m=''1619260''>of</span> <span m=''1619350''>Reed-Solomon</span>
  <span m=''1619470''>codes.</span> <span m=''1620850''>Do you</span> <span m=''1621310''>have</span>
  <span m=''1621450''>any</span> <span m=''1621590''>questions</span> <span m=''1621960''>about</span>
  <span m=''1622120''>any</span> <span m=''1622310''>of</span> <span m=''1622430''>this?</span>
  <span m=''1623590''>Yeah.</span> </p><p><span m=''1624015''>AUDIENCE: I have a question
  about</span> <span m=''1624440''>do any</span> <span m=''1624905''>these</span>
  <span m=''1625370''>Reed-Solomon</span> <span m=''1625835''>codes</span> <span m=''1626765''>map</span>
  <span m=''1627230''>[INAUDIBLE]?</span> </p><p><span m=''1629555''>PROFESSOR: They</span>
  <span m=''1630030''>are</span> <span m=''1630100''>very</span> <span m=''1631170''>costly</span>
  <span m=''1631650''>map.</span> <span m=''1631990''>Usually,</span> <span m=''1633340''>it</span>
  <span m=''1633470''>depends</span> <span m=''1633860''>a</span> <span m=''1633900''>lot</span>
  <span m=''1634120''>on</span> <span m=''1634240''>the</span> <span m=''1634350''>application.</span>
  <span m=''1634940''>If</span> <span m=''1635020''>you</span> <span m=''1635110''>think</span>
  <span m=''1635320''>disc</span> <span m=''1635620''>drives,</span> <span m=''1636100''>[UNINTELLIGIBLE]</span>
  <span m=''1636530''>as</span> <span m=''1636740''>just</span> <span m=''1636960''>being</span>
  <span m=''1637180''>mapped,</span> <span m=''1638260''>you</span> <span m=''1638400''>take</span>
  <span m=''1638900''>Reed-Solomon</span> <span m=''1639350''>codes</span> <span m=''1639610''>over
  a</span> <span m=''1639870''>characteristic</span> <span m=''1640500''>2.</span>
  <span m=''1641330''>Then</span> <span m=''1641610''>each</span> <span m=''1641860''>field</span>
  <span m=''1642140''>element</span> <span m=''1642600''>is</span> <span m=''1642760''>represented</span>
  <span m=''1644060''>as</span> <span m=''1644200''>a</span> <span m=''1644250''>binary</span>
  <span m=''1644650''>vector.</span> <span m=''1645840''>And</span> <span m=''1646000''>that</span>
  <span m=''1646190''>binary</span> <span m=''1646580''>vector</span> <span m=''1647080''>is</span>
  <span m=''1647290''>mapped</span> <span m=''1647640''>into</span> <span m=''1647860''>on-off</span>
  <span m=''1648000''>keying.</span> <span m=''1650460''>Straight</span> <span m=''1650820''>off</span>
  <span m=''1650950''>the</span> <span m=''1651030''>bat.</span> <span m=''1652230''>Nothing</span>
  <span m=''1652530''>more</span> <span m=''1652670''>fancy.</span> <span m=''1654560''>That</span>
  <span m=''1654740''>is</span> <span m=''1657660''>for</span> <span m=''1657820''>disc</span>
  <span m=''1658100''>drives.</span> </p><p><span m=''1660090''>And</span> <span m=''1660350''>as</span>
  <span m=''1660600''>you</span> <span m=''1660880''>do</span> <span m=''1661020''>this,</span>
  <span m=''1661270''>the</span> <span m=''1661350''>satellite</span> <span m=''1661960''>standard,</span>
  <span m=''1662260''>where</span> <span m=''1662550''>it''s</span> <span m=''1662710''>mapped</span>
  <span m=''1663000''>onto</span> <span m=''1663200''>the</span> <span m=''1663990''>256-QAM</span>
  <span m=''1666490''>field</span> <span m=''1666750''>elements</span> <span m=''1668180''>[UNINTELLIGIBLE].</span>
  <span m=''1668510''>So it''s</span> <span m=''1668800''>many</span> <span m=''1669040''>different</span>
  <span m=''1669390''>ways.</span> <span m=''1671490''>Many</span> <span m=''1671755''>different</span>
  <span m=''1672020''>ways.</span> </p><p><span m=''1673328''>AUDIENCE: But</span>
  <span m=''1673764''>to prove</span> <span m=''1674200''>some</span> <span m=''1674900''>performance</span>
  <span m=''1675370''>[UNINTELLIGIBLE]</span> <span m=''1675640''>in the</span> <span
  m=''1676083''>[UNINTELLIGIBLE],</span> <span m=''1676970''>we need</span> <span
  m=''1677330''>to have</span> <span m=''1677760''>mappings,</span> <span m=''1678190''>right?</span>
  </p><p><span m=''1678980''>PROFESSOR: In</span> <span m=''1679410''>order</span>
  <span m=''1679630''>to</span> <span m=''1679740''>prove</span> <span m=''1680130''>performance</span>
  <span m=''1680360''>mode, we</span> <span m=''1680720''>need</span> <span m=''1680900''>to</span>
  <span m=''1681030''>have</span> <span m=''1681150''>mappings.</span> <span m=''1682110''>And</span>
  <span m=''1682550''>the</span> <span m=''1682640''>Hamming</span> <span m=''1683020''>distance</span>
  <span m=''1683720''>bounds</span> <span m=''1683980''>that</span> <span m=''1684230''>we</span>
  <span m=''1684310''>get</span> <span m=''1684510''>from</span> <span m=''1684750''>here</span>
  <span m=''1685700''>give</span> <span m=''1685900''>you</span> <span m=''1686060''>bounds</span>
  <span m=''1686500''>on</span> <span m=''1686640''>the</span> <span m=''1686760''>minimum</span>
  <span m=''1687160''>Euclidean</span> <span m=''1687620''>distance.</span> <span
  m=''1689060''>If</span> <span m=''1689290''>these</span> <span m=''1689580''>are</span>
  <span m=''1689730''>good</span> <span m=''1689990''>bounds</span> <span m=''1690370''>or</span>
  <span m=''1690460''>not</span> <span m=''1691470''>depends</span> <span m=''1691840''>a</span>
  <span m=''1691870''>lot</span> <span m=''1692180''>on</span> <span m=''1692300''>the</span>
  <span m=''1692400''>modulation</span> <span m=''1692920''>scheme.</span> </p><p><span
  m=''1694150''>And</span> <span m=''1694870''>to</span> <span m=''1694950''>be</span>
  <span m=''1695100''>perfectly</span> <span m=''1695440''>honest,</span> <span m=''1695650''>they</span>
  <span m=''1695720''>usually</span> <span m=''1696060''>are</span> <span m=''1696150''>not.</span>
  <span m=''1697620''>They</span> <span m=''1698150''>usually</span> <span m=''1698470''>are</span>
  <span m=''1698540''>not very</span> <span m=''1698885''>good,</span> <span m=''1699666''>the</span>
  <span m=''1700102''>bounds.</span> <span m=''1701850''>But</span> <span m=''1702060''>it''s</span>
  <span m=''1702310''>a</span> <span m=''1702420''>very</span> <span m=''1702770''>difficult</span>
  <span m=''1703170''>problem</span> <span m=''1704920''>to</span> <span m=''1705050''>design</span>
  <span m=''1705610''>a</span> <span m=''1705680''>code</span> <span m=''1706130''>or</span>
  <span m=''1706240''>to</span> <span m=''1706350''>find</span> <span m=''1706740''>a</span>
  <span m=''1706830''>representation</span> <span m=''1707750''>of</span> <span m=''1707890''>the</span>
  <span m=''1708140''>fields</span> <span m=''1709530''>that</span> <span m=''1709730''>maps</span>
  <span m=''1710130''>nicely</span> <span m=''1710690''>onto a</span> <span m=''1711010''>modulation</span>
  <span m=''1711690''>scheme.</span> <span m=''1711965''>Very</span> <span m=''1712240''>difficult</span>
  <span m=''1712737''>problem.</span> </p><p><span m=''1714725''>AUDIENCE: How do</span>
  <span m=''1715222''>we know how</span> <span m=''1715719''>to</span> <span m=''1716216''>think
  that</span> <span m=''1717210''>this is a</span> <span m=''1717707''>good code?</span>
  </p><p><span m=''1718210''>PROFESSOR: The</span> <span m=''1719030''>code</span>
  <span m=''1719310''>itself</span> <span m=''1719850''>is</span> <span m=''1720020''>excellent</span>
  <span m=''1720550''>in</span> <span m=''1720650''>terms</span> <span m=''1720940''>of</span>
  <span m=''1721100''>MDS,</span> <span m=''1721800''>the</span> <span m=''1722030''>MDS</span>
  <span m=''1722350''>property.</span> </p><p><span m=''1723010''>AUDIENCE: But</span>
  <span m=''1723422''>why does</span> <span m=''1723834''>MDS</span> <span m=''1724246''>mean
  good codes?</span> </p><p><span m=''1725070''>PROFESSOR: In</span> <span m=''1725510''>respect
  to</span> <span m=''1725950''>modulation?</span> </p><p><span m=''1726696''>AUDIENCE:
  Yes.</span> </p><p><span m=''1727580''>PROFESSOR: It</span> <span m=''1727780''>doesn''t.</span>
  <span m=''1729490''>It</span> <span m=''1729600''>doesn''t.</span> <span m=''1732374''>It''s
  a bit</span> <span m=''1732840''>like</span> <span m=''1733020''>this.</span> <span
  m=''1735390''>It''s</span> <span m=''1735570''>really</span> <span m=''1735800''>not</span>
  <span m=''1736020''>easy</span> <span m=''1736290''>to</span> <span m=''1736480''>define</span>
  <span m=''1736740''>codes</span> <span m=''1737030''>in</span> <span m=''1737070''>Euclidean</span>
  <span m=''1737500''>space.</span> <span m=''1739080''>So</span> <span m=''1739630''>all
  that</span> <span m=''1740080''>we</span> <span m=''1740200''>do</span> <span m=''1741690''>is</span>
  <span m=''1744810''>we</span> <span m=''1744930''>find</span> <span m=''1745290''>ways</span>
  <span m=''1745730''>to</span> <span m=''1745860''>do</span> <span m=''1746130''>that</span>
  <span m=''1746510''>and</span> <span m=''1746690''>guarantee</span> <span m=''1747170''>some</span>
  <span m=''1747520''>performance,</span> <span m=''1749910''>some</span> <span m=''1750250''>sort</span>
  <span m=''1750480''>of</span> <span m=''1750620''>performance.</span> </p><p><span
  m=''1752120''>It''s</span> <span m=''1752370''>not</span> <span m=''1752600''>easy</span>
  <span m=''1752860''>to</span> <span m=''1752990''>spread</span> <span m=''1753380''>out
  --</span> <span m=''1755400''>I</span> <span m=''1755520''>don''t</span> <span m=''1755720''>know
  --</span> <span m=''1755910''>2</span> <span m=''1756110''>to</span> <span m=''1756240''>the</span>
  <span m=''1756360''>1,000</span> <span m=''1756810''>points</span> <span m=''1758110''>in</span>
  <span m=''1761880''>1,500</span> <span m=''1762450''>dimensions.</span> <span m=''1764080''>These</span>
  <span m=''1764230''>would</span> <span m=''1764330''>be</span> <span m=''1764470''>typical</span>
  <span m=''1764820''>numbers</span> <span m=''1765100''>really.</span> <span m=''1769090''>It''s</span>
  <span m=''1769310''>not</span> <span m=''1769500''>easy.</span> <span m=''1771240''>And</span>
  <span m=''1771460''>since</span> <span m=''1771710''>that</span> <span m=''1771960''>problem
  is</span> <span m=''1772460''>practically</span> <span m=''1772900''>daunting,</span>
  <span m=''1774892''>it''s a</span> <span m=''1775350''>daunting</span> <span m=''1775700''>task,</span>
  <span m=''1776990''>you</span> <span m=''1777060''>have</span> <span m=''1777190''>to</span>
  <span m=''1777830''>develop</span> <span m=''1778360''>all</span> <span m=''1778650''>sort
  of</span> <span m=''1779050''>crutches</span> <span m=''1779530''>to</span> <span
  m=''1779630''>do</span> <span m=''1779780''>that.</span> <span m=''1780210''>And</span>
  <span m=''1780410''>this</span> <span m=''1780540''>is</span> <span m=''1780650''>really</span>
  <span m=''1780900''>one.</span> </p><p><span m=''1782290''>So</span> <span m=''1783650''>how</span>
  <span m=''1783830''>to</span> <span m=''1784000''>code</span> <span m=''1784370''>MDS</span>
  <span m=''1784850''>codes</span> <span m=''1786230''>playing</span> <span m=''1786570''>a</span>
  <span m=''1786620''>part</span> <span m=''1786960''>in</span> <span m=''1787090''>this</span>
  <span m=''1787300''>mapping.</span> <span m=''1788120''>If</span> <span m=''1788320''>you</span>
  <span m=''1788450''>want</span> <span m=''1788600''>to</span> <span m=''1788680''>be</span>
  <span m=''1788830''>more</span> <span m=''1789020''>fancy</span> <span m=''1789420''>about</span>
  <span m=''1789720''>that,</span> <span m=''1790570''>then</span> <span m=''1791860''>you</span>
  <span m=''1792010''>put</span> <span m=''1792190''>a</span> <span m=''1792230''>convolutional</span>
  <span m=''1792870''>code</span> <span m=''1793150''>or</span> <span m=''1793210''>some</span>
  <span m=''1793390''>other</span> <span m=''1793620''>code</span> <span m=''1793910''>also</span>
  <span m=''1794220''>in</span> <span m=''1794460''>there</span> <span m=''1795220''>and</span>
  <span m=''1795440''>do</span> <span m=''1795650''>a</span> <span m=''1795890''>combine</span>
  <span m=''1796410''>scheme.</span> <span m=''1799670''>I</span> <span m=''1799790''>think</span>
  <span m=''1799910''>Professor</span> <span m=''1800270''>Forney</span> <span m=''1800520''>will</span>
  <span m=''1800670''>talk</span> <span m=''1800920''>about that</span> <span m=''1801260''>more.</span>
  <span m=''1802910''>So</span> <span m=''1803770''>here, it''s</span> <span m=''1804150''>just
  the</span> <span m=''1804400''>coding</span> <span m=''1804720''>theoretic</span>
  <span m=''1805060''>groundwork</span> <span m=''1806650''>of</span> <span m=''1806750''>these</span>
  <span m=''1807060''>things.</span> <span m=''1810610''>Anything</span> <span m=''1810870''>else?</span>
  <span m=''1811090''>Yeah.</span> </p><p><span m=''1811565''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''1812900''>of the</span> <span m=''1813330''>[INAUDIBLE]</span> <span m=''1813760''>n
  minus 1.</span> <span m=''1815390''>Close,</span> <span m=''1815730''>very</span>
  <span m=''1816070''>close</span> <span m=''1816549''>[INAUDIBLE].</span> </p><p><span
  m=''1817507''>PROFESSOR: Yeah,</span> <span m=''1817986''>thanks.</span> <span m=''1824050''>So</span>
  <span m=''1825420''>the</span> <span m=''1825760''>algorithmic</span> <span m=''1826100''>treatment</span>
  <span m=''1827340''>of</span> <span m=''1827510''>Reed-Solomon</span> <span m=''1827950''>codes</span>
  <span m=''1828515''>is</span> <span m=''1828780''>extremely</span> <span m=''1829420''>elegant.</span>
  <span m=''1829980''>And</span> <span m=''1830110''>that''s</span> <span m=''1831460''>the</span>
  <span m=''1831830''>second</span> <span m=''1832190''>main</span> <span m=''1832430''>reason</span>
  <span m=''1832750''>they are</span> <span m=''1833020''>so</span> <span m=''1833150''>much</span>
  <span m=''1833400''>used.</span> <span m=''1834675''>It</span> <span m=''1835110''>doesn''t</span>
  <span m=''1835340''>cost</span> <span m=''1835670''>so</span> <span m=''1835770''>much</span>
  <span m=''1836080''>to implement</span> <span m=''1836557''>them.</span> <span m=''1837990''>Well,</span>
  <span m=''1838370''>at</span> <span m=''1838430''>least</span> <span m=''1838740''>we''ve</span>
  <span m=''1838900''>seen</span> <span m=''1839070''>that</span> <span m=''1839220''>for</span>
  <span m=''1839350''>the</span> <span m=''1839460''>encoder.</span> <span m=''1840210''>That''s</span>
  <span m=''1840390''>a</span> <span m=''1840430''>fairly</span> <span m=''1840690''>small</span>
  <span m=''1840960''>circuit.</span> </p><p><span m=''1842130''>So</span> <span m=''1842280''>what</span>
  <span m=''1842400''>about</span> <span m=''1842670''>decoding?</span> <span m=''1848950''>Decoding.</span>
  <span m=''1851650''>How</span> <span m=''1851800''>do</span> <span m=''1851920''>we</span>
  <span m=''1852030''>decode</span> <span m=''1852510''>these</span> <span m=''1852890''>things?</span>
  <span m=''1857990''>How</span> <span m=''1858180''>could</span> <span m=''1858340''>we</span>
  <span m=''1858430''>possibly</span> <span m=''1859030''>decode</span> <span m=''1859600''>them?</span>
  <span m=''1860400''>And</span> <span m=''1860580''>I</span> <span m=''1860640''>give</span>
  <span m=''1860860''>you --</span> </p><p><span m=''1862390''>AUDIENCE: Fourier?</span>
  </p><p><span m=''1864840''>PROFESSOR: Right,</span> <span m=''1865110''>that''s
  true.</span> <span m=''1865660''>We</span> <span m=''1865820''>could</span> <span
  m=''1866010''>do</span> <span m=''1866110''>the</span> <span m=''1866210''>Fourier</span>
  <span m=''1866450''>transform.</span> <span m=''1866930''>But</span> <span m=''1867070''>it</span>
  <span m=''1867150''>doesn''t</span> <span m=''1868110''>help</span> <span m=''1868380''>us</span>
  <span m=''1868550''>so</span> <span m=''1868670''>much</span> <span m=''1870240''>because</span>
  <span m=''1871130''>we</span> <span m=''1871290''>receive</span> <span m=''1871510''>something.</span>
  <span m=''1873026''>And</span> <span m=''1874780''>we</span> <span m=''1874950''>receive</span>
  <span m=''1875390''>a</span> <span m=''1875480''>vector,</span> <span m=''1876030''>say,</span>
  <span m=''1876220''>y.</span> <span m=''1880962''>From now</span> <span m=''1881420''>on,</span>
  <span m=''1881765''>let''s say</span> <span m=''1882110''>x</span> <span m=''1882410''>is</span>
  <span m=''1882520''>a</span> <span m=''1882580''>code</span> <span m=''1882830''>word.</span>
  <span m=''1887760''>rs,</span> <span m=''1888253''>right.</span> </p><p><span m=''1888750''>So</span>
  <span m=''1889140''>x,</span> <span m=''1890160''>it''s</span> <span m=''1890260''>usually</span>
  <span m=''1890610''>a</span> <span m=''1890660''>code word</span> <span m=''1891070''>from</span>
  <span m=''1891340''>now on.</span> <span m=''1892590''>So</span> <span m=''1892950''>this</span>
  <span m=''1893180''>is</span> <span m=''1893320''>a</span> <span m=''1893390''>code</span>
  <span m=''1893630''>word</span> <span m=''1894450''>plus</span> <span m=''1894810''>an
  error.</span> <span m=''1897190''>So</span> <span m=''1897560''>in</span> <span
  m=''1897660''>particular,</span> <span m=''1898230''>if</span> <span m=''1898320''>we</span>
  <span m=''1898410''>take</span> <span m=''1898600''>the</span> <span m=''1898670''>Fourier</span>
  <span m=''1898920''>transform,</span> <span m=''1899470''>we</span> <span m=''1899530''>take</span>
  <span m=''1899740''>the</span> <span m=''1899790''>Fourier</span> <span m=''1900260''>transform</span>
  <span m=''1900585''>of the</span> <span m=''1900910''>code word,</span> <span m=''1901170''>which</span>
  <span m=''1901350''>is</span> <span m=''1901490''>fine.</span> <span m=''1902110''>But</span>
  <span m=''1902280''>then</span> <span m=''1902470''>we</span> <span m=''1902550''>get</span>
  <span m=''1902660''>the</span> <span m=''1902770''>Fourier</span> <span m=''1902950''>transform</span>
  <span m=''1903220''>of the</span> <span m=''1903490''>error.</span> <span m=''1903590''>So</span>
  <span m=''1904010''>that</span> <span m=''1905690''>destroys</span> <span m=''1906070''>all</span>
  <span m=''1906180''>the</span> <span m=''1906370''>fun.</span> </p><p><span m=''1909370''>What
  else</span> <span m=''1909660''>could</span> <span m=''1909800''>we</span> <span
  m=''1909910''>do?</span> <span m=''1910110''>Here''s</span> <span m=''1910370''>typical</span>
  <span m=''1910760''>parameters</span> <span m=''1911390''>of</span> <span m=''1911490''>a</span>
  <span m=''1911590''>code.</span> <span m=''1914250''>255,</span> <span m=''1916150''>239,</span>
  <span m=''1919150''>256.</span> <span m=''1921740''>And</span> <span m=''1921870''>you</span>
  <span m=''1921950''>immediately</span> <span m=''1922380''>see</span> <span m=''1922660''>that,</span>
  <span m=''1923110''>OK,</span> <span m=''1923490''>any</span> <span m=''1923740''>sort</span>
  <span m=''1923960''>of</span> <span m=''1924100''>group</span> <span m=''1924320''>force</span>
  <span m=''1924780''>is out.</span> </p><p><span m=''1928820''>How</span> <span m=''1928960''>many</span>
  <span m=''1929190''>code words</span> <span m=''1929540''>do</span> <span m=''1929730''>we</span>
  <span m=''1929960''>have</span> <span m=''1930180''>here?</span> <span m=''1930490''>We
  have</span> <span m=''1930780''>8</span> <span m=''1931160''>to the</span> <span
  m=''1931440''>239</span> <span m=''1932450''>code</span> <span m=''1932770''>words.</span>
  <span m=''1933622''>Now</span> <span m=''1934050''>you</span> <span m=''1934230''>don''t</span>
  <span m=''1934410''>want</span> <span m=''1934530''>to</span> <span m=''1934570''>search</span>
  <span m=''1934940''>that.</span> <span m=''1936042''>You</span> <span m=''1936460''>definitely</span>
  <span m=''1936940''>don''t</span> <span m=''1937190''>want</span> <span m=''1937430''>to
  search</span> <span m=''1937908''>that.</span> </p><p><span m=''1942690''>So</span>
  <span m=''1943270''>how</span> <span m=''1943470''>could</span> <span m=''1943620''>we</span>
  <span m=''1943720''>possibly</span> <span m=''1944290''>decode</span> <span m=''1944670''>these</span>
  <span m=''1945070''>things?</span> <span m=''1948790''>Turns</span> <span m=''1949090''>out,</span>
  <span m=''1949410''>to</span> <span m=''1949530''>decode</span> <span m=''1950030''>them</span>
  <span m=''1950340''>in</span> <span m=''1950480''>some</span> <span m=''1950730''>sort</span>
  <span m=''1950950''>of</span> <span m=''1951070''>optimal</span> <span m=''1951590''>fashion,</span>
  <span m=''1952070''>maximum</span> <span m=''1952480''>likelihood</span> <span m=''1952730''>[INAUDIBLE]</span>
  <span m=''1953160''>actually,</span> <span m=''1953920''>it''s</span> <span m=''1954260''>an</span>
  <span m=''1954600''>NP-hard</span> <span m=''1955150''>problem.</span> <span m=''1957220''>Maybe</span>
  <span m=''1957710''>last</span> <span m=''1958000''>year,</span> <span m=''1958170''>actually,</span>
  <span m=''1958580''>it has been</span> <span m=''1958880''>shown</span> <span m=''1960100''>that</span>
  <span m=''1960440''>it''s</span> <span m=''1960780''>an</span> <span m=''1961140''>NP-hard</span>
  <span m=''1961490''>problem</span> <span m=''1961920''>to</span> <span m=''1962040''>decode</span>
  <span m=''1962460''>Reed-Solomon</span> <span m=''1962720''>codes.</span> <span
  m=''1964190''>It</span> <span m=''1964330''>was</span> <span m=''1964600''>known</span>
  <span m=''1964830''>that</span> <span m=''1964970''>decoding</span> <span m=''1965070''>in</span>
  <span m=''1965490''>general</span> <span m=''1965750''>was</span> <span m=''1966010''>NP-hard.</span>
  <span m=''1967110''>But</span> <span m=''1968030''>this</span> <span m=''1968490''>is</span>
  <span m=''1968740''>now</span> <span m=''1970280''>the</span> <span m=''1970750''>constraint</span>
  <span m=''1971220''>to</span> <span m=''1971310''>Reed-Solomon</span> <span m=''1971930''>codes</span>
  <span m=''1972080''>is</span> <span m=''1972340''>still</span> <span m=''1972560''>hard.</span>
  </p><p><span m=''1975200''>So</span> <span m=''1975350''>what do</span> <span m=''1975490''>we</span>
  <span m=''1975620''>do?</span> <span m=''1976940''>Yes,</span> <span m=''1977790''>OK,</span>
  <span m=''1978210''>what do we</span> <span m=''1978410''>do?</span> <span m=''1979640''>Let''s</span>
  <span m=''1979850''>say</span> <span m=''1980810''>x</span> <span m=''1981070''>is</span>
  <span m=''1981160''>a</span> <span m=''1981220''>code</span> <span m=''1981510''>word.</span>
  <span m=''1981800''>We</span> <span m=''1982300''>know</span> <span m=''1982630''>that.</span>
  <span m=''1985170''>And</span> <span m=''1985260''>set</span> <span m=''1985350''>rate</span>
  <span m=''1986240''>e,</span> <span m=''1988210''>let''s</span> <span m=''1988420''>just</span>
  <span m=''1988610''>call it</span> <span m=''1989085''>t.</span> </p><p><span m=''1996680''>So</span>
  <span m=''1998970''>what</span> <span m=''1999130''>happens</span> <span m=''1999550''>if</span>
  <span m=''1999660''>you</span> <span m=''1999760''>don''t</span> <span m=''2000130''>have</span>
  <span m=''2000520''>an</span> <span m=''2000650''>error?</span> <span m=''2003390''>Just</span>
  <span m=''2003730''>thought</span> <span m=''2003980''>experiment.</span> <span
  m=''2008630''>Thought</span> <span m=''2008870''>experiment,</span> <span m=''2009450''>if</span>
  <span m=''2009520''>you</span> <span m=''2009630''>don''t</span> <span m=''2009940''>have</span>
  <span m=''2010120''>an</span> <span m=''2010230''>error,</span> <span m=''2011700''>then</span>
  <span m=''2013740''>yi</span> <span m=''2014520''>in</span> <span m=''2014850''>all</span>
  <span m=''2015050''>the</span> <span m=''2015130''>positions</span> <span m=''2018180''>is</span>
  <span m=''2018630''>equal</span> <span m=''2019110''>to</span> <span m=''2020656''>F
  of</span> <span m=''2021040''>xi</span> <span m=''2026490''>for</span> <span m=''2026640''>some</span>
  <span m=''2027050''>F</span> <span m=''2027240''>of</span> <span m=''2027390''>x</span>
  <span m=''2028420''>of</span> <span m=''2029230''>degree.</span> <span m=''2039000''>In</span>
  <span m=''2039120''>particular,</span> <span m=''2040750''>since</span> <span m=''2041020''>we</span>
  <span m=''2041130''>know</span> <span m=''2041390''>the</span> <span m=''2041540''>x''s,</span>
  <span m=''2042170''>we</span> <span m=''2042260''>know</span> <span m=''2042520''>the</span>
  <span m=''2042630''>positions --</span> <span m=''2049440''>sorry,</span> <span
  m=''2053066''>oh,</span> <span m=''2053550''>sorry.</span> <span m=''2054600''>That''s</span>
  <span m=''2054830''>not</span> <span m=''2055020''>what</span> <span m=''2055150''>I</span>
  <span m=''2055179''>wanted</span> <span m=''2055460''>to</span> <span m=''2055560''>write.</span>
  <span m=''2057050''>This is</span> <span m=''2057300''>definitely</span> <span m=''2057760''>not</span>
  <span m=''2057969''>what</span> <span m=''2058100''>I</span> <span m=''2058130''>wanted</span>
  <span m=''2058310''>to</span> <span m=''2058489''>write.</span> </p><p><span m=''2061820''>Let''s</span>
  <span m=''2061969''>keep</span> <span m=''2062170''>that as</span> <span m=''2062440''>c</span>
  <span m=''2063430''>as a</span> <span m=''2063840''>code</span> <span m=''2064250''>word</span>
  <span m=''2066520''>and</span> <span m=''2070840''>position</span> <span m=''2073302''>i</span>
  <span m=''2075260''>in</span> <span m=''2076630''>c</span> <span m=''2078600''>is</span>
  <span m=''2078870''>associated</span> <span m=''2083780''>with</span> <span m=''2084130''>xi</span>
  <span m=''2087440''>in</span> <span m=''2088250''>the</span> <span m=''2088310''>fields.</span>
  <span m=''2089679''>So</span> <span m=''2089860''>meaning</span> <span m=''2092721''>ci</span>
  <span m=''2095426''>would</span> <span m=''2095878''>be F</span> <span m=''2096330''>of
  xi.</span> <span m=''2097340''>That''s</span> <span m=''2097620''>really</span>
  <span m=''2097810''>what</span> <span m=''2097960''>I</span> <span m=''2098090''>wanted</span>
  <span m=''2098570''>to</span> <span m=''2098940''>write.</span> <span m=''2099310''>It
  makes</span> <span m=''2099650''>more sense.</span> </p><p><span m=''2101810''>So</span>
  <span m=''2102180''>thought</span> <span m=''2102550''>experiment.</span> <span
  m=''2103710''>No</span> <span m=''2103750''>errors.</span> <span m=''2107080''>Then</span>
  <span m=''2107820''>yi</span> <span m=''2110281''>is</span> <span m=''2110740''>F</span>
  <span m=''2110900''>of</span> <span m=''2111070''>xi</span> <span m=''2111790''>for</span>
  <span m=''2112010''>some</span> <span m=''2112090''>F.</span> <span m=''2113770''>If</span>
  <span m=''2113930''>they</span> <span m=''2114060''>ran no</span> <span m=''2114530''>errors,</span>
  <span m=''2115800''>then</span> <span m=''2116070''>we</span> <span m=''2116170''>could</span>
  <span m=''2116390''>just</span> <span m=''2118050''>solve</span> <span m=''2118410''>this</span>
  <span m=''2118590''>linear</span> <span m=''2118900''>system</span> <span m=''2119290''>of</span>
  <span m=''2119410''>equations</span> <span m=''2121480''>to</span> <span m=''2121580''>find</span>
  <span m=''2121900''>the</span> <span m=''2121990''>coefficient</span> <span m=''2122560''>of</span>
  <span m=''2122650''>F.</span> <span m=''2123916''>And</span> <span m=''2124340''>the</span>
  <span m=''2124390''>coefficient</span> <span m=''2124880''>of</span> <span m=''2125020''>F,</span>
  <span m=''2125920''>say,</span> <span m=''2126200''>were our</span> <span m=''2126520''>information</span>
  <span m=''2127030''>circuits.</span> <span m=''2128286''>Is it</span> <span m=''2128640''>clear</span>
  <span m=''2128880''>that</span> <span m=''2129110''>this</span> <span m=''2129240''>is</span>
  <span m=''2129380''>a</span> <span m=''2129420''>linear</span> <span m=''2129680''>system</span>
  <span m=''2130020''>of</span> <span m=''2130110''>equations?</span> <span m=''2132100''>Yeah?</span>
  </p><p><span m=''2134380''>You</span> <span m=''2134510''>could</span> <span m=''2134650''>write</span>
  <span m=''2134920''>it out</span> <span m=''2135340''>as</span> <span m=''2136530''>y0,</span>
  <span m=''2137320''>y1,</span> <span m=''2137990''>y2</span> <span m=''2140280''>equal</span>
  <span m=''2140410''>to --</span> <span m=''2156490''>and here we</span> <span m=''2156988''>have</span>
  <span m=''2157880''>f0,</span> <span m=''2158140''>f1,</span> <span m=''2158410''>up</span>
  <span m=''2158630''>to</span> <span m=''2158750''>fk-1.</span> <span m=''2161260''>This
  is the</span> <span m=''2161610''>linear</span> <span m=''2162130''>system</span>
  <span m=''2162480''>of</span> <span m=''2162590''>equations.</span> <span m=''2163110''>We</span>
  <span m=''2163200''>know</span> <span m=''2163400''>the</span> <span m=''2163550''>xi''s.</span>
  <span m=''2164510''>This is</span> <span m=''2164670''>a</span> <span m=''2164700''>linear</span>
  <span m=''2164990''>system</span> <span m=''2165330''>of</span> <span m=''2165400''>equation</span>
  <span m=''2165500''>we have</span> <span m=''2165860''>to solve.</span> </p><p><span
  m=''2171170''>If</span> <span m=''2171360''>there</span> <span m=''2171550''>are
  no</span> <span m=''2171940''>errors,</span> <span m=''2172205''>then</span> <span
  m=''2172580''>life</span> <span m=''2172810''>is</span> <span m=''2172930''>easy.</span>
  <span m=''2173560''>That</span> <span m=''2173860''>seems</span> <span m=''2174110''>to</span>
  <span m=''2174220''>be</span> <span m=''2174460''>reasonable.</span> <span m=''2175360''>So</span>
  <span m=''2175570''>what</span> <span m=''2175710''>happens</span> <span m=''2176020''>if</span>
  <span m=''2176130''>we</span> <span m=''2176220''>do</span> <span m=''2176420''>have</span>
  <span m=''2176650''>errors?</span> <span m=''2177820''>Somehow,</span> <span m=''2178290''>we</span>
  <span m=''2178420''>have</span> <span m=''2178600''>to</span> <span m=''2178730''>make</span>
  <span m=''2178940''>sure</span> <span m=''2179750''>that</span> <span m=''2179930''>the</span>
  <span m=''2180070''>errors</span> <span m=''2180570''>that we</span> <span m=''2180910''>get</span>
  <span m=''2183720''>do</span> <span m=''2183810''>not</span> <span m=''2184280''>cause</span>
  <span m=''2185030''>any</span> <span m=''2185230''>problem</span> <span m=''2185730''>for</span>
  <span m=''2185940''>us.</span> <span m=''2187590''>And</span> <span m=''2191136''>then</span>
  <span m=''2191610''>we</span> <span m=''2191730''>do</span> <span m=''2191900''>something</span>
  <span m=''2192330''>very</span> <span m=''2192600''>ingenious.</span> </p><p><span
  m=''2193950''>We</span> <span m=''2194130''>define</span> <span m=''2194420''>something</span>
  <span m=''2194750''>called</span> <span m=''2195050''>an</span> <span m=''2195100''>error</span>
  <span m=''2195360''>locator</span> <span m=''2197450''>which</span> <span m=''2197520''>is</span>
  <span m=''2197730''>a polynomial</span> <span m=''2198570''>x</span> <span m=''2199950''>such</span>
  <span m=''2200410''>that</span> <span m=''2213095''>x</span> <span m=''2213570''>minus</span>
  <span m=''2214045''>xi.</span> <span m=''2215470''>So</span> <span m=''2215670''>it''s</span>
  <span m=''2215840''>a</span> <span m=''2215890''>polynomial</span> <span m=''2217740''>which</span>
  <span m=''2218020''>is</span> <span m=''2218210''>0</span> <span m=''2219680''>in</span>
  <span m=''2219900''>all</span> <span m=''2220360''>error</span> <span m=''2220950''>positions.</span>
  <span m=''2224700''>Well,</span> <span m=''2225200''>you</span> <span m=''2225300''>might</span>
  <span m=''2225530''>say,</span> <span m=''2225670''>we</span> <span m=''2225790''>do</span>
  <span m=''2225910''>not</span> <span m=''2226150''>know</span> <span m=''2226340''>the</span>
  <span m=''2226620''>error</span> <span m=''2226690''>positions.</span> <span m=''2227270''>Well,</span>
  <span m=''2227580''>OK,</span> <span m=''2227830''>that''s</span> <span m=''2228250''>true.</span>
  <span m=''2229750''>Basically,</span> <span m=''2230170''>this</span> <span m=''2230320''>is,</span>
  <span m=''2230450''>in</span> <span m=''2230520''>the</span> <span m=''2230650''>end,</span>
  <span m=''2230780''>what</span> <span m=''2230930''>we</span> <span m=''2231000''>want</span>
  <span m=''2231190''>to</span> <span m=''2231260''>find,</span> <span m=''2232480''>this</span>
  <span m=''2232650''>polynomial.</span> <span m=''2233150''>But</span> <span m=''2233310''>nonetheless,</span>
  <span m=''2233800''>this</span> <span m=''2233960''>polynomial</span> <span m=''2234480''>exists.</span>
  </p><p><span m=''2238080''>We</span> <span m=''2238330''>can</span> <span m=''2238540''>cast,</span>
  <span m=''2238920''>actually,</span> <span m=''2239220''>the</span> <span m=''2239350''>coding</span>
  <span m=''2245060''>problem --</span> <span m=''2245990''>this is</span> <span m=''2246190''>form</span>
  <span m=''2246550''>1</span> <span m=''2248890''>s.</span> <span m=''2252695''>Yes,
  what?</span> </p><p><span m=''2255032''>AUDIENCE: [INAUDIBLE PHRASE].</span> </p><p><span
  m=''2262130''>PROFESSOR: Yeah,</span> <span m=''2262360''>it''s an</span> <span
  m=''2262420''>additive</span> <span m=''2262780''>error</span> <span m=''2263130''>model.</span>
  <span m=''2266510''>But</span> <span m=''2266740''>you</span> <span m=''2266830''>can</span>
  <span m=''2267030''>cast</span> <span m=''2267370''>pretty much</span> <span m=''2267710''>anything</span>
  <span m=''2268020''>in the</span> <span m=''2268330''>[UNINTELLIGIBLE].</span> <span
  m=''2269140''>If</span> <span m=''2269300''>a</span> <span m=''2269470''>position</span>
  <span m=''2269920''>is</span> <span m=''2270040''>altered,</span> <span m=''2270870''>you
  can</span> <span m=''2271170''>always</span> <span m=''2271630''>model</span> <span
  m=''2271960''>that</span> <span m=''2272160''>as</span> <span m=''2272340''>if</span>
  <span m=''2272440''>something</span> <span m=''2272820''>was</span> <span m=''2272990''>added</span>
  <span m=''2273320''>to it.</span> </p><p><span m=''2276480''>Decoding</span> <span
  m=''2276750''>problem</span> <span m=''2277180''>one</span> <span m=''2277430''>is</span>
  <span m=''2280330''>find</span> <span m=''2280910''>lambda</span> <span m=''2282366''>of</span>
  <span m=''2282830''>x</span> <span m=''2283140''>of</span> <span m=''2283320''>minimal</span>
  <span m=''2283800''>degree</span> <span m=''2289670''>such</span> <span m=''2290150''>that</span>
  <span m=''2294000''>lambda</span> <span m=''2294370''>of</span> <span m=''2299180''>xi,</span>
  <span m=''2301480''>is</span> <span m=''2301600''>0</span> <span m=''2303264''>for</span>
  <span m=''2303716''>all</span> <span m=''2304170''>xi</span> <span m=''2306670''>and</span>
  <span m=''2310800''>degree</span> <span m=''2311155''>f</span> <span m=''2313450''>less</span>
  <span m=''2313760''>than</span> <span m=''2314210''>k.</span> <span m=''2315230''>So</span>
  <span m=''2315370''>I</span> <span m=''2315490''>claim</span> <span m=''2315930''>if</span>
  <span m=''2316080''>you</span> <span m=''2316230''>solve</span> <span m=''2316560''>this</span>
  <span m=''2316850''>problem,</span> <span m=''2319670''>namely,</span> <span m=''2321540''>this</span>
  <span m=''2321650''>is a</span> <span m=''2321750''>problem</span> <span m=''2322400''>I</span>
  <span m=''2323360''>give</span> <span m=''2323840''>you.</span> </p><p><span m=''2324570''>I</span>
  <span m=''2324670''>give</span> <span m=''2324900''>you</span> <span m=''2325090''>vector</span>
  <span m=''2325430''>y.</span> <span m=''2327000''>I</span> <span m=''2327100''>give</span>
  <span m=''2327290''>you</span> <span m=''2327460''>vector</span> <span m=''2327780''>y.</span>
  <span m=''2328335''>Here</span> <span m=''2328590''>it is.</span> <span m=''2328890''>Here
  is</span> <span m=''2329130''>vector</span> <span m=''2329420''>y.</span> <span
  m=''2330380''>And</span> <span m=''2330590''>I</span> <span m=''2330640''>give</span>
  <span m=''2330820''>you</span> <span m=''2330990''>vector</span> <span m=''2331330''>x</span>
  <span m=''2332160''>which</span> <span m=''2332470''>corresponds</span> <span m=''2332990''>to
  the</span> <span m=''2333170''>field</span> <span m=''2333500''>elements</span>
  <span m=''2333980''>where you</span> <span m=''2334120''>evaluated</span> <span
  m=''2334850''>that</span> <span m=''2336000''>in order</span> <span m=''2336150''>to</span>
  <span m=''2336310''>get</span> <span m=''2336600''>the</span> <span m=''2336680''>code</span>
  <span m=''2337110''>word.</span> </p><p><span m=''2337540''>And then</span> <span
  m=''2337870''>I said,</span> <span m=''2338430''>given</span> <span m=''2338910''>y</span>
  <span m=''2339440''>and</span> <span m=''2339620''>x,</span> <span m=''2340880''>find</span>
  <span m=''2341480''>two</span> <span m=''2341740''>polynomials</span> <span m=''2342560''>lambda</span>
  <span m=''2342760''>and</span> <span m=''2343240''>f</span> <span m=''2345710''>such</span>
  <span m=''2346005''>that</span> <span m=''2346300''>f</span> <span m=''2346590''>has</span>
  <span m=''2346850''>maximum</span> <span m=''2347340''>degree</span> <span m=''2347700''>k</span>
  <span m=''2348470''>and</span> <span m=''2348750''>lambda</span> <span m=''2349070''>has</span>
  <span m=''2349180''>minimum</span> <span m=''2349590''>degree,</span> <span m=''2350305''>the</span>
  <span m=''2350620''>smaller</span> <span m=''2351060''>degree</span> <span m=''2351380''>possible</span>
  <span m=''2352520''>so</span> <span m=''2352730''>that</span> <span m=''2352890''>this</span>
  <span m=''2353050''>is</span> <span m=''2353240''>true.</span> <span m=''2355360''>And</span>
  <span m=''2355500''>I</span> <span m=''2355540''>claim</span> <span m=''2356620''>this</span>
  <span m=''2356880''>solves the</span> <span m=''2357170''>decoding</span> <span
  m=''2357570''>problem.</span> <span m=''2359140''>This</span> <span m=''2359340''>would</span>
  <span m=''2359560''>solve the</span> <span m=''2359860''>decoding</span> <span m=''2360280''>problem</span>
  <span m=''2361080''>because</span> <span m=''2361900''>once</span> <span m=''2362120''>we</span>
  <span m=''2362190''>have</span> <span m=''2362340''>found</span> <span m=''2362680''>this,</span>
  <span m=''2363160''>then</span> <span m=''2363510''>we</span> <span m=''2363610''>can</span>
  <span m=''2363820''>take</span> <span m=''2364070''>lambda</span> <span m=''2364780''>to</span>
  <span m=''2364910''>be</span> <span m=''2365130''>the</span> <span m=''2365220''>error</span>
  <span m=''2365600''>locator.</span> <span m=''2367140''>And</span> <span m=''2367410''>we</span>
  <span m=''2367500''>can</span> <span m=''2367710''>basically</span> <span m=''2369570''>read</span>
  <span m=''2369860''>off</span> <span m=''2371655''>the</span> <span m=''2371950''>information</span>
  <span m=''2372480''>symbols</span> <span m=''2372860''>from</span> <span m=''2373050''>the</span>
  <span m=''2373200''>f.</span> </p><p><span m=''2375180''>So</span> <span m=''2375350''>this</span>
  <span m=''2375660''>decoding</span> <span m=''2376110''>formulation</span> <span
  m=''2376770''>now</span> <span m=''2377780''>brings</span> <span m=''2378040''>it,</span>
  <span m=''2378170''>at</span> <span m=''2378300''>least,</span> <span m=''2378600''>into</span>
  <span m=''2378810''>the</span> <span m=''2378950''>algebraic</span> <span m=''2379430''>ground,</span>
  <span m=''2381530''>brings</span> <span m=''2381780''>the</span> <span m=''2381880''>whole</span>
  <span m=''2382040''>decoding</span> <span m=''2382430''>problem,</span> <span m=''2382780''>makes</span>
  <span m=''2383040''>it</span> <span m=''2383130''>something</span> <span m=''2383500''>algebraically.</span>
  <span m=''2385072''>But</span> <span m=''2385430''>now</span> <span m=''2385600''>the</span>
  <span m=''2385690''>question</span> <span m=''2385980''>becomes,</span> <span m=''2387050''>is</span>
  <span m=''2387200''>that</span> <span m=''2387370''>easy?</span> <span m=''2389220''>Or</span>
  <span m=''2389330''>can</span> <span m=''2389500''>we</span> <span m=''2389590''>do</span>
  <span m=''2389700''>this?</span> <span m=''2390890''>This</span> <span m=''2391090''>problem</span>
  <span m=''2391355''>here.</span> </p><p><span m=''2394440''>Do</span> <span m=''2394670''>you</span>
  <span m=''2394770''>see</span> <span m=''2394980''>any</span> <span m=''2395170''>hope</span>
  <span m=''2395440''>for</span> <span m=''2395750''>solving</span> <span m=''2396120''>this</span>
  <span m=''2396320''>problem?</span> <span m=''2402270''>I</span> <span m=''2402390''>guess</span>
  <span m=''2402640''>the</span> <span m=''2402820''>only</span> <span m=''2403000''>answer</span>
  <span m=''2404090''>that --</span> <span m=''2405290''>OK,</span> <span m=''2405500''>anybody</span>
  <span m=''2405860''>says</span> <span m=''2406090''>no?</span> <span m=''2406660''>Anybody</span>
  <span m=''2407100''>does</span> <span m=''2407280''>not</span> <span m=''2407530''>see</span>
  <span m=''2407730''>any</span> <span m=''2407940''>hope?</span> <span m=''2410072''>All</span>
  <span m=''2410510''>right.</span> <span m=''2410950''>This</span> <span m=''2411120''>is</span>
  <span m=''2411300''>great.</span> <span m=''2411750''>You</span> <span m=''2411880''>all</span>
  <span m=''2412050''>see</span> <span m=''2412250''>hope</span> <span m=''2412590''>here.</span>
  <span m=''2414940''>You all</span> <span m=''2415210''>see</span> <span m=''2415360''>hope</span>
  <span m=''2415660''>here,</span> <span m=''2415890''>which</span> <span m=''2417510''>seems</span>
  <span m=''2417880''>to</span> <span m=''2418010''>make</span> <span m=''2418230''>you
  an</span> <span m=''2418380''>opportunistic</span> <span m=''2419170''>bunch.</span>
  <span m=''2420166''>Not</span> <span m=''2420612''>opportunistic.</span> <span m=''2421360''>What''s
  the</span> <span m=''2421770''>word?</span> <span m=''2422350''>Optimistic.</span>
  <span m=''2422930''>Optimistic</span> <span m=''2423380''>bunch.</span> </p><p><span
  m=''2426470''>Let''s</span> <span m=''2426950''>put it like</span> <span m=''2427130''>this.</span>
  <span m=''2427270''>What</span> <span m=''2427550''>is</span> <span m=''2427740''>the</span>
  <span m=''2427940''>problem</span> <span m=''2428200''>in</span> <span m=''2428460''>solving</span>
  <span m=''2428890''>this?</span> <span m=''2431991''>It''s not</span> <span m=''2432440''>linear.</span>
  <span m=''2434270''>You</span> <span m=''2434370''>get</span> <span m=''2434610''>the</span>
  <span m=''2434700''>coefficients</span> <span m=''2435330''>of</span> <span m=''2435720''>lambda.</span>
  <span m=''2435890''>Multiply</span> <span m=''2436420''>the</span> <span m=''2436520''>coefficients</span>
  <span m=''2437070''>of</span> <span m=''2437190''>f.</span> <span m=''2438390''>That</span>
  <span m=''2438590''>whole</span> <span m=''2438790''>thing</span> <span m=''2439160''>becomes</span>
  <span m=''2442570''>a</span> <span m=''2442720''>nonlinear</span> <span m=''2443300''>problem,</span>
  <span m=''2444365''>where</span> <span m=''2444680''>we</span> <span m=''2444900''>say</span>
  <span m=''2445170''>in</span> <span m=''2445310''>the</span> <span m=''2445550''>end,</span>
  <span m=''2450000''>find</span> <span m=''2450360''>the</span> <span m=''2450460''>solution</span>
  <span m=''2451010''>to</span> <span m=''2451140''>a</span> <span m=''2451190''>set</span>
  <span m=''2451390''>of</span> <span m=''2451490''>polynomial</span> <span m=''2452090''>equations</span>
  <span m=''2452540''>in</span> <span m=''2452620''>a</span> <span m=''2452690''>field,</span>
  <span m=''2454680''>which</span> <span m=''2455000''>is</span> <span m=''2456670''>a</span>
  <span m=''2456810''>multivariate</span> <span m=''2457400''>polynomial</span> <span
  m=''2458060''>equations,</span> <span m=''2458730''>where</span> <span m=''2458900''>the</span>
  <span m=''2459060''>coefficients</span> <span m=''2459650''>of</span> <span m=''2459760''>lambda</span>
  <span m=''2460250''>and f</span> <span m=''2460530''>are</span> <span m=''2460630''>the</span>
  <span m=''2460730''>variables.</span> </p><p><span m=''2462680''>You</span> <span
  m=''2462820''>can</span> <span m=''2463050''>do</span> <span m=''2463240''>that.</span>
  <span m=''2463540''>You</span> <span m=''2463660''>could</span> <span m=''2463840''>use</span>
  <span m=''2464160''>techniques</span> <span m=''2464670''>like</span> <span m=''2465100''>Grobner</span>
  <span m=''2465220''>basis</span> <span m=''2465720''>or</span> <span m=''2465810''>so,</span>
  <span m=''2466160''>and</span> <span m=''2466300''>you</span> <span m=''2466400''>could</span>
  <span m=''2466600''>do</span> <span m=''2466790''>that.</span> <span m=''2467720''>But</span>
  <span m=''2467890''>this</span> <span m=''2468070''>is</span> <span m=''2468220''>very</span>
  <span m=''2468480''>difficult.</span> <span m=''2469020''>This</span> <span m=''2469300''>is</span>
  <span m=''2470670''>computationally</span> <span m=''2471480''>tedious.</span> </p><p><span
  m=''2475710''>So</span> <span m=''2476400''>is</span> <span m=''2476770''>that</span>
  <span m=''2476980''>clear</span> <span m=''2477300''>why</span> <span m=''2477470''>this</span>
  <span m=''2477670''>is</span> <span m=''2477810''>nonlinear,</span> <span m=''2478270''>and</span>
  <span m=''2478440''>why</span> <span m=''2478630''>this</span> <span m=''2478810''>is</span>
  <span m=''2478930''>hard</span> <span m=''2479100''>to</span> <span m=''2479230''>solve
  a</span> <span m=''2479520''>nonlinear</span> <span m=''2480030''>problem</span>
  <span m=''2480405''>here?</span> <span m=''2484740''>If</span> <span m=''2484860''>not,</span>
  <span m=''2485130''>then</span> <span m=''2485290''>you</span> <span m=''2485360''>have</span>
  <span m=''2485500''>to</span> <span m=''2485620''>say</span> <span m=''2486590''>something</span>
  <span m=''2486970''>now,</span> <span m=''2487340''>or forever</span> <span m=''2487640''>hold</span>
  <span m=''2487830''>your</span> <span m=''2488050''>peace.</span> </p><p><span m=''2496880''>So</span>
  <span m=''2497100''>what</span> <span m=''2497200''>do</span> <span m=''2497310''>we</span>
  <span m=''2497410''>do</span> <span m=''2497570''>with</span> <span m=''2497780''>hard</span>
  <span m=''2497980''>problems?</span> <span m=''2501820''>Once</span> <span m=''2501970''>you</span>
  <span m=''2502100''>take</span> <span m=''2502300''>the</span> <span m=''2502380''>optimization</span>
  <span m=''2502960''>classes,</span> <span m=''2504290''>there''s</span> <span m=''2504440''>almost</span>
  <span m=''2504700''>like</span> <span m=''2504860''>a</span> <span m=''2504920''>reflex,</span>
  <span m=''2505490''>there is</span> <span m=''2505660''>a</span> <span m=''2505910''>relax</span>
  <span m=''2506170''>time.</span> <span m=''2507320''>We</span> <span m=''2507440''>find</span>
  <span m=''2507660''>the</span> <span m=''2507740''>proper</span> <span m=''2508050''>relaxation</span>
  <span m=''2508345''>of the</span> <span m=''2508640''>problem.</span> <span m=''2509870''>Now</span>
  <span m=''2509970''>the</span> <span m=''2510070''>proper</span> <span m=''2510370''>relaxation</span>
  <span m=''2511280''>of</span> <span m=''2511400''>this</span> <span m=''2511610''>problem</span>
  <span m=''2512870''>is</span> <span m=''2512940''>the</span> <span m=''2513010''>following.</span>
  </p><p><span m=''2520690''>Decoding</span> <span m=''2520990''>problem</span> <span
  m=''2521220''>two.</span> <span m=''2523150''>Find</span> <span m=''2526516''>lambda</span>
  <span m=''2526970''>of</span> <span m=''2527300''>x</span> <span m=''2529520''>of</span>
  <span m=''2529570''>minimal</span> <span m=''2529990''>degree</span> <span m=''2536330''>such</span>
  <span m=''2536720''>that --</span> <span m=''2537865''>it''s</span> <span m=''2538290''>almost</span>
  <span m=''2538890''>the</span> <span m=''2538970''>same,</span> <span m=''2539300''>almost</span>
  <span m=''2539840''>the</span> <span m=''2539930''>same --</span> <span m=''2541760''>lambda</span>
  <span m=''2542250''>fi</span> <span m=''2544200''>yi</span> <span m=''2546060''>minus</span>
  <span m=''2546490''>h</span> <span m=''2546820''>of</span> <span m=''2547010''>xi</span>
  <span m=''2548910''>is</span> <span m=''2549170''>0,</span> <span m=''2550060''>where</span>
  <span m=''2552670''>the</span> <span m=''2552730''>degree</span> <span m=''2553250''>of</span>
  <span m=''2553480''>h</span> <span m=''2554800''>is</span> <span m=''2559460''>less</span>
  <span m=''2559860''>than</span> <span m=''2561960''>k</span> <span m=''2562940''>plus</span>
  <span m=''2564940''>degree</span> <span m=''2566085''>lambda.</span> </p><p><span
  m=''2568820''>So</span> <span m=''2569020''>all</span> <span m=''2569240''>that
  we</span> <span m=''2569420''>did</span> <span m=''2570060''>from</span> <span m=''2570310''>this</span>
  <span m=''2570520''>formulation,</span> <span m=''2571340''>which</span> <span m=''2571940''>would</span>
  <span m=''2572210''>give</span> <span m=''2572370''>us</span> <span m=''2572550''>a
  clean</span> <span m=''2572890''>solution</span> <span m=''2573380''>to</span> <span
  m=''2573480''>the</span> <span m=''2573580''>whole</span> <span m=''2573750''>thing,</span>
  <span m=''2575130''>right</span> <span m=''2575290''>now,</span> <span m=''2575440''>we</span>
  <span m=''2575560''>multiply</span> <span m=''2576200''>in</span> <span m=''2576420''>this</span>
  <span m=''2576630''>lambda</span> <span m=''2578820''>which</span> <span m=''2579050''>gives</span>
  <span m=''2579300''>here,</span> <span m=''2579490''>it</span> <span m=''2579760''>keeps</span>
  <span m=''2580280''>the</span> <span m=''2580350''>lambda</span> <span m=''2580710''>times</span>
  <span m=''2581080''>y.</span> <span m=''2582060''>And</span> <span m=''2582200''>here,</span>
  <span m=''2582420''>we</span> <span m=''2582460''>get</span> <span m=''2582620''>a</span>
  <span m=''2582730''>new</span> <span m=''2582880''>polynomial,</span> <span m=''2583460''>lambda</span>
  <span m=''2583810''>times</span> <span m=''2584130''>f,</span> <span m=''2585370''>which</span>
  <span m=''2585550''>now</span> <span m=''2585720''>has</span> <span m=''2585960''>degree</span>
  <span m=''2587000''>at</span> <span m=''2587220''>most</span> <span m=''2587830''>k</span>
  <span m=''2588170''>plus</span> <span m=''2588520''>degree</span> <span m=''2588880''>lambda.</span>
  <span m=''2591800''>And</span> <span m=''2591940''>then</span> <span m=''2592090''>we</span>
  <span m=''2592120''>say,</span> <span m=''2592330''>let''s</span> <span m=''2592990''>instead</span>
  <span m=''2593240''>solve</span> <span m=''2593510''>this</span> <span m=''2593740''>problem.</span>
  <span m=''2595760''>Let''s</span> <span m=''2595950''>solve</span> <span m=''2596190''>this</span>
  <span m=''2596420''>problem.</span> </p><p><span m=''2598130''>In</span> <span m=''2598280''>particular,</span>
  <span m=''2601670''>the</span> <span m=''2602050''>question</span> <span m=''2602470''>now</span>
  <span m=''2602610''>becomes</span> <span m=''2611940''>well,</span> <span m=''2612270''>we</span>
  <span m=''2612380''>do</span> <span m=''2612580''>not</span> <span m=''2612800''>require</span>
  <span m=''2613350''>this</span> <span m=''2613640''>anymore.</span> <span m=''2615000''>In</span>
  <span m=''2615150''>this</span> <span m=''2615340''>relaxed</span> <span m=''2615870''>formulation,</span>
  <span m=''2617240''>we</span> <span m=''2617400''>do</span> <span m=''2617520''>not</span>
  <span m=''2617800''>require</span> <span m=''2618210''>this.</span> <span m=''2619870''>And</span>
  <span m=''2620000''>that</span> <span m=''2620210''>makes</span> <span m=''2620470''>all</span>
  <span m=''2620690''>the</span> <span m=''2620920''>difference.</span> <span m=''2621800''>It</span>
  <span m=''2622250''>makes</span> <span m=''2622560''>a</span> <span m=''2622680''>world
  of</span> <span m=''2623080''>difference</span> <span m=''2623610''>because</span>
  <span m=''2624090''>this</span> <span m=''2624380''>one --</span> <span m=''2625836''>look</span>
  <span m=''2626320''>at it --</span> <span m=''2626700''>it''s</span> <span m=''2626870''>a</span>
  <span m=''2626910''>linear</span> <span m=''2627270''>problem.</span> <span m=''2629470''>It''s</span>
  <span m=''2629630''>a</span> <span m=''2629670''>linear</span> <span m=''2629980''>program.</span>
  </p><p><span m=''2630760''>Why is</span> <span m=''2631170''>it a</span> <span m=''2631190''>linear</span>
  <span m=''2631530''>problem?</span> <span m=''2631880''>Do</span> <span m=''2632230''>you</span>
  <span m=''2632410''>see it''s</span> <span m=''2632680''>a</span> <span m=''2632880''>linear</span>
  <span m=''2632980''>problem?</span> <span m=''2636020''>Could</span> <span m=''2636430''>you</span>
  <span m=''2636520''>write</span> <span m=''2636740''>down</span> <span m=''2636980''>the</span>
  <span m=''2637130''>equation,</span> <span m=''2637620''>the</span> <span m=''2637940''>matrix</span>
  <span m=''2638460''>equation?</span> <span m=''2640180''>It''s pretty</span> <span
  m=''2640460''>straight,</span> <span m=''2640850''>right?</span> <span m=''2644690''>It''s</span>
  <span m=''2645150''>pretty</span> <span m=''2645350''>straight.</span> </p><p><span
  m=''2645730''>You</span> <span m=''2645820''>could,</span> <span m=''2646890''>for</span>
  <span m=''2647050''>example,</span> <span m=''2647550''>write</span> <span m=''2647640''>it</span>
  <span m=''2647830''>like,</span> <span m=''2648815''>here,</span> <span m=''2649220''>a</span>
  <span m=''2649340''>diagonal</span> <span m=''2649870''>matrix</span> <span m=''2653990''>yn.</span>
  <span m=''2656790''>Here,</span> <span m=''2657430''>you</span> <span m=''2657590''>would</span>
  <span m=''2657780''>get</span> <span m=''2658020''>something.</span> <span m=''2666688''>I</span>
  <span m=''2667170''>think</span> <span m=''2667420''>that</span> <span m=''2667580''>seems</span>
  <span m=''2667830''>to</span> <span m=''2667920''>be</span> <span m=''2668100''>all</span>
  <span m=''2668340''>right.</span> <span m=''2675710''>And</span> <span m=''2676140''>here,</span>
  <span m=''2676360''>just</span> <span m=''2676610''>the</span> <span m=''2676790''>evaluation</span>
  <span m=''2677285''>of the</span> <span m=''2677780''>h.</span> <span m=''2679070''>So</span>
  <span m=''2690560''>up to</span> <span m=''2690680''>hk</span> <span m=''2697640''>plus</span>
  <span m=''2698110''>degree</span> <span m=''2698580''>lambda.</span> </p><p><span
  m=''2700330''>That''s</span> <span m=''2700550''>a</span> <span m=''2700580''>linear</span>
  <span m=''2700930''>system</span> <span m=''2701290''>of equations.</span> <span
  m=''2703070''>We can</span> <span m=''2703340''>certainly</span> <span m=''2703720''>solve</span>
  <span m=''2704025''>this.</span> <span m=''2704330''>Well,</span> <span m=''2705370''>we</span>
  <span m=''2705450''>do</span> <span m=''2705580''>not</span> <span m=''2705780''>know</span>
  <span m=''2706040''>really</span> <span m=''2706390''>what</span> <span m=''2706590''>the</span>
  <span m=''2706650''>lambda</span> <span m=''2707120''>is,</span> <span m=''2708190''>what</span>
  <span m=''2708340''>degree</span> <span m=''2708710''>the</span> <span m=''2708790''>lambda</span>
  <span m=''2709220''>has.</span> <span m=''2710180''>But</span> <span m=''2710370''>we''re</span>
  <span m=''2710460''>just</span> <span m=''2710760''>hypothesizing</span> <span m=''2711500''>on</span>
  <span m=''2711750''>all</span> <span m=''2711940''>the</span> <span m=''2712020''>possible</span>
  <span m=''2712410''>degrees.</span> </p><p><span m=''2715920''>Well,</span> <span
  m=''2716110''>we</span> <span m=''2716190''>could</span> <span m=''2716380''>say,</span>
  <span m=''2716700''>OK,</span> <span m=''2717000''>let''s</span> <span m=''2717170''>assume</span>
  <span m=''2717540''>the</span> <span m=''2717630''>degree</span> <span m=''2717930''>lambda</span>
  <span m=''2719140''>is</span> <span m=''2721050''>0.</span> <span m=''2721915''>It''s
  a</span> <span m=''2722250''>constant,</span> <span m=''2723320''>which</span> <span
  m=''2723640''>would be</span> <span m=''2723890''>the</span> <span m=''2723970''>same</span>
  <span m=''2724260''>as</span> <span m=''2724350''>saying</span> <span m=''2724570''>there</span>
  <span m=''2724740''>are</span> <span m=''2724860''>no</span> <span m=''2725000''>errors.</span>
  <span m=''2727520''>Then</span> <span m=''2727640''>we</span> <span m=''2727710''>can</span>
  <span m=''2727870''>look</span> <span m=''2728040''>at</span> <span m=''2728140''>the</span>
  <span m=''2728240''>system</span> <span m=''2728560''>of</span> <span m=''2728690''>equations.</span>
  <span m=''2729120''>Does it</span> <span m=''2729360''>have</span> <span m=''2729460''>a</span>
  <span m=''2729570''>solution?</span> <span m=''2730120''>Well,</span> <span m=''2730410''>yes,</span>
  <span m=''2730720''>no.</span> <span m=''2731380''>If</span> <span m=''2731520''>no,</span>
  <span m=''2731790''>then</span> <span m=''2731910''>we</span> <span m=''2732060''>say,</span>
  <span m=''2732260''>all</span> <span m=''2732430''>right,</span> <span m=''2732600''>let''s</span>
  <span m=''2732760''>assume</span> <span m=''2733170''>it''s</span> <span m=''2733470''>1.</span>
  <span m=''2734300''>Well,</span> <span m=''2734620''>does it</span> <span m=''2734760''>have
  a</span> <span m=''2734900''>solution?</span> <span m=''2735370''>Yes,</span> <span
  m=''2735510''>no.</span> <span m=''2736250''>And</span> <span m=''2736420''>so</span>
  <span m=''2736560''>on.</span> <span m=''2736860''>Then we can</span> <span m=''2737150''>move
  on.</span> </p><p><span m=''2741480''>So</span> <span m=''2741630''>we</span> <span
  m=''2741730''>can</span> <span m=''2741960''>solve</span> <span m=''2742210''>this</span>
  <span m=''2742380''>relaxed</span> <span m=''2742760''>problem.</span> <span m=''2746610''>Does</span>
  <span m=''2746780''>that</span> <span m=''2746930''>help</span> <span m=''2747170''>us?</span>
  <span m=''2748580''>It''s</span> <span m=''2748870''>nice</span> <span m=''2749100''>to</span>
  <span m=''2749220''>solve</span> <span m=''2749420''>a</span> <span m=''2749460''>relaxed</span>
  <span m=''2749960''>problem.</span> <span m=''2750500''>And</span> <span m=''2750640''>in</span>
  <span m=''2750790''>the</span> <span m=''2750970''>end,</span> <span m=''2751150''>we</span>
  <span m=''2751230''>get</span> <span m=''2751450''>two</span> <span m=''2751550''>vectors</span>
  <span m=''2751980''>out</span> <span m=''2752130''>of</span> <span m=''2752270''>it,</span>
  <span m=''2752440''>two</span> <span m=''2752540''>polynomials,</span> <span m=''2755180''>lambda</span>
  <span m=''2755630''>and</span> <span m=''2755830''>h.</span> <span m=''2757620''>Does
  it</span> <span m=''2757900''>really</span> <span m=''2758110''>help</span> <span
  m=''2758380''>us?</span> </p><p><span m=''2762290''>Well,</span> <span m=''2766210''>yes.</span>
  <span m=''2766635''>Why?</span> <span m=''2768390''>Because --</span> <span m=''2769240''>let''s</span>
  <span m=''2769460''>put</span> <span m=''2769590''>it</span> <span m=''2769640''>like</span>
  <span m=''2769840''>this.</span> <span m=''2772930''>We</span> <span m=''2773010''>could</span>
  <span m=''2773210''>easily</span> <span m=''2773630''>check</span> <span m=''2773980''>if</span>
  <span m=''2774140''>this</span> <span m=''2774350''>is</span> <span m=''2774490''>true.</span>
  <span m=''2776960''>Once</span> <span m=''2777190''>we</span> <span m=''2777370''>have</span>
  <span m=''2777560''>our</span> <span m=''2777880''>h,</span> <span m=''2778210''>we</span>
  <span m=''2778280''>can</span> <span m=''2778440''>easily</span> <span m=''2778790''>check</span>
  <span m=''2779100''>if</span> <span m=''2779190''>this</span> <span m=''2779380''>is</span>
  <span m=''2779540''>true.</span> <span m=''2780860''>And</span> <span m=''2781030''>if</span>
  <span m=''2781140''>it</span> <span m=''2781260''>is</span> <span m=''2781470''>true,</span>
  <span m=''2782460''>then</span> <span m=''2782840''>we</span> <span m=''2782940''>have</span>
  <span m=''2783110''>solved</span> <span m=''2783420''>this</span> <span m=''2783620''>problem.</span>
  <span m=''2785760''>If</span> <span m=''2785920''>it</span> <span m=''2786030''>is</span>
  <span m=''2786220''>true,</span> <span m=''2786480''>we have</span> <span m=''2786570''>solved</span>
  <span m=''2786930''>this</span> <span m=''2787110''>problem,</span> <span m=''2788180''>which
  is</span> <span m=''2788380''>the</span> <span m=''2788430''>problem</span> <span
  m=''2788670''>we</span> <span m=''2788800''>wanted</span> <span m=''2789110''>to</span>
  <span m=''2789190''>solve.</span> <span m=''2791350''>Good.</span> </p><p><span
  m=''2800170''>So</span> <span m=''2800370''>is</span> <span m=''2800470''>that</span>
  <span m=''2800620''>all</span> <span m=''2800780''>we</span> <span m=''2800860''>need</span>
  <span m=''2801020''>to</span> <span m=''2801120''>know</span> <span m=''2801280''>about</span>
  <span m=''2801570''>this?</span> <span m=''2810390''>We</span> <span m=''2810540''>want</span>
  <span m=''2810700''>to</span> <span m=''2810790''>give</span> <span m=''2810970''>guarantees.</span>
  <span m=''2811950''>We</span> <span m=''2812030''>want</span> <span m=''2812220''>to</span>
  <span m=''2812320''>give</span> <span m=''2812570''>guarantees</span> <span m=''2812975''>that</span>
  <span m=''2813380''>we</span> <span m=''2813510''>correct</span> <span m=''2813950''>up</span>
  <span m=''2814140''>to</span> <span m=''2814680''>so</span> <span m=''2815020''>many</span>
  <span m=''2815380''>errors,</span> <span m=''2815840''>t</span> <span m=''2816250''>errors,</span>
  <span m=''2816560''>right?</span> <span m=''2819580''>So</span> <span m=''2819770''>we</span>
  <span m=''2819880''>have</span> <span m=''2820040''>to</span> <span m=''2820140''>guarantee</span>
  <span m=''2821460''>that</span> <span m=''2822000''>if</span> <span m=''2822230''>there</span>
  <span m=''2822350''>are</span> <span m=''2822560''>not</span> <span m=''2822780''>more</span>
  <span m=''2822970''>than</span> <span m=''2823160''>t</span> <span m=''2823390''>errors,</span>
  <span m=''2824540''>whatever</span> <span m=''2824870''>t will</span> <span m=''2825240''>turn</span>
  <span m=''2825500''>out</span> <span m=''2825650''>to</span> <span m=''2825740''>be,</span>
  <span m=''2827520''>we</span> <span m=''2827810''>can</span> <span m=''2828050''>guarantee</span>
  <span m=''2828600''>that</span> <span m=''2828780''>A,</span> <span m=''2829590''>we</span>
  <span m=''2829940''>will</span> <span m=''2830090''>find</span> <span m=''2830380''>a</span>
  <span m=''2830430''>solution,</span> <span m=''2832200''>and</span> <span m=''2832460''>B,</span>
  <span m=''2833450''>this</span> <span m=''2833680''>will hold.</span> <span m=''2835570''>So
  two</span> <span m=''2836000''>things</span> <span m=''2836210''>to</span> <span
  m=''2836660''>prove.</span> <span m=''2837815''>Is</span> <span m=''2838200''>that</span>
  <span m=''2838280''>clear?</span> <span m=''2838880''>That we</span> <span m=''2838970''>have</span>
  <span m=''2839090''>to</span> <span m=''2839220''>prove</span> <span m=''2839520''>those</span>
  <span m=''2839740''>two</span> <span m=''2839890''>things?</span> </p><p><span m=''2841360''>So</span>
  <span m=''2843030''>the</span> <span m=''2843170''>first</span> <span m=''2843360''>one</span>
  <span m=''2843550''>first.</span> <span m=''2847430''>When</span> <span m=''2849760''>do</span>
  <span m=''2850020''>we</span> <span m=''2850280''>find</span> <span m=''2852980''>a</span>
  <span m=''2853160''>solution?</span> <span m=''2854970''>And are</span> <span m=''2855230''>we</span>
  <span m=''2855450''>guaranteed</span> <span m=''2855785''>to</span> <span m=''2856120''>find
  it?</span> <span m=''2861200''>Can</span> <span m=''2861490''>we</span> <span m=''2863440''>guarantee</span>
  <span m=''2866240''>the</span> <span m=''2866400''>existence</span> <span m=''2869770''>of</span>
  <span m=''2869930''>a</span> <span m=''2869990''>solution?</span> </p><p><span m=''2875400''>Well,</span>
  <span m=''2876320''>when</span> <span m=''2876500''>can</span> <span m=''2876680''>we</span>
  <span m=''2876760''>do</span> <span m=''2876890''>that?</span> <span m=''2878050''>Let''s</span>
  <span m=''2878260''>look</span> <span m=''2878430''>at</span> <span m=''2878560''>this.</span>
  <span m=''2880390''>These</span> <span m=''2880680''>are</span> <span m=''2881650''>n</span>
  <span m=''2881890''>constraints.</span> <span m=''2885390''>This</span> <span m=''2885570''>is</span>
  <span m=''2885700''>a</span> <span m=''2885770''>system</span> <span m=''2886260''>of</span>
  <span m=''2886330''>linear</span> <span m=''2886620''>equations</span> <span m=''2887190''>with</span>
  <span m=''2887340''>n</span> <span m=''2887550''>constraints.</span> <span m=''2889350''>If</span>
  <span m=''2889520''>the</span> <span m=''2889640''>total</span> <span m=''2889980''>number</span>
  <span m=''2890320''>of</span> <span m=''2890540''>degrees</span> <span m=''2890960''>of</span>
  <span m=''2891050''>freedom</span> <span m=''2891530''>exceeds</span> <span m=''2891990''>n,</span>
  <span m=''2896990''>then</span> <span m=''2897270''>we</span> <span m=''2897420''>are</span>
  <span m=''2897590''>left</span> <span m=''2897850''>with</span> <span m=''2897930''>something</span>
  <span m=''2898360''>non-trivial</span> <span m=''2898900''>after</span> <span m=''2899190''>we
  solve</span> <span m=''2899640''>the system of</span> <span m=''2900090''>equations.</span>
  </p><p><span m=''2901060''>So</span> <span m=''2901250''>what''s</span> <span m=''2901370''>the</span>
  <span m=''2901500''>total</span> <span m=''2901870''>number</span> <span m=''2902830''>of</span>
  <span m=''2903010''>degrees</span> <span m=''2903400''>of</span> <span m=''2903490''>freedom?</span>
  <span m=''2906760''>The</span> <span m=''2906960''>number of</span> <span m=''2907160''>degrees</span>
  <span m=''2907520''>of</span> <span m=''2907610''>freedom --</span> <span m=''2913100''>so</span>
  <span m=''2913480''>we</span> <span m=''2913580''>get</span> <span m=''2913780''>the</span>
  <span m=''2913850''>lambda</span> <span m=''2914860''>as</span> <span m=''2915020''>a</span>
  <span m=''2915080''>degree</span> <span m=''2915330''>of</span> <span m=''2915450''>freedom,</span>
  <span m=''2917760''>so</span> <span m=''2918060''>which is</span> <span m=''2919920''>degree</span>
  <span m=''2920350''>lambda</span> <span m=''2922080''>plus</span> <span m=''2922380''>1.</span>
  <span m=''2924030''>And</span> <span m=''2924270''>the</span> <span m=''2924390''>other</span>
  <span m=''2924570''>one</span> <span m=''2924820''>is</span> <span m=''2926360''>plus
  --</span> <span m=''2929510''>what</span> <span m=''2929660''>is</span> <span m=''2929810''>this</span>
  <span m=''2929910''>one --</span> <span m=''2931910''>plus</span> <span m=''2933470''>k</span>
  <span m=''2933870''>plus</span> <span m=''2935730''>degree</span> <span m=''2937756''>lambda.</span>
  <span m=''2938930''>This</span> <span m=''2939180''>is</span> <span m=''2939290''>the</span>
  <span m=''2939390''>total</span> <span m=''2939720''>number</span> <span m=''2941040''>of</span>
  <span m=''2941220''>degrees</span> <span m=''2942120''>of</span> <span m=''2942200''>freedom</span>
  <span m=''2942640''>here.</span> <span m=''2944140''>And</span> <span m=''2944300''>the</span>
  <span m=''2944390''>reason</span> <span m=''2944780''>is</span> <span m=''2945290''>that</span>
  <span m=''2945510''>this</span> <span m=''2945690''>one</span> <span m=''2945830''>should</span>
  <span m=''2945980''>be</span> <span m=''2946140''>minus</span> <span m=''2946480''>1.</span>
  <span m=''2948550''>Sorry.</span> </p><p><span m=''2951400''>So</span> <span m=''2951560''>this
  is</span> <span m=''2951840''>total</span> <span m=''2952160''>number</span> <span
  m=''2952450''>of</span> <span m=''2952530''>degrees</span> <span m=''2952860''>of</span>
  <span m=''2952960''>freedom.</span> <span m=''2958505''>If</span> <span m=''2958940''>this</span>
  <span m=''2959110''>is</span> <span m=''2959250''>greater</span> <span m=''2959560''>than</span>
  <span m=''2959800''>n,</span> <span m=''2960010''>then</span> <span m=''2960170''>we</span>
  <span m=''2960260''>can</span> <span m=''2960460''>guarantee</span> <span m=''2961010''>the</span>
  <span m=''2961580''>existence</span> <span m=''2961930''>of a</span> <span m=''2962070''>solution,</span>
  <span m=''2962510''>a</span> <span m=''2962570''>nontrivial</span> <span m=''2963110''>solution.</span>
  <span m=''2963445''>Then</span> <span m=''2963780''>this</span> <span m=''2963930''>thing</span>
  <span m=''2964040''>will</span> <span m=''2964335''>have a</span> <span m=''2964630''>solution.</span>
  <span m=''2966690''>It''s</span> <span m=''2966820''>a</span> <span m=''2966860''>homogeneous</span>
  <span m=''2967480''>system</span> <span m=''2967820''>of equations.</span> <span
  m=''2968620''>So the</span> <span m=''2968860''>0</span> <span m=''2969190''>is
  always</span> <span m=''2969570''>a</span> <span m=''2969630''>solution.</span>
  <span m=''2970110''>But</span> <span m=''2970960''>that''s</span> <span m=''2971200''>not</span>
  <span m=''2971360''>much</span> <span m=''2971550''>good to</span> <span m=''2971962''>us.</span>
  </p><p><span m=''2973200''>So</span> <span m=''2973360''>what</span> <span m=''2973480''>do</span>
  <span m=''2973570''>we</span> <span m=''2973670''>get</span> <span m=''2973850''>here?</span>
  <span m=''2975458''>Degree</span> <span m=''2975860''>lambda.</span> <span m=''2977930''>To</span>
  <span m=''2978250''>a degree</span> <span m=''2978520''>lambda</span> <span m=''2979220''>greater</span>
  <span m=''2979570''>than</span> <span m=''2979790''>n</span> <span m=''2980000''>minus</span>
  <span m=''2980350''>k</span> <span m=''2980560''>plus</span> <span m=''2984190''>minus</span>
  <span m=''2984580''>1</span> <span m=''2986510''>or</span> <span m=''2988150''>n</span>
  <span m=''2988340''>minus</span> <span m=''2988780''>k.</span> <span m=''2992470''>So</span>
  <span m=''2992930''>the</span> <span m=''2993060''>degree</span> <span m=''2995181''>lambda</span>
  <span m=''2995680''>greater</span> <span m=''2996030''>than</span> <span m=''2996260''>n</span>
  <span m=''2996490''>minus</span> <span m=''2996930''>k</span> <span m=''2998220''>over</span>
  <span m=''2998460''>2 --</span> <span m=''2998600''>does</span> <span m=''2998770''>that</span>
  <span m=''2998880''>remind</span> <span m=''2999290''>you</span> <span m=''2999410''>of</span>
  <span m=''2999500''>anything</span> <span m=''2999800''>here?</span> <span m=''3004770''>So</span>
  <span m=''3005020''>this</span> <span m=''3005260''>one</span> <span m=''3005560''>is</span>
  <span m=''3009550''>d</span> <span m=''3009770''>minus</span> <span m=''3010220''>1</span>
  <span m=''3011860''>over</span> <span m=''3012100''>2.</span> </p><p><span m=''3014950''>So</span>
  <span m=''3015700''>very</span> <span m=''3015940''>interesting,</span> <span m=''3016460''>right?</span>
  <span m=''3016700''>Once</span> <span m=''3016930''>upon</span> <span m=''3017150''>a</span>
  <span m=''3017210''>time,</span> <span m=''3017550''>you</span> <span m=''3017640''>learned</span>
  <span m=''3017900''>that</span> <span m=''3018540''>if</span> <span m=''3018770''>you</span>
  <span m=''3019000''>make</span> <span m=''3019250''>less</span> <span m=''3019550''>than</span>
  <span m=''3019740''>d/2</span> <span m=''3020460''>errors,</span> <span m=''3021580''>you</span>
  <span m=''3021740''>can</span> <span m=''3021900''>correct</span> <span m=''3022300''>that.</span>
  <span m=''3023760''>Very</span> <span m=''3023900''>nice.</span> <span m=''3024040''>It</span>
  <span m=''3024500''>pops</span> <span m=''3024790''>up</span> <span m=''3024960''>here.</span>
  <span m=''3026780''>It</span> <span m=''3026920''>pops</span> <span m=''3027190''>up</span>
  <span m=''3027370''>here</span> <span m=''3028280''>out</span> <span m=''3028370''>of</span>
  <span m=''3028480''>the</span> <span m=''3028570''>blue.</span> <span m=''3029520''>The</span>
  <span m=''3029680''>reason</span> <span m=''3030040''>that</span> <span m=''3030200''>it</span>
  <span m=''3030300''>pops</span> <span m=''3030570''>up</span> <span m=''3030730''>here</span>
  <span m=''3030930''>is,</span> <span m=''3031040''>of</span> <span m=''3031180''>course,</span>
  <span m=''3031940''>the</span> <span m=''3032040''>same</span> <span m=''3032260''>statement,</span>
  <span m=''3032770''>that</span> <span m=''3032990''>as</span> <span m=''3033120''>long</span>
  <span m=''3033850''>as</span> <span m=''3034080''>we</span> <span m=''3034170''>stay</span>
  <span m=''3034450''>within</span> <span m=''3034740''>d/2</span> <span m=''3035520''>errors,</span>
  <span m=''3036420''>we</span> <span m=''3036570''>are</span> <span m=''3036730''>guaranteed</span>
  <span m=''3037370''>to</span> <span m=''3037510''>be</span> <span m=''3037730''>able</span>
  <span m=''3038010''>to</span> <span m=''3038120''>decode</span> <span m=''3038220''>this.</span>
  <span m=''3041200''>So</span> <span m=''3041440''>this</span> <span m=''3041620''>is</span>
  <span m=''3041760''>one.</span> </p><p><span m=''3042030''>So</span> <span m=''3042150''>we</span>
  <span m=''3042260''>know</span> <span m=''3043530''>this</span> <span m=''3043730''>one</span>
  <span m=''3043900''>was the</span> <span m=''3044300''>number of</span> <span m=''3044700''>errors.</span>
  <span m=''3045630''>If</span> <span m=''3045810''>t</span> <span m=''3046300''>is</span>
  <span m=''3046600''>greater</span> <span m=''3047050''>or</span> <span m=''3047150''>equal</span>
  <span m=''3047420''>than</span> <span m=''3047610''>this,</span> <span m=''3048060''>then
  --</span> <span m=''3058010''>let''s</span> <span m=''3058170''>forget</span> <span
  m=''3058380''>about</span> <span m=''3058550''>the</span> <span m=''3058650''>t.</span>
  <span m=''3061220''>If</span> <span m=''3061410''>you</span> <span m=''3061530''>proceed</span>
  <span m=''3061980''>in</span> <span m=''3062090''>this</span> <span m=''3062200''>algorithm</span>
  <span m=''3062730''>hypothesizing</span> <span m=''3063690''>the</span> <span m=''3063810''>degrees</span>
  <span m=''3064750''>of</span> <span m=''3065120''>lambda,</span> <span m=''3066200''>once</span>
  <span m=''3066460''>we''ve</span> <span m=''3066760''>reached</span> <span m=''3067870''>this</span>
  <span m=''3068140''>number</span> <span m=''3068840''>in</span> <span m=''3068990''>the</span>
  <span m=''3069100''>degree,</span> <span m=''3069470''>there</span> <span m=''3069650''>will</span>
  <span m=''3069790''>be</span> <span m=''3069930''>a</span> <span m=''3070000''>solution.</span>
  <span m=''3071150''>And</span> <span m=''3071500''>we</span> <span m=''3071670''>don''t</span>
  <span m=''3071850''>have</span> <span m=''3072030''>to</span> <span m=''3072120''>go</span>
  <span m=''3072230''>further</span> <span m=''3072390''>than that.</span> <span m=''3076380''>So</span>
  <span m=''3076630''>that''s</span> <span m=''3076840''>the</span> <span m=''3076900''>first</span>
  <span m=''3077220''>one.</span> </p><p><span m=''3078190''>So</span> <span m=''3078370''>the</span>
  <span m=''3078460''>second</span> <span m=''3078810''>thing</span> <span m=''3078980''>we</span>
  <span m=''3079100''>have</span> <span m=''3079230''>to</span> <span m=''3079340''>prove</span>
  <span m=''3079720''>is</span> <span m=''3081400''>that --</span> <span m=''3081880''>I</span>
  <span m=''3082225''>shouldn''t</span> <span m=''3082570''>have done</span> <span
  m=''3082740''>this --</span> <span m=''3089190''>that</span> <span m=''3089380''>for</span>
  <span m=''3089510''>some</span> <span m=''3089840''>t --</span> <span m=''3090320''>Yeah?</span>
  </p><p><span m=''3090784''>AUDIENCE: [INAUDIBLE]</span> <span m=''3093104''>standard
  degree</span> <span m=''3093568''>of freedom</span> <span m=''3094032''>or less</span>
  <span m=''3094496''>constraints?</span> </p><p><span m=''3096360''>PROFESSOR: You</span>
  <span m=''3096800''>want</span> <span m=''3096990''>to</span> <span m=''3097060''>guarantee</span>
  <span m=''3097510''>a</span> <span m=''3097570''>solution.</span> <span m=''3098310''>If</span>
  <span m=''3098450''>you</span> <span m=''3098550''>have</span> <span m=''3098650''>more</span>
  <span m=''3098980''>constraints</span> <span m=''3100150''>than</span> <span m=''3100300''>degrees</span>
  <span m=''3100650''>of</span> <span m=''3100750''>freedom,</span> <span m=''3101170''>then,</span>
  <span m=''3101750''>since it''s</span> <span m=''3102170''>homogeneous,</span> <span
  m=''3102820''>you</span> <span m=''3103360''>usually</span> <span m=''3103780''>would</span>
  <span m=''3103920''>be</span> <span m=''3104060''>stuck</span> <span m=''3104460''>with</span>
  <span m=''3104630''>a</span> <span m=''3104670''>zero</span> <span m=''3104980''>solution.</span>
  <span m=''3105490''>Everything''s</span> <span m=''3105810''>0,</span> <span m=''3107430''>which</span>
  <span m=''3107670''>is</span> <span m=''3108070''>no</span> <span m=''3108360''>good</span>
  <span m=''3108530''>to</span> <span m=''3108660''>us.</span> <span m=''3109520''>It</span>
  <span m=''3109660''>solves</span> <span m=''3110070''>this</span> <span m=''3110280''>problem,</span>
  <span m=''3111610''>but</span> <span m=''3111810''>it</span> <span m=''3111900''>doesn''t</span>
  <span m=''3112150''>give</span> <span m=''3112300''>us</span> <span m=''3112410''>any</span>
  <span m=''3112510''>information.</span> <span m=''3115305''>Is that</span> <span
  m=''3115730''>all</span> <span m=''3116130''>right?</span> </p><p><span m=''3120066''>AUDIENCE:
  Why does</span> <span m=''3120558''>it have to</span> <span m=''3121050''>be the</span>
  <span m=''3121542''>condition</span> <span m=''3122034''>that</span> <span m=''3122526''>degrees
  of</span> <span m=''3123018''>freedom</span> <span m=''3123510''>has to  be</span>
  <span m=''3124002''>greater</span> <span m=''3124494''>than the</span> <span m=''3124986''>constraints?</span>
  </p><p><span m=''3126970''>PROFESSOR: No, no,</span> <span m=''3128090''>the</span>
  <span m=''3128210''>degrees</span> <span m=''3128570''>of</span> <span m=''3128690''>freedom
  --</span> <span m=''3129400''>well,</span> <span m=''3130460''>OK,</span> <span
  m=''3131700''>it''s</span> <span m=''3131980''>true.</span> <span m=''3133460''>We</span>
  <span m=''3133650''>could</span> <span m=''3133830''>get</span> <span m=''3133970''>lucky.</span>
  <span m=''3136580''>We</span> <span m=''3136660''>could</span> <span m=''3136800''>have</span>
  <span m=''3136940''>redundancy</span> <span m=''3137590''>in</span> <span m=''3137700''>this</span>
  <span m=''3137810''>system</span> <span m=''3138190''>of equations.</span> <span
  m=''3140030''>And</span> <span m=''3140220''>if</span> <span m=''3140320''>we</span>
  <span m=''3140410''>get</span> <span m=''3140600''>lucky,</span> <span m=''3141680''>that''s</span>
  <span m=''3142980''>just</span> <span m=''3143280''>for the</span> <span m=''3143450''>better.</span>
  </p><p><span m=''3144780''>And</span> <span m=''3144880''>actually,</span> <span
  m=''3145150''>you</span> <span m=''3145260''>can</span> <span m=''3145450''>show</span>
  <span m=''3145810''>that</span> <span m=''3146890''>you</span> <span m=''3147010''>do</span>
  <span m=''3147270''>get</span> <span m=''3147490''>lucky</span> <span m=''3148260''>if</span>
  <span m=''3149000''>very</span> <span m=''3149260''>few</span> <span m=''3149460''>errors</span>
  <span m=''3149790''>happen.</span> <span m=''3151250''>Then</span> <span m=''3151600''>this</span>
  <span m=''3151800''>would</span> <span m=''3151920''>have</span> <span m=''3152080''>low</span>
  <span m=''3152280''>rank.</span> <span m=''3154260''>You</span> <span m=''3154350''>can</span>
  <span m=''3154530''>show</span> <span m=''3154790''>that.</span> <span m=''3155370''>But</span>
  <span m=''3156390''>short of</span> <span m=''3156500''>knowing</span> <span m=''3156910''>much,</span>
  <span m=''3157350''>we</span> <span m=''3157450''>want</span> <span m=''3157630''>to</span>
  <span m=''3158770''>guarantee --</span> <span m=''3159430''>I</span> <span m=''3159680''>just</span>
  <span m=''3159990''>want,</span> <span m=''3160200''>at</span> <span m=''3160330''>this</span>
  <span m=''3160510''>point</span> <span m=''3160730''>in</span> <span m=''3160810''>time,</span>
  <span m=''3161010''>to</span> <span m=''3161120''>guarantee</span> <span m=''3162000''>that</span>
  <span m=''3162280''>there</span> <span m=''3162380''>is</span> <span m=''3162600''>a</span>
  <span m=''3162670''>solution.</span> <span m=''3164370''>There</span> <span m=''3164580''>is</span>
  <span m=''3164710''>a</span> <span m=''3164790''>non-zero</span> <span m=''3165330''>solution</span>
  <span m=''3165810''>to</span> <span m=''3165920''>this</span> <span m=''3166150''>system</span>
  <span m=''3166530''>of</span> <span m=''3166650''>equations,</span> <span m=''3167590''>and</span>
  <span m=''3167830''>the</span> <span m=''3167940''>degree</span> <span m=''3168550''>of</span>
  <span m=''3168730''>lambda</span> <span m=''3169690''>is</span> <span m=''3169870''>not</span>
  <span m=''3170150''>more</span> <span m=''3170350''>than</span> <span m=''3170560''>d</span>
  <span m=''3170710''>minus</span> <span m=''3171040''>1</span> <span m=''3171260''>over</span>
  <span m=''3171450''>2.</span> <span m=''3173460''>There</span> <span m=''3173700''>is</span>
  <span m=''3173790''>a</span> <span m=''3173870''>solution</span> <span m=''3174610''>with</span>
  <span m=''3174810''>a</span> <span m=''3174870''>degree</span> <span m=''3175280''>of</span>
  <span m=''3175390''>lambda</span> <span m=''3175750''>being</span> <span m=''3176310''>upper</span>
  <span m=''3176690''>bounded</span> <span m=''3177015''>by this.</span> </p><p><span
  m=''3178324''>AUDIENCE: So</span> <span m=''3178816''>[INAUDIBLE]</span> <span m=''3179800''>less</span>
  <span m=''3180292''>constraints?</span> </p><p><span m=''3181280''>PROFESSOR: Yeah,</span>
  <span m=''3181550''>no,</span> <span m=''3182035''>no.</span> <span m=''3186550''>Once</span>
  <span m=''3186810''>this</span> <span m=''3186960''>is</span> <span m=''3187070''>satisfied,</span>
  <span m=''3188010''>I</span> <span m=''3188170''>guarantee</span> <span m=''3188660''>you</span>
  <span m=''3188780''>there is</span> <span m=''3189020''>a</span> <span m=''3189090''>solution.</span>
  <span m=''3190260''>That</span> <span m=''3190420''>means,</span> <span m=''3190720''>the</span>
  <span m=''3190820''>smallest</span> <span m=''3191310''>solution</span> <span m=''3193310''>is</span>
  <span m=''3193500''>guaranteed</span> <span m=''3194130''>not</span> <span m=''3194340''>to</span>
  <span m=''3194420''>be</span> <span m=''3194540''>larger</span> <span m=''3194840''>than</span>
  <span m=''3195000''>that.</span> <span m=''3199090''>But</span> <span m=''3199190''>there
  are,</span> <span m=''3199460''>of</span> <span m=''3199730''>course,</span> <span
  m=''3199940''>many,</span> <span m=''3200150''>many</span> <span m=''3200380''>more</span>
  <span m=''3200570''>larger</span> <span m=''3200910''>solutions.</span> <span m=''3201570''>There
  are</span> <span m=''3201730''>many</span> <span m=''3201900''>solutions</span>
  <span m=''3202350''>of</span> <span m=''3202450''>larger</span> <span m=''3202770''>degree</span>
  <span m=''3203180''>here,</span> <span m=''3205043''>which</span> <span m=''3205496''>we
  are</span> <span m=''3205950''>not</span> <span m=''3206110''>interested</span>
  <span m=''3206550''>in</span> <span m=''3206670''>since</span> <span m=''3206790''>we</span>
  <span m=''3206910''>are</span> <span m=''3207120''>interested</span> <span m=''3207550''>in</span>
  <span m=''3207640''>the</span> <span m=''3207750''>minimal</span> <span m=''3208080''>degree.</span>
  <span m=''3210370''>So</span> <span m=''3210510''>this</span> <span m=''3210700''>is</span>
  <span m=''3210820''>an</span> <span m=''3211140''>upper</span> <span m=''3211210''>bound</span>
  <span m=''3211570''>on</span> <span m=''3211670''>the</span> <span m=''3211780''>minimal</span>
  <span m=''3212190''>degree</span> <span m=''3212510''>lambda.</span> </p><p><span
  m=''3217200''>So</span> <span m=''3217460''>now</span> <span m=''3217680''>the</span>
  <span m=''3217820''>other</span> <span m=''3218010''>one.</span> <span m=''3218300''>So</span>
  <span m=''3222690''>now</span> <span m=''3222890''>we</span> <span m=''3223070''>want</span>
  <span m=''3223250''>to</span> <span m=''3224000''>make</span> <span m=''3224290''>the</span>
  <span m=''3224360''>statement</span> <span m=''3224790''>about</span> <span m=''3225060''>this</span>
  <span m=''3225290''>one</span> <span m=''3225470''>here.</span> <span m=''3226630''>When</span>
  <span m=''3226950''>can</span> <span m=''3227120''>we</span> <span m=''3227290''>guarantee</span>
  <span m=''3230540''>that</span> <span m=''3230710''>our</span> <span m=''3230950''>relaxation</span>
  <span m=''3231720''>didn''t</span> <span m=''3231960''>matter?</span> <span m=''3232990''>Despite</span>
  <span m=''3233355''>our</span> <span m=''3233720''>relaxation,</span> <span m=''3234890''>our</span>
  <span m=''3235080''>solution</span> <span m=''3235500''>that</span> <span m=''3235620''>we</span>
  <span m=''3235730''>find</span> <span m=''3236455''>that</span> <span m=''3236730''>in</span>
  <span m=''3236930''>the</span> <span m=''3237070''>solution</span> <span m=''3237430''>that</span>
  <span m=''3237540''>we</span> <span m=''3237650''>find</span> <span m=''3237970''>lambda</span>
  <span m=''3238370''>divides</span> <span m=''3238650''>h.</span> <span m=''3240110''>How
  can</span> <span m=''3240240''>we</span> <span m=''3240350''>guarantee</span> <span
  m=''3240780''>this?</span> <span m=''3243430''>So</span> <span m=''3243690''>how</span>
  <span m=''3243810''>can</span> <span m=''3243980''>we</span> <span m=''3244140''>guarantee</span>
  <span m=''3244290''>this?</span> <span m=''3244860''>How can</span> <span m=''3245145''>we</span>
  <span m=''3245430''>guarantee</span> <span m=''3245550''>this?</span> </p><p><span
  m=''3250080''>Let''s</span> <span m=''3250320''>look</span> <span m=''3250510''>at</span>
  <span m=''3252460''>lambda</span> <span m=''3254590''>xi</span> <span m=''3255470''>yi</span>
  <span m=''3257540''>minus</span> <span m=''3257950''>h</span> <span m=''3258210''>of</span>
  <span m=''3258350''>xi.</span> <span m=''3260310''>And</span> <span m=''3260520''>we</span>
  <span m=''3260680''>know</span> <span m=''3261340''>this</span> <span m=''3261640''>is</span>
  <span m=''3261770''>0</span> <span m=''3262080''>for</span> <span m=''3262390''>all</span>
  <span m=''3262820''>xi.</span> <span m=''3264610''>We</span> <span m=''3264900''>know</span>
  <span m=''3265140''>that.</span> </p><p><span m=''3269210''>We</span> <span m=''3269370''>know</span>
  <span m=''3269620''>that</span> <span m=''3269810''>this</span> <span m=''3270100''>guy</span>
  <span m=''3270380''>here</span> <span m=''3275370''>can</span> <span m=''3275560''>actually</span>
  <span m=''3275880''>be</span> <span m=''3276030''>written</span> <span m=''3276360''>as</span>
  <span m=''3276490''>ci</span> <span m=''3278180''>plus</span> <span m=''3278780''>ei</span>
  <span m=''3282190''>minus</span> <span m=''3282640''>h</span> <span m=''3282960''>of</span>
  <span m=''3283130''>xi.</span> <span m=''3287690''>This</span> <span m=''3287940''>is</span>
  <span m=''3288190''>just</span> <span m=''3288470''>expanding</span> <span m=''3288970''>this</span>
  <span m=''3289230''>guy.</span> <span m=''3290040''>We</span> <span m=''3290180''>also</span>
  <span m=''3290450''>know</span> <span m=''3290780''>that</span> <span m=''3290920''>we</span>
  <span m=''3291060''>can</span> <span m=''3291280''>write</span> <span m=''3291620''>lambda</span>
  <span m=''3293150''>xi</span> <span m=''3295020''>times</span> <span m=''3295400''>ci</span>
  <span m=''3296250''>alone</span> <span m=''3298270''>minus</span> <span m=''3300790''>f</span>
  <span m=''3301250''>of</span> <span m=''3301930''>xi</span> <span m=''3305588''>lambda</span>
  <span m=''3306520''>xi.</span> <span m=''3308051''>This is 0.</span> <span m=''3308520''>We</span>
  <span m=''3308730''>know</span> <span m=''3308910''>that</span> <span m=''3309070''>this</span>
  <span m=''3309210''>is</span> <span m=''3309360''>true</span> <span m=''3309590''>too.</span>
  </p><p><span m=''3310932''>AUDIENCE: For</span> <span m=''3311393''>some f.</span>
  </p><p><span m=''3312780''>PROFESSOR: For</span> <span m=''3312910''>some</span>
  <span m=''3313160''>f.</span> <span m=''3313320''>The</span> <span m=''3313440''>text
  is</span> <span m=''3313900''>to f,</span> <span m=''3315050''>so</span> <span m=''3315240''>that</span>
  <span m=''3315440''>this</span> <span m=''3315650''>is</span> <span m=''3315780''>true</span>
  <span m=''3316050''>too.</span> <span m=''3317220''>Then</span> <span m=''3318740''>let''s</span>
  <span m=''3319010''>just</span> <span m=''3319630''>subtract</span> <span m=''3320150''>these</span>
  <span m=''3320380''>two</span> <span m=''3320500''>guys.</span> <span m=''3322500''>Let''s</span>
  <span m=''3322670''>just</span> <span m=''3322880''>subtract</span> <span m=''3323360''>these</span>
  <span m=''3323600''>two</span> <span m=''3323950''>things</span> <span m=''3324310''>here.</span>
  <span m=''3325480''>And</span> <span m=''3325750''>then</span> <span m=''3327580''>we</span>
  <span m=''3327750''>know</span> <span m=''3328170''>that</span> <span m=''3331690''>lambda</span>
  <span m=''3331940''>xi</span> <span m=''3334260''>times</span> <span m=''3334660''>ei
  --</span> <span m=''3336460''>so</span> <span m=''3336640''>the</span> <span m=''3336760''>first</span>
  <span m=''3337090''>two</span> <span m=''3337430''>cancel --</span> <span m=''3338250''>minus</span>
  <span m=''3338780''>h</span> <span m=''3339070''>of</span> <span m=''3339230''>xi</span>
  <span m=''3342030''>minus</span> <span m=''3349750''>So</span> <span m=''3349960''>we</span>
  <span m=''3350070''>know</span> <span m=''3350290''>this</span> <span m=''3350480''>is</span>
  <span m=''3350630''>true</span> <span m=''3350860''>too.</span> </p><p><span m=''3351646''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''3353550''>PROFESSOR: Yeah,</span> <span m=''3354030''>sorry.</span>
  <span m=''3356210''>Just</span> <span m=''3356430''>in</span> <span m=''3356500''>time.</span>
  <span m=''3361220''>So</span> <span m=''3361410''>what</span> <span m=''3361740''>can
  we</span> <span m=''3361890''>learn</span> <span m=''3362040''>from</span> <span
  m=''3362260''>this?</span> <span m=''3362480''>So</span> <span m=''3362750''>what</span>
  <span m=''3362910''>is</span> <span m=''3363000''>the</span> <span m=''3363050''>degree</span>
  <span m=''3363410''>of</span> <span m=''3363530''>this?</span> <span m=''3365510''>What</span>
  <span m=''3365730''>is</span> <span m=''3365830''>the</span> <span m=''3365920''>degree</span>
  <span m=''3366280''>of</span> <span m=''3366700''>this?</span> </p><p><span m=''3367780''>Well,</span>
  <span m=''3367970''>this</span> <span m=''3368220''>guy</span> <span m=''3368450''>here
  --</span> <span m=''3369570''>we''ll</span> <span m=''3369830''>write it</span>
  <span m=''3370080''>somewhere</span> <span m=''3370320''>else --</span> <span m=''3397550''>well,</span>
  <span m=''3397850''>this</span> <span m=''3398110''>guy</span> <span m=''3398770''>had</span>
  <span m=''3399310''>degree</span> <span m=''3400870''>h</span> <span m=''3401310''>was</span>
  <span m=''3401620''>less</span> <span m=''3401900''>than</span> <span m=''3402080''>n</span>
  <span m=''3402270''>minus</span> <span m=''3402710''>k</span> <span m=''3404940''>plus</span>
  <span m=''3407320''>degree</span> <span m=''3407860''>lambda</span> <span m=''3413470''>less</span>
  <span m=''3413660''>than</span> <span m=''3413830''>k</span> <span m=''3415810''>plus</span>
  <span m=''3416050''>degree</span> <span m=''3416360''>lambda.</span> <span m=''3417310''>That''s</span>
  <span m=''3417980''>because</span> <span m=''3418320''>we</span> <span m=''3418410''>set</span>
  <span m=''3418650''>up</span> <span m=''3418830''>that</span> <span m=''3419030''>problem</span>
  <span m=''3419370''>that</span> <span m=''3419610''>way.</span> </p><p><span m=''3420760''>And</span>
  <span m=''3420990''>we</span> <span m=''3421110''>know</span> <span m=''3421500''>that</span>
  <span m=''3421760''>this</span> <span m=''3422010''>guy</span> <span m=''3430240''>degree</span>
  <span m=''3430570''>lambda.</span> <span m=''3433780''>We</span> <span m=''3433880''>know</span>
  <span m=''3434110''>that.</span> <span m=''3435740''>So</span> <span m=''3435990''>this</span>
  <span m=''3436240''>whole</span> <span m=''3436440''>thing,</span> <span m=''3437690''>let''s</span>
  <span m=''3437910''>call</span> <span m=''3438130''>it</span> <span m=''3438310''>S.</span>
  <span m=''3441150''>We</span> <span m=''3441300''>know</span> <span m=''3447450''>it''s</span>
  <span m=''3447510''>0</span> <span m=''3448160''>for</span> <span m=''3448390''>degree</span>
  <span m=''3449930''>S</span> <span m=''3450720''>less</span> <span m=''3451160''>than</span>
  <span m=''3454220''>degree</span> <span m=''3455140''>lambda.</span> </p><p><span
  m=''3459080''>So</span> <span m=''3459340''>why</span> <span m=''3459590''>does</span>
  <span m=''3459750''>that</span> <span m=''3459890''>help</span> <span m=''3460140''>us?</span>
  <span m=''3461730''>Well,</span> <span m=''3463720''>let''s</span> <span m=''3463900''>look</span>
  <span m=''3464080''>at</span> <span m=''3464210''>the</span> <span m=''3464300''>vector.</span>
  <span m=''3464740''>Now</span> <span m=''3464890''>let''s</span> <span m=''3465140''>look</span>
  <span m=''3465290''>at</span> <span m=''3465400''>all</span> <span m=''3465580''>the</span>
  <span m=''3465760''>positions.</span> <span m=''3468060''>Let''s</span> <span m=''3468250''>look</span>
  <span m=''3468470''>at</span> <span m=''3468640''>the</span> <span m=''3468750''>vector</span>
  <span m=''3471340''>where</span> <span m=''3471930''>we</span> <span m=''3472040''>had,</span>
  <span m=''3472450''>in</span> <span m=''3472650''>the</span> <span m=''3472760''>vector,</span>
  <span m=''3473220''>we have</span> <span m=''3473380''>lambda</span> <span m=''3475910''>xi</span>
  <span m=''3476510''>ei.</span> </p><p><span m=''3482620''>And</span> <span m=''3482910''>now</span>
  <span m=''3483160''>the</span> <span m=''3483250''>fundamental</span> <span m=''3483780''>question.</span>
  <span m=''3485480''>What</span> <span m=''3486150''>is</span> <span m=''3486250''>the</span>
  <span m=''3486360''>rate</span> <span m=''3486670''>of</span> <span m=''3486820''>this</span>
  <span m=''3487040''>vector?</span> <span m=''3489450''>At</span> <span m=''3489650''>most?</span>
  <span m=''3493400''>What''s</span> <span m=''3493830''>the</span> <span m=''3493920''>rate</span>
  <span m=''3494140''>of</span> <span m=''3494290''>this</span> <span m=''3494430''>guy</span>
  <span m=''3494680''>at most?</span> <span m=''3498883''>It''s 12</span> <span m=''3499350''>seconds,</span>
  <span m=''3499960''>[UNINTELLIGIBLE]?</span> <span m=''3505740''>Well,</span> <span
  m=''3505980''>the</span> <span m=''3506130''>rate</span> <span m=''3508030''>of</span>
  <span m=''3508230''>this</span> <span m=''3508480''>vector --</span> <span m=''3517030''>it''s</span>
  <span m=''3517250''>definitely</span> <span m=''3517770''>not</span> <span m=''3517950''>more</span>
  <span m=''3518140''>than</span> <span m=''3518320''>the</span> <span m=''3518410''>rate</span>
  <span m=''3518620''>of</span> <span m=''3518700''>the</span> <span m=''3518940''>error.</span>
  <span m=''3520410''>Because</span> <span m=''3520870''>every</span> <span m=''3521140''>time</span>
  <span m=''3521370''>the error</span> <span m=''3521700''>is</span> <span m=''3521800''>0,</span>
  <span m=''3522080''>the</span> <span m=''3522360''>rate</span> <span m=''3522560''>drops</span>
  <span m=''3522840''>out.</span> <span m=''3524260''>That''s</span> <span m=''3524410''>at</span>
  <span m=''3524550''>most</span> <span m=''3524910''>t.</span> </p><p><span m=''3528890''>What</span>
  <span m=''3529170''>is</span> <span m=''3529240''>the</span> <span m=''3529340''>rate</span>
  <span m=''3529580''>of</span> <span m=''3529680''>this</span> <span m=''3529920''>vector?</span>
  <span m=''3532660''>So</span> <span m=''3532940''>here</span> <span m=''3533210''>we</span>
  <span m=''3533300''>have</span> <span m=''3534295''>a</span> <span m=''3534620''>vector</span>
  <span m=''3535030''>on</span> <span m=''3535220''>the</span> <span m=''3535450''>other</span>
  <span m=''3535670''>side,</span> <span m=''3538500''>S of</span> <span m=''3538670''>xi,</span>
  <span m=''3540692''>a</span> <span m=''3541170''>vector</span> <span m=''3541570''>on</span>
  <span m=''3541780''>the</span> <span m=''3541950''>other</span> <span m=''3542120''>side.</span>
  <span m=''3544240''>What''s</span> <span m=''3544400''>the</span> <span m=''3544550''>rate</span>
  <span m=''3544750''>of</span> <span m=''3544840''>this</span> <span m=''3545120''>guy?</span>
  <span m=''3548790''>That''s</span> <span m=''3549030''>just</span> <span m=''3549280''>the</span>
  <span m=''3549350''>polynomial</span> <span m=''3550000''>of</span> <span m=''3550240''>degree</span>
  <span m=''3550630''>at</span> <span m=''3550800''>most</span> <span m=''3552420''>k</span>
  <span m=''3552830''>plus</span> <span m=''3553280''>degree</span> <span m=''3553810''>lambda</span>
  <span m=''3553950''>minus</span> <span m=''3554330''>1.</span> <span m=''3555640''>So</span>
  <span m=''3555900''>we</span> <span m=''3556040''>have</span> <span m=''3556280''>that</span>
  <span m=''3556510''>the</span> <span m=''3556650''>rate</span> <span m=''3556985''>of</span>
  <span m=''3559810''>this</span> <span m=''3560230''>vector</span> <span m=''3564239''>is</span>
  <span m=''3564720''>n</span> <span m=''3565070''>minus</span> <span m=''3567210''>k</span>
  <span m=''3568250''>plus</span> <span m=''3569940''>degree</span> <span m=''3570180''>lambda</span>
  <span m=''3571900''>minus</span> <span m=''3572270''>1</span> <span m=''3572800''>plus</span>
  <span m=''3573160''>1</span> <span m=''3574720''>because of</span> <span m=''3574890''>the
  minus.</span> </p><p><span m=''3575617''>AUDIENCE: Greater than</span> <span m=''3576064''>or
  equal</span> <span m=''3576511''>to?</span> </p><p><span m=''3579230''>PROFESSOR:
  It''s</span> <span m=''3579470''>greater</span> <span m=''3579780''>than</span>
  <span m=''3580090''>or equal,</span> <span m=''3580482''>sorry.</span> <span m=''3581660''>Otherwise,</span>
  <span m=''3582020''>I</span> <span m=''3582170''>would</span> <span m=''3582290''>have</span>
  <span m=''3582370''>been</span> <span m=''3582530''>in</span> <span m=''3582590''>trouble</span>
  <span m=''3582870''>in</span> <span m=''3583020''>a</span> <span m=''3583070''>second</span>
  <span m=''3583325''>here.</span> <span m=''3586350''>Yeah,</span> <span m=''3586670''>so</span>
  <span m=''3587120''>what</span> <span m=''3587260''>does</span> <span m=''3587390''>that</span>
  <span m=''3587570''>mean?</span> <span m=''3587800''>So</span> <span m=''3588180''>actually,</span>
  <span m=''3588450''>this</span> <span m=''3588660''>one</span> <span m=''3588890''>is</span>
  <span m=''3589030''>nice</span> <span m=''3589280''>to</span> <span m=''3589380''>rewrite</span>
  <span m=''3589830''>is</span> <span m=''3589920''>equal</span> <span m=''3590170''>to</span>
  <span m=''3590360''>d</span> <span m=''3591460''>n</span> <span m=''3591710''>minus</span>
  <span m=''3591970''>t</span> <span m=''3592220''>plus</span> <span m=''3592400''>1</span>
  <span m=''3593960''>d --</span> <span m=''3595865''>I</span> <span m=''3596260''>really
  should</span> <span m=''3596565''>have done</span> <span m=''3596870''>it</span>
  <span m=''3597100''>like</span> <span m=''3597320''>this</span> <span m=''3599028''>in
  order</span> <span m=''3599430''>not to --</span> <span m=''3600320''>it''s</span>
  <span m=''3600740''>d</span> <span m=''3602430''>minus</span> <span m=''3604166''>degree</span>
  <span m=''3604650''>lambda.</span> </p><p><span m=''3608230''>So</span> <span m=''3608430''>what
  can</span> <span m=''3608780''>we</span> <span m=''3608900''>learn</span> <span
  m=''3609060''>from</span> <span m=''3609260''>that?</span> <span m=''3612960''>So</span>
  <span m=''3615250''>we</span> <span m=''3615380''>know</span> <span m=''3615730''>this</span>
  <span m=''3615930''>is</span> <span m=''3616100''>true</span> <span m=''3616920''>for</span>
  <span m=''3617060''>all</span> <span m=''3617240''>the</span> <span m=''3617300''>positions.</span>
  <span m=''3619300''>So</span> <span m=''3619450''>if</span> <span m=''3619650''>this</span>
  <span m=''3619900''>is</span> <span m=''3620100''>true</span> <span m=''3620360''>for
  all</span> <span m=''3620660''>positions,</span> <span m=''3622110''>then --</span>
  <span m=''3624060''>so</span> <span m=''3624680''>if</span> <span m=''3626380''>d</span>
  <span m=''3626710''>minus</span> <span m=''3627140''>degree</span> <span m=''3627570''>lambda
  --</span> <span m=''3630070''>actually,</span> <span m=''3630430''>this</span> <span
  m=''3630630''>is</span> <span m=''3631360''>t</span> <span m=''3632340''>because</span>
  <span m=''3632800''>the</span> <span m=''3632970''>rate</span> <span m=''3633210''>was</span>
  <span m=''3633410''>defined.</span> <span m=''3634480''>t</span> <span m=''3634730''>was</span>
  <span m=''3634950''>the</span> <span m=''3635030''>number</span> <span m=''3635320''>of</span>
  <span m=''3635480''>errors.</span> <span m=''3637250''>And</span> <span m=''3637370''>the</span>
  <span m=''3637490''>error</span> <span m=''3637795''>locator</span> <span m=''3638160''>was</span>
  <span m=''3638350''>just defined</span> <span m=''3638930''>to</span> <span m=''3639050''>have</span>
  <span m=''3639190''>degree</span> <span m=''3639530''>t.</span> <span m=''3643650''>Right?</span>
  </p><p><span m=''3645390''>The</span> <span m=''3645840''>error</span> <span m=''3645960''>locator</span>
  <span m=''3646200''>was</span> <span m=''3646370''>just</span> <span m=''3647430''>x</span>
  <span m=''3647680''>minus</span> <span m=''3647940''>xi</span> <span m=''3648380''>over
  all</span> <span m=''3648810''>positions</span> <span m=''3649480''>where</span>
  <span m=''3649660''>we</span> <span m=''3649740''>had</span> <span m=''3649880''>an</span>
  <span m=''3650000''>error,</span> <span m=''3650470''>so</span> <span m=''3650690''>there</span>
  <span m=''3650890''>are</span> <span m=''3651090''>t of</span> <span m=''3651230''>those</span>
  <span m=''3651450''>positions.</span> <span m=''3651950''>The</span> <span m=''3652040''>degree</span>
  <span m=''3652440''>of</span> <span m=''3652550''>lambda</span> <span m=''3652870''>is</span>
  <span m=''3652980''>equal</span> <span m=''3653200''>to</span> <span m=''3653340''>t.</span>
  <span m=''3655550''>So</span> <span m=''3655690''>now</span> <span m=''3655840''>we</span>
  <span m=''3655920''>take</span> <span m=''3656190''>this.</span> <span m=''3656490''>If</span>
  <span m=''3656760''>d</span> <span m=''3657050''>minus</span> <span m=''3657880''>t</span>
  <span m=''3659760''>is</span> <span m=''3660730''>greater</span> <span m=''3661310''>than</span>
  <span m=''3661660''>t,</span> <span m=''3665840''>so</span> <span m=''3666090''>if</span>
  <span m=''3666350''>the</span> <span m=''3666550''>rate</span> <span m=''3666930''>of</span>
  <span m=''3667120''>this</span> <span m=''3667410''>vector</span> <span m=''3670360''>is</span>
  <span m=''3670560''>greater</span> <span m=''3671000''>than</span> <span m=''3671260''>the</span>
  <span m=''3671360''>rate</span> <span m=''3671640''>of</span> <span m=''3671770''>this</span>
  <span m=''3672040''>vector,</span> <span m=''3673500''>then</span> <span m=''3673660''>we</span>
  <span m=''3673720''>have</span> <span m=''3673890''>a</span> <span m=''3673930''>problem</span>
  <span m=''3675420''>because</span> <span m=''3675770''>that</span> <span m=''3675930''>cannot</span>
  <span m=''3676290''>be.</span> <span m=''3678030''>Of course,</span> <span m=''3678300''>by</span>
  <span m=''3678470''>this</span> <span m=''3678640''>identity,</span> <span m=''3679170''>the</span>
  <span m=''3679290''>rate</span> <span m=''3679540''>of</span> <span m=''3679640''>these</span>
  <span m=''3679840''>two</span> <span m=''3679990''>vectors</span> <span m=''3680480''>is</span>
  <span m=''3680600''>equal.</span> <span m=''3682520''>So what</span> <span m=''3682560''>is
  the</span> <span m=''3682700''>way</span> <span m=''3682920''>out?</span> <span
  m=''3686660''>What''s</span> <span m=''3686820''>the</span> <span m=''3686980''>way</span>
  <span m=''3687150''>out?</span> </p><p><span m=''3687550''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''3693286''>PROFESSOR: Yeah.</span> <span m=''3693770''>So</span>
  <span m=''3695370''>if</span> <span m=''3695570''>this</span> <span m=''3695830''>is</span>
  <span m=''3696040''>true,</span> <span m=''3698970''>then</span> <span m=''3703550''>S</span>
  <span m=''3705226''>of</span> <span m=''3705610''>xi</span> <span m=''3707120''>I</span>
  <span m=''3707260''>claim</span> <span m=''3707670''>has</span> <span m=''3707940''>to</span>
  <span m=''3708050''>be</span> <span m=''3708180''>0</span> <span m=''3710140''>and</span>
  <span m=''3713090''>lambda</span> <span m=''3714510''>of</span> <span m=''3714850''>xi</span>
  <span m=''3715450''>times</span> <span m=''3715880''>ei</span> <span m=''3717290''>has</span>
  <span m=''3717570''>to</span> <span m=''3717690''>be</span> <span m=''3717840''>0</span>
  <span m=''3718230''>too</span> <span m=''3720200''>for</span> <span m=''3720640''>all
  i.</span> <span m=''3723860''>That''s</span> <span m=''3724120''>the</span> <span
  m=''3724320''>only</span> <span m=''3724510''>way</span> <span m=''3724670''>out</span>
  <span m=''3724940''>of</span> <span m=''3725060''>this.</span> <span m=''3726460''>Because,</span>
  <span m=''3727330''>obviously,</span> <span m=''3727790''>this</span> <span m=''3727980''>was</span>
  <span m=''3728160''>allowed.</span> </p><p><span m=''3728760''>If</span> <span m=''3728920''>we</span>
  <span m=''3729030''>really</span> <span m=''3729300''>did</span> <span m=''3729570''>find</span>
  <span m=''3729890''>what</span> <span m=''3730050''>we</span> <span m=''3730140''>wanted</span>
  <span m=''3730360''>to</span> <span m=''3730570''>find,</span> <span m=''3731310''>namely,</span>
  <span m=''3731650''>an</span> <span m=''3731760''>error</span> <span m=''3732125''>locator</span>
  <span m=''3732490''>here,</span> <span m=''3733970''>then</span> <span m=''3734380''>this</span>
  <span m=''3734570''>vector --</span> <span m=''3735530''>we</span> <span m=''3735620''>said</span>
  <span m=''3735850''>it</span> <span m=''3735940''>has</span> <span m=''3736120''>to</span>
  <span m=''3736210''>be</span> <span m=''3736350''>less</span> <span m=''3736590''>than</span>
  <span m=''3736790''>t.</span> <span m=''3737410''>It</span> <span m=''3737750''>can</span>
  <span m=''3737960''>be</span> <span m=''3738080''>less.</span> <span m=''3738570''>In</span>
  <span m=''3738680''>particular,</span> <span m=''3738780''>it</span> <span m=''3738970''>can</span>
  <span m=''3739150''>be</span> <span m=''3739220''>0</span> <span m=''3741920''>if</span>
  <span m=''3742140''>this</span> <span m=''3742320''>is,</span> <span m=''3742460''>indeed,</span>
  <span m=''3742750''>an</span> <span m=''3742850''>error</span> <span m=''3743020''>locator.</span>
  <span m=''3744710''>And</span> <span m=''3745690''>if</span> <span m=''3745990''>our</span>
  <span m=''3746280''>relaxation</span> <span m=''3747040''>didn''t</span> <span m=''3747360''>matter
  --</span> <span m=''3748820''>that</span> <span m=''3749000''>means</span> <span
  m=''3749650''>the</span> <span m=''3750020''>h</span> <span m=''3750520''>that</span>
  <span m=''3750690''>we</span> <span m=''3750810''>find</span> <span m=''3752720''>factors</span>
  <span m=''3753010''>as</span> <span m=''3753440''>that --</span> <span m=''3754800''>if</span>
  <span m=''3754980''>the</span> <span m=''3755100''>relaxation</span> <span m=''3755680''>didn''t</span>
  <span m=''3755960''>matter,</span> <span m=''3756720''>then</span> <span m=''3756900''>S</span>
  <span m=''3757120''>would</span> <span m=''3757280''>be</span> <span m=''3757410''>0</span>
  <span m=''3757720''>too.</span> <span m=''3758480''>So</span> <span m=''3758590''>that
  is</span> <span m=''3758940''>a</span> <span m=''3759000''>fair</span> <span m=''3759220''>solution.</span>
  <span m=''3759830''>That''s</span> <span m=''3760060''>a</span> <span m=''3760110''>possibility.</span>
  </p><p><span m=''3761970''>And</span> <span m=''3762280''>if</span> <span m=''3763090''>d</span>
  <span m=''3763250''>minus</span> <span m=''3763730''>t</span> <span m=''3764080''>is</span>
  <span m=''3764270''>greater</span> <span m=''3764610''>than</span> <span m=''3764830''>t,</span>
  <span m=''3766950''>then</span> <span m=''3767740''>this</span> <span m=''3768000''>proves</span>
  <span m=''3768280''>this</span> <span m=''3768450''>is</span> <span m=''3768560''>the</span>
  <span m=''3768740''>only</span> <span m=''3768910''>solution</span> <span m=''3769370''>that</span>
  <span m=''3769440''>is</span> <span m=''3769610''>feasible.</span> <span m=''3771300''>That''s</span>
  <span m=''3771430''>the</span> <span m=''3771540''>only</span> <span m=''3771710''>solution</span>
  <span m=''3772130''>you have.</span> <span m=''3774180''>So</span> <span m=''3774670''>what</span>
  <span m=''3774860''>that</span> <span m=''3775060''>means</span> <span m=''3775380''>is</span>
  <span m=''3776850''>if</span> <span m=''3777140''>t</span> <span m=''3778810''>less</span>
  <span m=''3779280''>than</span> <span m=''3779520''>t/2,</span> <span m=''3782930''>then</span>
  <span m=''3783350''>the</span> <span m=''3783480''>relaxation</span> <span m=''3789760''>doesn''t</span>
  <span m=''3790110''>matter</span> <span m=''3793850''>and</span> <span m=''3794910''>h</span>
  <span m=''3795220''>of</span> <span m=''3795360''>xi</span> <span m=''3796690''>is</span>
  <span m=''3796870''>equal</span> <span m=''3797270''>to</span> <span m=''3799410''>lambda</span>
  <span m=''3799650''>of</span> <span m=''3800040''>xi</span> <span m=''3800320''>times</span>
  <span m=''3800600''>f of</span> <span m=''3801084''>xi.</span> </p><p><span m=''3812600''>So</span>
  <span m=''3812940''>is that</span> <span m=''3813240''>clear?</span> <span m=''3815040''>That''s</span>
  <span m=''3815240''>two</span> <span m=''3815570''>very</span> <span m=''3815860''>simple,</span>
  <span m=''3817760''>yet</span> <span m=''3819190''>nice</span> <span m=''3820980''>ways</span>
  <span m=''3821300''>to prove</span> <span m=''3821700''>things.</span> <span m=''3824380''>Here,</span>
  <span m=''3824490''>we</span> <span m=''3824590''>guarantee</span> <span m=''3825250''>the</span>
  <span m=''3825310''>solution.</span> <span m=''3829450''>Here, we</span> <span m=''3829680''>guarantee</span>
  <span m=''3830210''>the</span> <span m=''3830270''>solution.</span> <span m=''3831610''>Here,</span>
  <span m=''3831770''>we</span> <span m=''3831970''>guarantee</span> <span m=''3832540''>that</span>
  <span m=''3832740''>solution</span> <span m=''3833200''>is</span> <span m=''3833300''>correct,</span>
  <span m=''3834920''>namely,</span> <span m=''3835330''>if</span> <span m=''3835820''>not</span>
  <span m=''3836140''>too</span> <span m=''3836350''>many</span> <span m=''3836710''>errors</span>
  <span m=''3837060''>happen,</span> <span m=''3838020''>if</span> <span m=''3838290''>less</span>
  <span m=''3838560''>than</span> <span m=''3838750''>t/2</span> <span m=''3839420''>errors</span>
  <span m=''3839760''>happens,</span> <span m=''3842250''>then</span> <span m=''3842650''>relaxing</span>
  <span m=''3843290''>the</span> <span m=''3843490''>original</span> <span m=''3843980''>problem</span>
  <span m=''3844480''>here</span> <span m=''3846010''>to</span> <span m=''3846180''>this</span>
  <span m=''3846370''>other</span> <span m=''3846590''>form,</span> <span m=''3847010''>which</span>
  <span m=''3847220''>we</span> <span m=''3847320''>could</span> <span m=''3847510''>solve,</span>
  <span m=''3848170''>does</span> <span m=''3848360''>not</span> <span m=''3848550''>change</span>
  <span m=''3848930''>the</span> <span m=''3849010''>solution.</span> <span m=''3851690''>That''s</span>
  <span m=''3851950''>what''s</span> <span m=''3852060''>proved</span> <span m=''3852340''>there.</span>
  </p><p><span m=''3856960''>But</span> <span m=''3858816''>about</span> <span m=''3859310''>one-third</span>
  <span m=''3860070''>looks</span> <span m=''3860310''>puzzled.</span> <span m=''3861270''>About</span>
  <span m=''3861460''>half</span> <span m=''3861890''>looks</span> <span m=''3862080''>puzzled,</span>
  <span m=''3862330''>I</span> <span m=''3862430''>would</span> <span m=''3862730''>think.</span>
  <span m=''3869490''>Half</span> <span m=''3869760''>looks</span> <span m=''3870090''>puzzled.</span>
  <span m=''3870900''>Is</span> <span m=''3871090''>there</span> <span m=''3871180''>any
  way</span> <span m=''3871410''>I</span> <span m=''3871460''>can</span> <span m=''3871690''>explain</span>
  <span m=''3872040''>that</span> <span m=''3872210''>better?</span> <span m=''3873870''>Think.</span>
  </p><p><span m=''3882790''>Let''s</span> <span m=''3882960''>just</span> <span m=''3883130''>go</span>
  <span m=''3883260''>through</span> <span m=''3883470''>the</span> <span m=''3883550''>steps</span>
  <span m=''3884480''>quickly.</span> <span m=''3886980''>We</span> <span m=''3887090''>had</span>
  <span m=''3888340''>problem</span> <span m=''3888700''>number</span> <span m=''3888940''>one.</span>
  <span m=''3890640''>Problem</span> <span m=''3890980''>number</span> <span m=''3891260''>one,</span>
  <span m=''3892240''>which</span> <span m=''3892540''>is</span> <span m=''3892650''>a</span>
  <span m=''3892720''>nonlinear</span> <span m=''3893300''>problem,</span> <span m=''3894470''>but</span>
  <span m=''3894670''>you</span> <span m=''3895200''>see</span> <span m=''3896350''>that</span>
  <span m=''3896690''>if</span> <span m=''3896900''>you</span> <span m=''3897000''>could</span>
  <span m=''3897210''>solve</span> <span m=''3897610''>this,</span> <span m=''3898590''>you</span>
  <span m=''3898690''>could</span> <span m=''3898860''>solve</span> <span m=''3899170''>the</span>
  <span m=''3899260''>decoding</span> <span m=''3899670''>problem.</span> <span m=''3901800''>So</span>
  <span m=''3901970''>you</span> <span m=''3902070''>see</span> <span m=''3902290''>that.</span>
  <span m=''3903760''>Anybody</span> <span m=''3904010''>who</span> <span m=''3904080''>doesn''t</span>
  <span m=''3904380''>see</span> <span m=''3904520''>that?</span> <span m=''3906760''>All</span>
  <span m=''3906930''>right.</span> <span m=''3907090''>You''re smart</span> <span
  m=''3907480''>guys.</span> </p><p><span m=''3911130''>If</span> <span m=''3911300''>we</span>
  <span m=''3911380''>can</span> <span m=''3911550''>solve</span> <span m=''3911840''>problem</span>
  <span m=''3912130''>number</span> <span m=''3912370''>one,</span> <span m=''3912860''>we</span>
  <span m=''3913180''>are home</span> <span m=''3913390''>free.</span> <span m=''3913740''>We</span>
  <span m=''3913840''>have</span> <span m=''3913980''>solved</span> <span m=''3914170''>the</span>
  <span m=''3914350''>decoding</span> <span m=''3914570''>problem.</span> <span m=''3915300''>Fine,</span>
  <span m=''3915610''>we</span> <span m=''3915700''>cannot</span> <span m=''3916180''>solve
  it.</span> <span m=''3916270''>It''s a</span> <span m=''3916520''>nonlinear</span>
  <span m=''3917080''>problem.</span> <span m=''3917640''>Well,</span> <span m=''3917870''>we
  can</span> <span m=''3917980''>solve it</span> <span m=''3918490''>in</span> <span
  m=''3918690''>exponential</span> <span m=''3919270''>time,</span> <span m=''3920130''>but</span>
  <span m=''3920510''>that''s</span> <span m=''3921110''>little</span> <span m=''3921180''>fun.</span>
  <span m=''3923410''>So</span> <span m=''3923590''>we</span> <span m=''3923730''>relax</span>
  <span m=''3924025''>it.</span> </p><p><span m=''3924320''>We relax</span> <span
  m=''3924670''>it</span> <span m=''3925160''>into</span> <span m=''3926190''>problem</span>
  <span m=''3926540''>number</span> <span m=''3926850''>two.</span> <span m=''3928730''>All
  that</span> <span m=''3929100''>we</span> <span m=''3929180''>do,</span> <span m=''3929350''>we</span>
  <span m=''3929510''>multiply</span> <span m=''3929970''>things</span> <span m=''3930300''>out.</span>
  <span m=''3931444''>And</span> <span m=''3932680''>we</span> <span m=''3933790''>do</span>
  <span m=''3933900''>not</span> <span m=''3934280''>require,</span> <span m=''3936810''>once</span>
  <span m=''3937040''>we</span> <span m=''3937110''>solve</span> <span m=''3937450''>the</span>
  <span m=''3937510''>problem,</span> <span m=''3937910''>this</span> <span m=''3938010''>anymore.</span>
  <span m=''3946530''>Now</span> <span m=''3946710''>we</span> <span m=''3946820''>have</span>
  <span m=''3947300''>solved</span> <span m=''3947720''>this</span> <span m=''3947890''>problem.</span>
  <span m=''3948490''>We</span> <span m=''3948590''>have</span> <span m=''3948710''>solved</span>
  <span m=''3949050''>this</span> <span m=''3949220''>linear</span> <span m=''3949510''>system</span>
  <span m=''3949840''>of</span> <span m=''3949910''>equations.</span> <span m=''3951520''>And</span>
  <span m=''3952400''>after</span> <span m=''3952720''>doing</span> <span m=''3953100''>so,</span>
  <span m=''3954670''>we</span> <span m=''3954770''>have</span> <span m=''3955000''>found</span>
  <span m=''3955430''>lambda</span> <span m=''3957510''>and</span> <span m=''3957740''>h.</span>
  <span m=''3959640''>They are</span> <span m=''3959970''>lying</span> <span m=''3960320''>on</span>
  <span m=''3960450''>the</span> <span m=''3960550''>table</span> <span m=''3960930''>and</span>
  <span m=''3961050''>looking</span> <span m=''3961340''>at</span> <span m=''3961450''>us.</span>
  </p><p><span m=''3962470''>Now</span> <span m=''3962890''>what?</span> <span m=''3963610''>Are</span>
  <span m=''3963780''>they</span> <span m=''3963950''>any</span> <span m=''3964020''>good?</span>
  <span m=''3964820''>In</span> <span m=''3965310''>particular,</span> <span m=''3966070''>since</span>
  <span m=''3967150''>a priori</span> <span m=''3967690''>we</span> <span m=''3967820''>cannot</span>
  <span m=''3968120''>guarantee</span> <span m=''3968610''>that</span> <span m=''3968810''>this</span>
  <span m=''3968950''>relaxation</span> <span m=''3969560''>didn''t</span> <span m=''3969940''>completely</span>
  <span m=''3970420''>destroy</span> <span m=''3970850''>everything.</span> <span
  m=''3973170''>We have</span> <span m=''3973470''>solved</span> <span m=''3973770''>the</span>
  <span m=''3973840''>system.</span> <span m=''3974410''>Now</span> <span m=''3974670''>those</span>
  <span m=''3974920''>two</span> <span m=''3975050''>things</span> <span m=''3975370''>are</span>
  <span m=''3975440''>lying</span> <span m=''3975780''>on</span> <span m=''3975900''>the</span>
  <span m=''3975990''>table,</span> <span m=''3976330''>looking</span> <span m=''3976680''>at</span>
  <span m=''3976810''>us,</span> <span m=''3977040''>and</span> <span m=''3977170''>asking,</span>
  <span m=''3977940''>what</span> <span m=''3978110''>am</span> <span m=''3978290''>I?</span>
  <span m=''3979650''>And</span> <span m=''3980050''>in</span> <span m=''3980150''>general,</span>
  <span m=''3981330''>if</span> <span m=''3981520''>there''s</span> <span m=''3981740''>an</span>
  <span m=''3981830''>arbitrary</span> <span m=''3982340''>amount</span> <span m=''3982700''>of</span>
  <span m=''3982960''>errors</span> <span m=''3983380''>happening</span> <span m=''3984590''>near</span>
  <span m=''3984770''>the</span> <span m=''3984870''>channel,</span> <span m=''3986940''>actually,</span>
  <span m=''3987430''>they</span> <span m=''3987610''>do</span> <span m=''3987740''>not</span>
  <span m=''3987940''>mean</span> <span m=''3988180''>much.</span> <span m=''3989340''>They</span>
  <span m=''3989440''>do</span> <span m=''3989560''>not</span> <span m=''3989780''>mean</span>
  <span m=''3990000''>much.</span> </p><p><span m=''3992900''>But</span> <span m=''3993570''>now</span>
  <span m=''3993870''>I</span> <span m=''3993980''>claim</span> <span m=''3994360''>that,</span>
  <span m=''3995020''>well,</span> <span m=''3995410''>if</span> <span m=''3995590''>not</span>
  <span m=''3995830''>too</span> <span m=''3996000''>many</span> <span m=''3996330''>errors</span>
  <span m=''3996700''>happened,</span> <span m=''3998286''>but</span> <span m=''3998770''>if</span>
  <span m=''3998950''>the</span> <span m=''3999050''>number</span> <span m=''3999370''>of</span>
  <span m=''3999490''>errors</span> <span m=''3999800''>is</span> <span m=''3999940''>bounded</span>
  <span m=''4001980''>to</span> <span m=''4002120''>be</span> <span m=''4002310''>this,</span>
  <span m=''4003000''>less</span> <span m=''4003320''>than</span> <span m=''4003490''>half</span>
  <span m=''4003770''>the</span> <span m=''4003920''>minimum</span> <span m=''4004340''>distance,</span>
  <span m=''4005710''>then,</span> <span m=''4006130''>actually,</span> <span m=''4006440''>I</span>
  <span m=''4006540''>claim</span> <span m=''4007260''>it</span> <span m=''4007420''>did</span>
  <span m=''4007610''>not</span> <span m=''4007890''>matter</span> <span m=''4008240''>if</span>
  <span m=''4008380''>we</span> <span m=''4008550''>solved</span> <span m=''4008840''>the</span>
  <span m=''4008890''>relaxation</span> <span m=''4009790''>or</span> <span m=''4009870''>the</span>
  <span m=''4009950''>original</span> <span m=''4010360''>problem.</span> <span m=''4012260''>And</span>
  <span m=''4012400''>the</span> <span m=''4012530''>argument</span> <span m=''4013010''>is</span>
  <span m=''4013100''>roughly</span> <span m=''4013470''>this.</span> <span m=''4015880''>It</span>
  <span m=''4016030''>goes</span> <span m=''4016260''>like</span> <span m=''4016460''>this.</span>
  </p><p><span m=''4018135''>Here,</span> <span m=''4018570''>we</span> <span m=''4018680''>start.</span>
  <span m=''4019890''>We</span> <span m=''4020040''>have</span> <span m=''4020180''>solved</span>
  <span m=''4020555''>this.</span> <span m=''4021460''>We</span> <span m=''4021640''>have</span>
  <span m=''4021810''>two</span> <span m=''4022010''>polynomials</span> <span m=''4022760''>lambda</span>
  <span m=''4023230''>and</span> <span m=''4023380''>h,</span> <span m=''4025080''>so</span>
  <span m=''4025340''>that</span> <span m=''4025590''>this</span> <span m=''4025820''>is</span>
  <span m=''4026030''>true</span> <span m=''4026370''>for</span> <span m=''4026580''>all</span>
  <span m=''4026810''>xi.</span> <span m=''4030380''>We</span> <span m=''4030570''>know</span>
  <span m=''4031140''>that</span> <span m=''4031340''>we</span> <span m=''4031410''>can</span>
  <span m=''4031590''>write</span> <span m=''4031820''>it</span> <span m=''4031920''>like</span>
  <span m=''4032140''>this.</span> <span m=''4032440''>That''s</span> <span m=''4032590''>just</span>
  <span m=''4032820''>by</span> <span m=''4032930''>definition</span> <span m=''4033200''>of</span>
  <span m=''4033470''>yi,</span> <span m=''4035060''>just</span> <span m=''4035290''>expanding</span>
  <span m=''4035740''>the</span> <span m=''4035830''>yi</span> <span m=''4036120''>into</span>
  <span m=''4036410''>this.</span> </p><p><span m=''4038980''>We</span> <span m=''4039110''>know</span>
  <span m=''4039400''>that</span> <span m=''4039590''>this</span> <span m=''4039790''>is</span>
  <span m=''4039970''>true</span> <span m=''4040360''>by</span> <span m=''4040520''>the</span>
  <span m=''4040630''>definition</span> <span m=''4041110''>of</span> <span m=''4041230''>the</span>
  <span m=''4041310''>code.</span> <span m=''4042400''>The</span> <span m=''4042500''>ci</span>
  <span m=''4043130''>is the</span> <span m=''4043290''>evaluation</span> <span m=''4043655''>of
  f,</span> <span m=''4044930''>of</span> <span m=''4045060''>some</span> <span m=''4045560''>polynomial</span>
  <span m=''4045880''>f.</span> <span m=''4047500''>So</span> <span m=''4047630''>we</span>
  <span m=''4047740''>can</span> <span m=''4047970''>write</span> <span m=''4048260''>this</span>
  <span m=''4049650''>just</span> <span m=''4049870''>by</span> <span m=''4049960''>definition</span>
  <span m=''4050490''>of</span> <span m=''4050620''>the</span> <span m=''4050730''>code.</span>
  <span m=''4051770''>So</span> <span m=''4051960''>once</span> <span m=''4052170''>we</span>
  <span m=''4052260''>have</span> <span m=''4052420''>these</span> <span m=''4052680''>two</span>
  <span m=''4052800''>guys</span> <span m=''4053190''>here,</span> <span m=''4054990''>we</span>
  <span m=''4055060''>can</span> <span m=''4055470''>subtract</span> <span m=''4056070''>them</span>
  <span m=''4056430''>[UNINTELLIGIBLE]</span> <span m=''4056910''>here.</span> </p><p><span
  m=''4059930''>So</span> <span m=''4060850''>we</span> <span m=''4060980''>know</span>
  <span m=''4061270''>that</span> <span m=''4061430''>we</span> <span m=''4061580''>have</span>
  <span m=''4063000''>solved</span> <span m=''4063580''>the</span> <span m=''4063700''>following</span>
  <span m=''4064100''>problem.</span> <span m=''4064500''>We</span> <span m=''4064580''>have</span>
  <span m=''4064710''>found</span> <span m=''4065030''>lambda</span> <span m=''4066750''>and</span>
  <span m=''4067070''>h.</span> <span m=''4069000''>So</span> <span m=''4069290''>that</span>
  <span m=''4073050''>there</span> <span m=''4073610''>is</span> <span m=''4073810''>guaranteed</span>
  <span m=''4074760''>to</span> <span m=''4074880''>exist</span> <span m=''4075280''>the</span>
  <span m=''4075380''>polynomial</span> <span m=''4076110''>f,</span> <span m=''4077350''>so</span>
  <span m=''4077580''>that</span> <span m=''4077790''>this</span> <span m=''4077960''>whole</span>
  <span m=''4078240''>thing,</span> <span m=''4078500''>namely,</span> <span m=''4078780''>S</span>
  <span m=''4079000''>of</span> <span m=''4079280''>xi,</span> <span m=''4081500''>that</span>
  <span m=''4081710''>S</span> <span m=''4081950''>is</span> <span m=''4082100''>a</span>
  <span m=''4082580''>polynomial</span> <span m=''4082860''>of</span> <span m=''4083140''>degree</span>
  <span m=''4083500''>at</span> <span m=''4083650''>most --</span> <span m=''4084470''>what</span>
  <span m=''4084730''>did we have --</span> <span m=''4086130''>k</span> <span m=''4086360''>plus</span>
  <span m=''4087750''>degree</span> <span m=''4088090''>lambda</span> <span m=''4089290''>minus</span>
  <span m=''4089580''>1.</span> <span m=''4092880''>So</span> <span m=''4094760''>that''s</span>
  <span m=''4094950''>a</span> <span m=''4095000''>semi-hairy</span> <span m=''4095710''>step</span>
  <span m=''4097170''>here.</span> </p><p><span m=''4098550''>Is</span> <span m=''4098640''>that</span>
  <span m=''4098830''>clear</span> <span m=''4100370''>that</span> <span m=''4102670''>we</span>
  <span m=''4102840''>can</span> <span m=''4103080''>guarantee</span> <span m=''4103729''>the</span>
  <span m=''4103870''>existence</span> <span m=''4104479''>of</span> <span m=''4104630''>a</span>
  <span m=''4104700''>polynomial</span> <span m=''4105439''>S</span> <span m=''4107859''>of</span>
  <span m=''4108040''>degree</span> <span m=''4108529''>at</span> <span m=''4108649''>most</span>
  <span m=''4110260''>k</span> <span m=''4110540''>plus</span> <span m=''4110800''>degree</span>
  <span m=''4111130''>lambda</span> <span m=''4111819''>minus</span> <span m=''4112149''>1?</span>
  <span m=''4114340''>So</span> <span m=''4115620''>that</span> <span m=''4116120''>this</span>
  <span m=''4116319''>equation</span> <span m=''4118060''>holds.</span> <span m=''4123229''>Once</span>
  <span m=''4123420''>we</span> <span m=''4123490''>have</span> <span m=''4123620''>solved</span>
  <span m=''4123950''>this,</span> <span m=''4124630''>we</span> <span m=''4124750''>can</span>
  <span m=''4125029''>guarantee</span> <span m=''4125500''>the</span> <span m=''4125609''>existence</span>
  <span m=''4126090''>of</span> <span m=''4126220''>this.</span> <span m=''4126890''>That''s</span>
  <span m=''4127010''>what we''re</span> <span m=''4127210''>saying.</span> <span
  m=''4128939''>We</span> <span m=''4129130''>can</span> <span m=''4129340''>guarantee</span>
  <span m=''4129670''>the</span> <span m=''4129750''>existence</span> <span m=''4130090''>of</span>
  <span m=''4130380''>this.</span> </p><p><span m=''4131029''>So</span> <span m=''4131210''>now</span>
  <span m=''4131390''>look</span> <span m=''4131630''>at</span> <span m=''4131870''>this.</span>
  <span m=''4133819''>If</span> <span m=''4133930''>you</span> <span m=''4134100''>write</span>
  <span m=''4134479''>this</span> <span m=''4134700''>out for</span> <span m=''4135089''>all</span>
  <span m=''4135479''>i''s</span> <span m=''4135790''>and</span> <span m=''4135910''>put</span>
  <span m=''4136060''>it</span> <span m=''4136170''>in</span> <span m=''4136279''>a</span>
  <span m=''4136330''>vector,</span> <span m=''4138319''>what''s</span> <span m=''4138390''>the
  rate</span> <span m=''4138630''>of</span> <span m=''4138740''>this</span> <span
  m=''4138930''>vector?</span> <span m=''4140620''>Well,</span> <span m=''4140830''>it''s
  at</span> <span m=''4141050''>most</span> <span m=''4141370''>t</span> <span m=''4142080''>because</span>
  <span m=''4142510''>all</span> <span m=''4142680''>the</span> <span m=''4142810''>other</span>
  <span m=''4142979''>e''s</span> <span m=''4143430''>are 0.</span> <span m=''4145630''>If</span>
  <span m=''4146100''>lambda</span> <span m=''4146550''>is</span> <span m=''4146740''>an</span>
  <span m=''4146870''>error</span> <span m=''4147190''>locator,</span> <span m=''4147729''>it</span>
  <span m=''4148189''>is</span> <span m=''4148229''>0.</span> <span m=''4148890''>But</span>
  <span m=''4149140''>we</span> <span m=''4149210''>do</span> <span m=''4149310''>not</span>
  <span m=''4149500''>know</span> <span m=''4149680''>that</span> <span m=''4149870''>yet.</span>
  <span m=''4150740''>All</span> <span m=''4150939''>we</span> <span m=''4151069''>know,</span>
  <span m=''4151359''>it''s</span> <span m=''4151510''>at</span> <span m=''4151660''>most</span>
  <span m=''4152060''>t.</span> </p><p><span m=''4155149''>This</span> <span m=''4155330''>is</span>
  <span m=''4155460''>on</span> <span m=''4155600''>this</span> <span m=''4155810''>side,</span>
  <span m=''4156430''>so</span> <span m=''4156670''>that</span> <span m=''4156890''>vector</span>
  <span m=''4157250''>has a</span> <span m=''4157319''>rate</span> <span m=''4157479''>at</span>
  <span m=''4157680''>most</span> <span m=''4158040''>t.</span> <span m=''4158939''>On</span>
  <span m=''4159140''>this</span> <span m=''4159420''>side,</span> <span m=''4160770''>the</span>
  <span m=''4160930''>rate</span> <span m=''4161370''>of</span> <span m=''4161560''>this</span>
  <span m=''4161830''>vector</span> <span m=''4162950''>is</span> <span m=''4163140''>at</span>
  <span m=''4163310''>least</span> <span m=''4163729''>this.</span> <span m=''4165660''>Just</span>
  <span m=''4165979''>by</span> <span m=''4166430''>evaluating</span> <span m=''4167080''>a</span>
  <span m=''4167140''>polynomial</span> <span m=''4167519''>of</span> <span m=''4167899''>this</span>
  <span m=''4168090''>degree,</span> <span m=''4168939''>this</span> <span m=''4169109''>is</span>
  <span m=''4169250''>the</span> <span m=''4169310''>maximum</span> <span m=''4169700''>number</span>
  <span m=''4169990''>of</span> <span m=''4170050''>0''s</span> <span m=''4170410''>we
  can</span> <span m=''4170710''>get.</span> </p><p><span m=''4174350''>So</span>
  <span m=''4176000''>now</span> <span m=''4176200''>we</span> <span m=''4176350''>have</span>
  <span m=''4176500''>two</span> <span m=''4177010''>equalities,</span> <span m=''4178939''>this</span>
  <span m=''4179220''>one</span> <span m=''4180550''>and</span> <span m=''4180720''>this</span>
  <span m=''4180979''>one.</span> <span m=''4181740''>But</span> <span m=''4181939''>obviously,</span>
  <span m=''4182479''>the</span> <span m=''4182600''>two</span> <span m=''4182779''>vectors</span>
  <span m=''4183229''>must</span> <span m=''4183450''>be</span> <span m=''4183540''>the</span>
  <span m=''4183649''>same.</span> <span m=''4185330''>So</span> <span m=''4185500''>how</span>
  <span m=''4185720''>can</span> <span m=''4185930''>these</span> <span m=''4186210''>two</span>
  <span m=''4186340''>vectors</span> <span m=''4186939''>be</span> <span m=''4187140''>the</span>
  <span m=''4187270''>same</span> <span m=''4188149''>and</span> <span m=''4188340''>still</span>
  <span m=''4188640''>satisfy</span> <span m=''4189880''>these</span> <span m=''4190210''>two</span>
  <span m=''4190340''>inequalities?</span> <span m=''4193250''>Good</span> <span m=''4193460''>question.</span>
  <span m=''4193950''>How</span> <span m=''4194120''>can</span> <span m=''4194300''>they</span>
  <span m=''4194420''>be</span> <span m=''4194590''>the</span> <span m=''4194690''>same</span>
  <span m=''4195020''>and still</span> <span m=''4195340''>satisfy</span> <span m=''4195770''>this</span>
  <span m=''4195930''>inequality?</span> </p><p><span m=''4210720''>If</span> <span
  m=''4211000''>t</span> <span m=''4211240''>is</span> <span m=''4211340''>less</span>
  <span m=''4211610''>than</span> <span m=''4212130''>d/2,</span> <span m=''4213170''>then</span>
  <span m=''4213400''>the</span> <span m=''4213550''>rate</span> <span m=''4213840''>of</span>
  <span m=''4214030''>this</span> <span m=''4214330''>vector</span> <span m=''4214790''>would</span>
  <span m=''4215070''>have</span> <span m=''4215340''>to</span> <span m=''4215460''>be</span>
  <span m=''4215620''>larger</span> <span m=''4216690''>than</span> <span m=''4216920''>the</span>
  <span m=''4217030''>rate</span> <span m=''4217290''>of</span> <span m=''4217440''>this.</span>
  <span m=''4218000''>If</span> <span m=''4218190''>they</span> <span m=''4218310''>are</span>
  <span m=''4218430''>non-zero.</span> <span m=''4222530''>If</span> <span m=''4222690''>they</span>
  <span m=''4222810''>are</span> <span m=''4222940''>non-zero,</span> <span m=''4223600''>this</span>
  <span m=''4223830''>would</span> <span m=''4224040''>have</span> <span m=''4224240''>to</span>
  <span m=''4224340''>be</span> <span m=''4224470''>larger</span> <span m=''4224840''>than</span>
  <span m=''4225030''>this</span> <span m=''4226020''>because</span> <span m=''4226440''>then</span>
  <span m=''4227340''>d</span> <span m=''4227650''>minus</span> <span m=''4228140''>t</span>
  <span m=''4228580''>would</span> <span m=''4228810''>be</span> <span m=''4228910''>greater</span>
  <span m=''4229270''>than</span> <span m=''4229480''>t.</span> <span m=''4230250''>If</span>
  <span m=''4230470''>this</span> <span m=''4230650''>is</span> <span m=''4230810''>true,</span>
  <span m=''4231130''>this</span> <span m=''4231370''>implies</span> <span m=''4231880''>this.</span>
  <span m=''4236890''>If</span> <span m=''4237150''>this</span> <span m=''4237320''>is</span>
  <span m=''4237480''>true,</span> <span m=''4238280''>this</span> <span m=''4238550''>implies</span>
  <span m=''4239120''>this</span> <span m=''4240010''>which</span> <span m=''4240190''>implies</span>
  <span m=''4240710''>that</span> <span m=''4240870''>the</span> <span m=''4240980''>rate</span>
  <span m=''4241220''>of</span> <span m=''4241350''>this</span> <span m=''4241590''>vector</span>
  <span m=''4242460''>would</span> <span m=''4242800''>be</span> <span m=''4242940''>larger</span>
  <span m=''4243380''>than</span> <span m=''4243560''>the</span> <span m=''4243680''>rate</span>
  <span m=''4243920''>of</span> <span m=''4244020''>this</span> <span m=''4244270''>vector</span>
  <span m=''4244760''>if they</span> <span m=''4245060''>are</span> <span m=''4245200''>non-zero.</span>
  </p><p><span m=''4248840''>But</span> <span m=''4249020''>how</span> <span m=''4249200''>can</span>
  <span m=''4249370''>that</span> <span m=''4249580''>be?</span> <span m=''4250890''>Answer
  is</span> <span m=''4251470''>cannot.</span> <span m=''4253210''>Cannot</span> <span
  m=''4253650''>be,</span> <span m=''4254290''>hence,</span> <span m=''4254820''>they</span>
  <span m=''4254910''>must</span> <span m=''4255180''>be</span> <span m=''4255270''>0.</span>
  <span m=''4256080''>Both</span> <span m=''4256400''>vectors</span> <span m=''4256780''>must</span>
  <span m=''4257010''>be</span> <span m=''4257120''>0</span> <span m=''4257460''>completely,</span>
  <span m=''4259440''>which</span> <span m=''4259580''>means</span> <span m=''4259840''>this</span>
  <span m=''4260150''>is</span> <span m=''4260280''>an error</span> <span m=''4260540''>locator.</span>
  </p><p><span m=''4262250''>Because</span> <span m=''4262460''>otherwise,</span>
  <span m=''4262940''>this</span> <span m=''4263060''>wouldn''t</span> <span m=''4263260''>be</span>
  <span m=''4263340''>0,</span> <span m=''4264530''>and</span> <span m=''4267410''>this</span>
  <span m=''4267820''>one --</span> <span m=''4268180''>where did I</span> <span m=''4268624''>write
  it?</span> <span m=''4271910''>Somewhere</span> <span m=''4272070''>I</span> <span
  m=''4272300''>wrote it.</span> <span m=''4278640''>Where did I</span> <span m=''4279082''>write
  it?</span> <span m=''4281292''>Oh,</span> <span m=''4281740''>here.</span> <span
  m=''4282750''>So</span> <span m=''4283640''>this</span> <span m=''4283960''>S</span>
  <span m=''4286010''>has</span> <span m=''4286200''>to</span> <span m=''4286290''>be</span>
  <span m=''4286380''>0</span> <span m=''4286700''>too.</span> <span m=''4287300''>If</span>
  <span m=''4287580''>this</span> <span m=''4287780''>S</span> <span m=''4288040''>is</span>
  <span m=''4288170''>0,</span> <span m=''4289290''>then</span> <span m=''4289870''>h</span>
  <span m=''4290110''>of</span> <span m=''4290240''>xi</span> <span m=''4290780''>is</span>
  <span m=''4290920''>exactly</span> <span m=''4291353''>this,</span> <span m=''4292760''>means</span>
  <span m=''4293180''>factors</span> <span m=''4293640''>in</span> <span m=''4293740''>the</span>
  <span m=''4293850''>way</span> <span m=''4294000''>you</span> <span m=''4294140''>want</span>
  <span m=''4294570''>it to.</span> </p><p><span m=''4296870''>So</span> <span m=''4298350''>that''s</span>
  <span m=''4298540''>all</span> <span m=''4298680''>I</span> <span m=''4298730''>can</span>
  <span m=''4298920''>say.</span> <span m=''4300270''>I</span> <span m=''4300340''>could</span>
  <span m=''4300670''>say</span> <span m=''4300840''>it</span> <span m=''4300920''>again,</span>
  <span m=''4301310''>but</span> <span m=''4301490''>it''s</span> <span m=''4301630''>exactly</span>
  <span m=''4302110''>the</span> <span m=''4302210''>same</span> <span m=''4302460''>words.</span>
  <span m=''4303810''>And</span> <span m=''4304900''>there''s</span> <span m=''4305130''>a</span>
  <span m=''4305160''>limited</span> <span m=''4305670''>benefit</span> <span m=''4306040''>to</span>
  <span m=''4306130''>even</span> <span m=''4306330''>the</span> <span m=''4306420''>repetition</span>
  <span m=''4306880''>code.</span> </p><p><span m=''4310290''>So</span> <span m=''4311170''>beautiful,</span>
  <span m=''4311630''>right?</span> <span m=''4311880''>We</span> <span m=''4311950''>have</span>
  <span m=''4312510''>brought</span> <span m=''4312840''>down</span> <span m=''4313180''>the</span>
  <span m=''4313260''>entire</span> <span m=''4313680''>decoding</span> <span m=''4314150''>problem</span>
  <span m=''4314560''>for</span> <span m=''4314750''>Reed-Solomon</span> <span m=''4315310''>codes</span>
  <span m=''4316250''>to</span> <span m=''4316740''>solving</span> <span m=''4317230''>a</span>
  <span m=''4317270''>linear</span> <span m=''4317600''>system</span> <span m=''4318020''>of
  equations,</span> <span m=''4321300''>namely,</span> <span m=''4322690''>this</span>
  <span m=''4322930''>one</span> <span m=''4323180''>here</span> <span m=''4324440''>or</span>
  <span m=''4324580''>this</span> <span m=''4324810''>one in</span> <span m=''4325085''>short</span>
  <span m=''4325360''>form,</span> <span m=''4326580''>which,</span> <span m=''4326940''>well,
  it''s</span> <span m=''4327310''>no</span> <span m=''4327460''>problem</span> <span
  m=''4327880''>at</span> <span m=''4328010''>all</span> <span m=''4329136''>in</span>
  <span m=''4329540''>the</span> <span m=''4329600''>grand</span> <span m=''4329860''>scheme</span>
  <span m=''4330100''>of</span> <span m=''4330280''>things.</span> <span m=''4331130''>And</span>
  <span m=''4331570''>that''s</span> <span m=''4331740''>the</span> <span m=''4331840''>other</span>
  <span m=''4332040''>thing</span> <span m=''4332200''>that</span> <span m=''4332350''>makes</span>
  <span m=''4332570''>Reed-Solomon</span> <span m=''4332960''>codes</span> <span m=''4333250''>so</span>
  <span m=''4333390''>beautiful.</span> <span m=''4334080''>They''re</span> <span
  m=''4334370''>access</span> <span m=''4334660''>encoding,</span> <span m=''4335650''>they''re</span>
  <span m=''4335950''>access</span> <span m=''4336180''>decoding,</span> <span m=''4337674''>they''re</span>
  <span m=''4338440''>everything</span> <span m=''4338770''>that</span> <span m=''4338900''>we</span>
  <span m=''4339030''>want.</span> </p><p><span m=''4355380''>Let</span> <span m=''4355520''>me</span>
  <span m=''4355590''>do</span> <span m=''4355760''>one</span> <span m=''4355980''>more</span>
  <span m=''4356120''>thing</span> <span m=''4356400''>about</span> <span m=''4356580''>the</span>
  <span m=''4356760''>decoding</span> <span m=''4358050''>just</span> <span m=''4358290''>to</span>
  <span m=''4358350''>bring</span> <span m=''4358570''>it</span> <span m=''4358660''>down</span>
  <span m=''4358910''>a</span> <span m=''4358950''>little</span> <span m=''4359160''>bit,</span>
  <span m=''4359845''>to</span> <span m=''4360220''>talk</span> <span m=''4360480''>a</span>
  <span m=''4360500''>little</span> <span m=''4360720''>bit</span> <span m=''4360840''>about</span>
  <span m=''4361030''>complexity.</span> <span m=''4362850''>Solving</span> <span
  m=''4363320''>this</span> <span m=''4363670''>linear</span> <span m=''4363990''>system</span>
  <span m=''4364410''>of equations</span> <span m=''4369490''>has</span> <span m=''4369780''>been</span>
  <span m=''4369960''>subject</span> <span m=''4370440''>to</span> <span m=''4370560''>research</span>
  <span m=''4372300''>for</span> <span m=''4372800''>30</span> <span m=''4373160''>years,</span>
  <span m=''4373860''>40</span> <span m=''4374200''>years.</span> <span m=''4376850''>So</span>
  <span m=''4377200''>it</span> <span m=''4377430''>started</span> <span m=''4377670''>out</span>
  <span m=''4379470''>with</span> <span m=''4379850''>an</span> <span m=''4379980''>algorithm</span>
  <span m=''4380730''>which</span> <span m=''4380910''>essentially</span> <span m=''4381520''>solved</span>
  <span m=''4381920''>that</span> <span m=''4382040''>linear</span> <span m=''4382380''>system</span>
  <span m=''4382810''>directly.</span> <span m=''4384976''>It</span> <span m=''4385430''>was</span>
  <span m=''4385970''>formulated</span> <span m=''4386325''>a bit</span> <span m=''4386680''>different,</span>
  <span m=''4387900''>but</span> <span m=''4388030''>that''s</span> <span m=''4388260''>what</span>
  <span m=''4388390''>it</span> <span m=''4388490''>is.</span> <span m=''4388680''>It''s
  called</span> <span m=''4388890''>the</span> <span m=''4388980''>Peterson-Gorenstein-Zierler</span>
  <span m=''4390250''>algorithm.</span> <span m=''4394560''>They</span> <span m=''4394720''>realized</span>
  <span m=''4396510''>it</span> <span m=''4396620''>was</span> <span m=''4399400''>a</span>
  <span m=''4399670''>polynomial</span> <span m=''4400190''>time</span> <span m=''4400450''>decoding</span>
  <span m=''4400850''>algorithm,</span> <span m=''4401220''>a</span> <span m=''4401260''>nice</span>
  <span m=''4401590''>decoding</span> <span m=''4402000''>algorithm.</span> </p><p><span
  m=''4403500''>Then</span> <span m=''4403710''>Berlekamp --</span> <span m=''4404060''>I
  should</span> <span m=''4404480''>write</span> <span m=''4404840''>down</span> <span
  m=''4404960''>the</span> <span m=''4405040''>name.</span> <span m=''4410190''>Berlekamp</span>
  <span m=''4410690''>came</span> <span m=''4411010''>up</span> <span m=''4411190''>with</span>
  <span m=''4411300''>a</span> <span m=''4411360''>fast</span> <span m=''4411760''>algorithm</span>
  <span m=''4412480''>and</span> <span m=''4412840''>square</span> <span m=''4413130''>algorithm.</span>
  <span m=''4420030''>Massey</span> <span m=''4420260''>had</span> <span m=''4421770''>his</span>
  <span m=''4421900''>own</span> <span m=''4422070''>formulation</span> <span m=''4422435''>of</span>
  <span m=''4422800''>that</span> <span m=''4423200''>algorithm,</span> <span m=''4423650''>which</span>
  <span m=''4424190''>was</span> <span m=''4424445''>a</span> <span m=''4424700''>bit</span>
  <span m=''4424850''>more</span> <span m=''4425070''>streamlined</span> <span m=''4425770''>I</span>
  <span m=''4425800''>think.</span> <span m=''4428810''>Then</span> <span m=''4428950''>there</span>
  <span m=''4429060''>was</span> <span m=''4429250''>a</span> <span m=''4430236''>later</span>
  <span m=''4430640''>version,</span> <span m=''4432910''>Berlekamp-Welch.</span>
  <span m=''4438230''>The</span> <span m=''4438940''>complexity</span> <span m=''4439570''>of</span>
  <span m=''4439670''>these</span> <span m=''4439820''>algorithms</span> <span m=''4440360''>is</span>
  <span m=''4440470''>all</span> <span m=''4440660''>roughly</span> <span m=''4440970''>the</span>
  <span m=''4441070''>same,</span> <span m=''4441390''>is</span> <span m=''4441500''>all</span>
  <span m=''4441660''>n</span> <span m=''4441800''>squared</span> <span m=''4442224''>roughly,</span>
  <span m=''4443920''>which</span> <span m=''4444330''>solved</span> <span m=''4444610''>this</span>
  <span m=''4444920''>here.</span> </p><p><span m=''4446430''>And</span> <span m=''4446580''>then</span>
  <span m=''4448070''>there''s</span> <span m=''4448270''>roughly</span> <span m=''4448610''>nothing</span>
  <span m=''4448910''>happening</span> <span m=''4449370''>for</span> <span m=''4449500''>30</span>
  <span m=''4449860''>years.</span> <span m=''4453170''>And</span> <span m=''4453430''>after</span>
  <span m=''4453660''>30</span> <span m=''4453960''>years,</span> <span m=''4454230''>then</span>
  <span m=''4454400''>Madhu</span> <span m=''4454680''>Sudan</span> <span m=''4460330''>made</span>
  <span m=''4460520''>the</span> <span m=''4460700''>next</span> <span m=''4461150''>serious</span>
  <span m=''4461630''>dent</span> <span m=''4462020''>in</span> <span m=''4462420''>the</span>
  <span m=''4462820''>decoding</span> <span m=''4463210''>history</span> <span m=''4463495''>of</span>
  <span m=''4463780''>Reed-Solomon</span> <span m=''4464570''>codes.</span> <span
  m=''4465820''>So</span> <span m=''4465990''>he</span> <span m=''4466220''>found</span>
  <span m=''4466570''>a</span> <span m=''4466630''>way</span> <span m=''4470100''>to</span>
  <span m=''4470240''>solve</span> <span m=''4470620''>this</span> <span m=''4470900''>problem</span>
  <span m=''4472090''>even</span> <span m=''4472300''>beyond</span> <span m=''4472780''>half
  the</span> <span m=''4472990''>minimum</span> <span m=''4473240''>distance.</span>
  <span m=''4475700''>And</span> <span m=''4476660''>in</span> <span m=''4476810''>hindsight,</span>
  <span m=''4477380''>it''s</span> <span m=''4477500''>a</span> <span m=''4477550''>very</span>
  <span m=''4477730''>nice</span> <span m=''4479100''>and</span> <span m=''4479220''>very</span>
  <span m=''4479450''>simple</span> <span m=''4479980''>trick</span> <span m=''4481230''>that
  he</span> <span m=''4481420''>used.</span> </p><p><span m=''4486160''>So</span>
  <span m=''4493770''>we</span> <span m=''4494010''>started</span> <span m=''4494460''>with</span>
  <span m=''4494560''>the</span> <span m=''4494660''>following.</span> <span m=''4494945''>We</span>
  <span m=''4495230''>started</span> <span m=''4495720''>that,</span> <span m=''4496020''>well,</span>
  <span m=''4496450''>if we</span> <span m=''4496880''>have</span> <span m=''4497010''>no</span>
  <span m=''4497310''>errors,</span> <span m=''4498990''>then</span> <span m=''4502840''>the</span>
  <span m=''4503060''>pairs</span> <span m=''4503490''>of</span> <span m=''4503680''>points</span>
  <span m=''4506380''>xi,</span> <span m=''4507750''>yi</span> <span m=''4510280''>lie</span>
  <span m=''4510700''>on</span> <span m=''4510890''>this</span> <span m=''4511170''>curve.</span>
  <span m=''4513110''>That''s</span> <span m=''4513950''>another</span> <span m=''4514150''>way</span>
  <span m=''4514310''>to</span> <span m=''4514440''>formulate</span> <span m=''4514700''>what</span>
  <span m=''4514790''>we</span> <span m=''4515110''>said</span> <span m=''4515330''>that</span>
  <span m=''4516370''>yi</span> <span m=''4516940''>minus</span> <span m=''4517330''>f
  of</span> <span m=''4517723''>xi</span> <span m=''4518116''>has to</span> <span
  m=''4518510''>be 0.</span> <span m=''4520760''>We said,</span> <span m=''4520930''>well,</span>
  <span m=''4521360''>if there</span> <span m=''4521540''>are</span> <span m=''4521640''>no</span>
  <span m=''4521900''>errors,</span> <span m=''4522490''>all</span> <span m=''4522710''>the</span>
  <span m=''4522920''>points</span> <span m=''4523240''>that</span> <span m=''4523360''>we</span>
  <span m=''4523480''>receive</span> <span m=''4524340''>lie</span> <span m=''4524610''>on</span>
  <span m=''4524760''>this</span> <span m=''4524980''>curve.</span> <span m=''4526260''>Because</span>
  <span m=''4526770''>there</span> <span m=''4527030''>are</span> <span m=''4527290''>errors,</span>
  <span m=''4528400''>we</span> <span m=''4528820''>have</span> <span m=''4529090''>to</span>
  <span m=''4530260''>multiply</span> <span m=''4530930''>this with an</span> <span
  m=''4531300''>error</span> <span m=''4531780''>locator</span> <span m=''4533600''>and</span>
  <span m=''4533960''>say</span> <span m=''4534290''>this</span> <span m=''4534540''>is</span>
  <span m=''4534690''>0</span> <span m=''4536250''>for all</span> <span m=''4536990''>xi,</span>
  <span m=''4537610''>yi.</span> <span m=''4539570''>So</span> <span m=''4539880''>this</span>
  <span m=''4540100''>was</span> <span m=''4540370''>problem</span> <span m=''4540770''>number</span>
  <span m=''4541070''>one.</span> <span m=''4541430''>The</span> <span m=''4541570''>relaxed</span>
  <span m=''4542050''>form</span> <span m=''4543430''>was</span> <span m=''4545730''>lambda</span>
  <span m=''4546190''>xy</span> <span m=''4547850''>minus</span> <span m=''4548440''>h</span>
  <span m=''4548730''>of</span> <span m=''4548870''>x</span> <span m=''4550490''>0</span>
  <span m=''4554180''>xi,</span> <span m=''4554495''>yi.</span> </p><p><span m=''4557280''>That''s</span>
  <span m=''4558070''>the</span> <span m=''4558260''>way</span> <span m=''4558600''>we</span>
  <span m=''4558810''>do it.</span> <span m=''4559270''>So</span> <span m=''4559390''>what</span>
  <span m=''4559510''>did</span> <span m=''4559630''>Madhu</span> <span m=''4559900''>do?</span>
  <span m=''4560690''>Very</span> <span m=''4560980''>clever.</span> <span m=''4561330''>He</span>
  <span m=''4561650''>said,</span> <span m=''4563750''>all</span> <span m=''4563980''>that</span>
  <span m=''4564150''>we</span> <span m=''4564310''>have</span> <span m=''4564460''>to</span>
  <span m=''4564600''>do</span> <span m=''4564900''>is</span> <span m=''4565020''>annihilate</span>
  <span m=''4565900''>the</span> <span m=''4566010''>effect</span> <span m=''4566380''>of</span>
  <span m=''4566490''>the</span> <span m=''4566630''>error</span> <span m=''4567700''>right</span>
  <span m=''4568000''>in this.</span> <span m=''4569380''>The</span> <span m=''4569460''>whole</span>
  <span m=''4569710''>reason</span> <span m=''4570000''>for</span> <span m=''4570130''>that</span>
  <span m=''4570310''>lambda</span> <span m=''4570750''>was</span> <span m=''4571020''>to</span>
  <span m=''4571110''>annihilate --</span> <span m=''4572070''>so</span> <span m=''4572250''>to</span>
  <span m=''4572390''>take</span> <span m=''4572730''>out</span> <span m=''4574636''>the</span>
  <span m=''4575030''>error</span> <span m=''4575330''>influence</span> <span m=''4575890''>out</span>
  <span m=''4576040''>of</span> <span m=''4576130''>this</span> <span m=''4576270''>interpolation</span>
  <span m=''4576890''>formula,</span> <span m=''4577780''>to</span> <span m=''4577950''>allow</span>
  <span m=''4579920''>for a</span> <span m=''4580150''>few</span> <span m=''4580410''>errors</span>
  <span m=''4580700''>to</span> <span m=''4580800''>happen,</span> <span m=''4581190''>which</span>
  <span m=''4581360''>we</span> <span m=''4581450''>can</span> <span m=''4581610''>put</span>
  <span m=''4581760''>in lambda.</span> </p><p><span m=''4583180''>Well,</span> <span
  m=''4583270''>Madhu</span> <span m=''4583520''>said,</span> <span m=''4583830''>well,</span>
  <span m=''4584070''>what</span> <span m=''4584210''>about</span> <span m=''4584500''>we</span>
  <span m=''4584580''>take</span> <span m=''4586840''>a</span> <span m=''4586920''>polynomial</span>
  <span m=''4587430''>in</span> <span m=''4587520''>two</span> <span m=''4587680''>variables?</span>
  <span m=''4590570''>A</span> <span m=''4590740''>polynomial</span> <span m=''4591020''>in</span>
  <span m=''4591220''>two</span> <span m=''4591400''>variables,</span> <span m=''4593000''>then</span>
  <span m=''4594890''>same</span> <span m=''4595220''>thing.</span> <span m=''4596790''>If</span>
  <span m=''4598350''>no</span> <span m=''4598680''>errors</span> <span m=''4599060''>happen,</span>
  <span m=''4600450''>then</span> <span m=''4600810''>all</span> <span m=''4600980''>the</span>
  <span m=''4601150''>points</span> <span m=''4601450''>xi,</span> <span m=''4601870''>yi</span>
  <span m=''4602230''>will</span> <span m=''4602390''>lie</span> <span m=''4602870''>on</span>
  <span m=''4603030''>that</span> <span m=''4603250''>curve.</span> <span m=''4604580''>If</span>
  <span m=''4604740''>a</span> <span m=''4604800''>few</span> <span m=''4605050''>errors</span>
  <span m=''4605450''>happen,</span> <span m=''4606400''>then</span> <span m=''4606610''>let''s</span>
  <span m=''4606880''>find</span> <span m=''4607210''>a</span> <span m=''4607360''>lambda</span>
  <span m=''4607920''>xy,</span> <span m=''4610380''>two</span> <span m=''4610690''>variables</span>
  <span m=''4611970''>of</span> <span m=''4612080''>some</span> <span m=''4612360''>minimal</span>
  <span m=''4612830''>degree,</span> <span m=''4614430''>some</span> <span m=''4614710''>very</span>
  <span m=''4614970''>small</span> <span m=''4615280''>degree</span> <span m=''4615790''>so</span>
  <span m=''4616020''>that</span> <span m=''4616250''>this</span> <span m=''4616460''>is</span>
  <span m=''4617045''>still</span> <span m=''4617340''>satisfied.</span> </p><p><span
  m=''4622082''>And</span> <span m=''4622510''>the</span> <span m=''4622820''>problem</span>
  <span m=''4623300''>is</span> <span m=''4623420''>entirely</span> <span m=''4624000''>the</span>
  <span m=''4624110''>same.</span> <span m=''4627820''>And</span> <span m=''4628870''>this</span>
  <span m=''4629120''>one,</span> <span m=''4629300''>you</span> <span m=''4629410''>cannot</span>
  <span m=''4630000''>solve</span> <span m=''4630270''>either.</span> <span m=''4632420''>You</span>
  <span m=''4632840''>cannot</span> <span m=''4633440''>solve</span> <span m=''4633520''>either.</span>
  <span m=''4634160''>But</span> <span m=''4634450''>again,</span> <span m=''4634820''>you</span>
  <span m=''4634960''>can</span> <span m=''4635160''>solve</span> <span m=''4635510''>the</span>
  <span m=''4635600''>relaxation</span> <span m=''4639510''>minus --</span> <span
  m=''4647550''>again,</span> <span m=''4647910''>you</span> <span m=''4648020''>can</span>
  <span m=''4648190''>solve</span> <span m=''4648510''>the</span> <span m=''4648600''>relaxation.</span>
  <span m=''4649280''>This</span> <span m=''4649420''>is,</span> <span m=''4649550''>again,</span>
  <span m=''4649830''>a</span> <span m=''4649860''>linear</span> <span m=''4650160''>system</span>
  <span m=''4650520''>of equations.</span> <span m=''4651890''>And</span> <span m=''4652040''>the</span>
  <span m=''4652130''>coefficients</span> <span m=''4652690''>of</span> <span m=''4652790''>lambda</span>
  <span m=''4653260''>and psi</span> <span m=''4653545''>now.</span> </p><p><span
  m=''4656960''>Once</span> <span m=''4657210''>you</span> <span m=''4657370''>solve</span>
  <span m=''4657730''>this</span> <span m=''4657920''>linear</span> <span m=''4658000''>system</span>
  <span m=''4658350''>of</span> <span m=''4658450''>equations --</span> <span m=''4660020''>actually,</span>
  <span m=''4660170''>this</span> <span m=''4660380''>one</span> <span m=''4660530''>you</span>
  <span m=''4660640''>can</span> <span m=''4661590''>more</span> <span m=''4661800''>handily</span>
  <span m=''4662290''>write</span> <span m=''4662620''>simply --</span> <span m=''4663565''>now</span>
  <span m=''4664060''>there is</span> <span m=''4664430''>no</span> <span m=''4664590''>way</span>
  <span m=''4664810''>to</span> <span m=''4664950''>distinguish</span> <span m=''4665420''>the</span>
  <span m=''4665540''>y</span> <span m=''4665770''>anymore</span> <span m=''4666270''>since</span>
  <span m=''4667170''>both</span> <span m=''4667530''>sides</span> <span m=''4667890''>anyway</span>
  <span m=''4668340''>depend on</span> <span m=''4668590''>y.</span> <span m=''4670090''>Find</span>
  <span m=''4671600''>a</span> <span m=''4671700''>polynomial</span> <span m=''4673000''>in</span>
  <span m=''4673130''>two</span> <span m=''4673310''>variables</span> <span m=''4675030''>such</span>
  <span m=''4675400''>that</span> <span m=''4675690''>this</span> <span m=''4675910''>is</span>
  <span m=''4676180''>0</span> <span m=''4676590''>for all</span> <span m=''4677030''>xi,</span>
  <span m=''4677570''>yi.</span> <span m=''4679930''>This is</span> <span m=''4680170''>his</span>
  <span m=''4680560''>central</span> <span m=''4681130''>problem.</span> <span m=''4682030''>This</span>
  <span m=''4682220''>is</span> <span m=''4682360''>his</span> <span m=''4682540''>relaxation.</span>
  <span m=''4683160''>Find</span> <span m=''4683390''>a polynomial</span> <span m=''4683705''>in
  two</span> <span m=''4684020''>variables,</span> <span m=''4685240''>which he</span>
  <span m=''4685350''>evaluates</span> <span m=''4685740''>to</span> <span m=''4685850''>0.</span>
  </p><p><span m=''4689140''>And</span> <span m=''4689230''>then</span> <span m=''4689450''>he
  has,</span> <span m=''4692850''>essentially,</span> <span m=''4693310''>the</span>
  <span m=''4693410''>same</span> <span m=''4693690''>proofs</span> <span m=''4694070''>we</span>
  <span m=''4694240''>have</span> <span m=''4694490''>here,</span> <span m=''4695440''>a</span>
  <span m=''4695770''>bit</span> <span m=''4696140''>more</span> <span m=''4696380''>technical,</span>
  <span m=''4697200''>but</span> <span m=''4697390''>not</span> <span m=''4697630''>much.</span>
  <span m=''4700360''>I''m</span> <span m=''4700680''>sure</span> <span m=''4700890''>you</span>
  <span m=''4700960''>can</span> <span m=''4701140''>come</span> <span m=''4701350''>up</span>
  <span m=''4701530''>with</span> <span m=''4701660''>this</span> <span m=''4701890''>if</span>
  <span m=''4701980''>you</span> <span m=''4702110''>sit</span> <span m=''4702300''>down</span>
  <span m=''4702530''>at home.</span> <span m=''4706930''>Let''s</span> <span m=''4707060''>put</span>
  <span m=''4707190''>it</span> <span m=''4707250''>like</span> <span m=''4707420''>this.</span>
  <span m=''4707610''>There''s</span> <span m=''4707780''>no</span> <span m=''4707980''>heavy</span>
  <span m=''4708210''>machinery</span> <span m=''4708530''>in it.</span> <span m=''4709180''>There''s</span>
  <span m=''4709420''>no</span> <span m=''4709640''>heavy</span> <span m=''4709870''>math</span>
  <span m=''4710170''>in it.</span> <span m=''4710870''>There''s</span> <span m=''4711110''>a</span>
  <span m=''4711150''>lot</span> <span m=''4711370''>of</span> <span m=''4711500''>being</span>
  <span m=''4711710''>clever</span> <span m=''4712005''>in it,</span> <span m=''4712790''>but</span>
  <span m=''4712940''>there''s</span> <span m=''4713130''>no</span> <span m=''4713580''>heavy
  math</span> <span m=''4713840''>in it.</span> </p><p><span m=''4720690''>He</span>
  <span m=''4720790''>can now</span> <span m=''4721180''>guarantee</span> <span m=''4722500''>that</span>
  <span m=''4722950''>q</span> <span m=''4723260''>of</span> <span m=''4723420''>xy,</span>
  <span m=''4725380''>if</span> <span m=''4725820''>t</span> <span m=''4727850''>is</span>
  <span m=''4728040''>less</span> <span m=''4728422''>than</span> <span m=''4730050''>n</span>
  <span m=''4730450''>minus</span> <span m=''4732280''>square</span> <span m=''4732810''>root</span>
  <span m=''4733020''>of</span> <span m=''4733170''>2k --</span> <span m=''4735700''>is
  that</span> <span m=''4735850''>right --</span> <span m=''4737570''>2kn,</span>
  <span m=''4741660''>then</span> <span m=''4741930''>you</span> <span m=''4742080''>can</span>
  <span m=''4742310''>guarantee</span> <span m=''4742920''>that</span> <span m=''4743090''>y</span>
  <span m=''4743360''>minus</span> <span m=''4743770''>fx</span> <span m=''4746110''>is</span>
  <span m=''4746280''>a</span> <span m=''4746330''>factor</span> <span m=''4747150''>q</span>
  <span m=''4747500''>of</span> <span m=''4747610''>xy.</span> <span m=''4749420''>The</span>
  <span m=''4749500''>same</span> <span m=''4749800''>thing</span> <span m=''4750010''>we</span>
  <span m=''4750150''>wanted</span> <span m=''4750800''>to</span> <span m=''4750960''>guarantee.</span>
  <span m=''4752736''>And</span> <span m=''4753180''>like</span> <span m=''4753510''>I</span>
  <span m=''4753560''>said,</span> <span m=''4753900''>the</span> <span m=''4754000''>proof</span>
  <span m=''4755860''>is</span> <span m=''4757070''>very</span> <span m=''4757440''>clever,</span>
  <span m=''4758630''>but</span> <span m=''4758820''>no</span> <span m=''4758980''>heavy</span>
  <span m=''4759170''>machinery</span> <span m=''4759500''>in it.</span> <span m=''4759830''>It''s</span>
  <span m=''4760270''>no</span> <span m=''4760470''>heavy</span> <span m=''4760930''>algebraic</span>
  <span m=''4761420''>geometry</span> <span m=''4761705''>or</span> <span m=''4761990''>any
  of this</span> <span m=''4762270''>stuff</span> <span m=''4762535''>in</span> <span
  m=''4762800''>that.</span> <span m=''4765940''>It''s</span> <span m=''4766370''>high
  school</span> <span m=''4766690''>algebra.</span> <span m=''4769110''>Well,</span>
  <span m=''4771010''>freshman</span> <span m=''4771465''>college</span> <span m=''4771920''>algebra.</span>
  </p><p><span m=''4774200''>So</span> <span m=''4774350''>that''s</span> <span m=''4774550''>what</span>
  <span m=''4774680''>happens</span> <span m=''4775050''>here.</span> <span m=''4779056''>It
  took</span> <span m=''4779450''>30</span> <span m=''4779760''>years</span> <span
  m=''4780000''>and</span> <span m=''4780090''>a</span> <span m=''4780180''>computer</span>
  <span m=''4780550''>scientist</span> <span m=''4781030''>to</span> <span m=''4781130''>solve</span>
  <span m=''4781310''>that</span> <span m=''4781490''>problem.</span> <span m=''4790380''>That</span>
  <span m=''4790550''>was</span> <span m=''4791990''>not</span> <span m=''4792570''>all</span>
  <span m=''4792770''>I</span> <span m=''4792850''>wanted</span> <span m=''4793080''>to</span>
  <span m=''4793310''>say,</span> <span m=''4794340''>but</span> <span m=''4794800''>that''s</span>
  <span m=''4795110''>all I have</span> <span m=''4795440''>time</span> <span m=''4795680''>for.</span>
  <span m=''4797425''>There''s</span> <span m=''4797870''>one</span> <span m=''4798110''>minute</span>
  <span m=''4798330''>left,</span> <span m=''4798660''>so</span> <span m=''4798790''>there''s
  no</span> <span m=''4799060''>point</span> <span m=''4799340''>in starting</span>
  <span m=''4799720''>something</span> <span m=''4800160''>now.</span> </p><p><span
  m=''4801060''>Do you have</span> <span m=''4801150''>any</span> <span m=''4801320''>questions</span>
  <span m=''4801710''>about</span> <span m=''4801980''>any of</span> <span m=''4802120''>this?</span>
  <span m=''4808882''>I</span> <span m=''4809370''>should</span> <span m=''4809600''>say</span>
  <span m=''4809770''>that</span> <span m=''4811650''>this</span> <span m=''4811930''>2</span>
  <span m=''4812270''>one</span> <span m=''4812460''>can</span> <span m=''4812710''>get</span>
  <span m=''4812900''>rid</span> <span m=''4813140''>of,</span> <span m=''4814020''>but</span>
  <span m=''4814130''>that</span> <span m=''4814350''>takes</span> <span m=''4814640''>a</span>
  <span m=''4814670''>little</span> <span m=''4814840''>bit</span> <span m=''4814970''>more</span>
  <span m=''4815160''>machinery.</span> <span m=''4818330''>The</span> <span m=''4818440''>2</span>
  <span m=''4818710''>one</span> <span m=''4818800''>can</span> <span m=''4819000''>get</span>
  <span m=''4819150''>rid</span> <span m=''4819370''>of,</span> <span m=''4819765''>but</span>
  <span m=''4820160''>that''s a</span> <span m=''4820320''>bit more</span> <span m=''4820470''>heavy.</span>
  <span m=''4824544''>All right.</span> <span m=''4825040''>So</span> <span m=''4825330''>thanks</span>
  <span m=''4825600''>so</span> <span m=''4825670''>much.</span> <span m=''4827530''>That''s</span>
  <span m=''4827710''>it.</span> <span m=''4828910''>That''s</span> <span m=''4829210''>it.</span>
  </p>'
type: course
uid: b0b90c8a2a42ab2a7c3bf7391f004c6d

---
None