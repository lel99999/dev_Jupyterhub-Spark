# dev_Jupyterhub-Spark
Jupyterhub &amp; Spark2 (HDP 2.6) Integration Notes

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
