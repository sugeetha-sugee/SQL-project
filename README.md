1).SELECT s.ID, s.name, s.year, s.department, f.total_fees, f.paid_amount, f.status 
   FROM students s JOIN fees f ON s.ID = f.student_id WHERE f.status = 'pending';
   ![1 A](https://github.com/user-attachments/assets/37b809f0-86b5-418f-8434-e54110608258)
   ![1 B](https://github.com/user-attachments/assets/d02e0c3d-c341-40e2-b87b-16990465975b)

2). SELECT students.ID, students.name, students.department, library.book_id, library.issue_date, library.return_date,library.submitted
    FROM students JOIN library ON students.ID = library.student_id WHERE library.submitted = 'no';   
    ![2 A](https://github.com/user-attachments/assets/f22d980a-8921-4c7f-bbd2-64dfa1e38e63)
    ![2 B](https://github.com/user-attachments/assets/071783c7-a453-4452-b2cc-8b60cacf8fbf)
    ![2 C](https://github.com/user-attachments/assets/6e9d5159-69d8-43dd-bed0-762d03c0f6bb)

 3). SELECT s.ID,s.name,t.date,t.entry_time,t.exit_time
     FROM students s JOIN timing t ON s.ID = t.student_id WHERE t.entry_time > '09:10:00'; 
     ![3](https://github.com/user-attachments/assets/e140c8c3-7fd7-4ff2-9c46-954ac10e4c1e)

  4). SELECT s.ID, s.name, a.percentage,s.department
      FROM students s JOIN attendance a ON s.ID = a.student_id WHERE a.percentage > 80;   
      ![4 A](https://github.com/user-attachments/assets/f08cda40-b169-4b26-be94-128454486da0)
      ![4 B](https://github.com/user-attachments/assets/592f5b65-4364-485e-878b-c7136d0cefac)

      



    



