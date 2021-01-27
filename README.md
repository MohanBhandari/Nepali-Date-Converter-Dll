# Nepali-Date-Converter-Dll C# code

(between nepali date 2000 to 2121BS)
- convert to English date
  ConvertToEnglish(int yy, int mm, int dd)
- convert to Nepali date
  ConvertToNepali(int yy, int mm, int dd)
  
  
 # Example
 
using System;

using System.Collections.Generic;

using System.Linq;

using System.Text;

using System.Threading.Tasks;

using NepaliDateConverter.Net;

namespace PIS

{

    class Conversion
    
    {
    
        int year=2012, month=12, day=12;
        
        string convertedDate;
        
        DateConverter converted = DateConverter.ConvertToEnglish(year, month, day);
        
        convertedDate=converted.Year.ToString() + "/" + converted.Month.ToString() + "/" + converted.Day.ToString();
        
    }
