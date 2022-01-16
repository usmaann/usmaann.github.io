---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Selected Publications**

Please visit my [Google Scholar](https://scholar.google.com.au/citations?user=61Ou1P8AAAAJ&hl=en) page for a detailed list of my publications, including citations count.

**Conference papers**
1. Jahan, Sadia, Md Rafiqul Islam, Khan Md Hasib, **Usman Naseem**, and Md Saiful Islam. "Active Learning with an Adaptive Classifier for Inaccessible Big Data Analysis." In 2021 International Joint Conference on Neural Networks (IJCNN), pp. 1-7. IEEE, 2021.

2. **Naseem, Usman**, Matloob Khushi, Jinman Kim and Adam Dunn, "Classifying vaccine sentiment tweets by modelling domain-specific representation and commonsense knowledge into context-aware attentive GRU," 2021 International Joint Conference on Neural Networks (IJCNN), 2021, pp. 1-8, 

3. **Naseem, Usman**, Matloob Khushi, Vinay Reddy, Sakthivel Rajendran, Imran Razzak, and Jinman Kim. "Bioalbert: A simple and effective pre-trained language model for biomedical named entity recognition." In 2021 International Joint Conference on Neural Networks (IJCNN), pp. 1-7. IEEE, 2021.

4. Khushi, Matloob, **Usman Naseem**, Jonathan Du, Anis Khan, and Simon K. Poon. "Data mining encode data predicts a significant role of sina3 in human liver cancer." In International Conference on Neural Information Processing, pp. 15-25. Springer, Cham, 2020.

5. Panta, Adhish, Matloob Khushi, **Usman Naseem**, Paul Kennedy, and Daniel Catchpoole. "Classification of neuroblastoma histopathological images using machine learning." In International Conference on Neural Information Processing, pp. 3-14. Springer, Cham, 2020.

6. Thapa, Surendrabikram, Surabhi Adhikari, **Usman Naseem**, Priyanka Singh, Gnana Bharathy, and Mukesh Prasad. "Detecting Alzheimer’s disease by exploiting linguistic information from Nepali transcript." In International Conference on Neural Information Processing, pp. 176-184. Springer, Cham, 2020.

7. **Naseem, Usman**, Matloob Khushi, Shah Khalid Khan, Nazar Waheed, Adnan Mir, Atika Qazi, Bandar Alshammari, and Simon K. Poon. "Diabetic Retinopathy Detection Using Multi-layer Neural Networks and Split Attention with Focal Loss." In International Conference on Neural Information Processing, pp. 26-37. Springer, Cham, 2020.

8. **Naseem, Usman**, Katarzyna Musial, Peter Eklund, and Mukesh Prasad. "Biomedical named-entity recognition by hierarchically fusing biobert representations and deep contextual-level word-embedding." In 2020 International Joint Conference on Neural Networks (IJCNN), pp. 1-8. IEEE, 2020.

9. **Naseem, Usman**, Katarzyna Musial, Peter Eklund, and Mukesh Prasad. "Biomedical named-entity recognition by hierarchically fusing biobert representations and deep contextual-level word-embedding." In 2020 International Joint Conference on Neural Networks (IJCNN), pp. 1-8. IEEE, 2020.

10. **Naseem, Usman**, and Katarzyna Musial. "DICE: Deep Intelligent Contextual Embedding for Twitter Sentiment Analysis." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 953-958. IEEE Computer Society, 2019.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
