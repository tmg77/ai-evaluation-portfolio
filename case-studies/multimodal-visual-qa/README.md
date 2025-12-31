# Multimodal Visual QA (Synthetic Example)

## Task Type
Bounding box quality assurance for object detection in a crowded scene.

## QA Criteria
- Boundary tightness (no excessive background or cropping)
- Occlusion handling
- Label accuracy
- Consistency across similar objects
- Ambiguity identification and flagging

## Common Failure Modes
- Bounding boxes too loose or too tight
- Missed occluded object portions
- Inconsistent labeling of similar objects
- Ambiguous object class not flagged

## Evaluation Outcome
Annotations require revision due to inconsistent boundary placement
and failure to flag partially occluded objects as ambiguous.
