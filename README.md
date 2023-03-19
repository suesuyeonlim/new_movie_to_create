# Which movie to create for your new business?
## Overview and Business Understanding
My client sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they do not know anything about creating movies.

In this repository, I explore what types of films are currently doing the best and will in the future. I also give recommendations on whom to hire for the movie, using API data from various movie review websites.

## Data
The data used for this analysis are 1) Gross Revenue by movie from [Box Office Mojo](https://www.boxofficemojo.com/) and [The Numbers](https://www.the-numbers.com/); 2) Genre and Runtime information by movie from [IMDB](https://www.imdb.com/); and 3) Actor/Actresses and Directors information by movie.

## Analysis
Sci-Fi, Adventure, and Animation are the top 3 movie genres.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226206838-a039a734-615d-4a93-92fd-32a1089a66dc.png">

However, some movies are associated with multiple genres.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226206865-5fd69742-9d51-43ea-bb2b-24c436959089.png">

And multi-genre movies tend to be more successful.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226206886-c595e9d9-1c94-4b54-a581-984315d885ee.png">

Then among many different combinations of genres, Movies in Action, Adventure, and Sci-Fi generated the biggest revenue of $566M on average.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226207067-db0314d8-238e-4cae-bc89-d755d7cac09a.png">

Here are some example movies.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226207124-b4b9fc92-5434-427e-a243-5568980786b1.png">

Next, we can consider actors and actresses associated with higher gross revenue. Such actors include Chris Hemsworth, Mark Ruffalo, Robert Downey Jr., etc.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226207172-54c75048-88af-491c-b827-ad80cf96d2d8.png">

There are also directors who earned greater revenue than others, such as Michael Bay, Joe Russo, Anthony Russo, etc.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226207259-5571df71-a82c-4ad1-8fa6-a020b90173d3.png">

Lastly, majority of the movies and more financially successful movies range from 120 to 150 minutes.
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/19903898/226207354-b916a9ec-b09f-4a31-b8ea-ecf7295fcefd.png">

## Conclusions
My final recommendation to the client is to:
- Create a multi-genre movie, especially one in "Action, Adventure, and Sci-Fi"
- Hire actors and directors generating higher gross revenue
  - Such actors include: Chris Hemsworth, Mark Ruffalo, Robert Downey Jr., etc.
  - Such directors include: Michael Bay, Joe Russo, Anthony Russo, etc.
- Runtime should be between 120 to 150 minutes

## Locations of Data/Analysis
- Data: See "Data" folder.
- Analysis: See "Report.ipynb".
- Analysis with Detailed Explanation: See my blog post [here](https://medium.com/@limsue9123/which-movie-to-create-for-your-new-business-7bb1440cd7e6).
