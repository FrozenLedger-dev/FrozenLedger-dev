<div align="center">
  <img width=100% src=https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&reversal=true />
</div>

<style>
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  
  @keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
  }
  
  @keyframes glow {
    0%, 100% { filter: drop-shadow(0 0 5px rgba(138, 43, 226, 0.5)); }
    50% { filter: drop-shadow(0 0 15px rgba(138, 43, 226, 0.8)); }
  }
  
  @keyframes pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.1); }
  }
  
  @keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  
  @keyframes slideIn {
    from { opacity: 0; transform: translateX(-30px); }
    to { opacity: 1; transform: translateX(0); }
  }
  
  .skill-icon {
    display: inline-block;
    margin: 8px;
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    animation: fadeIn 0.8s ease-out backwards;
    animation-delay: calc(var(--i) * 0.05s);
  }
  
  .skill-icon:hover {
    transform: translateY(-10px) scale(1.2);
    filter: drop-shadow(0 10px 20px rgba(138, 43, 226, 0.7));
    z-index: 10;
    position: relative;
  }
  
  .skill-icon img {
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    border-radius: 10px;
    padding: 4px;
    background: rgba(255, 255, 255, 0.05);
  }
  
  .skill-icon:hover img {
    transform: rotate(8deg) scale(1.1);
    background: rgba(138, 43, 226, 0.1);
    box-shadow: 0 0 20px rgba(138, 43, 226, 0.4);
  }
  
  .section-title {
    animation: slideIn 1s ease-out;
    position: relative;
  }
  
  .section-title::after {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    width: 0;
    height: 3px;
    background: linear-gradient(90deg, #667eea, #764ba2, #f093fb);
    animation: expandWidth 1.5s ease-out 0.5s forwards;
  }
  
  @keyframes expandWidth {
    to { width: 200px; }
  }
  
  h2 {
    animation: slideIn 0.8s ease-out;
    position: relative;
    display: inline-block;
  }
  
  h2::before {
    content: '';
    position: absolute;
    left: -20px;
    top: 50%;
    transform: translateY(-50%);
    width: 4px;
    height: 0;
    background: linear-gradient(180deg, #667eea, #764ba2);
    animation: expandHeight 0.8s ease-out 0.3s forwards;
    border-radius: 2px;
  }
  
  @keyframes expandHeight {
    to { height: 100%; }
  }
  
  .about-me-img {
    animation: float 3s ease-in-out infinite;
    transition: all 0.3s ease;
  }
  
  .about-me-img:hover {
    transform: scale(1.02);
    filter: drop-shadow(0 10px 30px rgba(138, 43, 226, 0.3));
  }
  
  .badge-link {
    display: inline-block;
    margin: 5px;
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    animation: fadeIn 0.8s ease-out backwards;
    animation-delay: calc(var(--j) * 0.1s);
  }
  
  .badge-link:hover {
    transform: translateY(-5px) scale(1.1);
    filter: drop-shadow(0 8px 20px rgba(0, 0, 0, 0.4));
  }
  
  .badge-link img {
    transition: all 0.4s ease;
    border-radius: 6px;
  }
  
  .badge-link:hover img {
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
  }
  
  .profile-views {
    animation: pulse 2s ease-in-out infinite;
  }
  
  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  .welcome-text {
    animation: fadeIn 1.2s ease-out, gradient 5s ease infinite;
    background: linear-gradient(90deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #4facfe 75%, #667eea 100%);
    background-size: 300% auto;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 600;
    text-shadow: 0 0 30px rgba(138, 43, 226, 0.3);
  }
</style>

<div width="100%">
    <h1 align="center" class="section-title">
      <img
        src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=600&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Prince+Kitty;❤Senior+Blockchain+Developer❤;+Passinate+and+Reliable+Developer;"
        alt="Animated typing text: Hi There! 👋 I'm Prince Kitty ❤Senior Blockchain Developer❤ Passinate and Reliable Developer" />
    </h1>
  </div>

<div align="center">
  <br>
  <img src="aboutme.svg" width="1000" height="auto" alt="Click to see the source" class="about-me-img">
</div>

-----

## ✨ Skills 💪

### Programming Languages
<div align="center">
  <span class="skill-icon" style="--i: 0"><img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="TypeScript" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 1"><img src="https://skillicons.dev/icons?i=solidity" alt="Solidity" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 2"><img src="https://skillicons.dev/icons?i=rust" alt="Rust" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 3"><img src="https://skillicons.dev/icons?i=go" alt="Go" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 4"><img src="./assets/language/move.png" alt="Move" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 5"><img src="./assets/language/funC.png" alt="FunC" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 6"><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 7"><img src="https://skillicons.dev/icons?i=cpp" alt="C++" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 8"><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 9"><img src="https://skillicons.dev/icons?i=php" alt="PHP" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 10"><img src="https://skillicons.dev/icons?i=ruby" alt="Ruby" width="48" height="48" /></span>
</div>

### Frameworks & Tooling
<div align="center">
  <span class="skill-icon" style="--i: 0"><img src="./assets/framework/foundry.png" alt="Foundry" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 1"><img src="./assets/framework/hardhat.svg" alt="HardHat" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 2"><img src="./assets/framework/anchor.png" alt="Anchor" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 3"><img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 4"><img src="https://skillicons.dev/icons?i=express" alt="Express" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 5"><img src="https://skillicons.dev/icons?i=nestjs" alt="Nest.js" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 6"><img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 7"><img src="https://skillicons.dev/icons?i=nuxtjs" alt="Nuxt.js" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 8"><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 9"><img src="https://skillicons.dev/icons?i=angular" alt="Angular" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 10"><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React Native" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 11"><img src="https://skillicons.dev/icons?i=threejs" alt="Three.js" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 12"><img src="https://skillicons.dev/icons?i=tailwind" alt="Tailwind" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 13"><img src="https://skillicons.dev/icons?i=laravel" alt="Laravel" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 14"><img src="https://techstack-generator.vercel.app/django-icon.svg" alt="Django" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 15"><img src="https://skillicons.dev/icons?i=fastapi" alt="FastAPI" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 16"><img src="https://skillicons.dev/icons?i=flutter" alt="Flutter" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 17"><img src="./assets/framework/vapi.png" alt="VApi" width="48" height="48" /></span>
</div>

### Blockchain Networks
<div align="center">
  <span class="skill-icon" style="--i: 0"><img src="./assets/chain/solana.png" alt="Solana" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 1"><img src="./assets/chain/ethereum.png" alt="Ethereum" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 2"><img src="./assets/chain/binance.png" alt="BNB Chain" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 3"><img src="./assets/chain/aptos.png" alt="Aptos" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 4"><img src="./assets/chain/polkadot1.png" alt="Polkadot" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 5"><img src="./assets/chain/cosmos.png" alt="Cosmos" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 6"><img src="./assets/chain/polygon.png" alt="Polygon" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 7"><img src="./assets/chain/ton.png" alt="Ton" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 8"><img src="./assets/chain/trx.png" alt="Tron" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 9"><img src="./assets/chain/sui.png" alt="Sui" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 10"><img src="./assets/chain/stellar.png" alt="Stellar" width="48" height="48" /></span>
</div>

### Backend, Data & Cloud
<div align="center">
  <span class="skill-icon" style="--i: 0"><img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 1"><img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 2"><img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 3"><img src="https://skillicons.dev/icons?i=redis" alt="Redis" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 4"><img src="https://skillicons.dev/icons?i=aws" alt="AWS" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 5"><img src="https://skillicons.dev/icons?i=gcp" alt="GCP" width="48" height="48" /></span>
</div>

### AI & Agentic Systems
<div align="center">
  <span class="skill-icon" style="--i: 0"><img src="./assets/ai/openai.png" alt="OpenAI" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 1"><img src="./assets/ai/deepseek.svg" alt="DeepSeek" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 2"><img src="./assets/ai/Langchain.svg" alt="LangChain" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 3"><img src="./assets/ai/huggingface.svg" alt="HuggingFace" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 4"><img src="./assets/ai/eliza.jpg" alt="ElizaOS" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 5"><img src="https://skillicons.dev/icons?i=tensorflow" alt="TensorFlow" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 6"><img src="https://skillicons.dev/icons?i=pytorch" alt="PyTorch" width="48" height="48" /></span>
  <span class="skill-icon" style="--i: 7"><img src="./assets/ai/ollama.svg" alt="Ollama" width="48" height="48" /></span>
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=coinhole&style=plastic&color=blueviolet" alt="Profile Views" class="profile-views" />
</div>
<br>
<div align="center">
<a href="mailto:bluedragon47174@gmail.com" class="badge-link" style="--j: 0">
  <img src="https://img.shields.io/badge/Email-D14836?style=plastic&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://discord.com/users/<your_user_id>" class="badge-link" style="--j: 1">
  <img src="https://img.shields.io/badge/Discord-5865F2?style=plastic&logo=discord&logoColor=white" alt="Discord" />
</a>
<a href="https://t.me/hinatasugimoto" class="badge-link" style="--j: 2">
  <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=plastic&logo=telegram&logoColor=white" alt="Telegram" />
</a>
<a href="https://wa.me/<your_wa_number>" class="badge-link" style="--j: 3">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=plastic&logo=whatsapp&logoColor=white" alt="WhatsApp" />
</a>
<a href="https://github.com/coinhole" class="badge-link" style="--j: 4">
  <img src="https://img.shields.io/badge/GitHub-100000?style=plastic&logo=github&logoColor=white" alt="GitHub" />
</a>
</div>

-----

<h4 align="center" class="welcome-text">
  Welcome to my GitHub profile!    Don't forget to give ⭐star⭐ and 👍follow👍 me on GitHub.
</h4>
