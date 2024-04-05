<template>
    <div class="skill" id="Skill">
        <h1>SKILL</h1>
        <p>Ini adalah beberapa keahlian yang saya merasa cukup percaya diri dalam melakukannya.</p>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Ilmu-Ilmu Alam</li>
            <li>Matematika</li>
        </ul>
        <br>
        <p>Bahasa yang saya kuasai</p>
        <ul>
            <li>Bahasa - Native</li>
            <li>English - Intermediate</li>
        </ul>
    </div>
    <div class="imageSkill">
        <img src="../assets/pictskill.png" alt="Picture of Skills" class="PSkill">
    </div>
</template>

<style>
.skill {
    text-align: center; 
    left: 0;
    width: 100%;
    z-index: 1000; 
    margin-top: 250px;
    text-decoration: none;
    color: #815854;
    font-weight: bold;
    padding-top: 100px; 
}

.skill h1, .skill p {
    text-align: center; 
}

.skill ul {
    list-style-type: disc;
    padding: 10;
    text-align: left;
}
.imageSkill{
    width: 66%;
    height: 70%;
    position: absolute;
    bottom: 10;
    right: 70px;

}

.imageSkill .PSkill{
    height: 50%;
    position: absolute;
    left: 45%;
    bottom: 100%;

}

</style>