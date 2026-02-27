# Learning Roadmap

Suggested learning order for the Deep Understanding of Deep Learning course.
Notebooks marked with **[CC]** are Code Challenges.

---

## Phase 1: Foundations

### 1. Python Fundamentals (`python/`)
- DUDL_python_variables.ipynb
- DUDL_python_DataTypes.ipynb
- DUDL_python_indexSlice.ipynb
- DUDL_python_flowControl.ipynb
- DUDL_python_functions.ipynb
- DUDL_python_textVisualize.ipynb

### 2. Math for Deep Learning (`math/`)
- DUDL_math_derivatives1.ipynb
- DUDL_math_derivatives2.ipynb
- DUDL_math_dotproduct.ipynb
- DUDL_math_matrixMult.ipynb
- DUDL_math_transpose.ipynb
- DUDL_math_softmax.ipynb
- DUDL_math_log.ipynb
- DUDL_math_entropy.ipynb
- DUDL_math_argmin.ipynb
- DUDL_math_meanvar.ipynb
- DUDL_math_randomseed.ipynb
- DUDL_math_sampling.ipynb
- DUDL_math_ttest.ipynb

### 3. Gradient Descent (`gradientDescent/`)
- DUDL_GradientDescent_1D.ipynb
- DUDL_GradientDescent_2D.ipynb
- DUDL_GradientDescent_experiment.ipynb
- **[CC]** DUDL_GradientDescent_codeChallenge_lr.ipynb
- **[CC]** DUDL_GradientDescent_CodeChallengeStartValue.ipynb

---

## Phase 2: Core Neural Networks

### 4. Artificial Neural Networks (`ANN/`)
- DUDL_ANN_regression.ipynb
- DUDL_ANN_multilayer.ipynb
- DUDL_ANN_classifyQwerties.ipynb
- DUDL_ANN_learningrates.ipynb
- DUDL_ANN_nHiddenUnits.ipynb
- DUDL_ANN_numParameters.ipynb
- DUDL_ANN_breadthVsDepth.ipynb
- DUDL_ANN_seqVsClass.ipynb
- DUDL_ANN_multioutput.ipynb
- **[CC]** DUDL_ANN_codeChallenge_regression.ipynb
- **[CC]** DUDL_ANN_codeChallengeQwerties.ipynb
- **[CC]** DUDL_ANN_codeChallengeSeq2class.ipynb

### 5. Overfitting (`overfitting/`)
- DUDL_overfitting_regression.ipynb
- DUDL_overfitting_trainDevsetTest.ipynb
- DUDL_overfitting_manual.ipynb
- DUDL_overfitting_scikitlearn.ipynb
- DUDL_overfitting_dataLoader.ipynb

### 6. Metaparameters (`metaparams/`)
- DUDL_metaparams_loss.ipynb
- DUDL_metaparams_ActivationFuns.ipynb
- DUDL_metaparams_ActivationComparisons.ipynb
- DUDL_metaparams_optimizersComparison.ipynb
- DUDL_metaparams_momentum.ipynb
- DUDL_metaparams_learningRateDecay.ipynb
- DUDL_metaparams_batchNorm.ipynb
- DUDL_metaparams_intro2winedata.ipynb
- DUDL_metaparams_multioutput.ipynb
- **[CC]** DUDL_metaparams_CodeChallengeRelus.ipynb
- **[CC]** DUDL_metaparams_codeChallengeDropout.ipynb
- **[CC]** DUDL_metaparams_CodeChallengeAdamL2.ipynb
- **[CC]** DUDL_metaparams_CodeChallenge_sugar.ipynb
- **[CC]** DUDL_metaparams_CodeChallengeBatches.ipynb
- **[CC]** DUDL_metaparams_CodeChallengeOptimizers.ipynb

### 7. Data Handling (`data/`)
- DUDL_data_data2colab.ipynb
- DUDL_data_datasetLoader.ipynb
- DUDL_data_featureAugmentation.ipynb
- DUDL_data_noiseAugmentation.ipynb
- DUDL_data_oversampling.ipynb
- DUDL_data_saveLoadModels.ipynb
- DUDL_data_saveTheBest.ipynb
- DUDL_data_dataVsDepth.ipynb
- **[CC]** DUDL_data_CodeChallengeUnbalanced.ipynb

### 8. Measuring Performance (`measurePerformance/`)
- DUDL_measurePerformance_APRF.ipynb
- DUDL_measurePerformance_APRFexample1.ipynb
- DUDL_measurePerformance_example2.ipynb
- DUDL_measurePerformance_time.ipynb
- **[CC]** DUDL_measurePerformance_codeChallenge_unequal.ipynb

---

## Phase 3: Feed-Forward Networks in Practice

### 9. FFN on MNIST (`FFN/`)
- DUDL_FFN_aboutMNIST.ipynb
- DUDL_FFN_FFNonMNIST.ipynb
- DUDL_FFN_scrambledMNIST.ipynb
- DUDL_FFN_shiftedMNIST.ipynb
- DUDL_FFN_weightHistograms.ipynb
- **[CC]** DUDL_FFN_CodeChallenge_binMNIST.ipynb
- **[CC]** DUDL_FFN_CodeChallenge_missing7.ipynb
- **[CC]** DUDL_FFN_CodeChallenge_normalization.ipynb
- **[CC]** DUDL_FFN_CodeChallengeBreadthDepth.ipynb
- **[CC]** DUDL_FFN_CodeChallenge_optimizers.ipynb

