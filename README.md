#frequency polygon.
#c <- c(7,20,30,76,3,4,23,14,67)
Names <- c("MANASA","VARSHA","SASWITHA","SREYA","PRAGNA")
Rollno <- c("Y20CS110","Y20CS124","Y20CS135","Y20CS176","Y20CS093")
Gender <- c("Female","Female","Female","Female","Female")
Marks <-c(9,3,6,8,9)
Fee <-c(69400,57892,58903,69400,67390)
Section <-c("B","B","C","C","B")

rvrstudents <-data.frame(Names,Rollno,Gender,Marks,Fee,Section)
rvrstudents
write.csv(rvrstudents,"Rvr_Students.csv",row.names=F)

a <- read.csv("Rvr_Students.csv")


plot(rvrstudents$Marks,type="o",xlab="students names",ylab="students marks",xlim=c(1,10),ylim=c(0,40),main="RVRJC COLLEGE OF ENGINEERING.",col="green")



OUTPUT:
> #frequency polygon.
> #c <- c(7,20,30,76,3,4,23,14,67)
> Names <- c("UJJWAL","MANYA","SATWIKA","NITHYA","KIRAN")
> Rollno <- c("Y20CS161","Y20CS128","Y20CS149","Y20CS127","Y20CS129")
> Gender <- c("Male","Female","Female","Female","Male")
> Marks <-c(9,3,6,8,9)
> Fee <-c(69400,57892,58903,69400,67390)
> Section <-c("B","B","C","C","B")
> rvrstudents <-data.frame(Names,Rollno,Gender,Marks,Fee,Section)
> rvrstudents
    Names     Rollno   Gender   Marks    Fee    Section
1  MANASA    Y20CS110  Female    9      69400      B
2  VARSHA    Y20CS124  Female    3      57892      B
3 SASWITHA   Y20CS135  Female    6      58903      C
4  SREYA     Y20CS176  Female    8      69400      C
5  PRAGNA    Y20CS093  Female    9      67390      B
> write.csv(rvrstudents,"Rvr_Students.csv",row.names=F)
> a <- read.csv("Rvr_Students.csv")
> plot(rvrstudents$Marks,type="o",xlab="students names",ylab="students marks",xlim=c(1,10),ylim=c(0,40),main="RVRJC COLLEGE OF ENGINEERING.",col="green")
> 
