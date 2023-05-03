CREATE DATABASE todolist;

USE todolist;

CREATE TABLE tasks (
  task_id INT PRIMARY KEY,
  task_name VARCHAR(255),
  description TEXT,
  is_completed BOOLEAN
);

