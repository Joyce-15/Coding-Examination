# Coding-Examination

## ITEM NO. 1
  
    int num[9] = {5, 1, 4, 6, 7, 3, 5, 7, 3}; 
    int i, j; 
    int size = sizeof(num)/sizeof(num[0]); 
     
    cout <<"Array: "; 
     for(i=0; i < size; i++) 
     cout<< num[i] << " "; 
     cout<<"\nDuplicate elements: "; 
      
     for(i=0; i< size; i++) 
         for(j= i+1; j < size; j++) 
             if(num[i] == num[j]) 
                 cout<< num[i] << " "; 
      
     return 0; 






## ITEM NO. 2 

    int i,j; 
    for(i = 1; i<7; i++){ 
      for(j= 0; j<i; j++){ 
        cout<< i; 
      } 
      cout<< "\n"; 
    } 
    return 0; 
 



## ITEM NO. 3

double hired_m,hired_f, permanent_m, permanent_f,resigned_m, resigned_f, total_hired, total_permanent, total_resigned; 
  
 cout<< "Enter the number of newly hired males: "; 
 cin>> hired_m;  
  
 cout<< "\nEnter the number of newly hired females: "; 
 cin>> hired_f; 
  
 cout<< "\nEnter the number of permanent position males: "; 
 cin>> permanent_m;  
  
 cout<< "\n Enter the number of permanent position females: "; 
 cin>> permanent_f; 
 cout<< "\nEnter the number of resigned males: ";  
 cin>> resigned_m;  
  
 cout<< "\nEnter the number of resigned females: "; 
 cin>> resigned_f;  
 cout<<"\nThank for the information"<<endl;  
 cout<< "\nHere is the summary!\n";   
 cout<< "\nNumber of hired employee = "; 
 total_hired = hired_m + hired_f; 
 cout<< total_hired;   
 cout<< "\nMale = ";  
 cout<< printf("%.2f",(hired_m / total_hired) * 100.0) << "%";  
 cout<< "\nFemale = ";  
 cout<< printf("%.2f",(hired_f / total_hired) * 100.0) << "%"<<endl;   
 cout<< "\nNumber of Permanent employee = ";  
 total_permanent = permanent_f + permanent_m;  
 cout<< total_permanent;  cout<< "\nMale = ";  
 cout<< printf("%.2f",(permanent_m / total_permanent) * 100.0) <<"%";  
 cout<< "\nFemale = ";  
 cout<< printf("%.2f",(permanent_f / total_permanent) * 100.0)<< "%"<<endl;  
 cout<< "\nNumber of Resigned Employee = ";  
 total_resigned = resigned_m + resigned_f; 
 cout<< total_resigned <<endl;   
 cout<< "Male = " << printf("%.2f",(resigned_m / total_resigned) * 100.0)<< "%" <<endl;  
 cout<< "FemalCompilee = " << printf("%.2f",(resigned_f / total_resigned) *100.0) <<"%" <<endl;     
  
 return 0;
