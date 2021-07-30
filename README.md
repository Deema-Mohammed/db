

 
 @dayNumber NUMBER(10);
 @dayName varchar2(20);
@dayNumber :=  to_char(sysdate, 'DAY');
@dayName :=to_char(sysdate, 'DY');

-- SQLINES DEMO *** ay = 7.
IF(@dayNumber = 7 or @dayNumber=2 or @dayNumber=3 ) THEN 

select to_char(sysdate, 'DAY') full_name
    from dual;
    
END IF;
	-- SQLINES DEMO *** mber =7)
	-- SQLINES DEMO *** EKDAY, GETDATE());
