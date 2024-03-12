---
layout: project-left # alternative layouts: project, project-left, project-right, project-top
title: "MoodMuse"
description: "Breathing new life into old industrial estates"
date: 2019-12-20
weight: 3
permalink: /projects/project-3
thumbnail: "/assets/images/gen/projects/moodmuse.webp"
image: "/assets/images/gen/projects/moodmuse.webp"
#categories: [""]
client: "Making Music with Affective Computing and Empathic Artificial Intelligence"
role: "Building Designer & Software Developer"
gallery:
  - image: "/assets/images/gen/projects/moodmuse.webp"
    caption: "<strong>Above:</strong> FrontEnd MoodMuse with input characteristics on the right and a diashow on the left."
  - image: "/assets/images/gen/projects/faceemotionrecognition.webp"
    caption: "<strong>Above:</strong> Face Emotion Recognition with output = [[ Surprised, Happy, Neutral ], [ Happy, Sad, Neutral ], [ Happy, Neutral, Surprised ], [ Happy, Neutral, Angry ]], based on der FER2013 Dataset. "
  - image: "/assets/images/gen/projects/mapping.webp"
    caption: "<strong>Above:</strong> Mapping Emotion-to-Text/Emotion-to-Music."
  - image: "/assets/images/gen/projects/melody.webp"
    caption: "<strong>Above:</strong> Melody creation: The music logic behing it."
---

## Mood Muse is a unique AI tool that allows you to compose music just for you and your feelings. 

MoodMuse is based on a triple pipline architecture that goes through the process of music generation from an 20s video input to an 20s music output that underlines the emotion of the video in 4-8min. 

The 20s input is divided into 4 parts of 5s each. 

While the FER2013 dataset is used for face emotion recognition, the emotion-to-text and emotion-to-music mapping has been specially created. Each part is assigned an emotion, which then generates the appropriate music for each snippet using the Python library midiutil. Each snippet is based on the previous musical components. MusicGen refines all snippets into a coherent piece of music. 

Restrictions and difficulties encountered during the project and in the solution are listed in more detail in the following final presentation. 

[Download the final presentation here](/assets/files/MoodMuse_FinalPresentation.pdf)

This project was developed as part of the course "Affective Computing - Empathic Artifical Intelligence" at LMU under Dr. Marco Maier together with Franziska Woerle, Laura Schroeder, Ardit Mazreku and Phi Linh Phan.