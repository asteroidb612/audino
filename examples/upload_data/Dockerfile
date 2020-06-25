FROM python:3
ADD upload_data.py /
ADD OSR_us_000_0010_8k.wav /

RUN pip install requests
CMD [ "python", "upload_data.py", "--username", "admin", "--is_marked_for_review", "True", "--audio_file", "OSR_us_000_0010_8k.wav", "--host", "0.0.0.0", "--port", "80", "--key", "7e8fb788b2324aaa9c75ce04ed9c083b", "--reference_transcription", "'The birch canoe slid on the smooth planks. Glue the sheet to the dark blue background. It's easy to tell the depth of a well. These days a chicken leg is a rare dish. Rice is often served in round bowls. The juice of lemons makes fine punch. The box was thrown beside the parked truck. The hogs were fed chopped corn and garbage. Four hours of steady work faced us. Large size in stockings is hard to sell.'" ]
