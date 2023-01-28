# layout2

<!DOCTYPE html>
<html>

<head>
    <title> layout </title>
    <style type="text/css">
        div {
            font-size: 20px;
            font-weight: bold;
        }

        #R1 {
            background-color: grey;
            height: 33px;
            width: 100%;
            padding-top: 20px;
            margin-top: 10px;
            text-align: center;

        }

        #R1D1 {
            /* float: left; */
            padding-left: 2%;
        }

        /* #R1D2 {
            float: right;
            padding-right: 2%;
        } */

        #R2,
        #R5 {
            background-color: grey;
            height: 33px;
            width: 98%;
            padding-top: 7px;
            padding-left: 2%;
            margin-top: 10px;
            text-align: center;
        }

        #R3 {
            background-color: grey;
            height: 90px;
            width: 100%;
            padding-top: 60px;
            margin-top: 10px;
            text-align: center;
        }

        #R4 {
            height: 600px;
            width: 100%;
            margin-top: 10px;
        }

        #R4C1 {
            width: 23%;
            margin-right: 2%;
        }

        #R4C2 {
            width: 25%;
        }

        #R4C3 {
            width: 23%;
            margin-left: 2%;

        }

        #R4C4 {
            width: 23%;
            margin-left: 2%;
        }

        #R4 div {
            background-color: grey;
            float: left;
            height: 320px;
            padding-top: 280px;
            text-align: center;
        }
    </style>
</head>

<body>
    <div>
        <div id="R1">
            <div id="R1D1">
                LOGO
            </div>

            <!-- <div id="R1D2">
                DESING
            </div> -->

        </div>
        <div id="R2">
            NAVIGATION
        </div>
        <div id="R3">
            BANNER
        </div>
        <div id="R4">
            <div id="R4C1">
                BOX 1
            </div>
            <div id="R4C2">
                BOX 2
            </div>
            <div id="R4C3">
                BOX 3
            </div>
            <div id="R4C4">
                BOX 4
            </div>
        </div>
        <div id="R5">
            FOOTER
        </div>
    </div>
    </div>
</body>

</html>
