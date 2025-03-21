
# Idealization

Some people miss out on playing some of the most popular games simply because they don't have a partner to play with. That’s the problem that inspired this project.

The initial idea was to create a game designed for pairs, but if a user doesn’t have someone to play with, they can play with an AI tool that learns alongside them, adjusting its abilities based on the user’s skills. This idea was later refined, and now the goal is to develop an AI model that can learn how to play by being given the game's instructions, making it adaptable to any two-player game.

This is not meant to replace a second player, but rather to ensure that if someone doesn’t have a partner, they can still enjoy the game.

# Articles about advances of AI in video games

1. **Differ bots and players**

    Launching a software application that can differentiate bots from real players in games. Advancements in AI have fueled a rise and human gamers say these bots ruin the fun in part by putting them at a skill disadvantage.

    [click here to read more](https://www.wsj.com/livecoverage/stock-market-today-dow-nasdaq-sp500-03-17-2025/card/new-software-from-sam-altman-backed-world-targets-ai-bots-in-videogames-UxQoickmmqVUcAg2G0A0)

2. **Talk with the characters and process responses in real time**

    Sony is working on a prototype AI-powered version of at least one its PlayStation game characters. The prototype uses AI-powered version of Aloy that can hold a conversation with a player through voice prompts during gameplay. Aloy could be seen responding to queries with an AI-powered synthesized voice and facial movements. 

    The technology demo uses OpenAI’s whisper for speech-to-text, and both GPT-4 and Llama 3 for conversations and decision making. Sony’s has its own internal Emotional Voice Synthesis (EVS) system that it uses for speech generation, according to Raghoebardajal, and audio to face animation is powered by Sony’s own Mockingbird technology. 

    Nvidia has been working on its own similar technology for AI-powered NPCs in games, where you speak freely to video game characters. Microsoft has also been partnering closely with Inworld AI to eventually bring AI characters to Xbox, allowing game developers to use generative AI characters, storylines, and more. Microsoft has also created its own Muse AI model that generates gameplay, designed initially for game developers to create a game environment for prototyping and ideating. 

    [click here to read more](https://www.theverge.com/news/626695/sony-playstation-ai-characters-aloy-horizon-forbidden-west-prototype)

3. **AI model could generate examples of gameplay from a single screenshot**

    That’s the idea behind Microsoft’s Muse, a transformer. The result is a model that, when prompted with a screenshot of the game, can generate multiple examples of gameplay, which can extend up to several minutes in length.

    Muse (also known as the World and Human Action Model, or WHAM) was trained on human gameplay data from the multiplayer action game Bleeding Edge. 

    Muse isn’t the first AI model capable of generating gameplay. Notable predecessors include Google DeepMind’s Genie, Tencent’s GameGen-X, and GameNGen. Unlike prior models, Muse was trained on real-world human gameplay data that includes image data from gameplay and corresponding controller inputs. Genie and GameGen-X, by contrast, didn’t have access to controller inputs and instead trained on publicly available image data from various games.

    Muse also uses an autoregressive transformer architecture, which is uncommon for a model that generates images (gameplay, like video, is a series of images in sequence). GameNGen and GameGen-X, meanwhile, use specialized diffusion models to generate gameplay, and again don’t model controller input.

    **Muse and the WHAM Demonstrator are available for download from HuggingFace.**

    The clips are generated at a resolution of just 380 by 180 pixels and 10 frames per second, which is far too low for an enjoyable gameplay experience. Muse is also limited to generating gameplay similar to Bleeding Edge. 

    [click here to read more](https://spectrum.ieee.org/ai-video-games)

4. **Build videogames**

    Liminal Experiences Inc.  is creating a tool that allows users to build their own role playing-style video games using artificial intelligence tools that create characters, environments and storylines. 

    [click here to read more](https://labusinessjournal.com/technology/liminal-developing-ai-game-tool/)

5. **Talk like a friend with Gemini**

    Gemini asked about my weekend plans, and then I asked if it liked to play games.

    It created the following game:
    ~~~
    "You find yourself standing at the edge of a whispering forest. The air is thick with the scent of damp earth and ancient trees. A narrow path winds its way into the depths of the woods, disappearing into the shadows. To your left, you see a crumbling stone wall, partially overgrown with ivy. To your right, a small, gurgling stream flows from the forest, its water dark and clear.

    What do you do?

    Options:

    1 Follow the path into the forest.

    2 Examine the stone wall.

    3 Follow the stream.

    4 Listen to the sounds of the forest.
    ~~~

    [click here to read more](https://www.techradar.com/computing/artificial-intelligence/i-asked-gemini-to-play-a-text-based-adventure-game-with-me-and-the-ai-whisked-me-away-to-a-word-based-fantasy)

6. **Better games with AI**

    - Improved NPC (Non-Playable Characters) Behavior: In previous years, NPCs followed predictable patterns, which often made them feel robotic or easy to beat. AI has enabled NPCs to learn from players and adapt some of their skills in real-time.

    - Procedural Content Generation: AI is also used to create procedurally generated content, such as environments, levels, or entire game worlds. Video games like No Man’s Sky or Minecraft use AI to generate new planets, landscapes, or structures for players to explore, making each playthrough different and based on the individual player’s taste.

    - Personalized Gaming Experience: AI can analyze a player’s actions. This might involve changing the narrative based on the player's choices. Games like Digimon Survive and The Witcher are perfect examples of games that change their patterns specifically based on a player’s choice.

    - Voice Recognition and Natural Language Processing (NLP): Players can interact with games using voice commands. Games like Star Wars Jedi: Fallen Order and Skyrim VR use AI-powered voice recognition to allow for more immersive dialogues and actions.

    - AI in Game Testing and Quality Assurance: Testing and quality assurance are critical in game development, and AI is accelerating the process. AI-driven bots can simulate thousands of gameplay scenarios, spotting bugs and glitches that might be overlooked by human testers. 
    
    [click here to read more](https://www.redbull.com/mea-en/how-artificial-intelligence-is-revolutionizing-the-world-of-video-games)

7. **Otimizar desempenho do PC para jogos**

    Software OMEN AI Beta, que permite optimizar o desempenho do PC ao nível do hardware e do software com um único clique, eliminando a necessidade de procurar as melhores definições para cada jogo.

    [click here to read more](https://www.pcguia.pt/2025/01/hp-apresenta-o-novo-omen-max-16-e-um-software-de-optimizacao-de-jogos-com-inteligencia-artificial/)

8. **AI in games**

    **Google's use of AI in video games began with a critical development: creating an AI capable of recognizing game environments and reacting like a human player. In this early work, they introduced a deep reinforcement learning agent that could learn control strategies directly from gameplay. Central to this development was a convolutional neural network, trained using Q-learning, which processed raw screen pixels and converted them into game-specific actions based on the current state.**

    **Building on their early AI successes, Google set its sights on a more complex challenge: StarCraft II. This real-time strategy game is known for its complexity, as players must control armies, manage resources, and execute strategies in real-time. In 2019, Google introduced AlphaStar, an AI agent capable of playing StarCraft II professionally. AlphaStar's development used a mix of deep reinforcement learning and imitation learning. It first learned by watching replays of professional players, then improved through self-play, running millions of matches to refine its strategies. This achievement demonstrated AI's ability to handle complex, real-time strategy games, achieving results that matched human players.**

    Unlike earlier models that required access to a game's source code or custom APIs, SIMA operates with two inputs: on-screen images and straightforward language commands. SIMA translates these instructions into keyboard and mouse actions to control the game's central character. This method allows it to interact with different virtual settings in a way that mirrors human gameplay. Research has shown that AI trained across multiple games performs better than those trained on a single match, highlighting SIMA's potential to drive a new era of generalist or foundation AI for games.

    Google has expanded its focus from enhancing gameplay to developing tools that support game design. This shift is driven by advancements in generative AI, particularly in image and video generation. One significant development is using AI to create adaptive non-player characters (NPCs) that respond to player actions in more realistic and unpredictable ways.

    Additionally, Google has explored procedural content generation, where AI assists in designing levels, environments, and entire game worlds based on specific rules or patterns. This method can streamline development and offer players unique, personalized experiences with each playthrough, sparking a sense of curiosity and anticipation. A notable example is Genie, a tool that enables users to design 2D video games by providing an image or a description.

    Recently, they introduced GameNGen, a generative AI tool designed to simplify the game development process. GameNGen allows developers to build entire game worlds and narratives using natural language prompts, significantly cutting down the time and effort needed to create a game. By leveraging generative AI, GameNGen can generate unique game assets, environments, and storylines, enabling developers to focus more on creativity rather than technicalities. The technology behind GameNGen involves a two-phase training process. First, an AI agent is trained to play Doom, creating gameplay data. This data then trains a generative AI model that predicts future frames based on previous actions and visuals. The result is a generative diffusion model capable of producing real-time gameplay without traditional game engine components.

    [click here to read more](https://www.unite.ai/from-atari-to-doom-how-google-is-redefining-video-games-with-ai/)

9. **Like persons**

    **Eles desenvolveram a SIMA (Scalable Instructable Multiworld Agent), uma IA programada para cumprir uma diversidade de tarefas aleatórias em games, jogando todos eles como se fosse um ser humano.**

    Segundo o anúncio, a SIMA foi treinada para responder a uma variedade de ambientes 3D virtuais. O que ela faz é ser instruída a experimentar como eles funcionam com responsividade, completando objetivos que mudam constantemente em tempo real.

    **Ela já foi treinada para mais de 600 habilidades e comandos responsivos, incluindo navegação, interação com objetos e tomadas de decisão de acordo com o que acontece na tela. Numa experiência que se aproxima muito do jogador humano, ela pode executar ações que não levam mais do que 10 segundos para serem pensadas e completadas.**

    [click here to read more](https://meups.com.br/tecnologia/sima-ia-google-joga-games-como-humano/)