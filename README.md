# UberConf 2019 Notes
This repository contains my notes from the sessions I attended at UberConf 2019. 

My notes are all in Jupyter notebook format, using various JVM language kernels like Java and Kotlin. You should be able to view the notebook even if you don't have the required kernels installed.

### Sessions
I attended the following sessions:
* [Collective Problem Solving in Music, Science, Art, and Software](collective-problem-solving.ipynb)
* [The Evolution of Java: 9, 10, 11, and 12](evolution-of-java.ipynb)
* [Extreme Spring Boot](extreme-spring-boot.ipynb)
* [Spring Boot: Application Management with Actuator](spring-boot-actuator.ipynb)
* [Architecture Foundations: Styles and Patterns](architecture-foundations.ipynb)
* [Securing Spring: REST and OAuth2](spring-security.ipynb)
* [Kafka as a Platform](kafka-as-a-platform.ipynb)
* [Meshing around with Istio](meshing-around-with-istio.ipynb)
* [Kotlin Fundamentals and Kotlin: Beyond the Basics](kotlin.ipynb)
* [Grokking Generics](grokking-generics.ipynb)
* [Core Software Design Principles](core-software-design-principles.ipynb)
* [Machine Learning: Natural Language Processing](natural-language-processing.ipynb)
* [Hacking and Hardening Java](hacking-and-hardening-java.ipynb)
* [On Being an Effective Developer](on-being-an-effective-developer.ipynb)

### Running these Notebooks
Several of these notebooks have code cells in them. You should be able to view them using GitHub or another notebook viewer, but if you'd like to actually run them you'll need to do some extra work to make the JVM languages runnable. You can install the requisite JVM language kernels using [BeakerX](http://beakerx.com/). I recommend the following process:

1. Install Anaconda
2. Create a new virtual environment named *beakerx* in Anaconda
4. Install BeakerX:
    ```
    conda install numpy
    conda install -c conda-forge ipywidgets beakerx
    ```
5. Start up Jupyter Notebook or Lab and you should see the various JVM language kernels in addition to Python.
