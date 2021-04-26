---
about_this_resource_text: '<p><strong>Topics covered: </strong>Codes on Graphs</p><p><strong>Instructor:
  </strong>Prof. David Forney</p>'
course_id: 6-451-principles-of-digital-communication-ii-spring-2005
embedded_media:
- id: 17.jpg
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-17-codes-on-graphs/17.jpg
  title: 17.jpg
  type: null
  uid: ab68368825b0cea85d4492ac5e355124
- id: Video-YouTube-Stream
  media_location: DyRLOmVRQDw
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Video-YouTube-Stream
  type: Video
  uid: 1ea2161c64ed92b501c6d26513e19f2a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/DyRLOmVRQDw/default.jpg
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 6f6b8429e2b2890298e93a07f099cd08
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597857
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Video-iTunes U-MP4
  type: Video
  uid: 9995047c1538d31662a6921e3dd8cb23
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.451S05/17ocw-6.451_4-261-11apr2005-220k.mp4
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Video-Internet Archive-MP4
  type: Video
  uid: 39230fa89ec6789819e13ffa9324b6b7
- id: Thumbnail-OCW-JPG
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 82ce8958688b5085873b2796730e4928
- id: 3Play-3PlayYouTubeid-MP4
  media_location: DyRLOmVRQDw
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3eca8fda1f760d2b4e457c07b9bb93a5
- id: DyRLOmVRQDw.srt
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-17-codes-on-graphs/DyRLOmVRQDw.srt
  title: 3play caption file
  type: null
  uid: 05011b34c8bda9f85f723da708b4baa7
- id: DyRLOmVRQDw.pdf
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-17-codes-on-graphs/DyRLOmVRQDw.pdf
  title: 3play pdf file
  type: null
  uid: 246e78033b721bb45bce2738097a9979
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 29173ebdc97314a1004040b5f40ba0ad
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1ffb818d0630053e5f9b6a9864f72bce
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f7510ee3aa8a92675b81e8de0fad7f20
inline_embed_id: 93174121lecture17:codesongraphs4802416
layout: video
order_index: null
parent_uid: 73f9a1c91575f1a3abda44e7358df3a2
related_resources_text: ''
short_url: lecture-17-codes-on-graphs
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-17-codes-on-graphs
template_type: Tabbed
title: 'Lecture 17: Codes on Graphs'
transcript: '<p><span m=''490''>PROFESSOR: The</span> <span m=''730''>topic</span>
  <span m=''1210''>of</span> <span m=''1330''>this</span> <span m=''1550''>chapter</span>
  <span m=''2120''>is</span> <span m=''2400''>finding</span> <span m=''3280''>trellis</span>
  <span m=''3660''>representations</span> <span m=''4720''>for</span> <span m=''5280''>block</span>
  <span m=''5600''>codes,</span> <span m=''6130''>in</span> <span m=''6230''>particular</span>
  <span m=''7390''>linear</span> <span m=''8460''>block</span> <span m=''8690''>codes.</span>
  <span m=''9120''>We''re</span> <span m=''9260''>looking</span> <span m=''9580''>only</span>
  <span m=''9830''>at</span> <span m=''10420''>binary</span> <span m=''10780''>block</span>
  <span m=''11120''>codes,</span> <span m=''11560''>except</span> <span m=''11920''>one</span>
  <span m=''12070''>of</span> <span m=''12120''>the</span> <span m=''12270''>homework</span>
  <span m=''12630''>problems</span> <span m=''13080''>looks</span> <span m=''13360''>at</span>
  <span m=''13990''>MDS</span> <span m=''14590''>codes</span> <span m=''14990''>over</span>
  <span m=''15240''>ground field</span> <span m=''15380''>of</span> <span m=''15810''>q.</span>
  <span m=''16830''>The</span> <span m=''17440''>principles</span> <span m=''17960''>are</span>
  <span m=''18060''>the</span> <span m=''18170''>same</span> <span m=''18600''>for</span>
  <span m=''19750''>general</span> <span m=''20150''>Fq</span> <span m=''20660''>or</span>
  <span m=''20830''>in</span> <span m=''20930''>fact</span> <span m=''21300''>for</span>
  <span m=''21440''>group</span> <span m=''21720''>codes.</span> <span m=''23070''>We''re</span>
  <span m=''23230''>looking</span> <span m=''23570''>for</span> <span m=''23930''>minimal</span>
  <span m=''24540''>trellis</span> <span m=''24910''>representations.</span> </p><p><span
  m=''28270''>And</span> <span m=''28640''>so</span> <span m=''28890''>just</span>
  <span m=''29200''>to</span> <span m=''29300''>review</span> <span m=''30390''>our</span>
  <span m=''30650''>line</span> <span m=''30910''>of</span> <span m=''31020''>thought,</span>
  <span m=''31430''>basically</span> <span m=''32070''>we</span> <span m=''33280''>proved</span>
  <span m=''33810''>a</span> <span m=''34400''>basic</span> <span m=''34840''>theorem</span>
  <span m=''35340''>called the</span> <span m=''35680''>state</span> <span m=''36110''>space</span>
  <span m=''36450''>theorem</span> <span m=''36780''>that</span> <span m=''36900''>tells</span>
  <span m=''37250''>us</span> <span m=''37930''>that</span> <span m=''38840''>there</span>
  <span m=''39050''>is</span> <span m=''39380''>a</span> <span m=''41350''>vector</span>
  <span m=''41720''>space</span> <span m=''42470''>over</span> <span m=''42720''>the</span>
  <span m=''43340''>ground</span> <span m=''43730''>field</span> <span m=''44120''>at</span>
  <span m=''44340''>any</span> <span m=''44410''>time</span> <span m=''45340''>which</span>
  <span m=''45640''>we</span> <span m=''45770''>can</span> <span m=''45910''>identify</span>
  <span m=''46510''>with</span> <span m=''46750''>the</span> <span m=''47030''>state</span>
  <span m=''47440''>space.</span> <span m=''48330''>It</span> <span m=''48650''>has
  a</span> <span m=''48910''>certain</span> <span m=''49210''>dimension.</span> </p><p><span
  m=''50590''>And</span> <span m=''51900''>we</span> <span m=''52030''>got</span>
  <span m=''52210''>a</span> <span m=''52230''>little</span> <span m=''52460''>formula</span>
  <span m=''53760''>in</span> <span m=''53930''>terms</span> <span m=''54380''>of</span>
  <span m=''54630''>subcodes</span> <span m=''55470''>for</span> <span m=''55610''>the</span>
  <span m=''55710''>dimension</span> <span m=''56110''>of</span> <span m=''56150''>the</span>
  <span m=''56210''>state</span> <span m=''56560''>space.</span> <span m=''57850''>We</span>
  <span m=''58280''>set</span> <span m=''58500''>up</span> <span m=''58650''>a</span>
  <span m=''58720''>little</span> <span m=''58920''>generator</span> <span m=''59410''>matrix</span>
  <span m=''60030''>where</span> <span m=''60220''>we</span> <span m=''60390''>isolated</span>
  <span m=''61720''>the</span> <span m=''61830''>past</span> <span m=''62360''>part</span>
  <span m=''62600''>of</span> <span m=''62680''>the</span> <span m=''62770''>code</span>
  <span m=''63160''>with</span> <span m=''63280''>respect</span> <span m=''63790''>to</span>
  <span m=''63880''>a</span> <span m=''63940''>certain</span> <span m=''64330''>cut</span>
  <span m=''64750''>time</span> <span m=''65170''>future</span> <span m=''65610''>part</span>
  <span m=''65890''>of</span> <span m=''65980''>the</span> <span m=''66080''>code,</span>
  <span m=''66500''>generators</span> <span m=''67120''>for</span> <span m=''67250''>that.</span>
  <span m=''68120''>We</span> <span m=''68250''>subtract</span> <span m=''68840''>those</span>
  <span m=''69150''>generators</span> <span m=''69780''>out.</span> <span m=''71880''>What''s</span>
  <span m=''72200''>left?</span> <span m=''72610''>The</span> <span m=''72730''>number
  of</span> <span m=''73080''>generators</span> <span m=''73840''>is</span> <span
  m=''74160''>the</span> <span m=''75820''>number of</span> <span m=''76090''>generators</span>
  <span m=''76770''>it</span> <span m=''76950''>takes</span> <span m=''77410''>to</span>
  <span m=''78080''>generate</span> <span m=''78500''>the</span> <span m=''78590''>state</span>
  <span m=''78920''>space,</span> <span m=''79340''>in</span> <span m=''79390''>other</span>
  <span m=''79560''>words</span> <span m=''79850''>the</span> <span m=''79950''>dimension</span>
  <span m=''80420''>of</span> <span m=''80510''>the</span> <span m=''80600''>state</span>
  <span m=''80940''>space.</span> <span m=''81850''>So</span> <span m=''82140''>we</span>
  <span m=''82290''>got</span> <span m=''82670''>a</span> <span m=''83480''>theorem</span>
  <span m=''83950''>on</span> <span m=''84230''>the</span> <span m=''84350''>dimension</span>
  <span m=''84880''>of</span> <span m=''84950''>the</span> <span m=''85050''>state</span>
  <span m=''85360''>space</span> <span m=''85770''>at</span> <span m=''85850''>any</span>
  <span m=''86080''>time.</span> </p><p><span m=''87330''>And</span> <span m=''87610''>then</span>
  <span m=''87890''>we</span> <span m=''88070''>found</span> <span m=''88520''>a</span>
  <span m=''89060''>nifty</span> <span m=''89460''>little</span> <span m=''89880''>algorithm</span>
  <span m=''90610''>to</span> <span m=''90740''>find</span> <span m=''92740''>a --</span>
  <span m=''93300''>to</span> <span m=''93790''>determine</span> <span m=''94390''>the</span>
  <span m=''94660''>dimensions</span> <span m=''95260''>of</span> <span m=''95320''>the</span>
  <span m=''95850''>state</span> <span m=''96260''>spaces</span> <span m=''96670''>at</span>
  <span m=''96740''>all</span> <span m=''96980''>times,</span> <span m=''98260''>the</span>
  <span m=''98670''>minimal</span> <span m=''98980''>state</span> <span m=''99400''>spaces.</span>
  <span m=''100080''>And</span> <span m=''101620''>in</span> <span m=''101870''>fact</span>
  <span m=''103090''>we</span> <span m=''103280''>can</span> <span m=''103420''>use</span>
  <span m=''103660''>this</span> <span m=''103850''>algorithm</span> <span m=''104310''>to</span>
  <span m=''104430''>construct</span> <span m=''105070''>a</span> <span m=''105440''>minimal</span>
  <span m=''105860''>trellis</span> <span m=''106940''>realization.</span> <span m=''108095''>The</span>
  <span m=''108410''>algorithm</span> <span m=''109040''>involves</span> <span m=''109680''>a</span>
  <span m=''110180''>trellis-oriented</span> <span m=''111500''>generator</span> <span
  m=''111960''>matrix.</span> </p><p><span m=''113450''>And</span> <span m=''113830''>the</span>
  <span m=''114040''>idea</span> <span m=''114420''>here</span> <span m=''115580''>turns</span>
  <span m=''115830''>out</span> <span m=''115970''>to</span> <span m=''116040''>be</span>
  <span m=''116110''>very</span> <span m=''116340''>simple.</span> <span m=''117560''>All</span>
  <span m=''117720''>you</span> <span m=''117930''>do</span> <span m=''118140''>is</span>
  <span m=''119690''>you</span> <span m=''119820''>find</span> <span m=''120120''>any</span>
  <span m=''120350''>generator</span> <span m=''120790''>matrix</span> <span m=''121360''>for</span>
  <span m=''121550''>your</span> <span m=''122060''>linear</span> <span m=''122430''>block</span>
  <span m=''122790''>code,</span> <span m=''123780''>and</span> <span m=''123890''>you</span>
  <span m=''123990''>reduce</span> <span m=''124380''>it</span> <span m=''124490''>to</span>
  <span m=''124610''>trellis-oriented</span> <span m=''125500''>form.</span> <span
  m=''126910''>Trellis-oriented</span> <span m=''127750''>form</span> <span m=''128160''>means</span>
  <span m=''128419''>that</span> <span m=''128684''>the</span> <span m=''128949''>generators</span>
  <span m=''129699''>have</span> <span m=''129850''>as</span> <span m=''130009''>short
  a</span> <span m=''130509''>span</span> <span m=''130970''>as</span> <span m=''131130''>possible.</span>
  <span m=''131720''>It''s</span> <span m=''131980''>a</span> <span m=''132030''>minimum</span>
  <span m=''132280''>span</span> <span m=''133180''>generator</span> <span m=''133650''>matrix.</span>
  <span m=''134750''>And</span> <span m=''134870''>we</span> <span m=''135000''>do</span>
  <span m=''135200''>that</span> <span m=''135560''>just</span> <span m=''136040''>in</span>
  <span m=''136250''>a</span> <span m=''136310''>greedy</span> <span m=''136690''>fashion</span>
  <span m=''137240''>by</span> <span m=''137500''>any</span> <span m=''137740''>time</span>
  <span m=''137970''>we</span> <span m=''138060''>have</span> <span m=''138200''>an</span>
  <span m=''138320''>opportunity</span> <span m=''139740''>to</span> <span m=''140060''>add</span>
  <span m=''141200''>two</span> <span m=''141510''>generators</span> <span m=''142110''>together</span>
  <span m=''142580''>such</span> <span m=''142920''>that</span> <span m=''143770''>either</span>
  <span m=''144060''>their</span> <span m=''144230''>starting</span> <span m=''144670''>position</span>
  <span m=''145220''>cancels,</span> <span m=''145860''>or</span> <span m=''146170''>their
  end</span> <span m=''146430''>position</span> <span m=''146880''>cancels,</span>
  <span m=''147440''>we</span> <span m=''147560''>do</span> <span m=''147780''>it.</span>
  </p><p><span m=''148400''>And</span> <span m=''148720''>out</span> <span m=''148740''>of</span>
  <span m=''148890''>that</span> <span m=''149100''>we</span> <span m=''149220''>get</span>
  <span m=''149370''>a</span> <span m=''149440''>shorter</span> <span m=''150320''>generator,</span>
  <span m=''150940''>and</span> <span m=''151020''>we</span> <span m=''151210''>can</span>
  <span m=''151360''>replace</span> <span m=''152650''>one</span> <span m=''152850''>of</span>
  <span m=''152950''>the</span> <span m=''153070''>two</span> <span m=''153330''>generators</span>
  <span m=''153950''>in</span> <span m=''154020''>the</span> <span m=''154100''>combination</span>
  <span m=''154810''>by</span> <span m=''155050''>that.</span> <span m=''155730''>We
  can</span> <span m=''155920''>keep</span> <span m=''156130''>shortening</span> <span
  m=''156590''>everything</span> <span m=''157020''>up.</span> <span m=''158290''>The</span>
  <span m=''158430''>algorithm</span> <span m=''159190''>must</span> <span m=''159560''>terminate</span>
  <span m=''160670''>at</span> <span m=''160850''>the</span> <span m=''160940''>point</span>
  <span m=''161300''>where</span> <span m=''161520''>no</span> <span m=''161800''>further</span>
  <span m=''162880''>shortening</span> <span m=''163400''>is</span> <span m=''163540''>possible.</span>
  <span m=''166490''>And</span> <span m=''166760''>that</span> <span m=''166980''>is</span>
  <span m=''167250''>explicitly</span> <span m=''168120''>the</span> <span m=''168230''>point</span>
  <span m=''168640''>at</span> <span m=''168790''>which</span> <span m=''169480''>all</span>
  <span m=''169690''>the</span> <span m=''169750''>starting</span> <span m=''170160''>times</span>
  <span m=''170480''>of</span> <span m=''170610''>the</span> <span m=''170700''>generators</span>
  <span m=''171280''>are</span> <span m=''171320''>different,</span> <span m=''171780''>and</span>
  <span m=''171900''>all</span> <span m=''172040''>the</span> <span m=''172130''>ending</span>
  <span m=''172420''>times</span> <span m=''173350''>of</span> <span m=''173570''>all</span>
  <span m=''173750''>the</span> <span m=''173840''>generators</span> <span m=''174460''>are</span>
  <span m=''174590''>different.</span> </p><p><span m=''177000''>For</span> <span
  m=''177230''>example,</span> <span m=''177770''>here''s</span> <span m=''178060''>a</span>
  <span m=''178130''>trellis-oriented</span> <span m=''178890''>generator</span> <span
  m=''179330''>matrix.</span> <span m=''180660''>The</span> <span m=''181120''>starting</span>
  <span m=''181570''>times,</span> <span m=''182830''>the</span> <span m=''182940''>spans</span>
  <span m=''183470''>of</span> <span m=''183570''>the</span> <span m=''183680''>generators,</span>
  <span m=''185330''>are</span> <span m=''186100''>like</span> <span m=''186350''>this.</span>
  <span m=''186820''>The</span> <span m=''187000''>active</span> <span m=''187440''>times,</span>
  <span m=''188530''>starting</span> <span m=''189030''>times --</span> <span m=''189600''>there''s</span>
  <span m=''189900''>the</span> <span m=''189990''>starting</span> <span m=''190390''>time
  of</span> <span m=''190710''>this</span> <span m=''191000''>one,</span> <span m=''191230''>and</span>
  <span m=''191440''>its</span> <span m=''191710''>ending</span> <span m=''192230''>time.</span>
  <span m=''193180''>Here''s</span> <span m=''193490''>the</span> <span m=''193580''>starting</span>
  <span m=''194010''>time</span> <span m=''194300''>of</span> <span m=''194380''>the</span>
  <span m=''194470''>next</span> <span m=''194830''>one,</span> <span m=''195150''>and</span>
  <span m=''195310''>its</span> <span m=''195480''>ending</span> <span m=''195940''>time.</span>
  <span m=''196530''>The</span> <span m=''197020''>starting</span> <span m=''197470''>time</span>
  <span m=''197740''>of</span> <span m=''197820''>the</span> <span m=''197910''>next</span>
  <span m=''198260''>one,</span> <span m=''199220''>and</span> <span m=''199890''>its</span>
  <span m=''200130''>ending</span> <span m=''200490''>time</span> <span m=''200840''>is</span>
  <span m=''200980''>here.</span> <span m=''201920''>And</span> <span m=''202250''>the</span>
  <span m=''202320''>starting</span> <span m=''202790''>time</span> <span m=''203120''>of</span>
  <span m=''203370''>this</span> <span m=''203620''>one,</span> <span m=''203870''>and</span>
  <span m=''204070''>its</span> <span m=''204930''>ending</span> <span m=''205230''>time</span>
  <span m=''205700''>is here.</span> </p><p><span m=''207260''>We''re</span> <span
  m=''207460''>not</span> <span m=''207660''>always</span> <span m=''208030''>going</span>
  <span m=''208140''>to</span> <span m=''208210''>find</span> <span m=''208520''>that</span>
  <span m=''208830''>the</span> <span m=''209070''>starting</span> <span m=''209540''>and</span>
  <span m=''209610''>ending</span> <span m=''209920''>times</span> <span m=''210310''>are</span>
  <span m=''210420''>disjoint.</span> <span m=''213180''>This</span> <span m=''213520''>happens,</span>
  <span m=''214250''>it</span> <span m=''214440''>turns</span> <span m=''214790''>out,</span>
  <span m=''215020''>because</span> <span m=''215420''>this</span> <span m=''215630''>is</span>
  <span m=''215840''>a</span> <span m=''216450''>self-dual</span> <span m=''217180''>code.</span>
  <span m=''217500''>In</span> <span m=''217630''>a</span> <span m=''217690''>self-dual</span>
  <span m=''218380''>code,</span> <span m=''218670''>you will</span> <span m=''218900''>always</span>
  <span m=''219240''>get</span> <span m=''219490''>this</span> <span m=''220470''>each</span>
  <span m=''220750''>time,</span> <span m=''221130''>either</span> <span m=''221460''>a</span>
  <span m=''221520''>starting</span> <span m=''221950''>time</span> <span m=''222250''>or</span>
  <span m=''222340''>an</span> <span m=''222410''>ending</span> <span m=''222690''>time.</span>
  <span m=''223190''>But</span> <span m=''223350''>that''s</span> <span m=''223620''>not</span>
  <span m=''223830''>a</span> <span m=''223900''>general</span> <span m=''224280''>property.</span>
  </p><p><span m=''225410''>For</span> <span m=''225550''>instance,</span> <span m=''226000''>another</span>
  <span m=''227350''>example</span> <span m=''228220''>that</span> <span m=''228360''>we''ve</span>
  <span m=''228440''>used</span> <span m=''228930''>is,</span> <span m=''230160''>say,</span>
  <span m=''230520''>the</span> <span m=''230770''>8</span> <span m=''231425''>7</span>
  <span m=''232580''>2</span> <span m=''233200''>single</span> <span m=''233560''>parity</span>
  <span m=''233960''>check</span> <span m=''234390''>code.</span> <span m=''236010''>What</span>
  <span m=''236180''>are</span> <span m=''236340''>its</span> <span m=''236780''>generators?</span>
  <span m=''238880''>Its</span> <span m=''240280''>generators</span> <span m=''241090''>look</span>
  <span m=''241330''>like</span> <span m=''241640''>this,</span> <span m=''246845''>dot,</span>
  <span m=''247077''>dot,</span> <span m=''247310''>dot,</span> <span m=''248240''>down</span>
  <span m=''248610''>to</span> <span m=''248900''>0,</span> <span m=''249280''>0,</span>
  <span m=''249730''>1,</span> <span m=''250030''>1.</span> <span m=''251190''>That''s</span>
  <span m=''251430''>a</span> <span m=''251700''>set of</span> <span m=''252170''>trellis-oriented</span>
  <span m=''252780''>generators</span> <span m=''253130''>with</span> <span m=''253560''>starting</span>
  <span m=''254040''>time,</span> <span m=''254750''>ending</span> <span m=''254900''>time,</span>
  <span m=''255620''>the</span> <span m=''255680''>first</span> <span m=''256079''>one</span>
  <span m=''256190''>here.</span> <span m=''256990''>Starting</span> <span m=''257500''>time,</span>
  <span m=''257910''>ending</span> <span m=''258269''>time</span> <span m=''258610''>of</span>
  <span m=''258670''>the</span> <span m=''258760''>second</span> <span m=''259149''>one</span>
  <span m=''259430''>there.</span> <span m=''260390''>So</span> <span m=''261700''>in</span>
  <span m=''261880''>general</span> <span m=''262280''>for</span> <span m=''262430''>this</span>
  <span m=''262720''>one,</span> <span m=''263130''>every</span> <span m=''263420''>time</span>
  <span m=''263790''>is</span> <span m=''263920''>a</span> <span m=''264000''>starting</span>
  <span m=''264470''>and</span> <span m=''264570''>ending</span> <span m=''264970''>time</span>
  <span m=''266050''>up</span> <span m=''266250''>to</span> <span m=''266550''>here,</span>
  <span m=''267080''>where</span> <span m=''268460''>every</span> <span m=''268730''>intermediate</span>
  <span m=''269320''>time</span> <span m=''269680''>is</span> <span m=''270310''>both</span>
  <span m=''270870''>the</span> <span m=''270950''>starting</span> <span m=''271400''>and
  an</span> <span m=''271580''>ending</span> <span m=''271940''>time.</span> </p><p><span
  m=''272690''>So</span> <span m=''272980''>it</span> <span m=''273370''>could</span>
  <span m=''273540''>happen</span> <span m=''273870''>that</span> <span m=''274130''>way,</span>
  <span m=''275330''>or</span> <span m=''277330''>another</span> <span m=''277640''>example</span>
  <span m=''278340''>would</span> <span m=''278590''>be</span> <span m=''278850''>the</span>
  <span m=''280970''>8</span> <span m=''281420''>1</span> <span m=''281880''>8</span>
  <span m=''282490''>repetition</span> <span m=''283280''>code.</span> <span m=''284870''>What''s</span>
  <span m=''285280''>a</span> <span m=''285780''>trellis-oriented</span> <span m=''286100''>generator</span>
  <span m=''286560''>matrix</span> <span m=''287020''>for</span> <span m=''287140''>that?</span>
  <span m=''287590''>It only</span> <span m=''287800''>has</span> <span m=''288000''>one</span>
  <span m=''288230''>generator.</span> <span m=''288545''>It</span> <span m=''288860''>looks</span>
  <span m=''289100''>like</span> <span m=''289330''>that.</span> <span m=''289690''>It
  has</span> <span m=''289870''>a</span> <span m=''289920''>starting</span> <span
  m=''291170''>span</span> <span m=''291460''>as</span> <span m=''291580''>the</span>
  <span m=''291680''>whole</span> <span m=''291910''>thing.</span> <span m=''292230''>The
  starting</span> <span m=''292630''>time</span> <span m=''292890''>is</span> <span
  m=''293010''>here.</span> <span m=''293230''>The</span> <span m=''293370''>ending</span>
  <span m=''293600''>time is</span> <span m=''293990''>here.</span> <span m=''295720''>So</span>
  <span m=''297680''>for</span> <span m=''297830''>general</span> <span m=''298230''>codes,</span>
  <span m=''299040''>the</span> <span m=''299100''>starting</span> <span m=''299480''>times</span>
  <span m=''299850''>and ending</span> <span m=''300180''>times</span> <span m=''300880''>could</span>
  <span m=''301000''>be</span> <span m=''301120''>anywhere.</span> <span m=''301500''>There
  will</span> <span m=''301690''>always</span> <span m=''302000''>be</span> <span
  m=''302130''>k</span> <span m=''302400''>of</span> <span m=''302560''>them.</span>
  </p><p><span m=''304740''>And</span> <span m=''306760''>otherwise,</span> <span
  m=''308150''>there''s</span> <span m=''308450''>always</span> <span m=''308670''>one</span>
  <span m=''308860''>at</span> <span m=''308940''>the</span> <span m=''309010''>beginning.</span>
  <span m=''309480''>If</span> <span m=''309630''>it''s</span> <span m=''309800''>a</span>
  <span m=''309870''>nontrivial</span> <span m=''310370''>code,</span> <span m=''310750''>there''s</span>
  <span m=''311060''>always</span> <span m=''311270''>an ending</span> <span m=''311600''>time</span>
  <span m=''311860''>at</span> <span m=''311940''>the</span> <span m=''312200''>end,</span>
  <span m=''312500''>et cetera.</span> <span m=''312970''>But</span> <span m=''314770''>this</span>
  <span m=''315000''>particular</span> <span m=''315520''>behavior</span> <span m=''316120''>is
  for</span> <span m=''316880''>self-dual</span> <span m=''317520''>codes.</span>
  </p><p><span m=''319380''>Anyway,</span> <span m=''319800''>having</span> <span
  m=''320090''>done</span> <span m=''320350''>that</span> <span m=''321550''>we</span>
  <span m=''321810''>can</span> <span m=''321990''>now</span> <span m=''323000''>read</span>
  <span m=''323360''>off</span> <span m=''323910''>the</span> <span m=''324340''>dimensions</span>
  <span m=''324970''>of</span> <span m=''325030''>the</span> <span m=''325110''>state</span>
  <span m=''325580''>spaces</span> <span m=''326880''>by</span> <span m=''327250''>simply</span>
  <span m=''327780''>looking</span> <span m=''328140''>for</span> <span m=''328390''>how</span>
  <span m=''328610''>many</span> <span m=''328840''>generators</span> <span m=''329530''>are</span>
  <span m=''329700''>active</span> <span m=''330330''>at</span> <span m=''330710''>any</span>
  <span m=''331090''>particular</span> <span m=''332190''>time.</span> <span m=''332980''>For</span>
  <span m=''333120''>a</span> <span m=''333180''>state</span> <span m=''333530''>space,</span>
  <span m=''333930''>we''re</span> <span m=''334070''>always</span> <span m=''334310''>looking</span>
  <span m=''334540''>at</span> <span m=''334610''>the</span> <span m=''334730''>times</span>
  <span m=''335670''>between</span> <span m=''336140''>the</span> <span m=''336230''>symbols,</span>
  <span m=''337230''>cut</span> <span m=''337410''>times.</span> <span m=''338830''>We
  could</span> <span m=''339010''>in</span> <span m=''339120''>fact</span> <span m=''339420''>draw</span>
  <span m=''339720''>a</span> <span m=''340060''>trivial</span> <span m=''340400''>one</span>
  <span m=''340690''>there,</span> <span m=''341050''>but</span> <span m=''341170''>we''re</span>
  <span m=''341310''>looking</span> <span m=''341630''>between</span> <span m=''342060''>here.</span>
  </p><p><span m=''342850''>How</span> <span m=''342990''>many</span> <span m=''343200''>are</span>
  <span m=''343310''>active</span> <span m=''343680''>at</span> <span m=''343790''>this</span>
  <span m=''344040''>time?</span> <span m=''344560''>One.</span> <span m=''345840''>So</span>
  <span m=''346330''>dimension</span> <span m=''347050''>of</span> <span m=''347120''>the</span>
  <span m=''347560''>state</span> <span m=''347890''>space</span> <span m=''348470''>at</span>
  <span m=''348730''>state</span> <span m=''349120''>time</span> <span m=''349470''>k</span>
  <span m=''350660''>is</span> <span m=''351140''>1,</span> <span m=''352790''>2,</span>
  <span m=''354170''>3.</span> <span m=''355750''>This</span> <span m=''355880''>point,</span>
  <span m=''356640''>we</span> <span m=''356850''>come</span> <span m=''357040''>back</span>
  <span m=''357340''>to 2</span> <span m=''357690''>again.</span> <span m=''359040''>3,</span>
  <span m=''360240''>2,</span> <span m=''360810''>1,</span> <span m=''361910''>0,</span>
  <span m=''362690''>0</span> <span m=''362950''>at the</span> <span m=''363220''>end.</span>
  <span m=''363490''>It''s</span> <span m=''363790''>always</span> <span m=''363920''>zero</span>
  <span m=''364160''>at</span> <span m=''364280''>the</span> <span m=''364410''>ends</span>
  <span m=''364820''>because</span> <span m=''365190''>at</span> <span m=''365260''>that</span>
  <span m=''365500''>point</span> <span m=''365750''>everything''s</span> <span m=''366220''>in</span>
  <span m=''366310''>the</span> <span m=''366390''>future,</span> <span m=''367460''>or</span>
  <span m=''367620''>everything</span> <span m=''367950''>is</span> <span m=''368070''>in</span>
  <span m=''368160''>the</span> <span m=''368240''>past.</span> </p><p><span m=''371040''>So</span>
  <span m=''371330''>these</span> <span m=''371550''>are</span> <span m=''371630''>trivial</span>
  <span m=''372050''>state</span> <span m=''372400''>spaces.</span> <span m=''373020''>These</span>
  <span m=''373290''>are</span> <span m=''373520''>the</span> <span m=''373650''>nontrivial</span>
  <span m=''374330''>state</span> <span m=''374730''>spaces</span> <span m=''375990''>in</span>
  <span m=''376140''>the</span> <span m=''376490''>trellis.</span> <span m=''378150''>And</span>
  <span m=''378310''>in</span> <span m=''378370''>fact,</span> <span m=''378770''>you</span>
  <span m=''378930''>remember</span> <span m=''379350''>we</span> <span m=''379530''>had</span>
  <span m=''379950''>a</span> <span m=''380970''>little</span> <span m=''381240''>picture.</span>
  <span m=''381980''>We</span> <span m=''382200''>can</span> <span m=''382540''>draw</span>
  <span m=''382810''>this</span> <span m=''383030''>complete</span> <span m=''383400''>trellis</span>
  <span m=''383840''>out</span> <span m=''384110''>with</span> <span m=''384190''>the</span>
  <span m=''384280''>state</span> <span m=''384670''>spaces</span> <span m=''385630''>of</span>
  <span m=''385770''>size</span> <span m=''386910''>1</span> <span m=''387310''>2</span>
  <span m=''387780''>4</span> <span m=''388320''>8</span> <span m=''388710''>4</span>
  <span m=''389320''>8</span> <span m=''389740''>4</span> <span m=''390310''>2</span>
  <span m=''390770''>1.</span> <span m=''392430''>So</span> <span m=''392640''>this</span>
  <span m=''392850''>is</span> <span m=''393020''>called</span> <span m=''393380''>the</span>
  <span m=''394020''>state</span> <span m=''394420''>dimension</span> <span m=''394940''>profile,</span>
  <span m=''395720''>just</span> <span m=''396060''>this</span> <span m=''397060''>set,</span>
  <span m=''397990''>this</span> <span m=''398210''>ordered</span> <span m=''398550''>set.</span>
  <span m=''399640''>Or</span> <span m=''400300''>the</span> <span m=''400430''>state</span>
  <span m=''400800''>space</span> <span m=''401170''>size</span> <span m=''401560''>profile</span>
  <span m=''402240''>is</span> <span m=''402420''>2</span> <span m=''402640''>to</span>
  <span m=''402740''>the</span> <span m=''403270''>dimension,</span> <span m=''404380''>of</span>
  <span m=''404470''>binary</span> <span m=''404940''>codes,</span> <span m=''405730''>whatever.</span>
  </p><p><span m=''407260''>And</span> <span m=''407490''>similarly</span> <span m=''407940''>down</span>
  <span m=''408260''>here,</span> <span m=''408640''>if</span> <span m=''408740''>we</span>
  <span m=''408840''>look</span> <span m=''409090''>at</span> <span m=''409350''>state</span>
  <span m=''409710''>space</span> <span m=''410050''>sizes,</span> <span m=''410560''>we</span>
  <span m=''410660''>see</span> <span m=''411580''>the</span> <span m=''411690''>dimension</span>
  <span m=''412230''>is</span> <span m=''412490''>going</span> <span m=''412600''>to</span>
  <span m=''412720''>be</span> <span m=''412850''>one at</span> <span m=''413350''>every</span>
  <span m=''413610''>time.</span> <span m=''415600''>So</span> <span m=''415810''>in</span>
  <span m=''415870''>this</span> <span m=''416090''>case,</span> <span m=''416540''>the</span>
  <span m=''416620''>dimension</span> <span m=''417130''>of</span> <span m=''417180''>the</span>
  <span m=''417280''>state</span> <span m=''417670''>space</span> <span m=''418605''>is</span>
  <span m=''419020''>0,</span> <span m=''419110''>1,</span> <span m=''419430''>1,</span>
  <span m=''419860''>1,</span> <span m=''420130''>1,</span> <span m=''420390''>1,</span>
  <span m=''420620''>1,</span> <span m=''420830''>1,</span> <span m=''421070''>1,</span>
  <span m=''421770''>0.</span> <span m=''422870''>And</span> <span m=''423050''>similarly</span>
  <span m=''423400''>down</span> <span m=''423690''>here,</span> <span m=''424150''>we</span>
  <span m=''424280''>look</span> <span m=''424490''>at</span> <span m=''424550''>the</span>
  <span m=''424760''>cut</span> <span m=''424990''>time.</span> <span m=''425320''>It</span>
  <span m=''425430''>cuts</span> <span m=''425880''>one</span> <span m=''426700''>active</span>
  <span m=''427100''>generator</span> <span m=''427620''>every</span> <span m=''427860''>time.</span>
  <span m=''428250''>So</span> <span m=''428470''>it''s</span> <span m=''428590''>0,</span>
  <span m=''428900''>1,</span> <span m=''429310''>1,</span> <span m=''429610''>1,</span>
  <span m=''429810''>1,</span> <span m=''430170''>1,</span> <span m=''431640''>0.</span>
  <span m=''432730''>So</span> <span m=''432970''>we</span> <span m=''433100''>get</span>
  <span m=''433850''>at</span> <span m=''433960''>least</span> <span m=''434320''>the</span>
  <span m=''434500''>state</span> <span m=''434840''>space</span> <span m=''435230''>dimensions</span>
  <span m=''436400''>just</span> <span m=''436620''>by</span> <span m=''436810''>inspection</span>
  <span m=''437460''>of</span> <span m=''437530''>the</span> <span m=''437630''>trellis-oriented</span>
  <span m=''438470''>generator</span> <span m=''438960''>matrix.</span> </p><p><span
  m=''443430''>Question?</span> </p><p><span m=''443885''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''447500''>PROFESSOR: We</span> <span m=''448040''>proved</span>
  <span m=''448350''>it</span> <span m=''449390''>in</span> <span m=''449470''>several</span>
  <span m=''449770''>steps.</span> <span m=''450200''>First</span> <span m=''450470''>we</span>
  <span m=''450530''>have</span> <span m=''450650''>the</span> <span m=''450730''>state</span>
  <span m=''451090''>space</span> <span m=''451490''>theorem,</span> <span m=''457780''>which</span>
  <span m=''458230''>I</span> <span m=''458320''>gave</span> <span m=''458730''>to</span>
  <span m=''458860''>you</span> <span m=''459100''>in</span> <span m=''459160''>the</span>
  <span m=''459270''>following</span> <span m=''459770''>form:</span> <span m=''460300''>the</span>
  <span m=''460490''>dimension</span> <span m=''460870''>of the</span> <span m=''460970''>state</span>
  <span m=''461340''>space</span> <span m=''461770''>at</span> <span m=''461870''>time</span>
  <span m=''462980''>k</span> <span m=''463410''>is</span> <span m=''463760''>equal</span>
  <span m=''464180''>to</span> <span m=''464430''>the</span> <span m=''464630''>dimension</span>
  <span m=''465460''>of</span> <span m=''465620''>the</span> <span m=''465790''>code</span>
  <span m=''466280''>minus</span> <span m=''467530''>the</span> <span m=''468680''>past</span>
  <span m=''469160''>subcode.</span> <span m=''469940''>Let</span> <span m=''470040''>me</span>
  <span m=''470180''>write</span> <span m=''470480''>that.</span> <span m=''470840''>The</span>
  <span m=''470920''>dimension</span> <span m=''471330''>of</span> <span m=''471380''>the</span>
  <span m=''471460''>past</span> <span m=''471780''>subcode</span> <span m=''474090''>minus</span>
  <span m=''474530''>the</span> <span m=''474620''>dimension</span> <span m=''475210''>of</span>
  <span m=''475580''>the</span> <span m=''476360''>future</span> <span m=''476950''>subcode</span>
  <span m=''477760''>at</span> <span m=''477980''>time</span> <span m=''478440''>k</span>
  <span m=''478770''>relative</span> <span m=''479200''>to</span> <span m=''479310''>this</span>
  <span m=''479570''>cut</span> <span m=''479820''>time.</span> </p><p><span m=''481500''>And</span>
  <span m=''482870''>we</span> <span m=''483040''>proved</span> <span m=''483500''>from
  the</span> <span m=''483690''>trellis-oriented</span> <span m=''484480''>generator</span>
  <span m=''484960''>matrix</span> <span m=''485460''>that</span> <span m=''485520''>the</span>
  <span m=''485620''>past</span> <span m=''486200''>subcode</span> <span m=''486700''>is</span>
  <span m=''486840''>generated</span> <span m=''487330''>by</span> <span m=''487900''>all</span>
  <span m=''488110''>the</span> <span m=''488180''>trellis-oriented</span> <span m=''488990''>generators</span>
  <span m=''489700''>that</span> <span m=''489820''>have</span> <span m=''490000''>support</span>
  <span m=''490380''>on</span> <span m=''490480''>the</span> <span m=''490560''>past,</span>
  <span m=''491660''>and</span> <span m=''491780''>the</span> <span m=''491850''>future</span>
  <span m=''492250''>by all</span> <span m=''492680''>the ones</span> <span m=''493000''>that
  have</span> <span m=''493120''>support</span> <span m=''493540''>on</span> <span
  m=''493610''>the</span> <span m=''493680''>future.</span> <span m=''495040''>So,</span>
  <span m=''495540''>it''s</span> <span m=''495710''>simply</span> <span m=''496240''>we</span>
  <span m=''496430''>take</span> <span m=''496700''>those</span> <span m=''497000''>out.</span>
  <span m=''498220''>And</span> <span m=''498350''>what</span> <span m=''498490''>do
  we</span> <span m=''498590''>have</span> <span m=''498750''>left?</span> <span m=''499110''>We</span>
  <span m=''499190''>have</span> <span m=''499290''>the</span> <span m=''499370''>ones</span>
  <span m=''499740''>that</span> <span m=''499950''>are</span> <span m=''500990''>active</span>
  <span m=''502060''>at</span> <span m=''502230''>time</span> <span m=''502520''>k,</span>
  <span m=''502990''>the ones</span> <span m=''503540''>that</span> <span m=''503650''>are</span>
  <span m=''503730''>neither</span> <span m=''504110''>wholly</span> <span m=''505200''>supported</span>
  <span m=''505630''>on</span> <span m=''505780''>the</span> <span m=''505850''>past</span>
  <span m=''506340''>nor on</span> <span m=''506560''>the</span> <span m=''506640''>future.</span>
  <span m=''506990''>They''re</span> <span m=''507340''>supported</span> <span m=''507770''>both</span>
  <span m=''508100''>on</span> <span m=''508200''>the</span> <span m=''508290''>past</span>
  <span m=''508720''>and</span> <span m=''508810''>future.</span> <span m=''509870''>And</span>
  <span m=''510030''>those,</span> <span m=''511460''>that''s</span> <span m=''511730''>what</span>
  <span m=''511910''>this</span> <span m=''512120''>difference</span> <span m=''512519''>is.</span>
  </p><p><span m=''516580''>So</span> <span m=''517870''>explicitly</span> <span m=''518640''>we</span>
  <span m=''518820''>have --</span> <span m=''519590''>the</span> <span m=''519679''>code</span>
  <span m=''520130''>is</span> <span m=''520669''>generated</span> <span m=''521299''>by</span>
  <span m=''522960''>all</span> <span m=''523299''>generators.</span> <span m=''526580''>That''s</span>
  <span m=''527270''>all</span> <span m=''527530''>k</span> <span m=''527870''>generators.</span>
  <span m=''529210''>Cpk</span> <span m=''530900''>is</span> <span m=''531190''>generated</span>
  <span m=''531790''>by</span> <span m=''533540''>trellis-oriented</span> <span m=''534500''>generators</span>
  <span m=''538340''>supported</span> <span m=''539090''>on</span> <span m=''539600''>the</span>
  <span m=''539710''>past.</span> <span m=''541690''>And</span> <span m=''542110''>Cfk</span>
  <span m=''543250''>is</span> <span m=''543500''>generated</span> <span m=''543970''>by</span>
  <span m=''544780''>the</span> <span m=''544860''>trellis-oriented</span> <span m=''545480''>generators</span>
  <span m=''546070''>supported</span> <span m=''546340''>on</span> <span m=''546610''>the</span>
  <span m=''546850''>future.</span> </p><p><span m=''549840''>So</span> <span m=''550150''>the</span>
  <span m=''550270''>difference --</span> <span m=''551880''>state</span> <span m=''552340''>code</span>
  <span m=''553140''>sk</span> <span m=''553560''>is</span> <span m=''553880''>generated</span>
  <span m=''554440''>by</span> <span m=''555540''>the</span> <span m=''555740''>trellis-oriented</span>
  <span m=''556670''>generators</span> <span m=''559370''>not</span> <span m=''559640''>supported</span>
  <span m=''560030''>on</span> <span m=''560250''>past or</span> <span m=''560650''>future,</span>
  <span m=''560935''>or</span> <span m=''561500''>active</span> <span m=''563940''>at</span>
  <span m=''564640''>time</span> <span m=''564940''>k.</span> <span m=''568020''>Probably</span>
  <span m=''568280''>good</span> <span m=''568500''>to</span> <span m=''568580''>write</span>
  <span m=''568790''>all</span> <span m=''568920''>that out</span> <span m=''569070''>at</span>
  <span m=''569420''>least</span> <span m=''569780''>once.</span> <span m=''572060''>Yeah?</span>
  </p><p><span m=''572772''>AUDIENCE: [INAUDIBLE]</span> <span m=''574218''>self-dual</span>
  <span m=''574700''>codes</span> <span m=''575182''>all have</span> <span m=''575664''>such</span>
  <span m=''576146''>properties</span> <span m=''576628''>that</span> <span m=''577110''>each</span>
  <span m=''577592''>time</span> <span m=''578074''>is starting</span> <span m=''578560''>and
  ending?</span> </p><p><span m=''579270''>PROFESSOR: Yes.</span> </p><p><span m=''581145''>AUDIENCE:
  Why</span> <span m=''581630''>is that?</span> </p><p><span m=''582390''>PROFESSOR:
  Why?</span> <span m=''583025''>It''s</span> <span m=''583280''>a</span> <span m=''583690''>duality</span>
  <span m=''584220''>theorem,</span> <span m=''584610''>and</span> <span m=''584930''>we''re</span>
  <span m=''585110''>not</span> <span m=''585380''>doing</span> <span m=''586130''>many</span>
  <span m=''586280''>duality</span> <span m=''586820''>theorems</span> <span m=''587040''>in</span>
  <span m=''587140''>this</span> <span m=''587390''>course,</span> <span m=''587800''>so</span>
  <span m=''588130''>I''ll</span> <span m=''588530''>simply tell</span> <span m=''588690''>you.</span>
  </p><p><span m=''589870''>AUDIENCE: [INAUDIBLE]</span> <span m=''591770''>has</span>
  <span m=''592245''>this</span> <span m=''592720''>property,</span> <span m=''593195''>it
  must</span> <span m=''593670''>be a</span> <span m=''594145''>self-dual.</span>
  </p><p><span m=''595990''>PROFESSOR: I</span> <span m=''596200''>don''t</span> <span
  m=''596460''>think</span> <span m=''596630''>that''s</span> <span m=''596930''>true.</span>
  <span m=''601100''>It''s</span> <span m=''601980''>possible</span> <span m=''602470''>that''s</span>
  <span m=''602750''>true.</span> <span m=''604190''>Duality</span> <span m=''604570''>theorems</span>
  <span m=''604780''>are</span> <span m=''604950''>very</span> <span m=''605190''>strong,</span>
  <span m=''605600''>but</span> <span m=''605790''>I</span> <span m=''605810''>don''t</span>
  <span m=''606010''>think</span> <span m=''606840''>this is a</span> <span m=''607060''>sufficient</span>
  <span m=''607620''>property.</span> </p><p><span m=''611990''>For instance,</span>
  <span m=''612530''>suppose</span> <span m=''612800''>I</span> <span m=''612890''>just</span>
  <span m=''613110''>changed</span> <span m=''613540''>one</span> <span m=''613660''>of</span>
  <span m=''613750''>the</span> <span m=''613840''>generators</span> <span m=''614145''>to</span>
  <span m=''614450''>look</span> <span m=''614660''>like</span> <span m=''614870''>that.</span>
  <span m=''617300''>It still</span> <span m=''617560''>has</span> <span m=''619960''>disjoint</span>
  <span m=''620470''>starting</span> <span m=''620850''>and</span> <span m=''620930''>ending</span>
  <span m=''621210''>times,</span> <span m=''622500''>but</span> <span m=''622650''>now</span>
  <span m=''622840''>I</span> <span m=''622930''>don''t</span> <span m=''623120''>think</span>
  <span m=''623270''>the</span> <span m=''623370''>code</span> <span m=''623620''>is
  self-dual.</span> <span m=''626920''>So</span> <span m=''627510''>here''s</span>
  <span m=''627790''>another</span> <span m=''628160''>code</span> <span m=''628960''>generated</span>
  <span m=''629440''>by</span> <span m=''629590''>these</span> <span m=''629890''>four</span>
  <span m=''630100''>generators,</span> <span m=''630730''>and</span> <span m=''631120''>I</span>
  <span m=''631510''>don''t believe </span> <span m=''632305''>self-dual.</span> </p><p><span
  m=''633740''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''636440''>PROFESSOR: I''m</span>
  <span m=''637230''>guessing</span> <span m=''637620''>that</span> <span m=''637750''>it</span>
  <span m=''637870''>isn''t.</span> <span m=''638370''>To</span> <span m=''638540''>prove</span>
  <span m=''638940''>it</span> <span m=''639160''>I</span> <span m=''639310''>would</span>
  <span m=''640420''>compute</span> <span m=''640840''>the</span> <span m=''640940''>dual</span>
  <span m=''641260''>code,</span> <span m=''643180''>and</span> <span m=''643840''>I</span>
  <span m=''644000''>would</span> <span m=''644160''>find that</span> <span m=''644520''>it</span>
  <span m=''644610''>wasn''t</span> <span m=''644960''>same</span> <span m=''645210''>code,</span>
  <span m=''645610''>didn''t</span> <span m=''646060''>have the</span> <span m=''646200''>same</span>
  <span m=''646370''>code words.</span> <span m=''649980''>But</span> <span m=''650130''>I''m</span>
  <span m=''650540''>guessing</span> <span m=''650960''>that</span> <span m=''651100''>if</span>
  <span m=''651240''>I</span> <span m=''651330''>just</span> <span m=''651570''>make</span>
  <span m=''651800''>random</span> <span m=''652570''>changes</span> <span m=''653120''>in</span>
  <span m=''653180''>the</span> <span m=''653310''>interior</span> <span m=''653700''>here,</span>
  <span m=''654090''>I''m</span> <span m=''654250''>not</span> <span m=''654450''>going</span>
  <span m=''654550''>to</span> <span m=''654600''>get</span> <span m=''654820''>a</span>
  <span m=''655060''>self-dual</span> <span m=''655570''>code,</span> <span m=''655860''>because</span>
  <span m=''656030''>that''s</span> <span m=''656270''>a</span> <span m=''656310''>very</span>
  <span m=''656580''>strong</span> <span m=''657450''>structural</span> <span m=''657950''>property.</span>
  <span m=''659650''>But</span> <span m=''659970''>I''m</span> <span m=''660060''>not</span>
  <span m=''660250''>going</span> <span m=''660350''>to</span> <span m=''660390''>take
  the</span> <span m=''660700''>time</span> <span m=''661060''>in</span> <span m=''661140''>class</span>
  <span m=''661570''>to do</span> <span m=''661976''>that.</span> </p><p><span m=''663600''>But</span>
  <span m=''663780''>these</span> <span m=''663980''>are</span> <span m=''664040''>good</span>
  <span m=''664240''>questions.</span> <span m=''666650''>The</span> <span m=''667420''>whole</span>
  <span m=''667690''>subject</span> <span m=''668130''>of</span> <span m=''668230''>duality</span>
  <span m=''668860''>is</span> <span m=''669050''>a</span> <span m=''669290''>wonderful</span>
  <span m=''669950''>and</span> <span m=''670100''>elegant</span> <span m=''671410''>topic</span>
  <span m=''671900''>that</span> <span m=''671990''>we</span> <span m=''672130''>just</span>
  <span m=''672320''>don''t</span> <span m=''672520''>have</span> <span m=''672670''>time</span>
  <span m=''672970''>to</span> <span m=''673050''>do</span> <span m=''673210''>much</span>
  <span m=''673520''>in</span> <span m=''673660''>this</span> <span m=''673810''>course.</span>
  <span m=''674230''>If I</span> <span m=''675160''>did it</span> <span m=''675230''>another</span>
  <span m=''675650''>time,</span> <span m=''676000''>I</span> <span m=''676080''>could</span>
  <span m=''676290''>spend</span> <span m=''677050''>many</span> <span m=''677320''>lectures</span>
  <span m=''677810''>on</span> <span m=''677930''>duality.</span> <span m=''678560''>Some
  of the</span> <span m=''678800''>homework</span> <span m=''679290''>problems</span>
  <span m=''679750''>have</span> <span m=''679860''>suggested</span> <span m=''681370''>what</span>
  <span m=''681630''>you</span> <span m=''681750''>might</span> <span m=''681960''>be</span>
  <span m=''682080''>able</span> <span m=''682220''>to</span> <span m=''682310''>do</span>
  <span m=''683030''>in</span> <span m=''684170''>orthogonal</span> <span m=''684800''>codes,</span>
  <span m=''685260''>but --</span> <span m=''690110''>well,</span> <span m=''690630''>one</span>
  <span m=''690800''>of</span> <span m=''690930''>the</span> <span m=''691060''>problems</span>
  <span m=''691460''>you''ll</span> <span m=''691700''>do</span> <span m=''691850''>on</span>
  <span m=''691960''>the</span> <span m=''692030''>homework --</span> <span m=''694730''>I</span>
  <span m=''694940''>was</span> <span m=''695110''>going</span> <span m=''695230''>to</span>
  <span m=''695300''>talk</span> <span m=''695560''>about</span> <span m=''695730''>it
  a</span> <span m=''695750''>little</span> <span m=''695940''>later.</span> <span
  m=''696210''>There''s</span> <span m=''696470''>a</span> <span m=''696540''>dual</span>
  <span m=''696830''>state</span> <span m=''697180''>space</span> <span m=''697560''>theorem</span>
  <span m=''697930''>that</span> <span m=''698040''>basically</span> <span m=''698460''>says</span>
  <span m=''698860''>the</span> <span m=''698940''>state</span> <span m=''699270''>space</span>
  <span m=''699600''>sizes,</span> <span m=''700630''>or</span> <span m=''700720''>dimensions,</span>
  <span m=''701430''>are</span> <span m=''701550''>the</span> <span m=''701670''>same</span>
  <span m=''702010''>for</span> <span m=''702140''>the</span> <span m=''702240''>dual</span>
  <span m=''702580''>code</span> <span m=''702930''>as</span> <span m=''703080''>they</span>
  <span m=''703220''>are</span> <span m=''703460''>for</span> <span m=''703550''>the</span>
  <span m=''703630''>primal</span> <span m=''704060''>code.</span> </p><p><span m=''706530''>Here''s</span>
  <span m=''706760''>one</span> <span m=''706960''>example.</span> <span m=''708500''>Of</span>
  <span m=''708880''>course,</span> <span m=''709600''>dual is</span> <span m=''710020''>itself,</span>
  <span m=''710570''>so</span> <span m=''710830''>it''s</span> <span m=''711070''>trivial</span>
  <span m=''711530''>that</span> <span m=''711690''>the</span> <span m=''711850''>state</span>
  <span m=''712140''>space</span> <span m=''712440''>size</span> <span m=''712760''>is</span>
  <span m=''712830''>the</span> <span m=''712960''>same.</span> <span m=''713250''>But</span>
  <span m=''713380''>here''s</span> <span m=''713610''>another</span> <span m=''713930''>less</span>
  <span m=''714160''>trivial</span> <span m=''714530''>example.</span> <span m=''715360''>These</span>
  <span m=''715610''>two</span> <span m=''715800''>codes</span> <span m=''716190''>are</span>
  <span m=''716270''>orthogonal</span> <span m=''716860''>to</span> <span m=''716970''>each</span>
  <span m=''717190''>other.</span> <span m=''718980''>And</span> <span m=''719540''>what</span>
  <span m=''720070''>is</span> <span m=''720160''>similar</span> <span m=''720530''>about</span>
  <span m=''720770''>their</span> <span m=''720890''>trellises?</span> <span m=''721580''>Their</span>
  <span m=''721850''>trellises</span> <span m=''722570''>are</span> <span m=''722710''>both</span>
  <span m=''722990''>two-state</span> <span m=''723520''>trellises.</span> <span m=''725010''>They
  don''t</span> <span m=''725420''>look</span> <span m=''725720''>the</span> <span
  m=''725830''>same.</span> <span m=''727100''>This</span> <span m=''727310''>trellis</span>
  <span m=''727780''>looks</span> <span m=''728020''>like</span> <span m=''728310''>this,</span>
  <span m=''730950''>because</span> <span m=''731280''>they''re</span> <span m=''731630''>all</span>
  <span m=''731880''>zeroes</span> <span m=''732350''>up</span> <span m=''732540''>here,</span>
  <span m=''733600''>and</span> <span m=''733780''>all</span> <span m=''734070''>ones</span>
  <span m=''734480''>down</span> <span m=''734790''>here.</span> <span m=''736950''>That''s</span>
  <span m=''737180''>the</span> <span m=''737260''>repetition</span> <span m=''737910''>code</span>
  <span m=''738210''>trellis,</span> <span m=''738720''>whereas</span> <span m=''739110''>this</span>
  <span m=''739340''>trellis</span> <span m=''740470''>looks</span> <span m=''740870''>like</span>
  <span m=''741430''>this.</span> <span m=''742550''>It</span> <span m=''742820''>has</span>
  <span m=''743820''>crosses</span> <span m=''744500''>every</span> <span m=''744800''>time</span>
  <span m=''746776''>and</span> <span m=''747180''>so</span> <span m=''747450''>forth,</span>
  <span m=''749370''>abstractly.</span> </p><p><span m=''750300''>So</span> <span
  m=''751200''>trellises</span> <span m=''752100''>are</span> <span m=''752380''>not</span>
  <span m=''752580''>the</span> <span m=''752670''>same.</span> <span m=''753280''>They</span>
  <span m=''753660''>have</span> <span m=''753680''>different</span> <span m=''755010''>branching</span>
  <span m=''755460''>properties,</span> <span m=''756200''>but</span> <span m=''756520''>the</span>
  <span m=''756600''>state</span> <span m=''756980''>space</span> <span m=''757240''>sizes</span>
  <span m=''757680''>are</span> <span m=''757740''>the</span> <span m=''757880''>same</span>
  <span m=''758220''>at</span> <span m=''758270''>all</span> <span m=''758490''>times.</span>
  <span m=''759410''>This is</span> <span m=''759570''>a</span> <span m=''759730''>general</span>
  <span m=''760100''>property</span> <span m=''760380''>of</span> <span m=''760660''>dual</span>
  <span m=''761110''>codes</span> <span m=''763000''>which</span> <span m=''763260''>you</span>
  <span m=''763390''>will</span> <span m=''763560''>prove</span> <span m=''763930''>on
  the</span> <span m=''764050''>homework,</span> <span m=''765045''>if</span> <span
  m=''765360''>you</span> <span m=''765470''>haven''t</span> <span m=''765670''>done</span>
  <span m=''765880''>so</span> <span m=''766120''>already.</span> </p><p><span m=''771420''>Sorry,</span>
  <span m=''772510''>it''s</span> <span m=''772780''>hard</span> <span m=''773020''>to</span>
  <span m=''773120''>know</span> <span m=''773350''>what</span> <span m=''774850''>to</span>
  <span m=''774960''>tell</span> <span m=''775120''>you</span> <span m=''775310''>about</span>
  <span m=''775710''>and</span> <span m=''775930''>what</span> <span m=''776180''>to</span>
  <span m=''776470''>suppress,</span> <span m=''777120''>because</span> <span m=''777360''>I''m</span>
  <span m=''777520''>also</span> <span m=''778370''>trying</span> <span m=''778610''>to</span>
  <span m=''778690''>cover</span> <span m=''778940''>more</span> <span m=''779140''>material</span>
  <span m=''779630''>this</span> <span m=''779880''>year.</span> <span m=''780480''>There''s</span>
  <span m=''780840''>a</span> <span m=''780890''>lot</span> <span m=''781070''>of</span>
  <span m=''781150''>material</span> <span m=''781700''>that''s</span> <span m=''781940''>really</span>
  <span m=''782200''>nice</span> <span m=''782570''>that I have</span> <span m=''782840''>to</span>
  <span m=''782950''>skip</span> <span m=''783260''>over.</span> </p><p><span m=''786350''>Let''s</span>
  <span m=''788780''>continue</span> <span m=''789350''>from</span> <span m=''789620''>this.</span>
  <span m=''790040''>Let''s</span> <span m=''790310''>make</span> <span m=''790770''>a</span>
  <span m=''791350''>minimal</span> <span m=''791760''>realization.</span> <span m=''794080''>So,</span>
  <span m=''795480''>a</span> <span m=''795560''>canonical</span> <span m=''796680''>minimal</span>
  <span m=''797080''>trellis.</span> <span m=''799770''>I''m</span> <span m=''799970''>doing</span>
  <span m=''800280''>this</span> <span m=''800550''>in a</span> <span m=''800620''>little</span>
  <span m=''800940''>bit</span> <span m=''801170''>different</span> <span m=''801580''>order</span>
  <span m=''802510''>than</span> <span m=''802920''>it''s</span> <span m=''803180''>done</span>
  <span m=''803380''>in</span> <span m=''803510''>the</span> <span m=''803630''>notes,</span>
  <span m=''804170''>but</span> <span m=''804370''>I</span> <span m=''804450''>think</span>
  <span m=''805110''>you will</span> <span m=''805390''>see</span> <span m=''806510''>this</span>
  <span m=''806930''>kind</span> <span m=''807060''>of</span> <span m=''807200''>argument</span>
  <span m=''807630''>very</span> <span m=''807880''>quickly.</span> </p><p><span m=''810730''>I''ve</span>
  <span m=''810980''>got</span> <span m=''811180''>this</span> <span m=''811350''>trellis-oriented</span>
  <span m=''812080''>generator</span> <span m=''812560''>matrix,</span> <span m=''813025''>but</span>
  <span m=''813490''>suppose</span> <span m=''813920''>I</span> <span m=''814000''>didn''t</span>
  <span m=''814270''>know</span> <span m=''814780''>what</span> <span m=''815000''>the</span>
  <span m=''815090''>trellis</span> <span m=''815520''>looked</span> <span m=''815750''>like.</span>
  <span m=''816025''>I</span> <span m=''816300''>put</span> <span m=''816500''>it</span>
  <span m=''816580''>up</span> <span m=''817030''>the</span> <span m=''817320''>first</span>
  <span m=''817580''>time</span> <span m=''817850''>last</span> <span m=''818220''>time.</span>
  <span m=''818490''>But</span> <span m=''819320''>all</span> <span m=''819500''>I</span>
  <span m=''819620''>have</span> <span m=''819740''>is</span> <span m=''819850''>this</span>
  <span m=''819990''>generator</span> <span m=''820400''>matrix,</span> <span m=''820960''>and</span>
  <span m=''821110''>I</span> <span m=''821140''>want</span> <span m=''821370''>to</span>
  <span m=''821440''>generate</span> <span m=''821970''>a</span> <span m=''822070''>trellis</span>
  <span m=''822830''>now</span> <span m=''823080''>for</span> <span m=''823220''>this</span>
  <span m=''823480''>code</span> <span m=''823810''>which</span> <span m=''824090''>has</span>
  <span m=''824390''>minimal</span> <span m=''824690''>state</span> <span m=''825080''>spaces.</span>
  <span m=''826170''>It''s</span> <span m=''826410''>also</span> <span m=''826710''>going</span>
  <span m=''826840''>to</span> <span m=''826910''>turn</span> <span m=''827160''>out</span>
  <span m=''827370''>to be</span> <span m=''827490''>minimal</span> <span m=''827830''>in</span>
  <span m=''827900''>every</span> <span m=''828100''>other</span> <span m=''828270''>way.</span>
  </p><p><span m=''831490''>Well,</span> <span m=''832140''>let''s</span> <span m=''832360''>start</span>
  <span m=''832610''>off</span> <span m=''832870''>by</span> <span m=''834120''>realizing</span>
  <span m=''834780''>the</span> <span m=''835000''>first</span> <span m=''835230''>generator</span>
  <span m=''835790''>here.</span> <span m=''838540''>The</span> <span m=''838730''>first</span>
  <span m=''838930''>generator</span> <span m=''839530''>generates</span> <span m=''840870''>a</span>
  <span m=''840940''>little</span> <span m=''841170''>one-dimensional</span> <span
  m=''841850''>code.</span> <span m=''845760''>G1,</span> <span m=''846610''>the</span>
  <span m=''846740''>code</span> <span m=''847120''>generated</span> <span m=''847680''>by</span>
  <span m=''847830''>the</span> <span m=''848080''>first</span> <span m=''848330''>generator,</span>
  <span m=''848990''>is</span> <span m=''849150''>simply</span> <span m=''849570''>the</span>
  <span m=''849770''>two</span> <span m=''849980''>code</span> <span m=''850340''>words</span>
  <span m=''851520''>0,</span> <span m=''851870''>0,</span> <span m=''852150''>0,</span>
  <span m=''852450''>0,</span> <span m=''853460''>1,</span> <span m=''853700''>1,</span>
  <span m=''853990''>1,</span> <span m=''854270''>1,</span> <span m=''854620''>0,</span>
  <span m=''854990''>0.</span> <span m=''858960''>So</span> <span m=''859160''>let</span>
  <span m=''859250''>me</span> <span m=''859420''>realize</span> <span m=''860050''>that</span>
  <span m=''860260''>little</span> <span m=''860480''>one-dimensional</span> <span
  m=''861170''>code</span> <span m=''861640''>with</span> <span m=''861810''>a</span>
  <span m=''862140''>minimal</span> <span m=''862550''>trellis</span> <span m=''862970''>for</span>
  <span m=''863080''>that.</span> <span m=''863935''>What</span> <span m=''864400''>would</span>
  <span m=''864550''>it</span> <span m=''864700''>look</span> <span m=''864920''>like?</span>
  </p><p><span m=''867124''>If</span> <span m=''867590''>I</span> <span m=''867670''>go</span>
  <span m=''867850''>through</span> <span m=''868160''>this,</span> <span m=''868610''>I''ll</span>
  <span m=''868830''>see</span> <span m=''868970''>that</span> <span m=''869130''>it</span>
  <span m=''869260''>has --</span> <span m=''870470''>my</span> <span m=''871150''>trellis-oriented</span>
  <span m=''872040''>generator</span> <span m=''872560''>matrix</span> <span m=''873110''>for</span>
  <span m=''873210''>this</span> <span m=''873450''>code</span> <span m=''873810''>is</span>
  <span m=''874080''>simply</span> <span m=''874590''>1,</span> <span m=''874830''>1,</span>
  <span m=''875060''>1,</span> <span m=''875380''>1,</span> <span m=''876320''>0,</span>
  <span m=''876620''>0,</span> <span m=''876970''>0.</span> <span m=''878080''>I</span>
  <span m=''878230''>see</span> <span m=''878520''>from</span> <span m=''878760''>that</span>
  <span m=''879170''>that</span> <span m=''879370''>the</span> <span m=''879480''>dimensions</span>
  <span m=''880180''>of</span> <span m=''880260''>the</span> <span m=''880350''>state</span>
  <span m=''880860''>spaces</span> <span m=''883090''>is</span> <span m=''883310''>0,</span>
  <span m=''883720''>1,</span> <span m=''884060''>1,</span> <span m=''884580''>1,</span>
  <span m=''885130''>0,</span> <span m=''885530''>0,</span> <span m=''885920''>0,</span>
  <span m=''886300''>0,</span> <span m=''886670''>0.</span> <span m=''890030''>And</span>
  <span m=''892070''>you</span> <span m=''892300''>can</span> <span m=''892510''>easily</span>
  <span m=''892990''>see</span> <span m=''893350''>that</span> <span m=''893710''>what</span>
  <span m=''894110''>the</span> <span m=''894210''>trellis,</span> <span m=''896240''>the</span>
  <span m=''896340''>minimal</span> <span m=''896740''>trellis,</span> <span m=''898480''>a</span>
  <span m=''898670''>minimal</span> <span m=''899060''>trellis</span> <span m=''899740''>looks</span>
  <span m=''900060''>like</span> <span m=''900530''>is</span> <span m=''902340''>0,</span>
  <span m=''902750''>0,</span> <span m=''903160''>0,</span> <span m=''903570''>0,</span>
  <span m=''904070''>1,</span> <span m=''904840''>1,</span> <span m=''905500''>1,</span>
  <span m=''907240''>1,</span> <span m=''908520''>0,</span> <span m=''909520''>0,</span>
  <span m=''910540''>0,</span> <span m=''911730''>0.</span> <span m=''914160''>So</span>
  <span m=''914360''>there</span> <span m=''914550''>is</span> <span m=''914730''>the</span>
  <span m=''914800''>minimal</span> <span m=''915230''>trellis</span> <span m=''915640''>realization</span>
  <span m=''916045''>for</span> <span m=''916450''>that</span> <span m=''916600''>one-dimensional</span>
  <span m=''917300''>code.</span> </p><p><span m=''919380''>It</span> <span m=''919530''>has</span>
  <span m=''920170''>state</span> <span m=''920690''>spaces</span> <span m=''921250''>of</span>
  <span m=''921740''>dimension</span> <span m=''922550''>0,</span> <span m=''923140''>1,</span>
  <span m=''923630''>1,</span> <span m=''924230''>1,</span> <span m=''924910''>0,</span>
  <span m=''925390''>0,</span> <span m=''925840''>0,</span> <span m=''926250''>0,</span>
  <span m=''926730''>0.</span> <span m=''927570''>Therefore</span> <span m=''927910''>the</span>
  <span m=''928050''>state</span> <span m=''928430''>spaces</span> <span m=''928900''>are</span>
  <span m=''929020''>all</span> <span m=''929730''>minimal,</span> <span m=''930770''>as</span>
  <span m=''931020''>proved</span> <span m=''932095''>from</span> <span m=''932570''>this.</span>
  <span m=''932965''>It''s</span> <span m=''933360''>all</span> <span m=''933810''>sort
  of</span> <span m=''934070''>elementary.</span> </p><p><span m=''938230''>Similarly,</span>
  <span m=''939470''>I</span> <span m=''939600''>can</span> <span m=''939730''>realize</span>
  <span m=''941420''>this</span> <span m=''941690''>one</span> <span m=''944970''>by</span>
  <span m=''946220''>another</span> <span m=''946740''>little</span> <span m=''948620''>machine</span>
  <span m=''949230''>that</span> <span m=''949350''>looks</span> <span m=''949610''>like</span>
  <span m=''949880''>this.</span> <span m=''959300''>0,</span> <span m=''959630''>0,</span>
  <span m=''959990''>0,</span> <span m=''960440''>0,</span> <span m=''960850''>0,</span>
  <span m=''961270''>0,</span> <span m=''961680''>0.</span> <span m=''962160''>This</span>
  <span m=''962400''>is</span> <span m=''962970''>just</span> <span m=''963360''>the</span>
  <span m=''963810''>state</span> <span m=''964220''>transition</span> <span m=''964800''>diagram</span>
  <span m=''965600''>of</span> <span m=''966310''>a</span> <span m=''966800''>linear</span>
  <span m=''967310''>time-varying</span> <span m=''968580''>finite</span> <span m=''968990''>state</span>
  <span m=''969410''>machine.</span> <span m=''970790''>And</span> <span m=''971140''>it</span>
  <span m=''971260''>looks</span> <span m=''971530''>like</span> <span m=''971770''>that,</span>
  <span m=''972080''>and</span> <span m=''972250''>it</span> <span m=''972440''>too</span>
  <span m=''972700''>is</span> <span m=''972910''>minimal</span> <span m=''973300''>by</span>
  <span m=''973460''>the</span> <span m=''974070''>same</span> <span m=''974390''>argument</span>
  <span m=''974880''>for</span> <span m=''975760''>the</span> <span m=''975810''>one-dimensional</span>
  <span m=''976500''>code</span> <span m=''976870''>generated</span> <span m=''977500''>by</span>
  <span m=''979300''>this</span> <span m=''979600''>generator.</span> </p><p><span
  m=''982690''>What</span> <span m=''982860''>is</span> <span m=''982980''>this</span>
  <span m=''983170''>saying</span> <span m=''983480''>here?</span> <span m=''983750''>This</span>
  <span m=''983990''>is</span> <span m=''984090''>saying</span> <span m=''985320''>we</span>
  <span m=''985430''>really --</span> <span m=''986480''>what</span> <span m=''986610''>we</span>
  <span m=''986720''>should</span> <span m=''986900''>imagine</span> <span m=''987400''>here</span>
  <span m=''987680''>is</span> <span m=''987780''>we</span> <span m=''987880''>have</span>
  <span m=''987950''>a</span> <span m=''988020''>little</span> <span m=''988250''>memory</span>
  <span m=''988660''>element</span> <span m=''990150''>that''s</span> <span m=''990370''>only</span>
  <span m=''990720''>active</span> <span m=''992090''>at</span> <span m=''992510''>state</span>
  <span m=''992940''>times</span> <span m=''993340''>1,</span> <span m=''993700''>2,</span>
  <span m=''993970''>and</span> <span m=''994270''>3.</span> <span m=''996100''>So</span>
  <span m=''996320''>to</span> <span m=''996380''>realize</span> <span m=''996890''>this,</span>
  <span m=''998410''>this</span> <span m=''998660''>is</span> <span m=''999070''>a</span>
  <span m=''1000020''>one-dimensional</span> <span m=''1002040''>memory</span> <span
  m=''1002530''>element.</span> <span m=''1003140''>Think</span> <span m=''1003380''>of
  it</span> <span m=''1003440''>as</span> <span m=''1003840''>a</span> <span m=''1004000''>little  --</span>
  <span m=''1006001''>well,</span> <span m=''1007120''>a</span> <span m=''1007240''>memory</span>
  <span m=''1007650''>for an</span> <span m=''1008010''>element</span> <span m=''1008370''>of</span>
  <span m=''1008700''>f2.</span> <span m=''1009600''>It''s</span> <span m=''1010080''>active</span>
  <span m=''1011600''>during</span> <span m=''1012870''>the</span> <span m=''1013000''>interval</span>
  <span m=''1013520''>1</span> <span m=''1013930''>through</span> <span m=''1014210''>3,</span>
  <span m=''1014930''>during</span> <span m=''1015110''>the</span> <span m=''1015280''>time
  that</span> <span m=''1015720''>this</span> <span m=''1015920''>generator</span>
  <span m=''1016510''>is</span> <span m=''1016640''>active.</span> <span m=''1019640''>It''s
  active</span> <span m=''1020100''>at</span> <span m=''1020200''>these</span> <span
  m=''1020450''>three</span> <span m=''1020710''>times,</span> <span m=''1021180''>not</span>
  <span m=''1021370''>otherwise.</span> </p><p><span m=''1023270''>So</span> <span
  m=''1023530''>you can</span> <span m=''1023730''>think</span> <span m=''1023910''>of</span>
  <span m=''1023970''>it</span> <span m=''1024020''>as</span> <span m=''1024160''>just</span>
  <span m=''1024400''>disappearing.</span> <span m=''1025150''>It</span> <span m=''1025300''>comes</span>
  <span m=''1025589''>into</span> <span m=''1025890''>existence</span> <span m=''1026560''>at</span>
  <span m=''1026690''>time</span> <span m=''1027020''>1.</span> <span m=''1028130''>It</span>
  <span m=''1028720''>holds</span> <span m=''1030200''>whatever</span> <span m=''1030660''>the</span>
  <span m=''1030790''>input</span> <span m=''1031260''>bit</span> <span m=''1031440''>is.</span>
  <span m=''1031839''>Think</span> <span m=''1032060''>of  --</span> <span m=''1033040''>we''re</span>
  <span m=''1033329''>trying</span> <span m=''1033619''>to</span> <span m=''1033760''>create</span>
  <span m=''1034230''>the</span> <span m=''1034380''>code</span> <span m=''1034839''>as</span>
  <span m=''1035280''>the</span> <span m=''1035480''>set</span> <span m=''1035690''>of</span>
  <span m=''1035975''>all  --</span> <span m=''1038270''>sum</span> <span m=''1038835''>of</span>
  <span m=''1039140''>ui</span> <span m=''1039819''>gi.</span> <span m=''1041109''>And</span>
  <span m=''1041250''>so</span> <span m=''1041410''>what</span> <span m=''1041540''>this</span>
  <span m=''1041730''>memory</span> <span m=''1042140''>element</span> <span m=''1042470''>really</span>
  <span m=''1042720''>does</span> <span m=''1043089''>is</span> <span m=''1043240''>it</span>
  <span m=''1043310''>holds</span> <span m=''1043780''>ui</span> <span m=''1044880''>during</span>
  <span m=''1045069''>the</span> <span m=''1045260''>time</span> <span m=''1045540''>that
  it''s</span> <span m=''1045869''>needed,</span> <span m=''1046690''>which</span>
  <span m=''1047099''>is</span> <span m=''1047220''>at</span> <span m=''1047329''>times</span>
  <span m=''1047780''>1,</span> <span m=''1048119''>2,</span> <span m=''1048390''>and</span>
  <span m=''1048660''>3.</span> <span m=''1050450''>Whatever</span> <span m=''1050810''>the</span>
  <span m=''1050950''>coefficient</span> <span m=''1051540''>is  --</span> <span m=''1052240''>what</span>
  <span m=''1052510''>could</span> <span m=''1052710''>it be,</span> <span m=''1053100''>0
  or</span> <span m=''1053380''>1?</span> <span m=''1054090''>Element</span> <span
  m=''1054390''>of</span> <span m=''1054440''>the</span> <span m=''1054520''>base</span>
  <span m=''1054840''>field,</span> <span m=''1055410''>f2.</span> <span m=''1056280''>So</span>
  <span m=''1056490''>the</span> <span m=''1056640''>memory</span> <span m=''1056900''>element</span>
  <span m=''1057930''>holds,</span> <span m=''1059460''>it</span> <span m=''1060070''>contains</span>
  <span m=''1061480''>u1</span> <span m=''1063320''>in</span> <span m=''1063440''>this</span>
  <span m=''1063670''>case.</span> </p><p><span m=''1066120''>Yeah?</span> </p><p><span
  m=''1067322''>AUDIENCE: What if</span> <span m=''1067768''>we</span> <span m=''1068214''>look</span>
  <span m=''1068660''>at</span> <span m=''1069106''>this</span> <span m=''1069552''>matrix</span>
  <span m=''1070080''>only</span> <span m=''1070350''>for the</span> <span m=''1070610''>second</span>
  <span m=''1071150''>code.</span> </p><p><span m=''1071960''>PROFESSOR: Yes.</span>
  </p><p><span m=''1072944''>AUDIENCE: So</span> <span m=''1073436''>that</span> <span
  m=''1073928''>will</span> <span m=''1074420''>give</span> <span m=''1075170''>0,</span>
  <span m=''1075260''>1,</span> <span m=''1075450''>0,</span> <span m=''1075630''>1,</span>
  <span m=''1076120''>1,</span> <span m=''1076200''>0,</span> <span m=''1076590''>1,</span>
  <span m=''1076880''>0.</span> </p><p><span m=''1078060''>PROFESSOR: Correct.</span>
  </p><p><span m=''1079190''>AUDIENCE: So</span> <span m=''1079480''>some</span> <span
  m=''1079940''>places</span> <span m=''1080190''>it</span> <span m=''1080613''>will
  suggest</span> <span m=''1081036''>that</span> <span m=''1081460''>the</span> <span
  m=''1081970''>dimension</span> <span m=''1082480''>is  --</span> </p><p><span m=''1084670''>PROFESSOR:
  The</span> <span m=''1084870''>fact</span> <span m=''1085260''>that</span> <span
  m=''1085450''>the</span> <span m=''1085560''>values</span> <span m=''1087240''>are  --</span>
  <span m=''1089900''>there</span> <span m=''1090220''>will</span> <span m=''1090360''>always</span>
  <span m=''1090750''>be</span> <span m=''1090880''>1</span> <span m=''1091200''>here</span>
  <span m=''1091550''>at</span> <span m=''1091650''>the</span> <span m=''1091750''>starting</span>
  <span m=''1092150''>time</span> <span m=''1092420''>and</span> <span m=''1092470''>the</span>
  <span m=''1092570''>ending</span> <span m=''1092880''>time.</span> <span m=''1093640''>Otherwise</span>
  <span m=''1094210''>we</span> <span m=''1094320''>wouldn''t</span> <span m=''1094700''>draw</span>
  <span m=''1095000''>a</span> <span m=''1095070''>branch</span> <span m=''1095630''>there.</span>
  <span m=''1096570''>But</span> <span m=''1096780''>they</span> <span m=''1096910''>can</span>
  <span m=''1097090''>be</span> <span m=''1097320''>arbitrary</span> <span m=''1097960''>in</span>
  <span m=''1098090''>between.</span> <span m=''1100150''>So</span> <span m=''1100480''>don''t</span>
  <span m=''1100750''>be</span> <span m=''1101350''>thrown</span> <span m=''1101670''>off</span>
  <span m=''1101880''>by</span> <span m=''1101960''>the</span> <span m=''1102050''>fact
  that</span> <span m=''1102440''>there</span> <span m=''1102650''>are</span> <span
  m=''1103360''>some</span> <span m=''1103620''>0</span> <span m=''1103960''>values</span>
  <span m=''1104520''>in</span> <span m=''1104620''>here.</span> <span m=''1105950''>What</span>
  <span m=''1106200''>we''re</span> <span m=''1106330''>doing</span> <span m=''1106690''>here</span>
  <span m=''1107070''>is</span> <span m=''1107200''>we''re</span> <span m=''1107900''>realizing</span>
  <span m=''1108680''>u2</span> <span m=''1109410''>times</span> <span m=''1109900''>g2,</span>
  <span m=''1110640''>where</span> <span m=''1110870''>u2</span> <span m=''1111350''>can</span>
  <span m=''1111540''>be</span> <span m=''1111730''>either</span> <span m=''1112560''>0</span>
  <span m=''1112830''>or</span> <span m=''1113060''>1.</span> <span m=''1114430''>And</span>
  <span m=''1114620''>g2</span> <span m=''1115850''>can</span> <span m=''1116040''>be</span>
  <span m=''1116170''>arbitrary,</span> <span m=''1117070''>except</span> <span m=''1117480''>that
  it</span> <span m=''1117660''>has</span> <span m=''1117880''>a</span> <span m=''1117950''>starting</span>
  <span m=''1118390''>time</span> <span m=''1118780''>and</span> <span m=''1119180''>an</span>
  <span m=''1119535''>ending time,</span> <span m=''1119890''>so it''s</span> <span
  m=''1120050''>not</span> <span m=''1120250''>arbitrary</span> <span m=''1120740''>for
  this</span> <span m=''1121240''>kind.</span> </p><p><span m=''1124740''>AUDIENCE:
  What</span> <span m=''1124950''>if</span> <span m=''1125275''>we</span> <span m=''1125600''>try
  to</span> <span m=''1125860''>find</span> <span m=''1126140''>the</span> <span m=''1126430''>state
  space</span> <span m=''1126908''>[INAUDIBLE]</span> </p><p><span m=''1131150''>PROFESSOR:
  For</span> <span m=''1131330''>this,</span> <span m=''1131740''>what</span> <span
  m=''1131950''>I</span> <span m=''1132050''>need</span> <span m=''1132390''>is</span>
  <span m=''1133520''>a</span> <span m=''1133590''>one-dimensional</span> <span m=''1134940''>memory</span>
  <span m=''1135240''>element</span> <span m=''1136350''>containing</span> <span m=''1136900''>u2</span>
  <span m=''1138480''>which</span> <span m=''1138750''>is</span> <span m=''1139010''>active</span>
  <span m=''1140590''>during</span> <span m=''1140950''>a</span> <span m=''1141320''>different</span>
  <span m=''1141640''>interval,</span> <span m=''1142880''>2</span> <span m=''1143240''>through</span>
  <span m=''1143970''>6.</span> <span m=''1147820''>So</span> <span m=''1147990''>think</span>
  <span m=''1148260''>of</span> <span m=''1148450''>these</span> <span m=''1148640''>as</span>
  <span m=''1148750''>like</span> <span m=''1148940''>little</span> <span m=''1149100''>stars</span>
  <span m=''1149440''>that</span> <span m=''1149780''>wink</span> <span m=''1150170''>on</span>
  <span m=''1150400''>or</span> <span m=''1150470''>wink</span> <span m=''1150830''>off.</span>
  <span m=''1152000''>This</span> <span m=''1152220''>thing</span> <span m=''1152420''>comes</span>
  <span m=''1152720''>into</span> <span m=''1152900''>existence</span> <span m=''1153520''>for</span>
  <span m=''1153620''>three</span> <span m=''1154310''>consecutive</span> <span m=''1154910''>times,</span>
  <span m=''1155250''>and</span> <span m=''1155390''>then</span> <span m=''1155490''>it</span>
  <span m=''1155600''>disappears.</span> <span m=''1157600''>This</span> <span m=''1157830''>thing</span>
  <span m=''1158020''>comes</span> <span m=''1158280''>into</span> <span m=''1158470''>existence</span>
  <span m=''1159080''>for</span> <span m=''1159650''>five</span> <span m=''1159970''>consecutive</span>
  <span m=''1160600''>times,</span> <span m=''1161270''>and</span> <span m=''1161720''>then</span>
  <span m=''1161930''>it</span> <span m=''1162050''>disappears.</span> <span m=''1163400''>Because</span>
  <span m=''1163540''>those</span> <span m=''1163750''>are</span> <span m=''1163850''>the</span>
  <span m=''1164020''>only</span> <span m=''1164190''>times</span> <span m=''1164540''>when</span>
  <span m=''1164680''>it''s</span> <span m=''1164880''>needed</span> <span m=''1165240''>to</span>
  <span m=''1165370''>contribute</span> <span m=''1165830''>to</span> <span m=''1165910''>the</span>
  <span m=''1166060''>output.</span> </p><p><span m=''1169600''>So</span> <span m=''1171790''>altogether,</span>
  <span m=''1172520''>we can</span> <span m=''1172840''>think</span> <span m=''1173080''>of</span>
  <span m=''1173360''>there</span> <span m=''1173760''>as</span> <span m=''1174120''>sort</span>
  <span m=''1174360''>of</span> <span m=''1174440''>being</span> <span m=''1174700''>four</span>
  <span m=''1176060''>memory</span> <span m=''1176440''>elements</span> <span m=''1177020''>which</span>
  <span m=''1177270''>contain</span> <span m=''1177740''>u1,</span> <span m=''1178550''>u2,</span>
  <span m=''1179740''>u3,</span> <span m=''1180610''>and</span> <span m=''1180790''>u4.</span>
  <span m=''1183140''>And</span> <span m=''1183430''>we</span> <span m=''1183730''>form</span>
  <span m=''1184340''>the</span> <span m=''1184530''>outputs</span> <span m=''1186250''>g1k</span>
  <span m=''1190310''>times</span> <span m=''1190830''>this,</span> <span m=''1191360''>sort</span>
  <span m=''1191710''>of</span> <span m=''1191830''>like</span> <span m=''1192190''>in
  the</span> <span m=''1192350''>convolutional</span> <span m=''1193230''>code.</span>
  <span m=''1194300''>g2k</span> <span m=''1197860''>g3k</span> <span m=''1199630''>and</span>
  <span m=''1200870''>g4k.</span> <span m=''1201900''>The</span> <span m=''1202050''>generators</span>
  <span m=''1203650''>step</span> <span m=''1204030''>along</span> <span m=''1204510''>in</span>
  <span m=''1204640''>time,</span> <span m=''1205120''>and</span> <span m=''1205230''>we</span>
  <span m=''1205370''>form</span> <span m=''1205690''>the</span> <span m=''1205830''>outputs.</span>
  <span m=''1206610''>We</span> <span m=''1206760''>sum</span> <span m=''1207700''>this</span>
  <span m=''1207960''>all</span> <span m=''1208190''>together</span> <span m=''1209840''>in</span>
  <span m=''1210010''>a</span> <span m=''1210120''>summer,</span> <span m=''1210660''>and</span>
  <span m=''1210810''>this</span> <span m=''1211050''>provides</span> <span m=''1212220''>yk,</span>
  <span m=''1213330''>the</span> <span m=''1213500''>output,</span> <span m=''1214030''>as</span>
  <span m=''1214250''>we</span> <span m=''1214370''>go</span> <span m=''1215290''>from</span>
  <span m=''1215760''>k</span> <span m=''1216060''>equals</span> <span m=''1216370''>1</span>
  <span m=''1216660''>through</span> <span m=''1216950''>8</span> <span m=''1220280''>as</span>
  <span m=''1220390''>we</span> <span m=''1220490''>go</span> <span m=''1220690''>through</span>
  <span m=''1220950''>the</span> <span m=''1221100''>code</span> <span m=''1221440''>word.</span>
  </p><p><span m=''1223010''>But</span> <span m=''1223170''>we</span> <span m=''1223300''>only</span>
  <span m=''1223510''>need</span> <span m=''1223850''>this</span> <span m=''1224100''>one</span>
  <span m=''1224460''>for  --</span> <span m=''1224920''>it''s</span> <span m=''1225190''>only</span>
  <span m=''1225480''>on</span> <span m=''1225830''>from</span> <span m=''1226020''>time</span>
  <span m=''1227200''>1,</span> <span m=''1227940''>2,</span> <span m=''1228480''>and</span>
  <span m=''1228920''>3.</span> <span m=''1230260''>And</span> <span m=''1230390''>this</span>
  <span m=''1230610''>is</span> <span m=''1231030''>on</span> <span m=''1231510''>from</span>
  <span m=''1231700''>time</span> <span m=''1232160''>2</span> <span m=''1232400''>through</span>
  <span m=''1232660''>6.</span> <span m=''1233720''>And</span> <span m=''1233960''>this</span>
  <span m=''1234150''>is</span> <span m=''1234330''>on</span> <span m=''1234660''>from</span>
  <span m=''1234870''>time</span> <span m=''1235270''>3</span> <span m=''1235730''>through</span>
  <span m=''1236030''>5.</span> <span m=''1237180''>And</span> <span m=''1237260''>this</span>
  <span m=''1237430''>is</span> <span m=''1237590''>on</span> <span m=''1237860''>from</span>
  <span m=''1238100''>time</span> <span m=''1238410''>4</span> <span m=''1239080''>through</span>
  <span m=''1239270''>7.</span> <span m=''1240770''>Because</span> <span m=''1240970''>we</span>
  <span m=''1241060''>don''t</span> <span m=''1241240''>need</span> <span m=''1241420''>it</span>
  <span m=''1241560''>any</span> <span m=''1241800''>other</span> <span m=''1242010''>time.</span>
  <span m=''1244820''>So</span> <span m=''1244910''>you</span> <span m=''1245050''>can</span>
  <span m=''1245170''>think</span> <span m=''1245460''>of</span> <span m=''1245570''>an</span>
  <span m=''1245670''>input</span> <span m=''1246270''>coming</span> <span m=''1246620''>in</span>
  <span m=''1247310''>at</span> <span m=''1247500''>time</span> <span m=''1247800''>1,</span>
  <span m=''1248130''>at</span> <span m=''1248200''>the</span> <span m=''1248330''>starting</span>
  <span m=''1248770''>time</span> <span m=''1249080''>of</span> <span m=''1249130''>the</span>
  <span m=''1249340''>first</span> <span m=''1249550''>generator,</span> <span m=''1250750''>being</span>
  <span m=''1251000''>saved</span> <span m=''1251750''>for</span> <span m=''1251970''>as</span>
  <span m=''1252070''>long</span> <span m=''1252300''>as</span> <span m=''1252410''>it''s</span>
  <span m=''1252600''>needed,</span> <span m=''1253590''>then it''s</span> <span m=''1253900''>discarded.</span>
  <span m=''1254210''>And</span> <span m=''1254520''>in</span> <span m=''1254690''>fact</span>
  <span m=''1255100''>we</span> <span m=''1255660''>don''t</span> <span m=''1255840''>need</span>
  <span m=''1256030''>that</span> <span m=''1256230''>memory</span> <span m=''1256350''>element</span>
  <span m=''1256730''>anymore.</span> </p><p><span m=''1261130''>How</span> <span
  m=''1261210''>many</span> <span m=''1261400''>people</span> <span m=''1261690''>are</span>
  <span m=''1261750''>getting</span> <span m=''1262040''>this?</span> <span m=''1263190''>Raise</span>
  <span m=''1263410''>your</span> <span m=''1263540''>hand</span> <span m=''1263810''>if</span>
  <span m=''1263890''>you</span> <span m=''1264020''>get</span> <span m=''1264260''>this.</span>
  </p><p><span m=''1267462''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''1270730''>PROFESSOR:
  It''s</span> <span m=''1270900''>a time  --</span> <span m=''1271540''>what</span>
  <span m=''1271740''>I''m</span> <span m=''1271820''>trying</span> <span m=''1271960''>to</span>
  <span m=''1272100''>do</span> <span m=''1272250''>is</span> <span m=''1272400''>draw</span>
  <span m=''1272720''>a</span> <span m=''1272790''>time-varying</span> <span m=''1273440''>machine.</span>
  <span m=''1275720''>So</span> <span m=''1275870''>how</span> <span m=''1276010''>do</span>
  <span m=''1276870''>I</span> <span m=''1276970''>do</span> <span m=''1277220''>that?</span>
  <span m=''1278810''>At</span> <span m=''1278960''>time</span> <span m=''1279270''>1,</span>
  <span m=''1279700''>it</span> <span m=''1279840''>looks</span> <span m=''1280100''>like</span>
  <span m=''1280360''>this.</span> <span m=''1283360''>Time</span> <span m=''1283660''>1,</span>
  <span m=''1284010''>it</span> <span m=''1284140''>just</span> <span m=''1284370''>has</span>
  <span m=''1284630''>u1,</span> <span m=''1285890''>and</span> <span m=''1286230''>we</span>
  <span m=''1286440''>multiply</span> <span m=''1287000''>it</span> <span m=''1287180''>by</span>
  <span m=''1287540''>g11,</span> <span m=''1288300''>which</span> <span m=''1288550''>is</span>
  <span m=''1288680''>1.</span> <span m=''1289890''>And</span> <span m=''1289990''>that</span>
  <span m=''1290170''>gives</span> <span m=''1290370''>me</span> <span m=''1290490''>the</span>
  <span m=''1290640''>output</span> <span m=''1291080''>at</span> <span m=''1291220''>time</span>
  <span m=''1291520''>1.</span> <span m=''1291850''>There''s</span> <span m=''1292060''>nothing</span>
  <span m=''1292370''>else</span> <span m=''1292630''>that</span> <span m=''1292760''>contributes.</span>
  </p><p><span m=''1295250''>At</span> <span m=''1296000''>time</span> <span m=''1297190''>2,</span>
  <span m=''1299390''>we''ve</span> <span m=''1300250''>got</span> <span m=''1300590''>now</span>
  <span m=''1300820''>another</span> <span m=''1301230''>input,</span> <span m=''1301760''>u1</span>
  <span m=''1301980''>and</span> <span m=''1302380''>u2.</span> <span m=''1303670''>And</span>
  <span m=''1303840''>we''ve</span> <span m=''1304020''>got</span> <span m=''1304230''>to</span>
  <span m=''1304290''>sum</span> <span m=''1304600''>the</span> <span m=''1304760''>contributions</span>
  <span m=''1305660''>from</span> <span m=''1305830''>both</span> <span m=''1306120''>of</span>
  <span m=''1306200''>those, </span> <span m=''1307050''>times</span> <span m=''1307420''>their</span>
  <span m=''1307570''>respective</span> <span m=''1308190''>coefficients.</span> <span
  m=''1311210''>At time</span> <span m=''1311460''>3,</span> <span m=''1312970''>we''re</span>
  <span m=''1313180''>up</span> <span m=''1313330''>to</span> <span m=''1313470''>three</span>
  <span m=''1313730''>of them,</span> <span m=''1315470''>and</span> <span m=''1315550''>we</span>
  <span m=''1315660''>need</span> <span m=''1315840''>all</span> <span m=''1316195''>of
  them.</span> <span m=''1316550''>We''re</span> <span m=''1316740''>going</span>
  <span m=''1316860''>to</span> <span m=''1316930''>form</span> <span m=''1317340''>some</span>
  <span m=''1317790''>linear</span> <span m=''1318180''>combination</span> <span m=''1318880''>according</span>
  <span m=''1319310''>to</span> <span m=''1319480''>the</span> <span m=''1319590''>generator</span>
  <span m=''1320060''>matrix.</span> </p><p><span m=''1321626''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1324770''>PROFESSOR: It''s</span> <span m=''1325000''>time-varying,</span>
  <span m=''1326240''>yeah.</span> <span m=''1328130''>So</span> <span m=''1328410''>get</span>
  <span m=''1328720''>used</span> <span m=''1329140''>to</span> <span m=''1329290''>it.</span>
  <span m=''1329410''>For</span> <span m=''1329520''>a</span> <span m=''1329560''>block</span>
  <span m=''1329945''>code</span> <span m=''1330330''>it</span> <span m=''1330800''>obviously</span>
  <span m=''1331180''>has</span> <span m=''1331440''>to</span> <span m=''1331510''>be</span>
  <span m=''1331630''>time-varying.</span> <span m=''1333820''>Obviously</span> <span
  m=''1335076''>if</span> <span m=''1335440''>we</span> <span m=''1335740''>regard</span>
  <span m=''1336210''>these</span> <span m=''1336945''>as</span> <span m=''1337220''>impulse</span>
  <span m=''1337730''>responses,</span> <span m=''1338530''>this</span> <span m=''1338740''>is</span>
  <span m=''1338990''>the</span> <span m=''1339100''>impulse</span> <span m=''1339500''>response</span>
  <span m=''1340050''>to</span> <span m=''1340170''>u1.</span> <span m=''1341205''>It
  only</span> <span m=''1341610''>lasts</span> <span m=''1342710''>in</span> <span
  m=''1342890''>terms</span> <span m=''1343240''>of</span> <span m=''1343310''>symbol</span>
  <span m=''1343690''>times</span> <span m=''1344130''>from</span> <span m=''1344370''>time</span>
  <span m=''1345570''>0</span> <span m=''1345950''>1</span> <span m=''1346250''>2</span>
  <span m=''1346520''>3,</span> <span m=''1347280''>for</span> <span m=''1347600''>four</span>
  <span m=''1347920''>time</span> <span m=''1348170''>units</span> <span m=''1348400''>of</span>
  <span m=''1348570''>symbol</span> <span m=''1348960''>time.</span> </p><p><span
  m=''1350930''>This</span> <span m=''1351190''>is</span> <span m=''1352140''>the</span>
  <span m=''1352230''>impulse</span> <span m=''1352640''>response</span> <span m=''1353160''>to</span>
  <span m=''1353250''>u2.</span> <span m=''1354790''>u2</span> <span m=''1354980''>you</span>
  <span m=''1355210''>can</span> <span m=''1355520''>think</span> <span m=''1355750''>of</span>
  <span m=''1355890''>as</span> <span m=''1356030''>an</span> <span m=''1356120''>input</span>
  <span m=''1356560''>that</span> <span m=''1356750''>comes</span> <span m=''1357050''>in</span>
  <span m=''1357190''>at</span> <span m=''1357330''>time</span> <span m=''1357670''>2,</span>
  <span m=''1358670''>and</span> <span m=''1358850''>whose</span> <span m=''1359060''>output</span>
  <span m=''1359570''>rings</span> <span m=''1360120''>for</span> <span m=''1361960''>five</span>
  <span m=''1362240''>more</span> <span m=''1362470''>times.</span> <span m=''1363270''>So</span>
  <span m=''1363520''>you</span> <span m=''1363650''>need</span> <span m=''1363850''>to</span>
  <span m=''1363920''>save</span> <span m=''1364300''>u2</span> <span m=''1364810''>for</span>
  <span m=''1364980''>five</span> <span m=''1365250''>more</span> <span m=''1365470''>times,</span>
  <span m=''1365940''>and</span> <span m=''1366190''>then it</span> <span m=''1366300''>disappears.</span>
  <span m=''1366900''>We</span> <span m=''1367010''>don''t</span> <span m=''1367160''>need</span>
  <span m=''1367330''>to</span> <span m=''1367370''>save</span> <span m=''1367580''>it</span>
  <span m=''1367730''>anymore.</span> <span m=''1368055''>We</span> <span m=''1368380''>can</span>
  <span m=''1368460''>let</span> <span m=''1368620''>it</span> <span m=''1369020''>drop</span>
  <span m=''1369330''>off</span> <span m=''1369560''>the</span> <span m=''1369690''>end</span>
  <span m=''1369860''>of</span> <span m=''1369910''>the</span> <span m=''1370020''>shift</span>
  <span m=''1370290''>register,</span> <span m=''1370770''>if</span> <span m=''1370880''>you</span>
  <span m=''1371020''>like.</span> </p><p><span m=''1373350''>u3</span> <span m=''1373940''>comes</span>
  <span m=''1374260''>in</span> <span m=''1374390''>at</span> <span m=''1374530''>time</span>
  <span m=''1374780''>3,</span> <span m=''1376740''>and</span> <span m=''1376900''>this</span>
  <span m=''1377060''>is</span> <span m=''1377200''>its</span> <span m=''1377410''>impulse</span>
  <span m=''1377820''>response.</span> <span m=''1379550''>And</span> <span m=''1379710''>u4</span>
  <span m=''1380290''>comes</span> <span m=''1380560''>in</span> <span m=''1380650''>at</span>
  <span m=''1380760''>time</span> <span m=''1381040''>5,</span> <span m=''1381790''>and</span>
  <span m=''1381940''>this</span> <span m=''1382130''>is</span> <span m=''1382270''>its</span>
  <span m=''1382500''>impulse</span> <span m=''1382890''>response.</span> <span m=''1385200''>Does
  that</span> <span m=''1385480''>help?</span> <span m=''1387210''>How</span> <span
  m=''1387330''>many</span> <span m=''1387470''>people</span> <span m=''1387800''>are</span>
  <span m=''1387850''>not</span> <span m=''1388190''>getting</span> <span m=''1388460''>it</span>
  <span m=''1388600''>now?</span> </p><p><span m=''1393372''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1400930''>PROFESSOR: We</span> <span m=''1401050''>don''t</span>
  <span m=''1401320''>need it</span> <span m=''1401590''>here,</span> <span m=''1401820''>but</span>
  <span m=''1401950''>we''re</span> <span m=''1402050''>going</span> <span m=''1402270''>to</span>
  <span m=''1402550''>need it again at</span> <span m=''1402880''>time</span> <span
  m=''1403120''>4,</span> <span m=''1404740''>so</span> <span m=''1404870''>we</span>
  <span m=''1404960''>have</span> <span m=''1405130''>to</span> <span m=''1405240''>save</span>
  <span m=''1405550''>it.</span> <span m=''1410650''>What</span> <span m=''1410720''>are</span>
  <span m=''1410800''>you</span> <span m=''1410840''>going</span> <span m=''1410910''>to</span>
  <span m=''1410990''>do</span> <span m=''1411250''>with</span> <span m=''1411500''>it</span>
  <span m=''1411710''>at</span> <span m=''1411900''>time</span> <span m=''1412130''>3?</span>
  <span m=''1412490''>You</span> <span m=''1412580''>going</span> <span m=''1412740''>to</span>
  <span m=''1413550''>hide</span> <span m=''1413830''>it</span> <span m=''1413980''>somewhere?</span>
  <span m=''1418540''>So</span> <span m=''1418710''>I</span> <span m=''1419090''>still</span>
  <span m=''1419380''>need</span> <span m=''1419590''>to</span> <span m=''1419670''>save</span>
  <span m=''1420020''>it.</span> </p><p><span m=''1424410''>This,</span> <span m=''1425160''>again,</span>
  <span m=''1425690''>is</span> <span m=''1426830''>linear</span> <span m=''1427180''>system</span>
  <span m=''1427590''>theory,</span> <span m=''1427820''>except</span> <span m=''1428240''>I</span>
  <span m=''1428290''>guess</span> <span m=''1428510''>you</span> <span m=''1428650''>just</span>
  <span m=''1428820''>don''t</span> <span m=''1429010''>get</span> <span m=''1429200''>taught</span>
  <span m=''1429470''>linear</span> <span m=''1429780''>system</span> <span m=''1430200''>theory</span>
  <span m=''1430410''>anymore.</span> <span m=''1432670''>But</span> <span m=''1432910''>this</span>
  <span m=''1433180''>is</span> <span m=''1433670''>what</span> <span m=''1433870''>you</span>
  <span m=''1433990''>have</span> <span m=''1434130''>to</span> <span m=''1434250''>do</span>
  <span m=''1434550''>if</span> <span m=''1434660''>you  --</span> <span m=''1435490''>before,</span>
  <span m=''1436140''>for</span> <span m=''1436300''>convolutional</span> <span m=''1436940''>codes,</span>
  <span m=''1437430''>we</span> <span m=''1437580''>did</span> <span m=''1438350''>linear</span>
  <span m=''1438650''>systems</span> <span m=''1439130''>theory</span> <span m=''1439500''>for</span>
  <span m=''1439770''>linear</span> <span m=''1440150''>time-invariant</span> <span
  m=''1440880''>systems.</span> <span m=''1442470''>They</span> <span m=''1442640''>have
  to be over</span> <span m=''1442820''>a finite</span> <span m=''1443240''>field,</span>
  <span m=''1443600''>but who</span> <span m=''1443820''>cares?</span> <span m=''1444310''>We</span>
  <span m=''1444460''>did</span> <span m=''1444990''>general</span> <span m=''1445340''>linear</span>
  <span m=''1445700''>system</span> <span m=''1446030''>theory.</span> <span m=''1446330''>This</span>
  <span m=''1446590''>is</span> <span m=''1447100''>general</span> <span m=''1447500''>linear</span>
  <span m=''1447850''>system</span> <span m=''1448260''>theory</span> <span m=''1448680''>for</span>
  <span m=''1448880''>realizing</span> <span m=''1449470''>time-varying</span> <span
  m=''1450120''>systems.</span> </p><p><span m=''1454060''>In</span> <span m=''1454240''>fact,</span>
  <span m=''1454710''>one</span> <span m=''1455040''>comment</span> <span m=''1455450''>that</span>
  <span m=''1455580''>might</span> <span m=''1455830''>be</span> <span m=''1455920''>good</span>
  <span m=''1456200''>to</span> <span m=''1456280''>make</span> <span m=''1456550''>at</span>
  <span m=''1456670''>this</span> <span m=''1456910''>point</span> <span m=''1458060''>is</span>
  <span m=''1458350''>that  --</span> <span m=''1459470''>now</span> <span m=''1459700''>go</span>
  <span m=''1459860''>back</span> <span m=''1460180''>and</span> <span m=''1460290''>remember</span>
  <span m=''1460620''>what</span> <span m=''1460790''>we</span> <span m=''1460930''>did</span>
  <span m=''1461150''>with</span> <span m=''1461460''>convolutional</span> <span m=''1462190''>codes.</span>
  <span m=''1465250''>We</span> <span m=''1465370''>started</span> <span m=''1465850''>out</span>
  <span m=''1466190''>with</span> <span m=''1466470''>a</span> <span m=''1468190''>rate</span>
  <span m=''1468450''>1</span> <span m=''1468650''>over</span> <span m=''1468960''>n</span>
  <span m=''1469180''>convolutional</span> <span m=''1469800''>code</span> <span m=''1470170''>c,</span>
  <span m=''1471280''>and</span> <span m=''1471480''>we</span> <span m=''1471630''>found</span>
  <span m=''1472940''>some</span> <span m=''1473480''>generator</span> <span m=''1474020''>for</span>
  <span m=''1474510''>it.</span> <span m=''1474760''>Basically</span> <span m=''1475220''>we
  can</span> <span m=''1475440''>take</span> <span m=''1475910''>any</span> <span
  m=''1476190''>code</span> <span m=''1476470''>word</span> <span m=''1477760''>in</span>
  <span m=''1478250''>the</span> <span m=''1478370''>code,</span> <span m=''1478920''>and</span>
  <span m=''1479150''>all</span> <span m=''1479400''>of</span> <span m=''1479520''>its</span>
  <span m=''1479620''>shifts</span> <span m=''1480080''>will</span> <span m=''1480260''>generate</span>
  <span m=''1480720''>the</span> <span m=''1480830''>code.</span> <span m=''1481410''>Any</span>
  <span m=''1481610''>non-zero</span> <span m=''1482170''>code</span> <span m=''1482440''>word,</span>
  <span m=''1483380''>all</span> <span m=''1483670''>of its</span> <span m=''1483780''>time</span>
  <span m=''1484160''>shifts</span> <span m=''1484550''>generate</span> <span m=''1484940''>the</span>
  <span m=''1485030''>convolutional</span> <span m=''1485630''>code.</span> <span
  m=''1489290''>So</span> <span m=''1490100''>take</span> <span m=''1490380''>any</span>
  <span m=''1490750''>code</span> <span m=''1491040''>word</span> <span m=''1492500''>g</span>
  <span m=''1492660''>of</span> <span m=''1492830''>d</span> <span m=''1492950''>in</span>
  <span m=''1493320''>a</span> <span m=''1493490''>convolutional</span> <span m=''1494300''>code,</span>
  <span m=''1495300''>and</span> <span m=''1495620''>g</span> <span m=''1495870''>of</span>
  <span m=''1496000''>d,</span> <span m=''1496320''>dg</span> <span m=''1496910''>of</span>
  <span m=''1497030''>d,</span> <span m=''1497530''>d</span> <span m=''1497750''>squared</span>
  <span m=''1498210''>g</span> <span m=''1498520''>of d</span> <span m=''1498700''>and</span>
  <span m=''1498810''>so</span> <span m=''1499010''>forth</span> <span m=''1499320''>generate</span>
  <span m=''1499740''>the code.</span> </p><p><span m=''1503000''>But</span> <span
  m=''1503100''>then</span> <span m=''1503300''>we</span> <span m=''1503510''>converted</span>
  <span m=''1503845''>it</span> <span m=''1506880''>by</span> <span m=''1507360''>doing</span>
  <span m=''1507650''>a</span> <span m=''1507720''>little</span> <span m=''1509250''>polynomial</span>
  <span m=''1510130''>or</span> <span m=''1511400''>Laurent</span> <span m=''1511690''>series</span>
  <span m=''1512210''>algebra.</span> <span m=''1514830''>We</span> <span m=''1515320''>took</span>
  <span m=''1515530''>a</span> <span m=''1515590''>rational</span> <span m=''1516160''>one</span>
  <span m=''1517160''>and</span> <span m=''1517280''>we</span> <span m=''1517470''>converted</span>
  <span m=''1518000''>it</span> <span m=''1518360''>to</span> <span m=''1519520''>a</span>
  <span m=''1519640''>canonical</span> <span m=''1520270''>one,</span> <span m=''1522990''>g</span>
  <span m=''1523280''>prime</span> <span m=''1523680''>of</span> <span m=''1524140''>d.</span>
  <span m=''1525980''>Which</span> <span m=''1526260''>if</span> <span m=''1526350''>you</span>
  <span m=''1526500''>remember,</span> <span m=''1526990''>this</span> <span m=''1527250''>is</span>
  <span m=''1527500''>the</span> <span m=''1527880''>polynomial</span> <span m=''1528770''>code</span>
  <span m=''1529060''>word</span> <span m=''1529390''>of</span> <span m=''1529480''>minimum</span>
  <span m=''1529920''>degree</span> <span m=''1535500''>in</span> <span m=''1535690''>the</span>
  <span m=''1535830''>code.</span> <span m=''1536840''>We</span> <span m=''1537340''>call</span>
  <span m=''1537620''>that</span> <span m=''1537780''>degree</span> <span m=''1538610''>nu.</span>
  </p><p><span m=''1542780''>What</span> <span m=''1542930''>were</span> <span m=''1543060''>we</span>
  <span m=''1543220''>doing</span> <span m=''1543540''>there?</span> <span m=''1548060''>The</span>
  <span m=''1548310''>shifts</span> <span m=''1548670''>of</span> <span m=''1548970''>g</span>
  <span m=''1549210''>prime</span> <span m=''1549615''>of</span> <span m=''1550020''>d</span>
  <span m=''1550160''>form</span> <span m=''1550500''>a</span> <span m=''1551170''>trellis-oriented</span>
  <span m=''1551880''>generator</span> <span m=''1552350''>matrix</span> <span m=''1552930''>for</span>
  <span m=''1553190''>this</span> <span m=''1553460''>convolutional</span> <span m=''1554060''>code.</span>
  <span m=''1556080''>For</span> <span m=''1556260''>instance,</span> <span m=''1556880''>for</span>
  <span m=''1557350''>our</span> <span m=''1557690''>canonical</span> <span m=''1558250''>example,</span>
  <span m=''1559600''>g</span> <span m=''1559870''>prime</span> <span m=''1560240''>of</span>
  <span m=''1560370''>d</span> <span m=''1560620''>looked</span> <span m=''1560850''>like</span>
  <span m=''1561160''>this.</span> <span m=''1566070''>Polynomial</span> <span m=''1566720''>notation,</span>
  <span m=''1567510''>it''s</span> <span m=''1567840''>1</span> <span m=''1568510''>plus</span>
  <span m=''1569190''>d</span> <span m=''1569390''>squared</span> <span m=''1570000''>1</span>
  <span m=''1570250''>plus</span> <span m=''1570620''>d</span> <span m=''1570890''>plus</span>
  <span m=''1571170''>d</span> <span m=''1571340''>squared</span> <span m=''1571780''>is</span>
  <span m=''1571960''>the</span> <span m=''1572010''>generator</span> <span m=''1572500''>matrix.</span>
  <span m=''1573740''>Let</span> <span m=''1573880''>me</span> <span m=''1573990''>write</span>
  <span m=''1574300''>that</span> <span m=''1574520''>out</span> <span m=''1575020''>as</span>
  <span m=''1575950''>1,</span> <span m=''1576270''>1</span> <span m=''1576830''>at</span>
  <span m=''1577090''>time</span> <span m=''1578480''>0</span> <span m=''1579180''>or</span>
  <span m=''1579860''>coefficient</span> <span m=''1580390''>0.</span> <span m=''1582380''>0,</span>
  <span m=''1582830''>1,</span> <span m=''1583380''>1,</span> <span m=''1583630''>1,</span>
  <span m=''1584540''>and</span> <span m=''1584710''>then</span> <span m=''1584990''>all</span>
  <span m=''1585300''>0''s</span> <span m=''1585760''>before</span> <span m=''1586170''>that,</span>
  <span m=''1588800''>and</span> <span m=''1588950''>all</span> <span m=''1589160''>0''s</span>
  <span m=''1589660''>after</span> <span m=''1589920''>that.</span> </p><p><span m=''1590190''>Is
  somebody</span> <span m=''1590520''>sleeping?</span> <span m=''1592720''>Wake</span>
  <span m=''1593020''>him</span> <span m=''1593240''>up</span> <span m=''1593420''>please,</span>
  <span m=''1593760''>before</span> <span m=''1594100''>I</span> <span m=''1594130''>turn</span>
  <span m=''1594380''>around.</span> <span m=''1598860''>What?</span> <span m=''1600696''>Oh,</span>
  <span m=''1601160''>all</span> <span m=''1601270''>right.</span> <span m=''1603190''>I''m</span>
  <span m=''1603630''>very</span> <span m=''1603980''>glad to</span> <span m=''1604420''>hear</span>
  <span m=''1604700''>that.</span> </p><p><span m=''1606360''>So</span> <span m=''1606640''>here</span>
  <span m=''1606950''>is</span> <span m=''1607950''>g</span> <span m=''1608210''>prime</span>
  <span m=''1608570''>of</span> <span m=''1608780''>d</span> <span m=''1609000''>written</span>
  <span m=''1609370''>out</span> <span m=''1610410''>as</span> <span m=''1610840''>bits.</span>
  <span m=''1612270''>dg</span> <span m=''1612870''>prime</span> <span m=''1613170''>of</span>
  <span m=''1613410''>d</span> <span m=''1613590''>looks</span> <span m=''1613900''>like</span>
  <span m=''1614180''>what?</span> <span m=''1614530''>It looks</span> <span m=''1614740''>like</span>
  <span m=''1614910''>the</span> <span m=''1614960''>same</span> <span m=''1615250''>thing</span>
  <span m=''1616320''>shifted</span> <span m=''1616830''>over</span> <span m=''1617120''>one.</span>
  <span m=''1620890''>d</span> <span m=''1621840''>squared</span> <span m=''1622370''>g</span>
  <span m=''1622590''>prime</span> <span m=''1622985''>of d</span> <span m=''1624420''>looks</span>
  <span m=''1624720''>like</span> <span m=''1626970''>this</span> <span m=''1629250''>and</span>
  <span m=''1629530''>so</span> <span m=''1629720''>forth.</span> </p><p><span m=''1635900''>Is</span>
  <span m=''1636150''>this</span> <span m=''1636750''>trellis-oriented?</span> <span
  m=''1638320''>In</span> <span m=''1638400''>this</span> <span m=''1638620''>case,</span>
  <span m=''1639250''>each</span> <span m=''1639560''>time</span> <span m=''1639890''>interval</span>
  <span m=''1640570''>contains</span> <span m=''1641150''>two</span> <span m=''1641330''>symbols.</span>
  <span m=''1642680''>Here</span> <span m=''1643040''>are</span> <span m=''1643380''>our</span>
  <span m=''1643720''>divisions</span> <span m=''1644430''>between</span> <span m=''1645330''>symbols.</span>
  <span m=''1646680''>We''ve</span> <span m=''1646780''>got</span> <span m=''1646890''>a</span>
  <span m=''1646920''>rate</span> <span m=''1647090''>1/2</span> <span m=''1647610''>code,</span>
  <span m=''1648030''>so we</span> <span m=''1648300''>chose to</span> <span m=''1648570''>take
  them</span> <span m=''1648950''>two</span> <span m=''1649150''>symbols</span> <span
  m=''1649580''>at</span> <span m=''1649690''>a</span> <span m=''1649780''>time.</span>
  </p><p><span m=''1654050''>Where</span> <span m=''1654460''>are the</span> <span
  m=''1654600''>starting</span> <span m=''1655100''>and</span> <span m=''1655250''>ending</span>
  <span m=''1655360''>times?</span> <span m=''1655830''>This</span> <span m=''1655980''>one</span>
  <span m=''1656120''>starts</span> <span m=''1656570''>here,</span> <span m=''1656880''>ends</span>
  <span m=''1657160''>here.</span> <span m=''1657550''>This</span> <span m=''1657740''>one</span>
  <span m=''1657870''>starts</span> <span m=''1658310''>here,</span> <span m=''1658610''>ends</span>
  <span m=''1658930''>here.</span> <span m=''1659210''>Starts</span> <span m=''1659660''>here,</span>
  <span m=''1659920''>ends</span> <span m=''1660230''>here.</span> <span m=''1661100''>So</span>
  <span m=''1661310''>all</span> <span m=''1661480''>the</span> <span m=''1661540''>starting</span>
  <span m=''1661890''>times</span> <span m=''1662250''>and ending</span> <span m=''1662590''>times</span>
  <span m=''1662910''>are</span> <span m=''1662960''>different.</span> <span m=''1663710''>Ergo,</span>
  <span m=''1664110''>this</span> <span m=''1664310''>is</span> <span m=''1664410''>a</span>
  <span m=''1664440''>trellis-oriented</span> <span m=''1664990''>generator</span>
  <span m=''1665530''>matrix.</span> <span m=''1667350''>Modulo</span> <span m=''1667900''>some</span>
  <span m=''1668110''>hand-waving</span> <span m=''1668700''>about</span> <span m=''1668960''>infinite</span>
  <span m=''1669390''>sequences.</span> </p><p><span m=''1671420''>Ergo,</span> <span
  m=''1671910''>we</span> <span m=''1672050''>ought</span> <span m=''1672120''>to</span>
  <span m=''1672190''>be</span> <span m=''1672340''>able to</span> <span m=''1672430''>use
  the</span> <span m=''1672690''>state</span> <span m=''1673140''>space</span> <span
  m=''1673520''>theorem</span> <span m=''1673900''>to</span> <span m=''1673990''>say</span>
  <span m=''1674240''>what</span> <span m=''1674450''>are</span> <span m=''1674630''>the</span>
  <span m=''1674780''>state</span> <span m=''1675090''>space</span> <span m=''1675450''>sizes.</span>
  <span m=''1677830''>Any</span> <span m=''1678100''>time</span> <span m=''1678420''>I</span>
  <span m=''1678500''>have</span> <span m=''1678670''>a</span> <span m=''1678740''>cut</span>
  <span m=''1679020''>here,</span> <span m=''1680010''>what</span> <span m=''1680190''>are</span>
  <span m=''1680230''>the</span> <span m=''1680360''>spans?</span> <span m=''1681020''>The</span>
  <span m=''1681210''>spans</span> <span m=''1681570''>are</span> <span m=''1681650''>like</span>
  <span m=''1681890''>there,</span> <span m=''1682600''>there,</span> <span m=''1683290''>there,</span>
  <span m=''1683770''>so</span> <span m=''1684020''>forth.</span> <span m=''1685590''>So</span>
  <span m=''1686180''>the</span> <span m=''1686280''>state</span> <span m=''1686650''>space</span>
  <span m=''1687070''>dimension</span> <span m=''1689120''>at</span> <span m=''1689320''>each</span>
  <span m=''1689600''>time</span> <span m=''1689980''>is</span> <span m=''1690170''>going</span>
  <span m=''1690320''>to</span> <span m=''1690460''>be</span> <span m=''1691010''>2,</span>
  <span m=''1691670''>2,</span> <span m=''1692250''>2,</span> <span m=''1692890''>2,</span>
  <span m=''1693500''>2.</span> </p><p><span m=''1696070''>And</span> <span m=''1696240''>if</span>
  <span m=''1696340''>we</span> <span m=''1696460''>go</span> <span m=''1696640''>through</span>
  <span m=''1696840''>this</span> <span m=''1697060''>construction</span> <span m=''1697660''>procedure,</span>
  <span m=''1698250''>what are</span> <span m=''1698460''>we</span> <span m=''1698580''>going</span>
  <span m=''1698690''>to</span> <span m=''1698730''>get?</span> <span m=''1700470''>We''re</span>
  <span m=''1700960''>going</span> <span m=''1701070''>to</span> <span m=''1701110''>get</span>
  <span m=''1701360''>something</span> <span m=''1702250''>that</span> <span m=''1702535''>at</span>
  <span m=''1702820''>time</span> <span m=''1703250''>0,</span> <span m=''1703600''>we</span>
  <span m=''1703790''>need</span> <span m=''1704080''>to</span> <span m=''1705230''>have</span>
  <span m=''1705400''>in</span> <span m=''1705570''>memory,</span> <span m=''1707810''>we</span>
  <span m=''1708240''>need</span> <span m=''1708460''>to</span> <span m=''1708540''>remember</span>
  <span m=''1709110''>u</span> <span m=''1709370''>minus</span> <span m=''1709830''>1</span>
  <span m=''1710520''>and</span> <span m=''1711180''>u</span> <span m=''1711350''>minus</span>
  <span m=''1711810''>2.</span> <span m=''1715050''>At</span> <span m=''1715250''>time</span>
  <span m=''1715610''>1,</span> <span m=''1717130''>just</span> <span m=''1717360''>doing</span>
  <span m=''1717610''>what</span> <span m=''1717770''>I</span> <span m=''1717810''>did</span>
  <span m=''1717990''>up</span> <span m=''1718160''>here,</span> <span m=''1718410''>we</span>
  <span m=''1718540''>need</span> <span m=''1718740''>to</span> <span m=''1718910''>have</span>
  <span m=''1719070''>in</span> <span m=''1719180''>memory</span> <span m=''1719810''>u</span>
  <span m=''1720030''>minus</span> <span m=''1720430''>1</span> <span m=''1721280''>and</span>
  <span m=''1721450''>u0.</span> <span m=''1723270''>At</span> <span m=''1723460''>time</span>
  <span m=''1723820''>2,</span> <span m=''1724130''>we</span> <span m=''1724270''>need</span>
  <span m=''1724510''>to</span> <span m=''1724650''>have</span> <span m=''1724790''>in</span>
  <span m=''1724900''>memory</span> <span m=''1725950''>u0</span> <span m=''1726850''>and</span>
  <span m=''1727080''>u1.</span> <span m=''1728810''>And</span> <span m=''1728930''>we</span>
  <span m=''1729060''>achieve</span> <span m=''1729430''>that</span> <span m=''1729710''>just</span>
  <span m=''1729940''>by</span> <span m=''1730120''>implementing</span> <span m=''1730580''>this</span>
  <span m=''1730780''>with</span> <span m=''1730880''>a</span> <span m=''1730970''>shift</span>
  <span m=''1731230''>register.</span> <span m=''1732450''>In</span> <span m=''1732550''>the</span>
  <span m=''1732660''>time-invariant</span> <span m=''1733430''>case</span> <span
  m=''1733800''>it''s</span> <span m=''1733970''>very</span> <span m=''1734210''>easy,</span>
  <span m=''1735650''>and</span> <span m=''1735840''>you all</span> <span m=''1736020''>understand</span>
  <span m=''1736320''>it.</span> </p><p><span m=''1737540''>So</span> <span m=''1740630''>exactly</span>
  <span m=''1741230''>the</span> <span m=''1741330''>same</span> <span m=''1741620''>theory</span>
  <span m=''1742050''>goes</span> <span m=''1742390''>through</span> <span m=''1742770''>for</span>
  <span m=''1743100''>rate</span> <span m=''1743260''>1</span> <span m=''1743480''>over</span>
  <span m=''1743700''>n</span> <span m=''1743890''>convolutional</span> <span m=''1744480''>codes.</span>
  <span m=''1745830''>I</span> <span m=''1746140''>will</span> <span m=''1746330''>tell</span>
  <span m=''1746470''>you</span> <span m=''1746610''>briefly</span> <span m=''1747220''>that</span>
  <span m=''1747470''>to</span> <span m=''1747820''>treat</span> <span m=''1748240''>rate</span>
  <span m=''1748680''>k</span> <span m=''1748910''>over</span> <span m=''1749220''>n,</span>
  <span m=''1749680''>it''s</span> <span m=''1750000''>basically</span> <span m=''1750440''>just</span>
  <span m=''1750670''>the</span> <span m=''1750750''>same</span> <span m=''1751040''>thing,</span>
  <span m=''1751950''>except</span> <span m=''1752270''>we</span> <span m=''1752410''>need</span>
  <span m=''1752980''>k</span> <span m=''1753230''>generators</span> <span m=''1753860''>starting</span>
  <span m=''1754250''>at</span> <span m=''1754320''>each</span> <span m=''1754580''>time</span>
  <span m=''1754910''>here.</span> <span m=''1755590''>But</span> <span m=''1756030''>in</span>
  <span m=''1756110''>order</span> <span m=''1756300''>to</span> <span m=''1756350''>get</span>
  <span m=''1756560''>a</span> <span m=''1756985''>canonical</span> <span m=''1757410''>encoder,</span>
  <span m=''1758200''>we</span> <span m=''1758370''>just</span> <span m=''1759180''>get</span>
  <span m=''1759300''>a</span> <span m=''1759370''>trellis-oriented</span> <span m=''1760060''>generator</span>
  <span m=''1760510''>matrix</span> <span m=''1760980''>again.</span> <span m=''1762790''>And</span>
  <span m=''1763110''>by</span> <span m=''1763280''>the</span> <span m=''1763450''>way,</span>
  <span m=''1764230''>modulo</span> <span m=''1764700''>this</span> <span m=''1764940''>hand-waving</span>
  <span m=''1765450''>about</span> <span m=''1765850''>infinite</span> <span m=''1766300''>sequences,</span>
  <span m=''1766930''>I''ve</span> <span m=''1767110''>now</span> <span m=''1767330''>proved</span>
  <span m=''1768180''>what</span> <span m=''1768320''>I</span> <span m=''1768460''>asserted,</span>
  <span m=''1770050''>that</span> <span m=''1771800''>this</span> <span m=''1771950''>encoder</span>
  <span m=''1772760''>is</span> <span m=''1773010''>minimal</span> <span m=''1773650''>among</span>
  <span m=''1774070''>all</span> <span m=''1774440''>encoders</span> <span m=''1775040''>for</span>
  <span m=''1775140''>this</span> <span m=''1775410''>code,</span> <span m=''1775700''>that</span>
  <span m=''1775990''>it has</span> <span m=''1776310''>the</span> <span m=''1776390''>minimum</span>
  <span m=''1776810''>number</span> <span m=''1777100''>of</span> <span m=''1777230''>memory</span>
  <span m=''1777510''>elements.</span> <span m=''1778640''>Because</span> <span m=''1779360''>from</span>
  <span m=''1779590''>this</span> <span m=''1779840''>argument,</span> <span m=''1780970''>the</span>
  <span m=''1781040''>minimal</span> <span m=''1781390''>state</span> <span m=''1781770''>space</span>
  <span m=''1782300''>dimension</span> <span m=''1782810''>at</span> <span m=''1783020''>each</span>
  <span m=''1783270''>time</span> <span m=''1783670''>is</span> <span m=''1783860''>2</span>
  <span m=''1785130''>once</span> <span m=''1785420''>I''ve</span> <span m=''1785490''>achieved</span>
  <span m=''1786010''>this</span> <span m=''1786560''>canonical</span> <span m=''1787070''>trellis-oriented</span>
  <span m=''1787810''>generator</span> <span m=''1788240''>matrix.</span> </p><p><span
  m=''1793070''>By</span> <span m=''1793270''>the</span> <span m=''1793390''>way,</span>
  <span m=''1793740''>this</span> <span m=''1794010''>theory</span> <span m=''1794260''>is</span>
  <span m=''1794440''>very</span> <span m=''1794670''>general.</span> <span m=''1797190''>It''s</span>
  <span m=''1797290''>really</span> <span m=''1797690''>all</span> <span m=''1797890''>you</span>
  <span m=''1798020''>need</span> <span m=''1798200''>to</span> <span m=''1798310''>know</span>
  <span m=''1798700''>to</span> <span m=''1799370''>do</span> <span m=''1799560''>minimal</span>
  <span m=''1799900''>realization</span> <span m=''1800610''>theory</span> <span m=''1800930''>of</span>
  <span m=''1801040''>linear</span> <span m=''1801350''>systems,</span> <span m=''1804110''>whether</span>
  <span m=''1804360''>they''re</span> <span m=''1804560''>time-varying</span> <span
  m=''1805610''>or</span> <span m=''1805680''>time-invariant</span> <span m=''1806020''>over</span>
  <span m=''1806460''>any</span> <span m=''1806860''>field,</span> <span m=''1808440''>or
  over</span> <span m=''1808780''>groups.</span> </p><p><span m=''1813140''>So</span>
  <span m=''1813390''>that</span> <span m=''1813610''>was</span> <span m=''1813850''>a</span>
  <span m=''1814290''>parenthetical</span> <span m=''1814730''>comment</span> <span
  m=''1815220''>about</span> <span m=''1815680''>convolutional</span> <span m=''1816290''>codes</span>
  <span m=''1816740''>just</span> <span m=''1816960''>to</span> <span m=''1817070''>tie</span>
  <span m=''1817320''>it</span> <span m=''1817440''>back</span> <span m=''1817750''>to</span>
  <span m=''1817870''>what</span> <span m=''1817990''>we</span> <span m=''1818100''>did</span>
  <span m=''1818270''>in</span> <span m=''1818360''>the</span> <span m=''1818440''>previous</span>
  <span m=''1818910''>chapter.</span> <span m=''1824860''>I</span> <span m=''1825010''>haven''t</span>
  <span m=''1825310''>completed</span> <span m=''1825750''>what</span> <span m=''1825920''>I</span>
  <span m=''1825980''>wanted</span> <span m=''1826230''>to</span> <span m=''1826340''>say</span>
  <span m=''1826590''>about</span> <span m=''1826680''>block</span> <span m=''1827050''>codes.</span>
  <span m=''1829320''>How</span> <span m=''1829580''>am I</span> <span m=''1829770''>going</span>
  <span m=''1830010''>to</span> <span m=''1830240''>do this</span> <span m=''1830660''>without
  erasing</span> <span m=''1830760''>something?</span> <span m=''1835080''>Let''s
  go</span> <span m=''1835575''>back</span> <span m=''1836070''>to</span> <span m=''1836170''>block</span>
  <span m=''1836580''>codes.</span> <span m=''1839140''>And</span> <span m=''1839440''>I</span>
  <span m=''1839740''>guess</span> <span m=''1840115''>I''ll move</span> <span m=''1840490''>over.</span>
  </p><p><span m=''1844710''>The</span> <span m=''1844830''>point</span> <span m=''1845150''>that</span>
  <span m=''1845280''>I</span> <span m=''1845330''>was</span> <span m=''1845530''>in</span>
  <span m=''1845590''>the</span> <span m=''1845670''>process</span> <span m=''1846260''>of</span>
  <span m=''1846360''>making</span> <span m=''1847120''>was</span> <span m=''1847560''>that</span>
  <span m=''1850620''>I can</span> <span m=''1850730''>realize</span> <span m=''1851370''>each</span>
  <span m=''1851660''>one</span> <span m=''1851860''>of</span> <span m=''1851910''>these</span>
  <span m=''1852190''>generators</span> <span m=''1853000''>individually</span> <span
  m=''1855410''>by</span> <span m=''1855890''>a</span> <span m=''1856060''>little</span>
  <span m=''1858460''>trellis</span> <span m=''1858900''>diagram</span> <span m=''1859570''>that''s</span>
  <span m=''1860590''>one-dimensional</span> <span m=''1861710''>during</span> <span
  m=''1861910''>the</span> <span m=''1862100''>time</span> <span m=''1862380''>that
  the</span> <span m=''1862520''>generator</span> <span m=''1862820''>is</span> <span
  m=''1863120''>active,</span> <span m=''1863640''>and</span> <span m=''1865990''>zero-dimensional</span>
  <span m=''1866870''>state</span> <span m=''1867230''>space</span> <span m=''1867590''>during</span>
  <span m=''1867790''>the</span> <span m=''1867890''>time</span> <span m=''1868110''>the</span>
  <span m=''1868200''>generator</span> <span m=''1868480''>is</span> <span m=''1868760''>inactive.</span>
  <span m=''1871220''>And</span> <span m=''1871600''>think</span> <span m=''1872040''>of</span>
  <span m=''1872310''>this</span> <span m=''1872570''>as</span> <span m=''1872810''>just</span>
  <span m=''1873090''>one</span> <span m=''1873390''>component</span> <span m=''1874080''>here.</span>
  </p><p><span m=''1875840''>To</span> <span m=''1876730''>generate</span> <span m=''1877140''>a</span>
  <span m=''1877210''>code</span> <span m=''1877560''>word,</span> <span m=''1879030''>a</span>
  <span m=''1879180''>particular</span> <span m=''1879820''>code</span> <span m=''1880120''>word</span>
  <span m=''1880420''>is</span> <span m=''1880630''>just</span> <span m=''1882550''>the</span>
  <span m=''1882660''>sum.</span> <span m=''1883700''>All</span> <span m=''1883920''>I</span>
  <span m=''1883980''>need</span> <span m=''1884170''>to</span> <span m=''1884270''>do</span>
  <span m=''1884460''>is</span> <span m=''1884530''>sum</span> <span m=''1884910''>the</span>
  <span m=''1885050''>outputs</span> <span m=''1885630''>of</span> <span m=''1885710''>all</span>
  <span m=''1885880''>these</span> <span m=''1886140''>generators</span> <span m=''1886870''>independently.</span>
  <span m=''1888400''>How</span> <span m=''1888540''>many</span> <span m=''1888900''>different</span>
  <span m=''1889230''>possibilities</span> <span m=''1890030''>are</span> <span m=''1890200''>there?</span>
  <span m=''1890430''>There</span> <span m=''1890570''>are</span> <span m=''1890640''>2</span>
  <span m=''1890870''>to</span> <span m=''1890940''>the</span> <span m=''1891090''>k</span>
  <span m=''1891620''>possible</span> <span m=''1892110''>code</span> <span m=''1892340''>words.</span>
  <span m=''1893380''>Each</span> <span m=''1893570''>one</span> <span m=''1893750''>of</span>
  <span m=''1893800''>these</span> <span m=''1894080''>generates</span> <span m=''1894550''>one</span>
  <span m=''1894740''>of</span> <span m=''1894840''>two</span> <span m=''1895050''>possible</span>
  <span m=''1895550''>code</span> <span m=''1895780''>words.</span> <span m=''1896120''>If
  I</span> <span m=''1896260''>take</span> <span m=''1896580''>the</span> <span m=''1896670''>set</span>
  <span m=''1896900''>of</span> <span m=''1897020''>all</span> <span m=''1898110''>possible</span>
  <span m=''1898570''>sums</span> <span m=''1899140''>of</span> <span m=''1899280''>these</span>
  <span m=''1899560''>four</span> <span m=''1900040''>code</span> <span m=''1900280''>words,</span>
  <span m=''1900660''>I''m</span> <span m=''1900780''>going</span> <span m=''1900900''>to</span>
  <span m=''1900940''>have</span> <span m=''1901050''>16</span> <span m=''1901600''>possible</span>
  <span m=''1902060''>code</span> <span m=''1902280''>words.</span> <span m=''1903240''>So</span>
  <span m=''1903530''>that</span> <span m=''1904020''>very</span> <span m=''1904390''>quickly</span>
  <span m=''1904860''>was</span> <span m=''1905060''>what</span> <span m=''1905240''>I</span>
  <span m=''1905330''>was</span> <span m=''1905540''>doing</span> <span m=''1905820''>when</span>
  <span m=''1905910''>I</span> <span m=''1906000''>said,</span> <span m=''1906660''>here''s</span>
  <span m=''1906920''>a</span> <span m=''1906970''>little</span> <span m=''1907190''>machine</span>
  <span m=''1908200''>that</span> <span m=''1908310''>generates</span> <span m=''1909090''>the</span>
  <span m=''1909180''>first</span> <span m=''1909570''>code,</span> <span m=''1910070''>c1.</span>
  <span m=''1910960''>Here''s</span> <span m=''1911190''>a</span> <span m=''1911240''>little</span>
  <span m=''1911380''>machine</span> <span m=''1911770''>that</span> <span m=''1911900''>generates</span>
  <span m=''1912390''>the</span> <span m=''1912480''>second</span> <span m=''1912910''>code,</span>
  <span m=''1913780''>c2.</span> <span m=''1915150''>Only</span> <span m=''1915350''>has</span>
  <span m=''1915510''>two</span> <span m=''1915690''>possible</span> <span m=''1916170''>code</span>
  <span m=''1916410''>words</span> <span m=''1916790''>according</span> <span m=''1917180''>to</span>
  <span m=''1917240''>the</span> <span m=''1917330''>value</span> <span m=''1917780''>of</span>
  <span m=''1917970''>what''s</span> <span m=''1918280''>in</span> <span m=''1918370''>storage.</span>
  <span m=''1919400''>This</span> <span m=''1919610''>generates</span> <span m=''1920620''>the</span>
  <span m=''1920870''>third</span> <span m=''1921540''>component.</span> <span m=''1922180''>This</span>
  <span m=''1922400''>generates</span> <span m=''1922860''>the</span> <span m=''1922950''>fourth</span>
  <span m=''1923300''>component.</span> <span m=''1924250''>Sum it</span> <span m=''1924580''>all</span>
  <span m=''1924850''>together,</span> <span m=''1926130''>and</span> <span m=''1926270''>you</span>
  <span m=''1926400''>get  --</span> <span m=''1927200''>sorry,</span> <span m=''1927670''>I''m
  calling</span> <span m=''1927950''>this</span> <span m=''1928120''>y</span> <span
  m=''1928500''>now.</span> <span m=''1928900''>y</span> <span m=''1929340''>equals</span>
  <span m=''1929920''>the</span> <span m=''1930020''>sum</span> <span m=''1930420''>of</span>
  <span m=''1930550''>the</span> <span m=''1930640''>ui</span> <span m=''1931050''>gi.</span>
  <span m=''1934540''>You</span> <span m=''1934630''>see</span> <span m=''1935060''>that?</span>
  <span m=''1936750''>I</span> <span m=''1936930''>hope</span> <span m=''1937130''>I''ve</span>
  <span m=''1937415''>beaten</span> <span m=''1937700''>it</span> <span m=''1939560''>into</span>
  <span m=''1939710''>the</span> <span m=''1939820''>ground</span> <span m=''1940200''>enough</span>
  <span m=''1940540''>now.</span> </p><p><span m=''1940850''>So</span> <span m=''1941310''>it''s</span>
  <span m=''1941600''>a</span> <span m=''1941690''>linear</span> <span m=''1942090''>time-varying</span>
  <span m=''1942730''>machine.</span> <span m=''1945170''>That</span> <span m=''1945400''>is</span>
  <span m=''1946070''>a</span> <span m=''1946190''>realization</span> <span m=''1946580''>of</span>
  <span m=''1946970''>it,</span> <span m=''1947670''>if</span> <span m=''1947770''>you''ve</span>
  <span m=''1948110''>understood</span> <span m=''1948670''>my</span> <span m=''1948800''>description</span>
  <span m=''1949350''>of</span> <span m=''1949490''>it</span> <span m=''1949620''>now.</span>
  <span m=''1950590''>And</span> <span m=''1950720''>now</span> <span m=''1950860''>we</span>
  <span m=''1950970''>can</span> <span m=''1951100''>draw</span> <span m=''1951340''>the</span>
  <span m=''1951390''>trellis</span> <span m=''1951820''>of</span> <span m=''1951980''>it.</span>
  <span m=''1957120''>That</span> <span m=''1957550''>what</span> <span m=''1957940''>can</span>
  <span m=''1958110''>happen</span> <span m=''1959580''>at</span> <span m=''1959980''>time</span>
  <span m=''1960220''>1,</span> <span m=''1961760''>we</span> <span m=''1961920''>can</span>
  <span m=''1962110''>either</span> <span m=''1962300''>have</span> <span m=''1962510''>u1.</span>
  <span m=''1964080''>Now</span> <span m=''1964320''>I</span> <span m=''1964410''>can</span>
  <span m=''1964590''>label</span> <span m=''1965020''>my</span> <span m=''1965170''>states</span>
  <span m=''1966260''>here,</span> <span m=''1967100''>at</span> <span m=''1967300''>this</span>
  <span m=''1967550''>time</span> <span m=''1968460''>u1.</span> <span m=''1969060''>u1</span>
  <span m=''1969610''>can</span> <span m=''1969760''>be</span> <span m=''1969870''>either</span>
  <span m=''1970100''>0</span> <span m=''1970520''>or</span> <span m=''1970740''>1.</span>
  <span m=''1971160''>This</span> <span m=''1971360''>is</span> <span m=''1971510''>u1.</span>
  </p><p><span m=''1974390''>At</span> <span m=''1975710''>time</span> <span m=''1976040''>2,</span>
  <span m=''1978300''>I</span> <span m=''1978450''>have</span> <span m=''1978800''>both</span>
  <span m=''1979180''>u1</span> <span m=''1979940''>and</span> <span m=''1980120''>u2</span>
  <span m=''1981910''>in</span> <span m=''1982100''>my</span> <span m=''1982270''>state.</span>
  <span m=''1982810''>So</span> <span m=''1982980''>this</span> <span m=''1983190''>can</span>
  <span m=''1983360''>either</span> <span m=''1983570''>be</span> <span m=''1983740''>0,</span>
  <span m=''1984110''>0</span> <span m=''1985310''>or</span> <span m=''1985560''>0,</span>
  <span m=''1985930''>1,</span> <span m=''1987790''>or</span> <span m=''1989560''>1,</span>
  <span m=''1989900''>0</span> <span m=''1990550''>or</span> <span m=''1990770''>1,</span>
  <span m=''1991040''>1.</span> <span m=''1991900''>And</span> <span m=''1992060''>obviously</span>
  <span m=''1992380''>if</span> <span m=''1992510''>I''ve</span> <span m=''1992640''>already</span>
  <span m=''1992870''>determined</span> <span m=''1993340''>u1</span> <span m=''1993760''>is</span>
  <span m=''1993890''>0</span> <span m=''1994240''>here,</span> <span m=''1994480''>it''s
  still</span> <span m=''1994830''>going</span> <span m=''1994940''>to</span> <span
  m=''1994990''>be</span> <span m=''1995130''>0</span> <span m=''1996340''>at</span>
  <span m=''1996580''>time</span> <span m=''1999290''>2.</span> </p><p><span m=''2002180''>I</span>
  <span m=''2002380''>label</span> <span m=''2002710''>these</span> <span m=''2003070''>with</span>
  <span m=''2003340''>their</span> <span m=''2004620''>associated</span> <span m=''2005440''>outputs.</span>
  <span m=''2007910''>This</span> <span m=''2008180''>is</span> <span m=''2009220''>1.</span>
  <span m=''2010710''>This</span> <span m=''2011040''>is</span> <span m=''2012340''>also</span>
  <span m=''2012800''>1.</span> <span m=''2013160''>This</span> <span m=''2013360''>can</span>
  <span m=''2013500''>turn</span> <span m=''2013720''>it</span> <span m=''2013860''>back</span>
  <span m=''2014160''>to</span> <span m=''2014300''>0.</span> <span m=''2015660''>And</span>
  <span m=''2015880''>I</span> <span m=''2015950''>just</span> <span m=''2016130''>keep</span>
  <span m=''2016400''>going.</span> <span m=''2016760''>At</span> <span m=''2016870''>the</span>
  <span m=''2016970''>third</span> <span m=''2017340''>time,</span> <span m=''2017700''>I
  have</span> <span m=''2017900''>u1,</span> <span m=''2018360''>u2,</span> <span
  m=''2018800''>u3.</span> <span m=''2020390''>I</span> <span m=''2020540''>have</span>
  <span m=''2020970''>eight</span> <span m=''2021260''>states.</span> <span m=''2024060''>At</span>
  <span m=''2024500''>time</span> <span m=''2024800''>4,</span> <span m=''2025280''>I</span>
  <span m=''2025330''>come</span> <span m=''2025600''>back.</span> <span m=''2026020''>I</span>
  <span m=''2026090''>only</span> <span m=''2026340''>have</span> <span m=''2026600''>u2,</span>
  <span m=''2027200''>u3</span> <span m=''2028490''>at</span> <span m=''2028700''>time</span>
  <span m=''2029000''>4,</span> <span m=''2030130''>and</span> <span m=''2030280''>so</span>
  <span m=''2030540''>these</span> <span m=''2030830''>merge.</span> <span m=''2034430''>So</span>
  <span m=''2034590''>I</span> <span m=''2034690''>get</span> <span m=''2034980''>something
  --</span> <span m=''2036614''>this doesn''t</span> <span m=''2037026''>merge</span>
  <span m=''2037438''>like</span> <span m=''2037850''>that,</span> <span m=''2038210''>though.</span>
  <span m=''2038940''>It</span> <span m=''2039370''>merges</span> <span m=''2039830''>down</span>
  <span m=''2040150''>here.</span> <span m=''2041710''>0,</span> <span m=''2041970''>0,</span>
  <span m=''2042250''>0,</span> <span m=''2042740''>0,</span> <span m=''2043100''>0,</span>
  <span m=''2043410''>1.</span> <span m=''2043840''>This</span> <span m=''2043940''>merges</span>
  <span m=''2044310''>to</span> <span m=''2044590''>0,</span> <span m=''2044970''>1</span>
  <span m=''2045300''>when</span> <span m=''2045480''>I</span> <span m=''2045540''>drop</span>
  <span m=''2045900''>the</span> <span m=''2046000''>first</span> <span m=''2046400''>one.</span>
  <span m=''2049510''>It''s</span> <span m=''2049639''>probably</span> <span m=''2049989''>worth</span>
  <span m=''2050310''>doing</span> <span m=''2050590''>this</span> <span m=''2050800''>more</span>
  <span m=''2051040''>carefully</span> <span m=''2051500''>than</span> <span m=''2051659''>I''m</span>
  <span m=''2051800''>doing</span> <span m=''2052120''>it.</span> <span m=''2055040''>0,</span>
  <span m=''2055330''>1</span> <span m=''2055770''>can</span> <span m=''2055949''>go
  to</span> <span m=''2056210''>0,</span> <span m=''2056560''>1,</span> <span m=''2056800''>0,</span>
  <span m=''2057620''>or</span> <span m=''2058280''>0,</span> <span m=''2058600''>1,</span>
  <span m=''2058870''>1.</span> <span m=''2060330''>0,</span> <span m=''2060650''>1,</span>
  <span m=''2060929''>0</span> <span m=''2061489''>can</span> <span m=''2061830''>either</span>
  <span m=''2062260''>go</span> <span m=''2062580''>to --</span> <span m=''2070150''>u2</span>
  <span m=''2070739''>equals</span> <span m=''2071100''>1.</span> <span m=''2072290''>I</span>
  <span m=''2072429''>guess</span> <span m=''2074489''>these</span> <span m=''2074739''>can''t</span>
  <span m=''2075080''>cross.</span> <span m=''2076100''>u2 --</span> </p><p><span
  m=''2076420''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''2079639''>PROFESSOR:
  Excuse me?</span> </p><p><span m=''2080667''>AUDIENCE: [INAUDIBLE]</span> <span
  m=''2082098''>u3</span> <span m=''2082575''>and</span> <span m=''2083052''>u4.</span>
  </p><p><span m=''2086510''>PROFESSOR: No,</span> <span m=''2089880''>this</span>
  <span m=''2090110''>is</span> <span m=''2090199''>state</span> <span m=''2090670''>time.</span>
  <span m=''2091090''>State</span> <span m=''2091580''>time</span> <span m=''2091880''>1,</span>
  <span m=''2092440''>2,</span> <span m=''2093300''>3.</span> <span m=''2094580''>u4</span>
  <span m=''2094940''>hasn''t</span> <span m=''2095280''>started</span> <span m=''2095760''>yet.</span>
  <span m=''2097030''>So</span> <span m=''2097280''>I''m</span> <span m=''2097430''>sorry,</span>
  <span m=''2097790''>this</span> <span m=''2098030''>is</span> <span m=''2099470''>5</span>
  <span m=''2099980''>through</span> <span m=''2102200''>7.</span> <span m=''2102940''>Is</span>
  <span m=''2103020''>that</span> <span m=''2103540''>right?</span> <span m=''2105470''>It</span>
  <span m=''2105700''>only lasts</span> <span m=''2106070''>for</span> <span m=''2106210''>three</span>
  <span m=''2107410''>intervals.</span> <span m=''2109080''>So</span> <span m=''2109290''>I</span>
  <span m=''2109450''>only</span> <span m=''2109610''>have</span> <span m=''2109920''>u2,</span>
  <span m=''2110170''>u3.</span> <span m=''2116030''>u1,</span> <span m=''2116360''>u2</span>
  <span m=''2117010''>has to</span> <span m=''2117265''>be</span> <span m=''2117520''>0,</span>
  <span m=''2117880''>0,</span> <span m=''2118020''>1,</span> <span m=''2118690''>so</span>
  <span m=''2119170''>this</span> <span m=''2119520''>would</span> <span m=''2119700''>then</span>
  <span m=''2119900''>go</span> <span m=''2120080''>to</span> <span m=''2120150''>0,</span>
  <span m=''2120600''>1.</span> <span m=''2121660''>0,</span> <span m=''2121975''>1.</span>
  <span m=''2123100''>These</span> <span m=''2123230''>seem</span> <span m=''2123560''>to</span>
  <span m=''2123650''>cross.</span> <span m=''2127220''>Yes,</span> <span m=''2127515''>they</span>
  <span m=''2127810''>do</span> <span m=''2128300''>cross.</span> </p><p><span m=''2136040''>So</span>
  <span m=''2136450''>let''s</span> <span m=''2136650''>see</span> <span m=''2136780''>if</span>
  <span m=''2136940''>I</span> <span m=''2137020''>can</span> <span m=''2137170''>actually</span>
  <span m=''2137540''>complete</span> <span m=''2137850''>it.</span> <span m=''2139180''>This</span>
  <span m=''2139410''>could</span> <span m=''2139590''>go</span> <span m=''2139770''>to</span>
  <span m=''2139870''>1,</span> <span m=''2140170''>0,</span> <span m=''2140530''>0,</span>
  <span m=''2141970''>or</span> <span m=''2142110''>1,</span> <span m=''2142340''>0,</span>
  <span m=''2142710''>1.</span> <span m=''2146540''>And</span> <span m=''2146790''>then</span>
  <span m=''2147040''>this</span> <span m=''2147320''>one</span> <span m=''2147560''>goes</span>
  <span m=''2147940''>up</span> <span m=''2148170''>to</span> <span m=''2148310''>either</span>
  <span m=''2148600''>0,</span> <span m=''2148990''>0</span> <span m=''2149410''>or</span>
  <span m=''2149550''>0,</span> <span m=''2149910''>1.</span> <span m=''2151410''>This</span>
  <span m=''2151680''>one</span> <span m=''2152030''>can</span> <span m=''2152180''>go</span>
  <span m=''2152490''>to</span> <span m=''2152810''>1,</span> <span m=''2153090''>1,</span>
  <span m=''2153430''>0</span> <span m=''2154610''>or</span> <span m=''2155080''>1,</span>
  <span m=''2155330''>1,</span> <span m=''2155650''>1.</span> <span m=''2156990''>And</span>
  <span m=''2157470''>that</span> <span m=''2157510''>can</span> <span m=''2157880''>go</span>
  <span m=''2158130''>like</span> <span m=''2158320''>this.</span> </p><p><span m=''2161290''>So</span>
  <span m=''2161420''>there''s</span> <span m=''2161720''>the</span> <span m=''2161820''>trellis</span>
  <span m=''2162290''>for</span> <span m=''2162380''>the</span> <span m=''2162500''>first</span>
  <span m=''2162930''>half.</span> <span m=''2164520''>It''s</span> <span m=''2166161''>topologically</span>
  <span m=''2167930''>the</span> <span m=''2168040''>same,</span> <span m=''2168530''>but</span>
  <span m=''2169500''>looks</span> <span m=''2169790''>a</span> <span m=''2169830''>little</span>
  <span m=''2170030''>different</span> <span m=''2170960''>from</span> <span m=''2171190''>what</span>
  <span m=''2171350''>I</span> <span m=''2171410''>put</span> <span m=''2171610''>up</span>
  <span m=''2171760''>before.</span> <span m=''2172270''>I</span> <span m=''2172580''>interchanged</span>
  <span m=''2172920''>these</span> <span m=''2173190''>two</span> <span m=''2173430''>with</span>
  <span m=''2173610''>these</span> <span m=''2173790''>two,</span> <span m=''2175430''>and</span>
  <span m=''2176170''>this</span> <span m=''2176390''>one</span> <span m=''2176600''>with</span>
  <span m=''2176750''>this</span> <span m=''2176990''>one.</span> <span m=''2179510''>But</span>
  <span m=''2181560''>you</span> <span m=''2181720''>can</span> <span m=''2181850''>recover</span>
  <span m=''2184070''>the</span> <span m=''2184170''>trellis</span> <span m=''2184610''>that
  I</span> <span m=''2184750''>had</span> <span m=''2184890''>before.</span> <span
  m=''2186110''>In</span> <span m=''2186230''>any</span> <span m=''2186420''>case,</span>
  <span m=''2186810''>I</span> <span m=''2186870''>claim</span> <span m=''2187410''>when</span>
  <span m=''2187630''>I''ve</span> <span m=''2187790''>labeled</span> <span m=''2188230''>this</span>
  <span m=''2188680''>with</span> <span m=''2188940''>what</span> <span m=''2189190''>the</span>
  <span m=''2189320''>appropriate</span> <span m=''2189800''>output</span> <span m=''2190800''>is</span>
  <span m=''2191090''>at</span> <span m=''2191190''>each</span> <span m=''2191440''>time,</span>
  <span m=''2191770''>I''ve</span> <span m=''2191910''>got</span> <span m=''2192110''>my</span>
  <span m=''2192210''>minimal</span> <span m=''2192600''>trellis.</span> </p><p><span
  m=''2200340''>And</span> <span m=''2201070''>now</span> <span m=''2201370''>we</span>
  <span m=''2201520''>can</span> <span m=''2201690''>make</span> <span m=''2201970''>more</span>
  <span m=''2202310''>comments</span> <span m=''2202890''>about</span> <span m=''2205420''>how</span>
  <span m=''2205650''>the</span> <span m=''2205780''>trellis</span> <span m=''2206220''>works.</span>
  <span m=''2207910''>You</span> <span m=''2208030''>see</span> <span m=''2208360''>that</span>
  <span m=''2209130''>whenever</span> <span m=''2209820''>a</span> <span m=''2210120''>generator</span>
  <span m=''2210670''>starts,</span> <span m=''2211320''>we</span> <span m=''2211590''>have</span>
  <span m=''2211860''>what''s</span> <span m=''2212140''>called</span> <span m=''2212500''>a</span>
  <span m=''2212590''>divergence</span> <span m=''2213410''>in</span> <span m=''2213520''>the</span>
  <span m=''2213620''>trellis,</span> <span m=''2214400''>a</span> <span m=''2214480''>branching</span>
  <span m=''2215610''>process,</span> <span m=''2216280''>a</span> <span m=''2216360''>branching</span>
  <span m=''2216870''>out,</span> <span m=''2217520''>whereas</span> <span m=''2217870''>whenever</span>
  <span m=''2218280''>a</span> <span m=''2218340''>generator</span> <span m=''2218910''>ends,</span>
  <span m=''2219420''>we</span> <span m=''2219580''>have</span> <span m=''2219870''>a</span>
  <span m=''2220290''>convergence</span> <span m=''2221160''>in.</span> </p><p><span
  m=''2223690''>So</span> <span m=''2226530''>a</span> <span m=''2226640''>starting</span>
  <span m=''2227130''>time --</span> <span m=''2228180''>if</span> <span m=''2228340''>we</span>
  <span m=''2228460''>have</span> <span m=''2229560''>a</span> <span m=''2229660''>generator</span>
  <span m=''2230240''>starting,</span> <span m=''2231890''>then</span> <span m=''2232200''>we</span>
  <span m=''2232350''>get</span> <span m=''2232680''>a</span> <span m=''2232760''>branch</span>
  <span m=''2233230''>that</span> <span m=''2233340''>looks</span> <span m=''2233620''>like</span>
  <span m=''2233870''>this,</span> <span m=''2234350''>like</span> <span m=''2234600''>here,</span>
  <span m=''2234930''>and</span> <span m=''2235010''>here,</span> <span m=''2235350''>and</span>
  <span m=''2235450''>here.</span> <span m=''2236626''>When</span> <span m=''2236990''>we</span>
  <span m=''2237220''>have</span> <span m=''2237440''>an</span> <span m=''2237550''>ending</span>
  <span m=''2237910''>time,</span> <span m=''2238250''>we</span> <span m=''2238500''>have</span>
  <span m=''2238850''>branches</span> <span m=''2239340''>that</span> <span m=''2239450''>look</span>
  <span m=''2239660''>like</span> <span m=''2239900''>this,</span> <span m=''2240310''>like</span>
  <span m=''2240540''>here.</span> <span m=''2241630''>So</span> <span m=''2241850''>this</span>
  <span m=''2242050''>is</span> <span m=''2242260''>a</span> <span m=''2242400''>starting</span>
  <span m=''2242880''>time,</span> <span m=''2243250''>starting</span> <span m=''2243690''>time,</span>
  <span m=''2244050''>starting</span> <span m=''2244510''>time,</span> <span m=''2244880''>and</span>
  <span m=''2245150''>ending</span> <span m=''2245340''>time.</span> <span m=''2248940''>So</span>
  <span m=''2249170''>this</span> <span m=''2250230''>tells</span> <span m=''2250580''>you</span>
  <span m=''2251380''>when</span> <span m=''2251720''>things</span> <span m=''2252160''>open</span>
  <span m=''2252580''>and</span> <span m=''2252810''>close</span> <span m=''2253970''>in</span>
  <span m=''2254170''>the</span> <span m=''2254280''>trellis.</span> </p><p><span
  m=''2256230''>Now</span> <span m=''2256360''>again,</span> <span m=''2257060''>as</span>
  <span m=''2257210''>I''ve</span> <span m=''2257290''>said</span> <span m=''2257700''>for</span>
  <span m=''2257810''>these</span> <span m=''2258100''>more</span> <span m=''2258300''>general</span>
  <span m=''2258690''>trellises,</span> <span m=''2259820''>down</span> <span m=''2260050''>here</span>
  <span m=''2260230''>we</span> <span m=''2260410''>can have</span> <span m=''2260560''>starting</span>
  <span m=''2261030''>and</span> <span m=''2261150''>ending</span> <span m=''2261490''>at</span>
  <span m=''2261590''>the</span> <span m=''2261680''>same</span> <span m=''2262000''>time.</span>
  <span m=''2263170''>And</span> <span m=''2263360''>in</span> <span m=''2263460''>that</span>
  <span m=''2263730''>case,</span> <span m=''2264120''>we</span> <span m=''2264260''>get</span>
  <span m=''2264390''>a</span> <span m=''2264830''>cross.</span> <span m=''2266460''>We</span>
  <span m=''2266740''>get</span> <span m=''2266900''>a</span> <span m=''2266950''>starting</span>
  <span m=''2267390''>and</span> <span m=''2267470''>ending</span> <span m=''2267780''>at</span>
  <span m=''2267890''>the</span> <span m=''2267970''>same</span> <span m=''2268290''>time,</span>
  <span m=''2269520''>we</span> <span m=''2269650''>get</span> <span m=''2270400''>something</span>
  <span m=''2270820''>that looks</span> <span m=''2271080''>like</span> <span m=''2271310''>this.</span>
  <span m=''2275630''>And</span> <span m=''2276100''>if</span> <span m=''2276270''>we</span>
  <span m=''2276400''>get</span> <span m=''2276670''>neither</span> <span m=''2277040''>starting</span>
  <span m=''2277510''>nor</span> <span m=''2277670''>ending,</span> <span m=''2279620''>empty,</span>
  <span m=''2281136''>then</span> <span m=''2281600''>nothing</span> <span m=''2281960''>happens.</span>
  <span m=''2282510''>We</span> <span m=''2282640''>just</span> <span m=''2282880''>get
  --</span> <span m=''2283980''>the</span> <span m=''2284130''>trellis</span> <span
  m=''2284430''>segment</span> <span m=''2284790''>looks</span> <span m=''2285030''>like</span>
  <span m=''2285240''>that,</span> <span m=''2285630''>like</span> <span m=''2285850''>this</span>
  <span m=''2286080''>one</span> <span m=''2286240''>here.</span> <span m=''2289900''>In</span>
  <span m=''2289950''>this</span> <span m=''2290160''>case</span> <span m=''2290500''>we</span>
  <span m=''2290600''>have</span> <span m=''2290690''>a</span> <span m=''2290780''>starting</span>
  <span m=''2291230''>time,</span> <span m=''2291535''>an</span> <span m=''2291840''>ending</span>
  <span m=''2292170''>time</span> <span m=''2292560''>in</span> <span m=''2292630''>this</span>
  <span m=''2292830''>trellis.</span> </p><p><span m=''2293680''>Here</span> <span
  m=''2293890''>we</span> <span m=''2294000''>have</span> <span m=''2294110''>nothing</span>
  <span m=''2294460''>happening.</span> <span m=''2294970''>Here</span> <span m=''2295170''>we</span>
  <span m=''2295270''>have</span> <span m=''2295430''>nothing</span> <span m=''2295830''>happening.</span>
  <span m=''2296850''>So</span> <span m=''2297030''>you</span> <span m=''2297180''>just</span>
  <span m=''2297420''>get</span> <span m=''2297960''>an</span> <span m=''2298070''>extension,</span>
  <span m=''2298420''>a</span> <span m=''2298770''>parallel</span> <span m=''2299180''>extension</span>
  <span m=''2299740''>where</span> <span m=''2299850''>nothing</span> <span m=''2300140''>happens.</span>
  <span m=''2301850''>So</span> <span m=''2302000''>again,</span> <span m=''2302260''>the</span>
  <span m=''2302340''>starting</span> <span m=''2302770''>and</span> <span m=''2302820''>ending</span>
  <span m=''2303100''>times</span> <span m=''2305250''>tell</span> <span m=''2305480''>you</span>
  <span m=''2305660''>what</span> <span m=''2307210''>happens</span> <span m=''2307590''>in</span>
  <span m=''2307680''>the</span> <span m=''2307770''>trellis.</span> </p><p><span
  m=''2323410''>There''s</span> <span m=''2323610''>one</span> <span m=''2323930''>other</span>
  <span m=''2324260''>thing</span> <span m=''2324630''>that</span> <span m=''2324760''>you</span>
  <span m=''2324970''>can</span> <span m=''2326400''>read</span> <span m=''2326900''>from</span>
  <span m=''2327080''>the</span> <span m=''2327200''>trellis,</span> <span m=''2329490''>which</span>
  <span m=''2329840''>is</span> <span m=''2330000''>the</span> <span m=''2330080''>size</span>
  <span m=''2330690''>of</span> <span m=''2330860''>branch</span> <span m=''2331270''>spaces.</span>
  <span m=''2335170''>And</span> <span m=''2337420''>since</span> <span m=''2337820''>as</span>
  <span m=''2337920''>usual</span> <span m=''2338350''>I''m</span> <span m=''2338660''>running
  a</span> <span m=''2338800''>little</span> <span m=''2339020''>later than</span>
  <span m=''2340650''>I</span> <span m=''2340830''>intend</span> <span m=''2341240''>to
  --</span> <span m=''2342300''>let</span> <span m=''2342440''>me</span> <span m=''2342580''>just</span>
  <span m=''2342820''>state</span> <span m=''2343300''>without</span> <span m=''2344430''>proof</span>
  <span m=''2344745''>that</span> <span m=''2345060''>there</span> <span m=''2345260''>is</span>
  <span m=''2347740''>a</span> <span m=''2347870''>similar</span> <span m=''2350970''>theorem</span>
  <span m=''2351520''>for</span> <span m=''2351750''>branch</span> <span m=''2352210''>spaces.</span>
  </p><p><span m=''2355960''>What</span> <span m=''2356140''>is</span> <span m=''2356310''>a</span>
  <span m=''2356360''>branch?</span> <span m=''2367660''>When</span> <span m=''2367820''>we</span>
  <span m=''2367880''>look</span> <span m=''2368040''>in</span> <span m=''2368190''>a</span>
  <span m=''2368270''>trellis,</span> <span m=''2368790''>a</span> <span m=''2368890''>branch</span>
  <span m=''2369420''>is</span> <span m=''2369600''>one</span> <span m=''2369820''>of</span>
  <span m=''2369910''>these</span> <span m=''2370280''>things.</span> <span m=''2372890''>That''s</span>
  <span m=''2373170''>a</span> <span m=''2373220''>branch.</span> <span m=''2375520''>What
  do</span> <span m=''2375700''>we</span> <span m=''2375820''>need</span> <span m=''2376040''>to</span>
  <span m=''2376150''>define</span> <span m=''2376650''>a</span> <span m=''2376700''>branch?</span>
  <span m=''2378940''>We</span> <span m=''2379150''>have</span> <span m=''2379630''>a</span>
  <span m=''2380740''>initial</span> <span m=''2381080''>state,</span> <span m=''2383090''>the</span>
  <span m=''2384190''>code</span> <span m=''2384580''>output</span> <span m=''2385190''>at</span>
  <span m=''2385400''>time</span> <span m=''2385710''>k.</span> <span m=''2386840''>We''re</span>
  <span m=''2387100''>calling</span> <span m=''2387360''>that</span> <span m=''2387660''>y</span>
  <span m=''2388300''>time</span> <span m=''2388660''>k</span> <span m=''2389740''>in</span>
  <span m=''2389900''>the</span> <span m=''2390000''>next</span> <span m=''2390350''>state.</span>
  <span m=''2392290''>So</span> <span m=''2392560''>it''s</span> <span m=''2392740''>that</span>
  <span m=''2393050''>triple.</span> <span m=''2394570''>Again,</span> <span m=''2394850''>this</span>
  <span m=''2395030''>is</span> <span m=''2395160''>linear</span> <span m=''2395780''>system</span>
  <span m=''2396140''>theory.</span> <span m=''2397120''>State,</span> <span m=''2397880''>output,</span>
  <span m=''2398460''>next</span> <span m=''2398710''>state.</span> <span m=''2400600''>Those</span>
  <span m=''2400890''>are</span> <span m=''2400930''>the</span> <span m=''2401040''>three</span>
  <span m=''2401310''>things</span> <span m=''2401820''>that</span> <span m=''2402150''>define</span>
  <span m=''2402600''>a</span> <span m=''2402680''>branch.</span> </p><p><span m=''2405730''>This</span>
  <span m=''2405970''>branch</span> <span m=''2406470''>is</span> <span m=''2406740''>state</span>
  <span m=''2407180''>1</span> <span m=''2407460''>0.</span> <span m=''2408260''>Output</span>
  <span m=''2408810''>whatever</span> <span m=''2409200''>it</span> <span m=''2409550''>is,</span>
  <span m=''2410540''>y</span> <span m=''2411090''>k,</span> <span m=''2412210''>and</span>
  <span m=''2412670''>next</span> <span m=''2413010''>state</span> <span m=''2413230''>1</span>
  <span m=''2413440''>0</span> <span m=''2413720''>0.</span> <span m=''2414810''>And</span>
  <span m=''2414940''>that</span> <span m=''2415160''>differentiates</span> <span
  m=''2415930''>it</span> <span m=''2416090''>from</span> <span m=''2416530''>this</span>
  <span m=''2416690''>down</span> <span m=''2417130''>here.</span> <span m=''2420280''>If</span>
  <span m=''2420430''>we</span> <span m=''2420550''>define</span> <span m=''2420990''>the</span>
  <span m=''2421070''>branch</span> <span m=''2421540''>as</span> <span m=''2421790''>this</span>
  <span m=''2422020''>triple,</span> <span m=''2424120''>then</span> <span m=''2424330''>we</span>
  <span m=''2424460''>can</span> <span m=''2424600''>add</span> <span m=''2425180''>triples.</span>
  <span m=''2426610''>States</span> <span m=''2427100''>form</span> <span m=''2427340''>a</span>
  <span m=''2427530''>vector</span> <span m=''2427950''>space</span> <span m=''2428430''>over</span>
  <span m=''2428680''>the</span> <span m=''2429290''>ground</span> <span m=''2429735''>field.</span>
  <span m=''2431010''>These</span> <span m=''2431660''>are</span> <span m=''2431900''>simply</span>
  <span m=''2432330''>symbols</span> <span m=''2432890''>over</span> <span m=''2433040''>the</span>
  <span m=''2433160''>ground</span> <span m=''2433470''>field.</span> <span m=''2434500''>These</span>
  <span m=''2434810''>are</span> <span m=''2436160''>vectors</span> <span m=''2437300''>over</span>
  <span m=''2437420''>the</span> <span m=''2437540''>ground</span> <span m=''2437860''>field.</span>
  <span m=''2438190''>So</span> <span m=''2438300''>we</span> <span m=''2438400''>can</span>
  <span m=''2438520''>add</span> <span m=''2438740''>them.</span> </p><p><span m=''2440360''>And</span>
  <span m=''2440530''>we</span> <span m=''2440670''>find</span> <span m=''2441030''>that
  it''s</span> <span m=''2441400''>closed,</span> <span m=''2442090''>and</span> <span
  m=''2442480''>the</span> <span m=''2442560''>set</span> <span m=''2442820''>of</span>
  <span m=''2442920''>all</span> <span m=''2443120''>branches</span> <span m=''2451220''>is</span>
  <span m=''2451850''>a</span> <span m=''2452150''>vector</span> <span m=''2452640''>space.</span>
  <span m=''2456710''>It''s</span> <span m=''2457130''>fairly</span> <span m=''2457400''>easy</span>
  <span m=''2457730''>to</span> <span m=''2457830''>show.</span> <span m=''2460100''>Look</span>
  <span m=''2460250''>at</span> <span m=''2460350''>the</span> <span m=''2460470''>notes,</span>
  <span m=''2462280''>but</span> <span m=''2462540''>it''s basically</span> <span
  m=''2462970''>because</span> <span m=''2463370''>these</span> <span m=''2464800''>are</span>
  <span m=''2465000''>all</span> <span m=''2465210''>projected</span> <span m=''2465860''>from</span>
  <span m=''2466660''>code</span> <span m=''2466930''>words</span> <span m=''2467250''>in</span>
  <span m=''2467330''>the</span> <span m=''2467400''>first</span> <span m=''2467730''>place,</span>
  <span m=''2468180''>and</span> <span m=''2468450''>code</span> <span m=''2468690''>words</span>
  <span m=''2469800''>form</span> <span m=''2469950''>a</span> <span m=''2470100''>vector</span>
  <span m=''2470470''>space,</span> <span m=''2470950''>so</span> <span m=''2471300''>this</span>
  <span m=''2471520''>is</span> <span m=''2471650''>just</span> <span m=''2471920''>a</span>
  <span m=''2471970''>projection</span> <span m=''2472610''>of</span> <span m=''2472750''>the</span>
  <span m=''2472840''>code</span> <span m=''2473120''>words,</span> <span m=''2474700''>a</span>
  <span m=''2474770''>certain</span> <span m=''2475130''>kind</span> <span m=''2475300''>of</span>
  <span m=''2475460''>projection</span> <span m=''2476120''>onto</span> <span m=''2476400''>the</span>
  <span m=''2476470''>state</span> <span m=''2476910''>spaces</span> <span m=''2477460''>and</span>
  <span m=''2477640''>symbol</span> <span m=''2478060''>spaces</span> <span m=''2478530''>and</span>
  <span m=''2478690''>so</span> <span m=''2478840''>forth.</span> <span m=''2479425''>A</span>
  <span m=''2479720''>projection</span> <span m=''2480390''>of</span> <span m=''2480460''>a</span>
  <span m=''2480520''>vector</span> <span m=''2480870''>space</span> <span m=''2481155''>is
  a</span> <span m=''2481440''>vector</span> <span m=''2481910''>space.</span> <span
  m=''2484310''>Roughly</span> <span m=''2484670''>the</span> <span m=''2484780''>proof.</span>
  </p><p><span m=''2488400''>And</span> <span m=''2488690''>what</span> <span m=''2488910''>is</span>
  <span m=''2489180''>the</span> <span m=''2489310''>dimension</span> <span m=''2493256''>of</span>
  <span m=''2493700''>the</span> <span m=''2493800''>branch</span> <span m=''2494150''>space?</span>
  <span m=''2497860''>Again,</span> <span m=''2498360''>I''m</span> <span m=''2498490''>just</span>
  <span m=''2498700''>going</span> <span m=''2498800''>to</span> <span m=''2498840''>give</span>
  <span m=''2499030''>you</span> <span m=''2499160''>the</span> <span m=''2499250''>answer.</span>
  <span m=''2499710''>Suppose</span> <span m=''2500050''>we</span> <span m=''2500170''>have</span>
  <span m=''2500360''>a</span> <span m=''2500430''>trellis-oriented</span> <span m=''2502050''>generator</span>
  <span m=''2502530''>matrix.</span> <span m=''2505220''>Let''s</span> <span m=''2505440''>suppose</span>
  <span m=''2505780''>we</span> <span m=''2505880''>want</span> <span m=''2506030''>to</span>
  <span m=''2506170''>find</span> <span m=''2506570''>out</span> <span m=''2507000''>the</span>
  <span m=''2507120''>size</span> <span m=''2507730''>of</span> <span m=''2507870''>the</span>
  <span m=''2507970''>branch</span> <span m=''2508380''>space</span> <span m=''2508910''>at</span>
  <span m=''2509130''>this</span> <span m=''2509440''>time.</span> <span m=''2511450''>What</span>
  <span m=''2511700''>doesn''t</span> <span m=''2512070''>enter</span> <span m=''2512380''>into</span>
  <span m=''2512730''>the</span> <span m=''2513410''>branch</span> <span m=''2513730''>space?</span>
  <span m=''2514120''>What</span> <span m=''2514310''>doesn''t</span> <span m=''2514600''>make</span>
  <span m=''2514790''>a</span> <span m=''2514850''>difference</span> <span m=''2515280''>to
  the</span> <span m=''2515440''>branches?</span> </p><p><span m=''2517020''>All</span>
  <span m=''2517310''>the</span> <span m=''2517400''>pasts</span> <span m=''2518080''>that</span>
  <span m=''2518160''>arrive</span> <span m=''2518630''>at</span> <span m=''2518730''>the</span>
  <span m=''2518820''>same</span> <span m=''2519150''>state</span> <span m=''2519680''>at</span>
  <span m=''2519860''>time</span> <span m=''2520190''>k</span> <span m=''2521420''>are</span>
  <span m=''2521630''>equivalent.</span> <span m=''2523450''>So</span> <span m=''2523660''>this</span>
  <span m=''2523880''>generator</span> <span m=''2524370''>doesn''t</span> <span m=''2524690''>enter</span>
  <span m=''2524980''>in.</span> <span m=''2526980''>All</span> <span m=''2527210''>the</span>
  <span m=''2527290''>futures</span> <span m=''2528130''>that</span> <span m=''2528480''>depart</span>
  <span m=''2528860''>from</span> <span m=''2529030''>time</span> <span m=''2529400''>k</span>
  <span m=''2529600''>plus</span> <span m=''2529980''>1</span> <span m=''2531280''>don''t</span>
  <span m=''2531540''>enter</span> <span m=''2531800''>in,</span> <span m=''2532530''>so</span>
  <span m=''2532790''>anything</span> <span m=''2533180''>that''s</span> <span m=''2533380''>supported</span>
  <span m=''2533870''>by</span> <span m=''2534020''>the</span> <span m=''2534130''>future</span>
  <span m=''2534610''>at</span> <span m=''2534760''>time</span> <span m=''2535050''>k</span>
  <span m=''2535250''>plus</span> <span m=''2535630''>1</span> <span m=''2537670''>doesn''t</span>
  <span m=''2537950''>enter</span> <span m=''2538250''>in.</span> <span m=''2540420''>And</span>
  <span m=''2540550''>what''s</span> <span m=''2540850''>left</span> <span m=''2541320''>is</span>
  <span m=''2541830''>all</span> <span m=''2542100''>of</span> <span m=''2542210''>the</span>
  <span m=''2542310''>generators</span> <span m=''2543060''>that</span> <span m=''2543190''>are</span>
  <span m=''2543350''>active</span> <span m=''2543920''>at</span> <span m=''2544120''>symbol</span>
  <span m=''2544580''>time</span> <span m=''2547440''>k.</span> <span m=''2547710''>Notice</span>
  <span m=''2548000''>the</span> <span m=''2548090''>symbol</span> <span m=''2548460''>times</span>
  <span m=''2548940''>occur</span> <span m=''2549320''>between</span> <span m=''2549740''>the</span>
  <span m=''2549830''>state</span> <span m=''2550240''>times.</span> </p><p><span
  m=''2551580''>So</span> <span m=''2558110''>certainly</span> <span m=''2559070''>this</span>
  <span m=''2559360''>is</span> <span m=''2559510''>an</span> <span m=''2559640''>easy
  --</span> <span m=''2562600''>this</span> <span m=''2562820''>is</span> <span m=''2562920''>one</span>
  <span m=''2563090''>of</span> <span m=''2563130''>those</span> <span m=''2563330''>results</span>
  <span m=''2563790''>that''s</span> <span m=''2563950''>easier</span> <span m=''2564310''>to</span>
  <span m=''2564450''>understand</span> <span m=''2565120''>than</span> <span m=''2565300''>to</span>
  <span m=''2565420''>prove,</span> <span m=''2566020''>and</span> <span m=''2566440''>I''ll</span>
  <span m=''2567940''>refer</span> <span m=''2568260''>you</span> <span m=''2568450''>to</span>
  <span m=''2568720''>the</span> <span m=''2568960''>notes</span> <span m=''2569410''>to</span>
  <span m=''2569530''>prove.</span> </p><p><span m=''2570610''>The</span> <span m=''2570710''>dimension</span>
  <span m=''2571160''>of</span> <span m=''2571210''>the</span> <span m=''2571290''>branch</span>
  <span m=''2571690''>space</span> <span m=''2572420''>is</span> <span m=''2572550''>simply</span>
  <span m=''2572890''>the</span> <span m=''2573020''>number</span> <span m=''2574342''>of</span>
  <span m=''2574690''>generators</span> <span m=''2576510''>that</span> <span m=''2576620''>are</span>
  <span m=''2576740''>active</span> <span m=''2577210''>at</span> <span m=''2577470''>symbol</span>
  <span m=''2577890''>time</span> <span m=''2578240''>k.</span> <span m=''2589971''>Because</span>
  <span m=''2590480''>branches</span> <span m=''2592200''>are</span> <span m=''2592310''>synchronized</span>
  <span m=''2592745''>with</span> <span m=''2593180''>the</span> <span m=''2593570''>symbol</span>
  <span m=''2594030''>times,</span> <span m=''2594440''>not</span> <span m=''2594650''>with
  the</span> <span m=''2594990''>state</span> <span m=''2595295''>times.</span> </p><p><span
  m=''2598190''>So</span> <span m=''2598370''>how</span> <span m=''2598510''>does</span>
  <span m=''2598680''>that</span> <span m=''2598890''>come out</span> <span m=''2599060''>over</span>
  <span m=''2599420''>here?</span> <span m=''2600450''>There''s</span> <span m=''2601170''>the</span>
  <span m=''2601320''>dimension</span> <span m=''2601730''>of</span> <span m=''2601770''>the</span>
  <span m=''2601840''>branch</span> <span m=''2602190''>space</span> <span m=''2602450''>is</span>
  <span m=''2602710''>1</span> <span m=''2603120''>here.</span> <span m=''2604140''>It''s</span>
  <span m=''2604410''>2</span> <span m=''2604840''>here.</span> <span m=''2606000''>It''s</span>
  <span m=''2606310''>3</span> <span m=''2606710''>here.</span> <span m=''2607930''>It''s</span>
  <span m=''2608480''>4</span> <span m=''2608890''>here.</span> <span m=''2609810''>I''m</span>
  <span m=''2609930''>sorry,</span> <span m=''2610390''>it''s 3</span> <span m=''2610620''>again</span>
  <span m=''2610920''>here.</span> <span m=''2612340''>This</span> <span m=''2612530''>one</span>
  <span m=''2612590''>hasn''t</span> <span m=''2612940''>started</span> <span m=''2613320''>yet.</span>
  <span m=''2614180''>It''s</span> <span m=''2614460''>3</span> <span m=''2614740''>again</span>
  <span m=''2615080''>here.</span> <span m=''2617390''>It''s</span> <span m=''2620670''>3</span>
  <span m=''2621260''>again</span> <span m=''2621600''>here,</span> <span m=''2622180''>2</span>
  <span m=''2622470''>here,</span> <span m=''2622910''>1</span> <span m=''2623130''>here.</span>
  <span m=''2625010''>That</span> <span m=''2625040''>means</span> <span m=''2625320''>that</span>
  <span m=''2625640''>the</span> <span m=''2625940''>size</span> <span m=''2626530''>of</span>
  <span m=''2626610''>the</span> <span m=''2626710''>branch</span> <span m=''2627160''>space</span>
  <span m=''2628280''>is</span> <span m=''2629220''>2,</span> <span m=''2629900''>4,</span>
  <span m=''2630520''>8,</span> <span m=''2630910''>8,</span> <span m=''2631320''>8,</span>
  <span m=''2631660''>8,</span> <span m=''2633350''>4,</span> <span m=''2634080''>2.</span>
  <span m=''2635685''>Is</span> <span m=''2636090''>that</span> <span m=''2636280''>right?</span>
  <span m=''2638290''>There</span> <span m=''2638410''>are</span> <span m=''2638480''>two</span>
  <span m=''2638660''>branches</span> <span m=''2639220''>here.</span> <span m=''2639530''>There
  are four</span> <span m=''2640000''>branches</span> <span m=''2640580''>here.</span>
  <span m=''2640880''>There are</span> <span m=''2641160''>eight</span> <span m=''2641300''>branches</span>
  <span m=''2641950''>here.</span> <span m=''2642240''>There</span> <span m=''2642430''>are</span>
  <span m=''2642480''>still</span> <span m=''2642880''>eight</span> <span m=''2643000''>branches</span>
  <span m=''2643580''>here.</span> <span m=''2644230''>And it''s</span> <span m=''2644470''>symmetric</span>
  <span m=''2645080''>on</span> <span m=''2645170''>the</span> <span m=''2645340''>other</span>
  <span m=''2645500''>side.</span> <span m=''2645930''>So</span> <span m=''2646240''>it</span>
  <span m=''2646550''>looks</span> <span m=''2646760''>like</span> <span m=''2646930''>we</span>
  <span m=''2647020''>got</span> <span m=''2647250''>the</span> <span m=''2647340''>right</span>
  <span m=''2647550''>answer</span> <span m=''2647920''>there,</span> <span m=''2649040''>and</span>
  <span m=''2650240''>in</span> <span m=''2650400''>fact</span> <span m=''2651010''>it''s</span>
  <span m=''2651260''>a</span> <span m=''2651320''>general</span> <span m=''2651710''>rule.</span>
  </p><p><span m=''2653740''>So</span> <span m=''2653920''>that''s</span> <span m=''2654190''>great.</span>
  <span m=''2654510''>That''s</span> <span m=''2654740''>another</span> <span m=''2655040''>property</span>
  <span m=''2655480''>of</span> <span m=''2655540''>trellis-oriented</span> <span
  m=''2656270''>generator</span> <span m=''2656760''>matrix.</span> <span m=''2657270''>We</span>
  <span m=''2657410''>can</span> <span m=''2657550''>again,</span> <span m=''2657860''>by</span>
  <span m=''2658100''>inspection,</span> <span m=''2658750''>get</span> <span m=''2659040''>the</span>
  <span m=''2659210''>dimensions</span> <span m=''2659690''>of</span> <span m=''2659790''>all</span>
  <span m=''2660000''>the</span> <span m=''2660070''>branch</span> <span m=''2660410''>space</span>
  <span m=''2660660''>sizes.</span> <span m=''2662480''>Are</span> <span m=''2662640''>the</span>
  <span m=''2662740''>branch</span> <span m=''2663390''>sizes</span> <span m=''2663930''>important?</span>
  <span m=''2665990''>Yes.</span> <span m=''2668490''>In</span> <span m=''2668940''>fact,</span>
  <span m=''2669320''>they''re</span> <span m=''2669470''>more</span> <span m=''2669790''>important</span>
  <span m=''2670540''>from</span> <span m=''2670780''>a</span> <span m=''2670860''>complexity</span>
  <span m=''2671520''>point</span> <span m=''2671820''>of</span> <span m=''2671890''>view</span>
  <span m=''2672290''>than</span> <span m=''2672420''>the</span> <span m=''2672490''>state</span>
  <span m=''2672890''>space</span> <span m=''2673070''>sizes.</span> <span m=''2674920''>95%</span>
  <span m=''2675680''>of</span> <span m=''2675830''>the</span> <span m=''2675940''>literature</span>
  <span m=''2676500''>has to</span> <span m=''2676730''>do with</span> <span m=''2676900''>state</span>
  <span m=''2677380''>spaces.</span> <span m=''2678020''>State</span> <span m=''2678430''>space</span>
  <span m=''2678920''>is</span> <span m=''2679370''>a</span> <span m=''2679680''>little</span>
  <span m=''2679940''>bit</span> <span m=''2680150''>more</span> <span m=''2680490''>elegant</span>
  <span m=''2680980''>mathematically.</span> <span m=''2684010''>For instance,</span>
  <span m=''2684460''>you</span> <span m=''2684540''>don''t</span> <span m=''2684740''>have</span>
  <span m=''2685340''>the</span> <span m=''2685460''>same</span> <span m=''2685750''>kind</span>
  <span m=''2685880''>of</span> <span m=''2686010''>dual</span> <span m=''2686300''>branch</span>
  <span m=''2686610''>space</span> <span m=''2687020''>theorem</span> <span m=''2687430''>as
  you</span> <span m=''2687540''>have</span> <span m=''2687640''>a</span> <span m=''2687690''>dual</span>
  <span m=''2688570''>state</span> <span m=''2688980''>space</span> <span m=''2689280''>theorem.</span>
  </p><p><span m=''2690950''>But</span> <span m=''2691120''>actually,</span> <span
  m=''2691570''>when</span> <span m=''2691760''>you''re</span> <span m=''2692640''>asking</span>
  <span m=''2693180''>what''s</span> <span m=''2693440''>going</span> <span m=''2693720''>on</span>
  <span m=''2693920''>in</span> <span m=''2694020''>the</span> <span m=''2694110''>Viterbi</span>
  <span m=''2694490''>algorithm,</span> <span m=''2695190''>what</span> <span m=''2695380''>does</span>
  <span m=''2695500''>the</span> <span m=''2695710''>Viterbi</span> <span m=''2695880''>algorithm</span>
  <span m=''2696400''>have</span> <span m=''2696640''>to</span> <span m=''2696760''>do?</span>
  <span m=''2697680''>At a</span> <span m=''2697840''>minimum,</span> <span m=''2698300''>it
  has</span> <span m=''2698570''>to</span> <span m=''2698630''>do</span> <span m=''2698770''>one</span>
  <span m=''2699070''>thing</span> <span m=''2699370''>for</span> <span m=''2699520''>each</span>
  <span m=''2699780''>branch.</span> <span m=''2701070''>It</span> <span m=''2701160''>has</span>
  <span m=''2701380''>to</span> <span m=''2701480''>perform</span> <span m=''2701960''>a</span>
  <span m=''2701990''>metric</span> <span m=''2702670''>extension,</span> <span m=''2703340''>a</span>
  <span m=''2703410''>metric</span> <span m=''2703900''>addition</span> <span m=''2704490''>computation</span>
  <span m=''2705630''>at</span> <span m=''2705740''>least</span> <span m=''2706030''>once</span>
  <span m=''2706290''>for</span> <span m=''2706440''>each</span> <span m=''2706650''>branch.</span>
  <span m=''2707150''>So</span> <span m=''2707270''>the</span> <span m=''2707470''>Viterbi</span>
  <span m=''2707660''>algorithm</span> <span m=''2708240''>complexity</span> <span
  m=''2710680''>is</span> <span m=''2710890''>better</span> <span m=''2711240''>estimated</span>
  <span m=''2711980''>by</span> <span m=''2712210''>the</span> <span m=''2712320''>size</span>
  <span m=''2712930''>of</span> <span m=''2713110''>the</span> <span m=''2713280''>branch</span>
  <span m=''2714310''>space</span> <span m=''2715010''>than</span> <span m=''2715150''>the</span>
  <span m=''2715250''>size</span> <span m=''2715730''>of</span> <span m=''2715850''>the</span>
  <span m=''2715910''>state</span> <span m=''2716310''>space.</span> </p><p><span
  m=''2718860''>To</span> <span m=''2719010''>progress</span> <span m=''2719730''>at</span>
  <span m=''2719850''>this</span> <span m=''2720080''>point,</span> <span m=''2720350''>a</span>
  <span m=''2720420''>Viterbi</span> <span m=''2720860''>algorithm</span> <span m=''2720990''>has
  to</span> <span m=''2721470''>do</span> <span m=''2721640''>at  least</span> <span
  m=''2721800''>eight</span> <span m=''2722210''>things.</span> <span m=''2722690''>To</span>
  <span m=''2723130''>progress</span> <span m=''2723850''>again,</span> <span m=''2724240''>it
  has to</span> <span m=''2724440''>do</span> <span m=''2724590''>at least</span>
  <span m=''2724740''>eight</span> <span m=''2725150''>things.</span> <span m=''2729050''>So</span>
  <span m=''2730070''>it''s</span> <span m=''2730500''>more</span> <span m=''2730810''>relevant</span>
  <span m=''2731240''>from</span> <span m=''2731330''>the</span> <span m=''2731420''>point</span>
  <span m=''2731660''>of</span> <span m=''2731730''>view of</span> <span m=''2731990''>complexity.</span>
  <span m=''2733570''>Furthermore,</span> <span m=''2734220''>you</span> <span m=''2734350''>can</span>
  <span m=''2734480''>play</span> <span m=''2734690''>games</span> <span m=''2735190''>with</span>
  <span m=''2735360''>state</span> <span m=''2735670''>space</span> <span m=''2736060''>size.</span>
  <span m=''2737440''>And</span> <span m=''2737600''>you''ve</span> <span m=''2737730''>seen</span>
  <span m=''2738940''>me</span> <span m=''2739100''>play</span> <span m=''2739360''>games</span>
  <span m=''2739780''>with</span> <span m=''2739900''>state</span> <span m=''2740270''>space</span>
  <span m=''2740440''>size.</span> </p><p><span m=''2740920''>For</span> <span m=''2741070''>instance,</span>
  <span m=''2741370''>if</span> <span m=''2741520''>I</span> <span m=''2741610''>draw</span>
  <span m=''2741870''>this</span> <span m=''2742150''>as</span> <span m=''2742260''>a</span>
  <span m=''2742360''>two-section</span> <span m=''2743090''>trellis --</span> <span
  m=''2746560''>the</span> <span m=''2746670''>first</span> <span m=''2747150''>picture</span>
  <span m=''2747560''>I</span> <span m=''2747620''>put</span> <span m=''2747880''>up</span>
  <span m=''2748220''>was</span> <span m=''2748440''>only</span> <span m=''2748670''>a</span>
  <span m=''2748730''>four-state</span> <span m=''2749440''>trellis,</span> <span
  m=''2749750''>and</span> <span m=''2749950''>it</span> <span m=''2750160''>looked</span>
  <span m=''2750390''>like</span> <span m=''2750700''>this.</span> <span m=''2753750''>I</span>
  <span m=''2753790''>went</span> <span m=''2753990''>immediately</span> <span m=''2754530''>to</span>
  <span m=''2754650''>time</span> <span m=''2755020''>2,</span> <span m=''2755460''>and
  I</span> <span m=''2755630''>aggregated</span> <span m=''2756380''>these</span>
  <span m=''2756610''>two</span> <span m=''2756810''>things.</span> <span m=''2757890''>0,</span>
  <span m=''2758200''>0</span> <span m=''2758810''>and</span> <span m=''2759120''>1,</span>
  <span m=''2759380''>1</span> <span m=''2760330''>were</span> <span m=''2760500''>up</span>
  <span m=''2760680''>here,</span> <span m=''2761040''>and</span> <span m=''2761180''>0,</span>
  <span m=''2761490''>1</span> <span m=''2761940''>and 1,</span> <span m=''2762210''>0</span>
  <span m=''2762520''>were</span> <span m=''2762640''>down</span> <span m=''2762940''>here.</span>
  <span m=''2763890''>And</span> <span m=''2764000''>then</span> <span m=''2764160''>I</span>
  <span m=''2764260''>had</span> <span m=''2764460''>a</span> <span m=''2764550''>nice
  --</span> <span m=''2765200''>I</span> <span m=''2765540''>just</span> <span m=''2765840''>drew</span>
  <span m=''2766060''>these</span> <span m=''2766350''>four</span> <span m=''2766640''>states</span>
  <span m=''2767160''>over</span> <span m=''2767420''>here.</span> <span m=''2768510''>And</span>
  <span m=''2768650''>if</span> <span m=''2768800''>I</span> <span m=''2768870''>do
  it</span> <span m=''2769020''>like</span> <span m=''2769370''>that,</span> <span
  m=''2769690''>then</span> <span m=''2769820''>I</span> <span m=''2769890''>get</span>
  <span m=''2770140''>a</span> <span m=''2771150''>much</span> <span m=''2771430''>nicer</span>
  <span m=''2771810''>picture.</span> <span m=''2772080''>It</span> <span m=''2772350''>looks</span>
  <span m=''2772640''>like</span> <span m=''2772890''>this.</span> <span m=''2778700''>It</span>
  <span m=''2779130''>looks</span> <span m=''2779570''>only</span> <span m=''2779790''>like</span>
  <span m=''2780000''>a</span> <span m=''2780060''>four-state</span> <span m=''2780670''>trellis.</span>
  </p><p><span m=''2782485''>Now,</span> <span m=''2782910''>is</span> <span m=''2783160''>this</span>
  <span m=''2783220''>still a</span> <span m=''2783550''>legitimate</span> <span m=''2784040''>trellis?</span>
  <span m=''2784730''>Yeah,</span> <span m=''2785000''>it''s still a</span> <span
  m=''2785290''>legitimate</span> <span m=''2785810''>trellis.</span> <span m=''2788270''>If</span>
  <span m=''2788480''>I</span> <span m=''2788820''>do</span> <span m=''2788970''>a</span>
  <span m=''2789070''>Viterbi</span> <span m=''2789520''>algorithm</span> <span m=''2789920''>decoding</span>
  <span m=''2790370''>of</span> <span m=''2790510''>this</span> <span m=''2790650''>trellis,</span>
  <span m=''2791100''>is</span> <span m=''2791240''>it</span> <span m=''2791320''>any</span>
  <span m=''2791540''>different</span> <span m=''2792330''>from</span> <span m=''2792850''>this?</span>
  <span m=''2793420''>Well,</span> <span m=''2793730''>in</span> <span m=''2793850''>detail</span>
  <span m=''2794115''>it</span> <span m=''2794380''>is</span> <span m=''2794550''>a</span>
  <span m=''2794600''>little</span> <span m=''2794790''>bit</span> <span m=''2794970''>different.</span>
  <span m=''2795330''>You</span> <span m=''2795460''>do</span> <span m=''2796130''>the</span>
  <span m=''2796260''>additions</span> <span m=''2796820''>and</span> <span m=''2796900''>the</span>
  <span m=''2796980''>comparisons</span> <span m=''2797970''>and</span> <span m=''2798050''>the</span>
  <span m=''2798130''>selection.</span> <span m=''2798420''>So</span> <span m=''2798710''>you</span>
  <span m=''2798940''>only</span> <span m=''2799130''>do</span> <span m=''2799270''>selections</span>
  <span m=''2801760''>every</span> <span m=''2802020''>this</span> <span m=''2802310''>often.</span>
  <span m=''2806000''>And</span> <span m=''2806230''>if</span> <span m=''2806330''>you</span>
  <span m=''2806420''>think</span> <span m=''2806660''>about it,</span> <span m=''2806940''>it''s</span>
  <span m=''2807170''>really</span> <span m=''2807440''>legitimate</span> <span m=''2808550''>to</span>
  <span m=''2808730''>think</span> <span m=''2809000''>of</span> <span m=''2809100''>this
  --</span> <span m=''2809970''>if</span> <span m=''2810030''>you</span> <span m=''2810150''>think</span>
  <span m=''2810470''>exactly</span> <span m=''2811100''>how</span> <span m=''2811270''>the</span>
  <span m=''2811470''>Viterbi</span> <span m=''2812090''>algorithm</span> <span m=''2812250''>works,</span>
  <span m=''2813480''>really</span> <span m=''2813710''>what''s</span> <span m=''2813890''>it</span>
  <span m=''2814030''>doing?</span> <span m=''2814290''>It''s</span> <span m=''2814470''>not</span>
  <span m=''2814610''>making</span> <span m=''2814860''>any</span> <span m=''2815030''>selection</span>
  <span m=''2815570''>here.</span> <span m=''2815870''>It''s</span> <span m=''2815980''>just</span>
  <span m=''2816220''>adding</span> <span m=''2816560''>an</span> <span m=''2816660''>increment</span>
  <span m=''2817160''>there,</span> <span m=''2817450''>and</span> <span m=''2817570''>then</span>
  <span m=''2817690''>adding</span> <span m=''2817980''>another</span> <span m=''2818330''>increment,</span>
  <span m=''2819260''>and</span> <span m=''2819380''>it''s</span> <span m=''2819560''>not</span>
  <span m=''2819750''>making</span> <span m=''2820000''>any</span> <span m=''2820180''>selection</span>
  <span m=''2820830''>until</span> <span m=''2821030''>it</span> <span m=''2821100''>gets</span>
  <span m=''2821370''>here.</span> </p><p><span m=''2822570''>So</span> <span m=''2823090''>it''s</span>
  <span m=''2823410''>perfectly</span> <span m=''2823870''>legitimate</span> <span
  m=''2824450''>to</span> <span m=''2824560''>think</span> <span m=''2824830''>of</span>
  <span m=''2825020''>this</span> <span m=''2825210''>as</span> <span m=''2825850''>basically</span>
  <span m=''2826360''>being</span> <span m=''2826720''>a</span> <span m=''2826830''>four-state</span>
  <span m=''2827460''>algorithm.</span> <span m=''2827980''>It</span> <span m=''2828070''>really</span>
  <span m=''2828880''>isn''t</span> <span m=''2829190''>doing</span> <span m=''2829430''>any</span>
  <span m=''2829600''>work</span> <span m=''2830050''>at</span> <span m=''2830290''>this</span>
  <span m=''2830510''>stage.</span> <span m=''2831470''>All</span> <span m=''2831650''>the</span>
  <span m=''2831730''>work</span> <span m=''2832070''>occurs</span> <span m=''2832550''>at</span>
  <span m=''2832650''>this</span> <span m=''2832880''>stage</span> <span m=''2834370''>if</span>
  <span m=''2834580''>you</span> <span m=''2834700''>think</span> <span m=''2834990''>about</span>
  <span m=''2835300''>the</span> <span m=''2835430''>operation</span> <span m=''2836050''>of</span>
  <span m=''2836110''>the</span> <span m=''2836230''>Viterbi</span> <span m=''2836892''>algorithm.</span>
  <span m=''2838310''>So</span> <span m=''2838500''>this</span> <span m=''2838720''>is
  a</span> <span m=''2839190''>quite</span> <span m=''2839460''>legitimate</span>
  <span m=''2840020''>representation.</span> </p><p><span m=''2841520''>And</span>
  <span m=''2841650''>so</span> <span m=''2842020''>what are we</span> <span m=''2842110''>going
  to</span> <span m=''2842210''>say?</span> <span m=''2842450''>Is</span> <span m=''2842630''>the</span>
  <span m=''2842720''>state</span> <span m=''2843020''>complexity</span> <span m=''2843820''>of</span>
  <span m=''2843990''>this</span> <span m=''2844240''>code,</span> <span m=''2844630''>is</span>
  <span m=''2844820''>it</span> <span m=''2845300''>four</span> <span m=''2845550''>states</span>
  <span m=''2845970''>or</span> <span m=''2846050''>is</span> <span m=''2846150''>it</span>
  <span m=''2846230''>eight</span> <span m=''2846440''>states?</span> <span m=''2848140''>Well,</span>
  <span m=''2848530''>to some</span> <span m=''2848710''>degree</span> <span m=''2848990''>it''s
  just a</span> <span m=''2849320''>matter of</span> <span m=''2849510''>definition.</span>
  <span m=''2852400''>How</span> <span m=''2852520''>do</span> <span m=''2852590''>you</span>
  <span m=''2852720''>choose</span> <span m=''2853070''>to</span> <span m=''2853180''>define</span>
  <span m=''2853610''>it?</span> <span m=''2854630''>If</span> <span m=''2854670''>you</span>
  <span m=''2854790''>want</span> <span m=''2854980''>something</span> <span m=''2855310''>more</span>
  <span m=''2855610''>fundamental,</span> <span m=''2858370''>it''s</span> <span m=''2858500''>better</span>
  <span m=''2858700''>to</span> <span m=''2858760''>go</span> <span m=''2858900''>to</span>
  <span m=''2858960''>branch</span> <span m=''2859350''>complexity.</span> </p><p><span
  m=''2861580''>What''s</span> <span m=''2861740''>the</span> <span m=''2861890''>branch</span>
  <span m=''2862210''>complexity</span> <span m=''2862900''>here</span> <span m=''2863290''>for</span>
  <span m=''2863450''>the</span> <span m=''2863590''>fully</span> <span m=''2863920''>displayed</span>
  <span m=''2864500''>trellis?</span> <span m=''2865385''>It''s</span> <span m=''2865640''>eight.</span>
  <span m=''2867070''>By</span> <span m=''2867390''>branch</span> <span m=''2867910''>complexity,</span>
  <span m=''2868480''>I</span> <span m=''2868510''>mean</span> <span m=''2868700''>the</span>
  <span m=''2868800''>maximum</span> <span m=''2869680''>size</span> <span m=''2870230''>of</span>
  <span m=''2870350''>any</span> <span m=''2870530''>branch</span> <span m=''2870890''>space.</span>
  <span m=''2872530''>What''s</span> <span m=''2872730''>the</span> <span m=''2872810''>branch</span>
  <span m=''2873250''>complexity</span> <span m=''2873900''>here?</span> <span m=''2876580''>It''s</span>
  <span m=''2876730''>eight.</span> <span m=''2877215''>We''ve</span> <span m=''2877510''>still</span>
  <span m=''2877750''>got</span> <span m=''2877940''>eight.</span> <span m=''2879010''>Ultimately</span>
  <span m=''2879490''>we''ve</span> <span m=''2879700''>got</span> <span m=''2879840''>to</span>
  <span m=''2880490''>compare</span> <span m=''2880850''>these</span> <span m=''2881070''>eight</span>
  <span m=''2881290''>things</span> <span m=''2881650''>and</span> <span m=''2881790''>reduce
  them to</span> <span m=''2882070''>four,</span> <span m=''2883080''>whether</span>
  <span m=''2883290''>we</span> <span m=''2883400''>do</span> <span m=''2883580''>it</span>
  <span m=''2883730''>here</span> <span m=''2884420''>or</span> <span m=''2884540''>here.</span>
  </p><p><span m=''2886280''>I</span> <span m=''2887220''>gave</span> <span m=''2887470''>you</span>
  <span m=''2887610''>another</span> <span m=''2887970''>trellis</span> <span m=''2888680''>which</span>
  <span m=''2889030''>was</span> <span m=''2889930''>only</span> <span m=''2890220''>a</span>
  <span m=''2890290''>two-section</span> <span m=''2891020''>trellis,</span> <span
  m=''2895310''>where</span> <span m=''2895620''>I</span> <span m=''2895690''>just</span>
  <span m=''2895920''>showed</span> <span m=''2896330''>the</span> <span m=''2896410''>four</span>
  <span m=''2896750''>central</span> <span m=''2897180''>states.</span> <span m=''2898480''>And</span>
  <span m=''2898560''>we</span> <span m=''2898670''>actually</span> <span m=''2899040''>have</span>
  <span m=''2899220''>two</span> <span m=''2899440''>branches</span> <span m=''2900220''>going</span>
  <span m=''2900500''>there,</span> <span m=''2900940''>two</span> <span m=''2901120''>branches</span>
  <span m=''2901680''>going</span> <span m=''2901960''>there,</span> <span m=''2902920''>two</span>
  <span m=''2903080''>branches</span> <span m=''2903610''>going</span> <span m=''2903850''>there,</span>
  <span m=''2904050''>and</span> <span m=''2904120''>two</span> <span m=''2904300''>branches</span>
  <span m=''2904830''>going</span> <span m=''2905090''>there.</span> <span m=''2905830''>What''s</span>
  <span m=''2905980''>the</span> <span m=''2906070''>branch</span> <span m=''2906390''>complexity</span>
  <span m=''2906695''>of</span> <span m=''2907000''>that</span> <span m=''2907300''>trellis?</span>
  <span m=''2908630''>Still</span> <span m=''2908920''>eight.</span> <span m=''2909755''>There
  are</span> <span m=''2910220''>eight</span> <span m=''2910570''>ways</span> <span
  m=''2910960''>to</span> <span m=''2911060''>get</span> <span m=''2911370''>from
  the</span> <span m=''2911550''>origin</span> <span m=''2911865''>to</span> <span
  m=''2912180''>here.</span> </p><p><span m=''2916800''>If</span> <span m=''2917000''>you</span>
  <span m=''2917230''>go</span> <span m=''2917480''>back</span> <span m=''2917990''>to</span>
  <span m=''2918440''>how</span> <span m=''2918660''>we</span> <span m=''2919760''>do</span>
  <span m=''2919850''>this</span> <span m=''2920120''>theorem,</span> <span m=''2920510''>if</span>
  <span m=''2920610''>you</span> <span m=''2920730''>believe</span> <span m=''2921110''>this</span>
  <span m=''2921360''>theorem,</span> <span m=''2923360''>what</span> <span m=''2923510''>happens</span>
  <span m=''2924100''>now</span> <span m=''2924570''>if</span> <span m=''2925820''>we</span>
  <span m=''2926270''>say</span> <span m=''2926740''>arbitrarily,</span> <span m=''2927510''>OK,</span>
  <span m=''2927860''>we''re</span> <span m=''2928010''>going</span> <span m=''2928120''>to</span>
  <span m=''2928190''>define</span> <span m=''2928610''>the</span> <span m=''2928690''>state</span>
  <span m=''2929020''>spaces</span> <span m=''2929560''>as</span> <span m=''2929710''>we</span>
  <span m=''2929850''>do</span> <span m=''2930150''>in</span> <span m=''2930200''>a</span>
  <span m=''2930260''>rate</span> <span m=''2930490''>1/2</span> <span m=''2931630''>convolutional</span>
  <span m=''2932220''>code.</span> <span m=''2932520''>We''re</span> <span m=''2932650''>just</span>
  <span m=''2932890''>going</span> <span m=''2933010''>to</span> <span m=''2933070''>define</span>
  <span m=''2933540''>the</span> <span m=''2933630''>state</span> <span m=''2934050''>times</span>
  <span m=''2934510''>to</span> <span m=''2934610''>be</span> <span m=''2934780''>every</span>
  <span m=''2935100''>two</span> <span m=''2935300''>times.</span> <span m=''2940980''>Then</span>
  <span m=''2941150''>the</span> <span m=''2941250''>dimension</span> <span m=''2941720''>of</span>
  <span m=''2941800''>the</span> <span m=''2941870''>state</span> <span m=''2942270''>spaces,</span>
  <span m=''2944450''>just</span> <span m=''2944670''>at those</span> <span m=''2945070''>times</span>
  <span m=''2945440''>we''ve</span> <span m=''2945650''>defined,</span> <span m=''2946340''>is</span>
  <span m=''2946680''>0,</span> <span m=''2947260''>2,</span> <span m=''2947960''>2,</span>
  <span m=''2948420''>2,</span> <span m=''2948710''>0.</span> <span m=''2949100''>They</span>
  <span m=''2949210''>don''t</span> <span m=''2949420''>change.</span> <span m=''2950370''>We</span>
  <span m=''2950700''>just</span> <span m=''2950900''>have</span> <span m=''2951030''>fewer</span>
  <span m=''2951330''>of</span> <span m=''2951560''>them</span> <span m=''2953560''>by</span>
  <span m=''2953710''>our</span> <span m=''2953880''>choice.</span> </p><p><span m=''2955120''>What</span>
  <span m=''2955420''>happens</span> <span m=''2955780''>to</span> <span m=''2955930''>the</span>
  <span m=''2956050''>dimensions</span> <span m=''2956305''>of</span> <span m=''2956560''>the</span>
  <span m=''2956660''>branch</span> <span m=''2957050''>spaces?</span> <span m=''2957610''>Again,</span>
  <span m=''2957910''>if the</span> <span m=''2958010''>theorem</span> <span m=''2958970''>is</span>
  <span m=''2959150''>correct,</span> <span m=''2960510''>we</span> <span m=''2960630''>should</span>
  <span m=''2960800''>just</span> <span m=''2961020''>count</span> <span m=''2961340''>the</span>
  <span m=''2961430''>number</span> <span m=''2961720''>of</span> <span m=''2961820''>active</span>
  <span m=''2962290''>generators</span> <span m=''2963820''>at</span> <span m=''2964030''>each</span>
  <span m=''2964430''>now of</span> <span m=''2964830''>these</span> <span m=''2965100''>four</span>
  <span m=''2966670''>bi-symbol</span> <span m=''2967410''>times.</span> <span m=''2968580''>So</span>
  <span m=''2968930''>it''s</span> <span m=''2969490''>2,</span> <span m=''2970530''>3,</span>
  <span m=''2971710''>3,</span> <span m=''2972670''>2.</span> <span m=''2974720''>Is</span>
  <span m=''2974890''>that</span> <span m=''2975060''>right?</span> <span m=''2975450''>That</span>
  <span m=''2975670''>is</span> <span m=''2975900''>the</span> <span m=''2976000''>branch</span>
  <span m=''2976350''>complexity</span> <span m=''2977000''>of</span> <span m=''2977110''>this</span>
  <span m=''2977180''>trellis</span> <span m=''2977840''>down</span> <span m=''2978100''>here.</span>
  <span m=''2979920''>It''s</span> <span m=''2980240''>4</span> <span m=''2980880''>in</span>
  <span m=''2981040''>the</span> <span m=''2981110''>initial</span> <span m=''2981530''>interval,</span>
  <span m=''2981960''>and</span> <span m=''2982090''>8</span> <span m=''2982500''>over</span>
  <span m=''2982730''>here.</span> <span m=''2985070''>So</span> <span m=''2985540''>again</span>
  <span m=''2985880''>it''s</span> <span m=''2986090''>correct.</span> </p><p><span
  m=''2987380''>Suppose</span> <span m=''2987820''>we</span> <span m=''2987940''>go</span>
  <span m=''2988200''>to</span> <span m=''2988270''>that</span> <span m=''2988830''>so-called</span>
  <span m=''2989400''>two-section</span> <span m=''2990060''>trellis.</span> <span
  m=''2990480''>We</span> <span m=''2990600''>just</span> <span m=''2990830''>say</span>
  <span m=''2991130''>there''s</span> <span m=''2991310''>a</span> <span m=''2991400''>first</span>
  <span m=''2991810''>half</span> <span m=''2992790''>and</span> <span m=''2992930''>a</span>
  <span m=''2993170''>second</span> <span m=''2993400''>half.</span> <span m=''2995140''>Now</span>
  <span m=''2995360''>the</span> <span m=''2995440''>states</span> <span m=''2995980''>is</span>
  <span m=''2996090''>going</span> <span m=''2996180''>to</span> <span m=''2996260''>be</span>
  <span m=''2996340''>0</span> <span m=''2996790''>2</span> <span m=''2997460''>0,</span>
  <span m=''2998780''>and</span> <span m=''2998920''>the</span> <span m=''2998990''>branch</span>
  <span m=''2999380''>complexity</span> <span m=''3000110''>is</span> <span m=''3000330''>going</span>
  <span m=''3000490''>to</span> <span m=''3000650''>be --</span> <span m=''3002160''>there</span>
  <span m=''3002635''>are</span> <span m=''3003110''>three</span> <span m=''3003430''>active</span>
  <span m=''3003770''>generators</span> <span m=''3004380''>in</span> <span m=''3004440''>the</span>
  <span m=''3004490''>first</span> <span m=''3004900''>half,</span> <span m=''3005300''>and
  three</span> <span m=''3005550''>active</span> <span m=''3005910''>generators</span>
  <span m=''3006200''>in</span> <span m=''3006490''>the</span> <span m=''3006620''>second</span>
  <span m=''3006970''>half.</span> </p><p><span m=''3011300''>So</span> <span m=''3011560''>by</span>
  <span m=''3011720''>playing</span> <span m=''3012090''>this</span> <span m=''3012280''>kind</span>
  <span m=''3012430''>of</span> <span m=''3012580''>game,</span> <span m=''3012960''>which</span>
  <span m=''3013140''>is</span> <span m=''3013280''>called</span> <span m=''3013530''>sectionalization,</span>
  <span m=''3016310''>we</span> <span m=''3016520''>can</span> <span m=''3017970''>make</span>
  <span m=''3018390''>the</span> <span m=''3018490''>state</span> <span m=''3018880''>complexity</span>
  <span m=''3019520''>sometimes</span> <span m=''3020080''>appear</span> <span m=''3020390''>simpler.</span>
  <span m=''3020880''>There</span> <span m=''3021070''>are</span> <span m=''3021110''>limits</span>
  <span m=''3021730''>to</span> <span m=''3022150''>how</span> <span m=''3022280''>much</span>
  <span m=''3022550''>simpler</span> <span m=''3022830''>we</span> <span m=''3023110''>can
  make it.</span> <span m=''3023480''>Well, there</span> <span m=''3023630''>actually</span>
  <span m=''3023970''>aren''t.</span> <span m=''3024470''>Suppose</span> <span m=''3024690''>we</span>
  <span m=''3024830''>took</span> <span m=''3025030''>the</span> <span m=''3025130''>whole</span>
  <span m=''3026950''>eight</span> <span m=''3027340''>symbols</span> <span m=''3027800''>as</span>
  <span m=''3027930''>one</span> <span m=''3028230''>time.</span> <span m=''3029970''>We''d</span>
  <span m=''3030110''>have</span> <span m=''3032100''>0</span> <span m=''3032360''>dimensional</span>
  <span m=''3032790''>state</span> <span m=''3033100''>space</span> <span m=''3033440''>at</span>
  <span m=''3033510''>the</span> <span m=''3033600''>beginning,</span> <span m=''3034010''>and</span>
  <span m=''3034130''>0</span> <span m=''3034410''>dimensional</span> <span m=''3034910''>at</span>
  <span m=''3035120''>the end.</span> <span m=''3035320''>What</span> <span m=''3035490''>does</span>
  <span m=''3035660''>that</span> <span m=''3035820''>trellis</span> <span m=''3036200''>look</span>
  <span m=''3036370''>like?</span> <span m=''3037170''>It</span> <span m=''3037520''>looks</span>
  <span m=''3037800''>like</span> <span m=''3038100''>16</span> <span m=''3039280''>parallel</span>
  <span m=''3039700''>transitions</span> <span m=''3040440''>from</span> <span m=''3040670''>beginning</span>
  <span m=''3040850''>to</span> <span m=''3041030''>end.</span> <span m=''3041700''>That''s</span>
  <span m=''3042080''>a</span> <span m=''3042470''>legitimate</span> <span m=''3042790''>trellis,</span>
  <span m=''3043290''>right?</span> <span m=''3043995''>We</span> <span m=''3044340''>should</span>
  <span m=''3044580''>have one state</span> <span m=''3044950''>at the</span> <span
  m=''3045320''>beginning</span> <span m=''3045680''>and</span> <span m=''3045770''>one</span>
  <span m=''3045950''>state</span> <span m=''3046240''>at</span> <span m=''3046350''>the</span>
  <span m=''3046530''>end,</span> <span m=''3046710''>and</span> <span m=''3046820''>16</span>
  <span m=''3047300''>transitions.</span> </p><p><span m=''3049180''>Is that what</span>
  <span m=''3049510''>we</span> <span m=''3049660''>get</span> <span m=''3050090''>if</span>
  <span m=''3050260''>we</span> <span m=''3050690''>went</span> <span m=''3050920''>through</span>
  <span m=''3051130''>this?</span> <span m=''3051480''>Yeah.</span> <span m=''3052790''>We</span>
  <span m=''3052920''>have</span> <span m=''3053220''>0</span> <span m=''3053810''>0.</span>
  <span m=''3054120''>And</span> <span m=''3054280''>what''s</span> <span m=''3054510''>the</span>
  <span m=''3054600''>branch</span> <span m=''3054940''>complexity?</span> <span m=''3055590''>It''s</span>
  <span m=''3055840''>4.</span> <span m=''3057340''>The</span> <span m=''3057430''>dimension</span>
  <span m=''3057870''>of</span> <span m=''3057910''>the</span> <span m=''3057980''>branch</span>
  <span m=''3058330''>space</span> <span m=''3058740''>is</span> <span m=''3059110''>4</span>
  <span m=''3059200''>if we</span> <span m=''3059300''>took</span> <span m=''3059510''>the</span>
  <span m=''3059610''>whole</span> <span m=''3059820''>thing.</span> </p><p><span
  m=''3062380''>So</span> <span m=''3063220''>we</span> <span m=''3063380''>can</span>
  <span m=''3063590''>mask</span> <span m=''3064100''>state</span> <span m=''3064670''>complexity</span>
  <span m=''3065660''>by</span> <span m=''3066260''>picking</span> <span m=''3066630''>our</span>
  <span m=''3066760''>state</span> <span m=''3067180''>spaces</span> <span m=''3067660''>at</span>
  <span m=''3067710''>appropriate</span> <span m=''3068330''>times,</span> <span m=''3069740''>but</span>
  <span m=''3069960''>you</span> <span m=''3070080''>can''t</span> <span m=''3071240''>ever</span>
  <span m=''3071550''>mask</span> <span m=''3072080''>branch</span> <span m=''3072490''>complexity.</span>
  <span m=''3074060''>And</span> <span m=''3074210''>again,</span> <span m=''3074440''>it''s</span>
  <span m=''3074650''>a</span> <span m=''3074730''>very</span> <span m=''3075380''>intuitive</span>
  <span m=''3076020''>proof</span> <span m=''3076410''>here.</span> <span m=''3078740''>Let''s</span>
  <span m=''3079020''>take</span> <span m=''3079480''>this</span> <span m=''3079830''>time</span>
  <span m=''3080170''>here,</span> <span m=''3080480''>where there</span> <span m=''3080770''>are
  three</span> <span m=''3080940''>active</span> <span m=''3081530''>generators.</span>
  <span m=''3084480''>By</span> <span m=''3084680''>expanding</span> <span m=''3085270''>that</span>
  <span m=''3085560''>time,</span> <span m=''3086020''>can we</span> <span m=''3086180''>ever</span>
  <span m=''3086380''>get</span> <span m=''3086690''>fewer</span> <span m=''3087070''>than</span>
  <span m=''3087530''>three active</span> <span m=''3088000''>generators?</span> <span
  m=''3089145''>No,</span> <span m=''3090400''>any</span> <span m=''3090760''>interval</span>
  <span m=''3091300''>that</span> <span m=''3091380''>includes</span> <span m=''3092460''>this</span>
  <span m=''3093110''>particular</span> <span m=''3093690''>time</span> <span m=''3094420''>is</span>
  <span m=''3094540''>going</span> <span m=''3094660''>to</span> <span m=''3094790''>have</span>
  <span m=''3094920''>three</span> <span m=''3095190''>active</span> <span m=''3095520''>generators</span>
  <span m=''3095830''>in</span> <span m=''3096140''>it.</span> </p><p><span m=''3098090''>So</span>
  <span m=''3098340''>branch</span> <span m=''3098770''>complexity</span> <span m=''3099500''>cannot</span>
  <span m=''3099870''>be</span> <span m=''3100010''>reduced</span> <span m=''3100490''>by</span>
  <span m=''3100640''>this</span> <span m=''3101050''>kind</span> <span m=''3101250''>of</span>
  <span m=''3101340''>sectionalization</span> <span m=''3102240''>game.</span> <span
  m=''3102560''>State</span> <span m=''3102920''>complexity</span> <span m=''3104300''>can</span>
  <span m=''3104440''>be</span> <span m=''3104580''>apparently</span> <span m=''3104890''>reduced.</span>
  <span m=''3105200''>It</span> <span m=''3105600''>isn''t</span> <span m=''3105990''>really.</span>
  <span m=''3107020''>But</span> <span m=''3107150''>branch</span> <span m=''3107530''>complexity</span>
  <span m=''3108150''>cannot.</span> </p><p><span m=''3108680''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''3112730''>PROFESSOR: And</span> <span m=''3112860''>if</span> <span
  m=''3112950''>you</span> <span m=''3113060''>go</span> <span m=''3113240''>too</span>
  <span m=''3113510''>far,</span> <span m=''3113860''>it might</span> <span m=''3114090''>increase.</span>
  </p><p><span m=''3117800''>So</span> <span m=''3119150''>at</span> <span m=''3119280''>the</span>
  <span m=''3119370''>very</span> <span m=''3119730''>end</span> <span m=''3119940''>of</span>
  <span m=''3120040''>the</span> <span m=''3120870''>chapter,</span> <span m=''3121420''>I</span>
  <span m=''3121510''>talk</span> <span m=''3121870''>about</span> <span m=''3122170''>sectionalization.</span>
  <span m=''3125110''>It''s</span> <span m=''3125530''>not</span> <span m=''3125710''>a</span>
  <span m=''3125750''>very</span> <span m=''3126000''>important</span> <span m=''3126470''>issue.</span>
  <span m=''3127580''>There''s</span> <span m=''3127740''>a</span> <span m=''3127800''>very</span>
  <span m=''3129450''>easy</span> <span m=''3129860''>heuristic</span> <span m=''3130630''>for</span>
  <span m=''3130990''>how</span> <span m=''3131190''>you</span> <span m=''3131400''>should</span>
  <span m=''3131860''>sectionalize,</span> <span m=''3132670''>which</span> <span
  m=''3132880''>is</span> <span m=''3133090''>basically</span> <span m=''3134140''>you</span>
  <span m=''3134260''>should</span> <span m=''3134430''>make</span> <span m=''3134630''>the</span>
  <span m=''3134720''>sections</span> <span m=''3135280''>as</span> <span m=''3135420''>big</span>
  <span m=''3135670''>as</span> <span m=''3135810''>you</span> <span m=''3136220''>can</span>
  <span m=''3136640''>without</span> <span m=''3137010''>increasing</span> <span m=''3137700''>branch</span>
  <span m=''3137970''>complexity.</span> </p><p><span m=''3139790''>So</span> <span
  m=''3140050''>in</span> <span m=''3140120''>this</span> <span m=''3140330''>case,</span>
  <span m=''3141390''>the</span> <span m=''3141490''>heuristic</span> <span m=''3142040''>says</span>
  <span m=''3142910''>we</span> <span m=''3143100''>know</span> <span m=''3143290''>we''re</span>
  <span m=''3143460''>going</span> <span m=''3143560''>to</span> <span m=''3143720''>have</span>
  <span m=''3143880''>to</span> <span m=''3144030''>have</span> <span m=''3144780''>branch</span>
  <span m=''3144940''>complexity</span> <span m=''3145490''>of</span> <span m=''3145590''>3.</span>
  <span m=''3147330''>But</span> <span m=''3147520''>without</span> <span m=''3147850''>increasing
  --</span> <span m=''3148620''>if</span> <span m=''3148850''>I</span> <span m=''3148990''>just</span>
  <span m=''3149320''>make</span> <span m=''3149550''>this</span> <span m=''3149750''>one</span>
  <span m=''3150430''>partition</span> <span m=''3151010''>at</span> <span m=''3151140''>the</span>
  <span m=''3151230''>center,</span> <span m=''3152560''>I</span> <span m=''3152660''>just</span>
  <span m=''3152870''>take</span> <span m=''3153090''>these</span> <span m=''3153350''>two</span>
  <span m=''3153530''>sections,</span> <span m=''3154170''>first</span> <span m=''3154530''>half,</span>
  <span m=''3154800''>second</span> <span m=''3155230''>half.</span> <span m=''3156360''>Then</span>
  <span m=''3156510''>I</span> <span m=''3156580''>have</span> <span m=''3156780''>an</span>
  <span m=''3156860''>increased</span> <span m=''3158180''>branch</span> <span m=''3158450''>complexity.</span>
  <span m=''3159980''>So</span> <span m=''3160120''>that''s</span> <span m=''3160360''>a</span>
  <span m=''3160420''>good</span> <span m=''3160640''>sectionalization.</span> <span
  m=''3162110''>This will</span> <span m=''3162390''>probably</span> <span m=''3162780''>lead</span>
  <span m=''3163090''>to</span> <span m=''3163190''>the</span> <span m=''3163300''>simplest</span>
  <span m=''3163780''>Viterbi</span> <span m=''3164240''>algorithm</span> <span m=''3164790''>and</span>
  <span m=''3164930''>the</span> <span m=''3165370''>simplest-looking</span> <span
  m=''3166310''>trellis</span> <span m=''3167110''>representation</span> <span m=''3167940''>of</span>
  <span m=''3168050''>the</span> <span m=''3168160''>code.</span> </p><p><span m=''3172290''>So</span>
  <span m=''3172760''>that''s</span> <span m=''3173360''>the</span> <span m=''3173470''>character</span>
  <span m=''3173735''>of</span> <span m=''3174000''>the</span> <span m=''3174100''>sectionalization</span>
  <span m=''3174940''>algorithm.</span> <span m=''3175380''>You</span> <span m=''3175510''>can</span>
  <span m=''3175630''>read</span> <span m=''3175840''>about</span> <span m=''3176170''>it.</span>
  <span m=''3176700''>It</span> <span m=''3176870''>usually</span> <span m=''3177970''>winds</span>
  <span m=''3178330''>up</span> <span m=''3178520''>with</span> <span m=''3178710''>a</span>
  <span m=''3179400''>sensible</span> <span m=''3180450''>time-varying</span> <span
  m=''3182030''>sectionalization,</span> <span m=''3183620''>and</span> <span m=''3184680''>it''s</span>
  <span m=''3184860''>worth</span> <span m=''3185420''>five</span> <span m=''3185680''>minutes</span>
  <span m=''3185910''>of</span> <span m=''3185980''>discussion.</span> <span m=''3186490''>Yes.</span>
  </p><p><span m=''3186860''>AUDIENCE: Is it</span> <span m=''3187313''>like</span>
  <span m=''3187766''>a</span> <span m=''3188219''>monotonic</span> <span m=''3188672''>kind
  of</span> <span m=''3189125''>thing,</span> <span m=''3189578''>like if you make</span>
  <span m=''3190031''>sections</span> <span m=''3190484''>bigger,</span> <span m=''3191390''>then</span>
  <span m=''3192130''>you''ll</span> <span m=''3192490''>only</span> <span m=''3192930''>either</span>
  <span m=''3193400''>increase</span> <span m=''3193880''>or keep the</span> <span
  m=''3193980''>same</span> <span m=''3194390''>branch</span> <span m=''3194880''>complexity?</span>
  </p><p><span m=''3195860''>PROFESSOR: Yeah,</span> <span m=''3196100''>that</span>
  <span m=''3196290''>was</span> <span m=''3196460''>my</span> <span m=''3196590''>basic</span>
  <span m=''3197040''>argument,</span> <span m=''3197360''>that</span> <span m=''3197680''>if</span>
  <span m=''3197970''>I</span> <span m=''3198180''>have</span> <span m=''3198380''>any</span>
  <span m=''3198640''>section</span> <span m=''3199120''>that</span> <span m=''3199240''>includes</span>
  <span m=''3200250''>this</span> <span m=''3200540''>time,</span> <span m=''3200870''>and
  I</span> <span m=''3200980''>start</span> <span m=''3201240''>making</span> <span
  m=''3201520''>it</span> <span m=''3201560''>bigger,</span> <span m=''3202800''>the</span>
  <span m=''3202890''>dimension</span> <span m=''3203510''>can</span> <span m=''3203630''>only</span>
  <span m=''3203870''>increase.</span> <span m=''3205240''>So</span> <span m=''3205490''>the</span>
  <span m=''3205730''>algorithm</span> <span m=''3205970''>is</span> <span m=''3206140''>to</span>
  <span m=''3206360''>keep</span> <span m=''3206640''>increasing</span> <span m=''3207230''>it</span>
  <span m=''3207410''>until</span> <span m=''3207840''>I</span> <span m=''3207930''>get</span>
  <span m=''3208840''>to</span> <span m=''3208960''>some</span> <span m=''3209190''>place</span>
  <span m=''3209560''>where</span> <span m=''3209780''>I</span> <span m=''3209800''>might</span>
  <span m=''3210120''>have</span> <span m=''3210380''>to</span> <span m=''3210700''>include</span>
  <span m=''3211080''>another</span> <span m=''3211380''>generator.</span> </p><p><span
  m=''3213050''>For</span> <span m=''3213200''>instance</span> <span m=''3213550''>here,</span>
  <span m=''3214450''>if</span> <span m=''3214600''>I''m</span> <span m=''3214710''>taking</span>
  <span m=''3215040''>this</span> <span m=''3215270''>time,</span> <span m=''3215540''>I</span>
  <span m=''3215620''>don''t</span> <span m=''3215870''>want</span> <span m=''3216000''>to</span>
  <span m=''3216040''>push</span> <span m=''3216350''>it</span> <span m=''3216430''>out</span>
  <span m=''3216600''>over</span> <span m=''3216800''>here,</span> <span m=''3217020''>because</span>
  <span m=''3217310''>then</span> <span m=''3217460''>I''ll</span> <span m=''3217580''>get</span>
  <span m=''3217730''>the</span> <span m=''3217800''>fourth</span> <span m=''3218120''>generator</span>
  <span m=''3218610''>in</span> <span m=''3218720''>there.</span> <span m=''3219710''>So</span>
  <span m=''3219920''>any</span> <span m=''3222760''>section</span> <span m=''3223240''>that</span>
  <span m=''3223340''>includes</span> <span m=''3224200''>time</span> <span m=''3224460''>3</span>
  <span m=''3226340''>should</span> <span m=''3226590''>not</span> <span m=''3227310''>be</span>
  <span m=''3227410''>extended</span> <span m=''3227850''>in</span> <span m=''3227920''>this</span>
  <span m=''3228100''>direction,</span> <span m=''3228590''>because</span> <span m=''3228860''>we''ll</span>
  <span m=''3229000''>get</span> <span m=''3229130''>another</span> <span m=''3229390''>generator.</span>
  <span m=''3230470''>But</span> <span m=''3230820''>no</span> <span m=''3230970''>problem</span>
  <span m=''3231310''>with</span> <span m=''3231490''>extending</span> <span m=''3231960''>in</span>
  <span m=''3232210''>this</span> <span m=''3232470''>direction.</span> <span m=''3234150''>So</span>
  <span m=''3234330''>that''s</span> <span m=''3234720''>the</span> <span m=''3234850''>basic</span>
  <span m=''3235420''>heuristic.</span> </p><p><span m=''3238260''>It''s</span> <span
  m=''3238370''>easy.</span> <span m=''3240070''>And</span> <span m=''3240460''>it''s</span>
  <span m=''3241660''>not</span> <span m=''3241820''>very</span> <span m=''3241990''>productive.</span>
  <span m=''3243130''>It</span> <span m=''3243270''>doesn''t</span> <span m=''3243590''>really</span>
  <span m=''3243910''>change</span> <span m=''3244360''>the</span> <span m=''3244490''>complexity</span>
  <span m=''3245190''>of</span> <span m=''3245620''>the</span> <span m=''3245790''>Viterbi</span>
  <span m=''3246120''>algorithm</span> <span m=''3246630''>as</span> <span m=''3246730''>a</span>
  <span m=''3246830''>representation</span> <span m=''3247200''>of</span> <span m=''3247570''>code.</span>
  </p><p><span m=''3248610''>So</span> <span m=''3248850''>these</span> <span m=''3249110''>are</span>
  <span m=''3249180''>just</span> <span m=''3249480''>a</span> <span m=''3249530''>couple</span>
  <span m=''3249890''>of</span> <span m=''3250040''>arguments</span> <span m=''3250540''>to</span>
  <span m=''3250650''>say</span> <span m=''3250870''>really</span> <span m=''3251920''>we</span>
  <span m=''3252070''>might --</span> <span m=''3252650''>the</span> <span m=''3252850''>branch</span>
  <span m=''3253210''>complexity</span> <span m=''3253740''>is</span> <span m=''3253870''>more</span>
  <span m=''3254080''>fundamental.</span> <span m=''3254720''>We</span> <span m=''3254840''>want</span>
  <span m=''3255050''>to</span> <span m=''3255100''>focus</span> <span m=''3255570''>on</span>
  <span m=''3255700''>branch</span> <span m=''3255990''>complexity</span> <span m=''3256470''>a</span>
  <span m=''3256530''>little</span> <span m=''3256720''>bit</span> <span m=''3256940''>more.</span>
  <span m=''3257600''>But</span> <span m=''3258000''>of</span> <span m=''3258050''>course,</span>
  <span m=''3259240''>if</span> <span m=''3259320''>you have a</span> <span m=''3259570''>fully</span>
  <span m=''3259900''>displayed</span> <span m=''3260800''>trellis,</span> <span m=''3268250''>the</span>
  <span m=''3268750''>maximum</span> <span m=''3269120''>state</span> <span m=''3269710''>space</span>
  <span m=''3270200''>dimension</span> <span m=''3270630''>is</span> <span m=''3271110''>either</span>
  <span m=''3271410''>going</span> <span m=''3271540''>to</span> <span m=''3271580''>be</span>
  <span m=''3271790''>equal</span> <span m=''3272120''>to</span> <span m=''3272230''>the</span>
  <span m=''3272320''>maximum</span> <span m=''3273110''>branch</span> <span m=''3273390''>space</span>
  <span m=''3273740''>dimension</span> <span m=''3274190''>or</span> <span m=''3274290''>one</span>
  <span m=''3274520''>less</span> <span m=''3274810''>than</span> <span m=''3274930''>it.</span>
  <span m=''3275760''>Because</span> <span m=''3276290''>in</span> <span m=''3276370''>these</span>
  <span m=''3276570''>binary</span> <span m=''3276940''>trellises,</span> <span m=''3278440''>we</span>
  <span m=''3278700''>get</span> <span m=''3279850''>at</span> <span m=''3280010''>most</span>
  <span m=''3280330''>a</span> <span m=''3280380''>binary</span> <span m=''3280750''>branch</span>
  <span m=''3281190''>at</span> <span m=''3281250''>each</span> <span m=''3281510''>time.</span>
  </p><p><span m=''3282570''>So</span> <span m=''3284200''>any</span> <span m=''3284400''>branch</span>
  <span m=''3284750''>complexity</span> <span m=''3285330''>is</span> <span m=''3285530''>at</span>
  <span m=''3285600''>most</span> <span m=''3285950''>twice</span> <span m=''3286380''>that</span>
  <span m=''3286600''>of</span> <span m=''3286720''>the</span> <span m=''3287030''>adjacent</span>
  <span m=''3287540''>state</span> <span m=''3288460''>space.</span> <span m=''3290630''>So</span>
  <span m=''3291040''>they''re</span> <span m=''3291320''>not going to</span> <span
  m=''3291780''>differ</span> <span m=''3292575''>by</span> <span m=''3293010''>very</span>
  <span m=''3293240''>much.</span> <span m=''3293640''>So</span> <span m=''3293860''>state</span>
  <span m=''3294150''>complexity</span> <span m=''3294750''>is</span> <span m=''3294890''>a</span>
  <span m=''3294940''>good</span> <span m=''3295200''>proxy</span> <span m=''3295740''>for</span>
  <span m=''3296400''>branch</span> <span m=''3296710''>complexity</span> <span m=''3298230''>in</span>
  <span m=''3298440''>a</span> <span m=''3298860''>fully</span> <span m=''3299210''>displayed</span>
  <span m=''3300340''>or</span> <span m=''3300710''>unsectionalized</span> <span m=''3301780''>trellis.</span>
  </p><p><span m=''3310070''>While</span> <span m=''3310370''>I''m</span> <span m=''3310510''>on</span>
  <span m=''3310700''>this</span> <span m=''3310820''>subject,</span> <span m=''3312530''>there''s</span>
  <span m=''3312720''>another</span> <span m=''3313040''>interesting</span> <span
  m=''3313420''>direction</span> <span m=''3314000''>we can</span> <span m=''3314390''>go,</span>
  <span m=''3319250''>which</span> <span m=''3319590''>is</span> <span m=''3322040''>average</span>
  <span m=''3322750''>dimension</span> <span m=''3323270''>bounds.</span> <span m=''3334080''>Again,</span>
  <span m=''3334460''>think</span> <span m=''3334750''>of</span> <span m=''3334900''>our</span>
  <span m=''3336680''>realization</span> <span m=''3337460''>here.</span> <span m=''3343850''>What</span>
  <span m=''3344200''>does</span> <span m=''3344350''>it</span> <span m=''3344480''>contribute?</span>
  <span m=''3345230''>What</span> <span m=''3345450''>does</span> <span m=''3345580''>a</span>
  <span m=''3345640''>single</span> <span m=''3346020''>generator</span> <span m=''3346600''>contribute</span>
  <span m=''3347230''>overall</span> <span m=''3347950''>to</span> <span m=''3351030''>state</span>
  <span m=''3351520''>and</span> <span m=''3351710''>branch</span> <span m=''3352000''>space</span>
  <span m=''3352800''>complexity?</span> </p><p><span m=''3355430''>A</span> <span
  m=''3355510''>single</span> <span m=''3355900''>generator</span> <span m=''3357960''>Gj</span>
  <span m=''3360410''>of</span> <span m=''3360870''>span</span> <span m=''3362810''>S,</span>
  <span m=''3364930''>which</span> <span m=''3365390''>of</span> <span m=''3365470''>course</span>
  <span m=''3365810''>has</span> <span m=''3366030''>to</span> <span m=''3366130''>be</span>
  <span m=''3366390''>greater</span> <span m=''3366690''>than or</span> <span m=''3366830''>equal</span>
  <span m=''3367170''>to</span> <span m=''3367650''>the</span> <span m=''3367740''>minimum</span>
  <span m=''3368010''>distance to</span> <span m=''3368460''>the</span> <span m=''3368580''>code,</span>
  <span m=''3369000''>right?</span> <span m=''3369370''>The</span> <span m=''3369450''>span</span>
  <span m=''3369900''>can''t</span> <span m=''3370160''>be</span> <span m=''3370290''>less</span>
  <span m=''3370920''>of</span> <span m=''3371030''>a</span> <span m=''3371080''>generator.</span>
  <span m=''3371335''>It</span> <span m=''3371590''>can''t</span> <span m=''3371870''>be</span>
  <span m=''3371990''>less</span> <span m=''3372320''>than</span> <span m=''3372480''>the</span>
  <span m=''3373170''>minimum</span> <span m=''3373530''>nonzero</span> <span m=''3374110''>weight</span>
  <span m=''3374300''>of</span> <span m=''3374450''>any</span> <span m=''3374590''>code</span>
  <span m=''3374850''>word.</span> <span m=''3377180''>Span</span> <span m=''3377600''>S</span>
  <span m=''3378490''>contributes</span> <span m=''3383570''>overall</span> <span
  m=''3384270''>to</span> <span m=''3384430''>all</span> <span m=''3384610''>the</span>
  <span m=''3384860''>state</span> <span m=''3385210''>space</span> <span m=''3385600''>dimensions.</span>
  <span m=''3386320''>It</span> <span m=''3386480''>contributes</span> <span m=''3387920''>S</span>
  <span m=''3388320''>minus</span> <span m=''3388790''>1</span> <span m=''3389790''>state</span>
  <span m=''3390190''>space</span> <span m=''3390610''>dimensions,</span> <span m=''3393020''>because</span>
  <span m=''3393260''>it''s</span> <span m=''3393480''>active</span> <span m=''3394050''>for</span>
  <span m=''3396480''>S</span> <span m=''3396760''>minus</span> <span m=''3397140''>1</span>
  <span m=''3397540''>state</span> <span m=''3397970''>times.</span> <span m=''3402360''>And</span>
  <span m=''3402570''>it</span> <span m=''3402620''>contributes</span> <span m=''3403290''>S</span>
  <span m=''3404330''>branch</span> <span m=''3404700''>dimensions</span> <span m=''3406170''>because</span>
  <span m=''3406400''>it''s</span> <span m=''3406760''>active</span> <span m=''3407200''>for</span>
  <span m=''3407570''>S</span> <span m=''3411170''>symbols.</span> </p><p><span m=''3414240''>If</span>
  <span m=''3414370''>I</span> <span m=''3414450''>look</span> <span m=''3414660''>at</span>
  <span m=''3414870''>it</span> <span m=''3415150''>spread</span> <span m=''3415460''>out</span>
  <span m=''3415630''>across</span> <span m=''3416100''>time,</span> <span m=''3416520''>this</span>
  <span m=''3416820''>generator</span> <span m=''3418075''>of</span> <span m=''3418530''>span</span>
  <span m=''3419190''>4,</span> <span m=''3420510''>it</span> <span m=''3420740''>contributed</span>
  <span m=''3421670''>three</span> <span m=''3422020''>times</span> <span m=''3422710''>to</span>
  <span m=''3424300''>a</span> <span m=''3424420''>state</span> <span m=''3424740''>space</span>
  <span m=''3425100''>dimension,</span> <span m=''3425680''>and</span> <span m=''3425780''>it</span>
  <span m=''3425890''>contributed</span> <span m=''3426510''>four</span> <span m=''3426800''>times</span>
  <span m=''3427250''>to</span> <span m=''3427440''>a</span> <span m=''3428690''>branch</span>
  <span m=''3429150''>dimension.</span> <span m=''3433510''>So</span> <span m=''3436880''>total</span>
  <span m=''3439790''>state</span> <span m=''3440220''>dimension</span> <span m=''3442830''>has</span>
  <span m=''3443090''>to</span> <span m=''3443180''>be</span> <span m=''3443550''>greater</span>
  <span m=''3443880''>than</span> <span m=''3444080''>or</span> <span m=''3444190''>equal</span>
  <span m=''3444550''>to</span> <span m=''3445490''>k</span> <span m=''3445850''>times</span>
  <span m=''3446390''>d</span> <span m=''3446530''>minus</span> <span m=''3446920''>1.</span>
  <span m=''3448360''>And</span> <span m=''3448480''>the</span> <span m=''3448610''>total</span>
  <span m=''3450020''>branch</span> <span m=''3450520''>dimension,</span> <span m=''3451590''>just</span>
  <span m=''3451800''>summing</span> <span m=''3452140''>up</span> <span m=''3452300''>across</span>
  <span m=''3452760''>the</span> <span m=''3452850''>trellis,</span> <span m=''3454380''>is</span>
  <span m=''3454570''>greater</span> <span m=''3454870''>than</span> <span m=''3455020''>or</span>
  <span m=''3455080''>equal</span> <span m=''3455410''>to</span> <span m=''3455850''>k</span>
  <span m=''3456110''>generators</span> <span m=''3456850''>times</span> <span m=''3457210''>d.</span>
  </p><p><span m=''3461960''>Now</span> <span m=''3462110''>how</span> <span m=''3462260''>many</span>
  <span m=''3462480''>different</span> <span m=''3462970''>nontrivial</span> <span
  m=''3463750''>state</span> <span m=''3464350''>spaces</span> <span m=''3464780''>are</span>
  <span m=''3464950''>there?</span> <span m=''3467000''>There</span> <span m=''3467140''>are</span>
  <span m=''3467210''>n</span> <span m=''3467470''>minus</span> <span m=''3467860''>1</span>
  <span m=''3468190''>nontrivial</span> <span m=''3469000''>state</span> <span m=''3469780''>times.</span>
  <span m=''3470300''>Excuse</span> <span m=''3470740''>me.</span> <span m=''3472420''>For</span>
  <span m=''3472560''>instance,</span> <span m=''3473050''>in this</span> <span m=''3473350''>code
  of</span> <span m=''3473750''>length</span> <span m=''3474240''>8,</span> <span
  m=''3474660''>there</span> <span m=''3474840''>are</span> <span m=''3474890''>7</span>
  <span m=''3475730''>nontrivial</span> <span m=''3476750''>state</span> <span m=''3477530''>spaces.</span>
  <span m=''3480830''>So</span> <span m=''3481160''>the</span> <span m=''3481400''>average</span>
  <span m=''3484470''>state</span> <span m=''3485770''>dimension</span> <span m=''3487490''>has</span>
  <span m=''3487750''>to</span> <span m=''3487840''>be</span> <span m=''3488020''>greater</span>
  <span m=''3488270''>than</span> <span m=''3488410''>or</span> <span m=''3488530''>equal</span>
  <span m=''3488940''>to</span> <span m=''3491920''>k</span> <span m=''3492875''>d</span>
  <span m=''3493390''>minus</span> <span m=''3493810''>1</span> <span m=''3494370''>over</span>
  <span m=''3495140''>n</span> <span m=''3495330''>minus</span> <span m=''3495740''>1.</span>
  <span m=''3498440''>And</span> <span m=''3498770''>the</span> <span m=''3498920''>average</span>
  <span m=''3500500''>branch</span> <span m=''3503300''>dimension</span> <span m=''3504645''>has</span>
  <span m=''3504960''>got</span> <span m=''3505120''>to be</span> <span m=''3505230''>greater</span>
  <span m=''3505610''>than</span> <span m=''3505720''>or equal</span> <span m=''3505990''>to</span>
  <span m=''3506100''>k</span> <span m=''3506410''>d</span> <span m=''3506830''>over</span>
  <span m=''3507160''>the</span> <span m=''3507670''>n</span> <span m=''3508030''>symbol</span>
  <span m=''3508400''>times.</span> </p><p><span m=''3515260''>So</span> <span m=''3515610''>actually</span>
  <span m=''3516290''>we</span> <span m=''3516660''>might</span> <span m=''3516850''>remember</span>
  <span m=''3517200''>that</span> <span m=''3517880''>quantity.</span> <span m=''3520350''>That''s</span>
  <span m=''3520600''>what we</span> <span m=''3520720''>called</span> <span m=''3521010''>the</span>
  <span m=''3521110''>coding</span> <span m=''3521510''>gain of</span> <span m=''3521760''>the</span>
  <span m=''3521860''>code,</span> <span m=''3522570''>the</span> <span m=''3522700''>nominal</span>
  <span m=''3523060''>coding</span> <span m=''3523280''>gain</span> <span m=''3523740''>on
  the</span> <span m=''3523900''>additive</span> <span m=''3524070''>white</span>
  <span m=''3524280''>Gaussian</span> <span m=''3524670''>noise</span> <span m=''3524990''>channel.</span>
  <span m=''3526700''>Well,</span> <span m=''3526940''>if the</span> <span m=''3527090''>average</span>
  <span m=''3527520''>dimension</span> <span m=''3528400''>is</span> <span m=''3528740''>lower</span>
  <span m=''3528990''>bounded</span> <span m=''3529300''>by</span> <span m=''3529520''>something,</span>
  <span m=''3530030''>then</span> <span m=''3530210''>certainly</span> <span m=''3530610''>the</span>
  <span m=''3530750''>maximum</span> <span m=''3531660''>state</span> <span m=''3532040''>space</span>
  <span m=''3532440''>dimension</span> <span m=''3532760''>is</span> <span m=''3533080''>lower</span>
  <span m=''3533290''>bounded</span> <span m=''3533700''>by that.</span> <span m=''3543280''>Max</span>
  <span m=''3543540''>has</span> <span m=''3543750''>to</span> <span m=''3543830''>be</span>
  <span m=''3543990''>at</span> <span m=''3544200''>least</span> <span m=''3544480''>as</span>
  <span m=''3544580''>great</span> <span m=''3544780''>as</span> <span m=''3544890''>the</span>
  <span m=''3545010''>average.</span> </p><p><span m=''3549510''>So</span> <span m=''3549850''>if</span>
  <span m=''3550060''>these</span> <span m=''3550380''>are</span> <span m=''3550430''>what</span>
  <span m=''3550580''>are</span> <span m=''3550660''>called</span> <span m=''3550920''>the</span>
  <span m=''3551060''>average</span> <span m=''3552130''>dimension</span> <span m=''3552580''>bounds</span>
  <span m=''3553720''>on</span> <span m=''3553920''>the</span> <span m=''3553960''>maximum</span>
  <span m=''3554470''>state</span> <span m=''3554830''>space</span> <span m=''3555220''>size,</span>
  <span m=''3556960''>and</span> <span m=''3559570''>there</span> <span m=''3559780''>are</span>
  <span m=''3559840''>some</span> <span m=''3560050''>interesting</span> <span m=''3561580''>implications.</span>
  <span m=''3563700''>Again,</span> <span m=''3564040''>this</span> <span m=''3564310''>expression</span>
  <span m=''3564850''>for</span> <span m=''3565190''>branch</span> <span m=''3565530''>dimension</span>
  <span m=''3565940''>is</span> <span m=''3566080''>nicer</span> <span m=''3566480''>here,</span>
  <span m=''3566690''>because</span> <span m=''3567060''>it''s</span> <span m=''3567260''>this</span>
  <span m=''3567450''>k</span> <span m=''3567650''>d</span> <span m=''3567790''>over</span>
  <span m=''3567930''>n</span> <span m=''3568440''>nominal</span> <span m=''3568820''>coding</span>
  <span m=''3569150''>gain</span> <span m=''3569420''>thing.</span> <span m=''3570090''>It''s</span>
  <span m=''3570360''>in</span> <span m=''3570510''>terms</span> <span m=''3570870''>of</span>
  <span m=''3570910''>the</span> <span m=''3570980''>basic</span> <span m=''3571480''>n
  k</span> <span m=''3571710''>d</span> <span m=''3572190''>parameters</span> <span
  m=''3572910''>of</span> <span m=''3573150''>the</span> <span m=''3573270''>code.</span>
  </p><p><span m=''3574606''>And</span> <span m=''3575020''>it</span> <span m=''3575310''>says</span>
  <span m=''3575500''>what?</span> <span m=''3576390''>It</span> <span m=''3576520''>says</span>
  <span m=''3576910''>if</span> <span m=''3577020''>you</span> <span m=''3578220''>want</span>
  <span m=''3578500''>a</span> <span m=''3578650''>nominal</span> <span m=''3579120''>coding</span>
  <span m=''3579460''>gain</span> <span m=''3579850''>of</span> <span m=''3580020''>2,</span>
  <span m=''3582655''>it</span> <span m=''3583080''>implies</span> <span m=''3584020''>that</span>
  <span m=''3584190''>the</span> <span m=''3585660''>max</span> <span m=''3587090''>branch</span>
  <span m=''3587580''>dimension</span> <span m=''3589116''>is</span> <span m=''3589570''>greater
  than</span> <span m=''3589830''>or</span> <span m=''3590170''>equal</span> <span
  m=''3590520''>to</span> <span m=''3591400''>2.</span> <span m=''3592560''>Or</span>
  <span m=''3592760''>the</span> <span m=''3592900''>max</span> <span m=''3595290''>size</span>
  <span m=''3596080''>is</span> <span m=''3596520''>greater</span> <span m=''3596730''>than
  or</span> <span m=''3596890''>equal</span> <span m=''3597180''>to</span> <span m=''3597320''>2</span>
  <span m=''3597510''>to</span> <span m=''3597580''>the</span> <span m=''3597710''>2,</span>
  <span m=''3598040''>or</span> <span m=''3598520''>you</span> <span m=''3598950''>need</span>
  <span m=''3599120''>a</span> <span m=''3599170''>branch</span> <span m=''3599560''>space</span>
  <span m=''3600050''>of</span> <span m=''3600140''>at</span> <span m=''3600200''>least</span>
  <span m=''3600510''>size</span> <span m=''3600910''>4,</span> <span m=''3601420''>or</span>
  <span m=''3601610''>dimension</span> <span m=''3602160''>2</span> <span m=''3605000''>to
  get</span> <span m=''3605430''>a</span> <span m=''3605770''>3 dB</span> <span m=''3606410''>nominal</span>
  <span m=''3606850''>coding</span> <span m=''3607050''>gain.</span> </p><p><span
  m=''3609540''>Similarly,</span> <span m=''3610990''>if</span> <span m=''3611090''>you</span>
  <span m=''3611230''>want</span> <span m=''3611370''>a</span> <span m=''3611440''>6
  dB</span> <span m=''3611910''>gain --</span> <span m=''3615850''>let''s</span> <span
  m=''3616070''>get</span> <span m=''3616240''>right</span> <span m=''3616570''>down</span>
  <span m=''3616820''>to</span> <span m=''3616920''>dB.</span> <span m=''3618382''>It</span>
  <span m=''3618780''>says</span> <span m=''3619200''>you''re</span> <span m=''3619370''>going</span>
  <span m=''3619480''>to</span> <span m=''3619540''>need</span> <span m=''3619850''>a</span>
  <span m=''3620000''>branch</span> <span m=''3620410''>space</span> <span m=''3621140''>size</span>
  <span m=''3622356''>greater than or</span> <span m=''3622762''>equal to</span> <span
  m=''3623170''>4,</span> <span m=''3624930''>or</span> <span m=''3625510''>at</span>
  <span m=''3625580''>least</span> <span m=''3625890''>a</span> <span m=''3625980''>16-state</span>
  <span m=''3626920''>trellis.</span> <span m=''3628320''>So</span> <span m=''3628490''>we</span>
  <span m=''3628590''>know</span> <span m=''3628800''>if</span> <span m=''3628880''>we</span>
  <span m=''3628950''>want</span> <span m=''3629110''>a</span> <span m=''3629160''>6
  dB</span> <span m=''3629600''>coding</span> <span m=''3630010''>gain,</span> <span
  m=''3630400''>we''re</span> <span m=''3630470''>going</span> <span m=''3630600''>to</span>
  <span m=''3630670''>need</span> <span m=''3630890''>at</span> <span m=''3630930''>least</span>
  <span m=''3631210''>a</span> <span m=''3631270''>16-state</span> <span m=''3631850''>trellis,</span>
  <span m=''3633730''>or a</span> <span m=''3633870''>16-branch</span> <span m=''3634890''>trellis.</span>
  <span m=''3635170''>It</span> <span m=''3635450''>might</span> <span m=''3635835''>be
  an</span> <span m=''3636220''>eight-state</span> <span m=''3636600''>trellis.</span>
  </p><p><span m=''3637710''>Well,</span> <span m=''3637900''>these</span> <span m=''3638190''>are</span>
  <span m=''3639030''>not</span> <span m=''3639340''>tight,</span> <span m=''3639770''>but</span>
  <span m=''3639970''>they''re</span> <span m=''3640810''>quite</span> <span m=''3641040''>indicative</span>
  <span m=''3641680''>in</span> <span m=''3641840''>fact</span> <span m=''3642170''>of
  what</span> <span m=''3642320''>we</span> <span m=''3642440''>see</span> <span m=''3643460''>in</span>
  <span m=''3643620''>both</span> <span m=''3644000''>the</span> <span m=''3645420''>tables</span>
  <span m=''3645910''>for</span> <span m=''3646110''>block</span> <span m=''3646460''>codes</span>
  <span m=''3647160''>and</span> <span m=''3647510''>for</span> <span m=''3649070''>convolutional</span>
  <span m=''3649730''>codes.</span> <span m=''3650685''>These</span> <span m=''3651170''>same</span>
  <span m=''3651390''>bounds</span> <span m=''3651770''>hold</span> <span m=''3652030''>for</span>
  <span m=''3652140''>convolutional</span> <span m=''3652660''>codes,</span> <span
  m=''3653000''>by</span> <span m=''3653170''>the</span> <span m=''3653300''>way,</span>
  <span m=''3654390''>just</span> <span m=''3654680''>average</span> <span m=''3655070''>over</span>
  <span m=''3655280''>infinite</span> <span m=''3655670''>time.</span> <span m=''3658540''>But</span>
  <span m=''3658780''>they''re</span> <span m=''3659420''>still</span> <span m=''3659660''>perfectly</span>
  <span m=''3660100''>good.</span> </p><p><span m=''3661870''>So</span> <span m=''3662690''>they</span>
  <span m=''3663250''>tell</span> <span m=''3663530''>us</span> <span m=''3663820''>that</span>
  <span m=''3663960''>in</span> <span m=''3664090''>order</span> <span m=''3664330''>to</span>
  <span m=''3664390''>get --</span> <span m=''3666020''>if</span> <span m=''3666320''>we</span>
  <span m=''3666400''>want</span> <span m=''3666680''>the</span> <span m=''3666900''>nominal</span>
  <span m=''3667350''>coding</span> <span m=''3667690''>gain</span> <span m=''3667980''>to</span>
  <span m=''3668080''>keep</span> <span m=''3668330''>going</span> <span m=''3668680''>up</span>
  <span m=''3669010''>to</span> <span m=''3669360''>8,</span> <span m=''3670060''>to</span>
  <span m=''3670150''>16,</span> <span m=''3671010''>to</span> <span m=''3671470''>infinity,</span>
  <span m=''3674740''>it</span> <span m=''3674830''>says</span> <span m=''3675050''>we''re</span>
  <span m=''3675120''>going</span> <span m=''3675210''>to</span> <span m=''3675300''>need</span>
  <span m=''3675470''>infinite</span> <span m=''3675910''>trellis</span> <span m=''3676290''>complexity</span>
  <span m=''3676960''>to</span> <span m=''3677060''>get</span> <span m=''3677270''>infinite</span>
  <span m=''3677690''>coding</span> <span m=''3677900''>gain.</span> </p><p><span
  m=''3683740''>Let''s</span> <span m=''3684230''>do</span> <span m=''3684400''>some</span>
  <span m=''3685840''>little</span> <span m=''3686210''>asymptotics,</span> <span
  m=''3686890''>be</span> <span m=''3687230''>a</span> <span m=''3687280''>little</span>
  <span m=''3687460''>bit</span> <span m=''3687640''>more</span> <span m=''3688760''>refined</span>
  <span m=''3689260''>about</span> <span m=''3689620''>this.</span> <span m=''3696280''>A</span>
  <span m=''3697890''>sequence</span> <span m=''3698430''>of</span> <span m=''3698570''>codes</span>
  <span m=''3704320''>Cn</span> <span m=''3706820''>of</span> <span m=''3707460''>length</span>
  <span m=''3709980''>n</span> <span m=''3710470''>going</span> <span m=''3710780''>to</span>
  <span m=''3711010''>infinity</span> <span m=''3713800''>is</span> <span m=''3714020''>called</span>
  <span m=''3714520''>good</span> <span m=''3716860''>if</span> <span m=''3718970''>both</span>
  <span m=''3719700''>the</span> <span m=''3719810''>rate</span> <span m=''3720700''>k</span>
  <span m=''3720980''>over</span> <span m=''3721260''>n</span> <span m=''3721490''>is</span>
  <span m=''3721670''>bounded</span> <span m=''3722050''>away</span> <span m=''3722370''>from</span>
  <span m=''3722630''>0</span> <span m=''3723110''>as</span> <span m=''3723290''>n</span>
  <span m=''3723460''>goes</span> <span m=''3723740''>to</span> <span m=''3723860''>infinity,</span>
  <span m=''3725310''>and</span> <span m=''3726420''>the</span> <span m=''3726510''>distance</span>
  <span m=''3727170''>d</span> <span m=''3727380''>over</span> <span m=''3727670''>n</span>
  <span m=''3728870''>is</span> <span m=''3729170''>bounded</span> <span m=''3729540''>away</span>
  <span m=''3729720''>from</span> <span m=''3729960''>0.</span> <span m=''3731690''>The</span>
  <span m=''3731800''>rate</span> <span m=''3732200''>and</span> <span m=''3732310''>the</span>
  <span m=''3732420''>relative</span> <span m=''3732920''>distance</span> <span m=''3733970''>are</span>
  <span m=''3734090''>both</span> <span m=''3735350''>bounded</span> <span m=''3735690''>away</span>
  <span m=''3735980''>from</span> <span m=''3736200''>0</span> <span m=''3736880''>as</span>
  <span m=''3737290''>n</span> <span m=''3737480''>goes</span> <span m=''3737750''>to</span>
  <span m=''3737870''>infinity.</span> </p><p><span m=''3738810''>Is</span> <span
  m=''3738960''>that</span> <span m=''3739120''>clear?</span> <span m=''3739450''>In</span>
  <span m=''3739520''>other</span> <span m=''3739670''>words,</span> <span m=''3739930''>we</span>
  <span m=''3740050''>want</span> <span m=''3740390''>the</span> <span m=''3741350''>dimension</span>
  <span m=''3742920''>and</span> <span m=''3743180''>the</span> <span m=''3743240''>minimum</span>
  <span m=''3743510''>distance</span> <span m=''3744030''>both</span> <span m=''3744280''>to</span>
  <span m=''3744400''>increase</span> <span m=''3744810''>linearly</span> <span m=''3745250''>with</span>
  <span m=''3745380''>n</span> <span m=''3747250''>in</span> <span m=''3747430''>a</span>
  <span m=''3747530''>good</span> <span m=''3747830''>sequence</span> <span m=''3748320''>of</span>
  <span m=''3748400''>codes.</span> <span m=''3748830''>This</span> <span m=''3749020''>is</span>
  <span m=''3749170''>a</span> <span m=''3749280''>classical</span> <span m=''3750290''>algebraic</span>
  <span m=''3751040''>definition,</span> <span m=''3751375''>and</span> <span m=''3751710''>it''s</span>
  <span m=''3752020''>easy</span> <span m=''3752320''>to</span> <span m=''3752420''>prove</span>
  <span m=''3752910''>there</span> <span m=''3753840''>exists</span> <span m=''3754340''>good</span>
  <span m=''3754550''>sequences</span> <span m=''3755160''>of</span> <span m=''3755290''>codes.</span>
  <span m=''3756660''>You</span> <span m=''3756750''>just</span> <span m=''3756940''>pick
  a</span> <span m=''3757230''>code</span> <span m=''3757520''>at</span> <span m=''3758070''>random,</span>
  <span m=''3758900''>rate</span> <span m=''3759150''>1/2</span> <span m=''3759790''>of</span>
  <span m=''3759880''>binary</span> <span m=''3760350''>linear</span> <span m=''3760730''>code.</span>
  <span m=''3762110''>It</span> <span m=''3763480''>on</span> <span m=''3763760''>average</span>
  <span m=''3764180''>will</span> <span m=''3764390''>have</span> <span m=''3765240''>a</span>
  <span m=''3765600''>relative</span> <span m=''3766010''>minimum</span> <span m=''3766320''>distance</span>
  <span m=''3766800''>about</span> <span m=''3767010''>11%.</span> <span m=''3768750''>This</span>
  <span m=''3769180''>is</span> <span m=''3769290''>just</span> <span m=''3769530''>basic</span>
  <span m=''3769910''>information</span> <span m=''3770560''>theory.</span> </p><p><span
  m=''3773650''>So</span> <span m=''3775580''>there</span> <span m=''3775820''>certainly</span>
  <span m=''3776120''>exists</span> <span m=''3776490''>sequences</span> <span m=''3776900''>of</span>
  <span m=''3777020''>good</span> <span m=''3777300''>codes,</span> <span m=''3777740''>and</span>
  <span m=''3777850''>this</span> <span m=''3778050''>is</span> <span m=''3778190''>what</span>
  <span m=''3779040''>most</span> <span m=''3779380''>of</span> <span m=''3779500''>coding</span>
  <span m=''3779830''>theory</span> <span m=''3781060''>was</span> <span m=''3781420''>occupied</span>
  <span m=''3781980''>with</span> <span m=''3782130''>constructing</span> <span m=''3782780''>for</span>
  <span m=''3782890''>a</span> <span m=''3783010''>very</span> <span m=''3783260''>long</span>
  <span m=''3783570''>time.</span> <span m=''3785380''>What</span> <span m=''3785660''>happens</span>
  <span m=''3786040''>if</span> <span m=''3786130''>you</span> <span m=''3786230''>have</span>
  <span m=''3786320''>a</span> <span m=''3786410''>good</span> <span m=''3786780''>sequence</span>
  <span m=''3787230''>of</span> <span m=''3787340''>codes?</span> <span m=''3790990''>We</span>
  <span m=''3791190''>have</span> <span m=''3792700''>this</span> <span m=''3793380''>nominal</span>
  <span m=''3793840''>coding</span> <span m=''3794210''>gain,</span> <span m=''3795630''>which</span>
  <span m=''3795850''>is</span> <span m=''3796010''>equal</span> <span m=''3796390''>to</span>
  <span m=''3796530''>kd</span> <span m=''3797200''>over</span> <span m=''3797500''>n,</span>
  <span m=''3798600''>which</span> <span m=''3798790''>is</span> <span m=''3798960''>equal</span>
  <span m=''3799380''>to</span> <span m=''3800320''>n</span> <span m=''3800710''>times</span>
  <span m=''3801700''>k</span> <span m=''3801960''>over</span> <span m=''3802290''>n</span>
  <span m=''3802610''>times</span> <span m=''3803610''>d</span> <span m=''3803840''>over</span>
  <span m=''3804100''>n.</span> <span m=''3804975''>If</span> <span m=''3805300''>both</span>
  <span m=''3805580''>of</span> <span m=''3805680''>these</span> <span m=''3806050''>are</span>
  <span m=''3806110''>bounded</span> <span m=''3806500''>away</span> <span m=''3806810''>from</span>
  <span m=''3807060''>zero,</span> <span m=''3808930''>then</span> <span m=''3809100''>the</span>
  <span m=''3809210''>nominal</span> <span m=''3809650''>coding</span> <span m=''3810030''>gain</span>
  <span m=''3810440''>has</span> <span m=''3810780''>to</span> <span m=''3811950''>increase</span>
  <span m=''3812490''>linearly</span> <span m=''3820400''>with</span> <span m=''3820570''>n.</span>
  </p><p><span m=''3823240''>That</span> <span m=''3823330''>means</span> <span m=''3823590''>that</span>
  <span m=''3823860''>the</span> <span m=''3824030''>average,</span> <span m=''3826290''>or</span>
  <span m=''3826420''>the</span> <span m=''3826520''>maximum</span> <span m=''3827030''>branch</span>
  <span m=''3827460''>dimension,</span> <span m=''3828515''>in</span> <span m=''3828820''>a</span>
  <span m=''3828840''>minimal</span> <span m=''3829260''>trellis</span> <span m=''3829650''>representation</span>
  <span m=''3831150''>for</span> <span m=''3831420''>your</span> <span m=''3831690''>code</span>
  <span m=''3832100''>has</span> <span m=''3832380''>to</span> <span m=''3832520''>increase</span>
  <span m=''3833010''>at</span> <span m=''3833210''>least</span> <span m=''3833410''>linearly</span>
  <span m=''3833830''>with</span> <span m=''3833940''>n,</span> <span m=''3834740''>which</span>
  <span m=''3835100''>means</span> <span m=''3835500''>that</span> <span m=''3835690''>the</span>
  <span m=''3836430''>actual</span> <span m=''3837890''>branch</span> <span m=''3838620''>complexity,</span>
  <span m=''3839390''>the</span> <span m=''3839510''>size</span> <span m=''3840000''>of</span>
  <span m=''3840190''>B,</span> <span m=''3840400''>has</span> <span m=''3840820''>to</span>
  <span m=''3842120''>increase</span> <span m=''3846071''>as --</span> <span m=''3848150''>it</span>
  <span m=''3848610''>goes</span> <span m=''3849000''>as</span> <span m=''3849190''>2</span>
  <span m=''3849510''>to</span> <span m=''3849710''>the</span> <span m=''3849950''>nominal</span>
  <span m=''3850400''>coding</span> <span m=''3850740''>gain,</span> <span m=''3851160''>which</span>
  <span m=''3851460''>is</span> <span m=''3852220''>in</span> <span m=''3852300''>other</span>
  <span m=''3852480''>words</span> <span m=''3852920''>exponentially</span> <span
  m=''3853730''>with</span> <span m=''3853870''>n.</span> </p><p><span m=''3863350''>So</span>
  <span m=''3864480''>basically</span> <span m=''3864910''>what</span> <span m=''3865080''>this</span>
  <span m=''3865360''>says</span> <span m=''3865790''>is</span> <span m=''3866130''>that</span>
  <span m=''3867140''>if</span> <span m=''3867380''>your</span> <span m=''3867600''>objective</span>
  <span m=''3868280''>is</span> <span m=''3868460''>to</span> <span m=''3868570''>get</span>
  <span m=''3868710''>a</span> <span m=''3868850''>good</span> <span m=''3869100''>sequence</span>
  <span m=''3869590''>of</span> <span m=''3869730''>codes,</span> <span m=''3870680''>if</span>
  <span m=''3870780''>this</span> <span m=''3871030''>is</span> <span m=''3871150''>the</span>
  <span m=''3871240''>way</span> <span m=''3871410''>you</span> <span m=''3871510''>think</span>
  <span m=''3871770''>you''re</span> <span m=''3871890''>going</span> <span m=''3872020''>to</span>
  <span m=''3872470''>get</span> <span m=''3872730''>to</span> <span m=''3872850''>channel</span>
  <span m=''3873210''>capacity,</span> <span m=''3876640''>then</span> <span m=''3877190''>sure</span>
  <span m=''3877560''>enough,</span> <span m=''3877780''>your</span> <span m=''3877910''>nominal</span>
  <span m=''3878330''>coding</span> <span m=''3878650''>gain</span> <span m=''3878970''>will</span>
  <span m=''3879480''>go</span> <span m=''3879700''>up</span> <span m=''3879970''>to</span>
  <span m=''3880120''>infinity</span> <span m=''3881050''>linearly</span> <span m=''3881480''>with</span>
  <span m=''3881620''>n.</span> <span m=''3883010''>But</span> <span m=''3883940''>how</span>
  <span m=''3884100''>are</span> <span m=''3884180''>you</span> <span m=''3884230''>going</span>
  <span m=''3884360''>to</span> <span m=''3884450''>decode</span> <span m=''3884880''>it?</span>
  <span m=''3885170''>Our</span> <span m=''3885480''>first</span> <span m=''3885970''>method</span>
  <span m=''3886330''>was</span> <span m=''3886500''>simply</span> <span m=''3886800''>maximum</span>
  <span m=''3887150''>likelihood</span> <span m=''3887780''>decoding.</span> <span
  m=''3888370''>The</span> <span m=''3888910''>complexity</span> <span m=''3889450''>of</span>
  <span m=''3889700''>that,</span> <span m=''3890720''>computing</span> <span m=''3891090''>the</span>
  <span m=''3891170''>distance</span> <span m=''3891600''>to</span> <span m=''3891680''>every</span>
  <span m=''3891910''>code</span> <span m=''3892150''>word,</span> <span m=''3892800''>that</span>
  <span m=''3893070''>certainly</span> <span m=''3893350''>goes</span> <span m=''3893670''>up</span>
  <span m=''3894550''>exponentially</span> <span m=''3895210''>with</span> <span m=''3895400''>n,</span>
  <span m=''3895660''>exhaustive</span> <span m=''3896340''>decoding,</span> <span
  m=''3897720''>comparing</span> <span m=''3898180''>with</span> <span m=''3898310''>every</span>
  <span m=''3898560''>code</span> <span m=''3898820''>word.</span> </p><p><span m=''3899570''>But</span>
  <span m=''3900040''>now</span> <span m=''3900220''>we</span> <span m=''3900300''>have</span>
  <span m=''3900430''>a</span> <span m=''3900490''>new</span> <span m=''3900660''>method</span>
  <span m=''3901140''>which</span> <span m=''3901410''>is,</span> <span m=''3901950''>we</span>
  <span m=''3902090''>hope,</span> <span m=''3902300''>simpler,</span> <span m=''3902930''>which</span>
  <span m=''3903210''>is</span> <span m=''3903470''>trellis</span> <span m=''3903730''>decoding.</span>
  <span m=''3904990''>But</span> <span m=''3905370''>we</span> <span m=''3905530''>find
  out,</span> <span m=''3905840''>unfortunately,</span> <span m=''3907500''>the</span>
  <span m=''3907700''>complexity</span> <span m=''3908470''>of</span> <span m=''3908630''>trellis</span>
  <span m=''3909050''>decoding</span> <span m=''3909500''>is</span> <span m=''3909670''>going</span>
  <span m=''3909780''>to</span> <span m=''3909830''>go</span> <span m=''3909940''>up</span>
  <span m=''3910110''>exponentially</span> <span m=''3910830''>with n</span> <span
  m=''3911180''>as</span> <span m=''3911400''>well.</span> </p><p><span m=''3913170''>So</span>
  <span m=''3916270''>the</span> <span m=''3916400''>good</span> <span m=''3916630''>news</span>
  <span m=''3917010''>was</span> <span m=''3917520''>that</span> <span m=''3919030''>with</span>
  <span m=''3919210''>the</span> <span m=''3919400''>Viterbi</span> <span m=''3919750''>algorithm</span>
  <span m=''3920410''>and</span> <span m=''3920650''>a</span> <span m=''3920890''>minimal</span>
  <span m=''3921250''>trellis,</span> <span m=''3921850''>we</span> <span m=''3922060''>can</span>
  <span m=''3922360''>get</span> <span m=''3922600''>a</span> <span m=''3922740''>simpler</span>
  <span m=''3924140''>optimum</span> <span m=''3924910''>maximum</span> <span m=''3925390''>likelihood</span>
  <span m=''3925960''>decoding</span> <span m=''3926430''>algorithm</span> <span m=''3926890''>for</span>
  <span m=''3927020''>block</span> <span m=''3927330''>code,</span> <span m=''3927630''>simpler</span>
  <span m=''3928000''>than</span> <span m=''3928160''>exhaustive</span> <span m=''3928690''>decoding.</span>
  <span m=''3930070''>The</span> <span m=''3930180''>bad</span> <span m=''3930470''>news</span>
  <span m=''3930800''>is</span> <span m=''3931700''>that</span> <span m=''3931890''>under</span>
  <span m=''3932130''>this</span> <span m=''3932340''>assumption,</span> <span m=''3933600''>the</span>
  <span m=''3934420''>complexity</span> <span m=''3934755''>of</span> <span m=''3935090''>that</span>
  <span m=''3935210''>algorithm</span> <span m=''3935720''>is</span> <span m=''3935800''>still</span>
  <span m=''3936030''>going</span> <span m=''3936150''>to</span> <span m=''3936230''>go</span>
  <span m=''3936390''>up</span> <span m=''3936800''>exponentially</span> <span m=''3937115''>with</span>
  <span m=''3937430''>n.</span> <span m=''3938140''>Maybe</span> <span m=''3938350''>just</span>
  <span m=''3938610''>a</span> <span m=''3938740''>lower</span> <span m=''3938950''>exponent,</span>
  <span m=''3939140''>that''s</span> <span m=''3939532''>all.</span> <span m=''3941070''>So</span>
  <span m=''3941360''>we</span> <span m=''3941480''>haven''t</span> <span m=''3941760''>really</span>
  <span m=''3942060''>solved</span> <span m=''3942570''>our</span> <span m=''3943760''>basic</span>
  <span m=''3944120''>problem,</span> <span m=''3944490''>which</span> <span m=''3944660''>is</span>
  <span m=''3944790''>exponential</span> <span m=''3945400''>decoding</span> <span
  m=''3945850''>complexity,</span> <span m=''3947860''>by</span> <span m=''3947980''>going</span>
  <span m=''3948220''>to</span> <span m=''3948300''>trellis</span> <span m=''3948510''>decoding.</span>
  </p><p><span m=''3952640''>We</span> <span m=''3952790''>have,</span> <span m=''3953830''>however,</span>
  <span m=''3956920''>another</span> <span m=''3957570''>way</span> <span m=''3957730''>to</span>
  <span m=''3957800''>go.</span> <span m=''3959376''>Do</span> <span m=''3959800''>we</span>
  <span m=''3960060''>really</span> <span m=''3960320''>need</span> <span m=''3961030''>the</span>
  <span m=''3961160''>coding</span> <span m=''3961380''>gain</span> <span m=''3962310''>to</span>
  <span m=''3962400''>go</span> <span m=''3962530''>to</span> <span m=''3962620''>infinity,</span>
  <span m=''3963720''>the</span> <span m=''3963820''>nominal</span> <span m=''3963970''>coding</span>
  <span m=''3964340''>gain</span> <span m=''3964610''>to</span> <span m=''3964660''>go</span>
  <span m=''3964780''>to</span> <span m=''3964910''>infinity?</span> </p><p><span
  m=''3967170''>If</span> <span m=''3967420''>we</span> <span m=''3967520''>go</span>
  <span m=''3967660''>back</span> <span m=''3968000''>and</span> <span m=''3968090''>remember</span>
  <span m=''3969220''>the</span> <span m=''3969520''>name</span> <span m=''3969730''>of</span>
  <span m=''3969790''>the</span> <span m=''3969880''>game,</span> <span m=''3970290''>the</span>
  <span m=''3970400''>playing</span> <span m=''3970760''>field</span> <span m=''3971030''>that</span>
  <span m=''3971355''>we''re on,</span> <span m=''3971680''>at least</span> <span
  m=''3971890''>in</span> <span m=''3971960''>the</span> <span m=''3972210''>additive</span>
  <span m=''3972440''>white Gaussian</span> <span m=''3972820''>noise</span> <span
  m=''3973200''>channel,</span> <span m=''3975240''>we</span> <span m=''3975440''>found</span>
  <span m=''3975820''>the</span> <span m=''3975930''>distance</span> <span m=''3976490''>between</span>
  <span m=''3977340''>uncoded</span> <span m=''3977760''>and the</span> <span m=''3978455''>Shannon</span>
  <span m=''3978730''>limit</span> <span m=''3979015''>was</span> <span m=''3979300''>some</span>
  <span m=''3979490''>finite</span> <span m=''3979930''>number,</span> <span m=''3982080''>something</span>
  <span m=''3982510''>like</span> <span m=''3983010''>9 dB</span> <span m=''3983740''>at</span>
  <span m=''3983870''>a</span> <span m=''3983970''>10</span> <span m=''3984150''>to</span>
  <span m=''3984210''>the</span> <span m=''3984300''>minus</span> <span m=''3984620''>5</span>
  <span m=''3984890''>error</span> <span m=''3985130''>probability,</span> <span m=''3985840''>larger</span>
  <span m=''3986290''>at</span> <span m=''3986340''>lower</span> <span m=''3986625''>error</span>
  <span m=''3986910''>probability.</span> <span m=''3987460''>So</span> <span m=''3988880''>that''s</span>
  <span m=''3989340''>the</span> <span m=''3989430''>maximum</span> <span m=''3989990''>effective</span>
  <span m=''3990560''>coding</span> <span m=''3990990''>gain</span> <span m=''3991180''>we</span>
  <span m=''3991330''>can</span> <span m=''3991470''>ever</span> <span m=''3991680''>get.</span>
  </p><p><span m=''3994440''>So</span> <span m=''3994740''>maybe we</span> <span m=''3994960''>only</span>
  <span m=''3995130''>need</span> <span m=''3995330''>a</span> <span m=''3995380''>finite</span>
  <span m=''3996390''>nominal</span> <span m=''3996820''>coding</span> <span m=''3997040''>gain.</span>
  <span m=''3999160''>In</span> <span m=''3999370''>practice,</span> <span m=''3999880''>this</span>
  <span m=''4000100''>means</span> <span m=''4000460''>maybe</span> <span m=''4000670''>we</span>
  <span m=''4000830''>don''t</span> <span m=''4001080''>need</span> <span m=''4001310''>a</span>
  <span m=''4001550''>minimum</span> <span m=''4001860''>distance</span> <span m=''4002440''>that</span>
  <span m=''4002560''>goes</span> <span m=''4002880''>up</span> <span m=''4003250''>linearly</span>
  <span m=''4003640''>with</span> <span m=''4003770''>n.</span> <span m=''4004580''>Maybe</span>
  <span m=''4004800''>we</span> <span m=''4005030''>can</span> <span m=''4005260''>have</span>
  <span m=''4005530''>a</span> <span m=''4005590''>very</span> <span m=''4005860''>long</span>
  <span m=''4006160''>code</span> <span m=''4006470''>with</span> <span m=''4008390''>a</span>
  <span m=''4008750''>low</span> <span m=''4009070''>minimum</span> <span m=''4009390''>distance.</span>
  <span m=''4011220''>And</span> <span m=''4011470''>that</span> <span m=''4011660''>would</span>
  <span m=''4011800''>be</span> <span m=''4012190''>another</span> <span m=''4012470''>way</span>
  <span m=''4012720''>to</span> <span m=''4012950''>crack</span> <span m=''4013310''>the</span>
  <span m=''4013390''>complexity</span> <span m=''4013960''>problem.</span> <span
  m=''4015660''>In</span> <span m=''4015890''>fact,</span> <span m=''4016250''>some</span>
  <span m=''4016520''>of</span> <span m=''4016620''>the</span> <span m=''4016730''>capacity-approaching</span>
  <span m=''4017760''>codes</span> <span m=''4018070''>that</span> <span m=''4018220''>we''re</span>
  <span m=''4018300''>going</span> <span m=''4018380''>to</span> <span m=''4018470''>talk</span>
  <span m=''4018760''>about,</span> <span m=''4019150''>specifically</span> <span
  m=''4019840''>turbo</span> <span m=''4020220''>codes,</span> <span m=''4021120''>tend</span>
  <span m=''4021350''>to</span> <span m=''4021420''>have</span> <span m=''4021810''>bad</span>
  <span m=''4022140''>minimum</span> <span m=''4022440''>distances.</span> <span m=''4023030''>You</span>
  <span m=''4023260''>have</span> <span m=''4023360''>a</span> <span m=''4023470''>turbo</span>
  <span m=''4023810''>code</span> <span m=''4024060''>that''s</span> <span m=''4024320''>thousands</span>
  <span m=''4024780''>of</span> <span m=''4024860''>bits</span> <span m=''4025160''>long,</span>
  <span m=''4026050''>and</span> <span m=''4026260''>its</span> <span m=''4027100''>minimum</span>
  <span m=''4027290''>distance</span> <span m=''4027700''>will</span> <span m=''4027770''>be</span>
  <span m=''4027890''>something</span> <span m=''4028200''>like</span> <span m=''4028370''>20</span>
  <span m=''4028660''>or</span> <span m=''4028750''>30.</span> <span m=''4032330''>And</span>
  <span m=''4032750''>yet</span> <span m=''4033050''>it</span> <span m=''4034300''>signals</span>
  <span m=''4035640''>within</span> <span m=''4036060''>1 dB</span> <span m=''4036560''>of</span>
  <span m=''4036700''>the</span> <span m=''4036800''>Shannon</span> <span m=''4037130''>limit.</span>
  <span m=''4037790''>It gives</span> <span m=''4038080''>you</span> <span m=''4038470''>low
  error</span> <span m=''4038940''>probabilities</span> <span m=''4040080''>within</span>
  <span m=''4040680''>1 dB</span> <span m=''4040860''>of the</span> <span m=''4041010''>Shannon</span>
  <span m=''4041610''>limit.</span> </p><p><span m=''4041920''>So</span> <span m=''4042670''>maybe</span>
  <span m=''4043050''>there''s</span> <span m=''4043450''>another</span> <span m=''4043730''>way</span>
  <span m=''4043880''>to</span> <span m=''4043950''>go,</span> <span m=''4046350''>at</span>
  <span m=''4046750''>least</span> <span m=''4047010''>if</span> <span m=''4047130''>we''re</span>
  <span m=''4047290''>only</span> <span m=''4047490''>interested</span> <span m=''4048070''>in</span>
  <span m=''4049600''>a</span> <span m=''4050000''>certain</span> <span m=''4050400''>error</span>
  <span m=''4050660''>probability.</span> <span m=''4051360''>Maybe</span> <span m=''4051640''>it''s</span>
  <span m=''4051980''>10 to</span> <span m=''4052110''>the</span> <span m=''4052230''>minus</span>
  <span m=''4052540''>5.</span> <span m=''4052900''>Maybe</span> <span m=''4053000''>it''s
  10</span> <span m=''4053270''>to</span> <span m=''4053380''>the</span> <span m=''4053450''>minus</span>
  <span m=''4053760''>10.</span> <span m=''4054340''>But</span> <span m=''4054470''>it''s
  still</span> <span m=''4054670''>only</span> <span m=''4054990''>a</span> <span
  m=''4055040''>finite</span> <span m=''4055900''>error</span> <span m=''4056210''>probability.</span>
  <span m=''4057350''>Maybe</span> <span m=''4057440''>we</span> <span m=''4057570''>don''t</span>
  <span m=''4057700''>need</span> <span m=''4057950''>the</span> <span m=''4058080''>minimum</span>
  <span m=''4058390''>distance</span> <span m=''4058820''>to</span> <span m=''4058900''>go</span>
  <span m=''4059050''>to</span> <span m=''4059160''>infinity.</span> </p><p><span
  m=''4060900''>Maybe</span> <span m=''4061220''>we</span> <span m=''4061410''>can</span>
  <span m=''4061790''>get</span> <span m=''4062460''>by</span> <span m=''4065220''>sampling</span>
  <span m=''4066130''>codes</span> <span m=''4066490''>which</span> <span m=''4066710''>are</span>
  <span m=''4067200''>lousy in</span> <span m=''4067410''>classical</span> <span m=''4068020''>terms,</span>
  <span m=''4068420''>which</span> <span m=''4068660''>have</span> <span m=''4068730''>poor</span>
  <span m=''4069040''>minimum</span> <span m=''4069350''>distance.</span> <span m=''4071290''>Maybe</span>
  <span m=''4072050''>they''d</span> <span m=''4072470''>be</span> <span m=''4072610''>lousy</span>
  <span m=''4073160''>in</span> <span m=''4074330''>distance</span> <span m=''4074800''>terms,</span>
  <span m=''4075220''>or</span> <span m=''4075350''>in</span> <span m=''4075420''>nominal</span>
  <span m=''4075860''>coding</span> <span m=''4076180''>gain</span> <span m=''4076860''>terms,</span>
  <span m=''4077750''>but</span> <span m=''4078610''>they''ll</span> <span m=''4078920''>be</span>
  <span m=''4078940''>very</span> <span m=''4079150''>good</span> <span m=''4079500''>from</span>
  <span m=''4079600''>the</span> <span m=''4079710''>point</span> <span m=''4079930''>of</span>
  <span m=''4079980''>view of</span> <span m=''4080190''>complexity.</span> <span
  m=''4080840''>Maybe</span> <span m=''4081070''>there''s</span> <span m=''4081220''>some</span>
  <span m=''4081390''>trade-off</span> <span m=''4081920''>here.</span> <span m=''4082910''>We</span>
  <span m=''4083080''>know</span> <span m=''4083260''>the</span> <span m=''4083370''>code</span>
  <span m=''4083580''>is</span> <span m=''4083710''>going</span> <span m=''4083840''>to
  have to</span> <span m=''4083980''>be</span> <span m=''4084100''>long,</span> <span
  m=''4084710''>but</span> <span m=''4085030''>maybe</span> <span m=''4085240''>it
  doesn''t</span> <span m=''4085760''>have</span> <span m=''4085970''>to</span> <span
  m=''4086050''>have</span> <span m=''4086180''>large</span> <span m=''4086450''>distance.</span>
  <span m=''4086990''>Yeah.</span> </p><p><span m=''4087954''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''4091810''>That''s</span> <span m=''4092292''>what you</span> <span m=''4092774''>are
  saying,</span> <span m=''4093256''>isn''t it?</span> <span m=''4093750''>We try</span>
  <span m=''4094030''>to</span> <span m=''4094430''>maintain</span> <span m=''4094830''>the
  --</span> </p><p><span m=''4094980''>PROFESSOR: We</span> <span m=''4095100''>certainly</span>
  <span m=''4095500''>want</span> <span m=''4095660''>to</span> <span m=''4095820''>maintain</span>
  <span m=''4096350''>a</span> <span m=''4096410''>finite</span> <span m=''4096840''>rate.</span>
  <span m=''4100189''>This</span> <span m=''4100490''>was</span> <span m=''4100680''>the</span>
  <span m=''4100770''>problem</span> <span m=''4101090''>with</span> <span m=''4101250''>orthogonal</span>
  <span m=''4102000''>and</span> <span m=''4102130''>simplex</span> <span m=''4102630''>codes</span>
  <span m=''4102960''>and</span> <span m=''4103040''>so</span> <span m=''4103229''>forth,</span>
  <span m=''4103569''>is</span> <span m=''4103779''>that</span> <span m=''4103939''>the</span>
  <span m=''4104330''>rate</span> <span m=''4104620''>went</span> <span m=''4104810''>to</span>
  <span m=''4104910''>zero,</span> <span m=''4105500''>and</span> <span m=''4105670''>therefore</span>
  <span m=''4105990''>the</span> <span m=''4106109''>spectral</span> <span m=''4106520''>efficiency</span>
  <span m=''4107029''>went</span> <span m=''4107220''>to</span> <span m=''4107300''>zero.</span>
  <span m=''4108330''>In</span> <span m=''4108830''>practically</span> <span m=''4109600''>all</span>
  <span m=''4109770''>cases,</span> <span m=''4110180''>that''s</span> <span m=''4110390''>unacceptable.</span>
  <span m=''4111850''>So</span> <span m=''4112080''>we</span> <span m=''4112200''>need</span>
  <span m=''4112520''>to</span> <span m=''4112700''>maintain</span> <span m=''4115550''>some</span>
  <span m=''4115930''>minimal</span> <span m=''4116670''>rate</span> <span m=''4117100''>or</span>
  <span m=''4117240''>spectral</span> <span m=''4117689''>efficiency</span> <span
  m=''4118319''>on</span> <span m=''4118704''>the</span> <span m=''4119090''>additive</span>
  <span m=''4119279''>white</span> <span m=''4119479''>Gaussian</span> <span m=''4119890''>noise.</span>
  <span m=''4120859''>So</span> <span m=''4121540''>that</span> <span m=''4121810''>we</span>
  <span m=''4121950''>need,</span> <span m=''4122710''>but</span> <span m=''4123090''>this</span>
  <span m=''4123370''>maybe</span> <span m=''4123479''>we</span> <span m=''4123670''>don''t</span>
  <span m=''4123770''>need.</span> </p><p><span m=''4131350''>So</span> <span m=''4133170''>that''s</span>
  <span m=''4133430''>just</span> <span m=''4133790''>a</span> <span m=''4134290''>interesting</span>
  <span m=''4134930''>little</span> <span m=''4135359''>bit</span> <span m=''4135810''>of</span>
  <span m=''4136510''>philosophy</span> <span m=''4137100''>we</span> <span m=''4137240''>can</span>
  <span m=''4137370''>do</span> <span m=''4137540''>at</span> <span m=''4137649''>this</span>
  <span m=''4137859''>point,</span> <span m=''4138370''>is</span> <span m=''4138810''>how</span>
  <span m=''4139010''>should</span> <span m=''4139319''>you</span> <span m=''4139439''>really</span>
  <span m=''4139700''>design</span> <span m=''4140810''>capacity-achieving</span>
  <span m=''4141880''>codes?</span> <span m=''4142390''>And</span> <span m=''4142649''>this</span>
  <span m=''4143810''>seems</span> <span m=''4144170''>to</span> <span m=''4144260''>be</span>
  <span m=''4144380''>a</span> <span m=''4144460''>clue</span> <span m=''4144870''>to</span>
  <span m=''4145040''>the</span> <span m=''4145149''>way</span> <span m=''4145859''>to</span>
  <span m=''4146350''>go</span> <span m=''4146670''>that</span> <span m=''4146890''>has</span>
  <span m=''4147080''>in</span> <span m=''4147229''>fact</span> <span m=''4147630''>proved</span>
  <span m=''4147960''>to</span> <span m=''4148090''>be</span> <span m=''4149200''>good.</span>
  </p><p><span m=''4150580''>However,</span> <span m=''4151000''>I</span> <span m=''4151050''>should</span>
  <span m=''4151290''>add</span> <span m=''4151569''>that</span> <span m=''4151740''>not</span>
  <span m=''4151939''>all</span> <span m=''4153140''>capacity-approaching</span> <span
  m=''4154200''>codes</span> <span m=''4155000''>have</span> <span m=''4155229''>this</span>
  <span m=''4155450''>property.</span> <span m=''4157770''>A</span> <span m=''4157850''>random</span>
  <span m=''4158229''>low-density</span> <span m=''4158890''>parity</span> <span m=''4159270''>check</span>
  <span m=''4159569''>code</span> <span m=''4159960''>is</span> <span m=''4160140''>going</span>
  <span m=''4160250''>to</span> <span m=''4160300''>have</span> <span m=''4160479''>both</span>
  <span m=''4160720''>low</span> <span m=''4160950''>complexity</span> <span m=''4161840''>and</span>
  <span m=''4162160''>a</span> <span m=''4162569''>very</span> <span m=''4162810''>good</span>
  <span m=''4163040''>minimum</span> <span m=''4163380''>distance</span> <span m=''4164979''>as</span>
  <span m=''4165200''>well.</span> <span m=''4165580''>So</span> <span m=''4167700''>this</span>
  <span m=''4167899''>certainly</span> <span m=''4169140''>isn''t</span> <span m=''4169490''>the</span>
  <span m=''4170010''>full</span> <span m=''4170250''>story.</span> </p><p><span m=''4176490''>There
  are</span> <span m=''4178620''>just</span> <span m=''4179060''>two</span> <span
  m=''4179290''>more</span> <span m=''4180729''>topics</span> <span m=''4181359''>in</span>
  <span m=''4181500''>chapter</span> <span m=''4182010''>10,</span> <span m=''4183160''>and</span>
  <span m=''4183450''>maybe</span> <span m=''4183800''>I''ll</span> <span m=''4183939''>discuss</span>
  <span m=''4184430''>them</span> <span m=''4184529''>both</span> <span m=''4185050''>briefly</span>
  <span m=''4185510''>right</span> <span m=''4185850''>now.</span> <span m=''4189029''>One</span>
  <span m=''4189290''>is</span> <span m=''4189550''>I</span> <span m=''4189680''>skipped</span>
  <span m=''4190180''>over</span> <span m=''4191560''>projections.</span> <span m=''4197360''>And</span>
  <span m=''4198370''>how</span> <span m=''4198580''>shall I</span> <span m=''4198840''>introduce</span>
  <span m=''4199340''>this</span> <span m=''4199450''>subject?</span> </p><p><span
  m=''4200730''>I</span> <span m=''4200830''>talked</span> <span m=''4201220''>about</span>
  <span m=''4203270''>the</span> <span m=''4203380''>subcode</span> <span m=''4204540''>of,</span>
  <span m=''4204790''>say,</span> <span m=''4205130''>this</span> <span m=''4205440''>code,</span>
  <span m=''4205930''>which</span> <span m=''4206130''>is</span> <span m=''4206590''>pretty</span>
  <span m=''4206910''>badly</span> <span m=''4207290''>marked-up</span> <span m=''4207850''>by</span>
  <span m=''4208000''>now,</span> <span m=''4208280''>but</span> <span m=''4208480''>let
  me</span> <span m=''4208680''>keep</span> <span m=''4208900''>using</span> <span
  m=''4209280''>it.</span> <span m=''4211860''>I</span> <span m=''4211930''>talked</span>
  <span m=''4212260''>about</span> <span m=''4212400''>the</span> <span m=''4213260''>subcode</span>
  <span m=''4213920''>that''s</span> <span m=''4214090''>supported,</span> <span m=''4214660''>say,</span>
  <span m=''4215000''>on</span> <span m=''4215110''>the</span> <span m=''4215190''>first</span>
  <span m=''4215590''>half.</span> <span m=''4217270''>In</span> <span m=''4217390''>this</span>
  <span m=''4217620''>case</span> <span m=''4218020''>it''s</span> <span m=''4218830''>simply</span>
  <span m=''4219290''>the</span> <span m=''4219380''>subcode</span> <span m=''4219970''>that''s</span>
  <span m=''4220180''>generated</span> <span m=''4220670''>by</span> <span m=''4220830''>the</span>
  <span m=''4221060''>first</span> <span m=''4221300''>generator.</span> </p><p><span
  m=''4225100''>Here''s</span> <span m=''4225350''>another</span> <span m=''4228130''>code</span>
  <span m=''4228490''>that</span> <span m=''4228590''>we</span> <span m=''4228750''>can</span>
  <span m=''4228880''>look</span> <span m=''4229180''>at</span> <span m=''4229490''>that''s</span>
  <span m=''4229680''>kind</span> <span m=''4229870''>of</span> <span m=''4229940''>a</span>
  <span m=''4230000''>first</span> <span m=''4230420''>half</span> <span m=''4230710''>code.</span>
  <span m=''4231740''>Suppose</span> <span m=''4232170''>we</span> <span m=''4232300''>just</span>
  <span m=''4232910''>take</span> <span m=''4233440''>the</span> <span m=''4233540''>set</span>
  <span m=''4234000''>of</span> <span m=''4235940''>all</span> <span m=''4236270''>possible</span>
  <span m=''4236930''>first</span> <span m=''4237570''>four-tuples</span> <span m=''4238500''>in</span>
  <span m=''4238640''>this</span> <span m=''4238890''>code.</span> <span m=''4240100''>That''s</span>
  <span m=''4240310''>called</span> <span m=''4240580''>the</span> <span m=''4240630''>projection</span>
  <span m=''4241330''>onto</span> <span m=''4241620''>the</span> <span m=''4241720''>first</span>
  <span m=''4242100''>half.</span> <span m=''4243680''>In</span> <span m=''4244100''>other</span>
  <span m=''4244220''>words,</span> <span m=''4244350''>what</span> <span m=''4244530''>are</span>
  <span m=''4245050''>the</span> <span m=''4245260''>set</span> <span m=''4245490''>of</span>
  <span m=''4245590''>all</span> <span m=''4245820''>possible</span> <span m=''4246310''>four-tuples?</span>
  <span m=''4247900''>They''re</span> <span m=''4248320''>the</span> <span m=''4248600''>set
  of</span> <span m=''4252390''>code</span> <span m=''4252680''>words</span> <span
  m=''4253120''>that</span> <span m=''4253240''>are</span> <span m=''4253370''>generated</span>
  <span m=''4254100''>by</span> <span m=''4256690''>1,</span> <span m=''4256870''>1,</span>
  <span m=''4257080''>1,</span> <span m=''4257260''>1,</span> <span m=''4257750''>0,</span>
  <span m=''4258060''>1,</span> <span m=''4258280''>0,</span> <span m=''4258390''>1,</span>
  <span m=''4259570''>0,</span> <span m=''4259940''>0,</span> <span m=''4260330''>1,</span>
  <span m=''4260610''>1,</span> <span m=''4261720''>and</span> <span m=''4262060''>this</span>
  <span m=''4262260''>doesn''t</span> <span m=''4262580''>contribute</span> <span
  m=''4262960''>anything.</span> </p><p><span m=''4264050''>So</span> <span m=''4265130''>it''s</span>
  <span m=''4265310''>a</span> <span m=''4265380''>linear</span> <span m=''4265810''>code.</span>
  <span m=''4267870''>It''s</span> <span m=''4268290''>length</span> <span m=''4268620''>4.</span>
  <span m=''4270220''>It</span> <span m=''4270400''>has</span> <span m=''4270800''>three</span>
  <span m=''4271060''>generators,</span> <span m=''4271800''>dimension</span> <span
  m=''4272280''>3.</span> <span m=''4273550''>And</span> <span m=''4273980''>we</span>
  <span m=''4274220''>can</span> <span m=''4275330''>quickly</span> <span m=''4275670''>convince</span>
  <span m=''4276120''>ourselves</span> <span m=''4276720''>that</span> <span m=''4276900''>it''s</span>
  <span m=''4277080''>the</span> <span m=''4277350''>even</span> <span m=''4277560''>weight,</span>
  <span m=''4278050''>or</span> <span m=''4278300''>zero</span> <span m=''4278620''>sum,</span>
  <span m=''4279050''>or</span> <span m=''4279170''>a</span> <span m=''4279230''>single</span>
  <span m=''4279550''>parity</span> <span m=''4279880''>check</span> <span m=''4280220''>code</span>
  <span m=''4280850''>of</span> <span m=''4281000''>length</span> <span m=''4281260''>4.</span>
  <span m=''4283070''>So</span> <span m=''4283260''>if</span> <span m=''4283500''>we</span>
  <span m=''4283620''>project</span> <span m=''4284150''>this</span> <span m=''4284590''>on
  to</span> <span m=''4284660''>the</span> <span m=''4285580''>first</span> <span
  m=''4286020''>half,</span> <span m=''4286390''>we</span> <span m=''4286520''>get</span>
  <span m=''4287220''>a</span> <span m=''4287300''>4,</span> <span m=''4287550''>3,</span>
  <span m=''4287860''>2</span> <span m=''4288120''>code.</span> </p><p><span m=''4290390''>So</span>
  <span m=''4290540''>that''s</span> <span m=''4290770''>what</span> <span m=''4290880''>I</span>
  <span m=''4290920''>mean</span> <span m=''4291200''>by</span> <span m=''4291390''>a</span>
  <span m=''4291460''>projection.</span> <span m=''4293900''>If</span> <span m=''4294100''>I</span>
  <span m=''4294190''>project</span> <span m=''4294525''>on</span> <span m=''4294860''>to</span>
  <span m=''4295210''>here,</span> <span m=''4295720''>I</span> <span m=''4295820''>get</span>
  <span m=''4296060''>the</span> <span m=''4296150''>1</span> <span m=''4296440''>0</span>
  <span m=''4296770''>code.</span> <span m=''4298850''>I''m</span> <span m=''4299020''>sorry,</span>
  <span m=''4299300''>I</span> <span m=''4299350''>get</span> <span m=''4299550''>the</span>
  <span m=''4299920''>universe</span> <span m=''4300420''>code</span> <span m=''4300610''>of</span>
  <span m=''4300720''>length</span> <span m=''4301040''>1,</span> <span m=''4301340''>all</span>
  <span m=''4301660''>one-tuples.</span> <span m=''4302820''>On</span> <span m=''4303010''>here</span>
  <span m=''4303280''>I</span> <span m=''4303330''>get</span> <span m=''4303510''>all</span>
  <span m=''4303760''>two-tuples.</span> <span m=''4304630''>On</span> <span m=''4305020''>here</span>
  <span m=''4305270''>I</span> <span m=''4305330''>get</span> <span m=''4305520''>all</span>
  <span m=''4305710''>three-tuples.</span> <span m=''4306800''>But</span> <span m=''4307050''>on
  here</span> <span m=''4307280''>I</span> <span m=''4307340''>don''t</span> <span
  m=''4307600''>get</span> <span m=''4307720''>all</span> <span m=''4307930''>four-tuples.</span>
  <span m=''4308740''>I</span> <span m=''4308940''>get</span> <span m=''4309820''>a</span>
  <span m=''4309850''>single</span> <span m=''4310160''>parity</span> <span m=''4310540''>check</span>
  <span m=''4310860''>code.</span> <span m=''4311820''>So</span> <span m=''4312480''>those</span>
  <span m=''4312720''>are</span> <span m=''4312770''>my</span> <span m=''4312930''>projections.</span>
  </p><p><span m=''4316120''>Some</span> <span m=''4316440''>things</span> <span m=''4316950''>can</span>
  <span m=''4317130''>be</span> <span m=''4317320''>done</span> <span m=''4317600''>nicely</span>
  <span m=''4318050''>in</span> <span m=''4318180''>terms</span> <span m=''4318490''>of</span>
  <span m=''4318570''>projections.</span> <span m=''4319260''>Projections</span> <span
  m=''4319960''>are</span> <span m=''4320040''>kind</span> <span m=''4320250''>of
  the</span> <span m=''4320460''>dual</span> <span m=''4321020''>to</span> <span m=''4321170''>subcodes.</span>
  <span m=''4322550''>In</span> <span m=''4322770''>fact,</span> <span m=''4323530''>you</span>
  <span m=''4324150''>prove</span> <span m=''4324460''>this</span> <span m=''4324750''>on</span>
  <span m=''4324860''>the</span> <span m=''4324940''>homework</span> <span m=''4325400''>in</span>
  <span m=''4325480''>the</span> <span m=''4325590''>course</span> <span m=''4325980''>of</span>
  <span m=''4326090''>proving</span> <span m=''4326450''>the</span> <span m=''4326550''>dual</span>
  <span m=''4327210''>state</span> <span m=''4327660''>space</span> <span m=''4327980''>theorem.</span>
  <span m=''4328990''>In</span> <span m=''4329030''>other</span> <span m=''4329200''>words,</span>
  <span m=''4330370''>the</span> <span m=''4331410''>dual</span> <span m=''4333140''>of</span>
  <span m=''4333370''>a</span> <span m=''4333420''>subcode</span> <span m=''4336170''>of</span>
  <span m=''4336490''>a</span> <span m=''4336620''>code</span> <span m=''4337150''>C</span>
  <span m=''4337960''>is</span> <span m=''4338310''>the</span> <span m=''4338720''>projection</span>
  <span m=''4339900''>of</span> <span m=''4340060''>the</span> <span m=''4340140''>dual</span>
  <span m=''4340450''>code</span> <span m=''4340805''>of</span> <span m=''4341160''>C,</span>
  <span m=''4342410''>and</span> <span m=''4342580''>vice</span> <span m=''4342840''>versa.</span>
  <span m=''4344840''>They''re</span> <span m=''4345000''>always</span> <span m=''4345410''>tongue</span>
  <span m=''4345660''>twisters,</span> <span m=''4346260''>the</span> <span m=''4346590''>duality</span>
  <span m=''4347170''>theorem.</span> <span m=''4349450''>But</span> <span m=''4349630''>that''s</span>
  <span m=''4349920''>what</span> <span m=''4350220''>you</span> <span m=''4350430''>will
  prove</span> <span m=''4350920''>along</span> <span m=''4351150''>the way.</span>
  </p><p><span m=''4351380''>Let</span> <span m=''4351520''>me</span> <span m=''4353140''>give</span>
  <span m=''4353350''>you</span> <span m=''4355630''>the</span> <span m=''4355740''>relevance</span>
  <span m=''4356220''>of</span> <span m=''4356280''>this</span> <span m=''4356550''>to</span>
  <span m=''4356660''>the</span> <span m=''4356760''>state</span> <span m=''4357130''>space</span>
  <span m=''4357590''>theorem.</span> <span m=''4360950''>So</span> <span m=''4361360''>I</span>
  <span m=''4361610''>had</span> <span m=''4361900''>the</span> <span m=''4361970''>state</span>
  <span m=''4362370''>space</span> <span m=''4362660''>theorem</span> <span m=''4362910''>right</span>
  <span m=''4363140''>here.</span> <span m=''4363540''>So</span> <span m=''4364220''>let</span>
  <span m=''4364650''>me</span> <span m=''4364790''>leave</span> <span m=''4365010''>it
  up.</span> </p><p><span m=''4372350''>State</span> <span m=''4372830''>space</span>
  <span m=''4373140''>theorem</span> <span m=''4373540''>is</span> <span m=''4373770''>based</span>
  <span m=''4374200''>on --</span> <span m=''4376720''>in</span> <span m=''4376910''>general,</span>
  <span m=''4380600''>we</span> <span m=''4380770''>divide</span> <span m=''4382070''>the</span>
  <span m=''4382330''>generator</span> <span m=''4382850''>matrix</span> <span m=''4383530''>g</span>
  <span m=''4383720''>prime</span> <span m=''4385220''>into</span> <span m=''4385890''>a</span>
  <span m=''4386090''>part</span> <span m=''4387620''>that</span> <span m=''4388330''>is</span>
  <span m=''4388810''>a</span> <span m=''4388880''>generator</span> <span m=''4389540''>for</span>
  <span m=''4389720''>the</span> <span m=''4389850''>past</span> <span m=''4390270''>subcode</span>
  <span m=''4392440''>0.</span> <span m=''4397480''>0</span> <span m=''4398140''>generator</span>
  <span m=''4398770''>for</span> <span m=''4398950''>the</span> <span m=''4399080''>future</span>
  <span m=''4399380''>subcode.</span> <span m=''4401190''>And</span> <span m=''4401510''>then</span>
  <span m=''4403040''>some</span> <span m=''4403300''>stuff</span> <span m=''4403820''>down</span>
  <span m=''4404110''>here,</span> <span m=''4404360''>which</span> <span m=''4404620''>is</span>
  <span m=''4405010''>generators</span> <span m=''4405780''>of</span> <span m=''4406090''>the</span>
  <span m=''4406180''>state</span> <span m=''4406520''>space</span> <span m=''4406970''>code.</span>
  </p><p><span m=''4412640''>By</span> <span m=''4412960''>construction</span> <span
  m=''4413790''>here,</span> <span m=''4416960''>the</span> <span m=''4418540''>projections</span>
  <span m=''4419570''>of</span> <span m=''4419710''>any</span> <span m=''4419960''>nonzero</span>
  <span m=''4421350''>vector</span> <span m=''4422250''>in</span> <span m=''4422370''>the</span>
  <span m=''4423140''>state</span> <span m=''4423530''>space</span> <span m=''4423920''>code</span>
  <span m=''4424570''>are</span> <span m=''4424740''>nonzero.</span> <span m=''4426640''>If</span>
  <span m=''4426780''>they</span> <span m=''4426910''>were</span> <span m=''4427040''>zero,</span>
  <span m=''4429290''>any</span> <span m=''4430180''>nonzero</span> <span m=''4430910''>linear</span>
  <span m=''4431270''>combination</span> <span m=''4432010''>of</span> <span m=''4432090''>these</span>
  <span m=''4432370''>generators</span> <span m=''4432765''>down</span> <span m=''4433160''>here</span>
  <span m=''4433400''>cannot</span> <span m=''4433800''>be</span> <span m=''4433920''>zero</span>
  <span m=''4435380''>on</span> <span m=''4435610''>here.</span> </p><p><span m=''4440850''>So</span>
  <span m=''4441560''>the</span> <span m=''4441770''>projection</span> <span m=''4443530''>on</span>
  <span m=''4443790''>to</span> <span m=''4443920''>the</span> <span m=''4444040''>first</span>
  <span m=''4444470''>half</span> <span m=''4444830''>here,</span> <span m=''4445770''>the</span>
  <span m=''4445870''>dimension</span> <span m=''4446450''>of</span> <span m=''4446590''>the</span>
  <span m=''4446670''>projection --</span> <span m=''4448460''>I''m</span> <span m=''4448850''>making</span>
  <span m=''4449140''>a</span> <span m=''4449210''>slight</span> <span m=''4449570''>skip</span>
  <span m=''4449880''>here --</span> <span m=''4450120''>is</span> <span m=''4450290''>basically</span>
  <span m=''4451070''>equal</span> <span m=''4451570''>to</span> <span m=''4451770''>the</span>
  <span m=''4451960''>dimension</span> <span m=''4452670''>of</span> <span m=''4452790''>the</span>
  <span m=''4452890''>past</span> <span m=''4453440''>subspace</span> <span m=''4454100''>code</span>
  <span m=''4454810''>plus</span> <span m=''4455090''>the</span> <span m=''4455180''>dimension</span>
  <span m=''4455640''>of</span> <span m=''4455740''>the</span> <span m=''4456320''>state</span>
  <span m=''4456740''>code.</span> <span m=''4457990''>It''s</span> <span m=''4458180''>basically</span>
  <span m=''4458550''>generated</span> <span m=''4459020''>by</span> <span m=''4459160''>these</span>
  <span m=''4459470''>generators</span> <span m=''4460150''>and</span> <span m=''4460320''>these</span>
  <span m=''4460620''>generators</span> <span m=''4461530''>projected</span> <span
  m=''4462000''>onto</span> <span m=''4462230''>here.</span> <span m=''4462810''>We</span>
  <span m=''4462970''>can</span> <span m=''4463060''>forget</span> <span m=''4463430''>about</span>
  <span m=''4463720''>these</span> <span m=''4463940''>generators.</span> </p><p><span
  m=''4466190''>So</span> <span m=''4466450''>let</span> <span m=''4466570''>me</span>
  <span m=''4466680''>write</span> <span m=''4466980''>that</span> <span m=''4467250''>down.</span>
  <span m=''4469040''>The</span> <span m=''4470220''>dimension</span> <span m=''4471360''>of</span>
  <span m=''4471460''>C</span> <span m=''4472090''>projected</span> <span m=''4472730''>onto</span>
  <span m=''4473000''>the</span> <span m=''4473120''>past</span> <span m=''4474340''>is</span>
  <span m=''4474630''>equal</span> <span m=''4476130''>to</span> <span m=''4476830''>the</span>
  <span m=''4476930''>dimension</span> <span m=''4477780''>of</span> <span m=''4477940''>the</span>
  <span m=''4478270''>past</span> <span m=''4478810''>subcode</span> <span m=''4479980''>plus</span>
  <span m=''4480350''>the</span> <span m=''4480450''>dimension</span> <span m=''4482100''>of</span>
  <span m=''4482220''>the</span> <span m=''4482300''>state</span> <span m=''4482660''>space</span>
  <span m=''4483080''>code.</span> <span m=''4488450''>Which</span> <span m=''4490950''>leads</span>
  <span m=''4491300''>to</span> <span m=''4491410''>another</span> <span m=''4491710''>version</span>
  <span m=''4492240''>of</span> <span m=''4492460''>the</span> <span m=''4493460''>state</span>
  <span m=''4493840''>space</span> <span m=''4494260''>theorem.</span> <span m=''4494790''>I</span>
  <span m=''4494910''>could</span> <span m=''4495160''>simply</span> <span m=''4495480''>write</span>
  <span m=''4495900''>state</span> <span m=''4496340''>space</span> <span m=''4496650''>theorem</span>
  <span m=''4497460''>as</span> <span m=''4497920''>dimension</span> <span m=''4498235''>of
  the</span> <span m=''4498550''>state</span> <span m=''4498930''>space at</span>
  <span m=''4499370''>time</span> <span m=''4499710''>k</span> <span m=''4500030''>is</span>
  <span m=''4500180''>simply</span> <span m=''4500490''>the</span> <span m=''4500620''>difference</span>
  <span m=''4501720''>between</span> <span m=''4502090''>the</span> <span m=''4502170''>dimension</span>
  <span m=''4502950''>of</span> <span m=''4503070''>the</span> <span m=''4504040''>projection,</span>
  <span m=''4505620''>C</span> <span m=''4505970''>projected</span> <span m=''4506560''>on</span>
  <span m=''4506660''>the</span> <span m=''4506770''>past,</span> <span m=''4507370''>minus</span>
  <span m=''4507860''>the</span> <span m=''4507980''>dimension</span> <span m=''4509100''>of</span>
  <span m=''4509270''>the</span> <span m=''4509320''>subcode.</span> <span m=''4512210''>It''s</span>
  <span m=''4512940''>all of</span> <span m=''4513290''>these</span> <span m=''4513570''>guys</span>
  <span m=''4513970''>minus</span> <span m=''4514360''>these</span> <span m=''4514740''>guys.</span>
  </p><p><span m=''4517730''>And</span> <span m=''4517920''>again,</span> <span m=''4518210''>if</span>
  <span m=''4518330''>we</span> <span m=''4518420''>look</span> <span m=''4518630''>back</span>
  <span m=''4518900''>here,</span> <span m=''4520360''>we</span> <span m=''4520710''>see</span>
  <span m=''4520990''>we</span> <span m=''4521190''>have</span> <span m=''4521440''>the</span>
  <span m=''4521550''>4,</span> <span m=''4521880''>3</span> <span m=''4522260''>code</span>
  <span m=''4523490''>is</span> <span m=''4524270''>C</span> <span m=''4524720''>projected</span>
  <span m=''4525300''>on</span> <span m=''4525510''>p,</span> <span m=''4526680''>4,</span>
  <span m=''4526930''>3,</span> <span m=''4527250''>2,</span> <span m=''4527820''>and</span>
  <span m=''4528120''>C --</span> <span m=''4530080''>the</span> <span m=''4530180''>subcode</span>
  <span m=''4530620''>is</span> <span m=''4531040''>4,</span> <span m=''4531360''>1,</span>
  <span m=''4531650''>4.</span> <span m=''4532870''>In</span> <span m=''4533260''>fact,</span>
  <span m=''4533600''>for</span> <span m=''4533730''>this,</span> <span m=''4534120''>these</span>
  <span m=''4534380''>are</span> <span m=''4534470''>both</span> <span m=''4535900''>Reed-Muller</span>
  <span m=''4536420''>codes</span> <span m=''4536800''>of</span> <span m=''4536890''>half</span>
  <span m=''4537090''>the</span> <span m=''4537300''>length.</span> <span m=''4538100''>This</span>
  <span m=''4538280''>is</span> <span m=''4538440''>not an</span> <span m=''4538710''>accident,</span>
  <span m=''4539380''>as</span> <span m=''4539470''>you</span> <span m=''4539620''>will
  prove</span> <span m=''4540090''>in the</span> <span m=''4540310''>homework.</span>
  </p><p><span m=''4542420''>The</span> <span m=''4542520''>state</span> <span m=''4542930''>space</span>
  <span m=''4543130''>size</span> <span m=''4543750''>is</span> <span m=''4543950''>the</span>
  <span m=''4544050''>difference</span> <span m=''4544510''>in</span> <span m=''4544590''>the</span>
  <span m=''4544680''>dimensions</span> <span m=''4545340''>of</span> <span m=''4545410''>these</span>
  <span m=''4545660''>two</span> <span m=''4545790''>codes.</span> <span m=''4546290''>This</span>
  <span m=''4546580''>is a</span> <span m=''4546730''>very</span> <span m=''4546970''>handy</span>
  <span m=''4547340''>thing</span> <span m=''4547870''>to</span> <span m=''4548110''>know,</span>
  <span m=''4549130''>and</span> <span m=''4549310''>you''re</span> <span m=''4549420''>going</span>
  <span m=''4549530''>to</span> <span m=''4549860''>need</span> <span m=''4550110''>this.</span>
  <span m=''4551690''>This,</span> <span m=''4551910''>for instance,</span> <span
  m=''4552360''>will</span> <span m=''4552520''>give</span> <span m=''4552770''>you</span>
  <span m=''4553140''>that</span> <span m=''4553440''>in</span> <span m=''4553640''>general</span>
  <span m=''4554050''>for</span> <span m=''4554230''>Reed-Muller</span> <span m=''4555310''>codes,</span>
  <span m=''4555830''>if</span> <span m=''4555990''>you</span> <span m=''4556170''>divide</span>
  <span m=''4556600''>them</span> <span m=''4556680''>in</span> <span m=''4556800''>half
  --</span> <span m=''4559330''>we</span> <span m=''4559480''>had</span> <span m=''4559700''>this</span>
  <span m=''4559980''>general</span> <span m=''4562070''>picture</span> <span m=''4563210''>of</span>
  <span m=''4563310''>say</span> <span m=''4563630''>the</span> <span m=''4563830''>8</span>
  <span m=''4564050''>4</span> <span m=''4564400''>code</span> <span m=''4565390''>being</span>
  <span m=''4565710''>made</span> <span m=''4566020''>up</span> <span m=''4566570''>by</span>
  <span m=''4566750''>the</span> <span m=''4566860''>new</span> <span m=''4567110''>u</span>
  <span m=''4567320''>plus</span> <span m=''4567670''>v</span> <span m=''4567930''>construction.</span>
  <span m=''4569330''>These</span> <span m=''4569640''>two</span> <span m=''4569840''>together</span>
  <span m=''4570840''>make</span> <span m=''4571330''>the</span> <span m=''4571570''>8,</span>
  <span m=''4571850''>4,</span> <span m=''4572180''>4</span> <span m=''4572560''>code.</span>
  </p><p><span m=''4575190''>If</span> <span m=''4575350''>you</span> <span m=''4578820''>have</span>
  <span m=''4579040''>the</span> <span m=''4579160''>u</span> <span m=''4580500''>u</span>
  <span m=''4580700''>plus</span> <span m=''4581060''>v</span> <span m=''4581280''>construction,</span>
  <span m=''4582020''>there</span> <span m=''4582200''>you</span> <span m=''4582320''>are,</span>
  <span m=''4582560''>first</span> <span m=''4582990''>half,</span> <span m=''4583230''>second</span>
  <span m=''4583640''>half.</span> <span m=''4584750''>You will</span> <span m=''4585000''>find</span>
  <span m=''4585420''>that</span> <span m=''4585650''>the</span> <span m=''4586010''>projection</span>
  <span m=''4586600''>on</span> <span m=''4586710''>the</span> <span m=''4586800''>first</span>
  <span m=''4587230''>half</span> <span m=''4587560''>is</span> <span m=''4587980''>always</span>
  <span m=''4588540''>this</span> <span m=''4588830''>guy,</span> <span m=''4590000''>which</span>
  <span m=''4590710''>is</span> <span m=''4591100''>the</span> <span m=''4591220''>u</span>
  <span m=''4591470''>code.</span> <span m=''4592700''>And</span> <span m=''4594590''>the</span>
  <span m=''4594790''>subcode</span> <span m=''4595560''>is</span> <span m=''4595810''>v</span>
  <span m=''4596150''>code,</span> <span m=''4597620''>which</span> <span m=''4597770''>is</span>
  <span m=''4597910''>the</span> <span m=''4598010''>homework.</span> <span m=''4598530''>And</span>
  <span m=''4598910''>so</span> <span m=''4599590''>you</span> <span m=''4599720''>can</span>
  <span m=''4599860''>quickly</span> <span m=''4600280''>read</span> <span m=''4600560''>off</span>
  <span m=''4600840''>from</span> <span m=''4601040''>this</span> <span m=''4601350''>what</span>
  <span m=''4601580''>the</span> <span m=''4601670''>dimension</span> <span m=''4602180''>of</span>
  <span m=''4602260''>the</span> <span m=''4602350''>central</span> <span m=''4603600''>state</span>
  <span m=''4603990''>space</span> <span m=''4604340''>is</span> <span m=''4605160''>for</span>
  <span m=''4606085''>Reed-Muller</span> <span m=''4606790''>codes.</span> <span m=''4607290''>In</span>
  <span m=''4607580''>this</span> <span m=''4607800''>case</span> <span m=''4608100''>it''s</span>
  <span m=''4608310''>2.</span> </p><p><span m=''4609135''>But</span> <span m=''4609520''>for</span>
  <span m=''4609700''>instance</span> <span m=''4610060''>if</span> <span m=''4610210''>we</span>
  <span m=''4610330''>have</span> <span m=''4610585''>the</span> <span m=''4610840''>32,</span>
  <span m=''4612110''>16,</span> <span m=''4613040''>8</span> <span m=''4613370''>code,</span>
  <span m=''4615850''>then</span> <span m=''4617200''>what</span> <span m=''4617400''>is</span>
  <span m=''4617540''>that</span> <span m=''4617720''>made</span> <span m=''4617940''>up</span>
  <span m=''4618120''>of?</span> <span m=''4618470''>That''s</span> <span m=''4618810''>made</span>
  <span m=''4619030''>up</span> <span m=''4619200''>from</span> <span m=''4619440''>the</span>
  <span m=''4619540''>16,</span> <span m=''4620310''>11,</span> <span m=''4621800''>4</span>
  <span m=''4622230''>code</span> <span m=''4622830''>and</span> <span m=''4623030''>the</span>
  <span m=''4623240''>16,</span> <span m=''4624550''>5,</span> <span m=''4625390''>8</span>
  <span m=''4625740''>code.</span> <span m=''4626720''>And</span> <span m=''4627120''>so</span>
  <span m=''4627350''>we can</span> <span m=''4627570''>see</span> <span m=''4627840''>the</span>
  <span m=''4627930''>dimension</span> <span m=''4628390''>of</span> <span m=''4628430''>the</span>
  <span m=''4628510''>central</span> <span m=''4628940''>state</span> <span m=''4629320''>space</span>
  <span m=''4629710''>here</span> <span m=''4629930''>is</span> <span m=''4630060''>going</span>
  <span m=''4630160''>to</span> <span m=''4630270''>be</span> <span m=''4630380''>6.</span>
  <span m=''4631540''>We''re</span> <span m=''4631960''>going to get a</span> <span
  m=''4632300''>64-state</span> <span m=''4634010''>trellis</span> <span m=''4634260''>for</span>
  <span m=''4634500''>this</span> <span m=''4634780''>code,</span> <span m=''4635070''>at</span>
  <span m=''4635260''>least</span> <span m=''4635450''>just</span> <span m=''4636640''>measuring</span>
  <span m=''4636960''>the</span> <span m=''4637040''>size</span> <span m=''4637460''>of</span>
  <span m=''4637510''>the</span> <span m=''4637610''>central</span> <span m=''4637970''>state</span>
  <span m=''4638360''>space.</span> </p><p><span m=''4640230''>Now</span> <span m=''4640710''>it</span>
  <span m=''4640920''>turns</span> <span m=''4641250''>out</span> <span m=''4641480''>you</span>
  <span m=''4641760''>can</span> <span m=''4643570''>keep</span> <span m=''4643950''>having
  --</span> <span m=''4644590''>if</span> <span m=''4644710''>you</span> <span m=''4644850''>go</span>
  <span m=''4645090''>down</span> <span m=''4645510''>and you</span> <span m=''4645630''>make</span>
  <span m=''4645900''>four</span> <span m=''4646900''>cuts</span> <span m=''4647310''>here,</span>
  <span m=''4648150''>then</span> <span m=''4648320''>the</span> <span m=''4648400''>relevant</span>
  <span m=''4648890''>codes</span> <span m=''4649460''>are</span> <span m=''4649690''>what</span>
  <span m=''4649880''>you</span> <span m=''4650020''>get</span> <span m=''4650930''>one</span>
  <span m=''4651200''>more</span> <span m=''4652110''>space</span> <span m=''4652650''>back.</span>
  <span m=''4653130''>At</span> <span m=''4653260''>this</span> <span m=''4653500''>space,</span>
  <span m=''4653910''>we</span> <span m=''4654040''>have</span> <span m=''4654210''>the</span>
  <span m=''4654340''>2,</span> <span m=''4654590''>2,</span> <span m=''4654840''>1</span>
  <span m=''4655680''>as</span> <span m=''4655860''>the</span> <span m=''4655950''>projected</span>
  <span m=''4656560''>code,</span> <span m=''4657390''>and</span> <span m=''4657610''>the</span>
  <span m=''4657720''>2,</span> <span m=''4657950''>0,</span> <span m=''4658440''>infinity</span>
  <span m=''4659510''>as</span> <span m=''4659710''>the</span> <span m=''4659800''>subcode.</span>
  <span m=''4661080''>And</span> <span m=''4661240''>again,</span> <span m=''4661570''>the</span>
  <span m=''4661670''>difference</span> <span m=''4662100''>in</span> <span m=''4662190''>dimensions</span>
  <span m=''4662840''>here</span> <span m=''4663230''>is</span> <span m=''4663380''>going</span>
  <span m=''4663460''>to</span> <span m=''4663540''>be</span> <span m=''4663620''>the</span>
  <span m=''4663710''>same</span> <span m=''4664080''>as</span> <span m=''4664230''>the</span>
  <span m=''4664290''>different</span> <span m=''4664710''>dimensions</span> <span
  m=''4665240''>here.</span> <span m=''4666780''>Minor</span> <span m=''4666960''>miracle</span>
  <span m=''4667560''>at</span> <span m=''4667850''>first.</span> <span m=''4668150''>It</span>
  <span m=''4668270''>turns</span> <span m=''4668550''>out</span> <span m=''4668740''>to</span>
  <span m=''4668830''>be</span> <span m=''4668930''>just</span> <span m=''4670440''>from</span>
  <span m=''4670740''>the</span> <span m=''4670860''>construction.</span> </p><p><span
  m=''4671630''>Here</span> <span m=''4672180''>we</span> <span m=''4672450''>go</span>
  <span m=''4672650''>back</span> <span m=''4673080''>to</span> <span m=''4673250''>the</span>
  <span m=''4673550''>8,</span> <span m=''4673960''>7,</span> <span m=''4675330''>2</span>
  <span m=''4675930''>and</span> <span m=''4676160''>the</span> <span m=''4676370''>8,</span>
  <span m=''4676780''>1,</span> <span m=''4677500''>8.</span> <span m=''4678010''>And</span>
  <span m=''4678210''>again</span> <span m=''4678470''>we</span> <span m=''4678570''>see</span>
  <span m=''4678760''>the</span> <span m=''4678870''>difference</span> <span m=''4679300''>here</span>
  <span m=''4679530''>is</span> <span m=''4679620''>6.</span> <span m=''4682110''>So
  that</span> <span m=''4682460''>means</span> <span m=''4682840''>that</span> <span
  m=''4683020''>Reed-Muller</span> <span m=''4683640''>codes</span> <span m=''4685280''>always</span>
  <span m=''4685720''>have</span> <span m=''4686940''>trellises,</span> <span m=''4688520''>least</span>
  <span m=''4688790''>if</span> <span m=''4688880''>you</span> <span m=''4688990''>put</span>
  <span m=''4689220''>them</span> <span m=''4689340''>in</span> <span m=''4689430''>four</span>
  <span m=''4689740''>sections.</span> <span m=''4691640''>They</span> <span m=''4691780''>always</span>
  <span m=''4692140''>look</span> <span m=''4692330''>like</span> <span m=''4692540''>this</span>
  <span m=''4694600''>abstractly.</span> <span m=''4696080''>They</span> <span m=''4696620''>look</span>
  <span m=''4696920''>like</span> <span m=''4699208''>what</span> <span m=''4699630''>we''ve</span>
  <span m=''4700090''>already</span> <span m=''4700330''>seen</span> <span m=''4700730''>for</span>
  <span m=''4700840''>the</span> <span m=''4700970''>8,</span> <span m=''4701130''>4,</span>
  <span m=''4701420''>4</span> <span m=''4701800''>code.</span> <span m=''4707080''>And</span>
  <span m=''4707230''>you''ll</span> <span m=''4707450''>do</span> <span m=''4707570''>this</span>
  <span m=''4707850''>on</span> <span m=''4707960''>the</span> <span m=''4708050''>homework</span>
  <span m=''4708640''>using</span> <span m=''4708940''>projections.</span> <span m=''4709700''>That''s</span>
  <span m=''4709960''>not</span> <span m=''4710180''>very</span> <span m=''4710380''>hard.</span>
  </p><p><span m=''4712440''>It</span> <span m=''4712560''>doesn''t</span> <span m=''4712890''>mean</span>
  <span m=''4713230''>that --</span> <span m=''4714510''>so</span> <span m=''4714790''>we</span>
  <span m=''4714930''>know,</span> <span m=''4715460''>for</span> <span m=''4715600''>instance,</span>
  <span m=''4715930''>for</span> <span m=''4716040''>the</span> <span m=''4716180''>32</span>
  <span m=''4716750''>16</span> <span m=''4717340''>8,</span> <span m=''4717640''>we''re</span>
  <span m=''4717720''>going</span> <span m=''4717820''>to</span> <span m=''4717860''>do</span>
  <span m=''4718050''>this,</span> <span m=''4718410''>and there are</span> <span
  m=''4718550''>going</span> <span m=''4718640''>to</span> <span m=''4718690''>be</span>
  <span m=''4718760''>64</span> <span m=''4719400''>states</span> <span m=''4719830''>here,</span>
  <span m=''4720510''>64</span> <span m=''4721140''>states</span> <span m=''4721560''>here,</span>
  <span m=''4721820''>64</span> <span m=''4722440''>states</span> <span m=''4722890''>here.</span>
  <span m=''4723680''>We</span> <span m=''4723810''>don''t</span> <span m=''4723970''>know</span>
  <span m=''4724090''>what</span> <span m=''4724240''>it''s</span> <span m=''4724400''>going</span>
  <span m=''4724520''>to</span> <span m=''4724580''>be</span> <span m=''4724700''>in</span>
  <span m=''4724810''>between,</span> <span m=''4725300''>but</span> <span m=''4725470''>you</span>
  <span m=''4725630''>can</span> <span m=''4725760''>figure</span> <span m=''4726310''>that</span>
  <span m=''4726530''>out</span> <span m=''4726790''>too.</span> <span m=''4728630''>In</span>
  <span m=''4728810''>fact,</span> <span m=''4729130''>we</span> <span m=''4729320''>get</span>
  <span m=''4729740''>a</span> <span m=''4730000''>minimal</span> <span m=''4730070''>trellis</span>
  <span m=''4730460''>for</span> <span m=''4730560''>the</span> <span m=''4730630''>whole</span>
  <span m=''4730890''>thing.</span> </p><p><span m=''4734310''>That''s</span> <span
  m=''4734590''>what</span> <span m=''4734720''>you</span> <span m=''4734830''>need</span>
  <span m=''4735120''>to</span> <span m=''4735210''>do</span> <span m=''4735380''>the</span>
  <span m=''4735490''>homework.</span> <span m=''4738880''>There are</span> <span
  m=''4739310''>actually</span> <span m=''4739800''>two</span> <span m=''4739980''>more</span>
  <span m=''4740220''>topics</span> <span m=''4740500''>that</span> <span m=''4740780''>I</span>
  <span m=''4740850''>want</span> <span m=''4741020''>to</span> <span m=''4741070''>do</span>
  <span m=''4741200''>in</span> <span m=''4741300''>Chapter</span> <span m=''4741760''>10.</span>
  <span m=''4742670''>One</span> <span m=''4742890''>is</span> <span m=''4743050''>the</span>
  <span m=''4743130''>Muder</span> <span m=''4743430''>bound.</span> <span m=''4745500''>And</span>
  <span m=''4745850''>one --</span> <span m=''4747320''>I</span> <span m=''4747430''>actually</span>
  <span m=''4747770''>want</span> <span m=''4747970''>to</span> <span m=''4748020''>see</span>
  <span m=''4749640''>how</span> <span m=''4749910''>good</span> <span m=''4750160''>are</span>
  <span m=''4750530''>these</span> <span m=''4750740''>block</span> <span m=''4751120''>code</span>
  <span m=''4751440''>trellises</span> <span m=''4752450''>vis-a-vis</span> <span
  m=''4753020''>convolutional</span> <span m=''4753240''>code</span> <span m=''4753630''>trellises.</span>
  <span m=''4755010''>So</span> <span m=''4755220''>I''ll do</span> <span m=''4755400''>both</span>
  <span m=''4755730''>of</span> <span m=''4755880''>those</span> <span m=''4756040''>at
  the</span> <span m=''4756090''>beginning</span> <span m=''4756460''>of</span> <span
  m=''4756540''>next</span> <span m=''4756870''>time.</span> </p><p><span m=''4758110''>For</span>
  <span m=''4759140''>homework</span> <span m=''4760630''>problem</span> <span m=''4760920''>set,</span>
  <span m=''4762570''>let''s</span> <span m=''4762820''>this</span> <span m=''4763090''>week</span>
  <span m=''4764610''>do</span> <span m=''4765030''>only the</span> <span m=''4765270''>first</span>
  <span m=''4765520''>four</span> <span m=''4765780''>problems.</span> <span m=''4768240''>So</span>
  <span m=''4768800''>for</span> <span m=''4772130''>this</span> <span m=''4772440''>Wednesday,</span>
  <span m=''4774020''>do</span> <span m=''4775040''>problem</span> <span m=''4775400''>set
  --</span> <span m=''4775760''>what</span> <span m=''4775940''>are</span> <span m=''4775990''>we</span>
  <span m=''4776090''>up</span> <span m=''4776260''>to?</span> <span m=''4776480''>Seven,</span>
  <span m=''4776950''>is</span> <span m=''4777090''>it?</span> <span m=''4779260''>One</span>
  <span m=''4779570''>through</span> <span m=''4779880''>four,</span> <span m=''4781490''>and</span>
  <span m=''4781850''>for</span> <span m=''4783800''>Wednesday,</span> <span m=''4784450''>4/20,</span>
  <span m=''4785610''>we''ll</span> <span m=''4785850''>do</span> <span m=''4786240''>problem</span>
  <span m=''4786760''>set</span> <span m=''4787180''>seven,</span> <span m=''4788630''>five</span>
  <span m=''4789030''>and</span> <span m=''4789150''>six,</span> <span m=''4789720''>plus</span>
  <span m=''4790760''>I''ll probably</span> <span m=''4790890''>have</span> <span
  m=''4791070''>another</span> <span m=''4791320''>one.</span> </p><p><span m=''4792150''>But</span>
  <span m=''4792270''>we</span> <span m=''4792430''>have</span> <span m=''4792680''>a</span>
  <span m=''4792920''>holiday</span> <span m=''4793360''>next</span> <span m=''4793700''>Monday</span>
  <span m=''4794200''>also</span> <span m=''4795105''>if</span> <span m=''4795370''>you</span>
  <span m=''4795460''>recall,</span> <span m=''4795990''>Patriots''</span> <span m=''4796530''>Day.</span>
  <span m=''4798520''>So</span> <span m=''4798790''>we</span> <span m=''4798940''>only</span>
  <span m=''4799140''>get</span> <span m=''4799400''>one</span> <span m=''4799650''>more</span>
  <span m=''4799910''>class</span> <span m=''4800400''>on</span> <span m=''4800520''>Wednesday.</span>
  <span m=''4801230''>So</span> <span m=''4801500''>I</span> <span m=''4801570''>probably</span>
  <span m=''4801840''>won''t</span> <span m=''4802020''>have</span> <span m=''4802140''>much</span>
  <span m=''4802360''>more</span> <span m=''4802610''>to add</span> <span m=''4802990''>than
  this.</span> </p><p><span m=''4805770''>Is</span> <span m=''4805920''>that</span>
  <span m=''4806070''>clear?</span> <span m=''4807040''>Maybe</span> <span m=''4807190''>Ashish</span>
  <span m=''4807590''>you</span> <span m=''4807870''>could</span> <span m=''4808030''>put</span>
  <span m=''4808210''>out</span> <span m=''4808420''>a</span> <span m=''4811010''>email</span>
  <span m=''4811180''>to</span> <span m=''4811470''>the</span> <span m=''4811530''>class</span>
  <span m=''4812460''>to</span> <span m=''4812580''>do</span> <span m=''4812750''>that.</span>
  <span m=''4813530''>So</span> <span m=''4813760''>good.</span> <span m=''4814800''>We''ll</span>
  <span m=''4814920''>come</span> <span m=''4815060''>back</span> <span m=''4815410''>and</span>
  <span m=''4815530''>clean</span> <span m=''4815810''>up</span> <span m=''4817140''>Chapter</span>
  <span m=''4817560''>10</span> <span m=''4817880''>quickly</span> <span m=''4818370''>on</span>
  <span m=''4818570''>Wednesday,</span> <span m=''4819120''>and</span> <span m=''4819320''>then</span>
  <span m=''4820340''>move</span> <span m=''4820530''>on</span> <span m=''4820830''>to</span>
  <span m=''4821130''>11.</span> </p>'
type: course
uid: 1ffb818d0630053e5f9b6a9864f72bce

---
None