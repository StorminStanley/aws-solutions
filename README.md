# StackStorm AWS solutions repo

To run the create_instance action try a command like

st2 run aws-solutions.create_instance cidr_block="192.168.55.0/24" hostname="z" ami_id="ami-5189a661" key_name="my_key" dns_zone="x.y.net"
