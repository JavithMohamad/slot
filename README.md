# Ex03 Time Table
# DATE : 12/10/2023

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## CODE
```
<html>
    <body bgcolor="pink">
        <center>
            <img src = "LOGO.png" heght="00" width="700">
        </center>
        
       
        <h2 align="center">SLOT TIME TABLE : AFZARATHAGSIN JS</h2>
            
           
            
            <table align="center" border="3" width="800" height="700" >
            
            <tr style ="height:50px">
               
                <th>S.NO.</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
               </th>
                
            </tr>
            
            <tr>
                <td width="50">1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF
                    WEB APPLICATION
                </td>
                
            </tr>
            
            <tr>
                <td>2</td>
                <td>19EC307</td>
                <td>COMMUNICATION ENGINEERING</td>
                
                
            </tr>
            
            <tr>
                <td>3</td>
                <td>19CS407</td>
                <td>THEORY OF COMPUTATION</td>
    
            </tr>
            
            <tr>
                <td>4</td>
                <td>19CS521</td>
                <td>DATA WAREHOUSE AND DATA MINING</td>
              
            </tr>
            
            <tr>
                <td>5</td>
                <td>19CS409</td>
                <td>COMPILER DESIGN</td>
               
                
            </tr>

            <tr>
                <td>6</td>
                <td>19CS701</td>
                <td>MINI PROJECT</td>
               
                
            </tr>

            <tr>
                <td>7</td>
                <td>19CS411</td>
                <td>VIRTUALIZATION AND CLOUD COMPUTING</td>
               
                
            </tr>
            <tr>
                <td>8</td>
                <td>19CS412</td>
                <td>CRYPTOGRAHY AND NETWORK SECURITY</td>
               
                
            </tr>
            
            
            <tr style="width:550px" ></tr>
            </table>
           
<br/>
            <table align="center" border="4" width="1000" height="800" >
            
                <tr style ="height:50px" >
                   
                    <th>TIME</th>
                    <th> 8 - 9</th>
                    <th> 9 - 10</th>
                    <th> 10 - 11</th>
                    <th> 11 - 12</th>
                    <th> 12 - 1</th>
                    <th> 1 - 2</th>
                    <th> 2 - 3</th>
                    <th> 3 - 5</th>
                   
                   </th>
                    
                </tr>
                
                <tr>
                    <td width="50">MONADY</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>VCC</td>
                    <td>VCC</td>
                    <td rowspan="6" align="center">LUNCH BREAK</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>CRYPTO</td>

                    
                    
                </tr>
                
                <tr>
                    <td>TUESDAY</td>
                    <td>WEB</td>
                    <td>WEB</td>
                    <td>CE</td>
                    <td>CE</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                   
                    <td>TOC</td>
                    
                </tr>
                
                <tr>
                    <td>WEDNESDAY</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    
                    <td>DWDM</td>
                    <td>DWDM</td>
                    <td>CD</td>
                  
                </tr>
                
                <tr>
                    <td>THURSDAY</td>
                    <td>TOC</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>MINI PRO</td>
                   
                    <td>CE</td>
                    <td>FREE SLOT</td>
                    <td>WEB</td>
                  
                </tr>
                
                <tr>
                    <td>FRIDAY</td>
                    <td>VCC</td>
                    <td>VCC</td>
                    <td>VCC</td>
                    <td>DWDM</td>
                    <td>FREE SLOT</td>
                    <td>CD</td>
                    <td>CD</td>
                    
                   
                    
                </tr>
    
                <tr>
                    <td>SATURDAY</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>CRYPTO</td>
                    <td>CRYPTO</td>
                    
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>WEB</td>
                </tr>
    
               
                
                
                <tr style="width:550px" ></tr>
                </table>
               
            
            
            
            


    </body>
</html>

```

## OUTPUT
![new](https://github.com/JavithMohamad/slot/assets/121215951/307da171-f1be-491d-bcec-77d18f8fc8df)
![new1](https://github.com/JavithMohamad/slot/assets/121215951/f7c993d6-7b39-41b1-b521-8f0e3a563f44)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
