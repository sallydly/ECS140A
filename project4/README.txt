Ly, Sally, 999882177, sadly@ucdavis.edu
Sanders-Turner, Haley, 912296300, hfsanders@ucdavis.edu

Format of Predicates (X is the variable to test):

/* PART 1 */
fc_course(X)
imprereq(X, Course) (ie. imprereq(X, ecs20))
students(X, Course)
students_prereq(X)
allprereq(X, Course)
student_teach(X, Course)

/* PART 2 */
miss_cannibal(X).

/* PART 3 - takes approx 19 seconds with europe.p*/
mapcolor(X). 

References/Sources:
https://www.cpp.edu/~jrfisher/www/prolog_tutorial/2_16.html // For Missionary Cannibal Problem, understanding how to implement DFS in Prolog