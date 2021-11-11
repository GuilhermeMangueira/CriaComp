
# Passo a passo para Gerar Imagens
1. Abrir o [colab](https://colab.research.google.com/github/GuilhermeMangueira/CriaComp/blob/main/VQGAN%2BCLIP_(with_pooling)_ipynb%22.ipynb)
2. Rodar todos os blocos de código 
    - No bloco de 'Selection of models to download', selecione os modelos que quer baixar, eles serão os que serão usados mais a diante (eles ocupam espaço do HD do colab, evite baixar todos)
   - No bloco de 'Settings for this run' você pode colocar as configurações de execução

3.Variaveis
- 'text' é o promt de entrada, ou seja, o texto que a AI utilizará para criar ou alterar a imagem
    - 'width' e 'height' mudam o tamanho da imagem de saída
    - 'model' deve ser um dos modelos selecionados no bloco 'Selection of models to download'
    - 'images_interval' é representa o intervalo entre as imagens geradas que será exibido em tela (nos arquivos do Colab, existe uma pasta chamada 'Steps' onde todas as imagens geradas ficam
    - 'init_image' Opcional, caso você insira a AI gerará imagens partindo desta imagem utilizando o promt inserido em 'text'
    - 'target_images' Opcional, caso você insira a AI gerará imagens tentando chegar nesta imagem utilizando o prompt inserido em 'text'
    - 'seed' apenas um atributo para poder "randomizar' o resultado, para reproduzir uma geração é necessario o mesmo seed
    - 'max_iterations' é o numero de imagens que serão geradas no total
    - 'learning_rate' é o quanto as imagens evoluem entre cada geração. Valores baixos (0.01 por exemplo) geram resultados melhores que valores altos (0.3 por exemplo)

# As imagens dessa galeria foram geradas usando as configurações abaixo

## Armas
  1.[Axe](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/axe_lava-axe-Quantum%20wavetracing_it100.png)
  - Iterações: 100
  - step_size: 0.03
  - model: imagenet_16384
  - texts: lava | axe | Quantum wavetracing
  - seed: 42
  - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/axe_original.png)
  
  2.[Bow](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/bow_fire-bow%20and%20arrow%20in%20flames-Sunrays%20shine%20upon%20it_it150.png)
  - iterações: 150
  - step_size:  0.03
  - model: imagenet_16384
  - texts: fire | bow and arrow in flames | Sunrays shine upon it
  - seed: 42
  - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/bow_original.png)

  3.[Bow Arrow](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/bow-arrow_wolf-matte-painting_it125.png)
  - Iterações: 125
  - step_size: 0.03
  - model: imagenet_16384
  - texts: wolf bow and arrow matte painting
  - seed: 42
  - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/bow-arrow_original.jpeg)

  4.[Gun](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/gun_diamond-made-crystals-it57.png)
  - Iterações: 57
  - step_size: 0.03
  - model: imagenet_16384
  - texts: Diamond Gun made of crystals Ultra HD
  - seed: 42
  - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/gun_original.jpg)
  
  5.[Sword Fire](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/sword_made-of-fire_it100.png)
   - Iterações: 250
   - step_size: 0.03
   - model: wikiart_16384
   - texts: made of fire
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/sword_original.jpg)

  6.[Sword covered in fire](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/sword_shiny-metal-blade-covered-in-fire_it100.png)
   - Iterações: 250
   - step_size: 0.03
   - model: wikiart_16384
   - texts: shiny metal blade covered in fire
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/sword_original.jpg)

  7.[Sword Lightning](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/sword_sword-of-the-thunder-god%20%20lightning_it250.png)
   - Iterações: 250
   - step_size: 0.03
   - model: wikiart_16384
   - texts: sword of the thunder god | lightning
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/sword_original.jpg)
  
  8.[Whip](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/whip_snake%20whip-Marvel%20Comics_it100.png)
   - Iterações: 100
   - step_size: 0.03
   - model: imagenet_16384
   - texts: snake whip | Marvel Comics
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Armas/whip_original.png)


## Equipamentos
  1.[Armour Holographic](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/armour_holographic%20%20cyberpunk_it150.png)
   - Iterações: 250
   - step_size: 0.014
   - model: wikiart_16384
   - texts: holographic | cyberpunk
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/armour_original.jpg)
  
  2.[Armour Translucent](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/armour_translucent%20%20invisible-armor_it250.png)
   - Iterações: 250
   - step_size: 0.018
   - model: wikiart_16384
   - texts: translucent | invisible armor
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/armour_original.jpg)

  3.[Boots](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/boots_4k-image-of-boots-made-of-scales_it80.jpg)
   - Iterações: 200
   - step_size: 0.01
   - model: wikiart_16384
   - texts: 4k image of boots made of scales
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/boots_original.png)

  4.[Shield Moss](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/shield_stone-shield-covered-in-moss_it225.jpg)
   - Iterações: 250
   - step_size: 0.02
   - model: wikiart_16384
   - texts: stone shield covered in moss
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Equipamentos/shield_original.jpg)

