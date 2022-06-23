# resumeLatest
contains latest resume
SOURCE CODE:

<?xml version="1.0" encoding="UTF-8"?>
<student xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:noNamespaceSchemaLocation="student.xsd">
<detail>
<name>Harshit</name>
<course>btech</course>
<email>harshit@gmail.com</email>
<branch>CSE</branch>
<mobile>8532856800</mobile>
</detail>
</student>
SCHEMA:-
<?xml version="1.0" encoding="UTF-8"?>
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
<xs:element name="student">
<xs:complexType>
<xs:sequence>
<xs:element name="detail">
<xs:complexType>
<xs:sequence>
<xs:element name="name" type="xs:string"></xs:element>
<xs:element name="course" type="xs:string"></xs:element>
<xs:element name="email" type="xs:string"></xs:element>
<xs:element name="branch" type="xs:string"></xs:element>
<xs:element name="mobile" type="xs:int"></xs:element>
</xs:sequence>
</xs:complexType>
</xs:element>
</xs:sequence>
</xs:complexType>
</xs:element>
