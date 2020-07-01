<div class="<h2>DESCRIPTION:</h2>">
  .text-white on .bg-green-light
 </div>


The idea behind this project is to predict the 'chance of admit' during filing an application for Master studies.</br>
The important parameters that are considered during this process are:</br>
1. GRE Score</br>
2. TOEFL Score</br>
3. University rating</br>
4. Statement of purpose</br>
5. CGPA</br>
6. Research Experience</br>
7. Chance of admit</br>
<hr> </hr>


<h3> 1. GRE </h3>

The Graduate Record Examination is a standarized exam, often required for admission to graduate and MBA programs globally. It's made up of three components:</br>

1. Analytical Writing (Scored on a 0-6 scale in half-point increments)</br>
2. Verbal Reasoning (Scored on a 130-170 scale)</br>
3. Quantitative Reasoning (Scored on a 130-170 scale)</br>

Considering the dataset we have in our hands, graph of distributed GRE Scores of Applicants is:</br>

![download (2)](https://user-images.githubusercontent.com/38138793/86228672-47b47800-bbac-11ea-9a24-3bd1b82deaf4.png)
<hr> </hr>

<h3> 2. TOEFL</h3>

The Test of English as a Foreign Language is a standarized test for non-native English speakers that are choosing to enroll in English-speaking universities.</br>

The test is split up into 4 sections:</br>

1. Reading
2. Listening
3. Speaking
4. Writing

Considering the dataset we have in our hands, graph of distributed TOEFL Scores of Applicants is:</br>

![download (3)](https://user-images.githubusercontent.com/38138793/86228965-ae399600-bbac-11ea-8829-a0866392be16.png)
<hr> </hr>

<h3> 3. CGPA</h3>

The Cumulative Grade Point is a 10 point grading system.</br>
Cumulative grade point average is a average of grade points obtained from all the semesters.</br>

Considering the dataset we have in our hands, graph of distributed CGPA Scores of Applicants is:</br>

![download (1)](https://user-images.githubusercontent.com/38138793/86228011-7c73ff80-bbab-11ea-939f-d6d9171634a2.png)
<hr> </hr>

<h3> 4. UNIVERSITY RATING </h3> 

College and university rankings are rankings of institutions in higher education which have been ranked on the basis of various combinations of various factors.</br>
University ranking depends on the magazines,newspwper,websites,projects or academics of the university.</br>
Unversity ranking matters a lot for the admission higher studies</br>

Considering the dataset we have in our hands, graph of distributed University rating Scores of Applicants is:</br>

![download (5)](https://user-images.githubusercontent.com/38138793/86229683-bb0ab980-bbad-11ea-93a9-bd5ef7c5401b.png)
<hr> </hr>

<h3> 5. RESEARCH EXPERIENCE </h3> 

The systematic investigation into and study of materials and sources in order to establish facts and reach new conclusions.</br>
Research experiences motivate the students to pursue graduate degrees and to develop necessary skills in themselves.</br>
It define directions for furture studies based on research results.</br>

Considering the dataset we have in our hands, graph of distributed RESERACH EXPERIENCE of Applicants is:</br>

![download (4)](https://user-images.githubusercontent.com/38138793/86229156-f22c9b00-bbac-11ea-8882-534008be7bb0.png)
<hr> </hr>

<h3> 6. CHANCE OF ADMIT </h3> 
We hence take a look at how all the parameters effect the chance of admit:



![download](https://user-images.githubusercontent.com/38138793/86226627-8dbc0c80-bba9-11ea-960b-aa8b9d6c57e8.png)
<hr> </hr>



Following steps occur in this process:</br>

1.We will be building the following models to predict the chance of admit</br>
 -> MULTIPLE LINEAR REGRESSOR</br>
 -> RANDOM FOREST REGRESSOR</br>
 -> MULTIPLE LINEAR REGRESSOR with PCA</br>
 -> RANDOM FOREST REGRESSOR with PCA</br>

2.We will plot the actual and predicted values for all four models and
  also plot the most significant featurs against output y_pred.</br>

3.Hence by building all the models mentioned above we will be able to predict the 'chance of admit'.</br>

