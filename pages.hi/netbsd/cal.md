# cal

> एक कैलेंडर प्रदर्शित करें।
> अधिक जानकारी: <https://man.netbsd.org/cal.1>।

- वर्तमान महीने के लिए एक कैलेंडर प्रदर्शित करें:

`cal`

- एक विशेष वर्ष के लिए एक कैलेंडर प्रदर्शित करें:

`cal {{वर्ष}}`

- एक विशेष महीने और वर्ष के लिए एक कैलेंडर प्रदर्शित करें:

`cal {{महीना}} {{वर्ष}}`

- वर्तमान वर्ष के लिए संपूर्ण कैलेंडर प्रदर्शित करें [j]जूलियन दिन का उपयोग करते हुए (एक-आधारित, 1 जनवरी से क्रमांकित):

`cal -y -j`

- [h]आज को हाइलाइट करें और [3] महीनों को प्रदर्शित करें जो तारीख को कवर करते हैं:

`cal -h -3 {{महीना}} {{वर्ष}}`

- वर्तमान वर्ष के एक विशेष [m]महीने से [B]2 महीने पहले और [A]3 महीने बाद प्रदर्शित करें:

`cal -A 3 -B 2 {{महीना}}`

- निर्दिष्ट महीने से पहले और बाद में एक विशिष्ट संख्या के महीनों को प्रदर्शित करें ([C]संदर्भ):

`cal -C {{महीने}} {{महीना}}`

- सप्ताह के प्रारंभिक [d]दिन को निर्धारित करें (0: रविवार, 1: सोमवार, ..., 6: शनिवार):

`cal -d {{0..6}}`
