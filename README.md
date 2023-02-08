# Deepfake Detective Web App

Project Outline: Deepfakes have become an increasing concern. Particularly with regards to their potential for promoting fake news, damaging reputations and broader societal impacts. This project will focus on an investigation, implementation and analysis of deepfake technology.

## Installation
Clone this repository by `git clone https://github.com/tyeborg/deepfake-detective.git`.

Navigate to the `flaskapp` folder/change the working directory by entering the following in the command line: 
```bash
cd flaskapp
```
Open the Docker Application and ensure that you don't have any other containers running using `docker ps`

Enter the following to build the Docker container:
```bash
docker-compose up --build
```
Visit Deepfake Detective app at: `http://localhost:3000`

## Deepfake Detective Concept
<img width="1401" alt="Screen Shot 2022-10-07 at 11 49 07 PM" src="https://user-images.githubusercontent.com/96035297/194673110-b8b3e1cf-a195-4fed-8712-88fa6c0be4bb.png">

## Datasets Utilized
* [FaceForensics++][1] - consists of 1000 original video sequences that have been manipulated with Deepfakes.
* [140k Real and Fake Faces][2] - consists of all 70k REAL faces from the Flickr dataset collected by Nvidia, as well as 70k fake faces sampled from the 1 Million FAKE faces (generated by StyleGAN) that was provided by Bojan.

[1]: https://www.kaggle.com/datasets/sorokin/faceforensics
[2]: https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces

## Languages & Tools Utilized

<p float="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=js,python,flask,html,css,docker,git,vscode" />
  </a>
</p>
