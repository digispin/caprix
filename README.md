# caprix
NOTE: Some of the below parts are under construction or yet to upload.
      Due to limited development time, some parts will be updated based on time availability.

ABSTRACT:

Caprix provides a way to detect sudden failures in complex data series applying some of the following technique.
   
   a) Partial convolution with phythagorean hodograph  
   b) Optimal barcodes based on Persistent Homology
   c) Caprix algorithm to reduce noise 

The software provides examples of unexpected failures using 
  i. past financial data time series with modified analytic reduction on timing window for large number of stacks (around 20 to 30year).
  ii.IoT sensor data captured from connected fablabs 

The software can be used to rudimental prediction for unexpected failure for IoT sensor data.

SOFTWARE FRAMEWORK:

There are two implementations available: 
   a) electron based JavaScript implementation
   b) Mono VM based C# implementation.

How to Install;

How to run;



Note on framework:

There is an effort to merge backend to simplify the maintenance.
(Note 1. There are no good and tested framework to invoke C# APIs from JavaScript
           The initial trials with ReactNative did not provide needed performance.
           The ReactNative for windows is relatively new, and kind of depends on Windows 10,    due to the complex dependencies, the upgrade work was stopped)

Note on Porting:
   Electron based framework is easily portable on most of the platform. Leave a note if you need this for specific
    platform, our trials might already have a rough port on those platform.

   Mono based C# framework is more are less can execute on the platforms where Mono VM can be executed.
     



ACADAMIC PAPER:
    Some part of Caprix was explained in the following papers.
      Paper 1: Bureau for Big Data Containerization and Exchange: Project UniKirin       
            Note *: This paper was submitted to well-known Canadian university, under review for publishing

      Paper 2:          
            Note *: This paper was submitted to well-known European university, under review for publishing
            
LICENSE:
Caprix is currently copyright protected. You can use it for academic purpose only. This program is distributed in the hope that it will be useful, but without any warranty; without even the implied warranty of merchantability or fitness for a particular purpose. 
If you are in a doubt, please consult with a mail. The detailed license term will be uploaded later.  Also, the software framework (Mono VM, Electron etc) used for development of Caprix are MIT license and related open source license. If there are any software or algorithms which are used internally are private, please send details with the claim, it will be rectified as soon as possible.
In future Caprix may be released under the terms of GNU License.  See the GNU General Public License for more details. 

