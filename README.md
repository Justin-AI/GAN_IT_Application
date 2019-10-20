# GAN_IT_Application
This repository contains an example implementation of a Vanilla GAN for simulated data.

<br>The simulated data contains 100,000 observations for three variables that are representative of normal trading conditions.

<br>A GAN is trained to learn the representation of the simulated data.

<br>The trained discriminator is then deployed for classification against a mixture of the normal data and a small sample of anomalies.

<br>The role of the discriminator is to flag the anomalies as "fake" (abnormal) data and classify the normal data as "real".

<br>The trained discriminator proves to be relatively proficient at this task; achieving high accuracy scores for normal and abnormal data classifications.
