CREATE TABLE babymilestones_24months (id INTEGER PRIMARY KEY, milestone TEXT, age INTEGER);


INSERT INTO babymilestones_24months (milestone, age) VALUES ('sitting', '6');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('rolling', '3');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('crawling', '8');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('weight bearing', '8.54');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('grabbing toes', '3');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('standing', '10');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('grabbing toys', '3');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('taking a step', '11');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('walking with support', '11');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('walking without support', '13');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('using utensils', '18');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('throwing ball', '18');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('catching ball', '24');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('feeding independently', '24');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('helping with tasks', '15');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('painting', '18');
INSERT INTO babymilestones_24months (milestone, age) VALUES ('potty training', '24');

Select * FROM babymilestones_24months;

UPDATE babymilestones_24months
SET age = 8.5
WHERE id=4;

SELECT * FROM babymilestones_24months;

DELETE FROM babymilestones_24months WHERE milestone = 'painting';

Select * from babymilestones_24months;

