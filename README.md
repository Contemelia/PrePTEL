# <p> PrePTEL - Simulating Swayam's NPTEL Exam Environment </p>

<p>
PrePTEL is a quiz application that closely simulates the examination environment of NPTEL (National Programme on Technology Enhanced Learning) by Swayam. While primarily designed for NPTEL, PrePTEL is adaptable to other structured learning materials with a similar format. With a user-friendly command-line interface, PrePTEL becomes your trusted companion for an effective and comprehensive exam preparation experience.
</p>

<br>

## <p> <b> Section 1: </b> Guide to Installation and Proper Usage
<p>
You have the option to either download the '.exe' version or retrieve the '.py' script and execute it. Upon completion of the download, follow these steps to set up the environment:
<p>
<ul>
    <li> <b> Step 1: </b> Make sure you also have the folder titled `Materials` in the same directory as your script. This is to be considered regardles of whether you use the executable version or the script version. This folder will contain the `.xlsx` file comprising of the questions. </li>
    <li> <b> Step 2: </b> The script, will automatically attempt install the required modules. In case of a failure, make sure to check your connection and try again.</li>
</ul>
</p>
<b> NOTE: </b> You may be required to turn of your Windows operating system's security, as it may prevent the file from getting downloaded. This may be a direct cause of the lack of certificates for the script. You may ignore any further warning from your system's firewall and proceed with the download.
</p>

<br>

## <p> <b> Section 2: </b> Usage of other Materials
<p>
You have the freedom to choose between different materials, or even you your own. Only make sure that the material yoou use follows the structure specified below:
<p>
<br>
While you create the material (the question bank), ensure that it follows the format shown below. The first question of the material must start from the first row of the excel sheet (don't include any headings). The correct answer you mention in the 6th column must be present in one of the four options present in the columns 2 - 5.
<br>
<br>
<table>
    <tr>
        <td> The question </td>
        <td> First option </td>
        <td> Second option </td>
        <td> Third option </td>
        <td> Fourth option </td>
        <td> The correct answer </td>
    </tr>
</table>
<br>
<br>
If you have followed all this instructions, your material should look similar to the sample shown below:
<br>
<br>
<table>
    <tr>
        <td> questionOne </td>
        <td> oneOptionA </td>
        <td> oneOptionB </td>
        <td> oneOptionC </td>
        <td> oneOptionD </td>
        <td> oneOptionA </td>
    </tr>
    <tr>
        <td> questionTwo </td>
        <td> twoOptionA </td>
        <td> twoOptionB </td>
        <td> twoOptionC </td>
        <td> twoOptionD </td>
        <td> twoOptionB </td>
    </tr>
    <tr>
        <td> questionThree </td>
        <td> threeOptionA </td>
        <td> threeOptionB </td>
        <td> threeOptionC </td>
        <td> threeOptionD </td>
        <td> threeOptionC </td>
    </tr>
    <tr>
        <td> questionFour </td>
        <td> fourOptionA </td>
        <td> fourOptionB </td>
        <td> fourOptionC </td>
        <td> fourOptionD </td>
        <td> fourOptionD </td>
    </tr>
    <tr>
        <td> questionFive </td>
        <td> fiveOptionA </td>
        <td> fiveOptionB </td>
        <td> fiveOptionC </td>
        <td> fiveOptionD </td>
        <td> fiveOptionA </td>
    </tr>
</table>
<br>
<br>
<b> NOTE: </b> The excel file you've just created must be present in the `Materials` folder. The name of this excel file will be reflected as the name of the course. Follow the structure shown above to avoid any errors.
<br>
<br>
<b> NOTE: </b> The questions and options are presented in a jumbled up manner to increase the complexity of the exam.
</p>
