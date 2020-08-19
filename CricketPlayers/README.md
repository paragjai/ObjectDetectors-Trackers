## Player Detection and Tracking


An application to track and detect players of Indian Women's National Cricket Team playing in the international stadium. It uses [Intel OpenVino](https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit.html) for optimal utilization of the hardware for optimal performance. It can accept input in 2 forms : 

<ol>
<li><b>image</b></li>
<li><b>video</b></li>
</ol>


### Sample application input and output : 

1\. **Image :**

<img style="padding:0;display:block;margin:0 auto;max-height: 100%;max-width: 100%;border: 5px solid #555;" src="sample_input_and_output/input&Output/image/sample_input.png"></img>
<p align="center">Frame containing players playing in a international stadium</p>




<img style="padding:0;display:block;margin:0 auto;max-height: 100%;max-width: 100%;border: 5px solid #555;" src="sample_input_and_output/input&Output/image/sample_output.png"></img>
<p align="center" style="margin-top:-10px;">Frame containing players with detected and tracked players</p>


2\. **Video :**

<img style="padding:0;display:block;margin:0 auto;max-height: 100%;max-width: 100%;border: 5px solid #555;" src="sample_input_and_output/input&Output/video/sample_input.gif"></img>
<p align="center">Video input containing players</p>


<img style="padding:0;display:block;margin:0 auto;max-height: 100%;max-width: 100%;border: 5px solid #555;" src="sample_input_and_output/input&Output/video/sample_output.gif"></img>
<p align="center">Video output with players detected and tracked</p><br>



Code access and more details related to model used for inferencing and implementation : Source code for the application can be found <a href="">here</a>. Contact at <paragjainpes@gmail.com> for more details.
