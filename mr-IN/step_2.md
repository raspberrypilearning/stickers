## रंगीबेरंगी कोडिंग स्टिकर

ग्रेडियंट म्हणजे एका रंगापासून दुसर्‍या रंगात हळू हळू बदल. ग्रेडियंट्स आकर्षक प्रभाव तयार करण्यासाठी वापरले जाऊ शकतात. आपण ते आपल्या वेब पेज वापरू शकणारे स्टिकर्स तयार करण्यासाठी वापरणार आहात.

+ हे trinket उघडा: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>.
    
    प्रकल्प असा दिसायला हवा:
    
    ![screenshot](images/stickers-starter.png)

+ चला एक 'I <3 Coding' बनवूयाg' sticker.
    
    स्टाइल करण्यासाठी `<div>` सोबत `sticker` क्लास आणि `coding` id चा वापर करा:
    
    ![screenshot](images/stickers-coding-error.png)

+ हम्म आपल्या लक्षात आले की आपणा कडुन त्रुट झाली आहे? कारण HTML मध्ये एक विशेष वर्ण आहे. '<' ऐवजी आपणास `&lt;` हा विशेष कोड वापरण्याची आवश्यकता आहे.
    
    `&lt;` वापरण्यासाठी आपला कोड अद्यतनित करा जेणेकरून त्रुटी दूर होईल.
    
    ![screenshot](images/stickers-coding-fixed.png)
    
    `<br>` हा टॅग नवीन ओळ देतो.

+ आता स्टिकरला मनोरंजक बनवू या.
    
    फाईल `style.css` वर स्विच करा. आपल्याला ते `.sticker` क्लास दिसेल आपल्यासाठी हे क्लास प्रदान केला गेला आहे. हे पेजवरील स्टिकर्सना लेआउट करेल आणि त्यांची सामग्री केंद्रित करेल.
    
    लक्षात ठेवा आपण आपल्या स्टिकरला `coding` आयडी जोडला आहे. `style.css` च्या तळाशी मजकूर स्टाईल करण्यासाठी खालील कोड जोडा:
    
    ![screenshot](images/stickers-coding-font.png)

+ आता आपण स्टिकरच्या पार्श्वभूमीसाठी ग्रेडियंट जोडू शकता. एक लिनियर ग्रेडियंट एका सरळ रेषेत एका रंगापासून दुसर्‍या रंगात बदलतो.
    
    हा ग्रेडियंट तळाशी लाल पासून वरून किरमिजी (magenta) रंगात बदलेल. आपल्या `coding` शैलीमध्ये ग्रेडियंट कोड जोडा:
    
    ![screenshot](images/stickers-coding-gradient.png)

+ पॅडिंग (padding) आणि गोलाकार कोन(rounded corners) जोडून आपण निकालात सुधारणा करू शकता.
    
    हायलाइट केलेला कोड जोडा:
    
    ![screenshot](images/stickers-coding-padding.png)
    
    `padding` शैली मध्ये डावीकडे आणि उजवीकडे 30px आणी, वर आणि खाली 50px ची पॅडिंग जोडली जाते.