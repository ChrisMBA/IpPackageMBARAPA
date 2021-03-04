# IpPackageMBARAPA 

import IpPackage.*;
class IpTest {
        public static void main (String args[]) {
            IpPackage ip1 = IpPackage.getInstance(128,12,45,21);
            System.out.println("\nLa suite ...");
            System.out.println("\n Adresse IP 1 --> " + ip1.adresseReseau(ip1));
            System.out.println("L'Adresse r\u00e9seaux de IP 1 --> " + ip1.estMemeReseau(ip1));

            IpPackage ip2 = IpPackage.getInstance(128,12,45,22);
            System.out.println("\nLa suite ...");
            System.out.println("\n Adresse IP 2 --> " + ip2.ToString());
            System.out.println("IP 2 est elle dans le m\u00eame r\u00e9seaux que IP 1 --> " + ip2.estMemeReseau(ip1));
          
            IpPackage ip3 = IpPackage.getInstance(128,12,45,23);
            System.out.println("\nLa suite ...");
            System.out.println("\n Adresse IP 3 --> " + ip3.ToString());
            System.out.println("IP 3 est elle dans le m\u00eame r\u00e9seaux que IP 1 --> " + ip3.estMemeReseau(ip1));
            }
        }
