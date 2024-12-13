
CREATE TABLE polls (
    poll_id INT AUTO_INCREMENT PRIMARY KEY,
    question VARCHAR(255) NOT NULL
);


CREATE TABLE options (
    option_id INT AUTO_INCREMENT PRIMARY KEY,
    poll_id INT NOT NULL,
    option_text VARCHAR(255) NOT NULL,
    vote_count INT DEFAULT 0,
    FOREIGN KEY (poll_id) REFERENCES polls(poll_id)
);


INSERT INTO polls (question) VALUES ('En sevdiğiniz programlama dili hangisi?');


INSERT INTO options (poll_id, option_text) VALUES 
(1, 'Python'),
(1, 'JavaScript'),
(1, 'Java');


UPDATE options 
SET vote_count = vote_count + 1 
WHERE option_id = 1;


SELECT 
    option_text, 
    vote_count, 
    ROUND((vote_count / (SELECT SUM(vote_count) FROM options WHERE poll_id = 1)) * 100, 2) AS percentage
FROM options 
WHERE poll_id = 1;
