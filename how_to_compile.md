Follow below steps to compile my OpenCV code in quick way..

First open Dev C++ and click on 'File' -> 'New' -> 'Project'.
![image](https://user-images.githubusercontent.com/9850882/32575943-751d81ce-c4fb-11e7-8182-66904cb6265d.png)

Now select 'Console Application' and 'C++ Project' and click on 'OK'.
![image](https://user-images.githubusercontent.com/9850882/32576069-d6756fb8-c4fb-11e7-8fee-cb450d854dfa.png)

Make any new folder and just 'Save' it.
![image](https://user-images.githubusercontent.com/9850882/32576153-0d251e46-c4fc-11e7-9a2b-aa6d56cd4132.png)

Now you will see main.cpp file having preloaded code just add 'using namespace std;' and 'cout << "We have completed step 1\n;'.
![image](https://user-images.githubusercontent.com/9850882/32576167-22b83914-c4fc-11e7-9009-020ab5fcbe44.png)

Now 'Compile and Run'.
![image](https://user-images.githubusercontent.com/9850882/32576248-663c2fe2-c4fc-11e7-9c26-fa6645baae15.png)

You will see output like this:
![image](https://user-images.githubusercontent.com/9850882/32576263-7979b944-c4fc-11e7-895e-95c944da92b1.png)

Now copy my code and paste it to the main.cpp file.
![image](https://user-images.githubusercontent.com/9850882/32576324-a6f7eefe-c4fc-11e7-9f2e-72cba61828bd.png)

Now extract opencv2_4_10.exe or opencv2_4_13.exe to any folder and open 'build' folder.
![image](https://user-images.githubusercontent.com/9850882/32576353-b7166b26-c4fc-11e7-8135-057265888824.png)

Now open 'include' folder and you will see two folders 'opencv' and 'opencv2', copy both the folders.
![image](https://user-images.githubusercontent.com/9850882/32576412-e1f995de-c4fc-11e7-8eb4-4207d37695c5.png)

Paste it inside folder 'Dev-Cpp\MinGW64\include' and 'Dev-Cpp\MinGW64\x86_64-w64-mingw32\include'. This will include all required header files of opencv to the project whenever required.
![image](https://user-images.githubusercontent.com/9850882/32576451-04f6c9da-c4fd-11e7-91d3-b05214c6fd11.png)
![image](https://user-images.githubusercontent.com/9850882/32576462-0c5001ce-c4fd-11e7-9596-4cd45a5ccf74.png)

Now copy three library files from folder 'opencv_2_4_13\build\x64\vc14\lib' to the folder where main.cpp file resides, these are required to run code

opencv_core2413.lib

opencv_highgui2413.lib

opencv_imgproc2413.lib

![image](https://user-images.githubusercontent.com/9850882/32576688-9e55cc2a-c4fd-11e7-981b-3a4424fbfbb5.png)
![image](https://user-images.githubusercontent.com/9850882/32576692-a42ccea0-c4fd-11e7-9f2d-4914c73ed6c9.png)

Now copy three dll files of above three libraries from folder 'opencv_2_4_13\build\x64\vc14\bin'  to the folder where main.cpp file resides, these are required to run code

opencv_core2413.dll

opencv_highgui2413.dll

opencv_imgproc2413.dll

![image](https://user-images.githubusercontent.com/9850882/32577024-a41fe180-c4fe-11e7-81c1-07c1b9292014.png)
![image](https://user-images.githubusercontent.com/9850882/32577031-a6faa1ec-c4fe-11e7-92ad-eab74c4cd5e6.png)

Now we will be having 6 files in our folder 

opencv_core2413.lib

opencv_highgui2413.lib

opencv_imgproc2413.lib

opencv_core2413.dll

opencv_highgui2413.dll

opencv_imgproc2413.dll

![image](https://user-images.githubusercontent.com/9850882/32577112-dec6f18e-c4fe-11e7-8777-46f5d2ef5a7c.png)

Now go to 'Project' -> 'Project Options...' and click on 'Parameters' and 'Add library or object'
![image](https://user-images.githubusercontent.com/9850882/32577135-ed7238c4-c4fe-11e7-9b91-659a22cc65e1.png)
![image](https://user-images.githubusercontent.com/9850882/32577140-f1dd8184-c4fe-11e7-8a0f-edc7d88edc36.png)

Now navigate to the folder where main.cpp and library files are residing and select 

opencv_core2413.lib

opencv_highgui2413.lib

opencv_imgproc2413.lib

![image](https://user-images.githubusercontent.com/9850882/32577252-3983f180-c4ff-11e7-9685-b41c67d1a886.png)
![image](https://user-images.githubusercontent.com/9850882/32577307-6dbc5956-c4ff-11e7-80e3-52f9e4b15f90.png)

And now click on 'Compile'
![image](https://user-images.githubusercontent.com/9850882/32577323-7c43174e-c4ff-11e7-99b5-7a7226830c84.png)

And at last you will see 'Compile Log' wihout any error and warning.
![image](https://user-images.githubusercontent.com/9850882/32577327-8231a918-c4ff-11e7-8751-73b2a96414c7.png)

That's it :)
