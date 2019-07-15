# MLsploit Tutorial Webpage

To add a module, you will need to edit the `_data/modules.yml` file. 
You can copy-paste information from an existing module and modify it accordingly.
For example, here's what data for one module looks like:
```yaml
- title: "SHIELD: Fast, Practical Defense and Vaccination for Deep Learning using JPEG Compression"
  authors: "Nilaksh Das, Madhuri Shanbhogue, Shang-Tse Chen, Fred Hohman, Siwei Li, Li Chen, Michael E. Kounavis, Duen Horng Chau"
  venue: "24th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD 2018)"
  venue-shorthand: KDD'18
  year: 2018

  paper-home: "https://poloclub.github.io/jpeg-defense/"
  award: Audience Appreciation Award, Runner-up
  pdf: "https://arxiv.org/abs/1802.06816"
  github: "https://www.github.com/poloclub/jpeg-defense"
  youtube: "https://youtu.be/zUB2-i7rSb4"
  slides: "#"

  icon: shield.jpg
  icon-fit: cover
  brand: SHIELD
  tagline: Fast, Practical Defense for Deep Learning
  summary: |
    SHIELD addresses the urgent need for practical defense that can be readily deployed to combat attacks in real-time. It places JPEG compression at the core of our proposed SHIELD defense framework, utilizing its capability to effectively "compress away" such pixel manipulation. 
    
    <ul>
    <li>SHIELD "vaccinates" a model by re-training it with compressed images, where different compression levels are applied to generate multiple vaccinated models that are ultimately used together in an ensemble defense.</li>
    
    <li>SHIELD adds an additional layer of protection by employing randomization at test time that compresses different regions of an image using random compression levels, making it harder for an adversary to estimate the transformation performed.</li>

    <li>Extensive large-scale experiments using the ImageNet dataset shows that SHIELD eliminates up to 94% of black-box attacks and 98% of gray-box attacks delivered by the recent, strongest attacks, such as Carlini-Wagner's L2 and DeepFool.</li>
    
    <li>SHIELD's novel fortified multi-pronged approach is fast and works without requiring knowledge about the model.</li>
    </ul>
    
  bibtex: |
    @article{das2018shield,
      title={SHIELD: Fast, Practical Defense and Vaccination for Deep Learning using JPEG Compression},
      author={Das, Nilaksh and Shanbhogue, Madhuri and Chen, Shang-Tse and Hohman, Fred and Li, Siwei and Chen, Li and Kounavis, Michael E and Chau, Duen Horng},
      booktitle={Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining},
      year={2018},
      organization={ACM}
    }
```
