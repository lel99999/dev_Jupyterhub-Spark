# dev_Jupyterhub-Spark
Jupyterhub &amp; Spark2 (HDP 2.6) Integration Notes
#### Ports
- Hive2
  - 10000:10100
  
- SaprkUI
  - 4000:4050

#### Kerberos Integration
- [https://github.com/lel99999/jupyterhub-example-kerberos](https://github.com/lel99999/jupyterhub-example-kerberos) <br/> 

#### Add Scala Interpreter
- Spylon-kernel
  [https://github.com/vericast/spylon-kernel](https://github.com/vericast/spylon-kernel) <br/>
  - Install
    ```
    $sudo /opt/jupyterhub/bin/python3 -m pip install spylon-kernel
    ```
  - Kernelspec add
    ```
    $sudo /opt/jupyterhub/bin/python3 -m spylon-kernel install
    ```
    ![https://github.com/lel99999/dev_Jupyterhub-Spark/blob/main/spylon-kernel_kernelspec-01.PNG](https://github.com/lel99999/dev_Jupyterhub-Spark/blob/main/spylon-kernel_kernelspec-01.PNG) <br/>
    ![https://github.com/lel99999/dev_Jupyterhub-Spark/blob/main/spylon-kernel_kernelspec-02.PNG](https://github.com/lel99999/dev_Jupyterhub-Spark/blob/main/spylon-kernel_kernelspec-02.PNG) <br/>

#### Kerberos Related Information
- Yarn Kerberos Configuration
  [https://spark.apache.org/docs/2.4.3/running-on-yarn.html#yarn-specific-kerberos-configuration](https://spark.apache.org/docs/2.4.3/running-on-yarn.html#yarn-specific-kerberos-configuration) <br/>
