# Just copy and paste these into your POM. We made Jblas the default and commented out Netlib Blas and Jcublas...

# API
<dependency>
	<groupId>org.nd4j</groupId>
	<artifactId>nd4j-jblas</artifactId>
	<version>${nd4j.version}</version>
</dependency>

# Jblas
 <dependency>
   <groupId>org.nd4j</groupId>
   <artifactId>nd4j-jblas</artifactId>
   <version>${nd4j.version}</version> 
 </dependency>

# Netlib Blas:
# <dependency>
#   <groupId>org.nd4j</groupId>
#   <artifactId>nd4j-api</artifactId>
#   <version>${nd4j.version}</version>
# </dependency>

# Jcublas
# <dependency>
#	<groupId>org.nd4j</groupId>
#	<artifactId>nd4j-jcublas</artifactId>
#	<version>${nd4j.version}</version>
# </dependency>