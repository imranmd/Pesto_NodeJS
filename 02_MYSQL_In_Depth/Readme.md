Hi

hiciyoj268@sportrid.com

Your account number is: 794262

Your new database is now ready to use.

To connect to your database use these details;

Host: sql6.freesqldatabase.com
Database name: sql6636508
Database user: sql6636508
Database password: zVBjTl7GCv
Port number: 3306


CREATE TABLE IF NOT EXISTS `tutorials` (
  id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
  title varchar(255) NOT NULL,
  description varchar(255),
  published BOOLEAN DEFAULT false
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

-- Inserting sample values into the tutorials table
INSERT INTO tutorials (title, description, published) VALUES
('Introduction to SQL', 'Learn the basics of SQL', true),
('Python for Beginners', 'A beginner-friendly guide to Python', true),
('Web Development 101', 'Getting started with web development', false),
('Data Analysis with Pandas', 'Explore data analysis using Pandas library', true),
('Machine Learning Fundamentals', 'Understanding the basics of machine learning', false);
