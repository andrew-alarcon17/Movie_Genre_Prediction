# Movie_Genre_Prediction



## Data Description:
This data contains multiple properties of movies, such as the release year, ethnicity, director, genre, its Wikipedia page, and plot.


<img src="https://github.com/andrew-alarcon17/Movie_Genre_Prediction/blob/main/Movie_Plots_Vis/Bar_Chart.png" width="500">


## Project Summary:
For this project, I wanted to be able to classify the genre of a movie based on its plot summary.
To do this, I fit_transformed the data's story (plot) column by using TfidfVectorizer. TfidfVectorizer is a useful tool that helps us transform text into a meaningful representation of numbers in order to be predicted on machine learning algorithms.
Also another important point to keep in mind is that Tf-idf can be successfully used for stop-words filtering from the text document.

## Findings:
Here is the plot of the predictions. As you can see, drama seems to be correlated with a variety of other different genres. Obviously it is most highly correlated to itself, but the runner up is surprisingly comedy.


{{< figure src="/Movie_Plot_Vis/Heatmap.png" >}}


To test the model further, I used the plot summary of The Dark Knight as an input. The model predicted this movie to be considered drama. I would agree with this prediction.


{{< figure src="/Movie_Plot_Vis/Prediction.png" >}}





