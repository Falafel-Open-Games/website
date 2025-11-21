# A Thank-you Game That Gives Customers A Reason To Come Back

## Alfred P2P Side-scrolling Game Case

The Brazilian Bitcoin exchange [Alfred P2P](https://alfredp2p.io) enhanced their after-purchase flow with a custom-made "thank you" game that unlocks discount coupons.

After buying satoshis through the service, customers take control of the mascot, Alfred the Bot, and engage in a playful experience where they can win coupons for the next purchases.

A good score in the game is the key to unlock increasingly better discounts on fees. This experience keeps the customer on the website for longer periods, giving them a reason to return, interact, and promote the service among their friends.

## Retro-styled Runner

The open-source game codenamed "Project London", commissioned by Alfred P2P, is a retro-styled take on the "Chrome Dinosaur Game" theme inspired by the 16 bit console era pixel-art 2D games. You control a friendly robot in its modest flying saucer that is able to perform jumps and small glides to surpass rocks and meteors in a desert planet.

<iframe width="560" height="315" src="https://www.youtube.com/embed/e1Oe_7edqb0?si=wMSeWDB0adxQWgi0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

https://www.youtube.com/watch?v=e1Oe_7edqb0

<img height="600" alt="Image" src="https://github.com/user-attachments/assets/253b106c-4459-4ba2-8481-03f41b7a3d98" />
<img height="600" alt="Image" src="https://github.com/user-attachments/assets/e8033459-53b2-439c-b1ef-b7914ea7dbab" />
<img height="600" alt="Image" src="https://github.com/user-attachments/assets/b15b4af1-a7a4-47ba-9009-dcb1a05ebbc2" />
<img height="600" alt="Image" src="https://github.com/user-attachments/assets/11603344-0398-4ea3-ae48-c298c10f5ec7" />
<img height="600" alt="Image" src="https://github.com/user-attachments/assets/e5be10dd-55bc-45fb-a55f-317fc2691ba8" />


<img width="600" alt="Image" src="https://github.com/user-attachments/assets/3cad4c13-7dc0-4a91-8d42-d20a0af7c293" />



## Fact Sheet

- Created by: Falafel Open Games
- Commissioned by: [Alfred P2P](https://www.alfredp2p.io/)
- Art Director: Fabricio Campos Zuardi
- Lead Programmer: Fabricio Campos Zuardi
- Inspired by: Dinosaur Game - Allan Bettes, Sebastian Gabriel, Edward Jung
- Music: [Hydrogene](https://hydrogene.itch.io/)
- Backgrounds: [Luis Zuno aka Ansimuz](https://ansimuz.com/)
- Obstaccles: [Kenney](https://kenney.nl/)
- Icons: [Nikoichu](https://nikoichu.itch.io/)
- Fonts: [GGBotNet](https://www.ggbot.net/)
- QA/Playtest: Juliana, Giovanni, Guilherme, Leonarddo, Lucas, Marcelo, Thiago, Rafael, Mauricio, Marcel
- Platform: HTML5
- Game Engine: [Godot](https://godotengine.org/)
- Date to Publish the Source Code: April 15th of 2026
- Github (private until end of embargo period): `https://github.com/fczuardi/side-scrolling`
- Itch (private until end of embargo period): `https://fczuardi.itch.io/side-scrolling`

## A Web-based Game To Support The Brand

The project was born during a meetup for bitcoiners with hamburguers, I presented Falafel's tech demo [Contractor Hero](https://fczuardi.itch.io/contractor-hero) to [Leonardo](https://www.linkedin.com/in/leonardo-maximiliano/) from Alfred P2P. 

As he played the demo, we discussed how a custom game could support his company's brand. They wanted to use Alfred the Bot, their mascot, as the game's hero.

We reached a proposed **open-source sponsorship model** that served well for their needs, it was strategic to their marketing timeframe (to launch on [Satsconf](https://satsconf.com.br/) and before Black Friday, a hard deadline), budget, and the impact to the brand experience they needed. The support of open-source highlights the brand's alignment with the Bitcoin freedom message and allowed us to move quickly with a peace-of-mind.

[Read more about how Falafel open-source model means lower risks](https://games.falafel.com.br/about)

To give them a first-mover advantage, we negotiated a 6-month embargo on the source, since they were the first ones to believe in this nascent indie game studio.


## Marketing Goals

### CC0 Assets - cheaper, safer and supportive of a healthy commons

Currently, Falafel Open Games don't have a full time pixel-artist or a chiptunes music author. As a small shop, we use the commons for solving games for marketing.

We kept the project under our proposed budget by using arts from this rich pool, [the public domain](https://www.thepublicdomain.org/enclosing-the-commons-of-the-mind/). 

The delivered game uses 3 incredible tracks from the artist [Hydrogene](https://hydrogene.itch.io/high-quality-8-bit-musics) and paralax background layers from the artist [Ansimuz](https://ansimuz.itch.io/gothicvania-patreon-collection), the complete list of contributors can be found in the "Info" section of the game, or in this URL after the code embargo (April 15th 2026): `https://github.com/fczuardi/side-scrolling/blob/main/themes/README.md`

### Integration - collaborating with the existing systems

Since players would be rewarded by their highscores, the game design and logic had to safely fit on the existing service.

We took care of validation of the game inputs and the impossible states by providing the path for integration with the sponsor's backend stack. Basic telemetry and some anti-cheating safeguards were a part of the work in colaboration with their tecch team. An example of how to communicate a Godot-based frontend with a Next.js website was provided and is available as an open source project as well.

### A gameplay that remains "just" for as long as your resistance allows

The game was designed based on the "endless" premise of early games from the Atari 2600 era (think [Enduro](https://en.wikipedia.org/wiki/Enduro_(video_game))) or the big reference here, [Chrome's Dino Game](https://en.wikipedia.org/wiki/Dinosaur_Game).

Keep yourself alive, and the difficult will keep increasing, but only up to a cap. There are some safeguards to asure that no sequence of obstacles is impossible to avoid. 

For example, there is a maximum speed and a minimum distance between obstacles, the idea is that a skillfull player would be able to play this game for hours, we reached for the qualities of other runners like [BitTrip Runner](https://en.wikipedia.org/wiki/Bit.Trip_Runner) in a sense that if you died, it was due to a mistake, and not due to an impossible to overcome level.

#### Nerdy Observation

The level although procedural, is deterministic, which means that any two players playing the same build of the game with the same "seed", will have the exact same sequence of obstacles and will be able to compare scores, without the looser having the excuse that he got a "harder" level.

