# Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`GPSP`](#class_g_p_s_p) | 
`struct `[`Command`](#struct_command) | 

# class `GPSP` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`GPSP`](#class_g_p_s_p_1a55a6a56692ef14e3677beb166e197750)`(Stream & serial)` | Construct a new [GPSP](#class_g_p_s_p) object, associating a Stream (Generally a Serial) to it.
`public void `[`defineCommand`](#class_g_p_s_p_1a1fe8b357a3d72435a811092decba8a18)`(`[`Command`](#struct_command)` command)` | Adds a new command to the List of Commands.
`public void `[`update`](#class_g_p_s_p_1a6a9d123d5d062302ad0dd476f893fdf2)`()` | Reads available data from Stream and stores it in a buffer until a NewLine or Semicolon is encountered. When this case is encountered call `[ProcessBuffer](#_1a5f37ce6cbb4485070fe547c3008eae3d)`, then clears the buffer.

## Members

#### `public  `[`GPSP`](#class_g_p_s_p_1a55a6a56692ef14e3677beb166e197750)`(Stream & serial)` 

Construct a new [GPSP](#class_g_p_s_p) object, associating a Stream (Generally a Serial) to it.

#### Parameters
* `serial`

#### `public void `[`defineCommand`](#class_g_p_s_p_1a1fe8b357a3d72435a811092decba8a18)`(`[`Command`](#struct_command)` command)` 

Adds a new command to the List of Commands.

#### Parameters
* `command` The new command

#### `public void `[`update`](#class_g_p_s_p_1a6a9d123d5d062302ad0dd476f893fdf2)`()` 

Reads available data from Stream and stores it in a buffer until a NewLine or Semicolon is encountered. When this case is encountered call `[ProcessBuffer](#_1a5f37ce6cbb4485070fe547c3008eae3d)`, then clears the buffer.

# struct `Command` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`Pointer`](#_g_p_s_p_8h_1a608c663b9f5067bb56222a0ace10f7c3)` `[`pointer`](#struct_command_1a52f87377703e996fc3157686e86d9302) | 
`public char * `[`name`](#struct_command_1aac61810b8e87055d1648ec142086eb0e) | 
`public char * `[`description`](#struct_command_1a4c2ce6d4fa23b96f04bfc5421b338f10) | 

## Members

#### `public `[`Pointer`](#_g_p_s_p_8h_1a608c663b9f5067bb56222a0ace10f7c3)` `[`pointer`](#struct_command_1a52f87377703e996fc3157686e86d9302) 

#### `public char * `[`name`](#struct_command_1aac61810b8e87055d1648ec142086eb0e) 

#### `public char * `[`description`](#struct_command_1a4c2ce6d4fa23b96f04bfc5421b338f10) 

Generated by [Moxygen](https://sourcey.com/moxygen)