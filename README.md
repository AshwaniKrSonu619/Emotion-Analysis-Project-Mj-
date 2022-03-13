# Emotion-Analysis-Project-Mj-
***Tools & Technology***
![image](https://user-images.githubusercontent.com/94763917/158051663-a3db4a9e-1d87-40ab-a6de-09615900d3b1.png)

Emotion analysis is the process of identifying and analyzing the underlying emotions expressed in textual data .It can be easily done based on the types of feelings expressed in the text such as fear,anger,happiness,sadness,love inspiring or neutral. Emotion analytics can extract the text data from multiple sources to analyze the subjective information and understand the emotions behind it.Human emotion detection is implemented in many areas requiring additional security or information about the person. It can be seen as a second step to face detection where we may be required to set up a second layer of security, where along with the face, the emotion is also detected. This can be useful to verify that the person standing in front of the camera is not just a 2-dimensional representation . Another important domain where we see the importance of emotion detection is for business promotions. Most of the businesses thrive on customer responses to all their products and offers. If an artificial intelligent system can capture and identify real time emotions based on user image or video, they can make a decision on whether the customer liked or disliked the product or offer. We have seen that security is the main reason for identifying any person. It can be based on finger-print matching, voice recognition, passwords, retina detection etc. Identifying the intent of the person can also be important to avert threats. This can be helpful in vulnerable areas like airports, concerts and major public gatherings which have seen many breaches in recent years.
Human emotions can be classified as: fear, contempt, disgust, anger, surprise, sad, happy, and neutral. These emotions are very subtle. Facial muscle contortions are very minimal.
In this research there are main topics discussed the first one is Emotions, and how an emotion can be detected from a photo, and finally the science and previous results behind the Convolutional Neural Networks and much details like comparing any previous results with this research results.
The discussion about emotions is very wide, in psychology emotions is a state of feeling a human can experience, it comes as a result of physical and psychological changes that play a huge role in influencing our thoughts and behaviours. Emotion is associated with a range of psychological phenomena, including mood, personality, mood, and motivation. There are some major types of emotions or it can be called theories, and they are physiological, neurological, and cognitive states. The physiological state is a state of mind or emotions that come from giving the responsibility for some body parts are responsible for emotions. Second thing is neurological state is a state of emotions that comes from the brain directly. And the last one is cognitive group, and these are the most complex group and these groups are responsible of some emotions when it comes to giving thoughts and some mental activities the responsibility of producing some major emotions.
Back then by time Charles Darwin said that emotions are developed by time because they are adaptive and they are very important because they give humans and even animals the rights of being alive. There is a theory or an evolutionary of emotions, and it says that emotions are exists to play their major role as an adaptive changer, and they are playing major role in giving us motivation and increases our chances of success and survive in life. One more thing is that understanding emotions of others like humans and animal is very important to survive and live, and from understanding emotions you can respond right and feel safe without feeling danger.

The main three concepts of emotion analysis projects is – 
a) Subjective experience

b) physiological responce 
 
c) Behavioral or expressive 
 
The fundamentals of emotion analysis project is charcterized by feeling joy, satisfaction, and well-being.
We can generalize the emotion detection steps as follows: 

1) Dataset preprocessing  
2) Face detection 
3) Feature extraction
4) Classification based on the features
 
 In this work, we focus on the feature extraction technique and emotion detection based on the extracted features. Section 2 focuses on some important features related to the face. Section 3 gives information on the related work done in this field. Related work covers many of the feature extraction techniques used until now. It also covers some important algorithms which can be used for emotion detection in human faces. We will also see details of  the tools and libraries used in the implementation.

