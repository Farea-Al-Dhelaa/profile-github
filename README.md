<!DOCTYPE html>
<html>
<head>
<style>
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.header {
    text-align: center;
    margin-bottom: 40px;
}

.header img {
    width: 100%;
    max-height: 300px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 20px;
}

.title {
    color: #2d333b;
    font-size: 2.5em;
    margin: 10px 0;
}

.subtitle {
    color: #484f58;
    font-size: 1.5em;
    margin-bottom: 30px;
}

.profile-section {
    display: flex;
    gap: 40px;
    margin-bottom: 40px;
}

.profile-info {
    flex: 1;
}

.profile-image {
    flex: 0 0 300px;
}

.profile-image img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.info-item {
    margin: 15px 0;
    display: flex;
    align-items: center;
    gap: 10px;
    color: #484f58;
}

.social-links {
    margin: 30px 0;
}

.social-links a {
    display: inline-block;
    margin-right: 15px;
    transition: transform 0.2s;
}

.social-links a:hover {
    transform: translateY(-3px);
}

.skills-section {
    margin: 40px 0;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
    gap: 20px;
    padding: 20px 0;
}

.skill-item {
    text-align: center;
    transition: transform 0.2s;
}

.skill-item:hover {
    transform: translateY(-5px);
}

.skill-item img {
    width: 40px;
    height: 40px;
}

.stats-section {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin: 40px 0;
}

.stats-card {
    background: white;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.stats-card img {
    width: 100%;
    height: auto;
}

h3 {
    color: #2d333b;
    border-bottom: 2px solid #0366d6;
    padding-bottom: 10px;
    margin-bottom: 20px;
}

.view-counter {
    display: inline-block;
    padding: 5px 10px;
    background: #0366d6;
    color: white;
    border-radius: 20px;
    font-size: 0.9em;
}
</style>
</head>
<body>
<div class="container">
    <div class="header">
        <img src="https://1.bp.blogspot.com/-7A4WynwLsMw/XbBpCXG8fHI/AAAAAAAAMt4/uOa1bpLskYgrwGbllhSu2SDj_Mig8SXJQCLcBGAsYHQ/s1600/2000_600px.gif" alt="MasterHead">
        <h1 class="title">Hi 👋, I'm Farea AL-Dhelaa</h1>
        <h2 class="subtitle">A passionate Full Stack developer from Yemen</h2>
        <span class="view-counter">
            <img src="https://komarev.com/ghpvc/?username=farea-al-dhelaa&label=Profile%20views&color=0e75b6&style=flat" alt="profile views">
        </span>
    </div>

    <div class="profile-section">
        <div class="profile-info">
            <div class="info-item">
                <span>🌱 I'm currently learning:</span>
                <strong>Node.js, React Native, Django</strong>
            </div>
            <div class="info-item">
                <span>💬 Ask me about:</span>
                <strong>Android, Flutter</strong>
            </div>
            <div class="info-item">
                <span>📫 How to reach me:</span>
                <strong>faraa717281413@gmail.com</strong>
            </div>

            <div class="social-links">
                <h3>Connect with me:</h3>
                <a href="https://twitter.com/farea_al_dhelaa" target="_blank">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30">
                </a>
                <a href="https://linkedin.com/in/farea-al-dhelaa" target="_blank">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30">
                </a>
                <a href="https://www.youtube.com/c/@farea_al_dhelaa" target="_blank">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" height="30">
                </a>
            </div>
        </div>
        <div class="profile-image">
            <img src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" alt="Coding">
        </div>
    </div>

    <div class="skills-section">
        <h3>Languages and Tools:</h3>
        <div class="skills-grid">
            <!-- Your existing skills icons here -->
        </div>
    </div>

    <div class="stats-section">
        <div class="stats-card">
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=farea-al-dhelaa&show_icons=true&locale=en&layout=compact" alt="Top Languages">
        </div>
        <div class="stats-card">
            <img src="https://github-readme-stats.vercel.app/api?username=farea-al-dhelaa&show_icons=true&locale=en" alt="GitHub Stats">
        </div>
        <div class="stats-card">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=farea-al-dhelaa" alt="GitHub Streak">
        </div>
    </div>
</div>
</body>
</html>
