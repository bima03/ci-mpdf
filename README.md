# CI-mPDF
=========
_Using mPDF 6.0_
Easy Generate PDF's in CodeIgniter using library based on mPDF.

Installation
============
1. Drop application folder into your project folder.

Usage
=====
You can convert a view into a PDF by using the following code.

    $this->load->library('pdf');
    $this->pdf->load_view('welcome');
    $this->pdf->Output();
  
You can also pass data to the function by using

    $this->pdf->load_view('welcome', $data);
  
License
=======
* mPDF - GNU GPL v2 licence.

Credits
=======
* CodeIgniter Conversion - [Yudha Pratama](http://blog.shinryu99.my.id)
* mPDF - (http://www.mpdf1.com/)
