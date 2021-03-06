# IMDb Rating and Release Year for Movies

Using [OMDb API](omdbapi.com), add movie release year, and/or IMDb movie rating to a file whose name is a movie title.

#### rating-fetcher
Try to search for ratings of movies from all local files in the directory the source file is present. If a score is found for a file name, rename the file and prepend the score. 

#### year-fetcher
Try to look for the release year of movies from all local files in the same directory as the source file. If a release year is found for a file name, rename the file and append the release year.

## Usage

1. Download the corresponding file(s) to add rating or release year to files.
2. Place the downloaded file(s) in the same folder as your movie files.
3. Run the python script using one of the following commands:
   * `python3 rating-fetcher.py`
   * `python3 year-fetcher.py`
4. Voilà! All valid movies now have more information to help you decide what to watch next.

## Examples

#### rating-fetcher          
P.S. I Love You [1080p].avi ⟶ **[IMDb 7.1]** P.S. I Love You [1080p].avi

#### year-fetcher
[IMDb 7.1] P.S. I Love You [1080p].avi ⟶ [IMDb 7.1] P.S. I Love You **(2010)** [1080p].avi
