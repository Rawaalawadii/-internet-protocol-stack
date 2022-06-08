# -internet-protocol-stack



 مفهوم internet protocol stack 



| application layer |
| ----------------- |
| transport layer   |
| network layer     |
| link layer        |
| physical layer    |

في طبقة application layer  هي مسؤولة عن الاتصال بين التطبيقات التي تعمل على نظامين طرفيين مختلفين .ونستعمل فيapplication layer راح نستعمل البرتوكول HTTPS

- Hypertext Transfer Protocol (HTTP): for transferring HTML web documents. 

وهي تتضمن صفحة web. 

في حال تم الارسال transport layer ستون هي المسؤولة عن جمع رسالة application layer وترسلها إلى  network layer وبعدها راح تكون هنا عندنا communicated مع network. 
البروتوكولات المستعملة : 

- Transmission Control Protocol (TCP)
- User Datagram Protocol (UDP)

اما بالحديث عن network layer ستكون طبقة network هي  طبقة الشبكة المسؤولة عن نقل البيانات من نظام إلى آخر على الشبكة. وتقوم بتمرير segment و destination address. 
وهي المسؤولة عن Routing. 

في حال تم نقل packet من خلال الانترنت بالطبع توجد عدة اجهزة وسيطة بينهما مثل :routers, switches تقف بين systems و network وهي link layer : وبالطبع هي المسؤولة عن communication بين device واخر .

واخيرا طبقة physical layer  وهي المسؤولة عن تقسيم data frame إلى bits وتحولة إلى نموذج يتم نقلة عبر  physical communication line  مثل موجات الراديو (fiber-optic ). 



ماهو TCP ؟ 

تتمثل وظيفة بروتوكول التحكم بالإرسال TCP في التحكم بنقل البيانات بحيث يمكن الاعتماد عليها. فعلى شبكات مثل الإنترنت، يتم إرسال البيانات في حزم والتي هي وحدات من البيانات التي يتم إرسالها بشكل مستقل على الشبكة، ويتم إعادة تجميعها بمجرد وصولها إلى الوجهة لإعادة البيانات الأصلية.


![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1640980865700_Screen+Shot+1443-05-27+at+10.59.24+PM.png)


بروتوكول TCP/IP هو بروتوكول قياسي يتضمن بداخله عدد من البروتوكولات التي تحدد طريقة معالجة بيانات الاتصالات:


| للاتصال بين التطبيقات.    | TCP  |
| ------------------------- | ---- |
| اتصال بسيط بين التطبيقات. | UDP  |
| للاتصال بين أجهزة         | IP   |
| للعناوين الديناميكية.     | DHCP |

أما بروتوكول MQTT  ، هو برتوكول راح نستعمله في انترنت الاشياء ، يختلف عن البروتوكالات بأنه عبارة عن subscribe و publish مو request و Response.  
وهو : يوفر طريقة قابلة للتطوير وموثوقة لتوصيل الأجهزة عبر الإنترنت واليوم الشركات التقنيه تستعمل MQTT لتوصيل ملايين الأجهزة بالإنترنت.



![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1641025548719_Screen+Shot+1443-05-28+at+11.25.02+AM.png)




Packet-switching versus circuit-switching



| circuit-switching                                            | Packet-switching                              |
| ------------------------------------------------------------ | --------------------------------------------- |
| End-end resources reserved for “call”<br>call setup required | each end-end data stream divided into packets |

بعض الاخطار التي قد تواجهنا في الامن Security 
| virus: self-replicating infection by receiving/executing object (e.g., e-mail attachment)<br><br>worm: self-replicating infection by passively receiving object that gets itself executed | malware           |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| Denial of Service (DoS): attackers make resources (server, bandwidth) unavailable to legitimate traffic by overwhelming resource with bogus traffic                                       | DOSAttack         |
| Packet sniffing is the practice of gathering, collecting, and logging some or all packets that pass through a computer network.                                                           | ”packet “sniffing |


لماذا نستعمل سيسكو باكت تريسر ؟ 
سيسكو باكت تريسر هو برنامج مجاني تم إطلاقه من شركة سيسكو يسمح للمستخدمين بتصميم ومحاكاة شبكات وأنظمة انترنت الأشياء باستخدام الأكواد البرمجية مع واجهة مستخدم تدعم خاصية السحب والإفلات. 

وبالاجابة على سؤال لمذا سيسكو باكت تريسر ؟
1_سهولة الاستخدام و التطبيق
2_تقارب الرسومات المستخدمة في المحاكاة مع
أشكالها في الواقع.
3_تحتوي المنصة على مكتبة غنية من الأيقونات للمحاكاة.
4_تحتوي المنصة على مكتبة غنية من الأمثلة البرمجية.


مشروع الشبكات 

ربط شبكتين مع بعض من خلال الراوتر 

![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1641026209402_Screen+Shot+1443-05-28+at+11.35.43+AM.png)


١-

![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1641026241544_Screen+Shot+1443-05-28+at+11.36.57+AM.png)


٢- 

![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1641026306304_Screen+Shot+1443-05-28+at+11.37.28+AM.png)


٣- 


![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1641026420530_Screen+Shot+1443-05-28+at+11.38.39+AM.png)


٤- 


![](https://paper-attachments.dropbox.com/s_51D4B74E1E15B4A8DD2A824E39329518431ACBC50C4720496AE72BA41299FC5E_1641026564777_Screen+Shot+1443-05-28+at+11.41.39+AM.png)


في الخطوة الاولى : pc نختار 
في الخطوة الثانية : 2 step3

    cross-over cable نختار
    eathernet ونوصل في منفذ

وفي الخطوة الثالثة :

    ip ونعطیھ ip config ثم desktop ثم pc نختار
    او مثلا 192.168.0.1 255.255.255.0 dhcp اما
    والثاني 192.168.0.2
    

وفي الخطوة الرابعة : 

    command prompt الثاني ونكتب الامر التالي في desktop ندخل في
    ping 192.168.0.1

وفي الخطوة الخامسة : 

    straight through ونستبدلھ ب cross cable نزیل
    ونوصلھ بین الجھازین switch نسحب
    ping نرسل

وفي الخطوة السادسة : 

    مع الجھازین switchننسخ ال
    مختلفة ip address نعطي

وفي الخطوة السابعة : 

    1841  : router نختار

وفي الخطوة التاسعة : 

    نوصلھ بالسویتشین 

 ومن ثم default gateway نغیر للاجهزة جميعها. 
