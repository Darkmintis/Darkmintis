<p align="center">
  <img src="https://github.com/Darkmintis/Darkmintis/blob/main/DarkmintisBanner.png" alt="Darkmintis Banner" width="100%" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=darkmintis&label=Profile%20Views&color=FF4500&style=flat" alt="Profile Views" />
</p>

<p align="center">
  <a href="mailto:darkmintis@gmail.com">
    <img src="https://img.icons8.com/color/48/000000/gmail-new.png" alt="Gmail" width="30" />
  </a>
  <a href="https://x.com/darkmintis">
    <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/x.svg" alt="X" width="30" />
  </a>
  <a href="https://t.me/Darkmintis">
    <img src="https://img.icons8.com/color/48/000000/telegram-app.png" alt="Telegram" width="30" />
  </a>
</p>

<h2 align="center">Tool Arsenal</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,javascript,react,nodejs,mongodb,kali,burpsuite,wireshark,tails" />
</p>

<h2 align="center" style="display: inline;">Organizations: </h2>
<p align="center" style="display: inline;">
  <span id="org-name"></span>
</p>

<script>
  const orgs = ['@Minix-Lab', '@D-Dark-Lab', '@Drimics-Games', '@D-Project24', '@BlockTech-Solutions', '@Round-Tech', '@Wallora-Themes', '@ACE-Core'];
  let currentOrg = 0;
  
  function updateOrgName() {
    document.getElementById('org-name').textContent = orgs[currentOrg];
    currentOrg = (currentOrg + 1) % orgs.length;  // Rotate through orgs
  }
  
  setInterval(updateOrgName, 2000);  // Update org every 2 seconds
  updateOrgName();  // Initial call to display the first org immediately
</script>





