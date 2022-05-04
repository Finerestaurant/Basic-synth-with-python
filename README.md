# Basic Synth

[Google Colaboratory](https://colab.research.google.com/drive/1sOwpxTez0zSEDkCzvUzMQVkL-5WgWeQY?hl=ko#scrollTo=Je7EsAKhWUjN)

I made simple algorithm with pitch information csv file and IPython display audio.

---

- **There’s four inputs.**

1. Scale selector. 
    - You can choose these two options.
        1. major 
        2. minor 
    
2. Keys. 
    - You can select root keys for scale. You can choose between C0 to B8. Input format must be follow example below.
        - C0
        - A4
        - C#0/Db0
        
3. Intervals. 
    - You can choose harmonic with numbers. Each number should be splited with space.
        - 1 3 5 7
        - 1 5 7 9
        - 1 8 13 14
        
4. Wave form.
    - You can use 3 wave forms.
        1. sine.
        2. sawtooth.
        3. square.

After you put all those four inputs, you will get 15 sec audio file with all those variables you set.

---

Here’s the result.

1. major
2. D3
3. 1 3 5 13
4. sine

[다운로드.wav](Basic%20Synth%20689bc7a6f17c4479ba1a7ff224ad2f07/%E1%84%83%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%AB%E1%84%85%E1%85%A9%E1%84%83%E1%85%B3.wav)

---

### Requirement

[pitch.csv](Basic%20Synth%20689bc7a6f17c4479ba1a7ff224ad2f07/pitch.csv)