#### terraform-may-vpc

```hcl
module "may" {
  source  = "LikeNo1Else/may/vpc"
  version = "2.0.0"
  vpc_cidr = ""
  subnet1_cidr = ""
  subnet2_cidr = "" 
  subnet3_cidr = ""
  vpc_name = "kaizen"

}