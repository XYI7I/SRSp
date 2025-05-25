 ==========================================
 *** Format of Fits File for SRSP-"Ra" ***
 ==========================================
 ==========================================
 ***           Primary Header           ***
 ==========================================
SIMPLE  =                    T / conforms to FITS standard                      
BITPIX  =                  -64 / array data type                                
NAXIS   =                    1 / number of array dimensions                     
NAXIS1  =                   39                                                  
EXTEND  =                    T                                                  
DATE    = '2025 04 11'         / Date of creation fits file                     
ORIGIN  = 'SRI RAS '           / Space Research Institute of the Russian Academy
EMAIL   = 'email   '           / Please contac us                               
TELESCOP= 'SRSP    '           / Solar Radio Spectroplarimetr                   
INSTRUME= 'Ra      '                                                            
OBSERVER= 'Name '                                                            
OBJECT  = 'SUN     '                                                            
FITS_VER= '1.0     '           / Version of the FITS file                       
DATE-OBS= '2025-04-11T02:54:03.517' / Observing Day in Russian Standard Time-ISO
DATE-BEG= '2025-04-11T02:54:03.517' / Time observation start (UT)               
DATE-END= '2025-04-11T15:49:00.875' / Time observation end (UT)                 
TIMESYS = 'UTC     '           / Coordinated Universal Time                     
DATEREF = '1979-01-01T00:00:00.000' / Unix timestamps milliseconds              
MJD-OBS =    60776.12087403935 / MJD of data start time                                                 
XPOSURE =                 0.05 / s / Time cadence of the data is 50ms           
F_START =                  3.0 / GHz / Band lowest frequency                    
F_STOP  =                 24.0 / GHz / Band highest frequency
BANDWIDT=                   10 / MHz / Bandwidth
CHANNELS=                   39 / Number of frequency channels                   
F_LOGSCL=                    F / Freq axis scale, FALSE - linear 
 ==========================================
 ***         Radio Array Data           ***
 ==========================================
 ***      Band frequency 3-24 GHz       ***
 ==========================================
EXTNAME = 'RADIODATA'          / extension name                                 
TTYPE1  = 'Frequency'                                                           
TFORM1  = 'D       '                                                            
TTYPE2  = 'TimeLCP '                                                            
TFORM2  = '35431K  '                                                            
TDIM2   = '(35431) '                                                            
TTYPE3  = 'FluxLCP '                                                            
TFORM3  = '35431D  '                                                            
TDIM3   = '(35431) '                                                            
TTYPE4  = 'TimeRCP '                                                            
TFORM4  = '35431K  '                                                            
TDIM4   = '(35431) '                                                            
TTYPE5  = 'FluxRCP '                                                            
TFORM5  = '35431D  '                                                            
TDIM5   = '(35431) '                                                            
TUNIT1  = 'GHz     '                                                            
TUNIT2  = 's       '                                                            
TUNIT3  = 'Jy      '                                                            
TUNIT4  = 's       '                                                            
TUNIT5  = 'Jy      '                                                            
COMMENT Radio flux density at 3-24 GHz with dual circular polarization 
 ==========================================
 ***             COMMENTS               ***
 ==========================================
COMMENT Time in the bintable show the miliseconds from 1979-01-01T00:00:00.     
COMMENT weather condition or/and instrumental issues                            
COMMENT For antenna with frequncies range 6-12 GHz use frequency 6.01 GHz for 6.
COMMENT 0 GHz                                                                   
COMMENT For antenna with frequncies range 12-24 GHz use frequency 12.01 GHz for 
COMMENT 12.0 GHz                                                                
COMMENT List of frequencies for antenna [ 3- 6]GHz:                             
COMMENT 3.0, 3.25, 3.5, 3.75, 4.0, 4.25, 4.5, 4.75, 5.0, 5.25, 5.5, 5.75, 6.0   
COMMENT List of frequencies for antenna [ 6-12]GHz:                             
COMMENT 6.01, 6.5, 7.0, 7.5, 8.0, 8.5, 9.0, 9.5, 10.0, 10.5, 11.0, 11.5, 12.0   
COMMENT List of frequencies for antenna [12-24]GHz:                             
COMMENT 12.01, 13.0, 14.0, 15.0, 16.0, 17.0, 18.0, 19.0, 20.0, 21.0, 22.0, 23.0,
COMMENT  24.0 
 =========================================
 =========================================
 ***           End of File             ***
 =========================================
