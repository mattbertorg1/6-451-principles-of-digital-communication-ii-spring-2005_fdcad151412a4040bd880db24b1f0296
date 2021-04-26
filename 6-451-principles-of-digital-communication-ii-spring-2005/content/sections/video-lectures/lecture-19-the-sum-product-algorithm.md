---
about_this_resource_text: '<p><strong>Topics covered: </strong>The Sum-Product Algorithm</p><p><strong>Instructor:
  </strong>Prof. David Forney</p>'
course_id: 6-451-principles-of-digital-communication-ii-spring-2005
embedded_media:
- id: 19.jpg
  parent_uid: eed1563e794f269c592125c3bcd253ce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-19-the-sum-product-algorithm/19.jpg
  title: 19.jpg
  type: null
  uid: 517b4d44dbf4f26508fd2f6effb74aee
- id: Video-YouTube-Stream
  media_location: dy44BdqxRAo
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Video-YouTube-Stream
  type: Video
  uid: f9c285f419b52ec7f338037e91945241
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/dy44BdqxRAo/default.jpg
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 098e7a2e011b89a657118f29c9d7e53e
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id341597857
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Video-iTunes U-MP4
  type: Video
  uid: 1f564c3492b36e6fa9f685302eed4815
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.451S05/19ocw-6.451_4-261-20apr2005-220k.mp4
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a61985b215cee24ffd5697354c48d54
- id: Thumbnail-OCW-JPG
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 4a0a6df832bc81ccfd6e73d79596772b
- id: 3Play-3PlayYouTubeid-MP4
  media_location: dy44BdqxRAo
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cbc09daa6943c88174f46c8459555dd1
- id: dy44BdqxRAo.srt
  parent_uid: eed1563e794f269c592125c3bcd253ce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-19-the-sum-product-algorithm/dy44BdqxRAo.srt
  title: 3play caption file
  type: null
  uid: 9ee2e226c7fa2b1c4330b0ba064ed05a
- id: dy44BdqxRAo.pdf
  parent_uid: eed1563e794f269c592125c3bcd253ce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-19-the-sum-product-algorithm/dy44BdqxRAo.pdf
  title: 3play pdf file
  type: null
  uid: e7d4844c93a7d1f826d32f23cc5b4da6
- id: Caption-3Play YouTube id-SRT
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b075a341fcbb79508b5fcb8dbed4d465
- id: Transcript-3Play YouTube id-PDF
  parent_uid: eed1563e794f269c592125c3bcd253ce
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d2d973d91daa39735c9ee2b82445a95d
inline_embed_id: 28532317lecture19:thesum-productalgorithm37421800
layout: video
order_index: null
parent_uid: 73f9a1c91575f1a3abda44e7358df3a2
related_resources_text: <p>The Sum-Product Algorithm (<a href="./resolveuid/ee9e85d57d6d74ab760b827e9b1043c7"
  target="_blank" title="Open in a new window.">PDF</a>)</p>
short_url: lecture-19-the-sum-product-algorithm
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-451-principles-of-digital-communication-ii-spring-2005/video-lectures/lecture-19-the-sum-product-algorithm
template_type: Tabbed
title: 'Lecture 19: The Sum-Product Algorithm '
transcript: '<p><span m=''2090''>PROFESSOR: We''re</span> <span m=''3770''>into</span>
  <span m=''4700''>chapter</span> <span m=''5150''>11.</span> <span m=''6120''>I''ve</span>
  <span m=''7710''>asked</span> <span m=''8480''>Ashish</span> <span m=''8940''>to
  hand out</span> <span m=''9170''>today</span> <span m=''9520''>a</span> <span m=''9620''>revision</span>
  <span m=''10220''>of</span> <span m=''10430''>the</span> <span m=''10520''>previous</span>
  <span m=''10930''>version</span> <span m=''11290''>of</span> <span m=''11380''>chapter</span>
  <span m=''11730''>11,</span> <span m=''12650''>plus</span> <span m=''13070''>chapter</span>
  <span m=''13440''>12</span> <span m=''13890''>on</span> <span m=''14050''>the</span>
  <span m=''14140''>sum-product</span> <span m=''14840''>algorithm,</span> <span m=''15420''>in</span>
  <span m=''15570''>case</span> <span m=''15870''>we</span> <span m=''16010''>get</span>
  <span m=''16280''>to</span> <span m=''16470''>it.</span> <span m=''18430''>I''m</span>
  <span m=''18750''>giving</span> <span m=''19030''>you</span> <span m=''19330''>a</span>
  <span m=''19450''>complete</span> <span m=''19910''>copy</span> <span m=''20320''>of</span>
  <span m=''20390''>the</span> <span m=''20490''>problem</span> <span m=''20820''>seven</span>
  <span m=''21180''>solutions</span> <span m=''21990''>for</span> <span m=''22180''>both</span>
  <span m=''22490''>weeks,</span> <span m=''23580''>and</span> <span m=''24500''>to</span>
  <span m=''24800''>get</span> <span m=''25000''>back</span> <span m=''25250''>on</span>
  <span m=''25360''>track,</span> <span m=''25800''>we''re</span> <span m=''25910''>handing</span>
  <span m=''26240''>out</span> <span m=''26420''>problem</span> <span m=''26730''>set</span>
  <span m=''27020''>eight.</span> <span m=''28740''>There</span> <span m=''28780''>probably</span>
  <span m=''29150''>will only</span> <span m=''29620''>be</span> <span m=''30430''>one</span>
  <span m=''30640''>more</span> <span m=''30920''>problem</span> <span m=''31370''>set</span>
  <span m=''31520''>that</span> <span m=''31630''>you</span> <span m=''31890''>hand</span>
  <span m=''32180''>in.</span> </p><p><span m=''33830''>All</span> <span m=''33880''>right.</span>
  <span m=''34260''>We''ve</span> <span m=''34430''>been</span> <span m=''34940''>getting</span>
  <span m=''36020''>to</span> <span m=''36300''>the</span> <span m=''36400''>centerpiece</span>
  <span m=''37260''>of</span> <span m=''39470''>the</span> <span m=''39650''>second</span>
  <span m=''40000''>half</span> <span m=''40350''>of</span> <span m=''40420''>the</span>
  <span m=''40540''>course</span> <span m=''41120''>which</span> <span m=''41410''>is</span>
  <span m=''41700''>codes</span> <span m=''42070''>on</span> <span m=''42230''>graphs,</span>
  <span m=''42760''>which</span> <span m=''42960''>is</span> <span m=''43100''>the</span>
  <span m=''43160''>way</span> <span m=''43300''>we''re</span> <span m=''43380''>going</span>
  <span m=''43530''>to</span> <span m=''43580''>get</span> <span m=''43900''>to</span>
  <span m=''44170''>capacity-achieving</span> <span m=''45280''>codes</span> <span
  m=''48130''>by</span> <span m=''48430''>building</span> <span m=''48810''>them</span>
  <span m=''49020''>on</span> <span m=''49540''>graphs</span> <span m=''50160''>of</span>
  <span m=''50390''>linear</span> <span m=''50810''>complexity</span> <span m=''52160''>and</span>
  <span m=''52330''>decoding</span> <span m=''52840''>them</span> <span m=''52970''>on</span>
  <span m=''53110''>the</span> <span m=''53200''>graphs</span> <span m=''54280''>with</span>
  <span m=''54600''>iterative</span> <span m=''54760''>decoding.</span> <span m=''56750''>I</span>
  <span m=''57330''>frame</span> <span m=''57800''>this</span> <span m=''58070''>in</span>
  <span m=''58150''>the</span> <span m=''58230''>language</span> <span m=''58770''>of</span>
  <span m=''58870''>behavioral</span> <span m=''60110''>realizations.</span> <span
  m=''60980''>I</span> <span m=''61070''>say a</span> <span m=''61420''>graph</span>
  <span m=''62440''>is</span> <span m=''62650''>a</span> <span m=''62700''>realization</span>
  <span m=''63610''>of</span> <span m=''63810''>a</span> <span m=''63910''>code</span>
  <span m=''64970''>via</span> <span m=''66460''>a</span> <span m=''66550''>behavior,</span>
  <span m=''67180''>which</span> <span m=''67470''>is</span> <span m=''67640''>the</span>
  <span m=''67750''>set</span> <span m=''68560''>of</span> <span m=''68680''>all</span>
  <span m=''68930''>the</span> <span m=''69310''>possible</span> <span m=''70250''>trajectories</span>
  <span m=''71030''>on</span> <span m=''71180''>the</span> <span m=''71270''>graph.</span>
  <span m=''72040''>So</span> <span m=''72240''>this</span> <span m=''72480''>is,</span>
  <span m=''72750''>again,</span> <span m=''73080''>putting</span> <span m=''73360''>it
  in</span> <span m=''73580''>system</span> <span m=''73910''>theory</span> <span
  m=''74250''>language.</span> </p><p><span m=''77030''>I</span> <span m=''77490''>want</span>
  <span m=''77660''>to</span> <span m=''77700''>distinguish</span> <span m=''78270''>between</span>
  <span m=''78720''>two</span> <span m=''78930''>types</span> <span m=''79380''>of</span>
  <span m=''79490''>variables.</span> <span m=''80240''>The</span> <span m=''81960''>external</span>
  <span m=''82590''>ones,</span> <span m=''83100''>which</span> <span m=''83340''>communicate</span>
  <span m=''83890''>with</span> <span m=''83960''>the</span> <span m=''84060''>outside</span>
  <span m=''84530''>world--</span> <span m=''85860''>in</span> <span m=''85980''>our</span>
  <span m=''86200''>case,</span> <span m=''86600''>these</span> <span m=''86870''>will</span>
  <span m=''86980''>be</span> <span m=''87130''>the</span> <span m=''87250''>symbols</span>
  <span m=''87830''>in</span> <span m=''87960''>a</span> <span m=''88040''>code</span>
  <span m=''88340''>word.</span> <span m=''89930''>These</span> <span m=''90140''>are</span>
  <span m=''90160''>the</span> <span m=''90230''>ones</span> <span m=''90490''>that
  are</span> <span m=''90650''>actually</span> <span m=''91120''>involved</span> <span
  m=''91560''>in</span> <span m=''91630''>the</span> <span m=''91760''>code.</span>
  <span m=''93350''>So</span> <span m=''93640''>these</span> <span m=''93910''>are</span>
  <span m=''93980''>more</span> <span m=''94160''>or</span> <span m=''94180''>less</span>
  <span m=''94390''>pre-specified</span> <span m=''95370''>for</span> <span m=''95630''>us</span>
  <span m=''95790''>when</span> <span m=''95900''>we''re</span> <span m=''96040''>trying</span>
  <span m=''96300''>to</span> <span m=''96370''>realize</span> <span m=''96850''>a</span>
  <span m=''96970''>code.</span> <span m=''98470''>But</span> <span m=''98700''>we</span>
  <span m=''98890''>can</span> <span m=''99165''>adjoin</span> <span m=''100210''>auxiliary</span>
  <span m=''100830''>variables,</span> <span m=''101550''>internal</span> <span m=''102050''>variables,</span>
  <span m=''102660''>we</span> <span m=''102890''>often</span> <span m=''103200''>call</span>
  <span m=''103430''>them</span> <span m=''103560''>state</span> <span m=''103980''>variables,</span>
  <span m=''104600''>hidden</span> <span m=''104870''>variables,</span> <span m=''105510''>latent</span>
  <span m=''105850''>variables,</span> <span m=''107710''>which</span> <span m=''107970''>are</span>
  <span m=''108070''>really</span> <span m=''108300''>there</span> <span m=''108540''>for</span>
  <span m=''108740''>our</span> <span m=''108920''>convenience.</span> <span m=''109730''>They''re</span>
  <span m=''109940''>to</span> <span m=''110100''>make</span> <span m=''110430''>the</span>
  <span m=''111030''>realization</span> <span m=''111720''>simpler,</span> <span m=''112440''>or</span>
  <span m=''112660''>more</span> <span m=''112910''>elegant</span> <span m=''113460''>in</span>
  <span m=''113610''>some way,</span> <span m=''114250''>or</span> <span m=''114360''>to
  have</span> <span m=''114480''>properties,</span> <span m=''115740''>or</span> <span
  m=''116100''>whatever.</span> <span m=''117090''>But</span> <span m=''117240''>these</span>
  <span m=''118070''>are</span> <span m=''118130''>free</span> <span m=''118460''>for</span>
  <span m=''118640''>us</span> <span m=''118800''>to</span> <span m=''119010''>have</span>
  <span m=''119220''>because</span> <span m=''119950''>they''re</span> <span m=''120200''>inside</span>
  <span m=''120700''>the</span> <span m=''120760''>box</span> <span m=''121640''>and</span>
  <span m=''121710''>the</span> <span m=''121790''>world</span> <span m=''122070''>never</span>
  <span m=''122300''>sees</span> <span m=''122660''>them.</span> </p><p><span m=''125190''>Now,</span>
  <span m=''125430''>we</span> <span m=''125550''>describe</span> <span m=''126190''>the</span>
  <span m=''126340''>behavior</span> <span m=''126910''>by</span> <span m=''127170''>a</span>
  <span m=''127360''>set</span> <span m=''127620''>of</span> <span m=''127760''>constraints</span>
  <span m=''129539''>on</span> <span m=''129750''>the</span> <span m=''129840''>variables,</span>
  <span m=''130520''>which</span> <span m=''130810''>in</span> <span m=''130900''>our</span>
  <span m=''131130''>case,</span> <span m=''132110''>these</span> <span m=''132340''>are</span>
  <span m=''132450''>local</span> <span m=''132850''>constraints</span> <span m=''133590''>that</span>
  <span m=''133680''>only</span> <span m=''133970''>involves</span> <span m=''134470''>a</span>
  <span m=''134540''>few</span> <span m=''134820''>of</span> <span m=''134940''>the</span>
  <span m=''135030''>variables,</span> <span m=''135700''>each</span> <span m=''135910''>one.</span>
  <span m=''137200''>The</span> <span m=''137460''>idea</span> <span m=''137790''>is</span>
  <span m=''138100''>to</span> <span m=''138350''>express</span> <span m=''138940''>a</span>
  <span m=''139010''>global</span> <span m=''139440''>behavior</span> <span m=''140080''>via</span>
  <span m=''140810''>local</span> <span m=''141250''>constraints</span> <span m=''141920''>on</span>
  <span m=''142090''>variables.</span> <span m=''144000''>And</span> <span m=''145760''>in</span>
  <span m=''145910''>our</span> <span m=''146110''>case,</span> <span m=''146650''>the</span>
  <span m=''146960''>constraints</span> <span m=''147610''>will</span> <span m=''147700''>be</span>
  <span m=''147830''>expressed</span> <span m=''148410''>by</span> <span m=''149110''>equations,</span>
  <span m=''149940''>as</span> <span m=''150080''>we''ve</span> <span m=''150250''>seen,</span>
  <span m=''151640''>or</span> <span m=''152000''>in</span> <span m=''152080''>a</span>
  <span m=''152140''>little</span> <span m=''152280''>bit</span> <span m=''152440''>more</span>
  <span m=''152650''>generality</span> <span m=''153310''>by</span> <span m=''155060''>little</span>
  <span m=''155500''>codes,</span> <span m=''156800''>which</span> <span m=''157000''>will</span>
  <span m=''157100''>go</span> <span m=''157300''>in to</span> <span m=''157600''>make</span>
  <span m=''157840''>up</span> <span m=''158000''>this</span> <span m=''158250''>big</span>
  <span m=''158510''>code.</span> <span m=''159310''>So</span> <span m=''159690''>in</span>
  <span m=''159770''>some</span> <span m=''159990''>sense,</span> <span m=''160310''>you
  can</span> <span m=''160450''>think</span> <span m=''160630''>of</span> <span m=''160720''>codes</span>
  <span m=''161130''>on</span> <span m=''161250''>graphs</span> <span m=''161780''>as</span>
  <span m=''161960''>being</span> <span m=''162570''>making</span> <span m=''162880''>big</span>
  <span m=''163170''>codes</span> <span m=''163510''>out of</span> <span m=''163760''>little</span>
  <span m=''164020''>codes,</span> <span m=''164450''>making</span> <span m=''164730''>global</span>
  <span m=''165150''>codes</span> <span m=''165540''>out of</span> <span m=''165730''>local</span>
  <span m=''166130''>codes.</span> </p><p><span m=''168890''>The</span> <span m=''169250''>behavior,</span>
  <span m=''169830''>then,</span> <span m=''170130''>is</span> <span m=''170240''>simply</span>
  <span m=''170610''>defined</span> <span m=''171200''>as</span> <span m=''171370''>the</span>
  <span m=''171470''>set</span> <span m=''171870''>of</span> <span m=''172010''>all</span>
  <span m=''172290''>combinations</span> <span m=''173000''>of</span> <span m=''173090''>variables,</span>
  <span m=''173750''>both</span> <span m=''174270''>external</span> <span m=''174960''>and</span>
  <span m=''175070''>internal,</span> <span m=''176330''>that</span> <span m=''176680''>satisfy</span>
  <span m=''177230''>all</span> <span m=''177370''>the</span> <span m=''177510''>constraints.</span>
  <span m=''178700''>If we</span> <span m=''178830''>can</span> <span m=''178980''>find</span>
  <span m=''179300''>a</span> <span m=''179350''>set</span> <span m=''179580''>of</span>
  <span m=''179690''>values</span> <span m=''180250''>for</span> <span m=''180400''>all</span>
  <span m=''180550''>the</span> <span m=''180620''>variables</span> <span m=''182060''>such</span>
  <span m=''182390''>that</span> <span m=''182500''>all</span> <span m=''182630''>these</span>
  <span m=''182810''>local</span> <span m=''183310''>constraints</span> <span m=''183960''>are</span>
  <span m=''184040''>satisfied,</span> <span m=''185730''>then</span> <span m=''186090''>that''s</span>
  <span m=''186450''>called</span> <span m=''186830''>a</span> <span m=''186950''>valid</span>
  <span m=''188320''>trajectory,</span> <span m=''189630''>or</span> <span m=''191390''>whatever.</span>
  <span m=''192430''>And</span> <span m=''192520''>that''s</span> <span m=''193040''>the</span>
  <span m=''193140''>entire</span> <span m=''193550''>behavior.</span> <span m=''194830''>And</span>
  <span m=''195030''>the</span> <span m=''195150''>code</span> <span m=''195690''>is</span>
  <span m=''195930''>simply</span> <span m=''196280''>the</span> <span m=''196390''>set</span>
  <span m=''197300''>of</span> <span m=''197500''>all</span> <span m=''199110''>external</span>
  <span m=''199720''>variable</span> <span m=''201090''>n-tuples</span> <span m=''202490''>that</span>
  <span m=''202650''>occur</span> <span m=''203110''>as</span> <span m=''203400''>parts</span>
  <span m=''203830''>of</span> <span m=''203960''>valid</span> <span m=''204340''>behaviors--</span>
  <span m=''204930''>in</span> <span m=''205180''>other words,</span> <span m=''205370''>the</span>
  <span m=''205430''>projection</span> <span m=''206040''>of</span> <span m=''206100''>the</span>
  <span m=''206180''>behavior</span> <span m=''206680''>just</span> <span m=''206970''>onto</span>
  <span m=''207210''>the</span> <span m=''207370''>external</span> <span m=''207880''>variables.</span>
  <span m=''208990''>All</span> <span m=''209310''>right,</span> <span m=''209660''>so</span>
  <span m=''210730''>it''s</span> <span m=''210920''>an</span> <span m=''210980''>elegant</span>
  <span m=''211530''>and</span> <span m=''211640''>rather</span> <span m=''211960''>implicit</span>
  <span m=''212530''>way</span> <span m=''212840''>of</span> <span m=''212940''>describing</span>
  <span m=''213530''>the</span> <span m=''213650''>code,</span> <span m=''214060''>but
  we''ll</span> <span m=''214240''>see</span> <span m=''214440''>it''s</span> <span
  m=''214670''>very,</span> <span m=''215470''>very</span> <span m=''215710''>powerful.</span>
  </p><p><span m=''217750''>And</span> <span m=''217920''>last</span> <span m=''218300''>time,</span>
  <span m=''218710''>we</span> <span m=''219190''>talked</span> <span m=''219580''>about</span>
  <span m=''220990''>various</span> <span m=''221460''>styles</span> <span m=''222080''>of</span>
  <span m=''222210''>realizations.</span> <span m=''224260''>I</span> <span m=''224320''>gave</span>
  <span m=''224610''>you</span> <span m=''224750''>examples</span> <span m=''225540''>of</span>
  <span m=''226440''>generator</span> <span m=''226960''>representations</span> <span
  m=''228220''>and</span> <span m=''229160''>parity-check</span> <span m=''229750''>representations.</span>
  <span m=''230770''>This</span> <span m=''230990''>is</span> <span m=''231130''>really</span>
  <span m=''231420''>where</span> <span m=''231660''>it</span> <span m=''231720''>all</span>
  <span m=''231970''>started,</span> <span m=''232500''>with</span> <span m=''232740''>parity-check</span>
  <span m=''233390''>representations,</span> <span m=''234230''>where</span> <span
  m=''234450''>this</span> <span m=''235210''>style</span> <span m=''235870''>of</span>
  <span m=''236100''>graphical</span> <span m=''236610''>representation</span> <span
  m=''237540''>is</span> <span m=''237700''>very</span> <span m=''238150''>natural.</span>
  <span m=''240720''>You''ve</span> <span m=''240890''>got</span> <span m=''241210''>the</span>
  <span m=''243280''>symbols</span> <span m=''243710''>in</span> <span m=''243770''>the</span>
  <span m=''243880''>code,</span> <span m=''244970''>those</span> <span m=''245240''>are</span>
  <span m=''245630''>the</span> <span m=''245790''>only</span> <span m=''245950''>symbols</span>
  <span m=''246350''>you</span> <span m=''246635''>need,</span> <span m=''246920''>and</span>
  <span m=''247030''>you''ve</span> <span m=''247170''>got</span> <span m=''247390''>parity</span>
  <span m=''247760''>checks,</span> <span m=''248200''>and</span> <span m=''248260''>the</span>
  <span m=''248340''>parity</span> <span m=''248730''>checks</span> <span m=''249160''>constrain</span>
  <span m=''249640''>the</span> <span m=''249740''>symbols.</span> <span m=''250360''>If</span>
  <span m=''250640''>you''ve</span> <span m=''250740''>got</span> <span m=''250900''>n</span>
  <span m=''251050''>minus</span> <span m=''251370''>k</span> <span m=''251600''>parity</span>
  <span m=''251980''>checks,</span> <span m=''252350''>you</span> <span m=''252610''>get</span>
  <span m=''252695''>n</span> <span m=''252780''>minus</span> <span m=''253130''>k</span>
  <span m=''253350''>constraints.</span> <span m=''254590''>And</span> <span m=''255180''>it''s</span>
  <span m=''256050''>a</span> <span m=''256140''>kernel</span> <span m=''256540''>representation</span>
  <span m=''257510''>in</span> <span m=''258000''>the</span> <span m=''258070''>language</span>
  <span m=''258610''>of</span> <span m=''260160''>linear</span> <span m=''260470''>algebra.</span>
  <span m=''262290''>It''s</span> <span m=''262670''>simply</span> <span m=''265500''>the</span>
  <span m=''265730''>set of</span> <span m=''266030''>all</span> <span m=''266510''>code</span>
  <span m=''266800''>n-tuples</span> <span m=''267400''>that</span> <span m=''267520''>satisfy</span>
  <span m=''267970''>all</span> <span m=''268120''>the</span> <span m=''268190''>parity</span>
  <span m=''268550''>checks.</span> <span m=''269290''>That''s</span> <span m=''269540''>it,</span>
  <span m=''269780''>we</span> <span m=''269880''>don''t</span> <span m=''270050''>need</span>
  <span m=''270240''>any</span> <span m=''271030''>hidden</span> <span m=''271300''>variables.</span>
  </p><p><span m=''272260''>In</span> <span m=''272380''>a</span> <span m=''272470''>generator</span>
  <span m=''273230''>representation,</span> <span m=''275520''>this</span> <span m=''275740''>is</span>
  <span m=''275910''>a</span> <span m=''275970''>more</span> <span m=''276210''>natural</span>
  <span m=''276620''>representation,</span> <span m=''277450''>when we''re</span>
  <span m=''277700''>trying</span> <span m=''277940''>to</span> <span m=''278170''>generate</span>
  <span m=''278940''>or</span> <span m=''279090''>simulate</span> <span m=''280380''>a</span>
  <span m=''280810''>code.</span> <span m=''281360''>We</span> <span m=''281490''>want</span>
  <span m=''281700''>to</span> <span m=''283520''>run</span> <span m=''283960''>through</span>
  <span m=''284260''>a</span> <span m=''284320''>set</span> <span m=''284590''>of</span>
  <span m=''284700''>inputs</span> <span m=''285310''>that</span> <span m=''287030''>in</span>
  <span m=''287160''>effect</span> <span m=''287530''>create</span> <span m=''287950''>all</span>
  <span m=''288170''>the</span> <span m=''288300''>outputs,</span> <span m=''288840''>all</span>
  <span m=''288960''>the</span> <span m=''289090''>code</span> <span m=''289350''>words.</span>
  <span m=''290340''>In</span> <span m=''290480''>this</span> <span m=''290690''>case,</span>
  <span m=''290980''>we</span> <span m=''291070''>don''t</span> <span m=''291260''>actually</span>
  <span m=''291610''>see</span> <span m=''291930''>the</span> <span m=''292060''>inputs</span>
  <span m=''292580''>as</span> <span m=''292720''>part</span> <span m=''293000''>of</span>
  <span m=''293080''>the</span> <span m=''293170''>code</span> <span m=''293480''>words,</span>
  <span m=''293860''>necessarily.</span> <span m=''294590''>We</span> <span m=''294770''>might,</span>
  <span m=''295210''>we</span> <span m=''295240''>might</span> <span m=''295500''>not.</span>
  <span m=''296230''>But</span> <span m=''296420''>we</span> <span m=''296630''>distinguish</span>
  <span m=''297180''>them</span> <span m=''297390''>in</span> <span m=''297460''>this</span>
  <span m=''297650''>representation</span> <span m=''298003''>and</span> <span m=''298710''>we</span>
  <span m=''299400''>regard</span> <span m=''299790''>the</span> <span m=''299910''>inputs</span>
  <span m=''300410''>as</span> <span m=''300570''>hidden</span> <span m=''300890''>variables,</span>
  <span m=''301750''>or</span> <span m=''301990''>state</span> <span m=''302300''>variables,</span>
  <span m=''302620''>if</span> <span m=''302940''>you</span> <span m=''303150''>like.</span>
  <span m=''303850''>They''re</span> <span m=''304270''>part</span> <span m=''304500''>of</span>
  <span m=''304570''>the</span> <span m=''304640''>realization,</span> <span m=''305440''>but</span>
  <span m=''305660''>they</span> <span m=''305790''>don''t</span> <span m=''306340''>actually</span>
  <span m=''306800''>occur</span> <span m=''307190''>in</span> <span m=''307380''>the</span>
  <span m=''307450''>code</span> <span m=''307760''>words,</span> <span m=''308060''>so</span>
  <span m=''308220''>they</span> <span m=''308380''>fit</span> <span m=''308620''>into</span>
  <span m=''308830''>the</span> <span m=''309050''>hidden</span> <span m=''309531''>category.</span>
  </p><p><span m=''311940''>OK,</span> <span m=''312290''>and</span> <span m=''312410''>we</span>
  <span m=''312580''>talked</span> <span m=''312930''>about</span> <span m=''313390''>two</span>
  <span m=''314000''>styles</span> <span m=''314570''>of</span> <span m=''314680''>graphs.</span>
  <span m=''316990''>Tanner</span> <span m=''317410''>graphs,</span> <span m=''317790''>which</span>
  <span m=''318220''>are</span> <span m=''318610''>older</span> <span m=''319110''>and</span>
  <span m=''319220''>more</span> <span m=''319430''>established.</span> <span m=''320400''>Tanner</span>
  <span m=''320630''>really</span> <span m=''320950''>wrote</span> <span m=''321220''>the</span>
  <span m=''321300''>foundation</span> <span m=''322310''>paper</span> <span m=''322670''>in</span>
  <span m=''322750''>this</span> <span m=''322870''>subject</span> <span m=''323390''>in</span>
  <span m=''323490''>1981.</span> <span m=''325030''>I</span> <span m=''325450''>regard</span>
  <span m=''325840''>him</span> <span m=''326040''>as</span> <span m=''326190''>the</span>
  <span m=''326270''>founder</span> <span m=''326750''>of</span> <span m=''326830''>the</span>
  <span m=''326930''>subject</span> <span m=''327360''>of</span> <span m=''327450''>codes</span>
  <span m=''327735''>on</span> <span m=''328020''>graphs.</span> <span m=''329340''>However,</span>
  <span m=''330390''>like</span> <span m=''330630''>a</span> <span m=''330680''>lot</span>
  <span m=''330860''>of good</span> <span m=''331140''>papers,</span> <span m=''331650''>his</span>
  <span m=''331850''>was</span> <span m=''332010''>completely</span> <span m=''332470''>ignored--</span>
  <span m=''334360''>that''s</span> <span m=''334790''>almost</span> <span m=''335210''>true--</span>
  <span m=''335670''>for</span> <span m=''344750''>15</span> <span m=''345230''>years.</span>
  <span m=''345540''>And</span> <span m=''345830''>then it was</span> <span m=''346000''>rediscovered</span>
  <span m=''346710''>around</span> <span m=''347360''>1995,</span> <span m=''348380''>when</span>
  <span m=''348530''>people</span> <span m=''348850''>began</span> <span m=''349210''>to</span>
  <span m=''349300''>wake</span> <span m=''349580''>up</span> <span m=''349760''>to</span>
  <span m=''349870''>this</span> <span m=''350010''>subject</span> <span m=''350490''>again.</span>
  </p><p><span m=''352120''>And</span> <span m=''352260''>Tanner</span> <span m=''352600''>graphs</span>
  <span m=''353100''>really</span> <span m=''353390''>come</span> <span m=''353610''>out</span>
  <span m=''353810''>of</span> <span m=''353890''>this</span> <span m=''354190''>idea.</span>
  <span m=''355490''>They</span> <span m=''355730''>were</span> <span m=''356100''>closely</span>
  <span m=''356600''>associated</span> <span m=''357130''>with</span> <span m=''357280''>that.</span>
  <span m=''357570''>We</span> <span m=''357700''>can</span> <span m=''357850''>generalize</span>
  <span m=''358510''>them</span> <span m=''358850''>to</span> <span m=''358940''>be</span>
  <span m=''359560''>more</span> <span m=''359720''>like</span> <span m=''360000''>this.</span>
  <span m=''360290''>But</span> <span m=''360460''>it''s</span> <span m=''360630''>this</span>
  <span m=''361090''>simple</span> <span m=''361540''>idea.</span> <span m=''361960''>We</span>
  <span m=''362050''>have</span> <span m=''362180''>a</span> <span m=''362240''>bipartite</span>
  <span m=''363000''>graph,</span> <span m=''363530''>we</span> <span m=''363630''>make</span>
  <span m=''363870''>one</span> <span m=''364090''>class</span> <span m=''364510''>of</span>
  <span m=''364780''>vertices</span> <span m=''365280''>into</span> <span m=''365340''>the</span>
  <span m=''365420''>variables,</span> <span m=''367150''>one</span> <span m=''367450''>class</span>
  <span m=''368050''>into</span> <span m=''368470''>the</span> <span m=''368600''>constraints,</span>
  <span m=''369250''>and</span> <span m=''369380''>we</span> <span m=''369510''>simply</span>
  <span m=''369970''>tie</span> <span m=''370360''>a</span> <span m=''370430''>variable</span>
  <span m=''370870''>to</span> <span m=''371460''>a</span> <span m=''371540''>constraint</span>
  <span m=''372400''>when</span> <span m=''372510''>it''s</span> <span m=''372670''>involved</span>
  <span m=''373170''>in</span> <span m=''373250''>the</span> <span m=''373360''>constraint.</span>
  <span m=''374430''>And</span> <span m=''374630''>we</span> <span m=''374770''>can</span>
  <span m=''374950''>generalize</span> <span m=''375570''>it</span> <span m=''375740''>by</span>
  <span m=''375880''>making</span> <span m=''376310''>internal</span> <span m=''376770''>and</span>
  <span m=''377530''>external</span> <span m=''378280''>variables,</span> <span m=''378960''>which</span>
  <span m=''379140''>we</span> <span m=''379240''>have</span> <span m=''379420''>to</span>
  <span m=''379550''>distinguish</span> <span m=''380240''>in</span> <span m=''380320''>the</span>
  <span m=''380410''>picture</span> <span m=''380840''>in</span> <span m=''380920''>some</span>
  <span m=''381150''>way.</span> </p><p><span m=''382160''>And</span> <span m=''383630''>the</span>
  <span m=''383930''>constraints,</span> <span m=''386130''>initially,</span> <span
  m=''386610''>they</span> <span m=''386760''>were</span> <span m=''386930''>just</span>
  <span m=''387180''>zero-sum</span> <span m=''387790''>constraints</span> <span m=''388340''>and</span>
  <span m=''388450''>parity-check</span> <span m=''389000''>codes.</span> <span m=''389380''>One</span>
  <span m=''389550''>of</span> <span m=''389600''>the</span> <span m=''389650''>things</span>
  <span m=''389960''>Tanner</span> <span m=''390280''>did</span> <span m=''390470''>was
  he</span> <span m=''390620''>said,</span> <span m=''390770''>well,</span> <span
  m=''390960''>they</span> <span m=''391100''>could</span> <span m=''391290''>be</span>
  <span m=''391460''>any</span> <span m=''391700''>codes.</span> <span m=''392950''>A</span>
  <span m=''393340''>single</span> <span m=''393680''>parity</span> <span m=''394040''>check</span>
  <span m=''395720''>is</span> <span m=''395880''>like</span> <span m=''396100''>a</span>
  <span m=''396150''>single</span> <span m=''396410''>parity-check</span> <span m=''396950''>code.</span>
  <span m=''397970''>And</span> <span m=''399170''>we</span> <span m=''399320''>can</span>
  <span m=''399440''>make</span> <span m=''399660''>any</span> <span m=''399860''>codes</span>
  <span m=''400280''>the</span> <span m=''400390''>constraints.</span> </p><p><span
  m=''401620''>And</span> <span m=''401850''>the</span> <span m=''402030''>edges</span>
  <span m=''402380''>don''t</span> <span m=''402610''>work</span> <span m=''402870''>very</span>
  <span m=''403090''>hard</span> <span m=''403350''>in</span> <span m=''403430''>the</span>
  <span m=''403590''>Tanner</span> <span m=''403940''>graph.</span> <span m=''404870''>They</span>
  <span m=''405810''>implicitly</span> <span m=''406740''>carry</span> <span m=''407100''>the</span>
  <span m=''407210''>variables</span> <span m=''407820''>to</span> <span m=''407940''>the</span>
  <span m=''408080''>constraints</span> <span m=''409120''>so</span> <span m=''409370''>we</span>
  <span m=''409510''>could</span> <span m=''409660''>label</span> <span m=''410010''>them</span>
  <span m=''410170''>with</span> <span m=''410300''>the</span> <span m=''410430''>variables.</span>
  <span m=''411506''>And</span> <span m=''411900''>we</span> <span m=''411990''>showed</span>
  <span m=''412280''>how</span> <span m=''412540''>a</span> <span m=''412780''>Tanner</span>
  <span m=''412880''>graph</span> <span m=''413310''>could</span> <span m=''413490''>always</span>
  <span m=''413840''>be</span> <span m=''414610''>transformed</span> <span m=''415380''>to</span>
  <span m=''415820''>this</span> <span m=''416090''>normal</span> <span m=''416450''>graph,</span>
  <span m=''416900''>which</span> <span m=''417100''>I</span> <span m=''417280''>think</span>
  <span m=''417460''>is</span> <span m=''418480''>certainly</span> <span m=''418900''>in</span>
  <span m=''418960''>more</span> <span m=''419160''>complicated</span> <span m=''419790''>situations,</span>
  <span m=''420490''>a</span> <span m=''420560''>cleaner</span> <span m=''420930''>way</span>
  <span m=''421720''>of</span> <span m=''421890''>explaining</span> <span m=''422450''>things,</span>
  <span m=''423740''>and</span> <span m=''424250''>cleaner</span> <span m=''424620''>in</span>
  <span m=''424720''>a</span> <span m=''424770''>variety</span> <span m=''425220''>of</span>
  <span m=''425300''>senses.</span> </p><p><span m=''426480''>Here</span> <span m=''427880''>is</span>
  <span m=''428250''>our</span> <span m=''429100''>taxonomy.</span> <span m=''429780''>Vertices</span>
  <span m=''431120''>indicate</span> <span m=''431630''>constraints,</span> <span
  m=''433420''>half</span> <span m=''433700''>edges</span> <span m=''434370''>indicate</span>
  <span m=''434810''>external</span> <span m=''435300''>variables.</span> <span m=''437180''>A</span>
  <span m=''437250''>half</span> <span m=''437500''>edge</span> <span m=''437740''>is</span>
  <span m=''437840''>something</span> <span m=''438140''>you</span> <span m=''438280''>can</span>
  <span m=''438450''>tie</span> <span m=''438740''>to</span> <span m=''438850''>another</span>
  <span m=''439140''>half</span> <span m=''439420''>edge</span> <span m=''439810''>to</span>
  <span m=''439950''>form</span> <span m=''440300''>an</span> <span m=''440610''>I/O</span>
  <span m=''441000''>pad.</span> <span m=''442190''>Edges</span> <span m=''443670''>tie</span>
  <span m=''443890''>together</span> <span m=''444270''>two</span> <span m=''444480''>constraints.</span>
  <span m=''445170''>They''re</span> <span m=''445320''>internal,</span> <span m=''446200''>and</span>
  <span m=''446320''>so</span> <span m=''446480''>these</span> <span m=''446680''>represent</span>
  <span m=''447210''>the</span> <span m=''447360''>internal</span> <span m=''447780''>variables.</span>
  <span m=''449070''>And</span> <span m=''449880''>this</span> <span m=''450240''>is</span>
  <span m=''450450''>cleaner</span> <span m=''450760''>both</span> <span m=''451010''>analytically--</span>
  <span m=''451760''>there''s</span> <span m=''452240''>this</span> <span m=''452520''>nice</span>
  <span m=''452810''>duality</span> <span m=''453330''>theorem</span> <span m=''453660''>about</span>
  <span m=''453860''>normal</span> <span m=''454190''>graphs</span> <span m=''454520''>that</span>
  <span m=''454720''>I</span> <span m=''454800''>won''t</span> <span m=''455020''>be</span>
  <span m=''455160''>presenting</span> <span m=''455670''>to</span> <span m=''455840''>you,</span>
  <span m=''456590''>and</span> <span m=''456810''>a</span> <span m=''456880''>couple</span>
  <span m=''457210''>other</span> <span m=''457400''>things.</span> <span m=''458720''>They''re</span>
  <span m=''459000''>cleaner</span> <span m=''459590''>when</span> <span m=''459890''>you</span>
  <span m=''460020''>come</span> <span m=''460250''>to</span> <span m=''460770''>implement</span>
  <span m=''461190''>the</span> <span m=''461280''>sum-product</span> <span m=''461920''>algorithm.</span>
  <span m=''463670''>I</span> <span m=''463920''>think</span> <span m=''464160''>they''re</span>
  <span m=''464270''>just</span> <span m=''464460''>generally</span> <span m=''464790''>cleaner,</span>
  <span m=''466030''>but</span> <span m=''466530''>I</span> <span m=''466760''>may</span>
  <span m=''466850''>be</span> <span m=''466990''>biased.</span> <span m=''467730''>I</span>
  <span m=''467860''>want</span> <span m=''468120''>you</span> <span m=''468250''>to</span>
  <span m=''468330''>see</span> <span m=''468550''>both</span> <span m=''468960''>because</span>
  <span m=''469220''>these</span> <span m=''469460''>still</span> <span m=''469800''>predominate</span>
  <span m=''470380''>the</span> <span m=''470490''>literature,</span> <span m=''471100''>although</span>
  <span m=''472140''>more</span> <span m=''472340''>and</span> <span m=''472400''>more</span>
  <span m=''472580''>people</span> <span m=''472900''>seem to</span> <span m=''473120''>be</span>
  <span m=''473230''>using</span> <span m=''473550''>this</span> <span m=''473810''>style
  of</span> <span m=''474100''>graph,</span> <span m=''474530''>and</span> <span m=''474620''>that''s</span>
  <span m=''474830''>what</span> <span m=''474960''>I</span> <span m=''475040''>will
  use</span> <span m=''475300''>in</span> <span m=''475410''>the</span> <span m=''475520''>course.</span>
  <span m=''476433''>All</span> <span m=''476926''>right?</span> <span m=''477420''>So</span>
  <span m=''477800''>that''s</span> <span m=''478130''>a</span> <span m=''478180''>review</span>
  <span m=''478640''>of</span> <span m=''478710''>where</span> <span m=''478920''>we</span>
  <span m=''479100''>are.</span> </p><p><span m=''481820''>OK.</span> <span m=''483710''>Today</span>
  <span m=''484360''>we''re</span> <span m=''484520''>going</span> <span m=''484650''>to</span>
  <span m=''484700''>go</span> <span m=''484910''>on</span> <span m=''485290''>to</span>
  <span m=''486970''>other</span> <span m=''487300''>important</span> <span m=''487830''>styles</span>
  <span m=''488360''>of</span> <span m=''488420''>realizations,</span> <span m=''489430''>and</span>
  <span m=''489640''>particularly</span> <span m=''492940''>the</span> <span m=''493220''>next</span>
  <span m=''493540''>one</span> <span m=''493710''>we''ll</span> <span m=''493900''>talk</span>
  <span m=''494260''>about</span> <span m=''494780''>is</span> <span m=''495420''>trellis</span>
  <span m=''495860''>realizations.</span> <span m=''497490''>So</span> <span m=''497720''>this</span>
  <span m=''497960''>will</span> <span m=''498190''>tie</span> <span m=''498420''>back</span>
  <span m=''499090''>to</span> <span m=''499230''>all</span> <span m=''499410''>the</span>
  <span m=''499510''>work</span> <span m=''499810''>we did</span> <span m=''499950''>in
  chapter</span> <span m=''500320''>10.</span> <span m=''502550''>And</span> <span
  m=''503460''>what</span> <span m=''503650''>did</span> <span m=''503740''>we</span>
  <span m=''503880''>discover</span> <span m=''504520''>in</span> <span m=''505240''>chapter</span>
  <span m=''505670''>10?</span> <span m=''506020''>The</span> <span m=''506140''>key</span>
  <span m=''506460''>to</span> <span m=''506670''>a</span> <span m=''507160''>trellis</span>
  <span m=''507550''>realization</span> <span m=''508250''>was</span> <span m=''509230''>a</span>
  <span m=''509330''>trellis-oriented</span> <span m=''510210''>generator</span> <span
  m=''510475''>matrix.</span> <span m=''512780''>And</span> <span m=''513049''>again,</span>
  <span m=''513470''>I</span> <span m=''513580''>will</span> <span m=''513820''>put</span>
  <span m=''514049''>up</span> <span m=''514340''>our</span> <span m=''515840''>favorite</span>
  <span m=''516450''>matrix</span> <span m=''516970''>on</span> <span m=''517090''>the</span>
  <span m=''517220''>board,</span> <span m=''520929''>the</span> <span m=''521159''>generator</span>
  <span m=''521890''>of</span> <span m=''522030''>the</span> <span m=''522480''>8,
  4, 4</span> <span m=''523669''>Reed-Muller</span> <span m=''524270''>code.</span>
  <span m=''528440''>And</span> <span m=''530530''>in</span> <span m=''530710''>the</span>
  <span m=''530800''>form</span> <span m=''531150''>we''ve</span> <span m=''531405''>come</span>
  <span m=''531660''>to</span> <span m=''531700''>know</span> <span m=''531890''>and</span>
  <span m=''531980''>love,</span> <span m=''532440''>it</span> <span m=''532540''>looks</span>
  <span m=''532860''>like</span> <span m=''533190''>this.</span> </p><p><span m=''534510''>And</span>
  <span m=''535770''>what</span> <span m=''535960''>makes</span> <span m=''536220''>it</span>
  <span m=''536290''>trellis-oriented</span> <span m=''536960''>is</span> <span m=''537295''>that</span>
  <span m=''538540''>all</span> <span m=''538810''>the</span> <span m=''538900''>starting</span>
  <span m=''539300''>times</span> <span m=''539680''>are</span> <span m=''539740''>different</span>
  <span m=''540090''>and</span> <span m=''540230''>all</span> <span m=''540450''>the</span>
  <span m=''540600''>ending</span> <span m=''540940''>times</span> <span m=''541290''>are</span>
  <span m=''541360''>different.</span> <span m=''542170''>Therefore</span> <span m=''542570''>these</span>
  <span m=''542780''>generators</span> <span m=''543380''>are</span> <span m=''543590''>as</span>
  <span m=''543660''>short</span> <span m=''543970''>as</span> <span m=''544120''>possible.</span>
  <span m=''545460''>The</span> <span m=''545730''>main</span> <span m=''546120''>feature</span>
  <span m=''546630''>of</span> <span m=''546690''>this</span> <span m=''546880''>generator</span>
  <span m=''547410''>that</span> <span m=''547510''>we</span> <span m=''547640''>want</span>
  <span m=''547850''>to</span> <span m=''547910''>look</span> <span m=''548200''>at</span>
  <span m=''548490''>is</span> <span m=''548790''>the</span> <span m=''549550''>spans,</span>
  <span m=''551170''>the</span> <span m=''551360''>active</span> <span m=''551910''>parts</span>
  <span m=''552390''>of</span> <span m=''552600''>the</span> <span m=''552710''>generators,</span>
  <span m=''553380''>which</span> <span m=''553580''>we''ve</span> <span m=''553740''>made</span>
  <span m=''554040''>as</span> <span m=''554110''>short</span> <span m=''554430''>as</span>
  <span m=''554570''>possible.</span> </p><p><span m=''555300''>And</span> <span m=''556170''>let</span>
  <span m=''556440''>me</span> <span m=''557640''>explicitly</span> <span m=''558430''>write</span>
  <span m=''558720''>out</span> <span m=''558980''>what</span> <span m=''559200''>they</span>
  <span m=''559410''>are.</span> <span m=''560130''>The</span> <span m=''560370''>first</span>
  <span m=''560650''>generator</span> <span m=''561790''>is</span> <span m=''562160''>active</span>
  <span m=''562790''>from</span> <span m=''563220''>symbol</span> <span m=''563610''>time</span>
  <span m=''564030''>0</span> <span m=''564330''>to</span> <span m=''564380''>symbol</span>
  <span m=''564750''>time</span> <span m=''565070''>3.</span> <span m=''566080''>This</span>
  <span m=''566340''>one</span> <span m=''566530''>is</span> <span m=''566700''>active</span>
  <span m=''567260''>from</span> <span m=''567540''>1</span> <span m=''568000''>to</span>
  <span m=''569250''>6.</span> <span m=''570870''>This</span> <span m=''571150''>one</span>
  <span m=''571390''>is</span> <span m=''571620''>active</span> <span m=''572280''>from</span>
  <span m=''573190''>2</span> <span m=''573600''>to</span> <span m=''574600''>5.</span>
  <span m=''575930''>And</span> <span m=''576160''>this</span> <span m=''576380''>one</span>
  <span m=''576560''>is</span> <span m=''576760''>active</span> <span m=''577340''>from</span>
  <span m=''578160''>4</span> <span m=''578920''>to</span> <span m=''579260''>7.</span>
  </p><p><span m=''580570''>OK,</span> <span m=''580940''>so those</span> <span m=''581210''>are</span>
  <span m=''581360''>the active</span> <span m=''581900''>spans.</span> <span m=''582380''>And</span>
  <span m=''582460''>we</span> <span m=''582600''>know</span> <span m=''582840''>from</span>
  <span m=''583230''>that,</span> <span m=''584440''>we</span> <span m=''584680''>can</span>
  <span m=''584940''>find</span> <span m=''585180''>the</span> <span m=''585300''>dimensions</span>
  <span m=''586230''>of</span> <span m=''586860''>minimal</span> <span m=''587250''>state</span>
  <span m=''587660''>spaces</span> <span m=''588300''>and</span> <span m=''588400''>of</span>
  <span m=''588530''>minimal</span> <span m=''589230''>branch</span> <span m=''589610''>spaces.</span>
  <span m=''590790''>OK,</span> <span m=''591270''>we</span> <span m=''591390''>just</span>
  <span m=''591610''>count</span> <span m=''591940''>the</span> <span m=''592010''>number</span>
  <span m=''592270''>of</span> <span m=''592340''>active</span> <span m=''592780''>generators</span>
  <span m=''593075''>at</span> <span m=''593370''>either</span> <span m=''593490''>of</span>
  <span m=''593770''>the</span> <span m=''593900''>state</span> <span m=''594290''>times,</span>
  <span m=''594710''>which</span> <span m=''594960''>are</span> <span m=''595390''>between</span>
  <span m=''595830''>the</span> <span m=''595930''>symbols,</span> <span m=''596460''>or</span>
  <span m=''596570''>the</span> <span m=''596690''>symbol</span> <span m=''597040''>times</span>
  <span m=''597540''>themselves</span> <span m=''598230''>for</span> <span m=''598570''>the</span>
  <span m=''598640''>branches.</span> <span m=''600310''>OK,</span> <span m=''600580''>again,</span>
  <span m=''601350''>quick</span> <span m=''601600''>review,</span> <span m=''603240''>especially</span>
  <span m=''603660''>because</span> <span m=''603900''>we</span> <span m=''604010''>have</span>
  <span m=''604110''>a</span> <span m=''604220''>few</span> <span m=''604450''>guests</span>
  <span m=''604800''>here</span> <span m=''605020''>who we</span> <span m=''605210''>haven''t</span>
  <span m=''605540''>seen</span> <span m=''605840''>previously</span> <span m=''606400''>in</span>
  <span m=''606510''>the</span> <span m=''606780''>course.</span> <span m=''607050''>So</span>
  <span m=''607520''>that''s</span> <span m=''607760''>where</span> <span m=''607930''>we''ve</span>
  <span m=''608070''>been.</span> </p><p><span m=''609620''>All</span> <span m=''609770''>right.</span>
  <span m=''612020''>Once</span> <span m=''612550''>you</span> <span m=''613330''>have</span>
  <span m=''613800''>any</span> <span m=''615180''>generator</span> <span m=''615680''>matrix,</span>
  <span m=''616260''>or</span> <span m=''616410''>in</span> <span m=''616490''>particular</span>
  <span m=''616905''>a</span> <span m=''617730''>trellis-oriented</span> <span m=''618550''>generator</span>
  <span m=''619060''>matrix,</span> <span m=''619456''>the</span> <span m=''619852''>code</span>
  <span m=''620250''>is</span> <span m=''620650''>simply</span> <span m=''621130''>described</span>
  <span m=''621960''>as</span> <span m=''622210''>the</span> <span m=''622840''>set</span>
  <span m=''623140''>of</span> <span m=''623260''>all</span> <span m=''623520''>linear</span>
  <span m=''623890''>combinations</span> <span m=''626690''>of</span> <span m=''627130''>the</span>
  <span m=''627250''>matrix</span> <span m=''627710''>elements.</span> <span m=''629176''>And</span>
  <span m=''629610''>in</span> <span m=''630000''>particular,</span> <span m=''630510''>the</span>
  <span m=''630640''>code</span> <span m=''630940''>symbol</span> <span m=''631560''>at</span>
  <span m=''631710''>every</span> <span m=''631900''>time</span> <span m=''632290''>is</span>
  <span m=''632490''>a</span> <span m=''632710''>linear</span> <span m=''633010''>combination</span>
  <span m=''634690''>of</span> <span m=''635800''>the</span> <span m=''636000''>matrix</span>
  <span m=''636410''>elements</span> <span m=''636840''>in</span> <span m=''636920''>a</span>
  <span m=''636980''>particular</span> <span m=''637490''>column.</span> </p><p><span
  m=''638890''>All</span> <span m=''638980''>right,</span> <span m=''639290''>so</span>
  <span m=''639420''>let''s</span> <span m=''639610''>use</span> <span m=''639970''>that</span>
  <span m=''640940''>to</span> <span m=''641080''>get</span> <span m=''641400''>a</span>
  <span m=''641490''>trellis</span> <span m=''641930''>realization.</span> <span m=''645890''>I''ve</span>
  <span m=''646070''>done</span> <span m=''646310''>this</span> <span m=''646570''>in</span>
  <span m=''646790''>various</span> <span m=''647270''>ways.</span> <span m=''647870''>I''m</span>
  <span m=''648760''>still</span> <span m=''649110''>not</span> <span m=''649400''>satisfied,</span>
  <span m=''650930''>though</span> <span m=''651850''>the</span> <span m=''651950''>way</span>
  <span m=''652200''>that</span> <span m=''652360''>I</span> <span m=''652670''>do</span>
  <span m=''652830''>it in</span> <span m=''652940''>the</span> <span m=''653060''>notes</span>
  <span m=''653590''>is</span> <span m=''653840''>quite</span> <span m=''655610''>notation</span>
  <span m=''656260''>heavy</span> <span m=''656830''>and</span> <span m=''657210''>mathematical.</span>
  <span m=''658830''>I</span> <span m=''658930''>hope</span> <span m=''659850''>this</span>
  <span m=''660110''>picture</span> <span m=''660590''>of</span> <span m=''660960''>what</span>
  <span m=''661180''>we''re</span> <span m=''661300''>going</span> <span m=''661410''>to</span>
  <span m=''661530''>do</span> <span m=''661820''>is</span> <span m=''662020''>going</span>
  <span m=''662170''>to</span> <span m=''663240''>give</span> <span m=''663700''>you</span>
  <span m=''664835''>a</span> <span m=''665280''>totally</span> <span m=''665610''>transparent</span>
  <span m=''666290''>idea</span> <span m=''666590''>of</span> <span m=''666670''>what''s</span>
  <span m=''666900''>going</span> <span m=''667230''>on.</span> </p><p><span m=''668570''>OK,</span>
  <span m=''673400''>we''re</span> <span m=''673520''>going</span> <span m=''673640''>to</span>
  <span m=''673740''>have</span> <span m=''673840''>a</span> <span m=''673910''>trellis</span>
  <span m=''674340''>realization.</span> <span m=''675770''>Let''s</span> <span m=''676010''>write</span>
  <span m=''676330''>down</span> <span m=''676650''>the</span> <span m=''677430''>symbol</span>
  <span m=''677890''>times.</span> <span m=''678160''>And</span> <span m=''678430''>I''ll</span>
  <span m=''678580''>write</span> <span m=''678880''>them</span> <span m=''679310''>all</span>
  <span m=''679430''>the</span> <span m=''679550''>way</span> <span m=''679680''>across</span>
  <span m=''680140''>the</span> <span m=''680210''>board.</span> <span m=''681170''>0,</span>
  <span m=''681590''>1,</span> <span m=''682000''>2,</span> <span m=''682400''>3,</span>
  <span m=''683470''>4,</span> <span m=''684260''>5,</span> <span m=''685360''>6,</span>
  <span m=''686480''>7.</span> <span m=''689720''>And</span> <span m=''691630''>let</span>
  <span m=''691970''>me</span> <span m=''693730''>save</span> <span m=''695220''>the</span>
  <span m=''695350''>coefficients,</span> <span m=''696550''>ui,</span> <span m=''698410''>here.</span>
  <span m=''699510''>And</span> <span m=''700770''>I''ll</span> <span m=''700950''>write</span>
  <span m=''701190''>them</span> <span m=''701320''>as</span> <span m=''701440''>equality</span>
  <span m=''701990''>constraints,</span> <span m=''702680''>but</span> <span m=''702890''>you</span>
  <span m=''703060''>can</span> <span m=''703200''>also</span> <span m=''704670''>think</span>
  <span m=''704830''>of</span> <span m=''704920''>them</span> <span m=''705020''>as</span>
  <span m=''705160''>a little</span> <span m=''705410''>binary</span> <span m=''705880''>shift</span>
  <span m=''706220''>register.</span> </p><p><span m=''708200''>I''m</span> <span
  m=''708350''>going</span> <span m=''708480''>to</span> <span m=''708560''>need</span>
  <span m=''708950''>u1</span> <span m=''710120''>at</span> <span m=''710360''>four</span>
  <span m=''710630''>different</span> <span m=''710960''>times.</span> <span m=''712500''>I''m</span>
  <span m=''712860''>going to</span> <span m=''712960''>need</span> <span m=''713160''>u1</span>
  <span m=''713540''>during</span> <span m=''713920''>its span</span> <span m=''714590''>at</span>
  <span m=''714750''>time</span> <span m=''715060''>0,</span> <span m=''715490''>1,</span>
  <span m=''715910''>2,</span> <span m=''716200''>and</span> <span m=''716410''>3.</span>
  <span m=''717410''>So</span> <span m=''718240''>I''ll</span> <span m=''718490''>set</span>
  <span m=''718740''>up a set of</span> <span m=''718870''>constraints</span> <span
  m=''719560''>here</span> <span m=''720450''>to</span> <span m=''720600''>propagate</span>
  <span m=''721460''>u1</span> <span m=''722060''>between</span> <span m=''722510''>these</span>
  <span m=''722780''>three</span> <span m=''723060''>times.</span> <span m=''724262''>And</span>
  <span m=''724600''>u1</span> <span m=''725100''>is</span> <span m=''725270''>going</span>
  <span m=''725420''>to</span> <span m=''725580''>be</span> <span m=''725740''>an</span>
  <span m=''725850''>internal</span> <span m=''726340''>variable.</span> <span m=''727470''>Strictly,</span>
  <span m=''728000''>there</span> <span m=''728190''>are</span> <span m=''728230''>three</span>
  <span m=''728530''>replicas</span> <span m=''729210''>of</span> <span m=''729310''>this</span>
  <span m=''729540''>internal</span> <span m=''730030''>variable</span> <span m=''730560''>here.</span>
  <span m=''731930''>And</span> <span m=''732170''>I</span> <span m=''732220''>can</span>
  <span m=''732410''>pull</span> <span m=''732660''>it</span> <span m=''732730''>out</span>
  <span m=''733030''>at</span> <span m=''733100''>each</span> <span m=''733350''>time,</span>
  <span m=''733650''>too.</span> <span m=''734080''>So</span> <span m=''737310''>this</span>
  <span m=''737560''>is</span> <span m=''738710''>where</span> <span m=''739240''>I''m</span>
  <span m=''739330''>going</span> <span m=''739460''>to</span> <span m=''739540''>keep</span>
  <span m=''739880''>u1,</span> <span m=''740550''>in</span> <span m=''740680''>effect.</span>
  </p><p><span m=''741650''>Similarly,</span> <span m=''743620''>u2</span> <span m=''745710''>I''m</span>
  <span m=''745940''>going</span> <span m=''746170''>to</span> <span m=''746960''>keep</span>
  <span m=''747240''>around</span> <span m=''747750''>for</span> <span m=''747920''>all</span>
  <span m=''748120''>the</span> <span m=''748190''>times</span> <span m=''748540''>that</span>
  <span m=''748710''>I</span> <span m=''748870''>need</span> <span m=''749170''>it,</span>
  <span m=''749440''>which</span> <span m=''749700''>is</span> <span m=''750590''>these</span>
  <span m=''750860''>six</span> <span m=''751350''>times.</span> <span m=''759978''>OK,</span>
  <span m=''760490''>so</span> <span m=''762810''>is</span> <span m=''762960''>that</span>
  <span m=''763110''>six?</span> <span m=''763590''>That''s</span> <span m=''763860''>only</span>
  <span m=''764550''>five.</span> <span m=''765280''>These</span> <span m=''765570''>are</span>
  <span m=''765670''>all</span> <span m=''765880''>the</span> <span m=''765960''>times</span>
  <span m=''766530''>that</span> <span m=''768020''>u2</span> <span m=''768620''>is</span>
  <span m=''768820''>actually</span> <span m=''769290''>involved</span> <span m=''770720''>in</span>
  <span m=''770980''>the</span> <span m=''771120''>output</span> <span m=''771590''>symbols,</span>
  <span m=''772010''>so</span> <span m=''772160''>I''m</span> <span m=''772280''>going</span>
  <span m=''772410''>to</span> <span m=''772450''>have</span> <span m=''772700''>it</span>
  <span m=''772850''>when</span> <span m=''773010''>I</span> <span m=''773080''>need</span>
  <span m=''773330''>it.</span> </p><p><span m=''774950''>u3</span> <span m=''775850''>I</span>
  <span m=''775950''>need</span> <span m=''776250''>for</span> <span m=''776410''>four</span>
  <span m=''776720''>times.</span> <span m=''786840''>I''ve</span> <span m=''786990''>been</span>
  <span m=''787410''>inconsistent</span> <span m=''787830''>in</span> <span m=''788250''>whether</span>
  <span m=''788570''>I</span> <span m=''788620''>write</span> <span m=''789210''>the</span>
  <span m=''789310''>variables</span> <span m=''790020''>or</span> <span m=''790080''>the</span>
  <span m=''790190''>values</span> <span m=''790740''>of</span> <span m=''790810''>the</span>
  <span m=''790970''>variables.</span> <span m=''792730''>In</span> <span m=''792780''>this</span>
  <span m=''792990''>case,</span> <span m=''793310''>I''m</span> <span m=''793410''>writing</span>
  <span m=''793700''>values.</span> <span m=''794660''>And</span> <span m=''796340''>finally,</span>
  <span m=''797240''>u4.</span> <span m=''798770''>I</span> <span m=''799160''>see</span>
  <span m=''799400''>I''m going to</span> <span m=''799890''>need more</span> <span
  m=''800140''>than</span> <span m=''800270''>one</span> <span m=''800520''>board</span>
  <span m=''800930''>here.</span> <span m=''812300''>So</span> <span m=''812520''>now</span>
  <span m=''812750''>I''ve</span> <span m=''812950''>got</span> <span m=''813240''>everything</span>
  <span m=''813770''>I</span> <span m=''813860''>need</span> <span m=''814250''>at</span>
  <span m=''814480''>the</span> <span m=''814580''>time</span> <span m=''817270''>that</span>
  <span m=''817480''>I</span> <span m=''817600''>need</span> <span m=''817860''>it.</span>
  </p><p><span m=''819390''>Now,</span> <span m=''820830''>this</span> <span m=''820980''>is</span>
  <span m=''821140''>going</span> <span m=''821220''>to</span> <span m=''821310''>be</span>
  <span m=''821440''>tricky.</span> <span m=''825260''>I''m</span> <span m=''825420''>simply</span>
  <span m=''825800''>going</span> <span m=''825950''>to</span> <span m=''825990''>have</span>
  <span m=''826210''>a</span> <span m=''826290''>linear</span> <span m=''826870''>combination--</span>
  <span m=''827800''>call</span> <span m=''828160''>it</span> <span m=''828940''>g0,</span>
  <span m=''830980''>g1,</span> <span m=''832380''>and</span> <span m=''832610''>so</span>
  <span m=''832880''>forth--</span> <span m=''833710''>which</span> <span m=''834240''>is</span>
  <span m=''834420''>going</span> <span m=''834540''>to</span> <span m=''834660''>create</span>
  <span m=''835360''>my</span> <span m=''835590''>output</span> <span m=''836160''>at</span>
  <span m=''838340''>time</span> <span m=''838640''>0,</span> <span m=''838930''>or</span>
  <span m=''839220''>time</span> <span m=''839570''>1,</span> <span m=''840810''>or</span>
  <span m=''841220''>time</span> <span m=''841550''>2,</span> <span m=''841890''>and</span>
  <span m=''842060''>so</span> <span m=''842270''>forth.</span> </p><p><span m=''847170''>And</span>
  <span m=''847510''>you''ll</span> <span m=''847780''>agree</span> <span m=''848300''>from</span>
  <span m=''848550''>this</span> <span m=''849130''>generator</span> <span m=''849640''>matrix</span>
  <span m=''850990''>that</span> <span m=''851370''>the</span> <span m=''851530''>output</span>
  <span m=''851970''>at</span> <span m=''852090''>time</span> <span m=''852400''>1</span>
  <span m=''852740''>is</span> <span m=''852910''>some</span> <span m=''853270''>linear</span>
  <span m=''853650''>combination</span> <span m=''854740''>of</span> <span m=''855650''>u1.</span>
  <span m=''859520''>And</span> <span m=''859830''>the</span> <span m=''859940''>output</span>
  <span m=''860380''>at</span> <span m=''860530''>time</span> <span m=''860830''>2</span>
  <span m=''861220''>is</span> <span m=''861330''>some</span> <span m=''861610''>linear</span>
  <span m=''861940''>combination</span> <span m=''863280''>of</span> <span m=''864390''>these</span>
  <span m=''864680''>two</span> <span m=''864870''>guys.</span> <span m=''869660''>OK,</span>
  <span m=''870240''>and</span> <span m=''870520''>the</span> <span m=''870640''>output</span>
  <span m=''871100''>at</span> <span m=''871250''>time</span> <span m=''871540''>3</span>
  <span m=''872530''>is</span> <span m=''872700''>some</span> <span m=''873060''>linear</span>
  <span m=''873440''>combination</span> <span m=''875950''>of</span> <span m=''876100''>these</span>
  <span m=''876250''>three</span> <span m=''876520''>guys,</span> <span m=''881527''>and</span>
  <span m=''882000''>so</span> <span m=''882230''>forth.</span> <span m=''882610''>You</span>
  <span m=''882710''>see what</span> <span m=''883000''>I''m</span> <span m=''883110''>doing?</span>
  </p><p><span m=''884240''>So</span> <span m=''885280''>I</span> <span m=''885420''>could</span>
  <span m=''885690''>describe</span> <span m=''886150''>these</span> <span m=''886430''>as</span>
  <span m=''886530''>simply</span> <span m=''886890''>a</span> <span m=''886970''>linear</span>
  <span m=''887390''>constraint.</span> <span m=''888000''>What</span> <span m=''888170''>are</span>
  <span m=''888220''>the</span> <span m=''888350''>possible</span> <span m=''888840''>combinations</span>
  <span m=''889660''>of</span> <span m=''889790''>inputs</span> <span m=''890050''>and</span>
  <span m=''890310''>outputs</span> <span m=''891420''>in</span> <span m=''891600''>this</span>
  <span m=''891840''>constraint?</span> <span m=''892810''>And</span> <span m=''893000''>similarly--</span>
  <span m=''899060''>and</span> <span m=''899520''>don''t</span> <span m=''899730''>make</span>
  <span m=''900100''>me</span> <span m=''900455''>draw</span> <span m=''900810''>the</span>
  <span m=''901170''>lines in.</span> <span m=''923100''>OK,</span> <span m=''923580''>so</span>
  <span m=''925930''>I</span> <span m=''926060''>claim</span> <span m=''930000''>this</span>
  <span m=''930180''>is</span> <span m=''930300''>a</span> <span m=''930360''>realization</span>
  <span m=''932300''>directly</span> <span m=''932870''>from</span> <span m=''933090''>this</span>
  <span m=''933310''>trellis-oriented</span> <span m=''934300''>generator</span> <span
  m=''934720''>matrix.</span> <span m=''935280''>Yes?</span> </p><p><span m=''935820''>AUDIENCE:
  In</span> <span m=''936708''>this</span> <span m=''938040''>example</span> <span
  m=''938230''>in</span> <span m=''940545''>the</span> <span m=''941000''>generator,</span>
  <span m=''941346''>g</span> <span m=''942040''>has</span> <span m=''942300''>a</span>
  <span m=''942490''>0</span> <span m=''942885''>[UNINTELLIGIBLE].</span> </p><p><span
  m=''944070''>PROFESSOR: Right.</span> </p><p><span m=''944950''>AUDIENCE: So</span>
  <span m=''945390''>before,</span> <span m=''945790''>the</span> <span m=''946200''>component</span>
  <span m=''946650''>had to</span> <span m=''947100''>be</span> <span m=''947550''>0</span>
  <span m=''948000''>in the</span> <span m=''948450''>linear</span> <span m=''948900''>combination?</span>
  <span m=''949350''>Or are you--</span> </p><p><span m=''950130''>PROFESSOR: I can</span>
  <span m=''950570''>do</span> <span m=''950860''>it that</span> <span m=''951230''>way.</span>
  <span m=''953710''>Clearly,</span> <span m=''954380''>I</span> <span m=''954530''>don''t</span>
  <span m=''954790''>need</span> <span m=''955590''>this</span> <span m=''955850''>input</span>
  <span m=''956360''>at</span> <span m=''956530''>this</span> <span m=''956790''>time.</span>
  <span m=''957670''>So</span> <span m=''957870''>I</span> <span m=''957980''>could</span>
  <span m=''958420''>erase</span> <span m=''958840''>that.</span> <span m=''959360''>Would
  that</span> <span m=''959470''>make</span> <span m=''959670''>you</span> <span m=''959760''>feel</span>
  <span m=''959950''>better?</span> <span m=''961940''>Actually,</span> <span m=''962310''>that</span>
  <span m=''962650''>gives</span> <span m=''962990''>an</span> <span m=''963140''>even</span>
  <span m=''963500''>better</span> <span m=''963800''>picture.</span> <span m=''965840''>It''s</span>
  <span m=''965960''>not</span> <span m=''966220''>going</span> <span m=''966330''>to</span>
  <span m=''966380''>make</span> <span m=''966630''>any</span> <span m=''966800''>fundamental</span>
  <span m=''967390''>difference,</span> <span m=''967900''>but</span> <span m=''969420''>I''m</span>
  <span m=''969540''>doing</span> <span m=''969820''>this</span> <span m=''970050''>for</span>
  <span m=''970260''>a</span> <span m=''970320''>generic</span> <span m=''970940''>set</span>
  <span m=''971190''>of</span> <span m=''971320''>generators</span> <span m=''972160''>that</span>
  <span m=''972350''>cover</span> <span m=''972660''>these</span> <span m=''972880''>spans.</span>
  <span m=''974060''>All</span> <span m=''974150''>right?</span> <span m=''974430''>For</span>
  <span m=''974550''>the</span> <span m=''974650''>particular</span> <span m=''975180''>ones</span>
  <span m=''975490''>we</span> <span m=''975700''>have</span> <span m=''975920''>here,</span>
  <span m=''976610''>yes,</span> <span m=''976950''>I</span> <span m=''977020''>can</span>
  <span m=''977220''>make</span> <span m=''977490''>that</span> <span m=''977730''>further</span>
  <span m=''978120''>change</span> <span m=''979350''>and</span> <span m=''981000''>eliminate</span>
  <span m=''981470''>those</span> <span m=''981740''>two</span> <span m=''981930''>inputs.</span>
  <span m=''982780''>But</span> <span m=''983600''>I''m</span> <span m=''983880''>shortly</span>
  <span m=''984350''>going</span> <span m=''984850''>to</span> <span m=''985110''>aggregate</span>
  <span m=''985780''>this</span> <span m=''986130''>and</span> <span m=''986240''>put</span>
  <span m=''986480''>it</span> <span m=''988990''>in</span> <span m=''989110''>a</span>
  <span m=''989170''>more</span> <span m=''989400''>aggregated</span> <span m=''989990''>form.</span>
  <span m=''990600''>And</span> <span m=''991460''>what''s</span> <span m=''991680''>happening</span>
  <span m=''992090''>internally</span> <span m=''992610''>here</span> <span m=''992820''>then</span>
  <span m=''993240''>won''t</span> <span m=''993490''>matter</span> <span m=''993900''>to
  us</span> <span m=''994110''>very</span> <span m=''994310''>much.</span> </p><p><span
  m=''996900''>OK.</span> <span m=''998270''>And</span> <span m=''998490''>notice</span>
  <span m=''999940''>that</span> <span m=''1002700''>I</span> <span m=''1002850''>can</span>
  <span m=''1003420''>regard</span> <span m=''1003870''>this</span> <span m=''1004190''>as</span>
  <span m=''1004510''>the</span> <span m=''1004600''>branch</span> <span m=''1004970''>space</span>
  <span m=''1005550''>at</span> <span m=''1005750''>this</span> <span m=''1006020''>time.</span>
  <span m=''1007480''>And</span> <span m=''1007690''>it</span> <span m=''1007790''>has</span>
  <span m=''1008100''>the</span> <span m=''1008180''>right</span> <span m=''1008500''>dimension</span>
  <span m=''1009510''>for</span> <span m=''1009670''>the</span> <span m=''1009840''>branch</span>
  <span m=''1010190''>space</span> <span m=''1010840''>at</span> <span m=''1010980''>each</span>
  <span m=''1011270''>of</span> <span m=''1011320''>these</span> <span m=''1011600''>times.</span>
  <span m=''1012610''>And</span> <span m=''1015270''>let</span> <span m=''1015710''>me</span>
  <span m=''1015810''>take</span> <span m=''1015970''>it a little</span> <span m=''1016100''>more</span>
  <span m=''1016290''>slowly.</span> <span m=''1016680''>First,</span> <span m=''1017140''>I</span>
  <span m=''1017240''>claim it''s a</span> <span m=''1017720''>realization.</span>
  <span m=''1018920''>If</span> <span m=''1019360''>I</span> <span m=''1019450''>built</span>
  <span m=''1019970''>that</span> <span m=''1020340''>thing</span> <span m=''1020580''>with</span>
  <span m=''1020730''>the</span> <span m=''1020850''>appropriate</span> <span m=''1021410''>linear</span>
  <span m=''1021730''>combinations</span> <span m=''1022530''>here,</span> <span m=''1023410''>then</span>
  <span m=''1023750''>the</span> <span m=''1023840''>behavior</span> <span m=''1024470''>of</span>
  <span m=''1024550''>this</span> <span m=''1024930''>is</span> <span m=''1026119''>basically</span>
  <span m=''1026640''>the</span> <span m=''1026690''>set</span> <span m=''1026970''>of</span>
  <span m=''1027079''>all</span> <span m=''1027319''>u''s</span> <span m=''1028640''>and</span>
  <span m=''1028859''>y''s</span> <span m=''1029440''>that</span> <span m=''1029569''>satisfy</span>
  <span m=''1030170''>all</span> <span m=''1030339''>these</span> <span m=''1030589''>constraints.</span>
  <span m=''1031390''>And</span> <span m=''1031480''>if</span> <span m=''1031599''>I</span>
  <span m=''1031670''>just</span> <span m=''1031890''>look</span> <span m=''1032060''>at</span>
  <span m=''1032150''>the</span> <span m=''1032280''>outputs,</span> <span m=''1033190''>that''s</span>
  <span m=''1033410''>the</span> <span m=''1033490''>set</span> <span m=''1033710''>of</span>
  <span m=''1033810''>all</span> <span m=''1034040''>code</span> <span m=''1034280''>words.</span>
  </p><p><span m=''1035950''>So</span> <span m=''1037050''>I''ve</span> <span m=''1037140''>constructed</span>
  <span m=''1039030''>a</span> <span m=''1039069''>behavioral</span> <span m=''1039640''>realization</span>
  <span m=''1040135''>in a</span> <span m=''1040630''>certain</span> <span m=''1040960''>way.</span>
  <span m=''1042700''>OK,</span> <span m=''1043180''>and</span> <span m=''1043560''>now</span>
  <span m=''1043890''>I''m</span> <span m=''1044069''>going</span> <span m=''1044200''>to</span>
  <span m=''1044329''>start</span> <span m=''1045020''>to</span> <span m=''1045800''>aggregate.</span>
  <span m=''1046579''>Aggregate</span> <span m=''1047170''>just</span> <span m=''1047420''>means</span>
  <span m=''1048580''>drawing</span> <span m=''1048990''>lines</span> <span m=''1049590''>around</span>
  <span m=''1050210''>sub-graphs.</span> <span m=''1052016''>Or</span> <span m=''1052470''>sometimes</span>
  <span m=''1052745''>in the</span> <span m=''1053020''>notes,</span> <span m=''1053070''>I</span>
  <span m=''1053423''>call</span> <span m=''1053776''>this</span> <span m=''1054130''>agglomeration.</span>
  <span m=''1058190''>So</span> <span m=''1058380''>I''m</span> <span m=''1058520''>going</span>
  <span m=''1058660''>to</span> <span m=''1058880''>regard</span> <span m=''1059360''>all</span>
  <span m=''1059750''>this</span> <span m=''1060920''>as</span> <span m=''1061150''>one</span>
  <span m=''1061490''>constraint</span> <span m=''1063340''>on</span> <span m=''1063610''>the</span>
  <span m=''1063700''>variables</span> <span m=''1064360''>that</span> <span m=''1065560''>come</span>
  <span m=''1065830''>out</span> <span m=''1066070''>of</span> <span m=''1066190''>this.</span>
  <span m=''1067380''>The</span> <span m=''1068190''>constraints</span> <span m=''1068900''>that</span>
  <span m=''1068990''>are</span> <span m=''1069100''>affected</span> <span m=''1069630''>by</span>
  <span m=''1069860''>this</span> <span m=''1070140''>agglomeration--</span> <span
  m=''1071020''>the</span> <span m=''1071250''>variables</span> <span m=''1071540''>that</span>
  <span m=''1071830''>are</span> <span m=''1071960''>affected</span> <span m=''1072410''>are</span>
  <span m=''1072540''>y0</span> <span m=''1073580''>and</span> <span m=''1073750''>u1.</span>
  </p><p><span m=''1075210''>OK,</span> <span m=''1075740''>so</span> <span m=''1076010''>this</span>
  <span m=''1077870''>I</span> <span m=''1078000''>can</span> <span m=''1078210''>draw--</span>
  <span m=''1078820''>let</span> <span m=''1079125''>me draw</span> <span m=''1079430''>it</span>
  <span m=''1079530''>this</span> <span m=''1079810''>way--</span> <span m=''1082020''>as</span>
  <span m=''1082300''>a</span> <span m=''1082410''>little</span> <span m=''1082730''>constraint</span>
  <span m=''1083390''>code</span> <span m=''1083950''>which</span> <span m=''1084180''>operates</span>
  <span m=''1084760''>at</span> <span m=''1084890''>time</span> <span m=''1085200''>0.</span>
  <span m=''1086590''>And</span> <span m=''1087180''>it''s</span> <span m=''1087380''>a</span>
  <span m=''1087470''>linear</span> <span m=''1087970''>2, 1</span> <span m=''1088510''>code</span>
  <span m=''1089570''>that</span> <span m=''1089780''>basically</span> <span m=''1090390''>ties</span>
  <span m=''1090820''>together</span> <span m=''1091450''>y0</span> <span m=''1092550''>and</span>
  <span m=''1093190''>u1,</span> <span m=''1096900''>whatever</span> <span m=''1097240''>the</span>
  <span m=''1097910''>relationship</span> <span m=''1098500''>between</span> <span
  m=''1098760''>them is.</span> <span m=''1098910''>It</span> <span m=''1099320''>probably</span>
  <span m=''1099710''>is</span> <span m=''1099900''>the</span> <span m=''1099990''>y0</span>
  <span m=''1100420''>equals</span> <span m=''1100710''>u1.</span> <span m=''1104400''>The</span>
  <span m=''1104500''>first</span> <span m=''1104790''>generator</span> <span m=''1105200''>starts</span>
  <span m=''1105600''>at</span> <span m=''1105670''>this</span> <span m=''1105890''>time.</span>
  <span m=''1106200''>That''s</span> <span m=''1106360''>about</span> <span m=''1106570''>the</span>
  <span m=''1106680''>only</span> <span m=''1106900''>thing</span> <span m=''1107290''>it
  could</span> <span m=''1107630''>be.</span> </p><p><span m=''1108210''>Similarly,</span>
  <span m=''1108700''>I''m</span> <span m=''1108850''>going</span> <span m=''1108980''>to</span>
  <span m=''1110080''>aggregate</span> <span m=''1110810''>all</span> <span m=''1111060''>this</span>
  <span m=''1111310''>part</span> <span m=''1111770''>of</span> <span m=''1111880''>the</span>
  <span m=''1111990''>realization</span> <span m=''1112800''>here</span> <span m=''1113170''>and</span>
  <span m=''1113370''>consider</span> <span m=''1113530''>it</span> <span m=''1113800''>a</span>
  <span m=''1113990''>big</span> <span m=''1115000''>block,</span> <span m=''1115500''>or
  a</span> <span m=''1115820''>big</span> <span m=''1116140''>constraint.</span> <span
  m=''1119160''>At</span> <span m=''1119450''>time</span> <span m=''1119820''>1,</span>
  <span m=''1120270''>there''s</span> <span m=''1120460''>some</span> <span m=''1120770''>constraint</span>
  <span m=''1121500''>that</span> <span m=''1122610''>affects</span> <span m=''1123340''>y1</span>
  <span m=''1125230''>and</span> <span m=''1126520''>u1</span> <span m=''1128210''>and</span>
  <span m=''1128370''>u2.</span> <span m=''1130760''>So</span> <span m=''1131870''>this</span>
  <span m=''1132120''>is</span> <span m=''1132360''>a</span> <span m=''1132470''>little</span>
  <span m=''1132750''>4, 2</span> <span m=''1133400''>code</span> <span m=''1133780''>on</span>
  <span m=''1133910''>the</span> <span m=''1133990''>four</span> <span m=''1134400''>incident</span>
  <span m=''1134930''>variables.</span> <span m=''1135550''>One</span> <span m=''1135760''>of</span>
  <span m=''1135820''>the</span> <span m=''1135920''>constraints</span> <span m=''1136570''>is</span>
  <span m=''1136890''>that</span> <span m=''1137410''>u1</span> <span m=''1137910''>on</span>
  <span m=''1138060''>this</span> <span m=''1138290''>side</span> <span m=''1138640''>equals</span>
  <span m=''1138990''>u1</span> <span m=''1139400''>on</span> <span m=''1139530''>this</span>
  <span m=''1139770''>side.</span> <span m=''1140520''>These</span> <span m=''1140740''>are</span>
  <span m=''1140800''>really</span> <span m=''1141140''>two</span> <span m=''1141350''>replicas</span>
  <span m=''1141970''>of</span> <span m=''1142040''>the</span> <span m=''1142140''>same</span>
  <span m=''1142430''>thing.</span> <span m=''1142750''>So</span> <span m=''1142930''>there''s</span>
  <span m=''1143140''>an</span> <span m=''1143210''>equality</span> <span m=''1143740''>constraint</span>
  <span m=''1144240''>propagating</span> <span m=''1144790''>through</span> <span
  m=''1145030''>there.</span> </p><p><span m=''1145830''>Then</span> <span m=''1146080''>I</span>
  <span m=''1146210''>have</span> <span m=''1146470''>some</span> <span m=''1146920''>function</span>
  <span m=''1147460''>of</span> <span m=''1147560''>y1</span> <span m=''1148230''>as</span>
  <span m=''1148400''>a</span> <span m=''1148580''>function</span> <span m=''1149020''>of</span>
  <span m=''1149750''>u1,</span> <span m=''1150320''>which</span> <span m=''1150560''>I''m</span>
  <span m=''1150660''>going</span> <span m=''1150740''>to</span> <span m=''1150830''>regard</span>
  <span m=''1151290''>as</span> <span m=''1151540''>the</span> <span m=''1151630''>state</span>
  <span m=''1152170''>at</span> <span m=''1152310''>this</span> <span m=''1152570''>time.</span>
  <span m=''1153900''>And</span> <span m=''1154070''>u1</span> <span m=''1154470''>and</span>
  <span m=''1154530''>u2,</span> <span m=''1155075''>let</span> <span m=''1155420''>me</span>
  <span m=''1156830''>call</span> <span m=''1157150''>that</span> <span m=''1157730''>state</span>
  <span m=''1158080''>space</span> <span m=''1158510''>at</span> <span m=''1158630''>time</span>
  <span m=''1158930''>1.</span> <span m=''1159300''>Let</span> <span m=''1159410''>me</span>
  <span m=''1159550''>call</span> <span m=''1159860''>this</span> <span m=''1160570''>at</span>
  <span m=''1160800''>time</span> <span m=''1161040''>0,</span> <span m=''1161355''>let</span>
  <span m=''1161670''>me call</span> <span m=''1161950''>this</span> <span m=''1162230''>the</span>
  <span m=''1162350''>state</span> <span m=''1162660''>space</span> <span m=''1163060''>at</span>
  <span m=''1163190''>time</span> <span m=''1163470''>1.</span> <span m=''1164630''>And</span>
  <span m=''1166700''>I</span> <span m=''1166800''>did</span> <span m=''1167030''>go</span>
  <span m=''1167190''>through</span> <span m=''1167490''>a</span> <span m=''1167550''>development</span>
  <span m=''1168130''>where</span> <span m=''1168360''>I</span> <span m=''1168430''>showed</span>
  <span m=''1168810''>that these</span> <span m=''1168980''>u''s</span> <span m=''1169770''>could</span>
  <span m=''1169970''>be</span> <span m=''1170090''>regarded</span> <span m=''1170570''>as</span>
  <span m=''1170710''>the</span> <span m=''1170810''>components</span> <span m=''1171440''>of</span>
  <span m=''1171580''>the</span> <span m=''1171680''>state</span> <span m=''1172090''>spaces.</span>
  <span m=''1172570''>This</span> <span m=''1172780''>is</span> <span m=''1172960''>a</span>
  <span m=''1173800''>more</span> <span m=''1174380''>constructive</span> <span m=''1175030''>way</span>
  <span m=''1175260''>of</span> <span m=''1175380''>seeing</span> <span m=''1175770''>the</span>
  <span m=''1175840''>same</span> <span m=''1176140''>thing.</span> </p><p><span m=''1177730''>And</span>
  <span m=''1178190''>notice</span> <span m=''1179050''>they</span> <span m=''1179250''>have</span>
  <span m=''1179440''>the</span> <span m=''1179530''>right</span> <span m=''1179810''>dimensions.</span>
  <span m=''1181680''>So the</span> <span m=''1182010''>states</span> <span m=''1182570''>are</span>
  <span m=''1182650''>what</span> <span m=''1182920''>carry</span> <span m=''1183340''>the</span>
  <span m=''1183470''>information</span> <span m=''1184210''>from</span> <span m=''1184450''>time</span>
  <span m=''1184970''>0 to</span> <span m=''1185330''>time</span> <span m=''1185760''>1,</span>
  <span m=''1186110''>just</span> <span m=''1186380''>as</span> <span m=''1186500''>we
  would</span> <span m=''1186640''>want.</span> <span m=''1187640''>They</span> <span
  m=''1187850''>kind</span> <span m=''1188080''>of</span> <span m=''1188690''>embody</span>
  <span m=''1189160''>the</span> <span m=''1189260''>Markov</span> <span m=''1189720''>property.</span>
  <span m=''1190220''>Yes?</span> </p><p><span m=''1190662''>AUDIENCE: Why is c0</span>
  <span m=''1191546''>length 2?</span> </p><p><span m=''1193320''>PROFESSOR: Why</span>
  <span m=''1193720''>is</span> <span m=''1194000''>c0--</span> </p><p><span m=''1196308''>AUDIENCE:
  Length 2.</span> </p><p><span m=''1197590''>PROFESSOR: Length</span> <span m=''1197930''>2.</span>
  <span m=''1198270''>Because it</span> <span m=''1198480''>affects</span> <span m=''1199020''>two</span>
  <span m=''1199160''>bits.</span> </p><p><span m=''1199880''>AUDIENCE: Thank you.</span>
  </p><p><span m=''1200940''>PROFESSOR: It</span> <span m=''1201490''>affects</span>
  <span m=''1201870''>these</span> <span m=''1202100''>two</span> <span m=''1202280''>bits.</span>
  <span m=''1206120''>Let''s</span> <span m=''1206310''>see,</span> <span m=''1206510''>how</span>
  <span m=''1206720''>did</span> <span m=''1206820''>I</span> <span m=''1206940''>know</span>
  <span m=''1207620''>that</span> <span m=''1208000''>there''s</span> <span m=''1208230''>only</span>
  <span m=''1208430''>one</span> <span m=''1208740''>possible</span> <span m=''1210340''>constraint</span>
  <span m=''1210850''>here?</span> <span m=''1211280''>Because</span> <span m=''1211710''>that''s</span>
  <span m=''1212060''>the</span> <span m=''1212430''>dimension</span> <span m=''1212910''>of</span>
  <span m=''1213010''>the</span> <span m=''1213100''>branch</span> <span m=''1213490''>space.</span>
  <span m=''1214360''>It''s</span> <span m=''1214450''>really</span> <span m=''1215230''>all</span>
  <span m=''1215440''>determined</span> <span m=''1215860''>by</span> <span m=''1216010''>u1.</span>
  <span m=''1218390''>Over</span> <span m=''1218620''>here,</span> <span m=''1218870''>however,</span>
  <span m=''1219260''>it''s</span> <span m=''1219430''>determined</span> <span m=''1219910''>by</span>
  <span m=''1220690''>u1</span> <span m=''1220860''>and</span> <span m=''1221130''>u2.</span>
  <span m=''1221790''>So</span> <span m=''1222180''>the</span> <span m=''1222290''>dimension</span>
  <span m=''1222780''>is</span> <span m=''1222940''>2.</span> <span m=''1223200''>u1</span>
  <span m=''1223440''>and</span> <span m=''1223670''>u2</span> <span m=''1224040''>are</span>
  <span m=''1224150''>free,</span> <span m=''1225830''>And</span> <span m=''1226060''>the</span>
  <span m=''1226170''>others</span> <span m=''1226550''>are</span> <span m=''1226960''>fixed</span>
  <span m=''1227420''>once</span> <span m=''1227650''>we</span> <span m=''1227780''>know</span>
  <span m=''1227970''>those.</span> <span m=''1229490''>So</span> <span m=''1229780''>I</span>
  <span m=''1229950''>was a</span> <span m=''1230130''>little</span> <span m=''1230290''>ahead</span>
  <span m=''1230470''>of</span> <span m=''1230550''>myself</span> <span m=''1231070''>there.</span>
  </p><p><span m=''1232560''>And</span> <span m=''1232750''>similarly,</span> <span
  m=''1233780''>let''s</span> <span m=''1234220''>keep</span> <span m=''1234550''>drawing</span>
  <span m=''1235130''>in</span> <span m=''1235340''>this</span> <span m=''1235600''>fashion,</span>
  <span m=''1237180''>here''s</span> <span m=''1237470''>a</span> <span m=''1237530''>constraint</span>
  <span m=''1238160''>code</span> <span m=''1238580''>at</span> <span m=''1238770''>time</span>
  <span m=''1239750''>2</span> <span m=''1240300''>which</span> <span m=''1240480''>relates</span>
  <span m=''1243150''>these</span> <span m=''1243660''>possible</span> <span m=''1244260''>variables,</span>
  <span m=''1246170''>u1,</span> <span m=''1246760''>u2,</span> <span m=''1247270''>u3,</span>
  <span m=''1247860''>which</span> <span m=''1248090''>I''m</span> <span m=''1248180''>going
  to</span> <span m=''1248470''>call</span> <span m=''1248840''>the</span> <span m=''1248940''>state</span>
  <span m=''1249340''>space</span> <span m=''1250870''>at</span> <span m=''1252450''>time</span>
  <span m=''1252790''>2.</span> <span m=''1254710''>So</span> <span m=''1256400''>my</span>
  <span m=''1256530''>times</span> <span m=''1256970''>are</span> <span m=''1257040''>not</span>
  <span m=''1257260''>what</span> <span m=''1257430''>I</span> <span m=''1257830''>expect.</span>
  <span m=''1260710''>But</span> <span m=''1261110''>it''s</span> <span m=''1261720''>always</span>
  <span m=''1262140''>really</span> <span m=''1262410''>a</span> <span m=''1262470''>problem</span>
  <span m=''1262900''>to</span> <span m=''1263040''>keep</span> <span m=''1264010''>the</span>
  <span m=''1264670''>indexes</span> <span m=''1265340''>consistent.</span> <span
  m=''1266440''>We</span> <span m=''1266600''>want</span> <span m=''1269190''>state</span>
  <span m=''1269600''>time</span> <span m=''1269910''>1</span> <span m=''1270590''>to</span>
  <span m=''1270720''>occur</span> <span m=''1271120''>after</span> <span m=''1272710''>the</span>
  <span m=''1272810''>first</span> <span m=''1273150''>symbol.</span> <span m=''1274330''>So</span>
  <span m=''1274610''>this</span> <span m=''1274730''>should</span> <span m=''1274920''>be</span>
  <span m=''1275120''>state</span> <span m=''1275480''>time</span> <span m=''1275850''>2,</span>
  <span m=''1276700''>this</span> <span m=''1276840''>should</span> <span m=''1277050''>be</span>
  <span m=''1277260''>state</span> <span m=''1277670''>time</span> <span m=''1278000''>3</span>
  <span m=''1279160''>to</span> <span m=''1279280''>be</span> <span m=''1279460''>consistent</span>
  <span m=''1280030''>with</span> <span m=''1280150''>what''s</span> <span m=''1280450''>in</span>
  <span m=''1280590''>the</span> <span m=''1280680''>notes.</span> <span m=''1281110''>I''m</span>
  <span m=''1281220''>sorry.</span> </p><p><span m=''1284740''>And</span> <span m=''1285840''>so</span>
  <span m=''1286080''>forth.</span> <span m=''1286460''>What</span> <span m=''1286670''>is</span>
  <span m=''1287490''>the</span> <span m=''1287580''>length</span> <span m=''1287950''>of</span>
  <span m=''1288050''>this</span> <span m=''1288340''>code?</span> <span m=''1288770''>It''s</span>
  <span m=''1288920''>simply</span> <span m=''1289270''>the</span> <span m=''1289400''>number</span>
  <span m=''1289760''>of</span> <span m=''1289820''>bits</span> <span m=''1290250''>that
  it</span> <span m=''1290560''>controls,</span> <span m=''1291880''>which</span>
  <span m=''1292170''>is</span> <span m=''1292270''>6.</span> <span m=''1293960''>1,</span>
  <span m=''1294130''>2,</span> <span m=''1294470''>3,</span> <span m=''1294860''>4,</span>
  <span m=''1295040''>5,</span> <span m=''1295220''>6.</span> <span m=''1296400''>What''s</span>
  <span m=''1296730''>the</span> <span m=''1297670''>dimension?</span> <span m=''1299290''>It''s</span>
  <span m=''1300840''>3,</span> <span m=''1301210''>because</span> <span m=''1301950''>u1,</span>
  <span m=''1302390''>u2,</span> <span m=''1302830''>u3</span> <span m=''1303320''>are</span>
  <span m=''1303420''>free</span> <span m=''1304980''>if</span> <span m=''1305400''>I</span>
  <span m=''1305490''>only</span> <span m=''1305720''>look</span> <span m=''1305950''>at</span>
  <span m=''1306060''>this</span> <span m=''1306710''>constraint</span> <span m=''1307250''>independent</span>
  <span m=''1307840''>of</span> <span m=''1307940''>everything</span> <span m=''1308400''>else.</span>
  </p><p><span m=''1312056''>OK,</span> <span m=''1312514''>and</span> <span m=''1313520''>continuing</span>
  <span m=''1313940''>this</span> <span m=''1314140''>way,</span> <span m=''1314350''>at</span>
  <span m=''1314470''>this</span> <span m=''1314720''>point,</span> <span m=''1315140''>you</span>
  <span m=''1315250''>notice</span> <span m=''1315710''>I</span> <span m=''1315840''>only</span>
  <span m=''1316100''>have</span> <span m=''1316400''>u2</span> <span m=''1316780''>and</span>
  <span m=''1316960''>u3.</span> <span m=''1319320''>So</span> <span m=''1319760''>my</span>
  <span m=''1319950''>state</span> <span m=''1320350''>space</span> <span m=''1320760''>at</span>
  <span m=''1320860''>time</span> <span m=''1321160''>4</span> <span m=''1321570''>has</span>
  <span m=''1321790''>gone</span> <span m=''1322050''>down</span> <span m=''1322340''>in</span>
  <span m=''1322490''>dimension.</span> <span m=''1325620''>And</span> <span m=''1326270''>here</span>
  <span m=''1326730''>I have</span> <span m=''1327070''>c3,</span> <span m=''1328690''>which</span>
  <span m=''1328940''>is,</span> <span m=''1329110''>again,</span> <span m=''1329440''>a</span>
  <span m=''1329490''>6, 3</span> <span m=''1330130''>code,</span> <span m=''1331380''>and</span>
  <span m=''1332350''>so</span> <span m=''1332630''>forth,</span> <span m=''1333030''>as</span>
  <span m=''1333220''>I</span> <span m=''1333270''>go</span> <span m=''1333490''>ahead.</span>
  <span m=''1333970''>Let</span> <span m=''1334110''>me just</span> <span m=''1335890''>draw</span>
  <span m=''1336240''>it.</span> <span m=''1338900''>This</span> <span m=''1339230''>is</span>
  <span m=''1339570''>also</span> <span m=''1340000''>a</span> <span m=''1340110''>6,</span>
  <span m=''1340660''>3.</span> <span m=''1344060''>This is</span> <span m=''1347070''>time</span>
  <span m=''1347350''>5.</span> <span m=''1353288''>I have  the</span> <span m=''1353780''>state</span>
  <span m=''1354530''>space</span> <span m=''1356216''>at</span> <span m=''1356640''>time</span>
  <span m=''1357030''>6.</span> <span m=''1362740''>This</span> <span m=''1363240''>is</span>
  <span m=''1363590''>back</span> <span m=''1363980''>down</span> <span m=''1364460''>to</span>
  <span m=''1365060''>1,</span> <span m=''1367320''>4.</span> <span m=''1369250''>It''s</span>
  <span m=''1369630''>symmetrical</span> <span m=''1370320''>on</span> <span m=''1370450''>this</span>
  <span m=''1370590''>side,</span> <span m=''1371900''>as</span> <span m=''1372090''>you</span>
  <span m=''1372220''>know.</span> </p><p><span m=''1387180''>So</span> <span m=''1387390''>that''s</span>
  <span m=''1387660''>my</span> <span m=''1388620''>trellis</span> <span m=''1389940''>realization.</span>
  <span m=''1390400''>And</span> <span m=''1390860''>I</span> <span m=''1390940''>claim</span>
  <span m=''1391760''>this,</span> <span m=''1392000''>too,</span> <span m=''1392240''>is</span>
  <span m=''1392360''>a</span> <span m=''1392420''>realization,</span> <span m=''1393860''>in</span>
  <span m=''1394010''>the</span> <span m=''1394110''>sense</span> <span m=''1394610''>that</span>
  <span m=''1394780''>any</span> <span m=''1395480''>combination</span> <span m=''1396210''>of</span>
  <span m=''1396360''>u''s</span> <span m=''1396900''>and</span> <span m=''1397020''>y''s</span>
  <span m=''1397690''>that</span> <span m=''1397820''>satisfy</span> <span m=''1398480''>all</span>
  <span m=''1398620''>of</span> <span m=''1398770''>these</span> <span m=''1399050''>constraints</span>
  <span m=''1399730''>is</span> <span m=''1399900''>a</span> <span m=''1400340''>legitimate</span>
  <span m=''1401760''>trajectory.</span> <span m=''1403300''>And</span> <span m=''1403530''>the</span>
  <span m=''1403610''>set</span> <span m=''1403860''>of</span> <span m=''1403970''>all</span>
  <span m=''1404460''>y''s</span> <span m=''1405100''>that</span> <span m=''1405240''>are</span>
  <span m=''1405290''>part</span> <span m=''1405540''>of</span> <span m=''1405610''>those</span>
  <span m=''1405910''>legitimate</span> <span m=''1407100''>trajectories</span> <span
  m=''1408030''>form</span> <span m=''1408300''>the</span> <span m=''1408420''>code.</span>
  <span m=''1409350''>In</span> <span m=''1409470''>fact,</span> <span m=''1410560''>it''s</span>
  <span m=''1410720''>pretty</span> <span m=''1411720''>explicit</span> <span m=''1412410''>here</span>
  <span m=''1413210''>that</span> <span m=''1413470''>the</span> <span m=''1413950''>dimension</span>
  <span m=''1414470''>of</span> <span m=''1414530''>the</span> <span m=''1414630''>code</span>
  <span m=''1414960''>is</span> <span m=''1415130''>4,</span> <span m=''1415660''>corresponding</span>
  <span m=''1416460''>to</span> <span m=''1417190''>u1,</span> <span m=''1417670''>u2,</span>
  <span m=''1418100''>u3.</span> <span m=''1419330''>So</span> <span m=''1419560''>I</span>
  <span m=''1419710''>have</span> <span m=''1420610''>8</span> <span m=''1420840''>outputs,</span>
  <span m=''1422050''>I</span> <span m=''1422190''>have</span> <span m=''1422800''>16</span>
  <span m=''1423450''>possible</span> <span m=''1423960''>behaviors.</span> <span
  m=''1425040''>I</span> <span m=''1425140''>pick</span> <span m=''1425450''>off</span>
  <span m=''1426450''>the</span> <span m=''1426590''>combinations</span> <span m=''1427460''>of</span>
  <span m=''1427590''>u''s</span> <span m=''1427860''>and</span> <span m=''1428130''>y''s</span>
  <span m=''1428700''>that</span> <span m=''1428820''>could</span> <span m=''1428990''>make</span>
  <span m=''1429270''>that,</span> <span m=''1430030''>which</span> <span m=''1430270''>is</span>
  <span m=''1430440''>basically</span> <span m=''1430990''>determined</span> <span
  m=''1431510''>by</span> <span m=''1431700''>this</span> <span m=''1432160''>matrix.</span>
  <span m=''1433430''>And</span> <span m=''1433780''>I</span> <span m=''1433840''>just</span>
  <span m=''1434040''>pick</span> <span m=''1434240''>off</span> <span m=''1434460''>the</span>
  <span m=''1434560''>y''s</span> <span m=''1435050''>and</span> <span m=''1435130''>that''s</span>
  <span m=''1435350''>my</span> <span m=''1435690''>8, 4</span> <span m=''1436270''>code.</span>
  </p><p><span m=''1437900''>OK,</span> <span m=''1438260''>so</span> <span m=''1438460''>that''s</span>
  <span m=''1440050''>what</span> <span m=''1440420''>trellis</span> <span m=''1440870''>looks</span>
  <span m=''1441180''>like.</span> <span m=''1443720''>The</span> <span m=''1443860''>constraint</span>
  <span m=''1444570''>code</span> <span m=''1445090''>really</span> <span m=''1445550''>embodies</span>
  <span m=''1446170''>the</span> <span m=''1446250''>branches.</span> <span m=''1449760''>This</span>
  <span m=''1450510''>encapsulates</span> <span m=''1451300''>everything</span> <span
  m=''1451680''>that</span> <span m=''1451800''>can</span> <span m=''1451930''>happen</span>
  <span m=''1452240''>at</span> <span m=''1452350''>time</span> <span m=''1452630''>0.</span>
  <span m=''1453010''>This</span> <span m=''1453600''>encapsulates</span> <span m=''1454340''>everything</span>
  <span m=''1454700''>that</span> <span m=''1454800''>could</span> <span m=''1454960''>happen</span>
  <span m=''1455320''>at</span> <span m=''1455460''>time</span> <span m=''1455720''>1.</span>
  <span m=''1457370''>The</span> <span m=''1458590''>u''s</span> <span m=''1459170''>are</span>
  <span m=''1459390''>really</span> <span m=''1459600''>my</span> <span m=''1459770''>state</span>
  <span m=''1460230''>spaces.</span> <span m=''1461670''>This</span> <span m=''1462050''>constrains</span>
  <span m=''1463510''>state,</span> <span m=''1464370''>output,</span> <span m=''1464920''>next</span>
  <span m=''1465160''>state,</span> <span m=''1466220''>in</span> <span m=''1466360''>nice</span>
  <span m=''1466850''>linear</span> <span m=''1467180''>system</span> <span m=''1467540''>theories</span>
  <span m=''1468110''>style.</span> <span m=''1468920''>This</span> <span m=''1469160''>tells</span>
  <span m=''1469440''>me</span> <span m=''1469550''>what</span> <span m=''1469770''>combinations</span>
  <span m=''1470510''>of</span> <span m=''1470600''>state,</span> <span m=''1471220''>output,</span>
  <span m=''1471720''>next</span> <span m=''1472080''>state,</span> <span m=''1472370''>I</span>
  <span m=''1472510''>can</span> <span m=''1472680''>have</span> <span m=''1472830''>at</span>
  <span m=''1472980''>time</span> <span m=''1474140''>2,</span> <span m=''1474680''>and</span>
  <span m=''1474830''>so</span> <span m=''1475020''>forth</span> <span m=''1475930''>across</span>
  <span m=''1476200''>the</span> <span m=''1476470''>board.</span> </p><p><span m=''1476800''>So</span>
  <span m=''1476950''>the</span> <span m=''1477070''>constraints</span> <span m=''1478940''>are</span>
  <span m=''1479100''>local</span> <span m=''1479500''>constraints--</span> <span
  m=''1480240''>local</span> <span m=''1480630''>in</span> <span m=''1480730''>time,</span>
  <span m=''1481160''>in</span> <span m=''1481250''>this</span> <span m=''1481390''>sense--</span>
  <span m=''1481900''>that</span> <span m=''1482490''>constrain</span> <span m=''1484530''>what</span>
  <span m=''1484730''>can</span> <span m=''1484870''>happen</span> <span m=''1485260''>as</span>
  <span m=''1485360''>you</span> <span m=''1485490''>get</span> <span m=''1485700''>to</span>
  <span m=''1485810''>the</span> <span m=''1485970''>next</span> <span m=''1486140''>state.</span>
  <span m=''1486470''>Once</span> <span m=''1486650''>you</span> <span m=''1486770''>get</span>
  <span m=''1486960''>to</span> <span m=''1487030''>the</span> <span m=''1487190''>next</span>
  <span m=''1487350''>state,</span> <span m=''1487730''>this</span> <span m=''1487820''>state</span>
  <span m=''1488110''>has</span> <span m=''1488300''>the</span> <span m=''1488380''>Markov</span>
  <span m=''1488910''>property.</span> <span m=''1489340''>This</span> <span m=''1489540''>is</span>
  <span m=''1489710''>all</span> <span m=''1490080''>that</span> <span m=''1490280''>the</span>
  <span m=''1490540''>memory</span> <span m=''1490830''>you</span> <span m=''1491000''>need</span>
  <span m=''1491300''>of</span> <span m=''1491410''>the</span> <span m=''1491520''>past</span>
  <span m=''1492100''>in</span> <span m=''1492200''>order</span> <span m=''1492470''>to</span>
  <span m=''1492620''>determine</span> <span m=''1493090''>the</span> <span m=''1493180''>future,</span>
  <span m=''1494180''>or</span> <span m=''1494540''>the</span> <span m=''1494760''>whole</span>
  <span m=''1494980''>set</span> <span m=''1495260''>of</span> <span m=''1495350''>future</span>
  <span m=''1495700''>possibilities.</span> <span m=''1498380''>Each</span> <span
  m=''1498700''>of</span> <span m=''1498780''>these</span> <span m=''1499320''>is</span>
  <span m=''1499790''>a</span> <span m=''1500190''>linear</span> <span m=''1501510''>vector</span>
  <span m=''1501970''>space</span> <span m=''1503610''>over</span> <span m=''1503860''>the</span>
  <span m=''1503960''>ground</span> <span m=''1504310''>field.</span> <span m=''1504660''>In</span>
  <span m=''1504790''>fact,</span> <span m=''1505160''>it''s</span> <span m=''1505320''>just</span>
  <span m=''1505530''>the</span> <span m=''1505610''>space</span> <span m=''1506060''>of</span>
  <span m=''1506250''>1-tuples,</span> <span m=''1506920''>2-tuples,</span> <span
  m=''1507620''>3-tuples,</span> <span m=''1508360''>2-tuples,</span> <span m=''1509060''>and</span>
  <span m=''1509140''>so</span> <span m=''1509360''>forth.</span> <span m=''1510570''>And</span>
  <span m=''1511770''>it</span> <span m=''1511940''>has</span> <span m=''1512150''>certain</span>
  <span m=''1512470''>dimension,</span> <span m=''1513540''>in</span> <span m=''1513710''>this</span>
  <span m=''1513930''>case,</span> <span m=''1514220''>equal</span> <span m=''1514490''>to</span>
  <span m=''1514650''>its</span> <span m=''1514830''>size.</span> </p><p><span m=''1516170''>And</span>
  <span m=''1516390''>if</span> <span m=''1516500''>you</span> <span m=''1516680''>calculate</span>
  <span m=''1517400''>the</span> <span m=''1517490''>dimensions</span> <span m=''1518350''>of--</span>
  <span m=''1519470''>call</span> <span m=''1519710''>this</span> <span m=''1519950''>the</span>
  <span m=''1520050''>state</span> <span m=''1520420''>space,</span> <span m=''1520970''>call</span>
  <span m=''1521260''>this</span> <span m=''1521530''>the</span> <span m=''1523430''>branch</span>
  <span m=''1524290''>constraint</span> <span m=''1524870''>code</span> <span m=''1525200''>if</span>
  <span m=''1525310''>you</span> <span m=''1525460''>like,</span> <span m=''1525785''>or</span>
  <span m=''1526110''>the</span> <span m=''1526440''>branch</span> <span m=''1526810''>space,</span>
  <span m=''1527770''>it''s</span> <span m=''1527890''>isomorphic,</span> <span m=''1529100''>the</span>
  <span m=''1529750''>dimensions</span> <span m=''1530460''>are</span> <span m=''1530890''>minimal</span>
  <span m=''1531320''>here</span> <span m=''1531590''>by</span> <span m=''1531800''>construction</span>
  <span m=''1533190''>from</span> <span m=''1533380''>the</span> <span m=''1533580''>trellis-oriented</span>
  <span m=''1534310''>generator</span> <span m=''1534790''>matrix.</span> <span m=''1536105''>If</span>
  <span m=''1536520''>we</span> <span m=''1536930''>want</span> <span m=''1537180''>to</span>
  <span m=''1537230''>know</span> <span m=''1539290''>the</span> <span m=''1539350''>minimal</span>
  <span m=''1539580''>size</span> <span m=''1540090''>of</span> <span m=''1540140''>the</span>
  <span m=''1540240''>state</span> <span m=''1540590''>space</span> <span m=''1541200''>at</span>
  <span m=''1541600''>time</span> <span m=''1543600''>4</span> <span m=''1544690''>here</span>
  <span m=''1545170''>in the</span> <span m=''1545410''>center,</span> <span m=''1546620''>we</span>
  <span m=''1547090''>just</span> <span m=''1547320''>calculate</span> <span m=''1547890''>the</span>
  <span m=''1547990''>number</span> <span m=''1548360''>of</span> <span m=''1548740''>generators</span>
  <span m=''1549080''>that</span> <span m=''1549420''>are</span> <span m=''1549580''>active</span>
  <span m=''1550000''>at</span> <span m=''1550110''>time</span> <span m=''1550420''>4,</span>
  <span m=''1550780''>and</span> <span m=''1550860''>that''s</span> <span m=''1551150''>precisely</span>
  <span m=''1552070''>what</span> <span m=''1552220''>we''re</span> <span m=''1552300''>going</span>
  <span m=''1552420''>to</span> <span m=''1552470''>get</span> <span m=''1552700''>over</span>
  <span m=''1552850''>there,</span> <span m=''1553170''>too,</span> <span m=''1553500''>by</span>
  <span m=''1553660''>our</span> <span m=''1553850''>construction.</span> </p><p><span
  m=''1554880''>If we</span> <span m=''1555120''>want</span> <span m=''1555350''>to</span>
  <span m=''1555910''>compute</span> <span m=''1556300''>the</span> <span m=''1556400''>dimension</span>
  <span m=''1557030''>of</span> <span m=''1557180''>the</span> <span m=''1557300''>branch</span>
  <span m=''1557710''>space</span> <span m=''1558045''>at</span> <span m=''1558380''>time</span>
  <span m=''1558720''>3,</span> <span m=''1559190''>it''s</span> <span m=''1559420''>the</span>
  <span m=''1559490''>number</span> <span m=''1559730''>of</span> <span m=''1559820''>active</span>
  <span m=''1561020''>generators</span> <span m=''1561630''>at</span> <span m=''1561830''>symbol</span>
  <span m=''1562180''>time</span> <span m=''1562490''>3.</span> <span m=''1562890''>There</span>
  <span m=''1563090''>are</span> <span m=''1563150''>3</span> <span m=''1563510''>active</span>
  <span m=''1563970''>ones,</span> <span m=''1564370''>and</span> <span m=''1564500''>we''ve</span>
  <span m=''1564730''>just</span> <span m=''1565930''>forced</span> <span m=''1566410''>this</span>
  <span m=''1566600''>to</span> <span m=''1566720''>have</span> <span m=''1566960''>that</span>
  <span m=''1567180''>structure.</span> <span m=''1568230''>So</span> <span m=''1572020''>this</span>
  <span m=''1572200''>is</span> <span m=''1572340''>a</span> <span m=''1572430''>normal</span>
  <span m=''1572850''>graph</span> <span m=''1573470''>of</span> <span m=''1573640''>a</span>
  <span m=''1575820''>minimal</span> <span m=''1576180''>trellis</span> <span m=''1576590''>realization</span>
  <span m=''1577270''>of</span> <span m=''1577350''>the</span> <span m=''1577630''>8,
  4</span> <span m=''1578020''>code.</span> <span m=''1579540''>OK?</span> </p><p><span
  m=''1581410''>So</span> <span m=''1581680''>we</span> <span m=''1581810''>can</span>
  <span m=''1581960''>clearly</span> <span m=''1582320''>do</span> <span m=''1582520''>that</span>
  <span m=''1582900''>for</span> <span m=''1583090''>any</span> <span m=''1583280''>code,</span>
  <span m=''1583900''>right?</span> <span m=''1584820''>For any</span> <span m=''1585080''>code,</span>
  <span m=''1585470''>we can</span> <span m=''1585560''>find a</span> <span m=''1585840''>trellis-oriented</span>
  <span m=''1586470''>generator</span> <span m=''1586890''>matrix.</span> <span m=''1587340''>We</span>
  <span m=''1587550''>can go</span> <span m=''1587700''>through</span> <span m=''1587900''>these</span>
  <span m=''1588050''>steps,</span> <span m=''1589040''>and</span> <span m=''1589170''>we''ll</span>
  <span m=''1589310''>always</span> <span m=''1589700''>come</span> <span m=''1589840''>up</span>
  <span m=''1590000''>with</span> <span m=''1590130''>something</span> <span m=''1590450''>that</span>
  <span m=''1590540''>looks</span> <span m=''1590800''>like</span> <span m=''1591050''>this</span>
  <span m=''1591330''>down</span> <span m=''1591610''>here.</span> </p><p><span m=''1594770''>OK,</span>
  <span m=''1595310''>now,</span> <span m=''1595900''>what</span> <span m=''1596170''>are</span>
  <span m=''1596250''>the</span> <span m=''1596400''>properties</span> <span m=''1597000''>of</span>
  <span m=''1597040''>this</span> <span m=''1597220''>graph?</span> <span m=''1597990''>Does
  it</span> <span m=''1598050''>have</span> <span m=''1598220''>cycles?</span> <span
  m=''1608600''>Does</span> <span m=''1609080''>this</span> <span m=''1609370''>graph</span>
  <span m=''1609690''>have</span> <span m=''1609830''>cycles?</span> <span m=''1610740''>Anybody?</span>
  <span m=''1612220''>&quot;No,&quot;</span> <span m=''1613440''>is</span> <span m=''1613790''>one</span>
  <span m=''1614020''>answer</span> <span m=''1614320''>I</span> <span m=''1614360''>get.</span>
  <span m=''1614580''>What''s</span> <span m=''1614780''>the</span> <span m=''1614910''>other</span>
  <span m=''1615080''>possible</span> <span m=''1615560''>answer?</span> <span m=''1617190''>How</span>
  <span m=''1617340''>many</span> <span m=''1617470''>people</span> <span m=''1617820''>say</span>
  <span m=''1618700''>no,</span> <span m=''1619010''>and how</span> <span m=''1619240''>many</span>
  <span m=''1619320''>people</span> <span m=''1619560''>say</span> <span m=''1619810''>yes?</span>
  <span m=''1620200''>I</span> <span m=''1620250''>want</span> <span m=''1620440''>to</span>
  <span m=''1620500''>see</span> <span m=''1620670''>a</span> <span m=''1620720''>show</span>
  <span m=''1620960''>of</span> <span m=''1621050''>hands.</span> <span m=''1621400''>How</span>
  <span m=''1621480''>many</span> <span m=''1621620''>people</span> <span m=''1622610''>think</span>
  <span m=''1622850''>this</span> <span m=''1623080''>graph</span> <span m=''1623440''>is</span>
  <span m=''1623580''>cycle</span> <span m=''1623970''>free?</span> <span m=''1627160''>OK,</span>
  <span m=''1627790''>and</span> <span m=''1627960''>how</span> <span m=''1628090''>many</span>
  <span m=''1628250''>people</span> <span m=''1629200''>think</span> <span m=''1629430''>that</span>
  <span m=''1629560''>it has</span> <span m=''1629810''>cycles?</span> </p><p><span
  m=''1632430''>OK,</span> <span m=''1633610''>the</span> <span m=''1633760''>majority</span>
  <span m=''1634220''>is</span> <span m=''1634350''>wrong.</span> <span m=''1635860''>This</span>
  <span m=''1636330''>graph</span> <span m=''1636710''>clearly</span> <span m=''1637070''>has</span>
  <span m=''1637270''>cycles.</span> <span m=''1637820''>Here</span> <span m=''1638040''>are
  two</span> <span m=''1638240''>edges</span> <span m=''1638600''>here,</span> <span
  m=''1638810''>and</span> <span m=''1638920''>here''s</span> <span m=''1639060''>a</span>
  <span m=''1639190''>cycle.</span> <span m=''1644180''>OK,</span> <span m=''1644650''>so</span>
  <span m=''1644980''>as</span> <span m=''1645110''>a</span> <span m=''1645240''>graph,</span>
  <span m=''1645780''>it</span> <span m=''1645910''>has</span> <span m=''1646050''>cycles</span>
  <span m=''1647230''>because</span> <span m=''1647640''>it</span> <span m=''1647710''>has</span>
  <span m=''1647920''>multiple</span> <span m=''1648380''>edges</span> <span m=''1649070''>going</span>
  <span m=''1649560''>between</span> <span m=''1649930''>these</span> <span m=''1650170''>constraints.</span>
  <span m=''1653130''>All right,</span> <span m=''1653580''>so</span> <span m=''1656440''>a</span>
  <span m=''1656570''>good</span> <span m=''1656840''>thing</span> <span m=''1657050''>to</span>
  <span m=''1657170''>do</span> <span m=''1657750''>is</span> <span m=''1657980''>to</span>
  <span m=''1658110''>make</span> <span m=''1658370''>this</span> <span m=''1658710''>a</span>
  <span m=''1659080''>cycle-free</span> <span m=''1659820''>graph,</span> <span m=''1662160''>and</span>
  <span m=''1662470''>that''s</span> <span m=''1662720''>just</span> <span m=''1662970''>a</span>
  <span m=''1663030''>matter</span> <span m=''1663460''>of</span> <span m=''1664470''>regarding</span>
  <span m=''1665860''>this</span> <span m=''1666460''>as</span> <span m=''1666880''>instead</span>
  <span m=''1667240''>of</span> <span m=''1667350''>two</span> <span m=''1667550''>binary</span>
  <span m=''1668000''>variables,</span> <span m=''1668610''>we</span> <span m=''1668730''>regard
  it</span> <span m=''1669160''>as</span> <span m=''1669300''>one</span> <span m=''1670190''>quaternary</span>
  <span m=''1670710''>variable.</span> </p><p><span m=''1673150''>All</span> <span
  m=''1673230''>right,</span> <span m=''1673570''>so</span> <span m=''1674250''>we''re</span>
  <span m=''1674450''>going</span> <span m=''1674550''>to</span> <span m=''1675020''>regard</span>
  <span m=''1675470''>this</span> <span m=''1676070''>as</span> <span m=''1681540''>a</span>
  <span m=''1681760''>single</span> <span m=''1682140''>binary</span> <span m=''1682540''>variable</span>
  <span m=''1682965''>of</span> <span m=''1683390''>dimension</span> <span m=''1683820''>one.</span>
  <span m=''1684350''>This</span> <span m=''1684620''>is a</span> <span m=''1684965''>quaternary</span>
  <span m=''1685860''>state</span> <span m=''1686220''>space.</span> <span m=''1686680''>There</span>
  <span m=''1686850''>are 4</span> <span m=''1687180''>possible</span> <span m=''1687660''>states</span>
  <span m=''1688140''>here.</span> <span m=''1688910''>So</span> <span m=''1689110''>the</span>
  <span m=''1689230''>dimension</span> <span m=''1689525''>of the</span> <span m=''1689820''>state</span>
  <span m=''1690230''>space</span> <span m=''1690610''>at this</span> <span m=''1690880''>time</span>
  <span m=''1691210''>is</span> <span m=''1691390''>2.</span> <span m=''1692620''>So</span>
  <span m=''1692860''>when</span> <span m=''1693030''>I</span> <span m=''1693110''>draw</span>
  <span m=''1693770''>abbreviations</span> <span m=''1694730''>like</span> <span m=''1695030''>this,</span>
  <span m=''1699220''>you</span> <span m=''1699400''>can</span> <span m=''1699570''>think</span>
  <span m=''1700930''>of</span> <span m=''1701050''>them</span> <span m=''1702790''>as</span>
  <span m=''1702960''>being</span> <span m=''1703330''>decomposable</span> <span m=''1704750''>into</span>
  <span m=''1705160''>binary</span> <span m=''1705550''>variables,</span> <span m=''1706090''>if</span>
  <span m=''1706240''>you</span> <span m=''1706400''>like.</span> </p><p><span m=''1707660''>But</span>
  <span m=''1707890''>the</span> <span m=''1708020''>advantage</span> <span m=''1708620''>of</span>
  <span m=''1708710''>drawing</span> <span m=''1709200''>them</span> <span m=''1709440''>as</span>
  <span m=''1710790''>larger</span> <span m=''1711210''>variables,</span> <span m=''1712520''>higher-valued</span>
  <span m=''1713230''>variables,</span> <span m=''1714620''>is</span> <span m=''1717102''>that</span>
  <span m=''1717560''>now</span> <span m=''1718090''>does</span> <span m=''1718230''>this</span>
  <span m=''1718460''>graph</span> <span m=''1718830''>have</span> <span m=''1718990''>a</span>
  <span m=''1719040''>cycle?</span> <span m=''1723790''>No,</span> <span m=''1724050''>this</span>
  <span m=''1724280''>graph</span> <span m=''1724590''>is</span> <span m=''1724680''>cycle</span>
  <span m=''1725140''>free.</span> <span m=''1727670''>I''ve</span> <span m=''1728000''>just</span>
  <span m=''1728230''>gotten</span> <span m=''1728460''>rid</span> <span m=''1728700''>of</span>
  <span m=''1728830''>all</span> <span m=''1729060''>the</span> <span m=''1729130''>possible</span>
  <span m=''1729610''>cycles.</span> <span m=''1731880''>How</span> <span m=''1732350''>can</span>
  <span m=''1732480''>you</span> <span m=''1732530''>tell</span> <span m=''1732810''>if</span>
  <span m=''1732900''>a</span> <span m=''1732970''>graph</span> <span m=''1733330''>is</span>
  <span m=''1733420''>cycle</span> <span m=''1733840''>free?</span> <span m=''1736670''>Various</span>
  <span m=''1737130''>ways.</span> <span m=''1737500''>I</span> <span m=''1737550''>think</span>
  <span m=''1737770''>the</span> <span m=''1737850''>most</span> <span m=''1738100''>elegant</span>
  <span m=''1738540''>one</span> <span m=''1738830''>is</span> <span m=''1739000''>to</span>
  <span m=''1739090''>say</span> <span m=''1739350''>if</span> <span m=''1739500''>every</span>
  <span m=''1739840''>edge is</span> <span m=''1740330''>by</span> <span m=''1740550''>itself</span>
  <span m=''1740930''>a</span> <span m=''1741400''>cut-set,</span> <span m=''1742190''>then</span>
  <span m=''1742310''>the</span> <span m=''1742400''>graph</span> <span m=''1742750''>is</span>
  <span m=''1742840''>cycle</span> <span m=''1743430''>free.</span> <span m=''1743740''>If</span>
  <span m=''1744010''>I</span> <span m=''1744110''>remove</span> <span m=''1745100''>any</span>
  <span m=''1745680''>edge,</span> <span m=''1747510''>then</span> <span m=''1747750''>I</span>
  <span m=''1747850''>decompose</span> <span m=''1748600''>the</span> <span m=''1748670''>graph</span>
  <span m=''1749080''>into</span> <span m=''1749380''>two</span> <span m=''1749590''>parts.</span>
  <span m=''1751010''>And</span> <span m=''1751100''>that''s</span> <span m=''1751320''>clearly</span>
  <span m=''1751680''>true</span> <span m=''1751980''>of this</span> <span m=''1752200''>graph.</span>
  <span m=''1752930''>We</span> <span m=''1753090''>don''t</span> <span m=''1753230''>really</span>
  <span m=''1753400''>have</span> <span m=''1753660''>to test the</span> <span m=''1754070''>half</span>
  <span m=''1754400''>edges.</span> </p><p><span m=''1755670''>In</span> <span m=''1756110''>fact,</span>
  <span m=''1756450''>this</span> <span m=''1756690''>is</span> <span m=''1757000''>kind</span>
  <span m=''1757230''>of</span> <span m=''1757400''>the</span> <span m=''1757670''>defining</span>
  <span m=''1758160''>concept</span> <span m=''1758880''>of</span> <span m=''1758970''>a</span>
  <span m=''1759020''>state</span> <span m=''1759390''>space.</span> <span m=''1760440''>A</span>
  <span m=''1760520''>state</span> <span m=''1760860''>space</span> <span m=''1761260''>is
  kind</span> <span m=''1761430''>of</span> <span m=''1761510''>a</span> <span m=''1761590''>cut</span>
  <span m=''1762050''>between</span> <span m=''1762400''>the</span> <span m=''1762480''>past</span>
  <span m=''1762980''>and</span> <span m=''1763040''>the</span> <span m=''1763140''>future.</span>
  <span m=''1764320''>When</span> <span m=''1764440''>we</span> <span m=''1764560''>asked</span>
  <span m=''1764850''>about</span> <span m=''1765040''>the</span> <span m=''1765130''>minimal</span>
  <span m=''1765490''>state</span> <span m=''1765860''>space,</span> <span m=''1766290''>we</span>
  <span m=''1766460''>asked</span> <span m=''1767980''>what''s</span> <span m=''1768390''>the</span>
  <span m=''1768980''>minimal</span> <span m=''1769650''>dimension</span> <span m=''1770240''>of</span>
  <span m=''1770350''>the</span> <span m=''1770470''>information,</span> <span m=''1771260''>the</span>
  <span m=''1771360''>state,</span> <span m=''1771830''>that</span> <span m=''1771920''>we</span>
  <span m=''1772020''>need</span> <span m=''1772170''>to</span> <span m=''1772320''>pass</span>
  <span m=''1773310''>from</span> <span m=''1773470''>the</span> <span m=''1773580''>past</span>
  <span m=''1774010''>to</span> <span m=''1774110''>the</span> <span m=''1774210''>future?</span>
  <span m=''1776730''>And</span> <span m=''1776870''>so</span> <span m=''1777060''>states</span>
  <span m=''1777970''>correspond</span> <span m=''1778550''>to</span> <span m=''1778640''>cuts.</span>
  <span m=''1779140''>If</span> <span m=''1779330''>we</span> <span m=''1779440''>make</span>
  <span m=''1780210''>each</span> <span m=''1783370''>state</span> <span m=''1783750''>space,</span>
  <span m=''1784150''>if</span> <span m=''1784270''>we</span> <span m=''1784360''>consider</span>
  <span m=''1784810''>it to</span> <span m=''1784920''>be</span> <span m=''1785060''>a</span>
  <span m=''1785120''>single</span> <span m=''1785560''>variable,</span> <span m=''1788380''>then</span>
  <span m=''1789220''>we</span> <span m=''1789410''>get</span> <span m=''1791000''>just</span>
  <span m=''1791350''>a</span> <span m=''1791480''>chain</span> <span m=''1791910''>graph</span>
  <span m=''1793110''>on</span> <span m=''1793420''>a</span> <span m=''1793830''>sequential</span>
  <span m=''1794490''>time</span> <span m=''1794810''>axis,</span> <span m=''1795560''>as</span>
  <span m=''1795850''>is</span> <span m=''1796070''>conventional</span> <span m=''1796430''>in</span>
  <span m=''1796790''>system</span> <span m=''1797230''>theory,</span> <span m=''1797890''>as</span>
  <span m=''1798020''>your</span> <span m=''1798220''>conventional</span> <span m=''1800220''>integer-time</span>
  <span m=''1800820''>axis</span> <span m=''1801450''>for</span> <span m=''1801610''>discrete</span>
  <span m=''1802100''>time</span> <span m=''1802400''>systems.</span> <span m=''1803310''>In</span>
  <span m=''1803390''>this</span> <span m=''1803610''>case,</span> <span m=''1804000''>it</span>
  <span m=''1804090''>only</span> <span m=''1804380''>has</span> <span m=''1804680''>a</span>
  <span m=''1804740''>finite</span> <span m=''1805170''>number</span> <span m=''1805430''>of</span>
  <span m=''1805510''>times</span> <span m=''1805900''>where</span> <span m=''1806040''>anything</span>
  <span m=''1806270''>happens.</span> <span m=''1807380''>But</span> <span m=''1807530''>you</span>
  <span m=''1807660''>can</span> <span m=''1807790''>think</span> <span m=''1807930''>of</span>
  <span m=''1808090''>this</span> <span m=''1808250''>as</span> <span m=''1808380''>part</span>
  <span m=''1808690''>of</span> <span m=''1808780''>the</span> <span m=''1809690''>infinite</span>
  <span m=''1810110''>set</span> <span m=''1810300''>of</span> <span m=''1810440''>integers.</span>
  <span m=''1811010''>And</span> <span m=''1811680''>so</span> <span m=''1811930''>this</span>
  <span m=''1812140''>is</span> <span m=''1812260''>everything</span> <span m=''1812570''>that</span>
  <span m=''1812690''>happens.</span> </p><p><span m=''1813150''>And a</span> <span
  m=''1813300''>trellis</span> <span m=''1813790''>is</span> <span m=''1813850''>always</span>
  <span m=''1814100''>going</span> <span m=''1814140''>to</span> <span m=''1814190''>be</span>
  <span m=''1814300''>very</span> <span m=''1814550''>boring.</span> <span m=''1815030''>It''s</span>
  <span m=''1815180''>always</span> <span m=''1815740''>going</span> <span m=''1815840''>to</span>
  <span m=''1815900''>look</span> <span m=''1816120''>like</span> <span m=''1816380''>this.</span>
  <span m=''1817600''>But</span> <span m=''1817770''>the</span> <span m=''1817870''>advantage</span>
  <span m=''1818580''>of</span> <span m=''1819610''>now</span> <span m=''1819900''>we</span>
  <span m=''1820020''>have</span> <span m=''1820290''>this</span> <span m=''1821160''>cycle-free</span>
  <span m=''1821850''>graph</span> <span m=''1822270''>realization,</span> <span m=''1822980''>we''ll</span>
  <span m=''1823090''>find</span> <span m=''1823370''>out</span> <span m=''1823660''>that</span>
  <span m=''1823750''>we</span> <span m=''1823890''>can</span> <span m=''1824080''>do</span>
  <span m=''1824800''>exact</span> <span m=''1825380''>decoding</span> <span m=''1826800''>of</span>
  <span m=''1827330''>cycle-free</span> <span m=''1827980''>realizations</span> <span
  m=''1828770''>using</span> <span m=''1829110''>the</span> <span m=''1829200''>sum-product</span>
  <span m=''1829870''>algorithm,</span> <span m=''1831480''>or</span> <span m=''1831700''>the</span>
  <span m=''1831810''>min-sum</span> <span m=''1832340''>algorithm,</span> <span m=''1833470''>which</span>
  <span m=''1833780''>in</span> <span m=''1833860''>this</span> <span m=''1834090''>case</span>
  <span m=''1835470''>kind</span> <span m=''1835670''>of</span> <span m=''1835870''>reduces
  to</span> <span m=''1836610''>the</span> <span m=''1836710''>Viterbi</span> <span
  m=''1837060''>algorithm</span> <span m=''1837710''>with</span> <span m=''1837830''>an</span>
  <span m=''1838650''>asterisk</span> <span m=''1838975''>on it.</span> </p><p><span
  m=''1840820''>And</span> <span m=''1841080''>the</span> <span m=''1841170''>cost</span>
  <span m=''1841640''>of</span> <span m=''1841730''>doing</span> <span m=''1842040''>that</span>
  <span m=''1842660''>is</span> <span m=''1843030''>that</span> <span m=''1844980''>now</span>
  <span m=''1845250''>have</span> <span m=''1845400''>to</span> <span m=''1845690''>instead</span>
  <span m=''1846050''>of</span> <span m=''1846160''>considering</span> <span m=''1846650''>two</span>
  <span m=''1846830''>binary</span> <span m=''1847260''>variables</span> <span m=''1847780''>here,</span>
  <span m=''1848020''>I</span> <span m=''1848070''>have</span> <span m=''1848190''>to</span>
  <span m=''1848370''>consider</span> <span m=''1848860''>a</span> <span m=''1848910''>single</span>
  <span m=''1850420''>variable</span> <span m=''1851020''>that</span> <span m=''1851110''>has</span>
  <span m=''1851320''>four</span> <span m=''1851550''>possible</span> <span m=''1852040''>states.</span>
  <span m=''1852500''>So</span> <span m=''1852690''>basically,</span> <span m=''1853330''>I''m</span>
  <span m=''1853420''>going</span> <span m=''1853610''>to</span> <span m=''1853650''>be</span>
  <span m=''1853810''>carrying</span> <span m=''1855090''>messages</span> <span m=''1856220''>which</span>
  <span m=''1856450''>are</span> <span m=''1856560''>vectors</span> <span m=''1858320''>indexed</span>
  <span m=''1858860''>by</span> <span m=''1859050''>the</span> <span m=''1859170''>state</span>
  <span m=''1859540''>space</span> <span m=''1860180''>across</span> <span m=''1860710''>here.</span>
  <span m=''1861370''>And</span> <span m=''1861710''>in</span> <span m=''1861960''>this</span>
  <span m=''1862190''>case,</span> <span m=''1862460''>the</span> <span m=''1862570''>vector</span>
  <span m=''1863000''>is</span> <span m=''1863120''>going</span> <span m=''1863230''>to
  have to</span> <span m=''1863500''>have</span> <span m=''1863590''>four</span> <span
  m=''1863970''>elements,</span> <span m=''1864590''>which</span> <span m=''1865090''>are</span>
  <span m=''1865310''>going</span> <span m=''1865440''>to</span> <span m=''1865570''>be</span>
  <span m=''1865700''>likelihoods</span> <span m=''1866390''>or</span> <span m=''1866780''>metrics</span>
  <span m=''1867310''>or</span> <span m=''1867420''>weights</span> <span m=''1867880''>of</span>
  <span m=''1867990''>some</span> <span m=''1868270''>kind.</span> <span m=''1870140''>It''s</span>
  <span m=''1870560''>basically</span> <span m=''1871100''>telling</span> <span m=''1871380''>me</span>
  <span m=''1871510''>what''s</span> <span m=''1871850''>the</span> <span m=''1872220''>weight</span>
  <span m=''1872550''>of</span> <span m=''1873200''>each</span> <span m=''1873430''>of</span>
  <span m=''1873510''>the</span> <span m=''1873600''>four</span> <span m=''1873910''>possible</span>
  <span m=''1874420''>survivors,</span> <span m=''1875160''>if</span> <span m=''1875270''>you</span>
  <span m=''1875560''>can</span> <span m=''1875750''>think of</span> <span m=''1875830''>the</span>
  <span m=''1875940''>trellis</span> <span m=''1876205''>that</span> <span m=''1876740''>goes</span>
  <span m=''1877190''>with</span> <span m=''1877380''>this.</span> <span m=''1877570''>Or</span>
  <span m=''1877660''>here,</span> <span m=''1877900''>I''m</span> <span m=''1877970''>going</span>
  <span m=''1878100''>to</span> <span m=''1878170''>need</span> <span m=''1878360''>to</span>
  <span m=''1878440''>carry</span> <span m=''1878770''>a</span> <span m=''1878820''>vector</span>
  <span m=''1879610''>with</span> <span m=''1879790''>8</span> <span m=''1879980''>elements.</span>
  <span m=''1880550''>So</span> <span m=''1884280''>it</span> <span m=''1884380''>takes</span>
  <span m=''1884660''>more</span> <span m=''1884900''>to</span> <span m=''1885660''>specify</span>
  <span m=''1886310''>a</span> <span m=''1886390''>vector</span> <span m=''1886740''>with</span>
  <span m=''1886900''>8</span> <span m=''1887050''>elements</span> <span m=''1887550''>than</span>
  <span m=''1887700''>3</span> <span m=''1887960''>vectors</span> <span m=''1888460''>each</span>
  <span m=''1888680''>with</span> <span m=''1890210''>two</span> <span m=''1890380''>elements.</span>
  </p><p><span m=''1890920''>So</span> <span m=''1891160''>by</span> <span m=''1891930''>aggregating</span>
  <span m=''1892560''>these,</span> <span m=''1893150''>I''ve</span> <span m=''1893390''>created</span>
  <span m=''1893920''>a</span> <span m=''1894130''>sort</span> <span m=''1894420''>of</span>
  <span m=''1894540''>exponential</span> <span m=''1895220''>complexity</span> <span
  m=''1895870''>situation</span> <span m=''1897090''>as</span> <span m=''1897280''>these</span>
  <span m=''1897380''>state</span> <span m=''1897810''>spaces</span> <span m=''1898280''>get</span>
  <span m=''1898630''>very</span> <span m=''1898890''>big.</span> <span m=''1900760''>But</span>
  <span m=''1901050''>on</span> <span m=''1901120''>the</span> <span m=''1901250''>other</span>
  <span m=''1901390''>hand,</span> <span m=''1901620''>I</span> <span m=''1901690''>get</span>
  <span m=''1901870''>cycle</span> <span m=''1902220''>freedom.</span> <span m=''1903048''>All
  right?</span> <span m=''1903924''>Yeah.</span> </p><p><span m=''1904362''>AUDIENCE:
  There''s</span> <span m=''1904800''>no real</span> <span m=''1905240''>difference</span>
  <span m=''1905545''>between</span> <span m=''1905850''>this</span> <span m=''1906130''>and
  what</span> <span m=''1906410''>you had before,</span> <span m=''1906910''>right?</span>
  </p><p><span m=''1911260''>PROFESSOR: As</span> <span m=''1911620''>President</span>
  <span m=''1912060''>Clinton</span> <span m=''1912410''>might</span> <span m=''1912590''>have</span>
  <span m=''1912690''>said,</span> <span m=''1913000''>it</span> <span m=''1913040''>depends</span>
  <span m=''1913420''>what</span> <span m=''1913580''>the</span> <span m=''1913670''>definition</span>
  <span m=''1914280''>of</span> <span m=''1914360''>&quot;real&quot;</span> <span
  m=''1914770''>is.</span> <span m=''1917405''>What</span> <span m=''1917880''>do
  you</span> <span m=''1917990''>mean</span> <span m=''1918180''>by</span> <span m=''1918330''>real</span>
  <span m=''1918800''>difference?</span> <span m=''1919920''>I</span> <span m=''1920100''>mean,</span>
  <span m=''1920350''>sure.</span> <span m=''1921780''>We</span> <span m=''1922350''>think</span>
  <span m=''1923200''>of</span> <span m=''1924070''>something</span> <span m=''1924590''>u1,</span>
  <span m=''1926090''>u2,</span> <span m=''1926740''>you</span> <span m=''1926870''>can</span>
  <span m=''1927010''>think</span> <span m=''1927160''>of that</span> <span m=''1927520''>as
  two</span> <span m=''1927670''>binary</span> <span m=''1928100''>variables</span>
  <span m=''1929500''>or</span> <span m=''1929690''>a</span> <span m=''1929740''>single</span>
  <span m=''1930410''>quaternary</span> <span m=''1930930''>variable.</span> <span
  m=''1931190''>Is</span> <span m=''1931450''>there</span> <span m=''1931520''>any</span>
  <span m=''1931630''>real</span> <span m=''1931990''>difference</span> <span m=''1932370''>between</span>
  <span m=''1932680''>that?</span> <span m=''1933540''>Well,</span> <span m=''1933810''>when
  we</span> <span m=''1933910''>actually</span> <span m=''1934240''>go</span> <span
  m=''1934410''>to the</span> <span m=''1934550''>implement</span> <span m=''1934990''>decoding</span>
  <span m=''1935470''>algorithms,</span> <span m=''1936010''>we''ll</span> <span m=''1936120''>find</span>
  <span m=''1936350''>there</span> <span m=''1936540''>is</span> <span m=''1936650''>a</span>
  <span m=''1936720''>real</span> <span m=''1937110''>difference</span> <span m=''1937620''>in</span>
  <span m=''1937740''>which</span> <span m=''1937970''>attitude</span> <span m=''1938295''>you</span>
  <span m=''1938620''>take.</span> <span m=''1940260''>But</span> <span m=''1940590''>mathematically,</span>
  <span m=''1943190''>it''s</span> <span m=''1943475''>a</span> <span m=''1943760''>distinction</span>
  <span m=''1944520''>with</span> <span m=''1944640''>hardly</span> <span m=''1944940''>any</span>
  <span m=''1945110''>difference.</span> </p><p><span m=''1945420''>AUDIENCE: So then</span>
  <span m=''1945730''>there''s</span> <span m=''1946202''>no</span> <span m=''1946674''>fundamental</span>
  <span m=''1947146''>difference</span> <span m=''1947618''>between</span> <span m=''1948090''>the</span>
  <span m=''1948562''>cycle</span> <span m=''1949040''>freeness</span> <span m=''1949325''>and</span>
  <span m=''1950110''>the</span> <span m=''1950610''>cycle--</span> </p><p><span m=''1951110''>PROFESSOR:
  No,</span> <span m=''1951200''>you''ll</span> <span m=''1951555''>see</span> <span
  m=''1951910''>this</span> <span m=''1953310''>real</span> <span m=''1953700''>difference--</span>
  <span m=''1956570''>there</span> <span m=''1956900''>is</span> <span m=''1957020''>another</span>
  <span m=''1957370''>real,</span> <span m=''1958280''>significant</span> <span m=''1958930''>difference.</span>
  <span m=''1959370''>If</span> <span m=''1959530''>I</span> <span m=''1959630''>drew</span>
  <span m=''1959850''>this</span> <span m=''1960090''>as</span> <span m=''1960210''>two</span>
  <span m=''1960370''>binary</span> <span m=''1960790''>variables,</span> <span m=''1961590''>I
  have a</span> <span m=''1961700''>graph</span> <span m=''1962050''>with</span> <span
  m=''1962170''>cycles.</span> <span m=''1962840''>And</span> <span m=''1964210''>we''ll</span>
  <span m=''1964380''>find</span> <span m=''1964650''>that</span> <span m=''1964770''>I</span>
  <span m=''1964840''>can''t</span> <span m=''1966350''>do</span> <span m=''1966590''>exact</span>
  <span m=''1967140''>decoding</span> <span m=''1967650''>with</span> <span m=''1967740''>a</span>
  <span m=''1967840''>sum-product</span> <span m=''1968510''>algorithm</span> <span
  m=''1969050''>on</span> <span m=''1969220''>a</span> <span m=''1969610''>graph</span>
  <span m=''1969940''>with</span> <span m=''1970050''>cycles.</span> <span m=''1971960''>So</span>
  <span m=''1972090''>if</span> <span m=''1972200''>I</span> <span m=''1972280''>tried</span>
  <span m=''1972640''>to</span> <span m=''1972710''>apply</span> <span m=''1974050''>that</span>
  <span m=''1974280''>algorithm</span> <span m=''1974790''>to</span> <span m=''1974920''>this,</span>
  <span m=''1975250''>I''d</span> <span m=''1975360''>sort</span> <span m=''1975620''>of</span>
  <span m=''1975720''>iterate</span> <span m=''1976110''>around</span> <span m=''1976350''>this</span>
  <span m=''1976510''>little</span> <span m=''1976670''>cycle.</span> </p><p><span
  m=''1978490''>Whereas</span> <span m=''1978910''>if</span> <span m=''1979110''>I</span>
  <span m=''1979970''>agglomerate</span> <span m=''1980660''>them</span> <span m=''1980870''>into</span>
  <span m=''1981060''>a</span> <span m=''1981120''>single</span> <span m=''1981490''>variable,</span>
  <span m=''1982110''>I</span> <span m=''1982200''>get</span> <span m=''1982360''>rid</span>
  <span m=''1982530''>of</span> <span m=''1982590''>that</span> <span m=''1982820''>behavior.</span>
  <span m=''1983630''>And</span> <span m=''1983880''>I can</span> <span m=''1983990''>summarize</span>
  <span m=''1984640''>everything</span> <span m=''1985960''>in</span> <span m=''1986110''>four</span>
  <span m=''1986380''>values.</span> <span m=''1988940''>So</span> <span m=''1989160''>in</span>
  <span m=''1989200''>that</span> <span m=''1989390''>sense,</span> <span m=''1989750''>it''s</span>
  <span m=''1989960''>a</span> <span m=''1990010''>huge</span> <span m=''1990290''>difference.</span>
  </p><p><span m=''1991344''>AUDIENCE: Can I</span> <span m=''1991768''>always</span>
  <span m=''1993040''>transform</span> <span m=''1993490''>this</span> <span m=''1994202''>whole
  graph</span> <span m=''1994560''>into</span> <span m=''1994820''>cycle-free</span>
  <span m=''1995287''>graph</span> <span m=''1995754''>using</span> <span m=''1996221''>this
  kind of</span> <span m=''1996688''>technique?</span> </p><p><span m=''1997622''>PROFESSOR:
  I didn''t</span> <span m=''1998090''>get the</span> <span m=''1998740''>first</span>
  <span m=''1999010''>part</span> <span m=''1999170''>of</span> <span m=''1999250''>your</span>
  <span m=''1999400''>question.</span> </p><p><span m=''2000070''>AUDIENCE: Can I</span>
  <span m=''2000260''>always</span> <span m=''2000470''>transform</span> <span m=''2002365''>the</span>
  <span m=''2002650''>graph</span> <span m=''2002980''>with</span> <span m=''2003190''>cycles</span>
  <span m=''2003380''>to a</span> <span m=''2003600''>cycle-free</span> <span m=''2003830''>graph</span>
  <span m=''2004437''>using</span> <span m=''2004844''>this--</span> <span m=''2005660''>combining</span>
  <span m=''2006023''>those--</span> </p><p><span m=''2006750''>PROFESSOR: Yeah,</span>
  <span m=''2007200''>OK.</span> <span m=''2007700''>So</span> <span m=''2008200''>this</span>
  <span m=''2008660''>agglomeration</span> <span m=''2009490''>technique</span> <span
  m=''2011120''>of</span> <span m=''2011550''>drawing</span> <span m=''2014760''>lines</span>
  <span m=''2015180''>around</span> <span m=''2015430''>sub-graphs</span> <span m=''2016095''>and
  then</span> <span m=''2016520''>considering</span> <span m=''2017510''>everything</span>
  <span m=''2017970''>inside</span> <span m=''2018460''>there</span> <span m=''2018740''>to</span>
  <span m=''2018880''>be</span> <span m=''2019070''>a</span> <span m=''2019160''>constraint,</span>
  <span m=''2020500''>and</span> <span m=''2020780''>all</span> <span m=''2021000''>the</span>
  <span m=''2021080''>variables</span> <span m=''2021790''>coming</span> <span m=''2022160''>out--</span>
  <span m=''2023480''>well,</span> <span m=''2023810''>it</span> <span m=''2023880''>depends</span>
  <span m=''2024210''>on</span> <span m=''2024280''>their</span> <span m=''2024470''>topology,</span>
  <span m=''2025200''>but</span> <span m=''2026130''>I</span> <span m=''2026250''>can</span>
  <span m=''2026440''>group</span> <span m=''2026780''>the</span> <span m=''2026900''>variables</span>
  <span m=''2027440''>coming</span> <span m=''2027740''>out</span> <span m=''2027970''>however</span>
  <span m=''2028720''>I</span> <span m=''2028940''>want--</span> <span m=''2029420''>yes,</span>
  <span m=''2029740''>I can</span> <span m=''2029930''>always</span> <span m=''2030250''>do</span>
  <span m=''2030380''>that.</span> </p><p><span m=''2031161''>AUDIENCE: So</span>
  <span m=''2031652''>we</span> <span m=''2032143''>can</span> <span m=''2032634''>always</span>
  <span m=''2033125''>do that for</span> <span m=''2033616''>things</span> <span m=''2034107''>[UNINTELLIGIBLE]</span>
  <span m=''2036688''>transform</span> <span m=''2037186''>the graph</span> <span
  m=''2037684''>into</span> <span m=''2038182''>cycle free.</span> </p><p><span m=''2038680''>PROFESSOR:
  Right.</span> <span m=''2040180''>But</span> <span m=''2040510''>we</span> <span
  m=''2040680''>may</span> <span m=''2040900''>find</span> <span m=''2042730''>that</span>
  <span m=''2045810''>to</span> <span m=''2045930''>make</span> <span m=''2046100''>it</span>
  <span m=''2046210''>cycle</span> <span m=''2046530''>free,</span> <span m=''2046840''>I</span>
  <span m=''2046880''>then</span> <span m=''2047080''>have</span> <span m=''2047300''>to</span>
  <span m=''2048020''>aggregate</span> <span m=''2048275''>all the</span> <span m=''2048530''>edges</span>
  <span m=''2049170''>into</span> <span m=''2049409''>a</span> <span m=''2049460''>single</span>
  <span m=''2049870''>edge</span> <span m=''2050650''>between</span> <span m=''2051250''>any</span>
  <span m=''2051780''>two</span> <span m=''2051940''>parts</span> <span m=''2052429''>of
  the</span> <span m=''2052500''>graph.</span> <span m=''2053480''>And</span> <span
  m=''2053699''>that</span> <span m=''2053920''>may</span> <span m=''2054300''>radically</span>
  <span m=''2054929''>increase</span> <span m=''2055330''>the</span> <span m=''2055429''>complexity.</span>
  <span m=''2055799''>And</span> <span m=''2056170''>I''ll</span> <span m=''2056280''>give</span>
  <span m=''2056449''>you</span> <span m=''2056540''>several</span> <span m=''2057090''>examples</span>
  <span m=''2057690''>of</span> <span m=''2057750''>that</span> <span m=''2058010''>today.</span>
  <span m=''2060530''>So</span> <span m=''2060840''>these</span> <span m=''2061940''>little</span>
  <span m=''2062150''>fine</span> <span m=''2062480''>points</span> <span m=''2063130''>all
  of a</span> <span m=''2063429''>sudden</span> <span m=''2063790''>loom</span> <span
  m=''2064130''>large</span> <span m=''2064500''>when we</span> <span m=''2064659''>actually</span>
  <span m=''2064989''>come</span> <span m=''2065210''>to</span> <span m=''2065340''>build</span>
  <span m=''2065580''>something.</span> </p><p><span m=''2067650''>Let</span> <span
  m=''2068010''>me</span> <span m=''2069500''>give</span> <span m=''2069650''>you</span>
  <span m=''2069719''>another</span> <span m=''2069940''>example</span> <span m=''2070210''>of</span>
  <span m=''2070480''>that.</span> <span m=''2070699''>A</span> <span m=''2070730''>very</span>
  <span m=''2070989''>fine</span> <span m=''2071320''>example</span> <span m=''2071870''>would</span>
  <span m=''2072040''>be</span> <span m=''2072210''>to</span> <span m=''2072300''>say,</span>
  <span m=''2072739''>what</span> <span m=''2072929''>does</span> <span m=''2073110''>sectionalization</span>
  <span m=''2073989''>consist</span> <span m=''2074374''>of?</span> <span m=''2075639''>We</span>
  <span m=''2075830''>talked</span> <span m=''2076150''>about</span> <span m=''2076380''>sectionalization.</span>
  <span m=''2077320''>Suppose</span> <span m=''2078400''>we</span> <span m=''2078540''>want</span>
  <span m=''2078800''>to</span> <span m=''2079810''>get</span> <span m=''2079960''>a</span>
  <span m=''2080030''>trellis</span> <span m=''2080489''>graph</span> <span m=''2080960''>for</span>
  <span m=''2083179''>a</span> <span m=''2083409''>4-section</span> <span m=''2084120''>trellis,</span>
  <span m=''2085400''>where</span> <span m=''2085780''>we</span> <span m=''2085949''>take</span>
  <span m=''2086650''>pairs</span> <span m=''2087090''>of</span> <span m=''2087230''>variables.</span>
  <span m=''2088313''>Well,</span> <span m=''2088735''>the</span> <span m=''2089159''>graph</span>
  <span m=''2089560''>realization</span> <span m=''2090400''>of</span> <span m=''2090650''>that</span>
  <span m=''2091030''>is</span> <span m=''2091150''>simply</span> <span m=''2091550''>obtained</span>
  <span m=''2092000''>by</span> <span m=''2092230''>agglomerating</span> <span m=''2095810''>pairs</span>
  <span m=''2096219''>of</span> <span m=''2096389''>these</span> <span m=''2096699''>blocks,</span>
  <span m=''2097580''>like</span> <span m=''2097860''>that.</span> </p><p><span m=''2099450''>OK,</span>
  <span m=''2101100''>so</span> <span m=''2102660''>let</span> <span m=''2102810''>me</span>
  <span m=''2102940''>do</span> <span m=''2103140''>that,</span> <span m=''2103490''>and</span>
  <span m=''2103620''>then</span> <span m=''2103790''>let</span> <span m=''2103940''>me</span>
  <span m=''2104070''>see</span> <span m=''2104480''>what</span> <span m=''2104680''>I''ve</span>
  <span m=''2104880''>got.</span> <span m=''2105250''>I''ve</span> <span m=''2105470''>now</span>
  <span m=''2105740''>got</span> <span m=''2106870''>here,</span> <span m=''2107320''>a</span>
  <span m=''2107480''>constraint</span> <span m=''2108220''>that</span> <span m=''2108340''>affects</span>
  <span m=''2109010''>two</span> <span m=''2109210''>variables.</span> <span m=''2110580''>Well,</span>
  <span m=''2110740''>first</span> <span m=''2111090''>of</span> <span m=''2111190''>all,</span>
  <span m=''2111740''>I''ve</span> <span m=''2112090''>now</span> <span m=''2112390''>got</span>
  <span m=''2112620''>only</span> <span m=''2112850''>two</span> <span m=''2114040''>visible</span>
  <span m=''2115440''>bits</span> <span m=''2115930''>in</span> <span m=''2116100''>each</span>
  <span m=''2116300''>of</span> <span m=''2116380''>the</span> <span m=''2116460''>state</span>
  <span m=''2116800''>variables.</span> <span m=''2118430''>Here</span> <span m=''2118860''>I
  have</span> <span m=''2119040''>u1,</span> <span m=''2119220''>u2,</span> <span
  m=''2119600''>here I have</span> <span m=''2119930''>u2, u3,</span> <span m=''2121060''>here
  i have</span> <span m=''2121390''>u3, u4.</span> <span m=''2122960''>So</span> <span
  m=''2124690''>we</span> <span m=''2125540''>get</span> <span m=''2125720''>rid</span>
  <span m=''2125920''>of</span> <span m=''2126000''>some</span> <span m=''2126260''>of</span>
  <span m=''2126340''>this</span> <span m=''2126880''>state</span> <span m=''2127240''>complexity.</span>
  <span m=''2128830''>We</span> <span m=''2128950''>did</span> <span m=''2129080''>this</span>
  <span m=''2129520''>trick</span> <span m=''2129850''>in</span> <span m=''2129920''>another</span>
  <span m=''2130220''>way</span> <span m=''2130420''>before,</span> <span m=''2131080''>by</span>
  <span m=''2131385''>sectionalization.</span> </p><p><span m=''2133600''>So</span>
  <span m=''2133790''>we</span> <span m=''2133910''>get</span> <span m=''2134070''>rid
  of</span> <span m=''2134230''>a</span> <span m=''2134340''>lot</span> <span m=''2134580''>of</span>
  <span m=''2134640''>state</span> <span m=''2135030''>spaces,</span> <span m=''2135510''>including</span>
  <span m=''2135880''>ones</span> <span m=''2136240''>that</span> <span m=''2136370''>are</span>
  <span m=''2136950''>big.</span> <span m=''2139140''>Let''s</span> <span m=''2139300''>see,</span>
  <span m=''2139580''>what</span> <span m=''2139740''>do</span> <span m=''2139780''>we</span>
  <span m=''2139910''>have</span> <span m=''2140230''>here?</span> <span m=''2140590''>This</span>
  <span m=''2140910''>is</span> <span m=''2141340''>now</span> <span m=''2142550''>a</span>
  <span m=''2142720''>code</span> <span m=''2143120''>which</span> <span m=''2143430''>has</span>
  <span m=''2144680''>got</span> <span m=''2144950''>two</span> <span m=''2145090''>bits</span>
  <span m=''2145410''>coming</span> <span m=''2145700''>in,</span> <span m=''2145960''>two</span>
  <span m=''2146160''>bits</span> <span m=''2146380''>coming</span> <span m=''2146720''>out.</span>
  <span m=''2146960''>It''s</span> <span m=''2147070''>a</span> <span m=''2147410''>4,
  2</span> <span m=''2148130''>code.</span> <span m=''2148500''>It''s</span> <span
  m=''2148700''>basically</span> <span m=''2149230''>controlled</span> <span m=''2149750''>by</span>
  <span m=''2150280''>u1</span> <span m=''2150480''>and</span> <span m=''2150790''>u2.</span>
  <span m=''2151690''>Probably</span> <span m=''2152050''>y0</span> <span m=''2152480''>and</span>
  <span m=''2152580''>y1</span> <span m=''2153140''>are</span> <span m=''2153690''>some</span>
  <span m=''2153960''>simple</span> <span m=''2154340''>linear</span> <span m=''2154670''>function</span>
  <span m=''2155110''>of</span> <span m=''2156210''>u1</span> <span m=''2156400''>and</span>
  <span m=''2156700''>u2.</span> <span m=''2157320''>So</span> <span m=''2157600''>this</span>
  <span m=''2157810''>is</span> <span m=''2157930''>a</span> <span m=''2158000''>4,
  2</span> <span m=''2158890''>constraint</span> <span m=''2159480''>code.</span>
  <span m=''2160300''>It</span> <span m=''2160640''>controls</span> <span m=''2161120''>these</span>
  <span m=''2161380''>two</span> <span m=''2161550''>bits</span> <span m=''2162400''>and</span>
  <span m=''2162570''>these</span> <span m=''2162770''>two</span> <span m=''2162910''>state</span>
  <span m=''2163300''>bits,</span> <span m=''2165440''>these</span> <span m=''2165870''>two</span>
  <span m=''2166100''>symbol</span> <span m=''2166500''>bits,</span> <span m=''2166640''>and</span>
  <span m=''2166820''>these</span> <span m=''2167210''>two</span> <span m=''2167370''>state</span>
  <span m=''2167700''>bits.</span> </p><p><span m=''2168100''>What</span> <span m=''2168280''>is</span>
  <span m=''2168370''>this</span> <span m=''2168590''>over</span> <span m=''2168830''>here</span>
  <span m=''2169070''>now?</span> <span m=''2169340''>We''ve</span> <span m=''2169550''>got</span>
  <span m=''2169760''>2,</span> <span m=''2170370''>2,</span> <span m=''2173130''>2.</span>
  <span m=''2173530''>So</span> <span m=''2173830''>this</span> <span m=''2174090''>is</span>
  <span m=''2174260''>going</span> <span m=''2174370''>to</span> <span m=''2174490''>be</span>
  <span m=''2175400''>a</span> <span m=''2175570''>code</span> <span m=''2176070''>of</span>
  <span m=''2176310''>length</span> <span m=''2176710''>6.</span> <span m=''2178510''>And</span>
  <span m=''2178870''>what</span> <span m=''2179110''>dimension?</span> <span m=''2179940''>This</span>
  <span m=''2180350''>is,</span> <span m=''2181000''>remember,</span> <span m=''2181410''>u2,</span>
  <span m=''2181940''>u3.</span> <span m=''2183090''>So</span> <span m=''2183290''>this</span>
  <span m=''2183480''>whole</span> <span m=''2183690''>behavior</span> <span m=''2183985''>here</span>
  <span m=''2184280''>is</span> <span m=''2184380''>affected</span> <span m=''2184820''>by</span>
  <span m=''2184980''>u1,</span> <span m=''2185460''>u2,</span> <span m=''2185600''>and</span>
  <span m=''2185930''>u3,</span> <span m=''2186590''>it</span> <span m=''2186880''>has</span>
  <span m=''2187170''>dimension</span> <span m=''2187620''>3.</span> </p><p><span
  m=''2188600''>Or</span> <span m=''2188760''>there''s</span> <span m=''2188990''>a</span>
  <span m=''2189040''>shortcut</span> <span m=''2189630''>I</span> <span m=''2189700''>can</span>
  <span m=''2189860''>do</span> <span m=''2190100''>here,</span> <span m=''2191250''>because</span>
  <span m=''2191590''>this</span> <span m=''2191790''>is a</span> <span m=''2192200''>self-dual</span>
  <span m=''2192570''>code,</span> <span m=''2192870''>all</span> <span m=''2192980''>of</span>
  <span m=''2193280''>these</span> <span m=''2193540''>little</span> <span m=''2193790''>codes</span>
  <span m=''2194160''>are</span> <span m=''2194230''>going</span> <span m=''2194380''>to</span>
  <span m=''2194470''>be</span> <span m=''2195840''>self-dual.</span> <span m=''2196730''>Well,</span>
  <span m=''2197180''>they''re</span> <span m=''2197600''>not going</span> <span m=''2197780''>to
  be</span> <span m=''2198210''>self-dual,</span> <span m=''2198350''>but</span> <span
  m=''2198550''>they''re</span> <span m=''2198660''>going</span> <span m=''2198830''>to
  be</span> <span m=''2198930''>rate</span> <span m=''2199120''>1/2.</span> <span
  m=''2201250''>Half</span> <span m=''2201550''>as</span> <span m=''2201700''>many</span>
  <span m=''2202860''>bits</span> <span m=''2203250''>here</span> <span m=''2203860''>as</span>
  <span m=''2204120''>they</span> <span m=''2204250''>do</span> <span m=''2204440''>here.</span>
  <span m=''2207410''>But</span> <span m=''2208305''>that''s</span> <span m=''2208760''>another</span>
  <span m=''2209180''>duality</span> <span m=''2209670''>theorem</span> <span m=''2210010''>that</span>
  <span m=''2210120''>we</span> <span m=''2210230''>won''t</span> <span m=''2210340''>prove.</span>
  </p><p><span m=''2212570''>OK,</span> <span m=''2213100''>and</span> <span m=''2213610''>symmetrically,</span>
  <span m=''2214070''>we</span> <span m=''2214530''>get</span> <span m=''2215350''>another</span>
  <span m=''2215670''>code</span> <span m=''2216020''>here,</span> <span m=''2216810''>which</span>
  <span m=''2217090''>is</span> <span m=''2217190''>a</span> <span m=''2217270''>6,
  3</span> <span m=''2217980''>code,</span> <span m=''2219150''>and</span> <span m=''2219390''>another</span>
  <span m=''2219640''>one</span> <span m=''2219820''>here.</span> <span m=''2221350''>So</span>
  <span m=''2221660''>we</span> <span m=''2221790''>can</span> <span m=''2221920''>do</span>
  <span m=''2222090''>this.</span> <span m=''2223940''>The</span> <span m=''2224220''>reason</span>
  <span m=''2224540''>I</span> <span m=''2224620''>call</span> <span m=''2224970''>this</span>
  <span m=''2225090''>styles</span> <span m=''2225980''>of</span> <span m=''2226100''>realization</span>
  <span m=''2226850''>is there''s</span> <span m=''2227210''>obviously</span> <span
  m=''2227670''>a</span> <span m=''2227740''>lot</span> <span m=''2227930''>of</span>
  <span m=''2228010''>freedom</span> <span m=''2228900''>in</span> <span m=''2229040''>how</span>
  <span m=''2229230''>we</span> <span m=''2229350''>want to</span> <span m=''2229680''>depict</span>
  <span m=''2230090''>the</span> <span m=''2230230''>code.</span> <span m=''2231110''>And</span>
  <span m=''2231540''>depending</span> <span m=''2231990''>on</span> <span m=''2232060''>how</span>
  <span m=''2232250''>we</span> <span m=''2232390''>depict</span> <span m=''2232890''>it,</span>
  <span m=''2233850''>when</span> <span m=''2234080''>we</span> <span m=''2234180''>get</span>
  <span m=''2234350''>to</span> <span m=''2234440''>decoding</span> <span m=''2234890''>algorithms,</span>
  <span m=''2235420''>it</span> <span m=''2235510''>may</span> <span m=''2235650''>affect</span>
  <span m=''2236010''>the</span> <span m=''2236100''>complexity</span> <span m=''2236480''>of
  the</span> <span m=''2236860''>algorithms.</span> <span m=''2237720''>So</span>
  <span m=''2237910''>we</span> <span m=''2237990''>want</span> <span m=''2238160''>to</span>
  <span m=''2238220''>find</span> <span m=''2238460''>a</span> <span m=''2238540''>nice</span>
  <span m=''2238900''>way</span> <span m=''2239100''>of</span> <span m=''2239330''>depicting</span>
  <span m=''2239625''>it.</span> </p><p><span m=''2240380''>AUDIENCE: I don''t</span>
  <span m=''2240840''>understand</span> <span m=''2241300''>why you--</span> <span
  m=''2241760''>so</span> <span m=''2242220''>you want</span> <span m=''2243140''>the</span>
  <span m=''2243620''>... freedom ...</span> <span m=''2243840''>is</span> <span m=''2244115''>[INAUDIBLE],</span>
  <span m=''2244390''>because</span> <span m=''2244630''>you would</span> <span m=''2245060''>only</span>
  <span m=''2245190''>have</span> <span m=''2245330''>two</span> <span m=''2245635''>[UNINTELLIGIBLE]</span>
  <span m=''2245940''>to be used</span> <span m=''2246130''>[UNINTELLIGIBLE].</span>
  <span m=''2246470''>And</span> <span m=''2246870''>then you</span> <span m=''2247290''>have</span>
  <span m=''2247650''>two</span> <span m=''2248010''>[UNINTELLIGIBLE]</span> <span
  m=''2248922''>u1 and</span> <span m=''2249380''>u2.</span> <span m=''2250320''>[UNINTELLIGIBLE]</span>
  <span m=''2250450''>u2</span> <span m=''2250640''>and</span> <span m=''2250870''>3.</span>
  </p><p><span m=''2251730''>PROFESSOR: There are</span> <span m=''2252030''>two bits</span>
  <span m=''2252330''>here,</span> <span m=''2253740''>two</span> <span m=''2253890''>bits</span>
  <span m=''2254180''>here,</span> <span m=''2255810''>two</span> <span m=''2255950''>bits</span>
  <span m=''2256220''>here.</span> </p><p><span m=''2257080''>AUDIENCE: But that''s</span>
  <span m=''2257490''>6.</span> <span m=''2257900''>That''s</span> <span m=''2258310''>6.</span>
  <span m=''2258720''>[INAUDIBLE]</span> </p><p><span m=''2259050''>PROFESSOR: Weight
  6,</span> <span m=''2259380''>all right.</span> </p><p><span m=''2260290''>AUDIENCE:
  [INAUDIBLE]</span> <span m=''2260630''>freedom</span> <span m=''2260970''>that you</span>
  <span m=''2261310''>talk about.</span> </p><p><span m=''2261756''>PROFESSOR: How</span>
  <span m=''2262202''>many</span> <span m=''2262650''>possibilities</span> <span m=''2263380''>are</span>
  <span m=''2263470''>there</span> <span m=''2263670''>for</span> <span m=''2263780''>these</span>
  <span m=''2263910''>6</span> <span m=''2264290''>bits?</span> <span m=''2264640''>I''ve</span>
  <span m=''2264740''>got</span> <span m=''2264890''>to</span> <span m=''2264970''>consider</span>
  <span m=''2265360''>all</span> <span m=''2265550''>possible</span> <span m=''2265950''>combinations</span>
  <span m=''2266550''>of</span> <span m=''2266640''>u1,</span> <span m=''2267280''>u2,</span>
  <span m=''2267810''>and</span> <span m=''2268140''>u3</span> <span m=''2269210''>to</span>
  <span m=''2269750''>drive</span> <span m=''2270260''>what''s</span> <span m=''2270510''>happening</span>
  <span m=''2270970''>in</span> <span m=''2271080''>these</span> <span m=''2271330''>two</span>
  <span m=''2271500''>times.</span> <span m=''2274712''>If</span> <span m=''2275150''>I</span>
  <span m=''2275270''>go</span> <span m=''2275480''>back</span> <span m=''2275810''>here</span>
  <span m=''2276100''>and</span> <span m=''2276170''>look</span> <span m=''2276370''>at</span>
  <span m=''2276490''>those</span> <span m=''2276770''>two</span> <span m=''2276960''>times,</span>
  <span m=''2278230''>I</span> <span m=''2278370''>see</span> <span m=''2278750''>that</span>
  <span m=''2278940''>there</span> <span m=''2279170''>are</span> <span m=''2279220''>three</span>
  <span m=''2279540''>generators</span> <span m=''2279875''>that</span> <span m=''2280210''>I''ve
  got to</span> <span m=''2280620''>consider,</span> <span m=''2283220''>these</span>
  <span m=''2283560''>three.</span> <span m=''2284890''>All</span> <span m=''2285000''>right,</span>
  <span m=''2285350''>so</span> <span m=''2285700''>for</span> <span m=''2285990''>all</span>
  <span m=''2286390''>eight</span> <span m=''2286670''>possible</span> <span m=''2287840''>linear</span>
  <span m=''2288140''>combinations</span> <span m=''2288930''>of</span> <span m=''2289050''>those</span>
  <span m=''2289480''>three</span> <span m=''2289730''>generators,</span> <span m=''2290500''>I''ll</span>
  <span m=''2290930''>get</span> <span m=''2291810''>different</span> <span m=''2292250''>combinations</span>
  <span m=''2293090''>of</span> <span m=''2293180''>these</span> <span m=''2293500''>six</span>
  <span m=''2293765''>bits</span> <span m=''2294030''>here.</span> </p><p><span m=''2302650''>And</span>
  <span m=''2302970''>I</span> <span m=''2303050''>can</span> <span m=''2303160''>go</span>
  <span m=''2303340''>further.</span> <span m=''2305030''>Actually,</span> <span m=''2305650''>at</span>
  <span m=''2305810''>the</span> <span m=''2305920''>end</span> <span m=''2306060''>of</span>
  <span m=''2306130''>the</span> <span m=''2306210''>day,</span> <span m=''2306450''>I</span>
  <span m=''2306550''>concluded</span> <span m=''2307670''>here,</span> <span m=''2308280''>we</span>
  <span m=''2308770''>said</span> <span m=''2309050''>the</span> <span m=''2309220''>idea</span>
  <span m=''2309580''>of</span> <span m=''2309680''>sectionalization</span> <span
  m=''2310620''>was</span> <span m=''2310940''>to</span> <span m=''2311400''>sectionalize</span>
  <span m=''2312150''>as</span> <span m=''2312290''>far</span> <span m=''2312590''>as</span>
  <span m=''2312720''>possible</span> <span m=''2313890''>without</span> <span m=''2314260''>increasing</span>
  <span m=''2314780''>the</span> <span m=''2314880''>branch</span> <span m=''2315240''>complexity,</span>
  <span m=''2316440''>which</span> <span m=''2316820''>we''ve</span> <span m=''2317040''>now</span>
  <span m=''2317210''>translated</span> <span m=''2317970''>into</span> <span m=''2318130''>this</span>
  <span m=''2318290''>constraint</span> <span m=''2318800''>code</span> <span m=''2319070''>complexity.</span>
  <span m=''2320550''>And</span> <span m=''2320870''>so</span> <span m=''2322080''>it''s</span>
  <span m=''2322200''>even</span> <span m=''2322420''>better</span> <span m=''2322910''>to</span>
  <span m=''2323070''>just</span> <span m=''2323310''>keep</span> <span m=''2323680''>aggregating.</span>
  <span m=''2325310''>Consider</span> <span m=''2325530''>the</span> <span m=''2325860''>first</span>
  <span m=''2326540''>half.</span> <span m=''2327760''>And</span> <span m=''2328170''>this</span>
  <span m=''2328430''>is</span> <span m=''2328610''>1,</span> <span m=''2328800''>2,</span>
  <span m=''2328980''>3,</span> <span m=''2329240''>4,</span> <span m=''2329900''>two</span>
  <span m=''2330070''>bits</span> <span m=''2330410''>there</span> <span m=''2330670''>is</span>
  <span m=''2330740''>still</span> <span m=''2331070''>only</span> <span m=''2331220''>a</span>
  <span m=''2331320''>6, 3</span> <span m=''2331630''>code.</span> <span m=''2333800''>And</span>
  <span m=''2334130''>the</span> <span m=''2334200''>second</span> <span m=''2334560''>half</span>
  <span m=''2335000''>is</span> <span m=''2335370''>still</span> <span m=''2335740''>only
  a</span> <span m=''2336070''>6, 3</span> <span m=''2336340''>code.</span> </p><p><span
  m=''2338390''>When</span> <span m=''2338520''>we</span> <span m=''2338640''>get</span>
  <span m=''2338970''>to</span> <span m=''2339200''>the</span> <span m=''2340080''>sum-product</span>
  <span m=''2340790''>algorithm,</span> <span m=''2341270''>that</span> <span m=''2341460''>means</span>
  <span m=''2341740''>we</span> <span m=''2341850''>have</span> <span m=''2342050''>to</span>
  <span m=''2342170''>compute</span> <span m=''2342660''>eight</span> <span m=''2342940''>things</span>
  <span m=''2343390''>when</span> <span m=''2343530''>we</span> <span m=''2343640''>get</span>
  <span m=''2343840''>to</span> <span m=''2343930''>this</span> <span m=''2344070''>node.</span>
  <span m=''2347540''>Maybe</span> <span m=''2347790''>it''s</span> <span m=''2347940''>a</span>
  <span m=''2347990''>slightly</span> <span m=''2348320''>more</span> <span m=''2348550''>complicated</span>
  <span m=''2349880''>thing,</span> <span m=''2350090''>but</span> <span m=''2350190''>as</span>
  <span m=''2350330''>long</span> <span m=''2350530''>as</span> <span m=''2350650''>we</span>
  <span m=''2350740''>keep</span> <span m=''2351000''>the</span> <span m=''2351110''>dimension</span>
  <span m=''2351580''>down</span> <span m=''2351810''>to</span> <span m=''2351880''>3,</span>
  <span m=''2352170''>we''re</span> <span m=''2352460''>only going</span> <span m=''2352630''>to
  have to</span> <span m=''2352970''>compute</span> <span m=''2353840''>eight</span>
  <span m=''2354090''>things.</span> <span m=''2355260''>So</span> <span m=''2355480''>we</span>
  <span m=''2355590''>haven''t</span> <span m=''2355830''>really</span> <span m=''2356080''>increased</span>
  <span m=''2356740''>the</span> <span m=''2356860''>decoding</span> <span m=''2357300''>complexity</span>
  <span m=''2357605''>at</span> <span m=''2357910''>all</span> <span m=''2358790''>by</span>
  <span m=''2358920''>doing</span> <span m=''2359220''>this.</span> <span m=''2360170''>So</span>
  <span m=''2360420''>that</span> <span m=''2360670''>we</span> <span m=''2360830''>consider</span>
  <span m=''2361270''>to</span> <span m=''2361340''>be</span> <span m=''2361530''>our</span>
  <span m=''2361700''>best</span> <span m=''2363270''>sectionalization.</span> </p><p><span
  m=''2365753''>And</span> <span m=''2367196''>if</span> <span m=''2367680''>we</span>
  <span m=''2367930''>tried</span> <span m=''2368210''>to</span> <span m=''2368280''>aggregate</span>
  <span m=''2368830''>these</span> <span m=''2369090''>two,</span> <span m=''2369380''>what
  would</span> <span m=''2369670''>we</span> <span m=''2369840''>get?</span> <span
  m=''2370310''>We''d</span> <span m=''2370530''>simply</span> <span m=''2370860''>get</span>
  <span m=''2371130''>the</span> <span m=''2371280''>eight</span> <span m=''2371500''>bits</span>
  <span m=''2371850''>here,</span> <span m=''2372410''>we</span> <span m=''2372670''>get</span>
  <span m=''2372840''>a</span> <span m=''2373330''>constraint</span> <span m=''2373860''>that</span>
  <span m=''2374020''>says</span> <span m=''2375040''>it''s</span> <span m=''2375220''>an</span>
  <span m=''2375330''>8, 4</span> <span m=''2375830''>constraint,</span> <span m=''2376540''>it
  says</span> <span m=''2376720''>these</span> <span m=''2376940''>eight</span> <span
  m=''2377170''>bits have</span> <span m=''2377500''>got</span> <span m=''2377630''>to</span>
  <span m=''2377700''>be</span> <span m=''2377820''>in</span> <span m=''2377920''>the</span>
  <span m=''2378030''>code.</span> <span m=''2380660''>So</span> <span m=''2380890''>we
  only</span> <span m=''2381210''>go</span> <span m=''2381390''>that</span> <span
  m=''2381650''>far,</span> <span m=''2382010''>because</span> <span m=''2382310''>that</span>
  <span m=''2382540''>would</span> <span m=''2382680''>increase</span> <span m=''2383070''>the</span>
  <span m=''2383160''>complexity</span> <span m=''2383710''>to</span> <span m=''2383840''>16.</span>
  <span m=''2386020''>All</span> <span m=''2386100''>right,</span> <span m=''2386460''>so</span>
  <span m=''2386780''>that''s</span> <span m=''2387240''>our</span> <span m=''2388500''>minimal</span>
  <span m=''2388950''>trellis.</span> <span m=''2389560''>We</span> <span m=''2389710''>call</span>
  <span m=''2390010''>it a</span> <span m=''2390170''>two-section</span> <span m=''2390970''>trellis</span>
  <span m=''2392110''>where</span> <span m=''2392330''>the</span> <span m=''2393170''>symbol</span>
  <span m=''2393600''>bits</span> <span m=''2394040''>have</span> <span m=''2394190''>been</span>
  <span m=''2394760''>grouped</span> <span m=''2395150''>into</span> <span m=''2395370''>4-tuples.</span>
  <span m=''2397770''>And</span> <span m=''2398000''>for</span> <span m=''2398250''>decoding,</span>
  <span m=''2398880''>that''s</span> <span m=''2399290''>the</span> <span m=''2400720''>simplest</span>
  <span m=''2401300''>one.</span> </p><p><span m=''2407150''>So</span> <span m=''2407760''>you</span>
  <span m=''2407900''>see</span> <span m=''2408100''>what</span> <span m=''2408240''>kind</span>
  <span m=''2408420''>of</span> <span m=''2408690''>games</span> <span m=''2409030''>we</span>
  <span m=''2409150''>can</span> <span m=''2409300''>play</span> <span m=''2409600''>here.</span>
  <span m=''2410700''>Yeah?</span> </p><p><span m=''2411000''>AUDIENCE: At the beginning
  of</span> <span m=''2411454''>this</span> <span m=''2411908''>process,</span> <span
  m=''2412362''>you started</span> <span m=''2412816''>at the</span> <span m=''2413270''>[UNINTELLIGIBLE].</span>
  </p><p><span m=''2415540''>PROFESSOR: Well,</span> <span m=''2416830''>you</span>
  <span m=''2417310''>remember</span> <span m=''2417700''>in</span> <span m=''2418130''>more</span>
  <span m=''2418350''>detail</span> <span m=''2420410''>how</span> <span m=''2420630''>we</span>
  <span m=''2421200''>concluded</span> <span m=''2421650''>this</span> <span m=''2421800''>was</span>
  <span m=''2421920''>the</span> <span m=''2422480''>optimal</span> <span m=''2422880''>sectionalization.</span>
  <span m=''2423660''>We</span> <span m=''2423770''>looked</span> <span m=''2424030''>at</span>
  <span m=''2424130''>time</span> <span m=''2424420''>3,</span> <span m=''2425220''>in</span>
  <span m=''2425340''>particular.</span> <span m=''2426265''>And</span> <span m=''2426520''>we</span>
  <span m=''2426700''>said</span> <span m=''2426980''>there</span> <span m=''2427140''>are</span>
  <span m=''2427180''>three</span> <span m=''2427810''>generators</span> <span m=''2428080''>that</span>
  <span m=''2428350''>are</span> <span m=''2428750''>active</span> <span m=''2428810''>at</span>
  <span m=''2428930''>time</span> <span m=''2429200''>3.</span> <span m=''2429890''>So</span>
  <span m=''2430140''>I''m going to</span> <span m=''2430270''>expand</span> <span
  m=''2430720''>that</span> <span m=''2430920''>as</span> <span m=''2431070''>far</span>
  <span m=''2431320''>as</span> <span m=''2431440''>I</span> <span m=''2431510''>can</span>
  <span m=''2432510''>without</span> <span m=''2432900''>bringing</span> <span m=''2433150''>any</span>
  <span m=''2433360''>more</span> <span m=''2433580''>generators</span> <span m=''2434190''>into</span>
  <span m=''2434340''>the</span> <span m=''2434410''>picture.</span> <span m=''2434850''>So</span>
  <span m=''2434990''>I</span> <span m=''2435070''>can''t</span> <span m=''2435500''>expand</span>
  <span m=''2435785''>it</span> <span m=''2436070''>over</span> <span m=''2436300''>here,</span>
  <span m=''2436700''>because</span> <span m=''2436970''>I''ll hit</span> <span m=''2437260''>u4.</span>
  <span m=''2438370''>But</span> <span m=''2438530''>I</span> <span m=''2438820''>can</span>
  <span m=''2438980''>expand</span> <span m=''2439340''>it as</span> <span m=''2439550''>far</span>
  <span m=''2439740''>as</span> <span m=''2439830''>I</span> <span m=''2439930''>want</span>
  <span m=''2440100''>over</span> <span m=''2440290''>here.</span> <span m=''2441220''>And</span>
  <span m=''2441370''>that''s</span> <span m=''2441630''>the way</span> <span m=''2441820''>we</span>
  <span m=''2441940''>sectionalize.</span> </p><p><span m=''2442230''>AUDIENCE: So
  do you</span> <span m=''2442520''>always</span> <span m=''2443000''>start</span>
  <span m=''2443480''>with</span> <span m=''2443960''>[UNINTELLIGIBLE]?</span> </p><p><span
  m=''2444920''>PROFESSOR: Well,</span> <span m=''2445280''>there''s</span> <span
  m=''2445640''>some art</span> <span m=''2445970''>in</span> <span m=''2446090''>this.</span>
  <span m=''2447570''>Here</span> <span m=''2447830''>it''s</span> <span m=''2448100''>kind</span>
  <span m=''2448250''>of</span> <span m=''2448290''>obvious</span> <span m=''2449420''>where</span>
  <span m=''2449530''>to</span> <span m=''2449650''>do</span> <span m=''2449870''>it.</span>
  <span m=''2451480''>And</span> <span m=''2451850''>I</span> <span m=''2452070''>give</span>
  <span m=''2452360''>two</span> <span m=''2452780''>heuristic</span> <span m=''2453340''>algorithms</span>
  <span m=''2454020''>in</span> <span m=''2454140''>the</span> <span m=''2454260''>notes</span>
  <span m=''2454720''>on</span> <span m=''2455073''>sectionalization,</span> <span
  m=''2456390''>which</span> <span m=''2457780''>we''ll</span> <span m=''2457990''>come</span>
  <span m=''2458160''>up</span> <span m=''2458320''>with</span> <span m=''2458480''>basically</span>
  <span m=''2458930''>the</span> <span m=''2459020''>same</span> <span m=''2459290''>thing.</span>
  <span m=''2460050''>But</span> <span m=''2460340''>for</span> <span m=''2460470''>simple</span>
  <span m=''2460770''>codes,</span> <span m=''2461090''>you</span> <span m=''2461300''>can
  just</span> <span m=''2461520''>eyeball</span> <span m=''2461930''>it.</span> </p><p><span
  m=''2464320''>OK,</span> <span m=''2464830''>so</span> <span m=''2467380''>let''s</span>
  <span m=''2467630''>see.</span> <span m=''2469220''>That''s</span> <span m=''2470110''>another</span>
  <span m=''2470860''>general</span> <span m=''2471330''>and</span> <span m=''2471430''>very</span>
  <span m=''2471690''>useful</span> <span m=''2472110''>style</span> <span m=''2472370''>of</span>
  <span m=''2472630''>realization.</span> <span m=''2473105''>It''s</span> <span m=''2473580''>a</span>
  <span m=''2473630''>trellis</span> <span m=''2474060''>realization,</span> <span
  m=''2474900''>or a</span> <span m=''2475070''>sectionalized</span> <span m=''2476300''>trellis</span>
  <span m=''2476690''>realization.</span> <span m=''2477590''>Is</span> <span m=''2477720''>there</span>
  <span m=''2477880''>anything</span> <span m=''2478180''>else</span> <span m=''2478490''>I</span>
  <span m=''2478550''>wanted</span> <span m=''2478870''>to</span> <span m=''2479850''>say</span>
  <span m=''2480160''>about</span> <span m=''2480510''>that?</span> <span m=''2480780''>We</span>
  <span m=''2480930''>can</span> <span m=''2481130''>do</span> <span m=''2481370''>it</span>
  <span m=''2482480''>so</span> <span m=''2482900''>that we</span> <span m=''2483030''>get</span>
  <span m=''2483400''>minimal</span> <span m=''2483890''>branch</span> <span m=''2484165''>and</span>
  <span m=''2484440''>state</span> <span m=''2484830''>spaces,</span> <span m=''2485620''>or</span>
  <span m=''2486040''>constraint</span> <span m=''2486620''>complexities.</span> <span
  m=''2488190''>It''s</span> <span m=''2488800''>cycle</span> <span m=''2489210''>free</span>
  <span m=''2489790''>if</span> <span m=''2490020''>we</span> <span m=''2490300''>aggregate</span>
  <span m=''2490980''>the</span> <span m=''2491840''>states</span> <span m=''2492420''>into</span>
  <span m=''2492570''>a</span> <span m=''2492640''>single</span> <span m=''2492980''>state</span>
  <span m=''2493350''>space.</span> <span m=''2494600''>Sectionalization,</span> <span
  m=''2495360''>we</span> <span m=''2495740''>talked</span> <span m=''2495950''>about</span>
  <span m=''2496370''>that.</span> <span m=''2497530''>OK,</span> <span m=''2497950''>so</span>
  <span m=''2498320''>let</span> <span m=''2498420''>me</span> <span m=''2498520''>leave</span>
  <span m=''2498720''>that</span> <span m=''2498890''>up,</span> <span m=''2499130''>because</span>
  <span m=''2499520''>we''re</span> <span m=''2499710''>of</span> <span m=''2499820''>course</span>
  <span m=''2500510''>not</span> <span m=''2501050''>done</span> <span m=''2501240''>with</span>
  <span m=''2501380''>that.</span> </p><p><span m=''2504620''>Now</span> <span m=''2505000''>let</span>
  <span m=''2505120''>me</span> <span m=''2505250''>talk</span> <span m=''2505610''>about</span>
  <span m=''2506040''>some</span> <span m=''2506260''>general</span> <span m=''2506720''>properties</span>
  <span m=''2507430''>of</span> <span m=''2507690''>graph</span> <span m=''2508100''>realizations.</span>
  <span m=''2520610''>And</span> <span m=''2520890''>the</span> <span m=''2522420''>most</span>
  <span m=''2522620''>important</span> <span m=''2523000''>thing</span> <span m=''2523360''>I''m
  going to</span> <span m=''2523440''>talk</span> <span m=''2523750''>about</span>
  <span m=''2523930''>here</span> <span m=''2524190''>is</span> <span m=''2524420''>the</span>
  <span m=''2525420''>cut-set</span> <span m=''2525670''>bound.</span> <span m=''2529920''>I
  want to</span> <span m=''2530160''>get</span> <span m=''2530380''>across</span>
  <span m=''2530880''>the</span> <span m=''2531040''>idea</span> <span m=''2531630''>that</span>
  <span m=''2534610''>a</span> <span m=''2534670''>graph</span> <span m=''2535080''>really</span>
  <span m=''2535350''>captures</span> <span m=''2535950''>dependency</span> <span
  m=''2536610''>relationships.</span> <span m=''2538360''>If</span> <span m=''2540090''>variables</span>
  <span m=''2540630''>are</span> <span m=''2540760''>incident</span> <span m=''2541190''>on</span>
  <span m=''2541350''>the</span> <span m=''2541440''>same</span> <span m=''2541780''>node,</span>
  <span m=''2542090''>they''re</span> <span m=''2542500''>obviously</span> <span m=''2542930''>all</span>
  <span m=''2543140''>dependent.</span> <span m=''2543800''>Or</span> <span m=''2544080''>if</span>
  <span m=''2544200''>you</span> <span m=''2544340''>think</span> <span m=''2544610''>of</span>
  <span m=''2545140''>larger</span> <span m=''2545540''>sets</span> <span m=''2545860''>of</span>
  <span m=''2545970''>variables</span> <span m=''2546710''>aggregated</span> <span
  m=''2547085''>in</span> <span m=''2547460''>this</span> <span m=''2547680''>way,</span>
  <span m=''2548480''>then</span> <span m=''2548930''>they''re</span> <span m=''2549170''>somehow</span>
  <span m=''2549490''>dependent.</span> <span m=''2550040''>Variables</span> <span
  m=''2550590''>that</span> <span m=''2550700''>are</span> <span m=''2550750''>very</span>
  <span m=''2551010''>far</span> <span m=''2551380''>away</span> <span m=''2551630''>on</span>
  <span m=''2551760''>the</span> <span m=''2551850''>graph</span> <span m=''2552360''>are</span>
  <span m=''2552560''>less</span> <span m=''2552880''>dependent</span> <span m=''2553270''>on</span>
  <span m=''2553390''>each</span> <span m=''2553620''>other</span> <span m=''2553890''>than</span>
  <span m=''2554060''>ones</span> <span m=''2554400''>that</span> <span m=''2554510''>are</span>
  <span m=''2554900''>close</span> <span m=''2555220''>to</span> <span m=''2555320''>each</span>
  <span m=''2555510''>other</span> <span m=''2555740''>on the</span> <span m=''2555840''>graph.</span>
  <span m=''2556240''>This</span> <span m=''2556450''>is</span> <span m=''2556590''>all</span>
  <span m=''2556850''>kind</span> <span m=''2557030''>of</span> <span m=''2557490''>vague</span>
  <span m=''2557890''>and</span> <span m=''2557970''>woolly</span> <span m=''2558300''>statements.</span>
  </p><p><span m=''2560160''>Let''s</span> <span m=''2560440''>see</span> <span m=''2560590''>if</span>
  <span m=''2560720''>we</span> <span m=''2560830''>can</span> <span m=''2560930''>make</span>
  <span m=''2561140''>them</span> <span m=''2561260''>more</span> <span m=''2561540''>concrete.</span>
  <span m=''2564190''>First</span> <span m=''2564610''>of</span> <span m=''2564650''>all,</span>
  <span m=''2564910''>there''s</span> <span m=''2565180''>a</span> <span m=''2567460''>very</span>
  <span m=''2567670''>simple</span> <span m=''2568160''>but</span> <span m=''2568400''>important</span>
  <span m=''2568830''>observation</span> <span m=''2570660''>that --</span> <span
  m=''2572598''>I''ll</span> <span m=''2573084''>put it</span> <span m=''2573570''>this</span>
  <span m=''2573810''>way--</span> <span m=''2574050''>disconnected</span> <span m=''2577070''>if</span>
  <span m=''2577290''>and</span> <span m=''2577380''>only</span> <span m=''2577810''>if</span>
  <span m=''2581080''>independent.</span> <span m=''2583215''>What does</span> <span
  m=''2583710''>this mean?</span> <span m=''2585600''>If</span> <span m=''2585980''>I</span>
  <span m=''2586090''>have</span> <span m=''2586170''>a</span> <span m=''2586260''>disconnected</span>
  <span m=''2587070''>graph,</span> <span m=''2588580''>let''s</span> <span m=''2588830''>suppose</span>
  <span m=''2589330''>I</span> <span m=''2589680''>have</span> <span m=''2590930''>one</span>
  <span m=''2591170''>graph</span> <span m=''2591660''>over</span> <span m=''2591930''>here</span>
  <span m=''2592280''>with</span> <span m=''2592460''>certain</span> <span m=''2593500''>external</span>
  <span m=''2594050''>variables.</span> <span m=''2594350''>Let</span> <span m=''2594650''>me</span>
  <span m=''2594840''>aggregate</span> <span m=''2595440''>them</span> <span m=''2595600''>all</span>
  <span m=''2595900''>into</span> <span m=''2596410''>y1</span> <span m=''2597780''>and</span>
  <span m=''2597940''>some</span> <span m=''2598260''>constraint</span> <span m=''2598850''>1</span>
  <span m=''2599190''>over</span> <span m=''2599420''>here,</span> <span m=''2600750''>and</span>
  <span m=''2601770''>a</span> <span m=''2601900''>completely</span> <span m=''2602650''>separate</span>
  <span m=''2603150''>graph,</span> <span m=''2604480''>some</span> <span m=''2604940''>different</span>
  <span m=''2605380''>code</span> <span m=''2605720''>over</span> <span m=''2605970''>here,</span>
  <span m=''2606250''>c2,</span> <span m=''2607500''>constraining</span> <span m=''2608090''>some</span>
  <span m=''2608590''>separate</span> <span m=''2609110''>set</span> <span m=''2609320''>of</span>
  <span m=''2609430''>variables,</span> <span m=''2610010''>y2.</span> </p><p><span
  m=''2613990''>OK,</span> <span m=''2615320''>that''s</span> <span m=''2616120''>a</span>
  <span m=''2616220''>disconnected</span> <span m=''2616900''>graph</span> <span m=''2617240''>realization.</span>
  <span m=''2617550''>It</span> <span m=''2617860''>has</span> <span m=''2618130''>to</span>
  <span m=''2618240''>look</span> <span m=''2618450''>like</span> <span m=''2618660''>that,</span>
  <span m=''2618980''>right?</span> <span m=''2620060''>So</span> <span m=''2620290''>we''re</span>
  <span m=''2620540''>aggregating</span> <span m=''2621220''>the</span> <span m=''2621340''>two</span>
  <span m=''2621580''>disconnected</span> <span m=''2622200''>halves.</span> <span
  m=''2624115''>All right,</span> <span m=''2624550''>what</span> <span m=''2624840''>can</span>
  <span m=''2624980''>I</span> <span m=''2625100''>say?</span> <span m=''2625590''>What</span>
  <span m=''2625870''>code</span> <span m=''2626360''>does</span> <span m=''2626570''>this</span>
  <span m=''2627240''>graph</span> <span m=''2627720''>realize?</span> <span m=''2632570''>This</span>
  <span m=''2632920''>graph,</span> <span m=''2634530''>the</span> <span m=''2634640''>code</span>
  <span m=''2635530''>that it</span> <span m=''2635630''>realizes</span> <span m=''2636780''>is</span>
  <span m=''2636920''>simply</span> <span m=''2637890''>the</span> <span m=''2637960''>Cartesian</span>
  <span m=''2638660''>product</span> <span m=''2639170''>of</span> <span m=''2639250''>c1</span>
  <span m=''2639510''>and</span> <span m=''2639880''>c2.</span> <span m=''2640520''>In</span>
  <span m=''2640580''>other</span> <span m=''2640760''>words,</span> <span m=''2642360''>this</span>
  <span m=''2642580''>means</span> <span m=''2643000''>the</span> <span m=''2643060''>set</span>
  <span m=''2643320''>of</span> <span m=''2643450''>all</span> <span m=''2644560''>pairs,</span>
  <span m=''2645450''>c1,</span> <span m=''2646310''>c2,</span> <span m=''2646670''>or</span>
  <span m=''2647150''>I</span> <span m=''2647380''>should</span> <span m=''2647590''>say</span>
  <span m=''2647790''>y1,</span> <span m=''2648410''>y2--</span> <span m=''2651840''>y1,</span>
  <span m=''2652780''>y2</span> <span m=''2653880''>such</span> <span m=''2654340''>that</span>
  <span m=''2655170''>y1</span> <span m=''2655880''>is</span> <span m=''2656070''>in</span>
  <span m=''2656320''>code</span> <span m=''2656650''>1</span> <span m=''2657150''>and</span>
  <span m=''2657600''>y2</span> <span m=''2657940''>is</span> <span m=''2658120''>in</span>
  <span m=''2658400''>code</span> <span m=''2658690''>2.</span> <span m=''2662000''>That</span>
  <span m=''2662200''>is</span> <span m=''2662370''>the</span> <span m=''2662460''>set</span>
  <span m=''2662730''>of</span> <span m=''2662870''>all</span> <span m=''2665390''>y1,</span>
  <span m=''2665860''>y2</span> <span m=''2666080''>that</span> <span m=''2666480''>satisfy</span>
  <span m=''2666750''>all</span> <span m=''2667020''>these</span> <span m=''2667290''>constraints,</span>
  <span m=''2667870''>right?</span> <span m=''2668480''>So</span> <span m=''2668890''>it''s</span>
  <span m=''2669070''>a</span> <span m=''2669110''>behavioral</span> <span m=''2669530''>realization</span>
  <span m=''2670280''>of</span> <span m=''2670420''>a</span> <span m=''2671170''>Cartesian</span>
  <span m=''2671810''>product</span> <span m=''2672350''>code.</span> </p><p><span
  m=''2677650''>Now</span> <span m=''2677800''>this</span> <span m=''2677980''>is</span>
  <span m=''2678110''>really</span> <span m=''2680920''>a</span> <span m=''2681040''>notion</span>
  <span m=''2681480''>of</span> <span m=''2681560''>independence,</span> <span m=''2682330''>right?</span>
  <span m=''2683510''>This</span> <span m=''2683740''>independently</span> <span m=''2684730''>realizes</span>
  <span m=''2686280''>a</span> <span m=''2686830''>code</span> <span m=''2687200''>word</span>
  <span m=''2687460''>from</span> <span m=''2687630''>c1</span> <span m=''2688340''>in</span>
  <span m=''2688530''>this</span> <span m=''2688740''>part</span> <span m=''2689100''>and</span>
  <span m=''2689350''>a</span> <span m=''2689410''>code</span> <span m=''2689650''>word</span>
  <span m=''2690050''>from c2</span> <span m=''2690370''>in</span> <span m=''2690690''>this</span>
  <span m=''2690940''>part.</span> <span m=''2691970''>What</span> <span m=''2692160''>would
  the</span> <span m=''2692310''>generator</span> <span m=''2692790''>matrix</span>
  <span m=''2693300''>look</span> <span m=''2693520''>like?</span> <span m=''2693850''>The</span>
  <span m=''2693910''>generator</span> <span m=''2694380''>matrix</span> <span m=''2694910''>from</span>
  <span m=''2695070''>this</span> <span m=''2695370''>would</span> <span m=''2695550''>look</span>
  <span m=''2695820''>like</span> <span m=''2696115''>a</span> <span m=''2697200''>generator</span>
  <span m=''2697810''>for</span> <span m=''2698020''>c1,</span> <span m=''2699750''>0,</span>
  <span m=''2700065''>this is a</span> <span m=''2700380''>0,</span> <span m=''2701270''>and</span>
  <span m=''2701340''>a</span> <span m=''2701430''>generator</span> <span m=''2701990''>for</span>
  <span m=''2702150''>c2.</span> <span m=''2704100''>So</span> <span m=''2704320''>there''s</span>
  <span m=''2704590''>a</span> <span m=''2704680''>generator</span> <span m=''2705190''>matrix</span>
  <span m=''2705650''>notion</span> <span m=''2705980''>of</span> <span m=''2706070''>independence.</span>
  <span m=''2706720''>In</span> <span m=''2706880''>other words,</span> <span m=''2707030''>these</span>
  <span m=''2707190''>are</span> <span m=''2707320''>just</span> <span m=''2707600''>two</span>
  <span m=''2707820''>independent</span> <span m=''2708280''>codes</span> <span m=''2708760''>that</span>
  <span m=''2708890''>for</span> <span m=''2709030''>some</span> <span m=''2709260''>reason,</span>
  <span m=''2709980''>we</span> <span m=''2710110''>choose</span> <span m=''2710520''>to</span>
  <span m=''2710910''>regard</span> <span m=''2711300''>as</span> <span m=''2711420''>one</span>
  <span m=''2711700''>code.</span> </p><p><span m=''2712790''>And</span> <span m=''2713420''>the</span>
  <span m=''2713520''>same</span> <span m=''2713780''>thing</span> <span m=''2714010''>is</span>
  <span m=''2714180''>true</span> <span m=''2714610''>that</span> <span m=''2714970''>if</span>
  <span m=''2715240''>we</span> <span m=''2715380''>have</span> <span m=''2716440''>a</span>
  <span m=''2716570''>Cartesian</span> <span m=''2717190''>product</span> <span m=''2717670''>code,</span>
  <span m=''2719050''>simply</span> <span m=''2719250''>a</span> <span m=''2719480''>code</span>
  <span m=''2719760''>made</span> <span m=''2719920''>up</span> <span m=''2720060''>of</span>
  <span m=''2720190''>two</span> <span m=''2720570''>independent</span> <span m=''2721160''>components,</span>
  <span m=''2722830''>then</span> <span m=''2722950''>we</span> <span m=''2723060''>can</span>
  <span m=''2723160''>always</span> <span m=''2723370''>realize</span> <span m=''2723810''>it
  in</span> <span m=''2723920''>this</span> <span m=''2724110''>way,</span> <span
  m=''2724560''>right?</span> <span m=''2724990''>We just</span> <span m=''2725170''>realize</span>
  <span m=''2725650''>c1,</span> <span m=''2725980''>realize</span> <span m=''2726390''>c2.</span>
  <span m=''2728550''>So</span> <span m=''2728860''>that''s</span> <span m=''2729370''>elementary,</span>
  <span m=''2730110''>but</span> <span m=''2730560''>it</span> <span m=''2730740''>begins</span>
  <span m=''2731140''>to</span> <span m=''2731250''>get</span> <span m=''2731400''>across</span>
  <span m=''2731820''>the</span> <span m=''2731960''>idea</span> <span m=''2732440''>that</span>
  <span m=''2733440''>graph</span> <span m=''2733820''>properties</span> <span m=''2734410''>have</span>
  <span m=''2734610''>to</span> <span m=''2734720''>do</span> <span m=''2734880''>with</span>
  <span m=''2735020''>dependence</span> <span m=''2735590''>properties.</span> <span
  m=''2736740''>And</span> <span m=''2736870''>here''s</span> <span m=''2737340''>the</span>
  <span m=''2737560''>most</span> <span m=''2737820''>radical</span> <span m=''2738950''>and</span>
  <span m=''2739250''>simple</span> <span m=''2739680''>form</span> <span m=''2740000''>of</span>
  <span m=''2740070''>that.</span> <span m=''2740440''>If</span> <span m=''2740550''>we</span>
  <span m=''2740830''>have</span> <span m=''2741110''>a</span> <span m=''2741170''>disconnected</span>
  <span m=''2741830''>graph,</span> <span m=''2742270''>then it</span> <span m=''2742470''>really</span>
  <span m=''2742720''>realizes</span> <span m=''2743330''>two</span> <span m=''2743550''>independent</span>
  <span m=''2743835''>codes.</span> </p><p><span m=''2748350''>Now,</span> <span m=''2748810''>more</span>
  <span m=''2749110''>important</span> <span m=''2749840''>than</span> <span m=''2750040''>that</span>
  <span m=''2752350''>is</span> <span m=''2753190''>the</span> <span m=''2753340''>cut-set</span>
  <span m=''2753570''>bound.</span> <span m=''2761100''>What</span> <span m=''2761320''>is</span>
  <span m=''2761460''>a</span> <span m=''2761550''>cut-set?</span> <span m=''2765870''>It''s</span>
  <span m=''2766080''>a</span> <span m=''2766220''>set</span> <span m=''2766660''>of</span>
  <span m=''2766910''>edges.</span> <span m=''2770270''>Actually, in</span> <span
  m=''2770750''>graph</span> <span m=''2771160''>theory,</span> <span m=''2771440''>it''s</span>
  <span m=''2771750''>defined</span> <span m=''2772200''>in</span> <span m=''2772340''>various</span>
  <span m=''2772780''>ways.</span> <span m=''2773220''>It</span> <span m=''2773310''>could</span>
  <span m=''2773490''>be</span> <span m=''2773600''>vertices,</span> <span m=''2773970''>it</span>
  <span m=''2774340''>could</span> <span m=''2774490''>be</span> <span m=''2774640''>edges.</span>
  <span m=''2775070''>Here,</span> <span m=''2775210''>we''re</span> <span m=''2775290''>going</span>
  <span m=''2775380''>to</span> <span m=''2775430''>say</span> <span m=''2775690''>it''s</span>
  <span m=''2776050''>a</span> <span m=''2776400''>set of</span> <span m=''2776750''>edges</span>
  <span m=''2778880''>whose</span> <span m=''2779170''>removal</span> <span m=''2779830''>disconnects</span>
  <span m=''2780530''>the</span> <span m=''2780630''>graph.</span> </p><p><span m=''2791180''>Probably</span>
  <span m=''2791610''>there</span> <span m=''2791750''>are</span> <span m=''2791820''>people</span>
  <span m=''2792180''>in</span> <span m=''2792300''>this</span> <span m=''2792410''>room</span>
  <span m=''2792680''>who</span> <span m=''2792790''>know</span> <span m=''2793000''>more</span>
  <span m=''2793320''>graph</span> <span m=''2793670''>theory</span> <span m=''2793880''>than</span>
  <span m=''2794020''>I</span> <span m=''2794130''>do?</span> <span m=''2794400''>Does</span>
  <span m=''2794540''>anyone</span> <span m=''2795550''>want</span> <span m=''2795740''>to</span>
  <span m=''2796670''>quibble</span> <span m=''2797070''>or</span> <span m=''2797300''>refine</span>
  <span m=''2797680''>that</span> <span m=''2797840''>in</span> <span m=''2797990''>any
  way?</span> <span m=''2799300''>That''s</span> <span m=''2799710''>my</span> <span
  m=''2799880''>idea</span> <span m=''2800200''>of</span> <span m=''2800310''>what</span>
  <span m=''2800670''>a</span> <span m=''2801050''>cut-set</span> <span m=''2801490''>is.</span>
  <span m=''2802730''>Any</span> <span m=''2803020''>elaboration?</span> <span m=''2804225''>No?</span>
  <span m=''2805155''>All right.</span> </p><p><span m=''2807020''>All</span> <span
  m=''2807180''>right,</span> <span m=''2807500''>so</span> <span m=''2807810''>we</span>
  <span m=''2808050''>have</span> <span m=''2808290''>some</span> <span m=''2809930''>large</span>
  <span m=''2811160''>graph</span> <span m=''2811800''>realization.</span> <span m=''2814110''>It''s</span>
  <span m=''2814620''>got</span> <span m=''2816560''>vertices</span> <span m=''2817270''>which</span>
  <span m=''2817400''>I</span> <span m=''2817690''>always</span> <span m=''2817990''>draw
  as</span> <span m=''2818290''>blocks,</span> <span m=''2818990''>its</span> <span
  m=''2819200''>constraint</span> <span m=''2819770''>codes,</span> <span m=''2822710''>they</span>
  <span m=''2823000''>have</span> <span m=''2823590''>various</span> <span m=''2824070''>interrelationships.</span>
  <span m=''2825032''>I''m</span> <span m=''2825430''>just</span> <span m=''2825650''>showing</span>
  <span m=''2827260''>one.</span> <span m=''2827710''>We</span> <span m=''2827890''>have</span>
  <span m=''2828090''>various</span> <span m=''2832650''>external</span> <span m=''2833290''>variables</span>
  <span m=''2833890''>that</span> <span m=''2834010''>we</span> <span m=''2834130''>bring</span>
  <span m=''2834430''>out</span> <span m=''2834610''>of</span> <span m=''2834770''>that,</span>
  <span m=''2835100''>and</span> <span m=''2835240''>that''s</span> <span m=''2836610''>the</span>
  <span m=''2836660''>general</span> <span m=''2837070''>graphical</span> <span m=''2837630''>realization</span>
  <span m=''2838310''>of</span> <span m=''2838390''>the</span> <span m=''2838470''>code.</span>
  </p><p><span m=''2839660''>What</span> <span m=''2839900''>are</span> <span m=''2840530''>some</span>
  <span m=''2841030''>cut-sets</span> <span m=''2841430''>in</span> <span m=''2841560''>here?</span>
  <span m=''2842902''>I''ve</span> <span m=''2843390''>drawn</span> <span m=''2843610''>this,</span>
  <span m=''2844040''>I''m</span> <span m=''2844250''>thinking</span> <span m=''2844700''>of</span>
  <span m=''2845020''>this</span> <span m=''2845340''>as</span> <span m=''2845550''>a</span>
  <span m=''2845610''>cut set.</span> <span m=''2845950''>If</span> <span m=''2846290''>I</span>
  <span m=''2846570''>take</span> <span m=''2847380''>these</span> <span m=''2847840''>two</span>
  <span m=''2848060''>edges</span> <span m=''2849810''>and</span> <span m=''2849920''>remove</span>
  <span m=''2850400''>them,</span> <span m=''2854990''>then</span> <span m=''2855100''>I''ve</span>
  <span m=''2855190''>disconnected</span> <span m=''2855760''>the</span> <span m=''2855850''>graph.</span>
  <span m=''2856330''>So</span> <span m=''2856610''>they</span> <span m=''2856780''>form</span>
  <span m=''2857110''>a</span> <span m=''2857160''>cut-set.</span> <span m=''2860670''>I''ve</span>
  <span m=''2860840''>already</span> <span m=''2861130''>mentioned</span> <span m=''2862230''>the</span>
  <span m=''2862360''>very</span> <span m=''2862840''>close</span> <span m=''2863950''>connection</span>
  <span m=''2864420''>between</span> <span m=''2864940''>cut-sets</span> <span m=''2865370''>and</span>
  <span m=''2865520''>cycle-free</span> <span m=''2866160''>graphs,</span> <span m=''2866740''>which</span>
  <span m=''2867030''>is</span> <span m=''2868090''>the</span> <span m=''2868230''>graph</span>
  <span m=''2868560''>is</span> <span m=''2869060''>cycle-free</span> <span m=''2869390''>if</span>
  <span m=''2869620''>and</span> <span m=''2869730''>only</span> <span m=''2870100''>if</span>
  <span m=''2871010''>by</span> <span m=''2871160''>removing</span> <span m=''2871620''>any</span>
  <span m=''2871840''>single</span> <span m=''2872270''>edge,</span> <span m=''2872950''>I</span>
  <span m=''2873090''>disconnect</span> <span m=''2873600''>the</span> <span m=''2873680''>graph.</span>
  <span m=''2874900''>So</span> <span m=''2875140''>every</span> <span m=''2875500''>single</span>
  <span m=''2875890''>edge is</span> <span m=''2876250''>itself</span> <span m=''2876700''>a</span>
  <span m=''2876940''>cut-set.</span> <span m=''2877910''>That''s</span> <span m=''2878180''>a</span>
  <span m=''2878250''>very</span> <span m=''2878530''>elegant</span> <span m=''2879000''>characterization.</span>
  </p><p><span m=''2881430''>All</span> <span m=''2881630''>right,</span> <span m=''2881830''>so</span>
  <span m=''2881940''>I''m</span> <span m=''2882070''>thinking</span> <span m=''2882430''>of</span>
  <span m=''2882530''>a</span> <span m=''2882920''>cut-set.</span> <span m=''2883230''>I''m</span>
  <span m=''2883310''>going</span> <span m=''2883440''>to</span> <span m=''2883570''>write</span>
  <span m=''2883850''>it</span> <span m=''2884150''>as</span> <span m=''2886420''>chi</span>
  <span m=''2887000''>for</span> <span m=''2887190''>scissors.</span> <span m=''2888710''>And</span>
  <span m=''2890360''>it''s</span> <span m=''2890580''>a</span> <span m=''2890640''>set</span>
  <span m=''2890920''>of</span> <span m=''2891050''>edges.</span> <span m=''2892050''>So</span>
  <span m=''2893140''>in</span> <span m=''2893310''>our</span> <span m=''2893500''>cases,</span>
  <span m=''2893950''>what are</span> <span m=''2894140''>the</span> <span m=''2894270''>edges?</span>
  <span m=''2894850''>It''s</span> <span m=''2895070''>a</span> <span m=''2895120''>set</span>
  <span m=''2895330''>of</span> <span m=''2895430''>state</span> <span m=''2895830''>spaces</span>
  <span m=''2897210''>for</span> <span m=''2897390''>some</span> <span m=''2897880''>index</span>
  <span m=''2898540''>set.</span> <span m=''2901700''>OK,</span> <span m=''2902110''>so</span>
  <span m=''2902280''>I''m</span> <span m=''2902400''>going</span> <span m=''2902520''>to</span>
  <span m=''2902690''>select</span> <span m=''2903160''>some</span> <span m=''2903830''>minimal</span>
  <span m=''2904160''>set</span> <span m=''2904330''>of</span> <span m=''2904490''>state</span>
  <span m=''2904920''>spaces</span> <span m=''2905440''>that</span> <span m=''2905540''>disconnects</span>
  <span m=''2906680''>the</span> <span m=''2906750''>graph.</span> <span m=''2909510''>All</span>
  <span m=''2909710''>my</span> <span m=''2909860''>edges</span> <span m=''2910290''>are</span>
  <span m=''2910710''>internal</span> <span m=''2911200''>variables.</span> <span
  m=''2911670''>We</span> <span m=''2911770''>don''t</span> <span m=''2911950''>really</span>
  <span m=''2912200''>need</span> <span m=''2912460''>to</span> <span m=''2912570''>worry</span>
  <span m=''2912900''>about</span> <span m=''2913260''>these</span> <span m=''2914180''>half</span>
  <span m=''2914560''>edges</span> <span m=''2914940''>out</span> <span m=''2915100''>here,</span>
  <span m=''2915340''>as</span> <span m=''2915500''>I''ve</span> <span m=''2915550''>said</span>
  <span m=''2915810''>before.</span> <span m=''2918430''>They''re</span> <span m=''2918650''>always</span>
  <span m=''2918940''>going</span> <span m=''2919080''>to</span> <span m=''2919210''>trivially</span>
  <span m=''2921650''>separate</span> <span m=''2922410''>their</span> <span m=''2922620''>variables</span>
  <span m=''2923260''>from</span> <span m=''2923440''>the</span> <span m=''2923530''>rest</span>
  <span m=''2923840''>of the</span> <span m=''2923920''>graph,</span> <span m=''2924790''>and</span>
  <span m=''2924890''>it''s</span> <span m=''2925140''>just</span> <span m=''2925340''>tedious</span>
  <span m=''2925620''>to</span> <span m=''2925900''>try</span> <span m=''2926130''>to</span>
  <span m=''2926250''>keep</span> <span m=''2926530''>them</span> <span m=''2926680''>in</span>
  <span m=''2926780''>the</span> <span m=''2926950''>explanation.</span> <span m=''2927690''>So</span>
  <span m=''2927930''>we''re</span> <span m=''2928060''>only</span> <span m=''2928240''>talking</span>
  <span m=''2928510''>about</span> <span m=''2928730''>state-edges</span> <span m=''2929390''>here.</span>
  </p><p><span m=''2931490''>All</span> <span m=''2931580''>right,</span> <span m=''2931890''>once</span>
  <span m=''2932220''>I''ve</span> <span m=''2932380''>done</span> <span m=''2932620''>that,</span>
  <span m=''2936690''>let</span> <span m=''2936880''>me</span> <span m=''2937020''>now</span>
  <span m=''2937400''>do</span> <span m=''2937650''>my</span> <span m=''2938370''>agglomeration</span>
  <span m=''2939320''>trick.</span> <span m=''2946330''>Sorry,</span> <span m=''2946790''>I''m</span>
  <span m=''2946900''>trying</span> <span m=''2947080''>to</span> <span m=''2947250''>draw</span>
  <span m=''2947560''>a</span> <span m=''2951720''>dotted</span> <span m=''2952070''>line</span>
  <span m=''2952450''>around</span> <span m=''2952600''>a</span> <span m=''2952740''>part</span>
  <span m=''2953030''>of</span> <span m=''2953070''>the</span> <span m=''2953180''>graph</span>
  <span m=''2953820''>that</span> <span m=''2954060''>I''m going to</span> <span m=''2954170''>leave</span>
  <span m=''2954440''>outside</span> <span m=''2955240''>the</span> <span m=''2957380''>external</span>
  <span m=''2957930''>variables</span> <span m=''2958330''>that</span> <span m=''2958730''>I</span>
  <span m=''2958900''>still</span> <span m=''2959220''>want to</span> <span m=''2959430''>be</span>
  <span m=''2959590''>external.</span> <span m=''2960220''>I''m</span> <span m=''2960350''>going</span>
  <span m=''2960560''>to</span> <span m=''2961450''>leave</span> <span m=''2961860''>the</span>
  <span m=''2962140''>state</span> <span m=''2962550''>variables,</span> <span m=''2965990''>which</span>
  <span m=''2966290''>I''m</span> <span m=''2966390''>going</span> <span m=''2966520''>to</span>
  <span m=''2966570''>remember</span> <span m=''2967090''>were</span> <span m=''2967290''>once</span>
  <span m=''2967620''>connected.</span> <span m=''2968120''>And</span> <span m=''2968290''>let</span>
  <span m=''2968420''>me</span> <span m=''2968550''>reconnect</span> <span m=''2969090''>them</span>
  <span m=''2969230''>now.</span> </p><p><span m=''2970930''>So</span> <span m=''2971130''>I''m</span>
  <span m=''2971320''>taking</span> <span m=''2971620''>my</span> <span m=''2971760''>original</span>
  <span m=''2972200''>graph</span> <span m=''2973440''>and</span> <span m=''2973670''>I''m</span>
  <span m=''2973820''>dividing</span> <span m=''2974360''>it</span> <span m=''2975150''>according</span>
  <span m=''2975720''>to</span> <span m=''2975900''>this</span> <span m=''2976530''>cut-set</span>
  <span m=''2977460''>into</span> <span m=''2978000''>two</span> <span m=''2978220''>parts.</span>
  <span m=''2981230''>And</span> <span m=''2981700''>I''m</span> <span m=''2981970''>arbitrarily</span>
  <span m=''2982620''>going</span> <span m=''2982750''>to</span> <span m=''2982880''>call</span>
  <span m=''2983200''>this</span> <span m=''2983540''>the</span> <span m=''2983640''>past,</span>
  <span m=''2984910''>p--</span> <span m=''2985390''>arbitrarily</span> <span m=''2986020''>but</span>
  <span m=''2986290''>suggestively--</span> <span m=''2987720''>and</span> <span m=''2987900''>the</span>
  <span m=''2987980''>future,</span> <span m=''2988280''>f.</span> <span m=''2988580''>And
  it</span> <span m=''2989010''>doesn''t</span> <span m=''2989280''>matter</span>
  <span m=''2989560''>which</span> <span m=''2989770''>one</span> <span m=''2989990''>I</span>
  <span m=''2990990''>call</span> <span m=''2991310''>p</span> <span m=''2991510''>and</span>
  <span m=''2991630''>which</span> <span m=''2991860''>one</span> <span m=''2992060''>f.</span>
  </p><p><span m=''2995654''>And</span> <span m=''2996110''>I''m</span> <span m=''2996230''>going</span>
  <span m=''2996360''>to</span> <span m=''2996400''>redraw</span> <span m=''2997000''>this,</span>
  <span m=''2999370''>so</span> <span m=''2999820''>this</span> <span m=''3000340''>is</span>
  <span m=''3000460''>just</span> <span m=''3000780''>a</span> <span m=''3000890''>re-drawing</span>
  <span m=''3001600''>of</span> <span m=''3001770''>that</span> <span m=''3002470''>in</span>
  <span m=''3002740''>a</span> <span m=''3003570''>nicer</span> <span m=''3003990''>form.</span>
  <span m=''3005260''>I''m going to</span> <span m=''3005400''>aggregate</span> <span
  m=''3006470''>all</span> <span m=''3006780''>of</span> <span m=''3006920''>these</span>
  <span m=''3007880''>variables</span> <span m=''3008380''>over</span> <span m=''3008630''>here.</span>
  <span m=''3009000''>And I''m</span> <span m=''3009140''>going</span> <span m=''3009270''>to</span>
  <span m=''3009950''>call</span> <span m=''3010220''>that</span> <span m=''3010460''>the</span>
  <span m=''3010560''>set</span> <span m=''3010850''>of</span> <span m=''3010960''>past</span>
  <span m=''3011600''>external</span> <span m=''3012140''>variables,</span> <span
  m=''3012850''>y</span> <span m=''3013760''>projected</span> <span m=''3014210''>on</span>
  <span m=''3014370''>the</span> <span m=''3014520''>past.</span> <span m=''3017365''>And</span>
  <span m=''3017800''>similarly</span> <span m=''3018290''>over</span> <span m=''3018510''>here,</span>
  <span m=''3018920''>I''ll</span> <span m=''3019000''>get the</span> <span m=''3019310''>set</span>
  <span m=''3019570''>of</span> <span m=''3019700''>all</span> <span m=''3020360''>external</span>
  <span m=''3020930''>variables</span> <span m=''3021500''>projected</span> <span
  m=''3022050''>on</span> <span m=''3022140''>the</span> <span m=''3022230''>future.</span>
  <span m=''3024080''>It</span> <span m=''3024150''>was</span> <span m=''3024290''>just</span>
  <span m=''3025160''>the</span> <span m=''3025250''>ones</span> <span m=''3025550''>that</span>
  <span m=''3025660''>occur</span> <span m=''3026360''>when</span> <span m=''3026540''>I</span>
  <span m=''3026850''>make</span> <span m=''3027130''>this</span> <span m=''3027350''>kind</span>
  <span m=''3027520''>of</span> <span m=''3027680''>cut</span> <span m=''3028150''>through</span>
  <span m=''3028380''>state</span> <span m=''3028820''>edges.</span> <span m=''3029840''>Some
  of</span> <span m=''3030210''>the</span> <span m=''3030400''>external</span> <span
  m=''3030850''>variables</span> <span m=''3031340''>wind</span> <span m=''3031610''>up</span>
  <span m=''3031750''>in</span> <span m=''3031840''>the</span> <span m=''3031930''>past</span>
  <span m=''3032370''>side,</span> <span m=''3032680''>and</span> <span m=''3032750''>some</span>
  <span m=''3033110''>wind</span> <span m=''3033430''>up</span> <span m=''3033600''>connected
  to the</span> <span m=''3033970''>future</span> <span m=''3034470''>side.</span>
  <span m=''3034870''>But</span> <span m=''3035570''>there are</span> <span m=''3035780''>obviously</span>
  <span m=''3036090''>none</span> <span m=''3036450''>connected</span> <span m=''3036940''>to</span>
  <span m=''3037020''>both</span> <span m=''3038190''>because</span> <span m=''3038690''>the</span>
  <span m=''3038810''>definition</span> <span m=''3039290''>of a</span> <span m=''3039560''>cut-set.</span>
  <span m=''3039860''>We''ve</span> <span m=''3040080''>disconnected</span> <span
  m=''3040700''>the</span> <span m=''3040780''>graph.</span> </p><p><span m=''3042320''>All</span>
  <span m=''3042410''>right,</span> <span m=''3042660''>so</span> <span m=''3042770''>there''s</span>
  <span m=''3043060''>the</span> <span m=''3043140''>past.</span> <span m=''3043660''>There''s</span>
  <span m=''3043950''>the</span> <span m=''3044020''>future.</span> <span m=''3045620''>And</span>
  <span m=''3047310''>here</span> <span m=''3047710''>are the</span> <span m=''3047910''>state</span>
  <span m=''3048370''>variables.</span> <span m=''3050050''>Now</span> <span m=''3050200''>I''m</span>
  <span m=''3050350''>going</span> <span m=''3050520''>to</span> <span m=''3051710''>define</span>
  <span m=''3052110''>these</span> <span m=''3052460''>all</span> <span m=''3052780''>together</span>
  <span m=''3054040''>as</span> <span m=''3054290''>a</span> <span m=''3054360''>super-state</span>
  <span m=''3055190''>space</span> <span m=''3056360''>as</span> <span m=''3056600''>I</span>
  <span m=''3056690''>did</span> <span m=''3056890''>in</span> <span m=''3056990''>the</span>
  <span m=''3057080''>trellis</span> <span m=''3057500''>graph</span> <span m=''3057880''>over</span>
  <span m=''3058080''>there.</span> <span m=''3060250''>So</span> <span m=''3062251''>let''s</span>
  <span m=''3062690''>see,</span> <span m=''3063100''>here</span> <span m=''3063420''>I</span>
  <span m=''3063510''>labeled</span> <span m=''3063910''>the</span> <span m=''3064090''>edges</span>
  <span m=''3064630''>by</span> <span m=''3064860''>a set of</span> <span m=''3065190''>states.</span>
  <span m=''3065770''>But</span> <span m=''3065910''>what</span> <span m=''3066110''>I</span>
  <span m=''3066200''>mean</span> <span m=''3066450''>here</span> <span m=''3066920''>is</span>
  <span m=''3067280''>that</span> <span m=''3068870''>the</span> <span m=''3068940''>super-state</span>
  <span m=''3069710''>space</span> <span m=''3070260''>is</span> <span m=''3070460''>just</span>
  <span m=''3070690''>the</span> <span m=''3070770''>product</span> <span m=''3071390''>of</span>
  <span m=''3071500''>the</span> <span m=''3071620''>component</span> <span m=''3072590''>state</span>
  <span m=''3073080''>spaces.</span> <span m=''3076100''>It''s</span> <span m=''3076330''>elements</span>
  <span m=''3077350''>s chi</span> <span m=''3079440''>are</span> <span m=''3079720''>just</span>
  <span m=''3081820''>the</span> <span m=''3082010''>set</span> <span m=''3082270''>of</span>
  <span m=''3082680''>sj,</span> <span m=''3087860''>j,</span> <span m=''3088730''>and</span>
  <span m=''3089150''>sigma-j,</span> <span m=''3089570''>is</span> <span m=''3090060''>that</span>
  <span m=''3090160''>clear?</span> <span m=''3092300''>In other</span> <span m=''3092380''>words,</span>
  <span m=''3092590''>I</span> <span m=''3092980''>have a</span> <span m=''3093180''>vector</span>
  <span m=''3093760''>of</span> <span m=''3093850''>states</span> <span m=''3094510''>here.</span>
  <span m=''3095040''>And</span> <span m=''3097000''>I</span> <span m=''3097070''>consider</span>
  <span m=''3097630''>the</span> <span m=''3097930''>super-state space</span> <span
  m=''3099120''>to</span> <span m=''3099210''>be</span> <span m=''3099400''>just</span>
  <span m=''3099710''>the</span> <span m=''3099820''>Cartesian--</span> <span m=''3100400''>this,</span>
  <span m=''3100590''>again,</span> <span m=''3100880''>is</span> <span m=''3101040''>the</span>
  <span m=''3101120''>Cartesian</span> <span m=''3101680''>product</span> <span m=''3102120''>of</span>
  <span m=''3102340''>all the</span> <span m=''3102460''>state</span> <span m=''3102850''>spaces.</span>
  </p><p><span m=''3105260''>OK,</span> <span m=''3106690''>and</span> <span m=''3106960''>then</span>
  <span m=''3107560''>I</span> <span m=''3107740''>have</span> <span m=''3107910''>constraints.</span>
  <span m=''3109930''>So</span> <span m=''3110280''>we''ll</span> <span m=''3110490''>call</span>
  <span m=''3110730''>this</span> <span m=''3111430''>the</span> <span m=''3112690''>aggregate</span>
  <span m=''3113200''>past</span> <span m=''3113620''>constraint,</span> <span m=''3113980''>and
  the</span> <span m=''3114340''>aggregate</span> <span m=''3114840''>future</span>
  <span m=''3115270''>constraint.</span> <span m=''3118580''>This</span> <span m=''3118790''>constrains</span>
  <span m=''3119310''>these</span> <span m=''3119540''>variables</span> <span m=''3119800''>in
  this</span> <span m=''3120220''>state.</span> <span m=''3121050''>This</span> <span
  m=''3121270''>constrains</span> <span m=''3121860''>these</span> <span m=''3122090''>variables</span>
  <span m=''3122610''>in</span> <span m=''3122670''>that</span> <span m=''3123040''>state.</span>
  </p><p><span m=''3126060''>OK,</span> <span m=''3126590''>so</span> <span m=''3126970''>that''s</span>
  <span m=''3127250''>where</span> <span m=''3127440''>figure</span> <span m=''3127790''>5</span>
  <span m=''3128190''>comes</span> <span m=''3128510''>from.</span> <span m=''3128790''>Every</span>
  <span m=''3129030''>year,</span> <span m=''3129450''>people</span> <span m=''3129760''>say,</span>
  <span m=''3130690''>how</span> <span m=''3130850''>did</span> <span m=''3130970''>you</span>
  <span m=''3131090''>get</span> <span m=''3131270''>figure</span> <span m=''3131570''>5?</span>
  <span m=''3132500''>That''s</span> <span m=''3132680''>how</span> <span m=''3132820''>I</span>
  <span m=''3132910''>get</span> <span m=''3133140''>figure</span> <span m=''3133400''>5.</span>
  <span m=''3133880''>Is</span> <span m=''3134110''>there any</span> <span m=''3134330''>confusion</span>
  <span m=''3134830''>about</span> <span m=''3135120''>that?</span> <span m=''3138320''>Today</span>
  <span m=''3138610''>I''ve</span> <span m=''3138740''>been</span> <span m=''3138870''>talking</span>
  <span m=''3139220''>about</span> <span m=''3139470''>agglomeration</span> <span
  m=''3140250''>quite</span> <span m=''3140500''>a</span> <span m=''3140540''>bit,</span>
  <span m=''3140990''>so</span> <span m=''3142190''>maybe</span> <span m=''3143910''>this</span>
  <span m=''3144130''>year</span> <span m=''3144360''>it''ll</span> <span m=''3144490''>come</span>
  <span m=''3144680''>through</span> <span m=''3144900''>better</span> <span m=''3145220''>than</span>
  <span m=''3145370''>in</span> <span m=''3145550''>past</span> <span m=''3145970''>years.</span>
  </p><p><span m=''3147348''>AUDIENCE: [INAUDIBLE]</span> <span m=''3148286''>that</span>
  <span m=''3148755''>we see</span> <span m=''3149224''>projected</span> <span m=''3149693''>on
  it.</span> <span m=''3150631''>Or is</span> <span m=''3151100''>it just--</span>
  </p><p><span m=''3153450''>PROFESSOR: It''s</span> <span m=''3154170''>just</span>
  <span m=''3154430''>the</span> <span m=''3154600''>aggregate</span> <span m=''3155200''>of</span>
  <span m=''3155350''>all</span> <span m=''3155600''>these</span> <span m=''3156640''>constraints.</span>
  <span m=''3158490''>What</span> <span m=''3158690''>does</span> <span m=''3159350''>this</span>
  <span m=''3159630''>say?</span> <span m=''3159770''>It''s</span> <span m=''3159970''>the</span>
  <span m=''3160060''>set</span> <span m=''3160480''>of</span> <span m=''3160610''>all</span>
  <span m=''3161090''>the</span> <span m=''3161510''>possible</span> <span m=''3161950''>values</span>
  <span m=''3162420''>of</span> <span m=''3162530''>these</span> <span m=''3162830''>variables,</span>
  <span m=''3163410''>and</span> <span m=''3163550''>these</span> <span m=''3163800''>variables</span>
  <span m=''3164350''>that</span> <span m=''3164480''>can</span> <span m=''3164620''>actually</span>
  <span m=''3164980''>occur.</span> <span m=''3166120''>That</span> <span m=''3166460''>forms</span>
  <span m=''3166900''>a</span> <span m=''3166970''>linear</span> <span m=''3167310''>space</span>
  <span m=''3167770''>which</span> <span m=''3167970''>we</span> <span m=''3168090''>call</span>
  <span m=''3168330''>little</span> <span m=''3168620''>code.</span> <span m=''3169670''>Anything</span>
  <span m=''3170020''>consistent</span> <span m=''3170360''>with</span> <span m=''3170700''>that</span>
  <span m=''3171660''>satisfies</span> <span m=''3172210''>this</span> <span m=''3172400''>constraint.</span>
  <span m=''3173580''>Anything</span> <span m=''3173930''>else</span> <span m=''3174280''>doesn''t.</span>
  </p><p><span m=''3175270''>AUDIENCE: [INAUDIBLE]</span> <span m=''3177745''>for</span>
  <span m=''3178240''>the c''s</span> <span m=''3179725''>projection</span> <span
  m=''3180220''>of the</span> <span m=''3180715''>code</span> <span m=''3181210''>on
  the</span> <span m=''3181705''>past?</span> </p><p><span m=''3184180''>PROFESSOR:
  No.</span> <span m=''3186390''>The</span> <span m=''3186740''>projection</span>
  <span m=''3187800''>of</span> <span m=''3187900''>the</span> <span m=''3188010''>code</span>
  <span m=''3188320''>on</span> <span m=''3188440''>the</span> <span m=''3188530''>past</span>
  <span m=''3189570''>would</span> <span m=''3189710''>be</span> <span m=''3190090''>you</span>
  <span m=''3190270''>realize</span> <span m=''3190770''>the</span> <span m=''3190880''>code</span>
  <span m=''3191310''>and</span> <span m=''3191470''>you</span> <span m=''3191640''>just</span>
  <span m=''3191780''>project</span> <span m=''3192420''>onto</span> <span m=''3192490''>these</span>
  <span m=''3192790''>variables</span> <span m=''3193330''>here.</span> <span m=''3194140''>So</span>
  <span m=''3194510''>no,</span> <span m=''3194810''>this</span> <span m=''3195050''>is</span>
  <span m=''3195210''>just</span> <span m=''3195540''>an</span> <span m=''3195830''>index.</span>
  <span m=''3196450''>This</span> <span m=''3196660''>is</span> <span m=''3197180''>a</span>
  <span m=''3197310''>constraint</span> <span m=''3198190''>whose</span> <span m=''3198350''>index</span>
  <span m=''3198725''>is the</span> <span m=''3199100''>past.</span> </p><p><span
  m=''3203170''>OK,</span> <span m=''3205140''>well,</span> <span m=''3206150''>all</span>
  <span m=''3206250''>right.</span> <span m=''3207400''>Oh, but</span> <span m=''3209110''>this</span>
  <span m=''3209400''>looks</span> <span m=''3209690''>like</span> <span m=''3209900''>a</span>
  <span m=''3209960''>trellis,</span> <span m=''3211400''>like a</span> <span m=''3211780''>two-section</span>
  <span m=''3212410''>trellis.</span> <span m=''3212940''>It</span> <span m=''3212980''>looks</span>
  <span m=''3213260''>very</span> <span m=''3213480''>much</span> <span m=''3213740''>like</span>
  <span m=''3213950''>this</span> <span m=''3214200''>thing</span> <span m=''3214330''>right</span>
  <span m=''3214590''>here.</span> <span m=''3217370''>It</span> <span m=''3217500''>has</span>
  <span m=''3217770''>the</span> <span m=''3217850''>same</span> <span m=''3218200''>general</span>
  <span m=''3218570''>form.</span> <span m=''3220600''>And</span> <span m=''3222710''>we</span>
  <span m=''3222910''>can</span> <span m=''3223040''>think</span> <span m=''3223320''>of</span>
  <span m=''3223480''>this</span> <span m=''3224240''>super-state</span> <span m=''3225030''>variable</span>
  <span m=''3225460''>here,</span> <span m=''3226410''>it</span> <span m=''3226600''>sort</span>
  <span m=''3226760''>of</span> <span m=''3226820''>has</span> <span m=''3227010''>the</span>
  <span m=''3227540''>Markov</span> <span m=''3228040''>property.</span> <span m=''3230130''>It,</span>
  <span m=''3230260''>again,</span> <span m=''3230670''>tells</span> <span m=''3231130''>everything</span>
  <span m=''3231590''>about</span> <span m=''3231880''>the</span> <span m=''3231950''>past</span>
  <span m=''3234000''>that</span> <span m=''3234120''>is</span> <span m=''3234270''>needed</span>
  <span m=''3235910''>to</span> <span m=''3236220''>specify</span> <span m=''3237210''>what</span>
  <span m=''3237570''>possible</span> <span m=''3238000''>futures</span> <span m=''3238520''>there</span>
  <span m=''3238720''>could</span> <span m=''3238910''>be.</span> <span m=''3239090''>We''re</span>
  <span m=''3239230''>really</span> <span m=''3239530''>interested</span> <span m=''3239830''>in
  these</span> <span m=''3240200''>up</span> <span m=''3240350''>here,</span> <span
  m=''3240590''>eventually.</span> <span m=''3241670''>But</span> <span m=''3241860''>this</span>
  <span m=''3242120''>is</span> <span m=''3242300''>the</span> <span m=''3242510''>whole</span>
  <span m=''3242730''>set</span> <span m=''3242970''>of</span> <span m=''3243100''>constraints</span>
  <span m=''3244240''>that</span> <span m=''3244400''>determine</span> <span m=''3244770''>the</span>
  <span m=''3244850''>futures</span> <span m=''3245420''>along</span> <span m=''3245750''>with--</span>
  <span m=''3246120''>there</span> <span m=''3246260''>may be</span> <span m=''3246540''>some</span>
  <span m=''3246750''>more</span> <span m=''3246880''>free</span> <span m=''3247160''>variables</span>
  <span m=''3247720''>over</span> <span m=''3247940''>here.</span> <span m=''3248760''>But</span>
  <span m=''3250880''>these</span> <span m=''3251140''>are</span> <span m=''3251170''>the</span>
  <span m=''3251310''>constraints</span> <span m=''3251870''>we</span> <span m=''3251990''>get</span>
  <span m=''3252170''>from</span> <span m=''3252320''>this</span> <span m=''3252550''>half</span>
  <span m=''3252840''>of</span> <span m=''3252910''>the</span> <span m=''3253030''>code</span>
  <span m=''3253490''>on</span> <span m=''3253720''>this</span> <span m=''3253840''>half
  of</span> <span m=''3254230''>the</span> <span m=''3254360''>code</span> <span m=''3254710''>and</span>
  <span m=''3254860''>vice</span> <span m=''3255170''>versa.</span> </p><p><span m=''3256930''>So</span>
  <span m=''3257990''>again,</span> <span m=''3258420''>a cut-set</span> <span m=''3260780''>is</span>
  <span m=''3261400''>related</span> <span m=''3262090''>to</span> <span m=''3262820''>a</span>
  <span m=''3262880''>Markov</span> <span m=''3263490''>property.</span> <span m=''3268450''>Let</span>
  <span m=''3268520''>me</span> <span m=''3268650''>try</span> <span m=''3268880''>to</span>
  <span m=''3268980''>state</span> <span m=''3269380''>this</span> <span m=''3270270''>property</span>
  <span m=''3270770''>more</span> <span m=''3271150''>explicitly.</span> <span m=''3276990''>The</span>
  <span m=''3278360''>code</span> <span m=''3279930''>by</span> <span m=''3280110''>the</span>
  <span m=''3280230''>behavioral</span> <span m=''3280760''>realization</span> <span
  m=''3281610''>is</span> <span m=''3281830''>simply</span> <span m=''3282200''>the</span>
  <span m=''3282330''>set</span> <span m=''3283310''>of</span> <span m=''3283460''>all</span>
  <span m=''3283740''>combinations</span> <span m=''3284600''>of --</span> <span m=''3287370''>let</span>
  <span m=''3287530''>me</span> <span m=''3287640''>say,</span> <span m=''3287880''>the</span>
  <span m=''3287980''>behavior</span> <span m=''3289070''>is</span> <span m=''3289460''>the</span>
  <span m=''3289570''>set</span> <span m=''3290060''>of</span> <span m=''3290240''>all</span>
  <span m=''3291650''>past</span> <span m=''3294180''>states</span> <span m=''3299240''>and</span>
  <span m=''3299460''>futures</span> <span m=''3301710''>that</span> <span m=''3301920''>satisfy</span>
  <span m=''3302570''>the</span> <span m=''3302730''>constraints.</span> </p><p><span
  m=''3313090''>OK,</span> <span m=''3314380''>so</span> <span m=''3314670''>this</span>
  <span m=''3315030''>gives</span> <span m=''3315290''>me</span> <span m=''3315460''>a</span>
  <span m=''3315540''>certain</span> <span m=''3316000''>set</span> <span m=''3316540''>of</span>
  <span m=''3317190''>pasts</span> <span m=''3317720''>that</span> <span m=''3317840''>are</span>
  <span m=''3317960''>consistent</span> <span m=''3318590''>with</span> <span m=''3318810''>each</span>
  <span m=''3319650''>possible</span> <span m=''3320120''>value</span> <span m=''3320500''>of</span>
  <span m=''3320570''>the</span> <span m=''3320690''>state</span> <span m=''3321220''>variable.</span>
  <span m=''3322850''>Let''s</span> <span m=''3323130''>call</span> <span m=''3323510''>that</span>
  <span m=''3324650''>y</span> <span m=''3326510''>projected</span> <span m=''3327170''>on</span>
  <span m=''3327320''>the</span> <span m=''3327420''>past</span> <span m=''3328000''>that''s</span>
  <span m=''3329540''>consistent</span> <span m=''3330180''>with</span> <span m=''3330530''>a</span>
  <span m=''3330590''>particular</span> <span m=''3331100''>value</span> <span m=''3331450''>of</span>
  <span m=''3331530''>the</span> <span m=''3331660''>state</span> <span m=''3332040''>variable,</span>
  <span m=''3333590''>the</span> <span m=''3333850''>super-state,</span> <span m=''3334450''>the</span>
  <span m=''3334550''>vector</span> <span m=''3334845''>of</span> <span m=''3335140''>states</span>
  <span m=''3335600''>here.</span> <span m=''3338280''>And</span> <span m=''3338430''>these</span>
  <span m=''3338680''>are</span> <span m=''3338720''>the</span> <span m=''3338820''>ones</span>
  <span m=''3340510''>in</span> <span m=''3340660''>the</span> <span m=''3340740''>future</span>
  <span m=''3341260''>that</span> <span m=''3341430''>are</span> <span m=''3341550''>consistent</span>
  <span m=''3342200''>with</span> <span m=''3342340''>that</span> <span m=''3342640''>state</span>
  <span m=''3343050''>variable.</span> <span m=''3346960''>We</span> <span m=''3347030''>define</span>
  <span m=''3347400''>that</span> <span m=''3348670''>so</span> <span m=''3348870''>the</span>
  <span m=''3348990''>set</span> <span m=''3349360''>of</span> <span m=''3349480''>all</span>
  <span m=''3349810''>possible</span> <span m=''3350520''>past</span> <span m=''3350980''>and</span>
  <span m=''3351220''>future</span> <span m=''3351640''>y''s</span> <span m=''3352590''>is</span>
  <span m=''3352740''>simply</span> <span m=''3353110''>this</span> <span m=''3353470''>Cartesian</span>
  <span m=''3354040''>product.</span> </p><p><span m=''3355362''>And</span> <span
  m=''3355790''>we</span> <span m=''3356100''>say</span> <span m=''3356340''>that</span>
  <span m=''3356490''>in a</span> <span m=''3356640''>more</span> <span m=''3356850''>graph</span>
  <span m=''3357180''>theoretic</span> <span m=''3357470''>way.</span> <span m=''3357760''>If</span>
  <span m=''3358010''>I</span> <span m=''3358100''>specify</span> <span m=''3358820''>the</span>
  <span m=''3358970''>state</span> <span m=''3359310''>here</span> <span m=''3359790''>as</span>
  <span m=''3360540''>some</span> <span m=''3360740''>particular</span> <span m=''3361230''>value,</span>
  <span m=''3361710''>sx,</span> <span m=''3362600''>and</span> <span m=''3362990''>I</span>
  <span m=''3363110''>fix</span> <span m=''3363540''>that,</span> <span m=''3365460''>I''ve</span>
  <span m=''3365590''>really</span> <span m=''3365810''>disconnected</span> <span
  m=''3366420''>the</span> <span m=''3366490''>graph.</span> <span m=''3370940''>For</span>
  <span m=''3371200''>a fixed</span> <span m=''3371700''>sx,</span> <span m=''3372460''>I</span>
  <span m=''3372550''>can</span> <span m=''3372710''>just</span> <span m=''3372930''>put</span>
  <span m=''3373140''>that</span> <span m=''3373370''>over</span> <span m=''3373620''>here,</span>
  <span m=''3374920''>put</span> <span m=''3375330''>that</span> <span m=''3375560''>over</span>
  <span m=''3375800''>here.</span> <span m=''3378790''>And</span> <span m=''3379000''>this</span>
  <span m=''3379220''>realizes,</span> <span m=''3380420''>this</span> <span m=''3380690''>connected</span>
  <span m=''3381350''>graph</span> <span m=''3381780''>that</span> <span m=''3381890''>realizes</span>
  <span m=''3382640''>the</span> <span m=''3382750''>Cartesian</span> <span m=''3383350''>product</span>
  <span m=''3383890''>of</span> <span m=''3385420''>whatever -- yp</span> <span m=''3386110''>of</span>
  <span m=''3386460''>sx.</span> <span m=''3387710''>This</span> <span m=''3387930''>just</span>
  <span m=''3388420''>comes</span> <span m=''3388700''>through</span> <span m=''3388920''>and</span>
  <span m=''3389190''>affects</span> <span m=''3389460''>that</span> <span m=''3390990''>with</span>
  <span m=''3391240''>yf</span> <span m=''3392480''>of</span> <span m=''3392640''>sx.</span>
  </p><p><span m=''3394890''>So</span> <span m=''3395120''>for</span> <span m=''3395320''>any</span>
  <span m=''3395410''>particular</span> <span m=''3395960''>value</span> <span m=''3396370''>of</span>
  <span m=''3396450''>the</span> <span m=''3396500''>state,</span> <span m=''3396970''>I</span>
  <span m=''3397130''>have a</span> <span m=''3398220''>certain</span> <span m=''3398550''>Cartesian</span>
  <span m=''3399110''>product</span> <span m=''3399650''>of</span> <span m=''3399760''>pasts</span>
  <span m=''3400580''>and</span> <span m=''3400760''>futures</span> <span m=''3401670''>they</span>
  <span m=''3401800''>can</span> <span m=''3401980''>occur.</span> <span m=''3403190''>Any</span>
  <span m=''3403460''>past</span> <span m=''3404000''>that''s</span> <span m=''3405050''>connected</span>
  <span m=''3405430''>with</span> <span m=''3405530''>that</span> <span m=''3405760''>state</span>
  <span m=''3406170''>can</span> <span m=''3406330''>be</span> <span m=''3406490''>connected</span>
  <span m=''3406900''>to</span> <span m=''3407010''>any</span> <span m=''3407250''>future</span>
  <span m=''3407830''>that''s</span> <span m=''3408135''>connected</span> <span m=''3408835''>with</span>
  <span m=''3409230''>this</span> <span m=''3409410''>state.</span> <span m=''3409790''>All</span>
  <span m=''3409960''>the</span> <span m=''3410050''>possible</span> <span m=''3410610''>future</span>
  <span m=''3411000''>continuations</span> <span m=''3412300''>of</span> <span m=''3412370''>any</span>
  <span m=''3412520''>particular</span> <span m=''3412980''>past</span> <span m=''3414150''>in</span>
  <span m=''3414350''>this</span> <span m=''3415140''>equivalence</span> <span m=''3415650''>class</span>
  <span m=''3417200''>are</span> <span m=''3417340''>the</span> <span m=''3417450''>same.</span>
  <span m=''3418950''>This</span> <span m=''3419030''>should</span> <span m=''3419290''>sound</span>
  <span m=''3419640''>very</span> <span m=''3419840''>much</span> <span m=''3420100''>like</span>
  <span m=''3420280''>the</span> <span m=''3420370''>kinds</span> <span m=''3420650''>of</span>
  <span m=''3420740''>things</span> <span m=''3421030''>we</span> <span m=''3421110''>were</span>
  <span m=''3421220''>talking</span> <span m=''3421590''>about</span> <span m=''3421850''>when</span>
  <span m=''3422010''>we</span> <span m=''3422160''>did</span> <span m=''3422470''>the</span>
  <span m=''3422940''>state</span> <span m=''3423220''>space</span> <span m=''3423580''>theorem.</span>
  </p><p><span m=''3427750''>And</span> <span m=''3427970''>we</span> <span m=''3428100''>get</span>
  <span m=''3428390''>a</span> <span m=''3428520''>sort</span> <span m=''3428860''>of</span>
  <span m=''3429100''>state</span> <span m=''3429570''>space</span> <span m=''3429840''>theorem</span>
  <span m=''3430180''>out of</span> <span m=''3430676''>this.</span> <span m=''3445070''>Just</span>
  <span m=''3445290''>to</span> <span m=''3445610''>draw</span> <span m=''3445920''>this</span>
  <span m=''3446220''>out,</span> <span m=''3448160''>we</span> <span m=''3448350''>kind</span>
  <span m=''3448550''>of</span> <span m=''3448640''>get a</span> <span m=''3448990''>two</span>
  <span m=''3449180''>section</span> <span m=''3450420''>trellis</span> <span m=''3450860''>realization</span>
  <span m=''3457474''>where</span> <span m=''3457960''>we</span> <span m=''3458090''>have</span>
  <span m=''3458280''>the</span> <span m=''3458380''>various</span> <span m=''3459130''>states</span>
  <span m=''3459730''>in</span> <span m=''3459830''>the</span> <span m=''3459930''>state</span>
  <span m=''3460270''>space</span> <span m=''3460720''>here,</span> <span m=''3461060''>s0,</span>
  <span m=''3461820''>s1,</span> <span m=''3462495''>and</span> <span m=''3462900''>so</span>
  <span m=''3463120''>forth.</span> <span m=''3465300''>We</span> <span m=''3465420''>have</span>
  <span m=''3465620''>the</span> <span m=''3465740''>pasts</span> <span m=''3466400''>that</span>
  <span m=''3466760''>are</span> <span m=''3466880''>connected</span> <span m=''3468870''>with</span>
  <span m=''3469370''>s0,</span> <span m=''3470800''>s1,</span> <span m=''3471320''>and</span>
  <span m=''3471500''>so</span> <span m=''3471670''>forth.</span> <span m=''3479770''>And</span>
  <span m=''3479870''>we</span> <span m=''3480000''>have</span> <span m=''3480120''>the</span>
  <span m=''3480220''>futures</span> <span m=''3480580''>that</span> <span m=''3480940''>are</span>
  <span m=''3481190''>connected</span> <span m=''3483370''>to</span> <span m=''3484000''>s0,</span>
  <span m=''3485190''>s1.</span> </p><p><span m=''3494790''>So</span> <span m=''3495960''>we</span>
  <span m=''3496130''>could</span> <span m=''3496320''>get</span> <span m=''3496590''>from</span>
  <span m=''3496830''>this,</span> <span m=''3497230''>this</span> <span m=''3497460''>picture</span>
  <span m=''3498370''>of</span> <span m=''3498480''>the</span> <span m=''3498610''>two</span>
  <span m=''3498790''>sectioned</span> <span m=''3499290''>trellis.</span> <span m=''3502180''>This</span>
  <span m=''3502500''>really</span> <span m=''3502800''>represents</span> <span m=''3503350''>a</span>
  <span m=''3503850''>set</span> <span m=''3504090''>of</span> <span m=''3504180''>parallel</span>
  <span m=''3504670''>transitions</span> <span m=''3505400''>here.</span> <span m=''3505700''>These</span>
  <span m=''3505930''>are</span> <span m=''3506070''>all</span> <span m=''3506500''>the</span>
  <span m=''3507250''>possible</span> <span m=''3507740''>pasts</span> <span m=''3508005''>that</span>
  <span m=''3509640''>are</span> <span m=''3509810''>consistent</span> <span m=''3510340''>with</span>
  <span m=''3510440''>that</span> <span m=''3510700''>state.</span> <span m=''3511110''>These</span>
  <span m=''3511340''>are</span> <span m=''3511410''>all the</span> <span m=''3511620''>futures</span>
  <span m=''3511885''>that</span> <span m=''3512150''>are</span> <span m=''3512560''>consistent</span>
  <span m=''3512740''>with</span> <span m=''3512870''>that</span> <span m=''3513330''>state.</span>
  <span m=''3513940''>We</span> <span m=''3514060''>can</span> <span m=''3514190''>tie</span>
  <span m=''3514420''>them</span> <span m=''3514580''>together,</span> <span m=''3515470''>and</span>
  <span m=''3515590''>that</span> <span m=''3515850''>realizes</span> <span m=''3516780''>the</span>
  <span m=''3516920''>code.</span> <span m=''3518470''>I</span> <span m=''3518650''>should</span>
  <span m=''3518970''>say</span> <span m=''3519420''>explicitly,</span> <span m=''3519870''>the</span>
  <span m=''3520000''>code</span> <span m=''3520660''>now</span> <span m=''3521160''>is</span>
  <span m=''3521610''>the</span> <span m=''3521760''>union</span> <span m=''3522510''>over</span>
  <span m=''3524130''>the</span> <span m=''3525150''>states</span> <span m=''3526160''>in</span>
  <span m=''3526310''>the</span> <span m=''3526450''>state</span> <span m=''3526930''>space,</span>
  <span m=''3529180''>the</span> <span m=''3529270''>super-state</span> <span m=''3529970''>space</span>
  <span m=''3530660''>of</span> <span m=''3532730''>the</span> <span m=''3532820''>pasts</span>
  <span m=''3534226''>there</span> <span m=''3537350''>times</span> <span m=''3537960''>the</span>
  <span m=''3538130''>futures.</span> <span m=''3539135''>They''re</span> <span m=''3539570''>consistent</span>
  <span m=''3539760''>with the state.</span> </p><p><span m=''3540570''>So</span>
  <span m=''3540800''>it''s</span> <span m=''3540970''>a</span> <span m=''3541030''>union
  of</span> <span m=''3541530''>Cartesian</span> <span m=''3542060''>products.</span>
  <span m=''3545420''>And</span> <span m=''3545510''>that''s</span> <span m=''3545750''>expressed</span>
  <span m=''3546210''>by</span> <span m=''3546340''>this</span> <span m=''3546580''>diagram.</span>
  <span m=''3548016''>This</span> <span m=''3548370''>is</span> <span m=''3548480''>one</span>
  <span m=''3548670''>of them.</span> <span m=''3548965''>This is</span> <span m=''3549260''>another</span>
  <span m=''3549540''>one.</span> <span m=''3550550''>These</span> <span m=''3550730''>are</span>
  <span m=''3550820''>all</span> <span m=''3551000''>of</span> <span m=''3551170''>them.</span>
  <span m=''3552250''>How</span> <span m=''3552380''>many</span> <span m=''3552610''>are</span>
  <span m=''3552770''>there?</span> <span m=''3553260''>The</span> <span m=''3553730''>size</span>
  <span m=''3554150''>of</span> <span m=''3554230''>the</span> <span m=''3554330''>super</span>
  <span m=''3554680''>state</span> <span m=''3554970''>variable,</span> <span m=''3556140''>which</span>
  <span m=''3556340''>by</span> <span m=''3556480''>the</span> <span m=''3556610''>way</span>
  <span m=''3556770''>is</span> <span m=''3556910''>the</span> <span m=''3556980''>product</span>
  <span m=''3557560''>of</span> <span m=''3557670''>the</span> <span m=''3557770''>sizes</span>
  <span m=''3558340''>of</span> <span m=''3558430''>the</span> <span m=''3558550''>state</span>
  <span m=''3558960''>spaces</span> <span m=''3559630''>of</span> <span m=''3559830''>each</span>
  <span m=''3560040''>of</span> <span m=''3560200''>these</span> <span m=''3560350''>individual</span>
  <span m=''3560900''>state</span> <span m=''3561300''>spaces</span> <span m=''3561750''>that</span>
  <span m=''3561890''>I</span> <span m=''3562040''>had</span> <span m=''3562180''>coming</span>
  <span m=''3562570''>across</span> <span m=''3562800''>here.</span> </p><p><span
  m=''3567770''>OK.</span> <span m=''3570910''>What''s</span> <span m=''3571250''>the</span>
  <span m=''3571720''>cut-set</span> <span m=''3571970''>bound</span> <span m=''3572370''>then?</span>
  <span m=''3575025''>For</span> <span m=''3575460''>linear</span> <span m=''3575940''>codes,</span>
  <span m=''3576450''>it''s</span> <span m=''3576620''>basically</span> <span m=''3577160''>the</span>
  <span m=''3577300''>same</span> <span m=''3577680''>as</span> <span m=''3577820''>the</span>
  <span m=''3577930''>state</span> <span m=''3578370''>space</span> <span m=''3578720''>theorem.</span>
  <span m=''3589700''>The</span> <span m=''3589780''>state</span> <span m=''3590110''>space</span>
  <span m=''3590550''>theorem</span> <span m=''3597730''>said</span> <span m=''3598010''>that</span>
  <span m=''3598290''>the</span> <span m=''3599800''>dimension</span> <span m=''3601095''>of</span>
  <span m=''3601380''>the</span> <span m=''3601590''>state</span> <span m=''3601960''>space</span>
  <span m=''3602370''>at</span> <span m=''3602530''>any</span> <span m=''3602660''>time
  --</span> <span m=''3603140''>well,</span> <span m=''3603450''>let</span> <span
  m=''3603520''>me</span> <span m=''3604270''>consider</span> <span m=''3604670''>now</span>
  <span m=''3604880''>this</span> <span m=''3605130''>state</span> <span m=''3605430''>space,</span>
  <span m=''3605710''>the</span> <span m=''3605990''>super-state</span> <span m=''3606480''>variable.</span>
  <span m=''3607462''>The</span> <span m=''3607880''>dimension</span> <span m=''3608380''>of</span>
  <span m=''3608500''>this</span> <span m=''3608640''>super-state</span> <span m=''3609370''>variable</span>
  <span m=''3609900''>has</span> <span m=''3610840''>got</span> <span m=''3611050''>to</span>
  <span m=''3611120''>be</span> <span m=''3611270''>greater</span> <span m=''3611660''>than</span>
  <span m=''3611970''>or</span> <span m=''3612080''>equal</span> <span m=''3612450''>to</span>
  <span m=''3613960''>the</span> <span m=''3614060''>dimension</span> <span m=''3614510''>of</span>
  <span m=''3614630''>the</span> <span m=''3615120''>code</span> <span m=''3615510''>that</span>
  <span m=''3615620''>we''re</span> <span m=''3615760''>realizing</span> <span m=''3618310''>minus</span>
  <span m=''3618970''>the</span> <span m=''3619110''>dimension</span> <span m=''3620470''>of</span>
  <span m=''3620880''>the --</span> <span m=''3621630''>this</span> <span m=''3622050''>is</span>
  <span m=''3622200''>going</span> <span m=''3622280''>to</span> <span m=''3622350''>be</span>
  <span m=''3622430''>bad</span> <span m=''3622730''>notation</span> <span m=''3623370''>now.</span>
  <span m=''3626530''>Now</span> <span m=''3626730''>I</span> <span m=''3626810''>mean</span>
  <span m=''3627120''>the</span> <span m=''3627440''>sub-code,</span> <span m=''3628550''>so</span>
  <span m=''3628730''>I</span> <span m=''3628900''>should</span> <span m=''3629140''>have</span>
  <span m=''3629270''>written</span> <span m=''3629500''>something</span> <span m=''3629850''>else</span>
  <span m=''3630130''>for</span> <span m=''3630230''>the</span> <span m=''3630360''>constraint</span>
  <span m=''3630890''>here.</span> </p><p><span m=''3636320''>Minus</span> <span m=''3636670''>the</span>
  <span m=''3636740''>dimension</span> <span m=''3637350''>of</span> <span m=''3637530''>the</span>
  <span m=''3637640''>sub-code</span> <span m=''3638310''>whose</span> <span m=''3638570''>support</span>
  <span m=''3639100''>is</span> <span m=''3639310''>entirely</span> <span m=''3639840''>on</span>
  <span m=''3639950''>the</span> <span m=''3640040''>past,</span> <span m=''3640590''>minus</span>
  <span m=''3640940''>the</span> <span m=''3641020''>dimension</span> <span m=''3641790''>of
  the sub-code</span> <span m=''3642550''>whose</span> <span m=''3642640''>support</span>
  <span m=''3643210''>is</span> <span m=''3643380''>entirely</span> <span m=''3643890''>on</span>
  <span m=''3644010''>the</span> <span m=''3644090''>future.</span> <span m=''3645260''>And</span>
  <span m=''3645390''>the</span> <span m=''3645460''>state</span> <span m=''3645780''>space</span>
  <span m=''3646170''>theorem</span> <span m=''3646450''>still</span> <span m=''3646750''>applies</span>
  <span m=''3649570''>for</span> <span m=''3649740''>this</span> <span m=''3650060''>partition.</span>
  <span m=''3651285''>So</span> <span m=''3651740''>that</span> <span m=''3652030''>gives</span>
  <span m=''3652240''>me</span> <span m=''3652430''>a</span> <span m=''3652570''>lower</span>
  <span m=''3652990''>bound</span> <span m=''3655620''>on</span> <span m=''3656000''>the</span>
  <span m=''3658200''>total</span> <span m=''3658550''>dimension</span> <span m=''3659160''>of</span>
  <span m=''3659380''>the</span> <span m=''3659490''>states</span> <span m=''3661180''>in</span>
  <span m=''3661570''>any</span> <span m=''3661810''>cut-set.</span> </p><p><span
  m=''3670060''>So</span> <span m=''3672250''>for</span> <span m=''3673410''>example,</span>
  <span m=''3675330''>in</span> <span m=''3675470''>the</span> <span m=''3675740''>8,
  4</span> <span m=''3676920''>code,</span> <span m=''3680500''>suppose</span> <span
  m=''3680920''>we</span> <span m=''3681040''>have</span> <span m=''3681740''>any</span>
  <span m=''3683410''>realization,</span> <span m=''3688210''>so</span> <span m=''3689070''>some</span>
  <span m=''3689290''>graph</span> <span m=''3689670''>here,</span> <span m=''3691090''>and</span>
  <span m=''3691880''>any</span> <span m=''3693820''>cut-set</span> <span m=''3695970''>such</span>
  <span m=''3698570''>that</span> <span m=''3699270''>the</span> <span m=''3699360''>size</span>
  <span m=''3701170''>of --</span> <span m=''3706440''>I should</span> <span m=''3706930''>say</span>
  <span m=''3707170''>the</span> <span m=''3707280''>dimension.</span> <span m=''3708475''>I</span>
  <span m=''3708960''>really</span> <span m=''3709300''>mean</span> <span m=''3709660''>that
  there</span> <span m=''3710020''>are</span> <span m=''3710350''>four</span> <span
  m=''3710930''>external</span> <span m=''3711560''>variables</span> <span m=''3712690''>in</span>
  <span m=''3712840''>the</span> <span m=''3712940''>past</span> <span m=''3713235''>and</span>
  <span m=''3713530''>in</span> <span m=''3713650''>the</span> <span m=''3713770''>future.</span>
  <span m=''3714730''>This is</span> <span m=''3715610''>dimension,</span> <span m=''3716890''>dimension.</span>
  <span m=''3719340''>In other</span> <span m=''3719830''>words,</span> <span m=''3720320''>we</span>
  <span m=''3720530''>have</span> <span m=''3721360''>four</span> <span m=''3721710''>variables</span>
  <span m=''3722220''>sticking</span> <span m=''3722640''>out</span> <span m=''3722830''>here,</span>
  <span m=''3723410''>and</span> <span m=''3723880''>four</span> <span m=''3724230''>variables</span>
  <span m=''3724660''>sticking</span> <span m=''3725120''>out</span> <span m=''3725350''>here,</span>
  <span m=''3726600''>and</span> <span m=''3726710''>we</span> <span m=''3726990''>have
  a cut</span> <span m=''3727260''>set</span> <span m=''3728220''>somehow</span> <span
  m=''3728690''>going</span> <span m=''3729000''>through</span> <span m=''3729240''>there.</span>
  <span m=''3732030''>So</span> <span m=''3732430''>our</span> <span m=''3732610''>picture</span>
  <span m=''3733050''>now</span> <span m=''3733540''>is going to</span> <span m=''3733730''>look</span>
  <span m=''3734530''>something</span> <span m=''3734950''>like</span> <span m=''3735200''>this.</span>
  </p><p><span m=''3737520''>What''s</span> <span m=''3737890''>the</span> <span m=''3738260''>minimum</span>
  <span m=''3738850''>possible</span> <span m=''3739460''>dimension</span> <span m=''3740240''>of</span>
  <span m=''3740510''>the</span> <span m=''3742690''>total</span> <span m=''3743050''>dimension</span>
  <span m=''3743630''>of</span> <span m=''3743840''>the</span> <span m=''3744010''>edges</span>
  <span m=''3744470''>that</span> <span m=''3744590''>cross</span> <span m=''3744990''>this</span>
  <span m=''3746770''>cut-set,</span> <span m=''3747560''>the</span> <span m=''3747910''>state</span>
  <span m=''3748350''>spaces</span> <span m=''3748640''>that are in</span> <span m=''3748940''>this
  cut-set.</span> <span m=''3750240''>We</span> <span m=''3750360''>know</span> <span
  m=''3750500''>this</span> <span m=''3750720''>code</span> <span m=''3750970''>very</span>
  <span m=''3751210''>well</span> <span m=''3751480''>now.</span> <span m=''3757290''>Let''s</span>
  <span m=''3757570''>do</span> <span m=''3757710''>the</span> <span m=''3757810''>Muder</span>
  <span m=''3758090''>bound.</span> <span m=''3758450''>What''s</span> <span m=''3758600''>the</span>
  <span m=''3758740''>maximum</span> <span m=''3759270''>dimension?</span> <span m=''3760170''>The</span>
  <span m=''3760250''>dimension</span> <span m=''3760560''>of the</span> <span m=''3760670''>code</span>
  <span m=''3761070''>is 4.</span> <span m=''3761920''>What''s</span> <span m=''3762090''>the</span>
  <span m=''3762260''>maximum</span> <span m=''3762830''>dimension</span> <span m=''3764440''>of</span>
  <span m=''3764590''>any</span> <span m=''3764890''>code</span> <span m=''3767550''>that</span>
  <span m=''3767690''>lives</span> <span m=''3768030''>on</span> <span m=''3768190''>the</span>
  <span m=''3768260''>past?</span> <span m=''3771090''>It''s</span> <span m=''3771290''>1,</span>
  <span m=''3771680''>because</span> <span m=''3771970''>such</span> <span m=''3772200''>a</span>
  <span m=''3772260''>code</span> <span m=''3772640''>has</span> <span m=''3772810''>to</span>
  <span m=''3772930''>have</span> <span m=''3773050''>minimum</span> <span m=''3773330''>distance</span>
  <span m=''3773940''>4.</span> <span m=''3774490''>So</span> <span m=''3776180''>it</span>
  <span m=''3776360''>can''t</span> <span m=''3776630''>have</span> <span m=''3776860''>dimension</span>
  <span m=''3777400''>greater</span> <span m=''3777710''>than</span> <span m=''3777870''>the</span>
  <span m=''3777950''>repetition</span> <span m=''3778590''>code</span> <span m=''3779000''>of
  length</span> <span m=''3779220''>4.</span> <span m=''3780560''>So</span> <span
  m=''3781240''>4</span> <span m=''3781660''>minus</span> <span m=''3782070''>1,</span>
  <span m=''3782510''>same</span> <span m=''3782840''>argument</span> <span m=''3783200''>for</span>
  <span m=''3783310''>the</span> <span m=''3783380''>future,</span> <span m=''3784600''>equals</span>
  <span m=''3785020''>2.</span> </p><p><span m=''3788550''>So</span> <span m=''3788810''>it</span>
  <span m=''3788920''>says</span> <span m=''3789350''>that</span> <span m=''3789740''>however</span>
  <span m=''3790130''>you</span> <span m=''3790290''>do</span> <span m=''3790570''>it,</span>
  <span m=''3792690''>you''re</span> <span m=''3792850''>going</span> <span m=''3792950''>to</span>
  <span m=''3793130''>have</span> <span m=''3793310''>to</span> <span m=''3793470''>have</span>
  <span m=''3794810''>at</span> <span m=''3794890''>least</span> <span m=''3795210''>two</span>
  <span m=''3795410''>binary</span> <span m=''3795900''>edges</span> <span m=''3796450''>or</span>
  <span m=''3796570''>one</span> <span m=''3796960''>quaternary</span> <span m=''3797670''>edge</span>
  <span m=''3798110''>crossing</span> <span m=''3799680''>a</span> <span m=''3800090''>cut-set</span>
  <span m=''3800380''>that</span> <span m=''3800550''>divides</span> <span m=''3801640''>the</span>
  <span m=''3802310''>external</span> <span m=''3802830''>variables</span> <span m=''3803390''>into</span>
  <span m=''3803580''>two</span> <span m=''3803840''>equal</span> <span m=''3804150''>sized</span>
  <span m=''3804550''>parts.</span> <span m=''3810180''>So</span> <span m=''3811950''>let''s</span>
  <span m=''3812200''>go</span> <span m=''3812360''>further.</span> <span m=''3812770''>Let''s</span>
  <span m=''3812990''>suppose</span> <span m=''3813500''>we</span> <span m=''3813640''>want</span>
  <span m=''3814040''>a</span> <span m=''3814190''>cycle-free</span> <span m=''3814790''>graph.</span>
  <span m=''3817550''>OK,</span> <span m=''3817830''>if</span> <span m=''3818130''>we</span>
  <span m=''3818250''>have</span> <span m=''3818350''>a</span> <span m=''3818400''>cycle-free</span>
  <span m=''3819050''>graph,</span> <span m=''3820070''>then</span> <span m=''3820200''>all</span>
  <span m=''3820410''>of the</span> <span m=''3820805''>cut-sets</span> <span m=''3821110''>are</span>
  <span m=''3821200''>single</span> <span m=''3821580''>edges.</span> </p><p><span
  m=''3823640''>All</span> <span m=''3823770''>right,</span> <span m=''3824120''>so</span>
  <span m=''3825616''>in a</span> <span m=''3826090''>cycle-free</span> <span m=''3826780''>graph,</span>
  <span m=''3828180''>when</span> <span m=''3828430''>we</span> <span m=''3828550''>make</span>
  <span m=''3828800''>a</span> <span m=''3828920''>cut, it''s</span> <span m=''3829410''>through</span>
  <span m=''3829600''>a</span> <span m=''3829670''>single</span> <span m=''3830080''>edge.</span>
  <span m=''3830910''>And</span> <span m=''3831210''>we''re</span> <span m=''3831400''>saying</span>
  <span m=''3831700''>the</span> <span m=''3831780''>state</span> <span m=''3832170''>space</span>
  <span m=''3834600''>if</span> <span m=''3835250''>there''s</span> <span m=''3835480''>a</span>
  <span m=''3835540''>way</span> <span m=''3835750''>you</span> <span m=''3835880''>can</span>
  <span m=''3836000''>make</span> <span m=''3836220''>a</span> <span m=''3836280''>cut</span>
  <span m=''3836640''>that</span> <span m=''3836770''>divides</span> <span m=''3837115''>this</span>
  <span m=''3837460''>into</span> <span m=''3837620''>two</span> <span m=''3837830''>equal</span>
  <span m=''3838120''>parts,</span> <span m=''3838510''>the</span> <span m=''3838570''>state</span>
  <span m=''3838870''>space</span> <span m=''3839750''>has</span> <span m=''3840070''>to</span>
  <span m=''3840620''>have</span> <span m=''3840760''>dimension</span> <span m=''3841210''>2,</span>
  <span m=''3841490''>it</span> <span m=''3841540''>has</span> <span m=''3841730''>to</span>
  <span m=''3841870''>have</span> <span m=''3842000''>size</span> <span m=''3842420''>4</span>
  <span m=''3843460''>for</span> <span m=''3843630''>any</span> <span m=''3843810''>cycle-free</span>
  <span m=''3844390''>graph.</span> </p><p><span m=''3852650''>Similarly,</span> <span
  m=''3853460''>if</span> <span m=''3853640''>we</span> <span m=''3853740''>have</span>
  <span m=''3853960''>the</span> <span m=''3854110''>24,</span> <span m=''3855520''>12,</span>
  <span m=''3856090''>8</span> <span m=''3856400''>code,</span> <span m=''3856880''>we''ve</span>
  <span m=''3857060''>proved</span> <span m=''3857320''>that</span> <span m=''3857580''>the</span>
  <span m=''3859270''>minimum</span> <span m=''3859690''>dimension</span> <span m=''3861930''>of</span>
  <span m=''3862110''>any</span> <span m=''3863260''>central</span> <span m=''3863830''>cut</span>
  <span m=''3864190''>has</span> <span m=''3864500''>to</span> <span m=''3864600''>be</span>
  <span m=''3864820''>at</span> <span m=''3864940''>least</span> <span m=''3867480''>6.</span>
  <span m=''3868820''>No,</span> <span m=''3869130''>in</span> <span m=''3869440''>the</span>
  <span m=''3869530''>center,</span> <span m=''3869910''>it has</span> <span m=''3870110''>to</span>
  <span m=''3870190''>be</span> <span m=''3870300''>at</span> <span m=''3870370''>least</span>
  <span m=''3871070''>8,</span> <span m=''3871350''>right?</span> <span m=''3877870''>Yeah,</span>
  <span m=''3879250''>because</span> <span m=''3879550''>the</span> <span m=''3879630''>dimension</span>
  <span m=''3880400''>of</span> <span m=''3880490''>the</span> <span m=''3880590''>code</span>
  <span m=''3880930''>is</span> <span m=''3881100''>12,</span> <span m=''3881385''>and</span>
  <span m=''3883770''>a</span> <span m=''3883990''>sub-code</span> <span m=''3885910''>that</span>
  <span m=''3886340''>has</span> <span m=''3886640''>support</span> <span m=''3887130''>on</span>
  <span m=''3887280''>12</span> <span m=''3887770''>can''t</span> <span m=''3888030''>have</span>
  <span m=''3888270''>dimension</span> <span m=''3888620''>more</span> <span m=''3888820''>than</span>
  <span m=''3889090''>2.</span> <span m=''3889810''>This</span> <span m=''3890050''>can''t</span>
  <span m=''3890250''>have</span> <span m=''3890460''>dimension</span> <span m=''3890840''>more</span>
  <span m=''3891130''>than</span> <span m=''3891300''>2.</span> <span m=''3892250''>So</span>
  <span m=''3892560''>that</span> <span m=''3892810''>would</span> <span m=''3893010''>be</span>
  <span m=''3893260''>8.</span> <span m=''3894140''>So</span> <span m=''3894830''>for</span>
  <span m=''3895010''>the</span> <span m=''3895140''>24,</span> <span m=''3895650''>12,</span>
  <span m=''3896030''>8</span> <span m=''3896300''>code,</span> <span m=''3899220''>the</span>
  <span m=''3899340''>set</span> <span m=''3899670''>of</span> <span m=''3899840''>edges</span>
  <span m=''3900340''>that</span> <span m=''3900470''>cross</span> <span m=''3900950''>the</span>
  <span m=''3901090''>cut</span> <span m=''3901690''>have</span> <span m=''3901960''>to</span>
  <span m=''3902090''>have</span> <span m=''3902210''>total</span> <span m=''3902550''>dimension</span>
  <span m=''3903370''>at</span> <span m=''3903510''>least</span> <span m=''3903910''>8.</span>
  <span m=''3905080''>And</span> <span m=''3905190''>if</span> <span m=''3905290''>we</span>
  <span m=''3905380''>want it</span> <span m=''3905690''>to</span> <span m=''3905780''>be</span>
  <span m=''3905930''>cycle</span> <span m=''3906360''>free,</span> <span m=''3907970''>then</span>
  <span m=''3908100''>there</span> <span m=''3908230''>has</span> <span m=''3908480''>to</span>
  <span m=''3908560''>be</span> <span m=''3908670''>a</span> <span m=''3908720''>single</span>
  <span m=''3909180''>edge</span> <span m=''3909670''>that</span> <span m=''3909890''>has</span>
  <span m=''3910220''>dimension</span> <span m=''3910930''>8.</span> </p><p><span
  m=''3914090''>So</span> <span m=''3914490''>the</span> <span m=''3929340''>general</span>
  <span m=''3929860''>conclusions --</span> <span m=''3937930''>we</span> <span m=''3938390''>first</span>
  <span m=''3938740''>talked</span> <span m=''3938990''>about</span> <span m=''3939190''>trellis</span>
  <span m=''3939570''>realizations.</span> <span m=''3940890''>We</span> <span m=''3941290''>can</span>
  <span m=''3941480''>generalize</span> <span m=''3942190''>that</span> <span m=''3942650''>any</span>
  <span m=''3943010''>cycle-free</span> <span m=''3943780''>realization--</span> <span
  m=''3945940''>and</span> <span m=''3946110''>we''re</span> <span m=''3946250''>going</span>
  <span m=''3946450''>to</span> <span m=''3947830''>see that</span> <span m=''3948170''>we</span>
  <span m=''3948450''>have</span> <span m=''3948740''>strong</span> <span m=''3949390''>motivation</span>
  <span m=''3950210''>to</span> <span m=''3950360''>keep</span> <span m=''3950690''>our</span>
  <span m=''3952250''>realization</span> <span m=''3953380''>cycle-free,</span> <span
  m=''3953740''>because</span> <span m=''3953980''>then</span> <span m=''3954130''>we</span>
  <span m=''3954260''>can</span> <span m=''3954390''>do</span> <span m=''3954570''>exact</span>
  <span m=''3955180''>maximum</span> <span m=''3955620''>likelihood</span> <span m=''3956090''>decoding.</span>
  <span m=''3958080''>So</span> <span m=''3958490''>we''d</span> <span m=''3958650''>like</span>
  <span m=''3958890''>to</span> <span m=''3959020''>have</span> <span m=''3959150''>cycle-free</span>
  <span m=''3959760''>realizations.</span> </p><p><span m=''3962610''>But</span> <span
  m=''3963110''>what</span> <span m=''3963300''>have</span> <span m=''3963360''>we</span>
  <span m=''3963530''>just</span> <span m=''3963780''>seen?</span> <span m=''3965450''>We''ve</span>
  <span m=''3965640''>just</span> <span m=''3965930''>seen</span> <span m=''3966340''>that</span>
  <span m=''3966570''>the</span> <span m=''3969720''>state</span> <span m=''3970780''>complexity</span>
  <span m=''3975740''>cannot</span> <span m=''3976290''>be</span> <span m=''3979640''>less</span>
  <span m=''3981130''>than</span> <span m=''3983180''>that</span> <span m=''3984822''>of
  a</span> <span m=''3985290''>trellis</span> <span m=''3990620''>realization</span>
  <span m=''3996440''>with</span> <span m=''3997100''>a</span> <span m=''3998550''>comparable</span>
  <span m=''3999210''>cut.</span> <span m=''4000120''>In</span> <span m=''4000180''>other</span>
  <span m=''4000320''>words,</span> <span m=''4000550''>one</span> <span m=''4000860''>that</span>
  <span m=''4001060''>divides</span> <span m=''4001740''>the</span> <span m=''4003170''>past</span>
  <span m=''4003590''>and</span> <span m=''4003690''>future</span> <span m=''4004120''>in</span>
  <span m=''4004220''>the</span> <span m=''4004310''>same</span> <span m=''4004620''>way,</span>
  <span m=''4006000''>divides</span> <span m=''4006470''>the</span> <span m=''4006580''>external</span>
  <span m=''4007060''>variables</span> <span m=''4007670''>into</span> <span m=''4008500''>the</span>
  <span m=''4008620''>same</span> <span m=''4008950''>size.</span> </p><p><span m=''4011720''>OK,</span>
  <span m=''4012130''>so</span> <span m=''4012310''>we</span> <span m=''4012450''>really</span>
  <span m=''4012730''>can''t</span> <span m=''4014150''>beat</span> <span m=''4014570''>the</span>
  <span m=''4014760''>trellis</span> <span m=''4015180''>bounds,</span> <span m=''4015600''>the</span>
  <span m=''4015700''>Muder</span> <span m=''4015960''>bound,</span> <span m=''4016320''>in</span>
  <span m=''4016430''>particular.</span> <span m=''4019240''>Now</span> <span m=''4019380''>again,</span>
  <span m=''4019680''>there''s</span> <span m=''4019840''>some</span> <span m=''4020040''>games</span>
  <span m=''4020460''>we</span> <span m=''4020600''>can</span> <span m=''4021060''>play.</span>
  <span m=''4022520''>Let''s</span> <span m=''4023460''>ask</span> <span m=''4023910''>about</span>
  <span m=''4024320''>the</span> <span m=''4024700''>24,</span> <span m=''4025380''>12,</span>
  <span m=''4026110''>8 cut.</span> <span m=''4026365''>We''ve</span> <span m=''4026620''>said</span>
  <span m=''4029490''>if</span> <span m=''4029660''>we</span> <span m=''4029740''>want</span>
  <span m=''4029950''>to</span> <span m=''4030010''>realize</span> <span m=''4030450''>it
  with</span> <span m=''4030570''>the</span> <span m=''4030670''>cycle-free</span>
  <span m=''4031230''>realization,</span> <span m=''4032460''>this</span> <span m=''4032710''>says,</span>
  <span m=''4034000''>well,</span> <span m=''4034340''>if</span> <span m=''4034460''>we</span>
  <span m=''4035290''>have</span> <span m=''4035450''>a</span> <span m=''4035610''>cut</span>
  <span m=''4035970''>that</span> <span m=''4036110''>divides</span> <span m=''4036750''>the</span>
  <span m=''4038940''>external</span> <span m=''4039380''>variables</span> <span m=''4039930''>into</span>
  <span m=''4040130''>two</span> <span m=''4040700''>parts</span> <span m=''4041070''>of</span>
  <span m=''4041140''>size</span> <span m=''4041600''>8,</span> <span m=''4042690''>then</span>
  <span m=''4043390''>we''re</span> <span m=''4043620''>going</span> <span m=''4043730''>to</span>
  <span m=''4043770''>be</span> <span m=''4043870''>stuck</span> <span m=''4044250''>with</span>
  <span m=''4044420''>a</span> <span m=''4044590''>state</span> <span m=''4044920''>space</span>
  <span m=''4045400''>of</span> <span m=''4045510''>dimension</span> <span m=''4045990''>8</span>
  <span m=''4046360''>and a</span> <span m=''4046660''>size</span> <span m=''4047090''>256.</span>
  <span m=''4048490''>No</span> <span m=''4048600''>way</span> <span m=''4048730''>around</span>
  <span m=''4049070''>it.</span> </p><p><span m=''4051610''>Here''s</span> <span m=''4052870''>a</span>
  <span m=''4052940''>slight</span> <span m=''4053310''>way</span> <span m=''4053530''>around</span>
  <span m=''4053950''>it.</span> <span m=''4056700''>Let</span> <span m=''4056920''>me</span>
  <span m=''4057740''>hypothesize</span> <span m=''4058970''>a</span> <span m=''4059050''>realization</span>
  <span m=''4059860''>that</span> <span m=''4059980''>looks</span> <span m=''4060280''>like</span>
  <span m=''4060660''>this.</span> <span m=''4066840''>This</span> <span m=''4067520''>is</span>
  <span m=''4067720''>a</span> <span m=''4068030''>14,</span> <span m=''4068620''>7</span>
  <span m=''4069130''>code.</span> <span m=''4070380''>So</span> <span m=''4070740''>is</span>
  <span m=''4070960''>this.</span> <span m=''4072490''>So</span> <span m=''4072990''>is</span>
  <span m=''4073250''>this.</span> <span m=''4074475''>We''re</span> <span m=''4074880''>going</span>
  <span m=''4075040''>to</span> <span m=''4075100''>divide</span> <span m=''4075740''>the</span>
  <span m=''4076770''>external</span> <span m=''4077410''>variables</span> <span m=''4078250''>into</span>
  <span m=''4078610''>three</span> <span m=''4079160''>parts,</span> <span m=''4079710''>each</span>
  <span m=''4080010''>of</span> <span m=''4080120''>size</span> <span m=''4080830''>8.</span>
  <span m=''4087790''>And</span> <span m=''4088190''>we''re</span> <span m=''4088350''>going</span>
  <span m=''4088450''>to</span> <span m=''4088620''>have</span> <span m=''4088780''>three</span>
  <span m=''4089310''>internal</span> <span m=''4089880''>state</span> <span m=''4090260''>spaces,</span>
  <span m=''4091810''>each</span> <span m=''4092060''>of</span> <span m=''4092210''>dimension</span>
  <span m=''4092980''>6.</span> <span m=''4093780''>And</span> <span m=''4094265''>we''re
  going to</span> <span m=''4094750''>constrain</span> <span m=''4095380''>those</span>
  <span m=''4095740''>by an</span> <span m=''4095950''>18,</span> <span m=''4096399''>9</span>
  <span m=''4096810''>code.</span> <span m=''4097959''>And</span> <span m=''4098450''>again,</span>
  <span m=''4098660''>these</span> <span m=''4098899''>all</span> <span m=''4099000''>have</span>
  <span m=''4099149''>rate</span> <span m=''4099399''>1/2</span> <span m=''4099560''>because</span>
  <span m=''4100000''>this</span> <span m=''4100304''>code is</span> <span m=''4100609''>dual.</span>
  </p><p><span m=''4102069''>Now,</span> <span m=''4102319''>is</span> <span m=''4102439''>there</span>
  <span m=''4102590''>anything</span> <span m=''4102970''>in</span> <span m=''4103060''>what</span>
  <span m=''4103229''>I''ve</span> <span m=''4103399''>done</span> <span m=''4103670''>that</span>
  <span m=''4103830''>prevents</span> <span m=''4104529''>this</span> <span m=''4104750''>kind</span>
  <span m=''4104950''>of</span> <span m=''4105020''>realization?</span> <span m=''4108710''>Let''s</span>
  <span m=''4108939''>test</span> <span m=''4109279''>the</span> <span m=''4109380''>cut-sets.</span>
  <span m=''4110020''>Where</span> <span m=''4110340''>are</span> <span m=''4110390''>the</span>
  <span m=''4110510''>cut-sets</span> <span m=''4111120''>in--</span> <span m=''4111689''>well,</span>
  <span m=''4112240''>A,</span> <span m=''4112470''>is</span> <span m=''4112649''>this</span>
  <span m=''4112710''>cycle-free</span> <span m=''4113399''>realization?</span> <span
  m=''4114330''>Yes,</span> <span m=''4115300''>OK,</span> <span m=''4115890''>good.</span>
  <span m=''4117500''>Let''s</span> <span m=''4117710''>test</span> <span m=''4118000''>the</span>
  <span m=''4118459''>cut-sets.</span> <span m=''4118819''>It''s</span> <span m=''4119010''>kind</span>
  <span m=''4119240''>of</span> <span m=''4119399''>a</span> <span m=''4120109''>three-way</span>
  <span m=''4120729''>symmetrical</span> <span m=''4121939''>thing.</span> <span m=''4122229''>The</span>
  <span m=''4122500''>internal</span> <span m=''4123189''>cut-sets</span> <span m=''4123540''>are</span>
  <span m=''4123640''>here,</span> <span m=''4123990''>here,</span> <span m=''4124300''>and</span>
  <span m=''4124390''>here.</span> <span m=''4126689''>Each</span> <span m=''4126960''>of</span>
  <span m=''4127010''>these</span> <span m=''4127590''>cut-sets</span> <span m=''4128750''>divides</span>
  <span m=''4129670''>the</span> <span m=''4129880''>coordinates</span> <span m=''4130520''>into</span>
  <span m=''4131859''>one</span> <span m=''4132140''>set</span> <span m=''4132590''>of</span>
  <span m=''4132670''>size</span> <span m=''4133100''>8</span> <span m=''4133410''>and</span>
  <span m=''4133510''>one</span> <span m=''4133720''>set</span> <span m=''4134060''>of</span>
  <span m=''4134140''>size</span> <span m=''4134800''>16.</span> <span m=''4137899''>In</span>
  <span m=''4138040''>that</span> <span m=''4138279''>case,</span> <span m=''4138970''>what</span>
  <span m=''4139470''>does</span> <span m=''4139590''>the</span> <span m=''4139680''>Muder</span>
  <span m=''4139960''>bound</span> <span m=''4140359''>give</span> <span m=''4140550''>us?</span>
  </p><p><span m=''4141550''>In</span> <span m=''4141660''>that</span> <span m=''4141910''>case,</span>
  <span m=''4143080''>8,</span> <span m=''4143330''>16,</span> <span m=''4143939''>the</span>
  <span m=''4144120''>dimension</span> <span m=''4144510''>of the</span> <span m=''4144590''>code</span>
  <span m=''4144890''>is</span> <span m=''4144979''>still</span> <span m=''4145340''>12.</span>
  <span m=''4146450''>The</span> <span m=''4146939''>minimum</span> <span m=''4147399''>dimension</span>
  <span m=''4147520''>of</span> <span m=''4147790''>a</span> <span m=''4148149''>code</span>
  <span m=''4148540''>of</span> <span m=''4148760''>length</span> <span m=''4149200''>16</span>
  <span m=''4150069''>and</span> <span m=''4150540''>minimum</span> <span m=''4150850''>distance</span>
  <span m=''4151359''>8</span> <span m=''4151680''>is</span> <span m=''4152170''>5.</span>
  <span m=''4153370''>And</span> <span m=''4153850''>one</span> <span m=''4154200''>of</span>
  <span m=''4154840''>length</span> <span m=''4155220''>8</span> <span m=''4155580''>and</span>
  <span m=''4155740''>minimum</span> <span m=''4156000''>distance</span> <span m=''4156450''>8</span>
  <span m=''4156710''>is</span> <span m=''4156920''>1.</span> <span m=''4158010''>So</span>
  <span m=''4158380''>as</span> <span m=''4158580''>we</span> <span m=''4158729''>did</span>
  <span m=''4159040''>on the</span> <span m=''4159109''>homework,</span> <span m=''4159670''>we</span>
  <span m=''4159859''>find</span> <span m=''4160290''>that</span> <span m=''4161500''>we</span>
  <span m=''4161700''>are</span> <span m=''4161890''>permitted</span> <span m=''4162950''>to</span>
  <span m=''4163060''>have</span> <span m=''4163170''>a</span> <span m=''4163210''>state</span>
  <span m=''4163580''>space--</span> <span m=''4164399''>the</span> <span m=''4164540''>minimal</span>
  <span m=''4165060''>state</span> <span m=''4165410''>space</span> <span m=''4165800''>here</span>
  <span m=''4166090''>could</span> <span m=''4166260''>have</span> <span m=''4166430''>dimension</span>
  <span m=''4166870''>6.</span> <span m=''4168100''>So</span> <span m=''4168300''>this</span>
  <span m=''4168910''>possibly</span> <span m=''4169450''>could</span> <span m=''4169700''>occur.</span>
  </p><p><span m=''4171180''>Again,</span> <span m=''4171490''>we''re</span> <span
  m=''4171630''>kind</span> <span m=''4171779''>of</span> <span m=''4171920''>camouflaging</span>
  <span m=''4172750''>some</span> <span m=''4172979''>of</span> <span m=''4173029''>the</span>
  <span m=''4173120''>state</span> <span m=''4173479''>space.</span> <span m=''4174300''>You</span>
  <span m=''4174390''>see</span> <span m=''4174560''>there</span> <span m=''4174779''>is</span>
  <span m=''4174939''>no</span> <span m=''4175100''>central</span> <span m=''4175750''>state</span>
  <span m=''4176100''>space</span> <span m=''4176470''>in</span> <span m=''4176670''>this.</span>
  <span m=''4176870''>There</span> <span m=''4177050''>is</span> <span m=''4177200''>no</span>
  <span m=''4177689''>cut-set</span> <span m=''4177840''>that</span> <span m=''4177990''>partitions</span>
  <span m=''4178640''>it</span> <span m=''4179080''>into</span> <span m=''4179330''>12</span>
  <span m=''4179670''>and</span> <span m=''4179770''>12.</span> <span m=''4180670''>So</span>
  <span m=''4180950''>by</span> <span m=''4181170''>being</span> <span m=''4181399''>a</span>
  <span m=''4181460''>little</span> <span m=''4181640''>bit</span> <span m=''4181840''>clever,</span>
  <span m=''4182800''>we''ve</span> <span m=''4182950''>got</span> <span m=''4183120''>it</span>
  <span m=''4183240''>down</span> <span m=''4183460''>to</span> <span m=''4183529''>something</span>
  <span m=''4184060''>where</span> <span m=''4185020''>instead</span> <span m=''4185310''>of
  a</span> <span m=''4185420''>256</span> <span m=''4186800''>central</span> <span
  m=''4187100''>state</span> <span m=''4187490''>space,</span> <span m=''4187870''>we''ve</span>
  <span m=''4188069''>got</span> <span m=''4188319''>three</span> <span m=''4189569''>64</span>
  <span m=''4190170''>state</span> <span m=''4190590''>spaces.</span> <span m=''4192100''>And</span>
  <span m=''4192220''>this</span> <span m=''4192380''>is</span> <span m=''4192500''>what</span>
  <span m=''4192660''>we</span> <span m=''4192779''>saw</span> <span m=''4193010''>on</span>
  <span m=''4193109''>the</span> <span m=''4193200''>trellis</span> <span m=''4193580''>realization</span>
  <span m=''4194290''>too,</span> <span m=''4194720''>that if</span> <span m=''4194870''>we</span>
  <span m=''4196300''>sectionalize</span> <span m=''4197130''>into</span> <span m=''4197280''>three</span>
  <span m=''4197550''>sections,</span> <span m=''4198230''>then</span> <span m=''4198320''>we</span>
  <span m=''4198420''>get</span> <span m=''4198570''>a</span> <span m=''4198630''>64</span>
  <span m=''4199250''>state</span> <span m=''4199700''>and a</span> <span m=''4199970''>64</span>
  <span m=''4201050''>state</span> <span m=''4201830''>at</span> <span m=''4201990''>the</span>
  <span m=''4202050''>boundaries</span> <span m=''4202540''>between</span> <span m=''4202850''>the</span>
  <span m=''4202940''>three</span> <span m=''4203180''>sections,</span> <span m=''4204030''>but</span>
  <span m=''4204490''>we</span> <span m=''4204640''>still</span> <span m=''4204910''>got</span>
  <span m=''4205320''>the</span> <span m=''4205400''>same</span> <span m=''4205690''>512</span>
  <span m=''4206580''>branch</span> <span m=''4206910''>complexity</span> <span m=''4207490''>in</span>
  <span m=''4207580''>the</span> <span m=''4207690''>middle.</span> </p><p><span m=''4208540''>And</span>
  <span m=''4208920''>what</span> <span m=''4209090''>do</span> <span m=''4209110''>you</span>
  <span m=''4209210''>know?</span> <span m=''4209450''>We</span> <span m=''4209620''>still</span>
  <span m=''4209880''>have</span> <span m=''4210140''>a</span> <span m=''4210390''>constraint</span>
  <span m=''4210860''>code</span> <span m=''4211130''>with</span> <span m=''4211550''>complexity</span>
  <span m=''4212160''>512</span> <span m=''4213090''>here,</span> <span m=''4213370''>too.</span>
  <span m=''4214090''>So</span> <span m=''4214350''>if</span> <span m=''4214420''>you</span>
  <span m=''4214540''>consider</span> <span m=''4214950''>that</span> <span m=''4215290''>the</span>
  <span m=''4215380''>more</span> <span m=''4215600''>valid</span> <span m=''4216130''>measure</span>
  <span m=''4216630''>of</span> <span m=''4216870''>complexity,</span> <span m=''4217760''>the</span>
  <span m=''4218220''>minimum</span> <span m=''4218510''>dimension</span> <span m=''4219000''>of</span>
  <span m=''4219230''>any</span> <span m=''4219400''>constraint</span> <span m=''4220030''>code</span>
  <span m=''4220770''>or</span> <span m=''4220940''>branch</span> <span m=''4221280''>space,</span>
  <span m=''4222290''>then</span> <span m=''4222440''>we</span> <span m=''4222570''>haven''t</span>
  <span m=''4222860''>improved.</span> </p><p><span m=''4224360''>So</span> <span
  m=''4226200''>subject</span> <span m=''4226740''>to</span> <span m=''4226840''>these</span>
  <span m=''4227100''>qualifiers,</span> <span m=''4227900''>this</span> <span m=''4228080''>is</span>
  <span m=''4228130''>a</span> <span m=''4228190''>pretty</span> <span m=''4228510''>strong</span>
  <span m=''4228970''>argument</span> <span m=''4229560''>that</span> <span m=''4230240''>by</span>
  <span m=''4230380''>going</span> <span m=''4230660''>beyond</span> <span m=''4231070''>trellis</span>
  <span m=''4231450''>realizations</span> <span m=''4232240''>to</span> <span m=''4232380''>general</span>
  <span m=''4236060''>cycle-free,</span> <span m=''4237470''>graphical</span> <span
  m=''4238640''>realizations,</span> <span m=''4240990''>we</span> <span m=''4241090''>can''t</span>
  <span m=''4241490''>gain</span> <span m=''4241770''>very</span> <span m=''4241990''>much.</span>
  <span m=''4244212''>So</span> <span m=''4244640''>the</span> <span m=''4244750''>moral</span>
  <span m=''4245230''>is</span> <span m=''4248530''>to</span> <span m=''4249180''>significantly</span>
  <span m=''4250070''>reduce</span> <span m=''4250470''>complexity,</span> <span m=''4252540''>we''re
  going</span> <span m=''4252700''>to need</span> <span m=''4252910''>to</span> <span
  m=''4253050''>go</span> <span m=''4255206''>to</span> <span m=''4255630''>graphs</span>
  <span m=''4256010''>with</span> <span m=''4256140''>cycles.</span> <span m=''4264280''>We</span>
  <span m=''4264790''>must</span> <span m=''4265290''>go</span> <span m=''4266820''>to</span>
  <span m=''4266960''>graphs</span> <span m=''4267235''>with</span> <span m=''4267510''>cycles.</span>
  <span m=''4275910''>OK,</span> <span m=''4276460''>so</span> <span m=''4278170''>you</span>
  <span m=''4278300''>don''t</span> <span m=''4278460''>get</span> <span m=''4278660''>much</span>
  <span m=''4278900''>for</span> <span m=''4279020''>free</span> <span m=''4279260''>in</span>
  <span m=''4279390''>this</span> <span m=''4279650''>life.</span> <span m=''4282360''>So</span>
  <span m=''4282600''>when</span> <span m=''4282740''>we</span> <span m=''4283500''>get</span>
  <span m=''4283720''>to</span> <span m=''4283840''>our</span> <span m=''4283960''>sum-product</span>
  <span m=''4284550''>decoding</span> <span m=''4284805''>algorithm,</span> <span
  m=''4285440''>we''re</span> <span m=''4285630''>going</span> <span m=''4285810''>to</span>
  <span m=''4285980''>have</span> <span m=''4286350''>to apply</span> <span m=''4286470''>it
  to</span> <span m=''4286560''>graphs</span> <span m=''4286970''>with</span> <span
  m=''4287060''>cycles</span> <span m=''4287650''>where</span> <span m=''4287880''>it''s</span>
  <span m=''4288070''>iterative,</span> <span m=''4288650''>where</span> <span m=''4288750''>it''s</span>
  <span m=''4288940''>not</span> <span m=''4289120''>exact,</span> <span m=''4290080''>where</span>
  <span m=''4290340''>it''s</span> <span m=''4291616''>just</span> <span m=''4292090''>a</span>
  <span m=''4292150''>lot</span> <span m=''4292370''>less</span> <span m=''4292730''>nice.</span>
  </p><p><span m=''4294920''>So</span> <span m=''4295200''>what</span> <span m=''4295340''>do</span>
  <span m=''4295380''>we</span> <span m=''4295490''>do</span> <span m=''4295690''>when</span>
  <span m=''4295840''>we</span> <span m=''4295880''>go</span> <span m=''4296030''>to</span>
  <span m=''4296110''>graphs</span> <span m=''4296540''>with</span> <span m=''4296690''>cycles?</span>
  <span m=''4297210''>Where</span> <span m=''4297510''>is</span> <span m=''4297630''>the</span>
  <span m=''4297710''>potential</span> <span m=''4298260''>gain?</span> <span m=''4299470''>The</span>
  <span m=''4299660''>potential</span> <span m=''4300270''>gain</span> <span m=''4301810''>is</span>
  <span m=''4302060''>that</span> <span m=''4302180''>now</span> <span m=''4302420''>this</span>
  <span m=''4302660''>super-state</span> <span m=''4303330''>variable</span> <span
  m=''4305740''>could</span> <span m=''4305950''>be</span> <span m=''4306090''>made</span>
  <span m=''4306410''>up</span> <span m=''4306980''>of</span> <span m=''4310480''>a</span>
  <span m=''4310540''>number</span> <span m=''4310880''>of</span> <span m=''4310940''>simpler</span>
  <span m=''4311870''>variables.</span> <span m=''4312680''>We''ve</span> <span m=''4312860''>got</span>
  <span m=''4314250''>a</span> <span m=''4314300''>certain</span> <span m=''4314590''>minimum</span>
  <span m=''4314950''>dimension</span> <span m=''4315260''>that</span> <span m=''4315570''>we''re</span>
  <span m=''4315660''>going</span> <span m=''4315770''>to</span> <span m=''4315820''>need</span>
  <span m=''4316440''>any</span> <span m=''4316680''>cut-set,</span> <span m=''4317250''>like</span>
  <span m=''4319900''>8</span> <span m=''4320280''>for</span> <span m=''4320410''>the</span>
  <span m=''4320540''>central</span> <span m=''4321160''>state</span> <span m=''4321520''>space</span>
  <span m=''4321930''>of the</span> <span m=''4322265''>Golay</span> <span m=''4322600''>code.</span>
  </p><p><span m=''4323300''>But</span> <span m=''4324150''>now</span> <span m=''4324390''>we</span>
  <span m=''4324520''>can</span> <span m=''4325560''>spread it</span> <span m=''4325950''>around</span>
  <span m=''4326440''>over</span> <span m=''4326810''>two</span> <span m=''4327100''>or</span>
  <span m=''4327260''>more</span> <span m=''4329290''>sub-state</span> <span m=''4330090''>variables.</span>
  <span m=''4331630''>So</span> <span m=''4331960''>for</span> <span m=''4332170''>instance,</span>
  <span m=''4332590''>maybe</span> <span m=''4332930''>we</span> <span m=''4333090''>can</span>
  <span m=''4333260''>find</span> <span m=''4333830''>something</span> <span m=''4334340''>where</span>
  <span m=''4335180''>we</span> <span m=''4335990''>now</span> <span m=''4336260''>have</span>
  <span m=''4336390''>a</span> <span m=''4336510''>graph</span> <span m=''4336890''>with</span>
  <span m=''4337040''>cycles</span> <span m=''4338320''>where</span> <span m=''4339560''>we</span>
  <span m=''4339730''>have</span> <span m=''4339900''>two</span> <span m=''4340110''>state</span>
  <span m=''4340530''>spaces</span> <span m=''4340930''>here.</span> <span m=''4341220''>Here''s</span>
  <span m=''4341560''>the</span> <span m=''4341670''>cycle</span> <span m=''4342140''>again.</span>
  <span m=''4343740''>And</span> <span m=''4343900''>the</span> <span m=''4344000''>two</span>
  <span m=''4344190''>state</span> <span m=''4344590''>spaces</span> <span m=''4345050''>each</span>
  <span m=''4345380''>have</span> <span m=''4346190''>size</span> <span m=''4346660''>only</span>
  <span m=''4346870''>16.</span> <span m=''4348880''>That</span> <span m=''4349050''>would</span>
  <span m=''4349180''>still</span> <span m=''4349520''>satisfy</span> <span m=''4350720''>this</span>
  <span m=''4350920''>cut-set</span> <span m=''4351430''>bound.</span> <span m=''4353190''>So</span>
  <span m=''4353460''>we</span> <span m=''4353610''>greatly</span> <span m=''4354090''>reduce</span>
  <span m=''4354540''>the</span> <span m=''4357480''>size</span> <span m=''4358130''>of</span>
  <span m=''4358270''>the</span> <span m=''4358360''>state</span> <span m=''4358690''>spaces,</span>
  <span m=''4360850''>which</span> <span m=''4361100''>is</span> <span m=''4361260''>exponential</span>
  <span m=''4361610''>in</span> <span m=''4361960''>their</span> <span m=''4362110''>dimension,</span>
  <span m=''4363670''>but</span> <span m=''4364020''>at</span> <span m=''4364130''>the</span>
  <span m=''4364230''>cost</span> <span m=''4364620''>of</span> <span m=''4364730''>introducing</span>
  <span m=''4365250''>a</span> <span m=''4365310''>cycle.</span> <span m=''4365720''>I
  insist</span> <span m=''4366000''>that''s</span> <span m=''4366280''>a</span> <span
  m=''4366540''>cycle.</span> </p><p><span m=''4367560''>Let''s</span> <span m=''4367780''>go
  over</span> <span m=''4368130''>to</span> <span m=''4368250''>this</span> <span
  m=''4368510''>trellis</span> <span m=''4368960''>here.</span> <span m=''4369510''>The</span>
  <span m=''4369680''>next</span> <span m=''4369850''>thing</span> <span m=''4370930''>I</span>
  <span m=''4371020''>might</span> <span m=''4371280''>talk</span> <span m=''4371560''>about</span>
  <span m=''4372040''>is</span> <span m=''4372330''>tail-biting</span> <span m=''4373120''>trellis</span>
  <span m=''4373930''>realizations.</span> <span m=''4380100''>This</span> <span m=''4380300''>is</span>
  <span m=''4380420''>very</span> <span m=''4380830''>simple.</span> <span m=''4381370''>What''s</span>
  <span m=''4381580''>the</span> <span m=''4381780''>first</span> <span m=''4383250''>realization</span>
  <span m=''4384010''>you would</span> <span m=''4384240''>think</span> <span m=''4384610''>of</span>
  <span m=''4384840''>on</span> <span m=''4384930''>a</span> <span m=''4385010''>graph</span>
  <span m=''4385480''>with</span> <span m=''4385570''>a</span> <span m=''4385670''>cycle?</span>
  <span m=''4387490''>Well,</span> <span m=''4388990''>here''s</span> <span m=''4389230''>a</span>
  <span m=''4389310''>trellis</span> <span m=''4389750''>realization.</span> <span
  m=''4390750''>It''s</span> <span m=''4390990''>always</span> <span m=''4391180''>going</span>
  <span m=''4391270''>to</span> <span m=''4391350''>look</span> <span m=''4391550''>like</span>
  <span m=''4391890''>this.</span> <span m=''4395200''>And</span> <span m=''4395550''>then</span>
  <span m=''4395990''>let''s</span> <span m=''4396180''>just</span> <span m=''4396360''>loop</span>
  <span m=''4396690''>this</span> <span m=''4396820''>around.</span> </p><p><span
  m=''4398074''>In</span> <span m=''4398511''>other</span> <span m=''4398950''>words,</span>
  <span m=''4399080''>we</span> <span m=''4399170''>make</span> <span m=''4399810''>the</span>
  <span m=''4399880''>last</span> <span m=''4400200''>state</span> <span m=''4400490''>space</span>
  <span m=''4400960''>equal</span> <span m=''4401250''>to</span> <span m=''4401300''>the</span>
  <span m=''4401380''>first</span> <span m=''4401730''>state</span> <span m=''4402010''>space.</span>
  <span m=''4402450''>We</span> <span m=''4402570''>don''t</span> <span m=''4403240''>require</span>
  <span m=''4403670''>they</span> <span m=''4403800''>used</span> <span m=''4403970''>to</span>
  <span m=''4404140''>be</span> <span m=''4404310''>trivial</span> <span m=''4404690''>state</span>
  <span m=''4405090''>spaces</span> <span m=''4405570''>of</span> <span m=''4405680''>size</span>
  <span m=''4406260''>1.</span> <span m=''4407040''>We</span> <span m=''4407240''>allow</span>
  <span m=''4407500''>them</span> <span m=''4407680''>to</span> <span m=''4407770''>have</span>
  <span m=''4407990''>some</span> <span m=''4408340''>dimension.</span> <span m=''4409710''>And</span>
  <span m=''4410060''>here''s</span> <span m=''4411180''>a</span> <span m=''4411320''>potential</span>
  <span m=''4411960''>realization</span> <span m=''4412690''>on</span> <span m=''4412800''>a</span>
  <span m=''4412860''>graph</span> <span m=''4413230''>with</span> <span m=''4413350''>a</span>
  <span m=''4413460''>cycle.</span> </p><p><span m=''4418150''>Cut-sets.</span> <span
  m=''4419920''>Where</span> <span m=''4420220''>are the</span> <span m=''4420330''>cut-sets</span>
  <span m=''4420930''>in</span> <span m=''4420990''>this</span> <span m=''4421200''>graph?</span>
  <span m=''4424288''>Well,</span> <span m=''4424740''>the</span> <span m=''4424870''>cut-sets</span>
  <span m=''4426480''>now</span> <span m=''4426710''>look</span> <span m=''4427160''>like</span>
  <span m=''4427430''>that.</span> <span m=''4427720''>All</span> <span m=''4427890''>the</span>
  <span m=''4427970''>cut-sets</span> <span m=''4428520''>involve</span> <span m=''4428930''>at</span>
  <span m=''4429110''>least</span> <span m=''4429290''>two</span> <span m=''4429460''>edges,</span>
  <span m=''4430040''>two</span> <span m=''4430250''>state</span> <span m=''4430650''>spaces.</span>
  <span m=''4432450''>OK,</span> <span m=''4432790''>so</span> <span m=''4432970''>we</span>
  <span m=''4433090''>potentially</span> <span m=''4433640''>might</span> <span m=''4433880''>get</span>
  <span m=''4434110''>this</span> <span m=''4434320''>kind</span> <span m=''4434520''>of</span>
  <span m=''4434580''>benefit.</span> </p><p><span m=''4438330''>Here''s</span> <span
  m=''4438550''>an</span> <span m=''4438600''>example.</span> <span m=''4440850''>Suppose</span>
  <span m=''4441570''>instead,</span> <span m=''4442620''>go</span> <span m=''4442770''>back</span>
  <span m=''4443110''>to</span> <span m=''4443260''>our</span> <span m=''4444600''>very</span>
  <span m=''4444810''>favorite</span> <span m=''4445220''>example,</span> <span m=''4446660''>suppose</span>
  <span m=''4447150''>we</span> <span m=''4447290''>let</span> <span m=''4447520''>u2</span>
  <span m=''4448130''>go</span> <span m=''4448310''>across</span> <span m=''4448780''>here,</span>
  <span m=''4451960''>and</span> <span m=''4452130''>we</span> <span m=''4452250''>bring</span>
  <span m=''4452570''>out</span> <span m=''4452840''>u3</span> <span m=''4453370''>out</span>
  <span m=''4453680''>of</span> <span m=''4454010''>here,</span> <span m=''4455616''>and
  we</span> <span m=''4456060''>bring</span> <span m=''4456340''>it</span> <span m=''4456890''>all</span>
  <span m=''4457250''>the</span> <span m=''4457330''>way</span> <span m=''4457460''>back</span>
  <span m=''4457770''>to</span> <span m=''4457890''>here.</span> <span m=''4461870''>Everything</span>
  <span m=''4462210''>still</span> <span m=''4462490''>good?</span> <span m=''4464540''>It''s</span>
  <span m=''4465130''>obviously</span> <span m=''4465660''>another</span> <span m=''4465910''>realization.</span>
  <span m=''4468050''>Now</span> <span m=''4468220''>I''ve</span> <span m=''4468420''>made</span>
  <span m=''4468620''>it</span> <span m=''4468790''>clear</span> <span m=''4469200''>that</span>
  <span m=''4469440''>when</span> <span m=''4469670''>I</span> <span m=''4469760''>draw</span>
  <span m=''4470070''>u2</span> <span m=''4470480''>and</span> <span m=''4470650''>u3</span>
  <span m=''4471140''>separately</span> <span m=''4471690''>here,</span> <span m=''4471880''>I''ve</span>
  <span m=''4472020''>really</span> <span m=''4472230''>got</span> <span m=''4472370''>a</span>
  <span m=''4472500''>cycle.</span> <span m=''4474240''>I''ve</span> <span m=''4474530''>made</span>
  <span m=''4474740''>a</span> <span m=''4474790''>big</span> <span m=''4475050''>cycle.</span>
  </p><p><span m=''4478130''>And</span> <span m=''4478290''>now</span> <span m=''4480360''>what''s</span>
  <span m=''4480710''>the</span> <span m=''4481060''>number of</span> <span m=''4481350''>states</span>
  <span m=''4481850''>in</span> <span m=''4481970''>this</span> <span m=''4482320''>two-section</span>
  <span m=''4482960''>realization</span> <span m=''4483650''>of</span> <span m=''4483690''>the</span>
  <span m=''4483810''>8,</span> <span m=''4484000''>4</span> <span m=''4484400''>code?</span>
  <span m=''4486680''>This</span> <span m=''4486820''>is</span> <span m=''4486950''>a</span>
  <span m=''4487030''>two-state</span> <span m=''4487760''>tail-biting</span> <span
  m=''4488280''>trellis,</span> <span m=''4488780''>because</span> <span m=''4489090''>each</span>
  <span m=''4489320''>of</span> <span m=''4489380''>these</span> <span m=''4490060''>is</span>
  <span m=''4490200''>just a</span> <span m=''4490440''>little</span> <span m=''4490650''>binary</span>
  <span m=''4491080''>variable.</span> <span m=''4497770''>So</span> <span m=''4497960''>I</span>
  <span m=''4498080''>get</span> <span m=''4498310''>some</span> <span m=''4498520''>kind</span>
  <span m=''4498700''>of</span> <span m=''4498870''>two-state</span> <span m=''4499450''>trellis.</span>
  <span m=''4499970''>If</span> <span m=''4500050''>I</span> <span m=''4500100''>were</span>
  <span m=''4500240''>actually to</span> <span m=''4500690''>draw</span> <span m=''4501050''>out</span>
  <span m=''4501330''>the</span> <span m=''4501430''>trellis,</span> <span m=''4502580''>I
  would</span> <span m=''4502850''>have</span> <span m=''4503120''>two</span> <span
  m=''4503330''>states</span> <span m=''4503910''>at</span> <span m=''4504030''>time</span>
  <span m=''4504330''>0,</span> <span m=''4505330''>two</span> <span m=''4505560''>states</span>
  <span m=''4506180''>at</span> <span m=''4506380''>time</span> <span m=''4506700''>4,</span>
  <span m=''4508650''>some</span> <span m=''4509090''>kind</span> <span m=''4509390''>of
  --</span> <span m=''4510086''>what have</span> <span m=''4510482''>I</span> <span
  m=''4510880''>got--</span> <span m=''4511150''>6,</span> <span m=''4511450''>3.</span>
  <span m=''4511800''>So</span> <span m=''4512070''>I''ve</span> <span m=''4512110''>got</span>
  <span m=''4512300''>8</span> <span m=''4512540''>branches</span> <span m=''4513190''>that</span>
  <span m=''4513280''>go</span> <span m=''4513530''>back</span> <span m=''4513880''>and</span>
  <span m=''4514000''>forth,</span> <span m=''4514230''>a</span> <span m=''4514460''>couple</span>
  <span m=''4514740''>of</span> <span m=''4516210''>parallel</span> <span m=''4516670''>branches.</span>
  <span m=''4517250''>It''s</span> <span m=''4517830''>going</span> <span m=''4517910''>to</span>
  <span m=''4517980''>look</span> <span m=''4518180''>like</span> <span m=''4518420''>that.</span>
  </p><p><span m=''4521680''>Then</span> <span m=''4523470''>same</span> <span m=''4523820''>thing</span>
  <span m=''4524260''>out</span> <span m=''4524600''>to</span> <span m=''4524900''>time</span>
  <span m=''4526550''>8.</span> <span m=''4526940''>I don''t</span> <span m=''4527270''>have</span>
  <span m=''4527470''>a</span> <span m=''4527550''>time</span> <span m=''4527880''>8.</span>
  <span m=''4528090''>This</span> <span m=''4528510''>is</span> <span m=''4528660''>really</span>
  <span m=''4528930''>time</span> <span m=''4529210''>0</span> <span m=''4529610''>again,</span>
  <span m=''4534890''>where</span> <span m=''4535530''>I</span> <span m=''4535670''>identify</span>
  <span m=''4536590''>these</span> <span m=''4536840''>two</span> <span m=''4537000''>state</span>
  <span m=''4537410''>spaces.</span> <span m=''4537920''>This</span> <span m=''4538170''>is</span>
  <span m=''4538280''>really</span> <span m=''4539040''>the</span> <span m=''4539130''>same</span>
  <span m=''4539640''>state</span> <span m=''4540160''>as</span> <span m=''4541980''>this,</span>
  <span m=''4544520''>and</span> <span m=''4544590''>this is</span> <span m=''4544830''>the
  same</span> <span m=''4545130''>one as that.</span> </p><p><span m=''4547240''>So</span>
  <span m=''4547530''>that''s</span> <span m=''4547810''>if</span> <span m=''4547970''>I</span>
  <span m=''4548040''>really</span> <span m=''4548310''>drew</span> <span m=''4548580''>out</span>
  <span m=''4548820''>the</span> <span m=''4548920''>trellis</span> <span m=''4549520''>in
  the</span> <span m=''4549750''>style</span> <span m=''4550650''>I</span> <span m=''4550790''>originally</span>
  <span m=''4551260''>drew</span> <span m=''4551670''>trellises,</span> <span m=''4552960''>this</span>
  <span m=''4553190''>would</span> <span m=''4553480''>be</span> <span m=''4553760''>a</span>
  <span m=''4555400''>picture</span> <span m=''4555850''>of</span> <span m=''4555920''>all</span>
  <span m=''4556160''>the--</span> <span m=''4557670''>there''s</span> <span m=''4557830''>a</span>
  <span m=''4557890''>1-to-1</span> <span m=''4558380''>map</span> <span m=''4558680''>between</span>
  <span m=''4558990''>all</span> <span m=''4559180''>the paths</span> <span m=''4559680''>through</span>
  <span m=''4559870''>this</span> <span m=''4560090''>trellis</span> <span m=''4560560''>that</span>
  <span m=''4560830''>start</span> <span m=''4561190''>and</span> <span m=''4561300''>end</span>
  <span m=''4561500''>in</span> <span m=''4561590''>the</span> <span m=''4561680''>same</span>
  <span m=''4562000''>state,</span> <span m=''4563500''>because</span> <span m=''4563740''>that''s</span>
  <span m=''4563970''>what</span> <span m=''4564080''>I</span> <span m=''4564130''>mean</span>
  <span m=''4564390''>when I</span> <span m=''4564540''>identify</span> <span m=''4565320''>the</span>
  <span m=''4565440''>beginning</span> <span m=''4565810''>and end</span> <span m=''4566070''>states.</span>
  <span m=''4567340''>So</span> <span m=''4568230''>if</span> <span m=''4568430''>I</span>
  <span m=''4568500''>start</span> <span m=''4568840''>in</span> <span m=''4568920''>this</span>
  <span m=''4569050''>state,</span> <span m=''4569570''>there''s</span> <span m=''4571420''>a</span>
  <span m=''4571900''>four-way</span> <span m=''4572690''>branch</span> <span m=''4573170''>here,</span>
  <span m=''4573600''>another</span> <span m=''4573870''>four-way</span> <span m=''4574260''>branch</span>
  <span m=''4574650''>there.</span> </p><p><span m=''4577510''>Is</span> <span m=''4577660''>that</span>
  <span m=''4577870''>right?</span> <span m=''4579370''>No,</span> <span m=''4579620''>there''s</span>
  <span m=''4580030''>only</span> <span m=''4580330''>a</span> <span m=''4580410''>two-way</span>
  <span m=''4580760''>branch</span> <span m=''4581190''>such</span> <span m=''4581390''>that</span>
  <span m=''4581560''>I can</span> <span m=''4581640''>get</span> <span m=''4581820''>back</span>
  <span m=''4582040''>to the</span> <span m=''4582160''>initial</span> <span m=''4582470''>state.</span>
  <span m=''4582745''>So</span> <span m=''4583020''>there are</span> <span m=''4584030''>8</span>
  <span m=''4584340''>possible</span> <span m=''4584850''>paths</span> <span m=''4585410''>that</span>
  <span m=''4585630''>start</span> <span m=''4585920''>here</span> <span m=''4586210''>and</span>
  <span m=''4586330''>get</span> <span m=''4586530''>back</span> <span m=''4586870''>to</span>
  <span m=''4586980''>the</span> <span m=''4587100''>same</span> <span m=''4587420''>state,</span>
  <span m=''4588240''>8</span> <span m=''4588370''>possible</span> <span m=''4588900''>paths</span>
  <span m=''4589290''>that</span> <span m=''4589370''>start</span> <span m=''4589630''>out
  from</span> <span m=''4589930''>here</span> <span m=''4590120''>and</span> <span
  m=''4590260''>get</span> <span m=''4590440''>back</span> <span m=''4590690''>to</span>
  <span m=''4590810''>the</span> <span m=''4590880''>same</span> <span m=''4591160''>state.</span>
  <span m=''4592030''>And</span> <span m=''4592260''>they</span> <span m=''4593850''>together</span>
  <span m=''4594770''>correspond</span> <span m=''4595270''>1-to-1</span> <span m=''4595510''>to</span>
  <span m=''4595730''>all the</span> <span m=''4597150''>code words.</span> </p><p><span
  m=''4599820''>OK,</span> <span m=''4600130''>well,</span> <span m=''4601240''>that''s</span>
  <span m=''4601510''>not</span> <span m=''4601650''>a</span> <span m=''4601670''>very</span>
  <span m=''4601890''>big</span> <span m=''4602140''>deal.</span> <span m=''4602430''>I</span>
  <span m=''4602750''>was</span> <span m=''4602960''>able</span> <span m=''4603150''>to</span>
  <span m=''4603190''>reduce</span> <span m=''4603610''>a</span> <span m=''4603670''>four-state</span>
  <span m=''4604230''>trellis</span> <span m=''4604730''>to</span> <span m=''4604850''>a</span>
  <span m=''4604960''>two-state</span> <span m=''4605520''>trellis.</span> <span m=''4608990''>But</span>
  <span m=''4609280''>suppose</span> <span m=''4609610''>I</span> <span m=''4609700''>do</span>
  <span m=''4609880''>the</span> <span m=''4609950''>same</span> <span m=''4610210''>thing</span>
  <span m=''4610480''>with</span> <span m=''4610670''>the</span> <span m=''4612820''>Golay</span>
  <span m=''4613240''>code.</span> <span m=''4614145''>In the</span> <span m=''4614510''>Golay</span>
  <span m=''4614860''>code,</span> <span m=''4615220''>there''s</span> <span m=''4615800''>a</span>
  <span m=''4615880''>very</span> <span m=''4616150''>beautiful</span> <span m=''4617560''>tail-biting</span>
  <span m=''4618080''>trellis</span> <span m=''4618990''>realization.</span> <span
  m=''4622410''>It</span> <span m=''4622550''>looks</span> <span m=''4622770''>like</span>
  <span m=''4623340''>this.</span> <span m=''4623710''>It</span> <span m=''4623780''>has</span>
  <span m=''4624050''>12</span> <span m=''4624520''>sections,</span> <span m=''4625805''>so</span>
  <span m=''4626290''>maybe I</span> <span m=''4626775''>won''t</span> <span m=''4627260''>draw</span>
  <span m=''4627330''>all</span> <span m=''4627510''>the</span> <span m=''4627680''>sections.</span>
  <span m=''4629440''>It</span> <span m=''4629930''>groups</span> <span m=''4631050''>each</span>
  <span m=''4631410''>of</span> <span m=''4631560''>the</span> <span m=''4631710''>output</span>
  <span m=''4632130''>variables</span> <span m=''4632770''>into</span> <span m=''4633370''>pairs</span>
  <span m=''4638260''>and</span> <span m=''4638850''>comes</span> <span m=''4639110''>around</span>
  <span m=''4639410''>like</span> <span m=''4639660''>that.</span> <span m=''4640710''>And</span>
  <span m=''4641500''>each</span> <span m=''4641760''>of</span> <span m=''4641830''>these</span>
  <span m=''4642050''>state</span> <span m=''4642510''>spaces</span> <span m=''4643030''>has</span>
  <span m=''4643300''>dimension</span> <span m=''4643810''>4,</span> <span m=''4644360''>or</span>
  <span m=''4644520''>size</span> <span m=''4645040''>16.</span> <span m=''4646860''>And</span>
  <span m=''4647020''>I</span> <span m=''4647080''>give</span> <span m=''4647310''>the</span>
  <span m=''4647430''>generator</span> <span m=''4647960''>matrix</span> <span m=''4648490''>for</span>
  <span m=''4648590''>this</span> <span m=''4649080''>in the</span> <span m=''4649570''>notes.</span>
  </p><p><span m=''4650860''>So</span> <span m=''4651210''>this</span> <span m=''4651460''>is</span>
  <span m=''4652640''>for the</span> <span m=''4652970''>24,</span> <span m=''4656650''>12,</span>
  <span m=''4657350''>8</span> <span m=''4657920''>code,</span> <span m=''4659970''>and</span>
  <span m=''4660100''>now</span> <span m=''4660220''>you</span> <span m=''4660400''>test</span>
  <span m=''4660810''>me.</span> <span m=''4662350''>Is</span> <span m=''4662500''>this</span>
  <span m=''4662710''>a</span> <span m=''4662790''>possible--</span> <span m=''4666800''>use</span>
  <span m=''4667070''>the</span> <span m=''4667150''>cut-set</span> <span m=''4667660''>bound.</span>
  <span m=''4668090''>See if</span> <span m=''4668250''>this</span> <span m=''4668430''>violates</span>
  <span m=''4668960''>the</span> <span m=''4669340''>cut-set</span> <span m=''4669430''>bound</span>
  <span m=''4669750''>anywhere.</span> <span m=''4670130''>Does</span> <span m=''4670580''>it</span>
  <span m=''4671300''>for</span> <span m=''4671660''>this</span> <span m=''4671990''>code?</span>
  <span m=''4675416''>No,</span> <span m=''4675880''>it</span> <span m=''4676230''>doesn''t.</span>
  <span m=''4676620''>Because</span> <span m=''4676920''>every</span> <span m=''4677930''>cut-set,</span>
  <span m=''4678350''>no matter</span> <span m=''4678460''>how</span> <span m=''4678570''>I</span>
  <span m=''4678710''>draw</span> <span m=''4679180''>it,</span> <span m=''4680150''>we''re</span>
  <span m=''4680310''>going</span> <span m=''4680430''>to</span> <span m=''4680550''>get</span>
  <span m=''4681340''>two</span> <span m=''4681610''>edges,</span> <span m=''4682150''>each</span>
  <span m=''4682390''>with</span> <span m=''4682470''>dimension</span> <span m=''4682930''>4,</span>
  <span m=''4683360''>adding</span> <span m=''4683660''>up</span> <span m=''4683800''>to</span>
  <span m=''4683950''>a</span> <span m=''4684010''>super-state</span> <span m=''4684840''>of</span>
  <span m=''4684950''>dimension</span> <span m=''4685490''>8.</span> <span m=''4686580''>And</span>
  <span m=''4688720''>the</span> <span m=''4689010''>state</span> <span m=''4689460''>spaces</span>
  <span m=''4690010''>at</span> <span m=''4690160''>all</span> <span m=''4690390''>the</span>
  <span m=''4690600''>even</span> <span m=''4690890''>times,</span> <span m=''4691440''>notice</span>
  <span m=''4691860''>I''ve</span> <span m=''4692430''>sectionalized</span> <span
  m=''4693300''>here,</span> <span m=''4693510''>so</span> <span m=''4693670''>I</span>
  <span m=''4693900''>only need</span> <span m=''4694260''>to</span> <span m=''4694350''>look</span>
  <span m=''4694540''>at</span> <span m=''4694590''>even</span> <span m=''4694940''>times.</span>
  <span m=''4695900''>The</span> <span m=''4695980''>state</span> <span m=''4696380''>spaces</span>
  <span m=''4696880''>at</span> <span m=''4696960''>all</span> <span m=''4697170''>even</span>
  <span m=''4697420''>times</span> <span m=''4697710''>in</span> <span m=''4697820''>this</span>
  <span m=''4698040''>code</span> <span m=''4699260''>could</span> <span m=''4700260''>have</span>
  <span m=''4700420''>dimensions</span> <span m=''4700850''>as</span> <span m=''4700920''>small</span>
  <span m=''4701420''>as</span> <span m=''4701730''>8.</span> <span m=''4704430''>Remember,</span>
  <span m=''4704690''>at</span> <span m=''4705060''>the odd</span> <span m=''4705350''>times,</span>
  <span m=''4705770''>they</span> <span m=''4705820''>go</span> <span m=''4705980''>up</span>
  <span m=''4706130''>to</span> <span m=''4706260''>9.</span> </p><p><span m=''4707760''>And</span>
  <span m=''4707890''>these</span> <span m=''4708180''>are</span> <span m=''4708300''>all</span>
  <span m=''4709470''>little--</span> <span m=''4710090''>4,</span> <span m=''4710390''>4--</span>
  <span m=''4710870''>these are</span> <span m=''4711230''>all</span> <span m=''4711460''>little</span>
  <span m=''4711780''>10,</span> <span m=''4712270''>5</span> <span m=''4712700''>codes.</span>
  <span m=''4713830''>So</span> <span m=''4714450''>the</span> <span m=''4714590''>branch</span>
  <span m=''4714980''>complexity</span> <span m=''4715590''>is</span> <span m=''4715740''>only</span>
  <span m=''4715970''>32.</span> <span m=''4717612''>So</span> <span m=''4718000''>this</span>
  <span m=''4718270''>is</span> <span m=''4718490''>very</span> <span m=''4718730''>much</span>
  <span m=''4718980''>simpler</span> <span m=''4719370''>than</span> <span m=''4719570''>any</span>
  <span m=''4719770''>of</span> <span m=''4719840''>the</span> <span m=''4719910''>conventional</span>
  <span m=''4720520''>trellises</span> <span m=''4720960''>that I''ve--</span> <span
  m=''4722370''>than</span> <span m=''4722510''>the</span> <span m=''4722590''>minimal</span>
  <span m=''4722960''>conventional</span> <span m=''4723500''>trellis</span> <span
  m=''4723990''>that we</span> <span m=''4724140''>were</span> <span m=''4724270''>able</span>
  <span m=''4724420''>to</span> <span m=''4724480''>draw</span> <span m=''4724740''>for</span>
  <span m=''4724920''>this</span> <span m=''4725180''>code.</span> <span m=''4726210''>Or</span>
  <span m=''4726535''>if</span> <span m=''4726860''>this</span> <span m=''4727160''>funny</span>
  <span m=''4727430''>little</span> <span m=''4728060''>pinwheel</span> <span m=''4728580''>with</span>
  <span m=''4728740''>three</span> <span m=''4728990''>arms</span> <span m=''4729350''>on</span>
  <span m=''4729490''>it,</span> <span m=''4729720''>which</span> <span m=''4729930''>is</span>
  <span m=''4730080''>also</span> <span m=''4730500''>a</span> <span m=''4730660''>cycle-free</span>
  <span m=''4731260''>realization,</span> <span m=''4731665''>this</span> <span m=''4732070''>code.</span>
  </p><p><span m=''4733540''>OK,</span> <span m=''4734030''>so</span> <span m=''4734750''>they''re</span>
  <span m=''4734860''>going</span> <span m=''4734990''>to</span> <span m=''4735120''>tail-biting.</span>
  <span m=''4736760''>That''s</span> <span m=''4736990''>a</span> <span m=''4737050''>significant</span>
  <span m=''4738990''>advance.</span> <span m=''4741080''>An</span> <span m=''4741260''>aside</span>
  <span m=''4742020''>note--</span> <span m=''4743500''>if</span> <span m=''4743790''>we</span>
  <span m=''4745310''>just</span> <span m=''4745570''>break</span> <span m=''4745900''>this,</span>
  <span m=''4747232''>it</span> <span m=''4747640''>turns</span> <span m=''4748010''>out</span>
  <span m=''4749510''>we</span> <span m=''4749820''>have</span> <span m=''4750240''>a</span>
  <span m=''4750600''>generator</span> <span m=''4751040''>matrix</span> <span m=''4751540''>that
  has</span> <span m=''4751790''>period</span> <span m=''4752210''>4,</span> <span
  m=''4753670''>and</span> <span m=''4753800''>let</span> <span m=''4754000''>this</span>
  <span m=''4754210''>go</span> <span m=''4754370''>on</span> <span m=''4755820''>infinitely,</span>
  <span m=''4756990''>this</span> <span m=''4757220''>is</span> <span m=''4757480''>a</span>
  <span m=''4758580''>realization</span> <span m=''4762530''>of</span> <span m=''4763350''>a</span>
  <span m=''4764030''>rate</span> <span m=''4764450''>1/2,</span> <span m=''4767570''>16</span>
  <span m=''4768340''>state,</span> <span m=''4770860''>branch</span> <span m=''4771310''>complexity</span>
  <span m=''4772120''>32,</span> <span m=''4773820''>as</span> <span m=''4774050''>we</span>
  <span m=''4774190''>expect--</span> <span m=''4774810''>perfectly</span> <span m=''4775780''>conventional,</span>
  <span m=''4776520''>except</span> <span m=''4776950''>it''s</span> <span m=''4777160''>periodically</span>
  <span m=''4777940''>time</span> <span m=''4778310''>varying--</span> <span m=''4785390''>linear</span>
  <span m=''4785960''>convolutional</span> <span m=''4786810''>code</span> <span m=''4789440''>with</span>
  <span m=''4790350''>absolutely</span> <span m=''4790750''>phenomenal</span> <span
  m=''4791310''>performance.</span> <span m=''4793470''>Like</span> <span m=''4793690''>the</span>
  <span m=''4793790''>Golay</span> <span m=''4794260''>code,</span> <span m=''4794710''>it</span>
  <span m=''4794840''>has</span> <span m=''4795720''>d</span> <span m=''4795820''>equals</span>
  <span m=''4796320''>8.</span> <span m=''4797760''>Therefore</span> <span m=''4798320''>it</span>
  <span m=''4798370''>has</span> <span m=''4798870''>a</span> <span m=''4800520''>nominal</span>
  <span m=''4800910''>coding</span> <span m=''4801240''>gain</span> <span m=''4801580''>of</span>
  <span m=''4802370''>4,</span> <span m=''4803210''>1/2</span> <span m=''4803620''>times</span>
  <span m=''4804010''>8,</span> <span m=''4805270''>or</span> <span m=''4805360''>6
  dB.</span> </p><p><span m=''4805890''>This</span> <span m=''4806380''>is</span>
  <span m=''4806500''>with</span> <span m=''4806765''>only a</span> <span m=''4807030''>16</span>
  <span m=''4807560''>state,</span> <span m=''4807860''>rate</span> <span m=''4808040''>1/2</span>
  <span m=''4808490''>code.</span> <span m=''4808860''>Look</span> <span m=''4809000''>at</span>
  <span m=''4809140''>the</span> <span m=''4809750''>ones</span> <span m=''4810050''>on</span>
  <span m=''4810110''>the</span> <span m=''4810210''>table.</span> <span m=''4810600''>This</span>
  <span m=''4810830''>is</span> <span m=''4811330''>significantly</span> <span m=''4811970''>better</span>
  <span m=''4812280''>than</span> <span m=''4812410''>that.</span> <span m=''4813910''>And</span>
  <span m=''4814380''>it''s</span> <span m=''4814710''>effective</span> <span m=''4815250''>coding</span>
  <span m=''4815580''>gain,</span> <span m=''4817380''>I</span> <span m=''4817500''>forget.</span>
  <span m=''4817930''>But</span> <span m=''4818060''>it''s</span> <span m=''4818220''>still</span>
  <span m=''4818510''>very</span> <span m=''4818780''>good,</span> <span m=''4820090''>excellent,</span>
  <span m=''4821760''>for</span> <span m=''4821980''>the</span> <span m=''4822100''>complexity</span>
  <span m=''4822720''>of</span> <span m=''4822820''>this</span> <span m=''4823060''>code.</span>
  <span m=''4824370''>So</span> <span m=''4824710''>this</span> <span m=''4825020''>is</span>
  <span m=''4826200''>called</span> <span m=''4826580''>the</span> <span m=''4826820''>Golay</span>
  <span m=''4827270''>convolutional</span> <span m=''4828140''>code.</span> <span
  m=''4836710''>And</span> <span m=''4838210''>it''s</span> <span m=''4838535''>an</span>
  <span m=''4839450''>interesting</span> <span m=''4840260''>example</span> <span
  m=''4840790''>of</span> <span m=''4840880''>the</span> <span m=''4840990''>interplay</span>
  <span m=''4841510''>between</span> <span m=''4841950''>this</span> <span m=''4842590''>block</span>
  <span m=''4842930''>coding</span> <span m=''4843270''>stuff</span> <span m=''4843530''>and
  the</span> <span m=''4843790''>convolutional</span> <span m=''4844360''>coding</span>
  <span m=''4844770''>stuff,</span> <span m=''4845180''>in</span> <span m=''4845260''>this</span>
  <span m=''4845500''>case.</span> </p><p><span m=''4847060''>Actually</span> <span
  m=''4847430''>this</span> <span m=''4847640''>code</span> <span m=''4847880''>was</span>
  <span m=''4848060''>first</span> <span m=''4848330''>discovered</span> <span m=''4848605''>in</span>
  <span m=''4848880''>computer</span> <span m=''4849320''>searches,</span> <span m=''4849870''>but</span>
  <span m=''4850050''>nobody</span> <span m=''4850690''>realized</span> <span m=''4851170''>how</span>
  <span m=''4851280''>wonderful</span> <span m=''4851720''>it</span> <span m=''4851770''>was.</span>
  <span m=''4852710''>And</span> <span m=''4852940''>it</span> <span m=''4853000''>was</span>
  <span m=''4853150''>only</span> <span m=''4853390''>when</span> <span m=''4853560''>its</span>
  <span m=''4853750''>connection</span> <span m=''4854230''>with</span> <span m=''4854510''>this</span>
  <span m=''4854990''>Golay</span> <span m=''4855170''>code</span> <span m=''4855700''>was</span>
  <span m=''4855900''>recognized</span> <span m=''4856750''>that</span> <span m=''4857650''>people</span>
  <span m=''4858250''>realized</span> <span m=''4858700''>this</span> <span m=''4858850''>was</span>
  <span m=''4858990''>really</span> <span m=''4859260''>a</span> <span m=''4859330''>special</span>
  <span m=''4859980''>code,</span> <span m=''4860310''>both</span> <span m=''4862490''>from</span>
  <span m=''4862660''>a</span> <span m=''4862700''>performance</span> <span m=''4863240''>versus</span>
  <span m=''4863530''>complexity</span> <span m=''4864130''>point</span> <span m=''4864400''>of</span>
  <span m=''4864460''>view,</span> <span m=''4864680''>and</span> <span m=''4864780''>also</span>
  <span m=''4865070''>algebraically.</span> </p><p><span m=''4867550''>OK,</span>
  <span m=''4867970''>well</span> <span m=''4868340''>that</span> <span m=''4868910''>brings</span>
  <span m=''4869250''>us</span> <span m=''4869450''>to</span> <span m=''4869500''>the</span>
  <span m=''4869670''>end.</span> <span m=''4869840''>There''s</span> <span m=''4870750''>actually</span>
  <span m=''4871130''>one</span> <span m=''4871400''>more</span> <span m=''4871640''>style</span>
  <span m=''4872240''>of</span> <span m=''4873010''>graph</span> <span m=''4873290''>realization</span>
  <span m=''4873645''>that</span> <span m=''4874000''>I</span> <span m=''4874070''>want</span>
  <span m=''4874280''>to</span> <span m=''4874320''>mention</span> <span m=''4874730''>to</span>
  <span m=''4874850''>you,</span> <span m=''4876380''>for</span> <span m=''4876550''>the</span>
  <span m=''4876650''>Reed-Muller</span> <span m=''4877285''>codes.</span> <span m=''4877700''>We</span>
  <span m=''4877830''>know</span> <span m=''4878290''>that</span> <span m=''4878610''>they''re</span>
  <span m=''4878870''>basically</span> <span m=''4879360''>based</span> <span m=''4879760''>on</span>
  <span m=''4879860''>Hadamard</span> <span m=''4880340''>transforms.</span> <span
  m=''4881210''>It''s</span> <span m=''4881380''>a</span> <span m=''4881430''>very</span>
  <span m=''4881710''>nice</span> <span m=''4882890''>kind</span> <span m=''4883180''>of</span>
  <span m=''4884050''>Fourier</span> <span m=''4884510''>transform</span> <span m=''4885120''>like</span>
  <span m=''4885410''>graph</span> <span m=''4885760''>realization</span> <span m=''4886450''>of</span>
  <span m=''4886530''>Hadamard</span> <span m=''4886970''>transforms.</span> <span
  m=''4888180''>So</span> <span m=''4888510''>that</span> <span m=''4888700''>gives</span>
  <span m=''4888910''>us</span> <span m=''4889070''>another</span> <span m=''4889430''>style</span>
  <span m=''4889970''>of</span> <span m=''4890090''>realization</span> <span m=''4890750''>of</span>
  <span m=''4890840''>Reed-Muller</span> <span m=''4891360''>codes</span> <span m=''4891920''>that</span>
  <span m=''4892790''>again,</span> <span m=''4893090''>we</span> <span m=''4893230''>can</span>
  <span m=''4893390''>aggregate</span> <span m=''4894060''>to</span> <span m=''4894190''>lead</span>
  <span m=''4894530''>to</span> <span m=''4894710''>a</span> <span m=''4894880''>lot</span>
  <span m=''4895090''>of</span> <span m=''4895210''>nice</span> <span m=''4897350''>structures.</span>
  <span m=''4899000''>Again,</span> <span m=''4899270''>at</span> <span m=''4899380''>the</span>
  <span m=''4899530''>end</span> <span m=''4899680''>of</span> <span m=''4899770''>the</span>
  <span m=''4899860''>day,</span> <span m=''4903170''>unless</span> <span m=''4903730''>we</span>
  <span m=''4904160''>allow</span> <span m=''4904480''>cycles,</span> <span m=''4905050''>we</span>
  <span m=''4905160''>don''t</span> <span m=''4905330''>really</span> <span m=''4905970''>gain</span>
  <span m=''4906180''>anything.</span> </p><p><span m=''4907090''>So</span> <span
  m=''4907240''>I''ll</span> <span m=''4907370''>do</span> <span m=''4907520''>that</span>
  <span m=''4908220''>the</span> <span m=''4908710''>first</span> <span m=''4908980''>part</span>
  <span m=''4909110''>of</span> <span m=''4909240''>next</span> <span m=''4909530''>time</span>
  <span m=''4910460''>and</span> <span m=''4910800''>then</span> <span m=''4910990''>do</span>
  <span m=''4911140''>the</span> <span m=''4911260''>sum-product</span> <span m=''4911940''>algorithm.</span>
  <span m=''4912846''>I</span> <span m=''4913290''>hope</span> <span m=''4913550''>I</span>
  <span m=''4913610''>can</span> <span m=''4913790''>do</span> <span m=''4913970''>it</span>
  <span m=''4914810''>in</span> <span m=''4914910''>one</span> <span m=''4915080''>lecture.</span>
  </p>'
type: course
uid: eed1563e794f269c592125c3bcd253ce

---
None