### 10. FFN Milestone Projects (`FFNmilestone/`)
- DUDL_FFNmilestone_project1.ipynb
- DUDL_FFNmilestone_project2.ipynb
- DUDL_FFNmilestone_project3.ipynb

---

## Phase 4: Training Deep Networks

### 11. Weight Initialization (`weights/`)
- DUDL_weights_matrixsizes.ipynb
- DUDL_weights_demoinits.ipynb
- DUDL_weights_XavierKaiming.ipynb
- DUDL_weights_weightchanges.ipynb
- DUDL_weights_freezeWeights.ipynb
- **[CC]** DUDL_weights_codeChallenge_identicalRandom.ipynb
- **[CC]** DUDL_weights_codeChallenge_weightstd.ipynb
- **[CC]** DUDL_weights_CodeChallenge_XavierKaiming.ipynb

### 12. Regularization (`regularization/`)
- DUDL_regular_L1regu.ipynb
- DUDL_regular_L2regu.ipynb
- DUDL_regular_dropout.ipynb
- DUDL_regular_dropoutInPytorch.ipynb
- DUDL_regular_dropout_example2.ipynb
- DUDL_regular_minibatch.ipynb
- DUDL_regular_testBatchT2.ipynb
- **[CC]** DUDL_regular_codeChallenge_minibatch.ipynb

---

## Phase 5: Convolutional Neural Networks

### 13. Convolution Operations (`convolution/`)
- DUDL_convolution_conv2.ipynb
- DUDL_convolution_conv2transpose.ipynb
- DUDL_convolution_convInCode.ipynb
- DUDL_convolution_meanMaxPool.ipynb
- DUDL_convolution_transforms.ipynb
- DUDL_convolution_customDataSet.ipynb
- **[CC]** DUDL_convolution_codeChallenge.ipynb

### 14. CNNs (`CNN/`)
- DUDL_CNN_CNN4MNIST.ipynb
- DUDL_CNN_EMNIST.ipynb
- DUDL_CNN_shiftedMNIST.ipynb
- DUDL_CNN_GaussClass.ipynb
- DUDL_CNN_GaussClassFeatureMaps.ipynb
- DUDL_CNN_GaussAE.ipynb
- DUDL_CNN_findGauss.ipynb
- **[CC]** DUDL_CNN_codeChallengeSoftcoding.ipynb
- **[CC]** DUDL_CNN_codeChallengeNumChans.ipynb
- **[CC]** DUDL_CNN_CodeChallengeLinearUnits.ipynb
- **[CC]** DUDL_CNN_codeChallengeCustomLoss.ipynb
- **[CC]** DUDL_CNN_CodeChallengeAEocclusion.ipynb
- **[CC]** DUDL_CNN_codeChallengeBeatThis.ipynb

### 15. CNN Milestone Projects (`CNNmilestone/`)
- DUDL_CNNmilestone_project1.ipynb
- DUDL_CNNmilestone_project2.ipynb
- DUDL_CNNmilestone_project3.ipynb
- DUDL_CNNmilestone_project4.ipynb

---

## Phase 6: Advanced Architectures

### 16. Recurrent Neural Networks (`RNN/`)
- DUDL_RNN_intro2RNN.ipynb
- DUDL_RNN_LSTMGRU.ipynb
- DUDL_RNN_altSequences.ipynb
- DUDL_RNN_loremipsum.ipynb
- **[CC]** DUDL_RNN_codeChallenge_SineExtrapolate.ipynb

### 17. Autoencoders (`autoencoders/`)
- DUDL_autoenc_MNISTlatentCode.ipynb
- DUDL_autoenc_denoisingMNIST.ipynb
- DUDL_autoenc_occlusion.ipynb
- DUDL_autoenc_tiedWeights.ipynb
- **[CC]** DUDL_autoenc_codeChallenge_Nunits.ipynb

### 18. GANs (`GANs/`)
- DUDL_GAN_MNIST.ipynb
- DUDL_GAN_CNNganGaus.ipynb
- DUDL_GAN_CNNganFMNIST.ipynb
- **[CC]** DUDL_GAN_codeChallengeGaus.ipynb
- **[CC]** DUDL_GAN_codeChallengeFMNIST.ipynb
- **[CC]** DUDL_GAN_codeChallengeCIFAR.ipynb
- **[CC]** DUDL_GAN_codeChallengeFaces.ipynb

---

## Phase 7: Production & Applied Topics

### 19. GPU Computing (`GPU/`)
- DUDL_GPU_implement.ipynb
- **[CC]** DUDL_GPU_CodeChallenge2GPU.ipynb

### 20. Transfer Learning (`transferlearning/`)
- DUDL_transfer_MNISTtoFMNIST.ipynb
- DUDL_transfer_pretrainFMNIST.ipynb
- DUDL_transfer_PretrainCIFAR.ipynb
- DUDL_transfer_resnet.ipynb
- **[CC]** DUDL_transfer_codeChallengeVGG16.ipynb
- **[CC]** DUDL_transfer_codeChallenge_letters2numbers.ipynb

### 21. Style Transfer (`styletransfer/`)
- DUDL_style_screamingBathtub.ipynb
- **[CC]** DUDL_style_codeChallengeAlexNet.ipynb
