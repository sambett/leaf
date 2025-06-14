# Plant Disease Classification Using Deep Learning

A comprehensive research project demonstrating advanced transfer learning strategies for agricultural disease detection. This project compares VGG16 and ResNet50 architectures using multiple transfer learning approaches on a small dataset of plant disease images.

## 🌟 Project Overview

This research explores the effectiveness of different transfer learning strategies for plant disease classification, achieving **98% accuracy** with optimized VGG16 architecture. The project provides valuable insights for deep learning applications on small datasets and agricultural AI systems.

### Key Achievements

- **98% Test Accuracy** using VGG16 with partial freezing strategy
- **Comprehensive Analysis** of transfer learning approaches
- **Professional Research Presentation** with interactive web interface
- **Practical Recommendations** for small dataset classification

## 📊 Dataset

- **Source**: Kaggle Plant Disease Dataset
- https://www.youtube.com/watch?v=bDs9qIJ9UgA
- **Total Images**: 1,530
- **Classes**: 3 (Healthy, Powdery, Rust)
- **Split**: Pre-divided into train/validation/test sets
- **Format**: RGB images of plant leaves

## 🧠 Methodology

### Transfer Learning Strategies Evaluated

1. **Full Training**: All layers trainable
   - Accuracy: 96.67%
   - Risk: Overfitting on small datasets

2. **Partial Freezing**: Early layers frozen, later layers trainable ⭐
   - Accuracy: **98.00%** (Best Performance)
   - Optimal balance between feature preservation and adaptation

3. **Full Freezing**: Only classifier trainable
   - Accuracy: 87.33%
   - Limited domain adaptation

### Architecture Comparison

| Model | Accuracy | Parameters | Complexity | Best Use Case |
|-------|----------|------------|------------|---------------|
| **VGG16** | **98%** | 138M | Moderate | Small datasets |
| **ResNet50** | 62% | 25.6M | High | Large datasets |

## 🚀 Key Findings

1. **Partial Freezing is Optimal**: For small datasets, partial freezing provides the best balance between preserving pre-trained features and domain adaptation.

2. **Architecture Complexity Matters**: Simpler architectures (VGG16) outperform complex models (ResNet50) on limited datasets due to reduced overfitting risk.

3. **Comprehensive Evaluation Essential**: Accuracy alone is insufficient; confusion matrices and per-class metrics are crucial for reliable assessment.

4. **Data Augmentation Benefits**: Strategic augmentation improves performance by 2.67% and enhances training stability.


## 🌐 Interactive Demo

### Live Website Features

- **Responsive Design**: Optimized for all devices
- **Interactive Navigation**: Smooth scrolling between sections
- **Professional Styling**: Modern botanical theme with animations
- **Comprehensive Content**: Detailed methodology, results, and analysis

### Access the Demo

1. **Live Classifier**: Test the model with your images
   - URL:(https://github.com/sambett/leaf_classification).
   
2. **Video Demonstration**: Watch the classification system in action
   - YouTube: Complete walkthrough and real-time predictions
   - (https://www.youtube.com/watch?v=bDs9qIJ9UgA).
   
3. **Source Code**: Access the complete implementation
   - GitHub: [Plant Disease Recognition Repository](https://github.com/sambett/leaf_classification.git)

## 📖 Research Paper

The complete academic paper includes:
- Detailed mathematical formulations
- Statistical analysis and graphs
- Confusion matrices and performance metrics
- Literature review and related work
- Future research directions

**Download**: [Full Research Paper PDF](Plant_Disease_Classification_Using_Deep_Learning_strategy _analysis.pdf)


### For Small Dataset Classification:

1. **Choose Transfer Learning**: Always prefer pre-trained models over custom CNNs
2. **Use Partial Freezing**: Optimal strategy for small datasets
3. **Select Appropriate Architecture**: Favor simpler models (VGG-style) over very deep networks
4. **Apply Data Augmentation**: Strategic augmentation improves performance and stability
5. **Implement Comprehensive Metrics**: Use confusion matrices and balanced evaluation metrics

## 👨‍💻 Author

**Selma Bettayeb**
- Research Focus: Deep Learning for Agricultural Applications
- Specialization: Transfer Learning strategies and small datasets challenges
- Institution: Fss faculty of science sfax
- Contact: sbettaie56@gmail.com

## 🤝 Collaborators

- **Dr. Emna FENDRI**: Research Supervisor
- **Dr. Sahar DAMMAK**: Research Supervisor



## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Kaggle for providing the plant disease dataset
- The open-source community for deep learning frameworks
- Agricultural research community for domain expertise
- Academic supervisors for guidance and support

---

**🌱 "Empowering agriculture through AI-driven plant disease detection"**

For questions, suggestions, or collaborations, please open an issue or contact the research team.
