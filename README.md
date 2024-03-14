# TextGenerator
- This is a tool for ocr dataset, text detection, fonts classification dataset generate.

## Functions：
- different font, size, color, rotation
- multithreading
- specific layout
- find smooth area to attach
- character-wised annotation

### image generated:

![](img/pic_7f6cb78368edaf8347a8f0ce7e5a46c2df4f3ddd.jpg)

### image attach:

![](img/fragment_6fc1b6ac180755dea3dfe711550251708b5e2ce519.jpg)

![](img/fragment_178b7da018e0d84c80b1455be4cc099bc68a07271.jpg)

![](img/fragment_ca71322eec0332fb3f6bb2a213c22f4a183c69da7.jpg)

![](img/fragment_f712bd7187d446b5fd5daf0ee0c6cb33ad26f98710.jpg)

### rotation

![](img/rotate_rect.png)

### bounding box of single word

![](img/char_box.png)
        
    ```
    # step 1
    pip install requirements.txt
    # step 2
    sh make.sh
    ```
  
- config file
    `config.yml`
    
- run script

    ```
    python3 run.py
    ```
  
- data generated
    `config.yml` -> `provider> layout> out_put_dir`
     
## content modified
1. np.int related
2. check the piplist.txt for package version

## todo:
Math generation and manipulation for formula detection task