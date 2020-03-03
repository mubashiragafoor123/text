use strict;
 
my @a;
my @b;
my @c;
my $r;
my $k;
my $c;
my $i;
my $j;
print "enter the no of rows of matrix";
$r = <stdin>;
print "\n";
print "enter the no of columns of matrix";
$c= <stdin>;
print "\n";
print "\n";
print "enter the elements of first matrix";
for($i=0;$i<$r;$i++)
{
  for($j=0;$j<$c;$j++)
  {
    $a[$i][$j]=<stdin>;
  }
}
 
print "\n";
 
  
print "enter the elements of second matrix";
for($i=0;$i<$r;$i++)
{
  for($j=0;$j<$c;$j++)
  {
    $b[$i][$j] = <stdin>;
  }
}
print "\n";  
 
for($i=0;$i<$r;$i++)
{
  for($j=0;$j<$c;$j++)
  {
    $c[$i][$j]=0;
    for($k=0;$k<$c;$k++)
    {
       $c[$i][$j]+=$a[$i][$k]*$b[$k][$j];  
    }
  }
}
 
 
print "\n";
print "the first matrix is:";
print "\n";
for($i=0;$i<$r;$i++)
{
  for($j=0;$j<$c;$j++)
  {
    print $a[$i][$j];
    print "\t";
  }
  print "\n";
}
 
print "\n";
print "the second matrix is:";
print "\n";
for($i=0;$i<$r;$i++)
{
  for($j=0;$j<$c;$j++)
  {
    print $b[$i][$j];
    print "\t";
  }
  print "\n";
}
 
print "\n";
print"the product of the matrix is";
 
print "\n";
 
for($i=0;$i<$r;$i++)
{
  for($j=0;$j<$c;$j++)
  {
    print $c[$i][$j];
    print "\t";
  }
  print "\n";
}
 
print "\n";
