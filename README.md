
# Surveylance
Surveylance is a module to detect survey scams in the wild. 

## Abstract

Online surveys are a popular mechanism for performing market research in exchange for monetary compensation.
Unfortunately, fraudulent survey websites are similarly rising in
popularity among cyber-criminals as a means for executing social
engineering attacks. In addition to the sizable population of users
that participate in online surveys as a secondary revenue stream,
unsuspecting users who search the web for free content or access
codes to commercial software can also be exposed to survey scams.
This occurs through redirection to websites that ask the user to
complete a survey in order to receive the promised content or a
reward.

In this paper, we present SURVEYLANCE, the first system
that automatically identifies survey scams using machine learning
techniques. Our evaluation demonstrates that SURVEYLANCE
works well in practice by identifying 8,623 unique websites
involved in online survey attacks. We show that SURVEYLANCE is
suitable for assisting human analysts in survey scam detection at
scale. Our work also provides the first systematic analysis of the
survey scam ecosystem by investigating the capabilities of these
services, mapping all the parties involved in the ecosystem, and
quantifying the consequences to users that are exposed to these
services. Our analysis reveals that a large number of survey scams
are easily reachable through the Alexa top 30K websites, and
expose users to a wide range of security issues including identity
fraud, deceptive advertisements, potentially unwanted programs
(PUPs), malicious extensions, and malware.

## Extention
Surveylance uses a custom extension to automatically find fields and populate them with a pre-defined data. 

## Classification

 A code sample is provided on how the training and testing should work. 
```surveylance_classifier.py```basically receives the training/labeled dataset as well as the unlabeled set in csv formats, and print out the 
classification results for the unlabled set. Some samples are provides.

## Citation 
```
@inproceedings{kharraz2018surveylance,
  title={Surveylance: Automatically Detecting Online Survey Scams},
  author={Amin Kharraz and and William Robertson and Engin Kirda},
  booktitle={2018 IEEE Symposium on Security and Privacy (SP)},
  pages={70--86},
  year={2018},
  organization={IEEE}
}
```
## Contacts
Please send an email to ak(AT)cs(DOT)fiu(DOT)edu if you have any questions. 
