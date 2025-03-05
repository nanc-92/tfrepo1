# tfrepo1
#working with tfcloud
resource "aws_vpc" "TFvpc1" {
    cidr_block = "10.199.0.0/16"
    tags = {
        Name = "from local to TFC VPC"
    }
}
