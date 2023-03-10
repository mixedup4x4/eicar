I needed a place to host the eicar test files so created this repository

From the EICAR.org website:
https://www.eicar.org/download-anti-malware-testfile/


ANTI MALWARE TESTFILE
Intended use
Additional notes:

This file used to be named ducklin.htm or ducklin-html.htm or similar based on its original author Paul Ducklin and was made in cooperation with CARO.
The definition of the file has been refined 1 May 2003 by Eddy Willems in cooperation with all vendors.
The content of this documentation (title-only) was adapted 1 September 2006 to add verification of the activity of anti-malware or anti-spyware products. It was decided not to change the file itself for backward-compatibility reasons.
Who needs the Anti-Malware Testfile

(read the complete text, it contains important information)
Version of 7 September 2006 

If you are active in the anti-virus research field, then you will regularly receive requests for virus samples. Some requests are easy to deal with: they come from fellow-researchers whom you know well, and whom you trust. Using strong encryption, you can send them what they have asked for by almost any medium (including across the Internet) without any real risk.

Other requests come from people you have never heard from before. There are relatively few laws (though some countries do have them) preventing the secure exchange of viruses between consenting individuals, though it is clearly irresponsible for you simply to make viruses available to anyone who asks. Your best response to a request from an unknown person is simply to decline politely.

A third set of requests come from exactly the people you might think would be least likely to want viruses „users of anti-virus software“. They want some way of checking that they have deployed their software correctly, or of deliberately generating a „virus incident in order to test their corporate procedures, or of showing others in the organisation what they would see if they were hit by a virus“.

Reasons for testing anti-virus software

Obviously, there is considerable intellectual justification for testing anti-virus software against real viruses. If you are an anti-virus vendor, then you do this (or should do it!) before every release of your product, in order to ensure that it really works. However, you do not (or should not!) perform your tests in a „real“ environment. You use (or should use!) a secure, controlled and independent laboratory environment within which your virus collection is maintained.

Using real viruses for testing in the real world is rather like setting fire to the dustbin in your office to see whether the smoke detector is working. Such a test will give meaningful results, but with unappealing, unacceptable risks.

Since it is unacceptable for you to send out real viruses for test or demonstration purposes, you need a file that can safely be passed around and which is obviously non-viral, but which your anti-virus software will react to as if it were a virus.

If your test file is a program, then it should also produce sensible results if it is executed. Also, because you probably want to avoid shipping a pseudo-viral file along with your anti-virus product, your test file should be short and simple, so that your customers can easily create copies of it for themselves.

The good news is that such a test file already exists. A number of anti-virus researchers have already worked together to produce a file that their (and many other) products „detect“ as if it were a virus.

Agreeing on one file for such purposes simplifies matters for users: in the past, most vendors had their own pseudo-viral test files which their product would react to, but which other products would ignore.

The Anti-Malware Testfile

This test file has been provided to EICAR for distribution as the „EICAR Standard Anti-Virus Test File“, and it satisfies all the criteria listed above. It is safe to pass around, because it is not a virus, and does not include any fragments of viral code. Most products react to it as if it were a virus (though they typically report it with an obvious name, such as „EICAR-AV-Test“).

The file is a legitimate DOS program, and produces sensible results when run (it prints the message „EICAR-STANDARD-ANTIVIRUS-TEST-FILE!“).

It is also short and simple – in fact, it consists entirely of printable ASCII characters, so that it can easily be created with a regular text editor. Any anti-virus product that supports the EICAR test file should detect it in any file providing that the file starts with the following 68 characters, and is exactly 68 bytes long:

X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*

The first 68 characters is the known string. It may be optionally appended by any combination of whitespace characters with the total file length not exceeding 128 characters. The only whitespace characters allowed are the space character, tab, LF, CR, CTRL-Z. To keep things simple the file uses only upper case letters, digits and punctuation marks, and does not include spaces. The only thing to watch out for when typing in the test file is that the third character is the capital letter „O“, not the digit zero.

You are encouraged to make use of the EICAR test file. If you are aware of people who are looking for real viruses „for test purposes“, bring the test file to their attention. If you are aware of people who are discussing the possibility of an industry-standard test file, tell them about www.eicar.org, and point them at this article.

Download Anti Malware Testfile
In order to facilitate various scenarios, we provide 4 files for download. The first, eicar.com, contains the ASCII string as described above. The second file, eicar.com.txt, is a copy of this file with a different filename. Some readers reported problems when downloading the first file, which can be circumvented when using the second version. Just download and rename the file to „eicar.com“. That will do the trick. The third version contains the test file inside a zip archive. A good anti-virus scanner will spot a ‚virus‘ inside an archive. The last version is a zip archive containing the third file. This file can be used to see whether the virus scanner checks archives more than only one level deep.

Once downloaded run your AV scanner. It should detect at least the file „eicar.com“. Good scanners will detect the ‚virus‘ in the single zip archive and may be even in the double zip archive. Once detected the scanner might not allow you any access to the file(s) anymore. You might not even be allowed by the scanner to delete these files. This is caused by the scanner which puts the file into quarantaine. The test file will be treated just like any other real virus infected file. Read the user’s manual of your AV scanner what to do or contact the vendor/manufacturer of your AV scanner.

IMPORTANT NOTE
EICAR cannot be held responsible when these files or your AV scanner in combination with these files cause any damage to your computer. YOU DOWNLOAD THESE FILES AT YOUR OWN RISK.  Download these files only if you are sufficiently secure in the usage of your AV scanner. EICAR cannot and will not provide any help to remove these files from your computer. Please contact the manufacturer/vendor of your AV scanner to seek such help.

How to delete the test file from your PC

We understand (from the many emails we receive) that it might be difficult for you to delete the test file from your PC. After all, your scanner believes it is a virus infected file and does not allow you to access it anymore. At this point we must refer to our standard answer concerning support for the test file. We are sorry to tell you that EICAR cannot and will not provide AV scanner specific support. The best source to get such information from is the vendor of the tool which you purchased.

Please contact the support people of your vendor. They have the required expertise to help you in the usage of the tool. Needless to say that you should have read the user’s manual first before contacting them.
