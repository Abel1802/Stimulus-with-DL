# Introduction

## Abstract
Creating a naturalistic speech stimulus continuum (i.e., a series of stimuli equally spaced along a specific acoustic dimension between two given categories) is an indispensable component in categorical perception studies. A common method is to manually modify the key acoustic parameter of speech sounds, yet the generation process is time-consuming and the quality of synthetic speech is still unsatisfying. In this paper, we adopt an adversarial learning framework to separate the specific acoustic feature from other contents in speech signals and achieve controllable speech stimulus generation by sampling from the latent space of the key acoustic feature. Specifically, in a case study of tone continuum generation, an autoencoder was trained first to learn pitch-independent latent representations and disentangled representation of pitch separately using another auxiliary pitch predictor to regularize the latent representation. Then several latent representations between the two reference pitch representations of the continuum endpoints were sampled equidistantly. The decoder merged the pitch-independent content and a sampled latent representation to recompose an intermediate speech stimulus. Experiments on stimulus generation of tone continuum and formant continuum validate the effectiveness of our proposed method in both objective and subjective evaluations.


## Speech samples

### /bei1/ to /bei4/ using WORLD
![](source/image/continuum_manual.png)

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world1.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train1.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train2.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world3.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train3.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world4.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train4.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world5.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train5.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world6.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train6.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world7.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train7.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world8.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train8.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world9.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train9.wav"></source>
  </audio>
</p>

<p>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/world10.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="source/audio/train10.wav"></source>
  </audio>
</p>

---


#### 1
<audio controls="controls">
<source type="audio/wav" src="source/audio/world1.wav"></source>
</audio>

#### 2
<audio controls="controls">
<source type="audio/wav" src="source/audio/world2.wav"></source>
</audio>

#### 3
<audio controls="controls">
<source type="audio/wav" src="source/audio/world3.wav"></source>
</audio>

#### 4
<audio controls="controls">
<source type="audio/wav" src="source/audio/world4.wav"></source>
</audio>

#### 5
<audio controls="controls">
<source type="audio/wav" src="source/audio/world5.wav"></source>
</audio>

#### 6
<audio controls="controls">
<source type="audio/wav" src="source/audio/world6.wav"></source>
</audio>

#### 7
<audio controls="controls">
<source type="audio/wav" src="source/audio/world7.wav"></source>
</audio>

#### 8
<audio controls="controls">
<source type="audio/wav" src="source/audio/world8.wav"></source>
</audio>

#### 9
<audio controls="controls">
<source type="audio/wav" src="source/audio/world9.wav"></source>
</audio>

#### 10
<audio controls="controls">
<source type="audio/wav" src="source/audio/world10.wav"></source>
</audio>


### /bei1/ to /bei4/ using our proposed methed
![](source/image/continuum_patch.png)

#### 1
<audio controls="controls">
<source type="audio/wav" src="source/audio/train1.wav"></source>
</audio>

#### 2
<audio controls="controls">
<source type="audio/wav" src="source/audio/train2.wav"></source>
</audio>

#### 3
<audio controls="controls">
<source type="audio/wav" src="source/audio/train3.wav"></source>
</audio>

#### 4
<audio controls="controls">
<source type="audio/wav" src="source/audio/train4.wav"></source>
</audio>

#### 5
<audio controls="controls">
<source type="audio/wav" src="source/audio/train5.wav"></source>
</audio>

#### 6
<audio controls="controls">
<source type="audio/wav" src="source/audio/train6.wav"></source>
</audio>

#### 7
<audio controls="controls">
<source type="audio/wav" src="source/audio/train7.wav"></source>
</audio>

#### 8
<audio controls="controls">
<source type="audio/wav" src="source/audio/train8.wav"></source>
</audio>

#### 9
<audio controls="controls">
<source type="audio/wav" src="source/audio/train9.wav"></source>
</audio>

#### 10
<audio controls="controls">
<source type="audio/wav" src="source/audio/train10.wav"></source>
</audio>
