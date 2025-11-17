# utl-creating-ms-access-mat-link-files-and-converting-can-mf4-filse-to-csv
creating ms access mat link files and converting can mf4 files to csv
    %let pgm=utl-creating-ms-access-mat-link-files-and-converting-can-mf4-filse-to-csv;

    %stop_submission;

    creating ms access mat link files and converting can mf4 files to csv;

    too long to post here,see github


    https://github.com/rogerjdeangelis/utl-creating-ms-access-mat-link-files-and-converting-can-mf4-filse-to-csv


    If you are serious about CAN MF4 analysis, you should install Python asammf packag,
    also check caseelectronics.

    community.altair.com/
    https://community.altair.com/discussion/61467

    CONTENTS

      1 Convert  mf4 fole to a csv
        see  d:/mf4/0000012-64BB8F50-CAN.csv for conversion of c:/mf4/0000012-64BB8F50.mf4
        also in this repo

      2  Create MS Access MAT file
         MAT files are just links to Access?
         I don't think it is possible to create them programatically.

    *                                  _                __ _  _     _       *                                 _                __ _  _     _
    / |   ___ ___  _ ____   _____ _ __| |_   _ __ ___  / _| || |   | |_ ___    ___ _____   __
    | |  / __/ _ \| `_ \ \ / / _ \ `__| __| | `_ ` _ \| |_| || |_  | __/ _ \  / __/ __\ \ / /
    | | | (_| (_) | | | \ V /  __/ |  | |_  | | | | | |  _|__   _| | || (_) || (__\__ \\ V /
    |_|  \___\___/|_| |_|\_/ \___|_|   \__| |_| |_| |_|_|    |_|    \__\___/  \___|___/ \_/

    */

    I could not get the python package asammdf to work, it wanted several oldversions of python and numpy?

    Perplexity said  'caseelectronics wsa a safe site?'

    Go to

    https://canlogger.csselectronics.com/tools-docs/converters_mf4/converters/csv/index.html#download

    Highlight 'mdf to csv converter'

      Then
        download - example data
        download > download (to get mde\f2csv.exe)

    save
            00000012-64BB8F50.mf4  in d:/mf4/00000012-64BB8F50.mf4
      and
            mdf2csv in d:/mf4/mdf2csv.exe

    This command will convert the mf4 to a csv

    Open cmd.exe and enter the command below

    d:/mf4/mdf2csv.exe -i "d:\mdf\00000012-64BB8F50.mf4"

    d:\mdf\00000012-64BB8F50-CAN.csy will be created

    d:\mdf\00000012-64BB8F50.mf4


    TimestampEpoch;BusChannel;ID;IDE;DLC;DataLength;Dir;EDL;BRS;ESI;RTR;DataBytes
    1689951599.925001;9;067;0;8;8;0;0;0;0;0;E19462F0C9F66E01
    1689951599.925002;9;068;0;4;4;0;0;0;0;0;F3120A00
    1689951599.925003;9;069;0;8;8;0;0;0;0;0;6F4D40DD0810DF00
    1689951599.925004;9;06B;0;5;5;0;0;0;0;0;4D8C200900
    1689951599.926300;9;06A;0;3;3;0;0;0;0;0;474400
    1689951599.926400;9;06F;0;8;8;0;0;0;0;0;F7CB0F4900021080
    1689951600.126650;9;065;0;1;1;0;0;0;0;0;6C
    1689951600.126651;9;066;0;6;6;0;0;0;0;0;03FF26591A1A
    1689951600.126652;9;067;0;8;8;0;0;0;0;0;07956210C5F66E01
    1689951600.126653;9;068;0;4;4;0;0;0;0;0;EF120A00
    1689951600.126654;9;069;0;8;8;0;0;0;0;0;734D00DD08F8DE00
    1689951600.126950;9;005;0;8;8;0;0;0;0;0;60AEAE065FAEAE06
    1689951600.126951;9;06B;0;5;5;0;0;0;0;0;1F8C000900

    /*___                        _                         _     _ _       _
    |___ \    ___ _ __ ___  __ _| |_ ___   _ __ ___   __ _| |_  | (_)_ __ | | __
      __) |  / __| `__/ _ \/ _` | __/ _ \ | `_ ` _ \ / _` | __| | | | `_ \| |/ /
     / __/  | (__| | |  __/ (_| | ||  __/ | | | | | | (_| | |_  | | | | | |   <
    |_____|  \___|_|  \___|\__,_|\__\___| |_| |_| |_|\__,_|\__| |_|_|_| |_|_|\_\

    */


    Creating and editing MS Access  MAT links

     Perplexity

    https://www.perplexity.ai/search/how-do-i-create-a-mat-link-to-o1LgGw7vTBGQ6pIg4gHt3A

    To create a linked table (MAT link) to an Access table, use Microsoft Access's built-in features
    to connect your database to another Access file or table. This process allows your database to
    reference data stored in a different .mdb or .accdb file so that you can view and interact with
    its contents as if they were in your current database.[2][3][6]

    ### Steps to Create a Linked Table in Access

    - Open your Access database where you want the link to appear.[3][2]
    - Go to the “External Data” tab on the Ribbon.[6][2]
    - Click “Access” in the Import & Link group.
    - In the dialog, choose “Link to the data source by creating a linked table,” then click “OK”.[3][6]
    - Browse to the Access database file that contains the table you want to link to, select the file, and confirm.
    - Select the tables you want to link in the "Link Tables" dialog, then click "OK." The tables will appear in
    your Database with a small arrow icon indicating they are linked.[4][2][3]
    - Open and use the linked table like a native one; changes are reflected directly in the source table.[5][2][4]

    ### Managing and Refreshing Links

    - Use the “Linked Table Manager” found under Database Tools to refresh or update paths to linked tables if the source location changes.[7][5]
    - Linked tables cannot have their structure (fields) altered from the destination database; updates must be made in the source database.[5]

    This method lets you integrate and work with external Access data seamlessly in your projects, without manual importing or duplication.[4][7][3]

    [1](https://www.youtube.com/watch?v=L3IVZpFGKqc)
    [2](https://sourcedaddy.com/ms-access/linking-access-tables.html)
    [3](https://support.microsoft.com/en-us/office/import-or-link-to-data-in-another-access-database-095ab408-89c7-45b3-aac2-58036e45fcf6)
    [4](https://theitservice.co.uk/microsoft-access-how-to-create-linked-tables/)
    [5](https://www.youtube.com/watch?v=7s2-LhlBfZY)
    [6](https://www.youtube.com/watch?v=xhOoTs0aCbY)
    [7](https://support.microsoft.com/en-us/office/manage-linked-tables-1d9346d6-953d-4f85-a9ce-4caec2262797)
    [8](https://stackoverflow.com/questions/850596/how-do-i-chain-linked-tables-in-access)
    [9](https://www.access-programmers.co.uk/forums/threads/how-to-link-the-fields-of-my-tables-in-to-a-master-table.313715/)
    [10](https://learn.microsoft.com/en-us/answers/questions/5332555/how-to-link-form-to-table?forum=msoffice-all)

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

    */