## Acessórios

  1.[Belt](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/belt_iron-holographic_it200.png)
  - Iterações: 200
  - step_size: 0.03
  - model: imagenet_16384
  - texts: belt | iron | holographic
  - seed: 42
  - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/belt_original.jpeg)

  2.[Crown of Vines](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/crown_4k-image-of_crown-made-of-branches-and-gemstones_30.png)
   - Iterações: 200
   - step_size: 0.01
   - model: wikiart_16384
   - texts: 4k image of crown made of branches and gemstones
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/crown_original.jpg)
   
   3.[Medallion](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/medallion_Mysterious%20Medallion%20made%20of%20vines%20Wiccan_it25.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: Mysterious Medallion made of vines Wiccan 
   - seed: 1376
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/medallion_original.jpeg)

  4.[Ring](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/ring_4k-image-of-ring-made-of-crystals_it30.jpg)
   - iterações: 250
   - step_size: 0.012
   - model: wikiart_16384
   - texts: ring made of smoke | oozing purple gas
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/ring_original.png)
   
   5.[Ring](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Acess%C3%B3rios/transparent-ring_typhoon-made-mist-photoillustration_it125.png)
   - Iterações: 125
   - step_size: 0.03
   - model: imagenet_16384
   - texts: typhoon ring made of mist photoillustration
   - init_image: transparent_ring.jpg
   - seed: 42

## Outros

  1.[Alfaia](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/alfaia_earth-drum-made-vines_it150.png)
   - Iterações: 150
   - step_size: 0.04
   - model: imagenet_16384
   - texts: Earth Drum | Made of vines
   - seed: 42
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/alfaia_original.jpg)
   
   2.[Banjo](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/banjo_banjo%20ice%20machine-spikes-Skeuomorphic_it100.png)
   - Iterações: 100
   - step_size: 0.03
   - model: imagenet_16384
   - texts: banjo ice machine | spikes | Skeuomorphic
   - seed: 42
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/banjo_original.png)

   3.[Book iridiscent](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book-2_magical-book-iridescent_it50.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: magical book iridescent 
   - seed: 1376
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book_original2.png)

   4.[Book Aurora](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book2_cosmic%20%20aurora-borealis_it150.png)
   - Iterações: 250
   - step_size: 0.015
   - model: wikiart_16384
   - texts: cosmic | aurora borealis
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book2_original.jpg)

   5.[Book Of dead](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book_4k-image-of-the-book-of-the-dead-by-HR-Geiger_it210.png)
   - Iterações: 200
   - step_size: 0.01
   - model: wikiart_16384
   - texts: 4k image of the book of the dead by HR Geiger
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book_original.png)

   6.[Book of Grass](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book_book-cover-made-of-grass_it200.png)
   - Iterações: 250
   - step_size: 0.015
   - model: wikiart_16384
   - texts: book cover made of grass
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/book_original.jpg)

   7.[Cassete Tape](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/cassettetape_Cassette%20tape%20Made%20of%20liquid%20metal%20holographic_it125.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: Cassette tape Made of liquid metal holographic
   - seed: 1376
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/cassettetape_original.png)

  8.[Floppy Disk](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/floppydisk_Mystical%20floppy%20disk%20flickering%20light_it150.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: Mystical floppy disk flickering light
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/floopydisk_original.png)
   - seed: 1376

   9.[Key](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/key_magical%20Key%20Parallax%20Quantum%20wavetracing_it25.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: magical Key Parallax Quantum wavetracing
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/key_original.png)
   - seed: 1376

  10.[Ring of smoke](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/ring_ring-made-of-smoke%20%20oozing-purple-gas_i200.png)
    - Iterações: 250
    - step_size: 0.012
    - model: wikiart_16384
    - texts: ring made of smoke | oozing purple gas
    - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/ring_original.jpg)
    
  11.[Teacup](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/teacup_Mysterious%20hot%20tea%20smoke%20beverage_it100.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: Mysterious hot tea smoke beverage
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/teacup_original.jpeg)
   - seed: 1376
    
  12.[Typewriter](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/typewriter_Typewriter%20Made%20of%20crystals%20Sunrays%20shine%20upon%20it_it50.png)
   - iterações 200
   - step_size:  0.1
   - model: wikiart_16384
   - texts: Typewriter Made of crystals Sunrays shine upon it
   - [init_image](https://github.com/GuilhermeMangueira/CriaComp/blob/main/Galeria/Outros/typewriter_original.jpeg)
   - seed: 1376
