# Book Recommendation System
A book recommendation system conducted in a machine learning class at Gachon University.
### INDEX
- Business Objective
- Data Exploration
- Data Preprocessing
- Modeling
- Evaluation / Analysis
### Business Objective


### Data Exploration
Goodbooks-10k Dataset:
- books_tag.csv: goodreads_book_id, tag_id, count
- books.csv: id, book_id, best_book_id, work_id, books_count, isbn13, authors, original_publication_year, original_title
- ratings.csv: book_id, user_id, rating
- tags.csv: tag_id, tag_name
- to_read.csv: user_id, book_id

Book Recommendation Dataset:
- Books.csv: ISBN, Book_Title, Book-Author, Year_Of-Publication, Publisher, Image-URL-S, Image-URL-M, Image-URL-L
- Ratings.csv: User-ID, ISBN, Book-Rating
- Users.csv: User-ID, Location, Age
### Data Preprocessing
Goodbooks-10k
- Remove unnecessary columns
- Merge ratings.csv, books.csv based on book_id
- Fill the missing values

Book Recommendation
- Remove unncessary columns
- Convert all string data to lowercase
- Merge Ratings.csv, Books.csv and Users.csv based on ISBN
- Delete noise data by eliminating data whose rating is 0.

Filtering
- Select books with 10 or more ratings
- Select books that have been rated by at least 5 different users.

Normalization
- Unify the column name of both data sets
- Change the data type of ISBN and User_ID
- Map the ISBN based on book title
- Fix the size of ISBN
- Exclude users only rated one book
- Exclude duplicated books of both dataset

### Modeling


### Evaluation / Analysis


### Team Member
- Kwon Soyeong
- Song Eunjung
- Jeon Sihyeon
- Jang Yonggeun
- Kim Jeongsu
