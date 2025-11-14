# Side-Scrolling Runner

<iframe width="560" height="315" src="https://www.youtube.com/embed/e1Oe_7edqb0?si=wMSeWDB0adxQWgi0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

https://www.youtube.com/watch?v=e1Oe_7edqb0

## Summary

The brazilian Bitcoin exchange [AlfredP2P](https://alfredp2p.io) wanted a simple, yet fun game to use at the end of the purchase flow, as a "thank you" game. Playing the game after buying satoshis gives the customers a toy to be entertained and new coupons for having less fees on next purchases can be unlocked depending on the highscore of the match.

On this retro-styled 2d pixel art inspired by the 16 bits classics, and the "Chrome Dinosaur Game", you control a friendly robot in their modest flying saucer that is able to perform jumps and small glides to surpass rocks and meteors in a desert planet.

## Fact Sheet

- Created by: Falafel Open Games
- Comissioned by: [Alfred P2P](https://www.alfredp2p.io/)
- Art Director: Fabricio Campos Zuardi
- Lead Programmer: Fabricio Campos Zuardi
- Inspired by: Dinosaur Game - Allan Bettes, Sebastian Gabriel, Edward Jung
- Music: Hydrogen
- Backgrounds: Ansimuz
- Obstaccles: Kenney
- Icons: Nickoichu
- Fonts: GGBotNet
- QA/Playtest: Juliana, Giovanni, Guilherme, Leonarddo, Lucas, Marcelo, Thiago, Rafael, Mauricio, Marcel
- Platform: HTML5
- Game Engine: Godot
- Date to Publish the Source Code: April 15th of 2026
- Github (private until end of embargo period): https://github.com/fczuardi/side-scrolling
- Itch (private until end of embargo period): https://fczuardi.itch.io/side-scrolling

## How the project was born

Other than a game developer, I am also an open-source enthusiast and I havee participated in free-softwaree and free culture communities since the beginning of projects like Mozilla and Creative Commons. Currently, the most exciting bunch of freedom tech nerds that I know of can bee found on Bitcoin and Nostr circles. I attend to brazilian metups both dev-focuseed like the Bitdevs promoted by [Vinteum](https://vinteum.org) in São Paulo, as well as other local meetups related to this particular freedom tech (Bitcoin).

Falafel Open Games started from my personal curiosity of learning [Godot](https://godotengine.org/), the powerful open-source game engine that can be used for both 3D and 2D games alike, I usually cowork with other indie gamee dev friends at an innovation center in São Carlos - SP, [ONOVO Lab](https://onovolab.com/). But when I am in the capital São Paulo SP for the Bitdevs meetups, I usually cowork for at least 1 day at **Casa Vinteum**, a Hacker House in the city. I develop parts of my [Contractor Hero](https://fczuardi.itch.io/contractor-hero) demo there.

Anyways, back to local meetups, at São Carlos... 

During a meetup for bitcoiners with hamburguers I met a bunch of people, including [Leonardo](https://www.linkedin.com/in/leonardo-maximiliano/) from AlfredP2P, I gave him the Contractor Hero demo to play and we talked about the possibility of developing a custom game for his company's brand, the conversation progressed, they were open to the idea of sponsoring an open-source 2D side-scrolling game that could be adapted to different themes, as long as the first theme was one with their mascot, Alfred the bot.

On this particular comissioned work we negotiated a 6-month embargo on the source, in order to give them more peace of mind on the investment and some kind of first-mover-advantage, since they were the first ones to believe in my work and to risk funding a project with a still nascent indie game studio.

## Made cheaper andd safer with the use of CC0 licensed art

As a small team, Falafel Open Games dont have a full time pixel-artist or a chiptunes music author, in order to keep the project under our proposed budget, arts from the commons were used, the delivered game uses 3 incredible tracks from the artist [Hydrogene](https://hydrogene.itch.io/high-quality-8-bit-musics) and paralax background layers from the artist [Ansimuz](https://ansimuz.itch.io/gothicvania-patreon-collection), the complete list of contributors can be found in the "Info" section of the game, or in this URL after the code embargo (April 15th 2026): https://github.com/fczuardi/side-scrolling/blob/main/themes/README.md

## Prizes for playing

In this case, customers of the website were rewarded by good highscores in the game, providing an engaging expeerience with the brand, the "thank-you game" keeps the people in the website for longer times, give them a reason to return and interact again, as well as promote it to their friends.

### Tech Challenges

The validation of the game inputs, the game impossible states, as well as integration with the sponsor's backend stack, including basic telemetry and anti-cheating safeguards was a part of the work that I did in colaboration with their tecch team and a simple example of how to communicate a Godot-based frontend with a Next.js website was provided and is available as an open source project as well, contact mee for details.

## A gameplay that remains "just" for as long as your resistance allows

This was a game that can be considered in the genre of "endless runners", with a procedurally generated sequence of obstacles that doesnt have an end, much like some early games from the Atari 2600 era (think Enduro) or the big reference here, the Chrome's Dino Game. The more you keep yourself alive, more difficult the obstacles become, they come at you increasingly faster, with a bigger diversity (meteors after reaching a certain number of points), but there are some safeguards to asure the player that no sequence of obstacles is impossible to avoid. For example, there is a maximum speed and a minimum distance between obstacles, the idea is that a skillfull player in theory can be able to play this game for hours, this game tries to follow the qualities of other runners like BitTrip Runner in a sense that if you died, it was due to a mistake, and not due to an impossible to overcome level.

The level although procedural, is deterministic, which means that any two players playing the same build of the game with the same "seed", will have the exact same sequence of obstacles and will be able to compare scores, without the looser having the excuse that he got a "harder" level.







