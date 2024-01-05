---
title: "Antony"
date: 2023-06-22T07:55:41+02:00
---

<style>
.profile-container {
  display: flex;
  align-items: center;
  margin-top: 0;
}

.profile-image {
  border-radius: 50%;
  height: 250px;
  width: 250px;
  margin-right: 70px;
}

.profile-details {
  margin-top: 20px;
}

@media (max-width: 600px) {
  .profile-container {
    flex-direction: column;
    align-items: center; /* Horizontally center the elements */
  }

  .profile-image {
    margin-right: 0;
    margin-bottom: 20px;
    margin-left: auto; /* Horizontally center the image */
    margin-right: auto;
  }
}
</style>

<div class="profile-container">
  <!-- Set up a circular image with a border radius of 50% -->
  <img src="./Antony.jpg" alt="Antony" class="profile-image">

  <div class="profile-details">
    <h1>Antony Zappacosta</h1>
    <h3 style="display: inline;">Researcher and Helmholtz AI consultant</h3>
    <h3 style="display: inline;"> - German Aerospace Center (DLR)</h4>
    <h5>
    I'm a Research Fellow at the German Aerospace Center's Institute of Earth Observation, based in Oberpfaffenhofen (Bavaria). My work revolves around applying machine and deep learning to satellite imagery.
    </h5>
    <h5>Prior to joining DLR, I graduated summa cum laude with a MSc in Computer Engineering from Bologna University, Italy.</h5>
    <h5>Out of work I love reading and hiking.</h5>
  </div>
</div>