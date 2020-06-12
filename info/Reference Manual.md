# Libra Reference Manual  

Libra is an open source deep learning API that provides a toolkit of intuitive and easily accessible machine learning methods, enabling users to streamline their data science workflows. The reference manual contains a detailed description of the Libra API. This reference delineates each of the methods avaiable for use, explaining how one can utilize them as well their respective parameters. The manual assumes that you have a baseline comprehension of some of the key concepts in machine learning. The reference is organized mainly in terms of location in the code where the method was defined as well as in accordance with OOP hierarchy, with a class introduced first and then its methods appearing underneath.
***

Table of Contents
=================

* [dataset_labelmatcher.py](#dataset_labelmatcher)
   * [produceMask](#produceMask)
   * [get_similar_column](#get_similar_column)
   * [get_similar_model](#get_similar_model)
* [grammartree.py](#grammartree)
   * [get_value_instruction](#get_value_instruction)
* [regression_split_functions.py](#regression_split_functions)
   * [initializer](#initializer)
   * [preprocesser](#preprocesser)
   * [instruction_identifier](#instruction_identifier)
   * [set_splitter](#set_splitter)
   * [modeler](#modeler)
   * [plotter](#plotter)
* [predictionModelCreation.py](#predictionModelCreation)
   * [get_keras_model_reg](#get_keras_model_reg)
   * [get_keras_model_class](#get_keras_model_class)
   * [get_keras_text_class](#get_keras_text_class)
   * [getKerasConvolutional](#getKerasConvolutional)
* [tuner.py](#tuner)
   * [class CNNHyperModel](#class-CNNHyperModel)
      * [__init__](#__init__-CNNHyperModel)
      * [build](#build)
   * [tuneReg](#tuneReg)
   * [build_model](#build_model)
   * [tuneClass](#tuneClass)
   * [tuneCNN](#tuneCNN)  
* [generatePlots.py](#generatePlots)
  * [generate_clustering_plots](#generate_clustering_plots)
  * [generate_regression_plots](#generate_regression_plots)
  * [generate_classification_plots](#generate_classification_plots)
  * [generate_classification_together](#generate_classification_together)
  * [plot_loss](#plot_loss)
  * [plot_corr](#plot_corr)
  * [plot_acc](#plot_acc)
* [NLP_preprocessing.py](#NLP_preprocessing)
  * [lemmatize_text](#lemmatize_text)
  * [tokenize_text](#tokenize_text)
  * [text_clean_up](#text_clean_up)
* [data_preprocesser.py](#data_preprocesser)
  * [initial_preprocesser](#initial_preprocesser)
  * [structured_preprocesser](#structured_preprocesser)
  * [image_preprocess](#image_preprocess)
  * [processColorChanel](#processColorChanel)
  * [process_dates](#process_dates)
* [data_reader.py](#data_reader)
  * [class DataReader](#class-DataReader)
    * [__init__](#__init__-DataReader)
    * [retrieve_extension](#retrieve_extension)
    * [data_generator](#data_generator)
* [dimensionality_red_queries.py](#dimensionality_red_queries)
  * [logger](#logger)
  * [dimensionality_reduc](#dimensionality_reduc)
  * [dimensionality_RF](#dimensionality_RF)
  * [dimensionality_PCA](#dimensionality_PCA)
  * [dimensionality_ICA](#dimensionality_ICA)
  * [get_last_file](#get_last_file)
* [predictionQueries.py](#predictionQueries)
  * [clearLog](#clearLog)
  * [class client](#class-client)
    * [__init__](#__init__-client)
    * [get_models](#get_models)
    * [predict](#predict)
    * [neural_network_query](#neural_network_query)
    * [regression_query_ann](#regression_query_ann)
    * [classification_query_ann](#classification_query_ann)
    * [kmeans_clustering_query](#kmeans_clustering_query)
    * [svm_query](#svm_query)
    * [nearest_neighbor_query](#nearest_neighbor_query)
    * [decision_tree_query](#decision_tree_query)
    * [allClassQuery](#allClassQuery)
    * [tune](#tune)
    * [stat_analysis](#stat_analysis)
    * [convolutional_query](#convolutional_query)
    * [encode_text](#encode_text)
    * [predict_text_sentiment](#predict_text_sentiment)
    * [text_classification_query](#text_classification_query)
    * [dimensionality_reducer](#dimensionality_reducer)
    * [show_plots](#show_plots)

***

## dataset_labelmatcher ##

### produceMask ###

### get_similar_column ###

### get_similar_model ###

***

## grammatree ##

### get_value_instruction ###

***

## regression_split_functions ##
   
### initializer ###
   
### preprocesser ###
   
### instruction_identifier ###
   
### set_splitter ###
   
### modeler ###
   
### plotter ###

***

## predictionModelCreation ##

### get_keras_model_reg ###

### get_keras_model_class ###
   
### get_keras_text_class ###
   
### getKerasConvolutional ###

***

## tuner ##

### class CNNHyperModel ###

#### __init__-CNNHyperModel ####

#### build ####

#### tuneReg ####

#### build_model ####

#### tuneClass ####

#### tuneCNN ####  

***

## generatePlots ##

### generate_clustering_plots ###

### generate_regression_plots ###

### generate_classification_plots ###

### generate_classification_together ###

### plot_loss ###

### plot_corr ###

### plot_acc ###

***

## NLP_preprocessing ##

### lemmatize_text ###

### tokenize_text ###

### text_clean_up ###

***

## data_preprocesser ##

### initial_preprocesser ###

### structured_preprocesser ###

### image_preprocess ###

### processColorChanel ###

### process_dates ###

***

## data_reader ##
  
### class-DataReader ###
    
#### __init__-DataReader ####
    
#### retrieve_extension ####
    
#### data_generator ####

***

## dimensionality_red_queries ##
  
### logger ###
 
### dimensionality_reduc ###
  
### dimensionality_RF ###

### dimensionality_PCA ###

### dimensionality_ICA ###

### get_last_file ###

***

## predictionQueries ##

### clearLog ###

### class-client ###

#### __init__-client ####

#### get_models ####

#### predict ####

#### neural_network_query ####
    
#### regression_query_ann ####
    
#### classification_query_ann ####
    
#### kmeans_clustering_query ####
    
#### svm_query ####
    
#### nearest_neighbor_query ####
    
#### decision_tree_query ####
    
#### allClassQuery ####
    
#### tune ####
    
#### stat_analysis ####
    
#### convolutional_query ####
    
#### encode_text ####
    
#### predict_text_sentiment ####
    
#### text_classification_query ####
  
#### dimensionality_reducer ####
    
#### show_plots ####