Face detection is a computer technology being used in a variety of applications that identifies human faces in digital images. Face detection also refers to the psychological process by which humans locate and attend to faces in a visual scene.
Face detection can be regarded as a specific case of object-class detection. In object-class detection, the task is to find the locations and sizes of all objects in an image that belong to a given class. Examples include upper torsos, pedestrians, and cars.
Face-detection algorithms focus on the detection of frontal human faces. It is analogous to image detection in which the image of a person is matched bit by bit. Image matches with the image stores in database. Any facial feature changes in the database will invalidate the matching process
A reliable face-detection approach based on the genetic algorithm and the eigen-face technique:
Firstly, the possible human eye regions are detected by testing all the valley regions in the gray-level image. Then the genetic algorithm is used to generate all the possible face regions which include the eyebrows, the iris, the nostril and the mouth corners.
Each possible face candidate is normalized to reduce both the lighting effect, which is caused by uneven illumination; and the shirring effect, which is due to head movement. The fitness value of each candidate is measured based on its projection on the eigen-faces. After a number of iterations, all the face candidates with a high fitness value are selected for further verification. At this stage, the face symmetry is measured and the existence of the different facial features is verified for each face candidate.
Digital Image Processing
Digital image processing is the use of a digital computer to process digital images through an algorithm. As a subcategory or field of digital signal processing, digital image processing has many advantages over analog image processing. It allows a much wider range of algorithms to be applied to the input data and can avoid problems such as the build-up of noise and distortion during processing. Since images are defined over two dimensions (perhaps more) digital image processing may be modeled in the form of multidimensional systems. The generation and development of digital image processing are mainly affected by three factors: first, the development of computers; second, the development of mathematics (especially the creation and improvement of discrete mathematics theory); third, the demand for a wide range of applications in environment, agriculture, military, industry and medical science has increased.
An important development in digital image compression technology was the discrete cosine transform (DCT), a lossy compression technique first proposed by Nasir Ahmed in 1972. DCT compression became the basis for JPEG, which was introduced by the Joint Photographic Experts Group in 1992. JPEG compresses images down to much smaller file sizes, and has become the most widely used image file format on the Internet. Its highly efficient DCT compression algorithm was largely responsible for the wide proliferation of digital images and digital photos,with several billion JPEG images produced every day as of 2015.

**Face Dectection**


Face detection is a computer technology being used in a variety of applications that identifies human faces in digital images. Face detection also refers to the psychological process by which humans locate and attend to faces in a visual scene.
Face detection can be regarded as a specific case of object-class detection. In object-class detection, the task is to find the locations and sizes of all objects in an image that belong to a given class. Examples include upper torsos, pedestrians, and cars.
Face-detection algorithms focus on the detection of frontal human faces. It is analogous to image detection in which the image of a person is matched bit by bit. Image matches with the image stores in database. Any facial feature changes in the database will invalidate the matching process
A reliable face-detection approach based on the genetic algorithm and the eigen-face technique:
Firstly, the possible human eye regions are detected by testing all the valley regions in the gray-level image. Then the genetic algorithm is used to generate all the possible face regions which include the eyebrows, the iris, the nostril and the mouth corners.
Each possible face candidate is normalized to reduce both the lighting effect, which is caused by uneven illumination; and the shirring effect, which is due to head movement. The fitness value of each candidate is measured based on its projection on the eigen-faces. After a number of iterations, all the face candidates with a high fitness value are selected for further verification. At this stage, the face symmetry is measured and the existence of the different facial features is verified for each face candidate.


**Digital Image Processing**


Digital image processing is the use of a digital computer to process digital images through an algorithm. As a subcategory or field of digital signal processing, digital image processing has many advantages over analog image processing. It allows a much wider range of algorithms to be applied to the input data and can avoid problems such as the build-up of noise and distortion during processing. Since images are defined over two dimensions (perhaps more) digital image processing may be modeled in the form of multidimensional systems. The generation and development of digital image processing are mainly affected by three factors: first, the development of computers; second, the development of mathematics (especially the creation and improvement of discrete mathematics theory); third, the demand for a wide range of applications in environment, agriculture, military, industry and medical science has increased.
An important development in digital image compression technology was the discrete cosine transform (DCT), a lossy compression technique first proposed by Nasir Ahmed in 1972. DCT compression became the basis for JPEG, which was introduced by the Joint Photographic Experts Group in 1992. JPEG compresses images down to much smaller file sizes, and has become the most widely used image file format on the Internet. Its highly efficient DCT compression algorithm was largely responsible for the wide proliferation of digital images and digital photos,with several billion JPEG images produced every day as of 2015.


**Testing & Findings**
 ![Screenshot (58)](https://user-images.githubusercontent.com/94763917/158051698-86eb4f34-7664-4dd7-850c-596018e4ac6c.png)


**Applications**
![Screenshot (60)](https://user-images.githubusercontent.com/94763917/158051571-e06404ea-176b-4b24-b1c6-02d8d763e05b.png)


**Conclusion**



The result obtained from the proposed model gives the estimated  emotion prediction of the subject based on the data sets and  information. The resulting output can be used in many situations, the mental disorders and  stress level is estimated and therefore in case of "critical sentiments the peers and family members of the subject can take actions to encourage, motivate and uplift the emotional state of the subject thus resulting in the harmony and peace of mind of the subject. Therefore such emotion  analysis models are a  requirement for shaping the society into a happening place.

**Future Scope**


Companies across the world are harnessing the power of emotional intelligence to improve their business processes. What we have seen here is just a snippet of the true potential of emotion analytics. The future of sentiment analysis is going to continue to dig deeper, far past the surface of the number of likes, comments and shares, and aim to reach, and truly understand, the significance of social media interactions and what they tell us about the consumers behind the screens.


https://www.dropbox.com/s/raw/nilt43hyl1dx82k/dataset.zip
