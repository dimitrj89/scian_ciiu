# SCIAN-CIIU
A library to search the corresponding mexican scian/ciiu given an input parameter

## How to use
_After installing the package use following import:_ <br>

**from scian_ciiu import scian_id_to_ciiu, scian_string_to_ciiu, ciiu_id_to_scian, ciiu_string_to_scian**

_Then use following commands:_

**scian_id = "111219"<br>**
**result_dict = scian_id_to_ciiu(scian_id)<br>**

_Or:_

**scian_string = "Cultivo"<br>**
**result_dict = scian_string_to_ciiu(scian_string)<br>**

_Or:_

**ciiu_id = "0111"<br>**
**result_dict = ciiu_id_to_scian(ciiu_id)<br>**

_Or:_

**ciiu_string = "Cultivo"<br>**
**result_dict = ciiu_string_to_scian(ciiu_string)<br>**