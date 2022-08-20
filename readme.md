# SCHOOL RESULT MANAGEMENT SYSTEM

# Description

This is a website that will serve as a respository for lesson notes,lesson videos and submittion of assignments and exam scores for student and also allow students view their results.

# FUNCTIONALITY

1. **Student Dashboard**
    
    This is the portal for each student to login and perform the following operations:
   
    - Lesson note: Student will have access to teachers lesson note for all subjects from their dashboard
    - Lesson video: This a video that are available to students, they can play, pause and seek
    - Assignment: Teachers can give assignment to students which can be either typed directly or upload in the following format (pdf,exl,doc,ppt,txt).

    - View/print academic result(s)
    - Take a lesson (video/note)
    - Submit assignments
    - View/print test result
    - View/Print class timetable
    - Make a complaint to a teacher
    - View/Print exam timetable
    - View current/outstanding fees

2. **Teachers Dashboard**
    
    This is a portal for each teacher which gives them access to perfom the following operations:
    
    - Upload lesson notes
    - Upload lesson videos
    - Assign task to class or a student
    - Upload/input test scores
    - Upload/input exam scores
    - View/access assignment submitted by students
    - Accept/Reject a submitted assignment/task
    - Submit result sheet to the administration for approval
    - File a complaint
    
    **Result Preparation**
    
    This will allow teachers to upload results into the application by entering the score of each subject for each student.

  3. **Administrator Dashboard**

   - Allocate teachers to class
   - Allocate subjects to teachers
   - View and attend to complaints from student and teachers
   
    **How are result entered into the application?**
    
    Teacher are to select the following to enter student score:
    
    - session
    - term
    - class
    - Student name : this will retrieve the student ID and passport
    - Enter score, Remark and submit
    
    ### **Result Format**
    
    There are two type of results:
    
    1. Term Result: this is a single term result
    
    ![Frist Term.jpg](https://drive.google.com/file/d/1tR8ORt80BL9z8-lf1BUlHhbuImBADRyK/view?usp=sharing)
    
    1. Cummulative Result: This is the Third term result sheet.
    
    ![Third.jpg](https://drive.google.com/file/d/1woD8J0fS3VorPrBMzfL-W2MUTIYvAigo/view?usp=sharing)
    
    ### **Users**
    
    There are three types of users of this application and with different authorization levels.
    
    - **Teacher**
    
    These are the academic staff of the school
    
    - **Student**
    
    These are students of the school
    
    - **Administrator**
    
    These are users(Teachers) who have higher privilege to perfom administrative functions and can also grant such privilege to others.
    
    Admin will create the following:
    
    Session
    
    Term
    
    ### **Functions of an admininstrator**
    
    The administrator will have access to perfom the following operations:
    
    1. Create user account for teachers
    2. Grant/Revoke privileges assigned to a teacher
    3. Approval of submitted Results
    4. Assignment of class to teachers
    5. Assignment of subjects to teachers
    
    **TYPES OF ADMIN:**
    
    **ICT Manager:** oversees the entire system
    
    **Princinpal:** This is admin for secondary section
    
    **Head Mistress:** This is the admin for Primary section
    
    **Head Teacher:** This is the admin for Nursary section
    
    ### Approval of Results & Result Remarks
    
    Approval of Results and providing Remarks will be done by the following:
    
    1. Pricipal: For seconday section
    2. Head Mistress: For Primary Section
    3. Head Teacher for Nursery Section
    
    **Remark Requires the following to be in view for all students:**
    
    1. English
    2. Maths
    3. Cummulative Average
    
    **CREATING OF TEACHERS ACCOUNT REQUIRES:**
    
    Only the ICT manager is authorized to create teachers’ account;
    
    1. Name (fullname)
    2. Subject handling(multiple)
    3. Picture
    4. Username(email)
    5. Default Password(change on first login)
    6. Teacher’s role
    7. Signature image
    
    **CREATING OF STUDENT’S ACCOUNT**
    
    Only the ICT manager is authorized to create student account:
    
    1. student adminNO
    2. Fullname (firstname, lastname & other name)
    3. Passport
    4. Class
    5. Session
    6. term
    
    **QUESTIONS**
    
    Do students have ID if yes how is the ID generated?
    
    ANSWER: Yes, the ID is the student's roll number in the attantance register, this is called Admin Number.
    
    ### **Required Modification For Student ID**
    
    Create a unique student ID for each student
    
    student ID will takes the format:
    
    school_Name&section/registration_year/adminNo
    
    EISP/2022/225 (P for Primary)
    
    EISS/2022/200 (S for Secondary) and so on.
     

    # APPLICATION STRUCTURE
