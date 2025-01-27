# SimplePod_ComfyUI
Instructions to get a simplepod.ai comfyui instance setup 


<h3 class="wp-block-heading"><strong>Create Your Own Image Generation ComfyUI Instance!</strong></h3>

<p>Welcome to this beginner-friendly tutorial on creating a ComfyUI GPU instance on the Simplepod.AI Cloud Compute Servers. In this guide, we will walk you through the process of setting up a simplepod.ai cloud instance to run inference or train image models within ComfyUI. Image generation technology has advanced significantly, allowing us to create highly interesting and creative images and videos.</p>


<h3 class="wp-block-heading">What You Will Learn</h3>

<ul class="wp-block-list">

<li><strong>Understanding ComfyUI Front end</strong>: ComfyUI is a free, open-source program that lets users create AI-generated images from text prompts. It uses a node-based interface to create workflows for image generation. </li>

</ul>

<ul class="wp-block-list"><!-- wp:list-item {"style":{"spacing":{"padding":{"top":"0","bottom":"0","left":"0","right":"0"}},"border":{"radius":"0px","width":"0px","style":"none"}}} -->

<li style="border-style:none;border-width:0px;border-radius:0px;padding-top:0;padding-right:0;padding-bottom:0;padding-left:0"><strong>Setting Up a Cloud Instance</strong>: We will guide you through the steps to set up a cloud environment where you can run the necessary tools and scripts. This setup is crucial for handling the computational requirements of of image generation and training.</li>

</ul>

<ul class="wp-block-list">

</ul>

<li><strong>Cloud vs. Local Setup</strong>: While this tutorial focuses on using a cloud instance, you can also run the tools locally if your hardware supports it. Each setup has its pros and cons.</li>

</ul>


<ul class="wp-block-list">

<h3 class="wp-block-heading">Getting Started</h3>
<p>Before diving into the technical details, make sure you have the following prerequisites:</p>
<ul class="wp-block-list">
<li>While not required, a basic understanding of Python and cloud computing would be very helpful. I will try to guide you as best I can but the process can be nuanced.</li>

<li>Access to Simplepod.AI account </li>

</ul>

<p>Step 1. Login to Simplepod.ai and click "find instances".</p>
<p>
    <img src="Screenshot 2025-01-08 000652.png" width="720" height="340"/>
</p>



<p>Step 2. Select a single RTX 4090. Note: for now stick with a single GPU. Multi GPU training is called distributed data processing or D.D.P for short. This can become extremely complex and in some cases is not supported. You can circle back to learn D.D.P at a later time but ultimately is beyond the scope of this tutorial.</p>

<p>
    <img src="Screenshot 2025-01-08 000802.png" width="720" height="340"/>
</p>


<p></p>

<p>Step 3. The docker templates page will pop open and from here scroll down until you find "simplepodai/jarodmica-ai-voice-cloning". </p>

<p>
    <img src="Screenshot 2025-01-08 000905.png" width="720" height="340"/>
</p>



<p>NOTE: Be aware that the version numbers may change at a later date. This is fine, as long as it says "jarodmica/ai-voice-cloning" you're doing the right thing.</p>

<p></p>

<p>Step 4. This will open up a side panel to your right. Verify your settings match mine. You shouldn't have to change anything.</p>
<p>
    <img src="Screenshot 2025-01-08 001134.png" width="720" height="340"/>
</p>



<figure class="wp-block-image size-large"><img src="https://commandcentersystems.wordpress.com/wp-content/uploads/2024/11/image-2.png?w=679" alt="" class="wp-image-57" /></figure>




<p>Step 5. This will send it to your private template list. Scroll up and click use.</p>
<p>
    <img src="Screenshot 2025-01-08 001229.png" width="720" height="340"/>
</p>


<figure class="wp-block-image size-large"><img src="https://commandcentersystems.wordpress.com/wp-content/uploads/2024/11/image-9.png?w=123" alt="" class="wp-image-66" /></figure>


<figure class="wp-block-image size-large"><img src="https://commandcentersystems.wordpress.com/wp-content/uploads/2024/11/image-10.png?w=104" alt="" class="wp-image-67" /></figure>




<p>You will get a quick popup. Click it to go to your instance. If you're not fast enough you can click "My Instances" on the left side panel to get to the same place.<br></p>

<p>
    <img src="Screenshot 2025-01-08 001240.png" width="720" height="340"/>
</p>
<p>
    <img src="Screenshot 2025-01-08 001422.png" width="720" height="340"/>
</p>


<figure class="wp-block-image size-large"><img src="https://commandcentersystems.wordpress.com/wp-content/uploads/2024/11/image-11.png?w=550" alt="" class="wp-image-68" /></figure>


<p>Now you have to wait for the instance to load the docker image. It will look something like this:</p>


<figure class="wp-block-image size-large"><img src="https://commandcentersystems.wordpress.com/wp-content/uploads/2024/11/image-12.png?w=1024" alt="" class="wp-image-69" /></figure>

<p></p>

<p>Step 6. When the instance has loaded up you'll start to see buttons appear. These are different ways to access the data and scripts within the instance. In this case, lets open the WebUI by clicking on the Port 7860 button.<br></p>





<figure class="wp-block-image size-large"><img src="https://commandcentersystems.wordpress.com/wp-content/uploads/2024/11/image-13.png?w=1024" alt="" class="wp-image-71" /></figure>




<p>You are now within the instance and can begin training your model and or running inference. </p>




<p>For more specifics on how to train a model take a look at Jarod Mica's repo where he goes over the whole process in detail <br><a href="https://github.com/JarodMica/ai-voice-cloning">https://github.com/JarodMica/ai-voice-cloning</a></p>




<p><br>and in two videos he made:<br><a href="https://youtu.be/WWhNqJEmF9M?si=RhUZhYersAvSZ4wf">https://youtu.be/WWhNqJEmF9M?si=RhUZhYersAvSZ4wf</a><br><a href="https://www.youtube.com/watch?v=7tpWH8\_S8es&amp;t=504s">https://www.youtube.com/watch?v=7tpWH8\_S8es&amp;t=504s</a><br></p>

]]></content:encoded>
