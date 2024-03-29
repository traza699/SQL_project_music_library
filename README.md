# SQL_project_music_library
 I've been working on a project to create and manage a Music Library Database. The database consists of eleven interconnected tables, each containing essential information about various aspects of the music industry, such as artists, albums, tracks, genres, and more. Throughout the project, I've utilized various SQL query commands to retrieve, manipulate, and analyze data effectively.
#Database_and_Tools
Postgre SQL
PgAdmin4

#Tables
Artists: Contains information about different music artists.
Albums: Stores details about albums, including title, release year, and artist.
Tracks: Holds data on individual tracks, such as title, duration, album, and artist.
Genres: Stores different music genres.
Playlists: Contains information about user-created playlists.
Playlist_Tracks: A junction table linking playlists to tracks, allowing for many-to-many relationships.
Customers: Stores customer information.
Invoices: Contains data on sales transactions.
Invoice_line: Holds details about items purchased in invoices.
Employees: Stores employee information.
Medi_type: Types of media used 

#Query_Commands_Used:
SELECT: Used to retrieve specific columns from tables.
JOIN: Utilized to combine data from multiple tables based on related columns.
WHERE: Used to filter records based on specified conditions.
PRIMARY KEY: Assigned to unique identifiers in each table for data integrity.
HAVING: Used in conjunction with GROUP BY to filter grouped data.
GROUP BY: Used to group rows sharing common attributes.
ORDER BY: Utilized to sort query results based on specified columns.
