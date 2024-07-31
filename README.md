# acccode19
sql
'''COUNT(EMPNO)     DEPTNO                                                         
------------ ----------                                                         
           2         20    '''
           > select count(empno),deptno
  2  from emp
  3  where job='CLERK'
  4  group by deptno
  5  having count(empno)>=2;
