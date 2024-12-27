---
title: "EEG and Human Perceived Fairness in the Workload Division Process"
excerpt: |
  Evaluate the impact of UI designs on user cognitive load and engagement in the workload division process with electroencephalogram (EEG). <br/>
  <video width="600" height="400" autoplay muted loop>
    <source src="/files/tetris-eeg_compressed.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
collection: projects
---

<div class="media-container">
  <div class="media-item">
    <video width="400" height="300" autoplay muted loop>
      <source src="/files/tetris-eeg_compressed.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div class="media-item">
    <img src="/files/Tetris_EEG_figure1.png" alt="Project Image" width="400" height="300">
  </div>
</div>

<p>
  <br>
  <br>
 • We aim to study human’s perception on fairness in terms of dividing workload in a group. For stimulating 2 people working in a group, we let participant play a Tetris game, and they can see how their partner is playing in real time. Each participants will play 8 rounds of game. We plan to manipulate the “game summary” page (outline in blue in figure 1), and see if different UI designs would impact participants’ cognitive load, engagement, and most importantly, their perception.
  <br>
   <br>
 • Based on several related papers, we have found “social comparison” and “intention” being two crucial factors affecting one’s perception on fairness. We plan to implement a 2x2 within subject design on showing: (1) Note from the system: Your game difficulty level is harder (easier) than your partner, and (2) Message from your partner: Your partner sent you a thumbs up (or not) in 8 rounds of games.
  <br>
   <br>
 • We designed a game platform for measuring participants’ Event-Related Potential (ERP). The game platform is auto-advanced so we could accurately sync their behavioral data with EEG measurements.
  <br>
   <br>
 • Currently in the data collection process
 </p>


<style>
  .media-container {
    display: flex;
    justify-content: space-between; /* Space between video and image */
    align-items: center; /* Vertically center content */
    gap: 20px; /* Space between video and image */
  }

  .media-item {
    flex: 1; /* Makes each item take up equal space */
    text-align: center; /* Centers content inside each item */
  }

  img, video {
    max-width: 100%; /* Ensures the video and image scale responsively */
    height: auto; /* Maintains aspect ratio */
  }

  @media (max-width: 768px) {
    .media-container {
      flex-direction: column; /* Stacks the video and image vertically on smaller screens */
      align-items: center;
    }
  }

  img, video {
  width: 500px;  /* Set width to 500px for both */
  height: 400px; /* Set height to 500px for both */
  object-fit: cover; /* Ensures the content covers the full area, maintaining aspect ratio */
  border: 1px solid black; /* Adds a solid black border of 1px thickness */
  border-radius: 5px; /* Optional: rounded corners */
}
</style>




