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
    <h3 style="display: inline;">Software engineer</h3>
    <h4 style="display: inline;"> - Munich, Germany</h4>
    <h5>Computer Engineering graduate from the University of Bologna, Italy. Deeply passionate about software engineering and computer vision.</h5>
  </div>
</div>