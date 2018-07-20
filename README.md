Fun:
    Command Piping (Max 4)  : Run multiple image commands through a single command.
      Operator              : ";"
      Example               : .magik <image> ; waaw ; sharpen 10 ; explode

    1. Apply Magik to Image : .magik <image> <image(s)>*
    2. Apply Magik to GIF   : .gmagik <gif> or <image>
    3. React                : .react <message_id>* <text/emoji(s)>
    4. Bad Meme (Imgur)     : .badmeme
    5. Random 4chan post    : .chan <board>*
    6. Text Wall            : .textwall/twall <text>
    7. Aesthetics           : .aesthetics <text>
    8. ASCII                : .ascii <text>
    9. Image to ASCII       : .iascii <image>
    10. GIF to ASCII        : .gascii <gif> <liquid_rescale>*
    11. RIP Generator       : .rip <text> <text2>*
    12. Urban Dictionary    : .urban <word>
    13. Triggered GIF       : .triggered <image>
      1. Triggered Image    : .triggered2 <image>
      2. Triggered2 Image   : .triggered3 <image>
    14. Resize Image        : .resize <1-8/size> <image>
    -- You can split top and bottom text using a | divider.
    15. Meme                : .meme <image> <top_text> <bottom_text>
    16. Reverse Text        : .reverse/r <text>
    17. Identify Image/Gif  : .identify <url>
    18. Merge Images        : .merge <images (>= 2)>
    -- <text> argument IS required.
    19. Turn Text into      : .emojify/efy <background (default: 😂)> <foreground (default: 🅱)> <text>
        Emojis
        1. Vertical Emoji   : .emojify vertical/v ^^^ *same args* ^^^
           Arrangement
    20. Tone of Text        : .tone/toe <text>
    21. Huge Discord Emoji/ : .e/emoji <:emoji(s):> (if > 1, emojis merge) <ios/emojione>* (type of emoji) <size|10-2048>*
        Twitch/Frankerz
    22. Steam Emoji         : .se/steamemoji <:steam_emoji:>
    23. Add eyes to a face  : .eyes <image-face>
      -- Alias for the eye name is also the command number (e.g. ".eyes 1" instead of ".eyes spongebob").
      1. Spongebob          : .eyes spongebob <image-face>
      2. Big Eye            : .eyes big <image-face>
      3. Small Eye          : .eyes small <image-face>
      4. Money              : .eyes money <image-face>
      5. Bloodshot          : .eyes blood <image-face>
      6. Horror             : .eyes horror <image-face>
      7. Illuminati         : .eyes illuminati/triangle <image-face>
      8. Googly             : .eyes googly <image-face>
      9. Flipped            : .eyes flip/reverse <image-face>
      10. Center            : .eyes center <image-face>
      11. Red Flare         : .eyes red <image-face>
      12. Blue Flare        : .eyes blue <image-face>
      13. Green Flare       : .eyes green <image-face>
      14. Yellow Flare      : .eyes yellow <image-face>
      15. Pink Flare        : .eyes pink <image-face>
      16. White Flare       : .eyes white <image-face>
      17. Black Flare       : .eyes black <image-face>
      18. Fidget Spinner    : .eyes spinner <image-face>
    24. Word Cloud          : .wordcloud/wc <max_messages>* <image (custom mask)>*
    -- Rewrite WIP
    -- 26. Text 2 Speach       : .tts <text>
    --   1. Custom Voice       : .tts custom <voice> <text>
    --   2. List Voices        : .tts list
    25. Watermark           : .watermark <image> <watermark_image>*
    -- Aliases can be accesed by removing "say".
    26. Cow                 : .cowsay <text>
      1. Mech               : .mechsay <text>
      2. Pony               : .ponysay <text>
      3. Dino               : .dinosay <text>
      4. Sheep              : .sheepsay <text>
      5. Flaming Sheep      : .flamingsheepsay <text>
      6. Apt                : .aptsay <text>
      7. Moofasa            : .moofasasay <text>
      8. Sodomized Sheep    : .sodomizedsheepsay <text>
      9. Bong               : .bongsay <text>
      10. Beavis            : .beavissay <text>
      11. Tux               : .tuxsay <text>
      12. Duck              : .ducksay <text>
      13. Elephant          : .elephantsay <text>
      14. Eyes              : .eyessay <text>
      15. Milk              : .milksay <text>
      16. Moose             : .moosesay <text>
      17. Mutilated Cow     : .mutilatedsay <text>
      18. Chicken           : .cocksay <text>
      19. Head in Ass       : .headinass <text>
      20. Cheese            : .cheesesay <text>
      21. Gopher (Go)       : .gophersay <text>
    27. Giphy Gif           : .gif <text/query>*
    28. Imgur Image/Gallery : .imgur <text/query>*
    29. Glitch an Image     : .glitch <gif> or <image> <amount>* <seed>* <iterations>*
      1. Glitch 2           : .glitch2 <image>
    30. Pixelsort an Image  : .sort <image> <interval_function (random, threshold, edges, waves, none)>* <pixel_angle>*
    31. NeedsMoreJpeg       : .jpeg/magik2 <image> <quality|1-10>*
    32. Pixelate            : .pixel <image> <pixels>*
    33. Retro               : .retro <text (split each line by '|')>
    34. Retro 2             : .retro2 <text (split each line by '|')>
    35. Retro 3             : .retro3 <text (split each line by '|')>
    36. WaaW                : .waaw <image>
    37. HaaH                : .haah <image>
    38. WooW                : .woow <image>
    39. HooH                : .hooh <image>
    40. Flip                : .flip <image>
    41. Flop                : .flop <image>
    42. Regional Emote Text : .regional <text>
    43. WebMD               : .webmd <question>*
    44. Wasted              : .wasted <image>
    45. 4Chan Green Text    : .green <text>
    46. Rainbow             : .rainbow <image>
    47. Waves               : .wave <image>
    48. Wall                : .wall <image>
    49. Rotate              : .rotate <degree> <image>
    50. Layer               : .layer <image>
    51. Multiply            : .multiply/multi <image>
    52. Multiply and Rotate : .multiply2/multi2 <image>
    53. Dice                : .dice <image>
    54. Shake               : .shake <image>
    55. Spin                : .spin <image>
    56. Scramble            : .scramble <image>
    57. Scramble 2          : .scramble2 <image>
        (No Rotation)
    58. Who Did This        : .whodidthis/wdt <image>
    59. Agar Text           : .agar <text>
    60. Agarify Text        : .agarify <text>
    -- Do ".illegal <text> are" to replace "IS" with "ARE" in the GIF.
    61. Trump Illegal GIF   : .illegal <text>
    62. Trump Legal GIF     : .legal <text>
    63. Oilpainting         : .oil <image>
    64. XD                  : .xd <text>
    65. Trace               : .trace <image>
    66. Swirl               : .swirl <image>
    67. Side To Side        : .ss/s2s <image>
    68. Up To Down          : .utd/u2d <image>
    69. Recolor             : .recolor <image>
    -- Poorly trained Neural Network Model (Nothing really NSFW).
    70. Edges2Porn (NSFW)   : .edges2porn/e2p <image>
      1. Gif                : .gedges2porn/ge2p <gif>
    71. Sharpen             : .sharpen <image>
    72. Rewind GIF          : .rewind <gif>
    73. Gay Flag Overlay    : .gay <image>
    74. Rewind GIF Loop     : .gloop <gif>
    75. Blur                : .blur <image> <scale>*
    76. Pixelate GIF        : .gpixel <gif>
    77. JPEG GIF            : .gjpeg <gif>
    78. Glitch GIF          : .gg/glitchgif <image>
    -- FaceApp Commands (for human faces).
    79. Smile               : .smile <image-face>
    80. Smile 2             : .smile2 <image-face>
    81. Old                 : .old <image-face>
    82. Young               : .young <image-face>
    83. Female              : .female <image-face>
    84. Female 2            : .female2 <image-face>
    85. Male                : .male <image-face>
    86. Hot                 : .hot <image-face>
    87. Wave / Hot 2        : .hot2 <image-face>
    88. Beard / Pan         : .beard/pan <image-face>
    89. Hitman              : .hitman/hit <image-face>
    90. Heisenberg          : .heisenberg/walter/ww <image-face>
        (Breaking Bad)
    91. Glasses             : .glasses <image-face>
    92. Hipster             : .hipster/hip <image-face>
    93. Impression          : .impression/imp <image-face>
    94. Makeup              : .makeup <image-face>
    95. Hollywood           : .hollywood/hw <image-face>
    96. Mustache            : .mustache/must/stache <image-face>
    97. Bangs               : .bangs <image-face>
    98. Goatee              : .goatee/goat <image-face>
    99. Sun Glasses         : .sunglasses/sung <image-face>
    100. Tight Smile        : .tightsmile/tight <image-face>
    101. Full Beard         : .fullbeard/fullb <image-face>
    102. Implode            : .implode <image> <scale>*
    103. Explode            : .explode <image> <scale>*
    104. Circular/Radial    : .circle/radial <image> <angle>*
         Blur
    105. Fisheye Lens       : .fish/bulge <image>
    106. Deep Fry           : .deepfry/df <image>
    107. Brazzers Logo      : .brazzers/br <image>
    108. oWo                : .owo <image>
    109. Noose Guy          : .nooseguy <image>
    110. Composite Images   : .composite <images (limit 20)>
    111. Disabled           : .disabled <image>
    112. Kekistan           : .kekistan/kekflag <image>
    113. Watchmojo          : .watchmojo/mojo <image> <text>
    114. Snapchat Dog       : .snapchat/sc <image-face>
      1. Dog 2              : .snapchat dog2/d2 <image-face>
      2. Cat                : .snapchat cat/c <image-face>
      3. Cat 2              : .snapchat cat2/c2 <image-face>
      4. Devil              : .snapchat devil/d <image-face>
      5. Bunny              : .snapchat bunny/b <image-face>
      6. Heart              : .snapchat heart/h <image-face>
      7. Flowers            : .snapchat flowers/f <image-face>
      8. Flowers 2          : .snapchat flowers2/f2 <image-face>
      9. Glasses            : .snapchat glasses/g <image-face>
      10. Moustache         : .snapchat moustache/m <image-face>
      11. Angery            : .snapchat angery/a <image-face>
      12. Sunglasses        : .snapchat sunglasses/sg <image-face>
    115. iDubbbz Painting   : .paint <image>
    --Use negative speeds to make it slower.
    116. GIF Speed          : .gspeed <speed>
    117. Bob Ross           : .bobross/paint2 <image>
    118. Stepped on Shit    : .shit <image>
    119. Perfection         : .perfection <image>
    120. Worse Than Hitler  : .wth <image>
    121. For REALLY big     : .mistake <image>
         mistakes
    122. Reminder           : .reminder <image> <text>
    123. Zuckerbergs        : .zuckerberg/zuck <image>
         approval
    124. Ugly               : .ugly <image>
    125. Cool Guy           : .coolguy/cg <image>
    126. God                : .god <image>
    127. Gaben              : .gaben <image>
    128. Autism Hat         : .autism <image-face>
    129. Snapple Fact       : .fact <text>
    130. DLSR Image         : .dslr <image>
         Enchancement
    131. Ed Ed and Eddy     : .dork <image>
    132. Squidward Nose     : .art/squidward <image-face>
    133. p90.zone           : .p90 <tags>*
    134. 9GAG Watermark     : .9gag <image>
    135. Adidas             : .adidas <image>
    136. Admin Walk         : .adminwalk/adw <image>
    137. America            : .america <image>
    138. Autism Level       : .autismlevel/alevel <image>
    139. Bandicam           : .bandicam/bandi <image>
    140. Condom Fails       : .condomfail/condom <image>
    141. Depression         : .depression/depr <image>
    142. Hacker             : .hacker <text>
    143. Gold Star          : .goldstar/star <image>
    144. Hyper Cam          : .hypercam/hcam <image>
    145. Challange          : .jackoff/challenge <image>
    146. Keemstar           : .keemstar/keem <image>
    147. Rope Portal        : .portal <image>
    148. PornHub Caption    : .phcaption/phc <image> <text>
    149. Respects           : .respects <image>
    150. Russia             : .russia <image>
    151. Spain              : .spain <image>
    152. Stockphoto         : .stock <image>
         Watermark
    153. USSR               : .ussr <image>
    154. iFunny Watermark   : .ifunny <image>
    --Auto places if no face detected.
    155. Santa Hat          : .santahat/hat <image/face>
    156. Gif Sharpen        : .gsharpen <gif> <scale>*
    157. Pixel 2            : .pixel2 <image> <scale>*
    158. Face Swap          : .swap <image (>= 2 faces)>
    159. Bernie             : .bernie/congress <image>
    160. Thug Life          : .thug/thuglife <image-face>
    161. Crop/Zoom Face     : .zoom <image-face>
    162. Race Recognition   : .races/kairos <image-face>
    163. Gimp Resize Error  : .gimp <image>
    164. Transgender Flag   : .trans <image>
    165. Sonic              : .sonic <text>
    166. NotSoBot Face      : .notsobot/nsb <image-face>
    167. Zalgo              : .zalgo <text>
    168. Yusuke             : .yusuke <image>
    169. Thinking Face      : .thinking <image-face>
    170. Joy Face           : .joy <image-face>
    171. Ajit Pai           : .ajit <image>
    172. Jack               : .jack <image>
    173. Israel Flag        : .israel <image>
    174. Logan Paul         : .logan <image>
    175. Gif Deep Fry       : .gdeepfy/gdf <gif>
    176. Trump              : .trump <image>
    177. Black              : .black <image-face>
    178. Black Panther      : .panther <image>
    179. SpaceX Starman     : .spacex/starman <image>
    180. Thinking Blend     : .think <image> <scale|1-100 (opacity)>*
    181. Invert Flash       : .flash <image> <delay (ms)>
    182. GExplode           : .gexplode/gex <image> <scale|1-6>*
    183. GImplode           : .gimplode/gim <image> <scale|1-6>*
    184. Change My Mind     : .changemymind/cmm <text>
    185. WikiHow            : .wikihow <query>
    186. Supreme Logo       : .supreme <image>
    -- Create a discord message screenshot.
    -- Use flags such as "-compact" or "-light" to change the theme.
    187. Quote              : .quote <user-mention/id>* <text>
      1. Message            : .quote id <message_id>
      -- Last 100 messages
      2. User               : .quote user <@discord_user>
    188. Stephen Hawking    : .hawking/hawk <image>
    189. Rain               : .rain <image>
    190. Gold               : .gold <image>
    191. Gold 2             : .gold2 <image>
    192. Exo                : .exo <image>
    193. Kek                : .kek <image>
    194. Kek 2 - Rain       : .kek2 <image>
    195. Paper/Napkin       : .paper <image>
    196. Bubble             : .bubble <image>
    197. Tunnel             : .tunnel <image>
      1. Mode 2             : .tunnel2 <image>
    198. In Out             : .inout/io <image> <delay|20-200 (ms)>
    199. Out In             : .outin/oi <image> <delay|20-200 (ms)>
    200. Blurple            : .blurple <image>
    201. Universe Overlay   : .universe/uni <image> <overlay_type|1-4>*
    202. Einstein Chalk     : .einstein/ein <text|1-15 characters>
    203. Fat Maker          : .fat <image-face>
    204. 100 Dollar Bill    : .bill/100 <image>
    205. Anime Eyes (Black) : .anime <image-face>
      1. Blue               : .anime blue/1 <image-face>
      2. Aqua               : .anime aqua/2 <image-face>
      3. Green              : .anime green/3 <image-face>
      4. Brown              : .anime brown/4 <image-face>
      5. Red                : .anime red/5 <image-face>
      6. Purple             : .anime purple/6 <image-face>
    206. Clown Face         : .clown <image-face>
    207. Alien Face         : .alien <image-face>
    208. Soup Letters       : .soup <text|1-14 characters>
    209. Mount Rushmore     : .mount <image-face>
         Faces
    210. Galatea of the     : .spheres/galatea <image>
         Spheres
    211. Museum Frame       : .museum <image>
    212. Burning Photo      : .burn <image>
    213. Pop Art (2 x 2)    : .popart/pop <image>
    -- Removes transparent body surrounding image.
    214. Center Image       : .center <image>
    215. Face Ovleray       : .faceoverlay/overlay <image-face> <image-overlay>
    216. Hot Girl Bottle    : .grill <text>
    217. Simpsons Days      : .days/simpsons <text>
         Since
    218. Face -Magik-       : .facemagik/fm <image-face>
      -- Alias for the effect is also the command number (e.g. ".fm 1" instead of ".eyes explode").
      1. Explode            : .fm explode/exp <image-face>
      2. Implode            : .fm implode/impl <image-face>
      3. Swirl              : .fm swirl <image-face>
      4. Circular/Radial    : .fm circle/radial <image-face>
          Blur
      5. Blur               : .fm blur <image-face>
      6. Charcoal           : .fm charcoal/coal <image-face>
      7. Tehi               : .fm tehi <image-face>
      8. Pixelate           : .fm pixelate/pixel <image-face>
      9. Spin - Random Hues : .fm spin <image-face>
      10. Alternative Magik : .fm magika <image-face>
      11. Rain              : .fm rain <image-face>
      12. Gold              : .fm gold <image-face>
      13. Frost             : .fm frost <image-face>
    219. Wheeze             : .wheeze <image>
